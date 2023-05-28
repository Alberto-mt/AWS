## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/index.md)

### VPC - Redes en AWS
[![AWS](https://img.shields.io/badge/VPC_Redes_en_AWS-c044b8?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/categories/VPC_Redes_en_AWS.md)

#### VPC - Redes en AWS
- VPC (Amazon Virtual Private Cloud): Su propia red dentro de AWS.
Permite lanzar recursos de AWS en una red virtual que se haya definido, con los beneficios 
de usar la infraestructura escalable de AWS.
- Conceptos de VPC:
	- **Subnets**: Subredes dentro de la VPC en una AZ.
	- **Sub-red Publica/Public Subnet**: Accesible desde internet.
	- **Tabla de enrutamiento/Route Table**: Determina donde puede acceder.
	- **Internet Gateway**: Permiten que una VPC tenga salida a Internet.
	- **NAT Gateways**: Permiten a las sub redes privadas acceder a internet.
- Características:
	- Nubes privadas virtuales (VPC):
		- Red virtual que se parece mucho a una red tradicional que operaría en su 
		propio centro de datos. Después de crear una VPC, puede agregar subredes.
	- Subredes:
		- Es un rango de direcciones IP en su VPC. Una subred debe residir en una 
		única zona de disponibilidad. Después de agregar subredes, puede 
		implementar recursos de AWS en su VPC.
	- Direccionamiento IP:
		- Puede asignar direcciones IP , tanto IPv4 como IPv6, a sus VPC y subredes. También
		puede traer sus direcciones GUA IPv4 e IPv6 públicas a AWS y asignarlas a 
		recursos en su VPC, como instancias EC2, puertas de enlace NAT y 
		balanceadores de carga de red.
	- Enrutamiento:
		- Utiliza tablas de rutas para determinar hacia dónde se dirige el tráfico 
		de red de su subred o puerta de enlace.
	- Puertas de enlace y puntos finales:
		- Conecta su VPC a otra red. Utilice una puerta de enlace de Internet para 
		conectar su VPC a Internet. Utilice un punto de enlace de la VPC para 
		conectarse a los servicios de AWS de forma privada, sin utilizar una 
		puerta de enlace de Internet o un dispositivo NAT.
	- Conexiones de emparejamiento:
 		- Interconexiones de VPC para enrutar el tráfico entre los recursos de dos VPC.
	- Duplicación de tráfico:
		- Copia el tráfico de red desde las interfaces de red y enviar a 
		dispositivos de seguridad y monitoreo para una inspección profunda de paquetes.
	- Pasarelas de tránsito:
		- Actúa como un concentrador central, para enrutar el tráfico entre las 
		VPC, conexiones VPN y conexiones de AWS Direct Connect.
	- Registros de flujo de VPC:
		- Captura información sobre el tráfico IP que va y viene de las interfaces
		de red en la VPC.
	- Conexiones VPN: 
		- Conecta las VPC a las redes locales mediante AWS Virtual Private Network 
		(AWS VPN).
- Creación y administración de VPC mediante interfaces:
	- **Consola de administración de AWS**: 
		- Interfaz web para acceder a las VPC.
	- **Interfaz de línea de comandos de AWS (AWS CLI)**: 
		- Comandos para un amplio conjunto de servicios de AWS, incluido Amazon VPC,
 		y compatible con Windows, Mac y Linux.
	- **SDK de AWS**: 
		- API específicas del idioma, se encarga de detalles de conexión, como el 
		cálculo de firmas, el número de peticiones y el manejo de errores.
	- **API de consulta**: 
		- Acciones de API de bajo nivel a las que llama mediante peticiones HTTPS. 
		El uso de Query API es la forma más directa de acceder a Amazon VPC, pero 
		requiere que su aplicación maneje detalles de bajo nivel, como generar el 
		hash para firmar la petición y el control de errores.
- [Amazon Virtual Private Cloud (Amazon VPC)](https://aws.amazon.com/es/vpc/)

#### Route 53
- Amazon Route 53 es un servicio web de sistema de nombres de dominio (DNS) altamente 
disponible y escalable. Conecta las peticiones de los usuarios con las aplicaciones de 
Internet que se ejecutan en AWS o en las instalaciones.
- [Amazon Route 53](https://aws.amazon.com/es/route53/)
