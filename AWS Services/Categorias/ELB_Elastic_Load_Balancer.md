## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/AWS%20Services/AWS_Services.md)

### ELB - Elastic Load Balancer
  [![AWS](https://img.shields.io/badge/ELB_Elastic_Load_Balancer-44c04c?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/AWS%20Services/Categorias/ELB_Elastic_Load_Balancer.md)

#### ELB_Elastic_Load_Balancer
- Distribuye automáticamente el tráfico de aplicaciones entrantes entre varios destinos y dispositivos virtuales.
	- EC2
	- Contenedores
	- Direcciones IP
	- Funciones Lamda
- Puede usarse en una o varias Zonas de Disponibilidad.
- Características
	- Servicio administrado, AWS garantiza el servicio y se encarga del mantenimiento.
	- Distribuye la carga.
	- Minimiza los fallos de los flujos de tráfico hacia las instancias.
	- Punto único de acceso para los nombres de DNS de las instancias.
	- Escalable.
	- Elástico.
- Tipos
	- **Balanceador de carga de aplicaciones** >> HTTP/HTTPS. Capa7 >> **ALB**
	- **Balanceador de carga de red** >> TCP/TLS. Microservicios, Contenedores. Capa4 >> **NLB**
	- **Balanceador de carga clásico** >> Capa 4/ Capa7
- [AWS Elastic Load Balancer](https://aws.amazon.com/es/elasticloadbalancing/)
