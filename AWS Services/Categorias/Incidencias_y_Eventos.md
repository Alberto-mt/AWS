## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/AWS%20Services/AWS_Services.md)

### Incidencias y eventos
[![AWS](https://img.shields.io/badge/Incidencias_y_Eventos-c08a44?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/AWS%20Services/Categorias/Incidencias_y_Eventos.md)

#### Incidencias y eventos
- GuardDuty
	- Servicio de detección de amenazas que supervisa de manera continua las cargas de trabajo y cuentas de AWS para detectar actividades maliciosas y envía hallazgos detallados 
de seguridad para su visibilidad y resolución.
	- Características:
		- Utiliza fuentes de datos de AWS y de terceros líderes del sector y combina el 	aprendizaje automático.
		- Monitorea continuamente sus cuentas, instancias, cargas de trabajo de 			contenedores, usuarios, bases de datos y almacenamiento de AWS para detectar posibles 	amenazas.
		- Detecta amenazas rápidamente mediante detección de anomalías, ML, modelado del 		comportamiento y fuentes de inteligencia sobre amenazas de AWS y de líderes externos.
		- Mitiga las amenazas con antelación mediante el inicio de respuestas automatizadas.
	- Casos de uso:
		- Mejora de la visibilidad de las operaciones de seguridad. 
		- Ayuda para los analistas de seguridad en las investigaciones.
		- Identificación de archivos que contienen software malintencionado.
		- Enrutamiento de la información de los hallazgos de seguridad.
	- [Amazon GuardDuty](https://aws.amazon.com/es/guardduty/)

- Inspector
	- Servicio de administración automatizada de vulnerabilidades que analiza continuamente 	las cargas de trabajo de AWS en busca de vulnerabilidades de software y exposición 	involuntaria a la red. Descubre automáticamente cargas de trabajo, como las instancias de 	Amazon EC2, 	contenedores y funciones de Lambda, y los escanea para encontrar 	vulnerabilidades de software y exposición involuntaria de red.
	- Características:
		- Detecta y analiza cargas de trabajo de AWS en busca de vulnerabilidades de 		software y exposición de red no deseadas de manera inmediata con un solo clic.
		- Consolida sus soluciones de administración de vulnerabilidades para Amazon EC2, 	las funciones de AWS Lambda y las imágenes de contenedores en Amazon ECR en un servicio 	completamente administrado.
		- Utiliza el puntaje de riesgo de Inspector de gran precisión para priorizar de 		forma eficaz su resolución de problemas.
		- Reduce el tiempo medio de resolución (MTTR) de vulnerabilidades y optimice el 		flujo de trabajo con integraciones de Amazon EventBridge y AWS Security Hub.
	- Casos de uso: 
		- Descubre rápidamente las vulnerabilidades en las cargas de trabajo de 	computación.
		- Priorización de la corrección de parches.
		- Cumplimiento de los requisitos de conformidad.
		- Identificación temprana de vulnerabilidades de día cero.
	- [Amazon Inspector](https://aws.amazon.com/es/inspector/)
		
- Kinesis
	- Procesa y analiza de forma rentable datos de streaming a cualquier escala como un 	servicio totalmente administrado. Con Kinesis, se pueden recopilar datos en tiempo 	real, como vídeo, audio, logs de aplicaciones, secuencias de clics de sitios web y 	datos telemétricos de IoT, para aprendizaje automático (ML), análisis y otras 	aplicaciones.
	- Características:
		- Recopilar, almacenar en búfer y procesar datos en tiempo real para obtener 		información en cuestión de minutos, no de días.
		- Ejecutar las aplicaciones de streaming en una infraestructura sin servidor con 		un servicio totalmente gestionado.
		- Gestionar cualquier cantidad de datos de streaming procedentes de miles de 	fuentes y procesarlos con bajas latencias.
	- Tipos:
		- Kinesis Data Analytics:
			- Transformar y analizar más fácilmente los datos de streaming en tiempo real
		mediante Apache Flink.
		- Kinesis Data Firehose:
			- Servicio de extracción, transformación y carga (ETL) que captura, transforma 		y entrega datos de streaming a lagos de datos, almacenes de datos y servicios de 			análisis.
		- Kinesis Data Streams:
			- Servicio de datos de streaming sin servidor que simplifica la captura, el 			procesamiento y el almacenamiento de transmisiones de datos a cualquier escala.
		- Kinesis Video Streams: 
			- Transmitir vídeo de forma más sencilla y segura desde dispositivos 				conectados a AWS para análisis, ML, reproducción y otros procesamientos.
	- Casos de uso:
		- Crear aplicaciones en tiempo real.
		- Evolucionar del análisis por lotes al análisis en tiempo real.
		- Analizar datos de dispositivos IoT.
		- Crear aplicaciones de análisis de vídeo.
	- [Amazon Kinesis](https://aws.amazon.com/es/kinesis/)
