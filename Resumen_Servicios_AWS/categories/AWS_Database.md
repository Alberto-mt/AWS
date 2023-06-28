## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/index.md)

### AWS Database
[![AWS](https://img.shields.io/badge/AWS_Database-447ac0?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/categories/AWS_Database.md)

#### 1. Relacionales
Aplicaciones tradicionales, ERP, CRM, comercio electrónico.
##### **Amazon Aurora**
- Ofrece seguridad integrada.
- Copias de seguridad continuas.
- Computación sin servidor.
- Hasta 15 réplicas de lectura.
- Replicación automatizada en varias regiones.
- Integraciones en otros servicios de AWS.
- [Amazon Aurora](https://aws.amazon.com/es/rds/aurora/).

##### **Amazon RDS (Amazon Relational Database Service)**
- Colección de servicios administrados que facilita las tareas de configuración, operación y escalado de una base de datos en la nube.
- Siete motores populares entre los que elgir:
  - [Amazon Aurora con compatibilidad con MySQL](https://aws.amazon.com/es/rds/aurora/?pg=ln&sec=hiw).
  - [Amazon Aurora con compatibilidad con PostgreSQL](https://aws.amazon.com/es/rds/aurora/?pg=ln&sec=hiw).
  - [MySQL](https://aws.amazon.com/es/rds/mysql/?pg=ln&sec=hiw).
  - [ MariaDB](https://aws.amazon.com/es/rds/mariadb/?pg=ln&sec=hiw).
  - [PostgreSQL](https://aws.amazon.com/es/rds/postgresql/?pg=ln&sec=hiw).
  - [Oracle ](https://aws.amazon.com/es/rds/oracle/?pg=ln&sec=hiw).
  - [SQL Server](https://aws.amazon.com/es/rds/sqlserver/?pg=ln&sec=hiw).
- Se puede implementar en las instalaciones con Amazon RDS en [AWS Outposts](https://aws.amazon.com/es/rds/outposts/?).
- [Amazon RDS](https://aws.amazon.com/es/rds/).

##### **Amazon Redshift**
- Utiliza SQL para analizar datos estructurados y semiestructurados en almacenamientos de datos, bases de datos operativas y lagos de datos, con hardware y machine learning diseñado por AWS para ofrecer rendimiento al mejor precio a cualquier escala.
- [Amazon Redshift](https://aws.amazon.com/es/redshift/).

#### 2. Clave-Valor
Aplicaciones web de alto tráfico, sistemas de comercio electrónico, aplicaciones de juegos.
##### **Amazon DynamoDB**
- Base de datos NoSQL de clave-valor sin servidor y completamente administrada.
- Diseñada para ejecutar aplicaciones de alto rendimiento a cualquier escala.
- Ofrece seguridad integrada, copias de seguridad continuas, replicación automatizada en varias regiones.
- Almacenamiento de caché en memoria.
- Herramientas de importación y exportación de datos.
- [Amazon DynamoDB](https://aws.amazon.com/es/dynamodb/).

#### 3. En memoria
Almacenamiento en caché, gestión de sesiones, tablas de clasificación de juegos, aplicaciones geoespaciales.
##### **Amazon ElastiCache for Redis**
- Opción para implementar una caché en memoria de alta disponibilidad, distribuida y segura a fin de reducir la latencia de acceso, incrementar la capacidad de procesamiento y aliviar la carga de las aplicaciones y bases de datos relacionales o NoSQL.
- Puede abastecer elementos solicitados con frecuencia con tiempos de respuesta inferiores a un milisegundo.
- Permite escalar con facilidad si las cargas se incrementan sin tener que ampliar bases de datos backend de mayor costo.
- Usos como el almacenamiento en caché de los resultados de las consultas a la base de datos, de las sesiones persistentes y de las páginas completas.
- [Amazon ElastiCache for Redis](https://aws.amazon.com/es/elasticache/redis/).

##### **Amazon MemoryDB for Redis**
- Servicio de base de datos en memoria, duradero y compatible con Redis para un rendimiento ultrarrápido.
- [Amazon MemoryDB for Redis](https://aws.amazon.com/memorydb/).

#### 4. Documento
Gestión de contenidos, catálogos, perfiles de usuario.
##### **Amazon DocumentDB (with MongoDB compatibility)**
- Base de datos de documentos JSON nativa totalmente administrada que facilita y rentabiliza el funcionamiento de cargas de trabajo de documentos críticos a prácticamente cualquier escala sin necesidad de administrar la infraestructura.
- Simplifica su arquitectura al proporcionar prácticas recomendadas de seguridad integradas, backups continuos e integraciones nativas con otros servicios de AWS.
- [Amazon DocumentDB (with MongoDB compatibility)](https://aws.amazon.com/documentdb/).

#### 5. Columna-ancha
Aplicaciones industriales a gran escala para mantenimiento de equipos, gestión de flotas y optimización de rutas.
##### **Amazon Keyspaces (for Apache Cassandra)**
- Servicio de base de datos escalable, altamente disponible y administrado compatible con Apache Cassandra.
- Permite ejecutar cargas de trabajo de Cassandra en AWS utilizando el mismo código de aplicación de Cassandra y las mismas herramientas para desarrolladores que utiliza actualmente. No se tiene que aprovisionar, parchear ni administrar servidores, ni tampoco instalar, mantener u operar software.
- No tiene servidor, por lo que solo paga por los recursos que utiliza y el servicio puede escalar automáticamente las tablas hacia arriba y hacia abajo en respuesta al tráfico de la aplicación.
- Permite crear aplicaciones que atiendan miles de solicitudes por segundo con un rendimiento y un almacenamiento prácticamente ilimitados.
- Los datos se cifran de forma predeterminada.
- Permite realizar backups continuos de los datos de las tablas mediante la recuperación puntual.
- Proporciona desempeño, elasticidad y características empresariales que necesita para operar cargas de trabajo de Cassandra críticas para el negocio a escala.
- [Amazon Keyspaces (for Apache Cassandra)](https://aws.amazon.com/keyspaces/).

#### 6. Gráfico
Detección de fraudes, redes sociales, motores de recomendación.
##### **Amazon Neptune**
- Servicio de base de datos completamente administrado y creado para la nube que facilita la creación y ejecución de aplicaciones de grafos.
- Proporciona seguridad integrada, copias de seguridad continuas, computación sin servidor e integraciones con otros servicios de AWS.
- [Amazon Neptune](https://aws.amazon.com/es/neptune/).

#### 7. Series temporales
Aplicaciones IoT, DevOps, telemetría industrial.
##### **Amazon Timestream**
- Servicio de base de datos de series temporales rápido, escalable y sin servidor que facilita el almacenamiento y el análisis de billones de eventos al día hasta 1000 veces más rápido.
- Se escala automáticamente hacia arriba o hacia abajo para ajustar la capacidad y el desempeño, de manera que no se tenga que administrar la infraestructura subyacente.
- [Amazon Timestream](https://aws.amazon.com/timestream/).

#### 8. Libro mayor
Sistemas de registro, cadena de suministro, registros, transacciones bancarias.
##### **Amazon Quantum Ledger Database (QLDB)**
- Base de datos de libro mayor completamente administrada en la que se proporciona un registro de transacciones transparente, inmutable y que se puede verificar mediante criptografía.
- [Amazon Quantum Ledger Database (QLDB)](https://aws.amazon.com/es/qldb/).

[![AWS](https://img.shields.io/badge/Inicio-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/categories/AWS_Database.md)
