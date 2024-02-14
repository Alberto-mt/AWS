## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/index.md)

### CloudFront
[![AWS](https://img.shields.io/badge/CloudFront-44c04c?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/CloudFront.md)

#### 1.  Autenticación
- Origin Access Control
- Origin Access Identity
- Sigv4

#### 2. Básico
- Configuras "Distribuciones" y se copia contenido de ALBs a CloudFront
- El origin es de donde sacas la informacion (a nivel de Cloud)

#### 3. Certificados de servidor
- Para utilizar un certificado ACM con CloudFront, asegúrese de solicitar (o importar) el certificado en la región EE. UU. Este (Norte de Virginia) (us-east-1).

#### 4. Functions
- Escritas en JS
- Manipular CIERTAS cosas en el "extremo final" de la comunicación con el cliente
  - Puedes hacer un URL redirect
  - Puedes manipular las cabeceras HTTP
- No pueden usar  el "origin request event"
  - No puedes manipular el "source bucket" de una request por ejemplo

#### 5. Hosting S3
- Para acceder por HTTPs lo recomendado es SSL en CloudFront
- Ideal para cachear contenidos estáticos habilitados como web y le puedes poner TTL elevado

#### 6. Lambda@edge
- Usar KMS para encriptar campos sensibles
- Solo se pueden crear en us-east-1 (y luego seleccionas en que cloudfronts quieres que corran)
- Si pueden manipular el "request origin event"
  - Cambiar el bucket al que la va la solicitud

#### 7. Signed urls
- Se usan para proteger accesos a servicios de la region validando en cloudfront
- Para poder crearlas hay que generar un par de claves RSA
- La clave privada la tiene que tener la app que quiere llegar a la region
- Las claves publicas deben estar en cloudfront para verificar la firma

#### 8. Super freaky
- Puedes tener "multiorigin" para traer archivos de diferentes buckets

#### 9. WAF
- Las ACLs permiten configurar reglas que validan solicitudes en base a caracteristicas de los paquetes de datos y esas reglas se pueden replicar a CF

[![AWS](https://img.shields.io/badge/CloudFront-44c04c?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/CloudFront.md)
