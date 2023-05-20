## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/AWS%20Services/AWS_Services.md)

### S3 - Simple Storage Service
[![AWS](https://img.shields.io/badge/S3_Simple_Storage_Service.md-c08a44?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/AWS%20Services/Categorias/EBS_Elastic_Block_Store.md)

#### S3 - Simple Storage Service
- Almacenamiento de objetos creado para recuperar cualquier volumen de datos desde cualquier lugar. Amazon Simple Storage Service (Amazon S3) es un servicio de almacenamiento de objetos que ofrece escalabilidad, disponibilidad de datos, seguridad y rendimiento.

- Casos de uso:
	- Web Site estaticos.
	- Copias de seguridad y restauración (Backup and Restore).
	- Archivo de datos.
	- Lagos de datos para Big Data (Data Lake).
	- Recuperación de desastres.
	- Almacenamiento para nube híbrida.
	- Seguridad y cumplimiento.

- Tipos:
	- **Amazon S3 Standard** - Propósito general.
		- Activo, datos de acceso frecuente.
		- Acceso en milisegundos.
		- Mayor o igual a 3 AZ.
	- **Amazon S3 Intelligent Tiering**.
		- Datos con patrón de acceso cambiante.
		- Acceso en milisegundos.
		- Mayor o igual a 3 AZ.
		- Costo por monitoreo de obj.
		- Duración min de almacenamiento.
	- **Amazon S3 Standard-Infrequent Access (IA)** - Acceso poco frecuente.
		- Datos accedidos de forma infrecuente.
		- Acceso en milisegundos.
		- Mayor o igual a 3 AZ.
		- Costo por obtención del dato por GB.
		- Duración min de almacenamiento.
		- Tamaño mínimo del objeto.
	- **Amazon S3 One Zone-Infrequent Access** - Acceso poco frecuente.
		- Datos reproducible.
		- Acceso en milisegundos.
		- 1 AZ.
		- Costo por obtención del dato por GB.
		- Duración min de almacenamiento y tamaño.
	- **Amazon Glacier**.
		- Datos historicos.
		- Acceso en min o horas.
		- Mayor o igual a 3 AZ.
		- Costo por obtención del dato por GB.
		- Duración min de almacenamiento y tamaño.
	- **Amazon Glacier Deep Archive**.
		- Datos historicos.
		- Acceso en horas.
		- Mayor o igual a 3 AZ.
		- Costo por obtención del dato por GB.
		- Duración min de almacenamiento y tamaño.

- **S3: Buckets** >> Contenedores para objetos = Directorio
	- Nombre Único Global.
	- Definidos en una región.
	- Nombre:
		- 3-63 caracteres.
		- Sin mayúsculas.
		- Sn guion bajo "_".
		- No puede ser una IP.
		- Deben empezar con una minúscula o número.

- **S3: Objects** >> Objeto = Archivo
		- 1 bite a 5 Terabytes.
		- Se colocan en un bucket.
		- Contiene Data + Meta Data.
		- Etiquetas (TAGs).
		- Identificador de versión.
		- Key Prefijo + Nombre de Objeto.

- [Amazon S3](https://aws.amazon.com/es/s3/)
