## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/index.md)

### AWS Networking & Content Delivery
[![AWS](https://img.shields.io/badge/AWS_Networking_&_Content_Delivery-44c04c?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/categories/AWS_Networking_%26_Content_Delivery.md)

#### 1. Construir una red en la nube
##### **Amazon VPC (Amazon Virtual Private Cloud)**
- Permite el control total sobre el entorno de redes virtuales, incluidas la ubicación de los recursos, la conectividad y la seguridad.
  1. Configurar su VPC en la consola de los servicios de AWS.
  2. Agréguele recursos, como instancias de Amazon Elastic Compute Cloud (EC2) y Amazon Relational Database Service (RDS). 
  3. Defina cómo se comunican sus VPC entre sí, entre cuentas, zonas de disponibilidad o regiones de AWS. 
- [Amazon VPC (Amazon Virtual Private Cloud)](https://aws.amazon.com/es/vpc/)

##### **AWS Transit Gateway**
- Conecta las nubes virtuales privadas (VPC) y las redes en las instalaciones a través de un eje central. Esto simplifica la red y pone fin a las complejas relaciones de interconexión.
- Funciona como un enrutador de nube muy escalable; cada conexión solo se realiza una sola vez.
- [AWS Transit Gateway](https://aws.amazon.com/es/transit-gateway/)

##### **AWS PrivateLink**
- Proporciona conectividad privada entre las nubes virtuales privadas (VPC), los servicios de AWS compatibles y las redes en las instalaciones, sin exponer el tráfico a la Internet pública.
- Los puntos de conexión de VPC de interfaz, basados en PrivateLink, permiten conectarse a servicios alojados por socios de AWS y soluciones compatibles disponibles en AWS Marketplace.
- [AWS PrivateLink](https://aws.amazon.com/es/privatelink/)

##### **Amazon Route 53**
- Servicio web de sistema de nombres de dominio (DNS) escalable y de alta disponibilidad. Route 53 conecta las solicitudes de los usuarios con las aplicaciones de Internet que se ejecutan en AWS o en las instalaciones.
- [Amazon Route 53](https://aws.amazon.com/es/route53/)

#### 2. Ampliar el diseño de la red
##### **Amazon ELB (Amazon  Elastic Load Balancing)**
- Distribuye automáticamente el tráfico entrante de aplicaciones entre varios destinos y dispositivos virtuales en una o varias zonas de disponibilidad (AZ).
- [Amazon ELB (Amazon  Elastic Load Balancing)](https://aws.amazon.com/elasticloadbalancing/)

##### **AWS Global Accelerator**
- Servicio de red que le ayuda a mejorar la disponibilidad, el desempeño y la seguridad de sus aplicaciones públicas. Global Accelerator proporciona dos IP públicas estáticas globales que actúan como punto de entrada fijo a los puntos de enlace de sus aplicaciones, como balanceadores de carga de aplicaciones, balanceadores de carga de red, instancias de Amazon Elastic Compute Cloud (EC2) e IP elásticas.
- [AWS Global Accelerator](https://aws.amazon.com/global-accelerator/)

#### 3. Crear una red informática híbrida
##### **AWS Client VPN**
- Es una solución de VPN de acceso remoto totalmente administrada que su personal remoto utiliza para acceder de forma segura a los recursos de AWS y de su red on-premise. Totalmente elástica, se amplía o reduce automáticamente en función de la demanda. Al migrar aplicaciones a AWS, los usuarios acceden a ellas de la misma manera antes, durante y después del traslado. AWS Client VPN, incluido el cliente de software, admite el protocolo OpenVPN.
- [AWS Client VPN](https://aws.amazon.com/vpn/client-vpn/)

##### **AWS Site-to-Site VPN**
- Servicio totalmente administrado que crea una conexión segura entre su centro de datos o sucursal y sus recursos de AWS mediante túneles de seguridad IP (IPSec). Al utilizar Site-to-Site VPN, puede conectarse tanto a sus Amazon Virtual Private Clouds (VPC) como a AWS Transit Gateway, y se utilizan dos túneles por conexión para aumentar la redundancia.
Para aplicaciones distribuidas globalmente, la opción Accelerated Site-to-Site VPN proporciona un rendimiento aún mayor al trabajar con AWS Global Accelerator para enrutar de forma inteligente su tráfico al punto final de red de AWS más cercano con el mejor rendimiento.
- [AWS Site-to-Site VPN](https://aws.amazon.com/vpn/site-to-site-vpn/)

##### **AWS Direct Connect**
- El servicio de nube AWS Direct Connect es la ruta más corta hacia los recursos de AWS. Mientras está en tránsito, el tráfico de la red se mantiene en la red global de AWS y nunca tiene contacto con el Internet público. Esto reduce las probabilidades de encontrar cuellos de botella o aumentos de la latencia inesperados. Cuando se crea una nueva conexión, puede elegir una conexión alojada que proporcione un socio de entrega de AWS Direct Connect, o bien, puede optar por una conexión dedicada de AWS e implementar en más de 100 ubicaciones de AWS Direct Connect en todo el mundo.
- Permite enviar datos entre ubicaciones de AWS Direct Connect para crear conexiones de red privadas entre las oficinas y los centros de datos en una red global.
- [AWS Direct Connect](https://aws.amazon.com/es/directconnect/)

#### 4. Redes de distribución de contenidos
##### **Amazon CloudFront**
- Servicio de red de entrega de contenido (CDN) creado para ofrecer un alto rendimiento, seguridad y comodidad para los desarrolladores.
- [Amazon CloudFront](https://aws.amazon.com/es/cloudfront/)

#### 5. Construir una red para arquitecturas de microservicios
##### **AWS App Mesh**
- Proporciona conexión de red de nivel de aplicación para que los servicios puedan comunicarse a través de varios tipos de infraestructura de computación.
- [AWS App Mesh](https://aws.amazon.com/es/app-mesh/)

##### **Amazon API Gateway**
- Servicio completamente administrado que facilita a los desarrolladores la creación, la publicación, el mantenimiento, el monitoreo y la protección de API a cualquier escala.
- Las API actúan como la "puerta de entrada" para que las aplicaciones accedan a los datos, la lógica empresarial o la funcionalidad de sus servicios de backend.
- Permite crear API RESTful y API WebSocket que permiten aplicaciones de comunicación bidireccional en tiempo real.
- Admite cargas de trabajo en contenedores y sin servidor, así como aplicaciones web.
- Gestiona todas las tareas implicadas en la aceptación y el procesamiento de hasta cientos de miles de llamadas a API simultáneas, entre ellas, la administración del tráfico, compatibilidad con CORS, el control de autorizaciones y acceso, la limitación controlada, el monitoreo y la administración de versiones de API.
- No requiere pagos mínimos ni costos iniciales. Se paga por las llamadas a las API que se reciben y por la cantidad de datos salientes transferidos; además, con el modelo de precios por niveles de API Gateway, se pueden reducir costos a medida que se cambia la escala de uso de las API.
- [Amazon API Gateway](https://aws.amazon.com/es/api-gateway/)

##### **AWS Cloud Map**
- Servicio de descubrimiento de recursos en la nube.
- Se pueden definir nombres personalizados para los recursos de su aplicación, y mantener la ubicación actualizada de estos recursos que cambian dinámicamente. Esto aumenta la disponibilidad de la aplicación porque el servicio web siempre descubre las ubicaciones más actualizadas de los recursos.
- Permite registrar cualquier recurso de la aplicación, como bases de datos, colas, microservicios y otros recursos en la nube, con nombres personalizados. A continuación, Cloud Map comprueba constantemente el estado de los recursos para asegurarse de que la ubicación está actualizada. A continuación, la aplicación puede consultar el registro para conocer la ubicación de los recursos necesarios en función de la versión de la aplicación y el entorno de despliegue.
- [AWS Cloud Map](https://aws.amazon.com/cloud-map/)
