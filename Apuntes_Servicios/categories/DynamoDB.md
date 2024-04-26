## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/index.md)

### DynamoDB
[![AWS](https://img.shields.io/badge/DynamoDB-c08a44?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/DynamoDB.md)

#### 1. Almacenamiento NoSQL
- Datos almacenados en JSON
- En vez de "rows" o "tuplas" usa el concepto "items"
- Para indices puedes seleccionar "attributes" concretos como campos de indexacion
- Tablas con atributos y la PK esta formada por "subclaves"
- Tablas regionales y globales
- Tiene que haber una PartitionKey, la SortKey es opcional:
  - En una tabla que sólo tiene una clave de partición, no puede haber dos elementos con el mismo valor de clave de partición.
    
#### 2. Básico
- Es estructurado, NO relacional (no PK-FK), distribuido (shards)
- No admite Resource Based Policies
#### 3. CRUD
- Se puede limitar que atributos puedo actualizar con condiciones en PutItem
- Se puede poner TTL en un campo de tiempo y eso marca para borrado < 48h
  
#### 4. DAX
- Cache global de DynamoDB

#### 5. Encriptación
- En Cliente:
  - Hay una libreria que encripta en cliente usando un proveedor de criptograria.
- En Servidor
  
#### 6. Índices
- Globales:
  - Tienen sus propios RCUs.
- Locales:
  - Consumen los RCUs de la tabla
  - Para cambiar la sort key, pero no la partition key (xq estas en una partición ya!)
    
#### 7. Paginación
- BatchGetItem: 
  - UnprocessedKeys te indica lo que queda por procesar, se puede producir por exceso de datos o limites de RCU.
    
#### 8. Querying
- Lo GSI son para hacer queries más rápidas por Sort Key o atributos "normales"
- PartiQL:
  - Se puede lanzar hasta desde AWS Cli.
- Algunas operaciones de consulta (por campos no primarios) tendrían que escanear toda la tabla:
  - Creamos un secondary index para hacer queries por otros campos:
    - Sera global si necesitamos queries por un campo no primario (por ejemplo el mail de un usuario que es fijo).
    - Será local si nos vale que la query sea solo de los datos locales (por ejemplo si queremos query "por mes" y ya está particionado por ese criterio.

#### 9. Serverless
- RCU:
    - Eventually consistent read:
      - 0.5 RCU --> 1 KB --> 1 Seg 
    - Strongly consistent read:
        - 1 RCU --> 1 KB --> 1 Seg 
    - Transactional read:
        - 2 RCU --> 1 KB --> 1 Seg
- WCU:
  - Normal:
    - 1 WCU --> 1 KB --> 1 Seg 
  - Transaccional:
      - 2 WCU --> 1 KB --> 1 Seg
  
#### 10. Streams
- Se puede habilitar un stream que al hacer borrado por TTL, envíe el registro al stream.
- Se puede asociar una lambda como destino de stream para hacer más cosas.
  
#### 11. Throttling y 400
- Exponential backoff:
  - Ir posponiedo calls que fallan a DynamoDB por temas de exceso de trafico.
- ProvisionedThroughputExceeded no es lo mismo que ProvisionedThroughputExceededException:
  - ProvisionedThroughputExceeded:
    - Mensaje: El rendimiento supera la capacidad actual de su tabla o índice. DynamoDB está escalando automáticamente la tabla o el índice.
  - ProvisionedThroughputExceededException:
      - Mensaje: Se ha excedido el rendimiento máximo permitido para una tabla o para uno o más índices secundarios globales.
  - En ambos casos "Ok to retry".
- RequestLimitExceeded:
  - Mensaje: El rendimiento supera el límite de rendimiento actual de su cuenta. Para solicitar un aumento del límite, póngase en contacto con AWS Support.
- ThrottlingException:
  - Esta excepción se devuelve como una respuesta de AmazonServiceException con un código de estado THROTTLING_EXCEPTION. Es posible que se devuelva esta excepción si realiza operaciones de la API del plano de control con demasiada rapidez.
- Se pueden consumir hasta cinco minutos de capacidad no utilizada en ráfagas para hacer frente a picos de solicitudes.

[![AWS](https://img.shields.io/badge/DynamoDB-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/DynamoDB.md)
