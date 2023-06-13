## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/index.md)

### AWS Analytics
[![AWS](https://img.shields.io/badge/AWS_Analytics-447ac0?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/categories/AWS_Analytics.md)

#### 1. Analítica
##### 1.1. Análisis interactivos
###### **Amazon Athena**
- Servicio de análisis interactivo y sin servidor creado en marcos de código abierto, es compatible con formatos abiertos de archivos y tablas.
- Proporciona un método simplificado y flexible de analizar petabytes de datos donde residan.
- Analiza datos o crea aplicaciones a partir de un lago de datos de Amazon Simple Storage Service (S3) y más de 25 orígenes de datos, que incluyen orígenes de datos en las instalaciones u otros sistemas en la nube que usan SQL o Python.
- [Amazon Athena](https://aws.amazon.com/es/athena/).
- <a href="https://aws.amazon.com/es/athena/" target="_blank">Amazon Athena.</a>

##### 1.2. Procesamiento de macrodatos
###### **Amazon EMR**
- Solución de macrodatos en la nube destinado al procesamiento de datos a escala de petabytes.
- Análisis interactivo y aprendizaje automático mediante el uso de marcos de código abierto, como Apache Spark, Apache Hive y Presto.
	- [Apache Spark](https://aws.amazon.com/es/emr/features/spark/)
	- [Apache Hive](https://aws.amazon.com/es/emr/features/hive/)
	- [Presto](https://aws.amazon.com/es/emr/features/presto/)
- [Amazon EMR](https://aws.amazon.com/es/emr/)

##### 1.3. Almacenamiento de datos
###### **Amazon Redshift**
- Utiliza SQL para analizar datos estructurados y semiestructurados en almacenamientos de datos, bases de datos operativas y lagos de datos, con hardware y machine learning.
- Ofrece rendimiento al mejor precio a cualquier escala.
- [Amazon Redshift](https://aws.amazon.com/es/redshift/)

##### 1.4. Análisis en tiempo real
###### **Amazon Kinesis**
- Facilita la recopilación, el procesamiento y el análisis de datos de streaming en tiempo real para obtener datos de manera oportuna y reaccionar rápidamente ante información nueva.
- Ofrece capacidades clave para procesar de manera rentable datos de streaming a cualquier escala, además de la flexibilidad para elegir las herramientas más adecuadas para los requisitos de la aplicación.
- Se pueden incorporar datos en tiempo real, como videos, audios, registros de aplicaciones, secuencias de clics de sitios web y datos de telemetría de IoT para aprendizaje automático, análisis y otras aplicaciones.
- Permite procesar y analizar datos a medida que se reciben y responder instantáneamente en vez de tener que esperar a que los datos se recopilen antes de que el procesamiento pueda comenzar.
- [Amazon Kinesis](https://aws.amazon.com/es/kinesis/)

##### 1.5. Análisis operativo
###### **Amazon OpenSearch Service**
- Facilita la realización de análisis de logs interactivos, monitorización de aplicaciones en tiempo real, búsquedas en sitios web y mucho más.
- Es una suite de análisis y búsqueda distribuida de código abierto derivada de Elasticsearch. 
- Ofrece las versiones más recientes de OpenSearch, compatibilidad con 19 versiones de Elasticsearch (versiones 1.5 a 7.10), así como capacidades de visualización impulsadas por OpenSearch Dashboards y Kibana (versiones 1.5 a 7.10).
- Cuenta con decenas de miles de clientes activos con cientos de miles de clústeres administrados que procesan cientos de billones de solicitudes al mes.
- [Amazon OpenSearch Service](https://aws.amazon.com/opensearch-service/)

##### 1.6. Cuadros de mando y visualizaciones
###### **Amazon QuickSight**
- Permite que todos los miembros de una organización comprendan sus datos mediante preguntas en lenguaje natural, la exploración a través de paneles interactivos o la búsqueda automática de patrones y valores atípicos impulsada por machine learning.
- Lanza millones de visualizaciones semanales del panel para clientes, lo que permite a sus usuarios finales tomar mejores decisiones controladas por datos.
- [Amazon QuickSight](https://aws.amazon.com/es/quicksight/)

#### 2. Flujo de datos
##### 2.1. Flujo de datos en tiempo real
###### **Amazon Managed Streaming for Apache Kafka (MSK)**
- Facilita la ingesta y el procesamiento de datos de transmisión en tiempo real con Apache Kafka completamente administrado.
- [Amazon Managed Streaming for Apache Kafka (MSK)](https://aws.amazon.com/es/msk/)

###### **Amazon Kinesis Data Streams**
- Servicio de datos de streaming sin servidor que hace que sea fácil capturar, procesar y almacenar flujos de datos a cualquier escala.
- [Amazon Kinesis Data Streams](https://aws.amazon.com/es/kinesis/data-streams/)

###### **Amazon Kinesis Data Firehose**
- Servicio de extracción, transformación y carga (ETL) que captura, transforma y entrega de manera fiable datos de streaming en lagos y almacenes de datos y servicios de análisis.
- [Amazon Kinesis Data Firehose](https://aws.amazon.com/es/kinesis/data-firehose/)

###### **Amazon Kinesis Data Analytics**
- Ofrece la manera más sencilla de transformar y analizar datos de streaming en tiempo real con Apache Flink.
- [Amazon Kinesis Data Analytics](https://aws.amazon.com/es/kinesis/data-analytics/)

###### **Amazon Kinesis Video Streams**
- Facilita la transmisión segura de videos desde dispositivos conectados a AWS para tareas de análisis, aprendizaje automático (ML), reproducción y otros procesos.
- Aprovisiona automáticamente y escala de manera elástica toda la infraestructura necesaria para incorporar datos de las transmisiones de vídeo de millones de dispositivos. 
- Almacena, cifra e indexa de forma duradera datos de videos en transmisiones y permite obtener acceso a los datos mediante API fáciles de usar. 
- Permite reproducir videos para visualizaciones en directo y bajo demanda, y crear rápidamente aplicaciones que aprovechan la visión artificial y el análisis de videos a través de la integración con Amazon Rekognition Video, y bibliotecas para marcos de ML, como Apache MxNet, TensorFlow y OpenCV.
- Admite WebRTC, un proyecto de código abierto que permite la transmisión y la interacción de medios en tiempo real entre los navegadores web, las aplicaciones móviles y los dispositivos conectados mediante API simples. 
- Videollamadas y transmisiones de medios entre pares.
- [Amazon Kinesis Video Streams](https://aws.amazon.com/es/kinesis/video-streams/?amazon-kinesis-video-streams-resources-blog.sort-by=item.additionalFields.createdDate&amazon-kinesis-video-streams-resources-blog.sort-order=desc)

###### **AWS Glue**
- Servicio de integración de datos sin servidor que facilita la detección, preparación, migración e integración de datos provenientes de varios orígenes para el análisis, machine learning (ML) y desarrollo de aplicaciones.
- [AWS Glue](https://aws.amazon.com/es/glue/)

#### 3. Lago de datos
##### 3.1. Almacenamiento de objetos
###### **AWS Lake Formation**
- Almacenamiento de objetos.
- Crea fácilmente lagos de datos seguros, poniendo los datos a disposición de análisis de amplio alcance.
- [AWS Lake Formation](https://aws.amazon.com/lake-formation/)

##### 3.2. Datos de terceros
###### **AWS Data Exchange**
- Datos de terceros.
- Aumenta la velocidad de obtención de valor de los conjuntos de datos de terceros en la nube.
- Se pueden encontrar archivos de datos, tablas de datos y API de datos de una amplia cartera de conjuntos de datos de terceros. 
- [AWS Data Exchange](https://aws.amazon.com/data-exchange/?adx-cards2.sort-by=item.additionalFields.eventDate&adx-cards2.sort-order=desc)
