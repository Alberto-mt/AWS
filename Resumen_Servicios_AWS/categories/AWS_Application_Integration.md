## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/index.md)

### AWS Application Integration
[![AWS](https://img.shields.io/badge/AWS_Application_Integration-c044b8?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/index.md)

#### Mensajería
##### **Amazon SNS**
- Amazon Simple Notification Service (SNS) envía notificaciones de dos maneras: A2A y A2P. 
	- A2A brinda mensajería de muchos a muchos de alto rendimiento, basada en push, entre sistemas distribuidos, microservicios y aplicaciones sin servidor controladas por eventos. Estas aplicaciones incluyen Amazon Simple Queue Service (SQS), Amazon Kinesis Data Firehose, AWS Lambda y otros puntos de conexión HTTPS. 
	- A2P permite enviar mensajes a los clientes con mensajes SMS, notificaciones push y correos electrónicos. 
- [Amazon SNS](https://aws.amazon.com/es/sns/)

##### **Amazon SQS**
- Con Amazon Simple Queue Service (SQS), puede enviar, almacenar y recibir mensajes entre componentes de software de cualquier volumen sin perder mensajes ni requerir la disponibilidad de otros servicios.
- [Amazon SQS](https://aws.amazon.com/es/sqs/)

##### **Amazon MQ**
 - Servicio de agentes de mensajería administrado for Apache ActiveMQ y RabbitMQ que simplifica la configuración, la operación y la gestión de agentes de mensajes en AWS. 
	- Los agentes de mensajes permiten que los sistemas de software, que suelen utilizar lenguajes de programación diferentes en múltiples plataformas, se comuniquen e intercambien información.
- En pocos pasos, Amazon MQ aprovisiona su agente de mensajes con compatibilidad para actualizaciones de versiones de software.
- [Amazon MQ](https://aws.amazon.com/es/amazon-mq/)

#### Flujos de trabajo
##### **AWS Step Functions**
- Servicio de flujo de trabajo visual que ayuda a los desarrolladores a usar servicios de AWS para crear aplicaciones distribuidas, automatizar procesos, organizar microservicios y crear canalizaciones de datos y de machine learning (ML).
- [AWS Step Functions](https://aws.amazon.com/es/step-functions/)

#### Gestión de API
##### **Amazon API Gateway**
- Servicio completamente administrado que facilita a los desarrolladores la creación, la publicación, el mantenimiento, el monitoreo y la protección de API a cualquier escala. 
- Las API actúan como la "puerta de entrada" para que las aplicaciones accedan a los datos, la lógica empresarial o la funcionalidad de sus servicios de backend. 
- Puede crear API RESTful y API WebSocket que permiten aplicaciones de comunicación bidireccional en tiempo real. 
- Admite cargas de trabajo en contenedores y sin servidor, así como aplicaciones web.
- Gestiona todas las tareas implicadas en la aceptación y el procesamiento de hasta cientos de miles de llamadas a API simultáneas, entre ellas, la administración del tráfico, compatibilidad con CORS, el control de autorizaciones y acceso, la limitación controlada, el monitoreo y la administración de versiones de API. API Gateway no requiere pagos mínimos ni costos iniciales. - Se paga por las llamadas a las API que se reciben y por la cantidad de datos salientes transferidos.
- El modelo de precios por niveles de API Gateway, reduce los costos a medida que se cambia la escala de uso de las API.
- [Amazon API Gateway](https://aws.amazon.com/es/api-gateway/)

##### **AWS AppSync**
- Crea las API sin servidor de GraphQL y de publicación o suscripción que simplifican el desarrollo de aplicaciones a través de un único punto de conexión para consultar, actualizar o publicar datos de forma segura. 
- [AWS AppSync](https://aws.amazon.com/es/appsync/)

#### Bus de eventos
##### **Amazon EventBridge**
- El bus de eventos de Amazon EventBridge es un bus de eventos sin servidor que ayuda a recibir, transformar, enrutar y entregar eventos.
- [Amazon EventBridge](https://aws.amazon.com/es/eventbridge/)

##### **Amazon AppFlow**
- Automatiza los flujos de datos bidireccionales entre las aplicaciones SaaS y los servicios de AWS con tan solo unos clics. 
- Ejecuta los flujos de datos con la frecuencia que se elija, ya sea de forma programada, en respuesta a un evento empresarial o bajo demanda. 
- Simplifica la preparación de datos con transformaciones, partición y agregación. 
- Automatiza la preparación y el registro de un esquema con el catálogo de datos de AWS Glue para poder descubrir y compartir datos con los servicios de análisis y aprendizaje automático de AWS.
- [Amazon AppFlow](https://aws.amazon.com/appflow/)
