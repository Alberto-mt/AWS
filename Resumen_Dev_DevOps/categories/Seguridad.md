## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/index.md)

### Seguridad
[![AWS](https://img.shields.io/badge/Seguridad-44c04c?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/categories/Seguridad.md)

#### Seguridad
- IAM Identity Center (Antiguo AWS SSO - Single Sign-On  )
	- Gestiona de forma segura el acceso a servicios y recursos.
	- Identificación simplificada que administra el acceso a cuentas de AWS y 	aplicaciones empresariales.
	- Características:
		- Reforzar la seguridad de las contraseñas.
		- Mejora de la productividad.
		- Reducción de costos.
		- Mejora la posición de seguridad.
		- Una mejor experiencia al cliente.
	- Tipos:
		- SAML:
			- SAML, o lenguaje de marcado de aserción de seguridad, es un 			protocolo o conjunto de reglas que utilizan las aplicaciones para 			intercambiar información de autenticación con el servicio SSO. SAML 		utiliza XML, un lenguaje de marcas compatible con el navegador, para 		intercambiar datos de identificación de usuarios. Los servicios SSO 		basados en SAML brindan mayor seguridad y flexibilidad, ya que las 			aplicaciones no necesitan almacenar las credenciales de los usuarios 		en su sistema.
		- OAuth:
			- OAuth, o autorización abierta, es un estándar abierto que 			permite que las aplicaciones obtengan acceso seguro a la información 		del usuario desde otros sitios web sin darles la contraseña. En lugar 		de solicitar contraseñas de usuario, las aplicaciones usan OAuth para 		obtener permiso de usuario para acceder a datos protegidos por 				contraseña. OAuth establece la confianza entre las aplicaciones a 			través de la API, lo que permite que la aplicación envíe y responda 		solicitudes de autenticación en un marco establecido.
		- OIDC:
			- OpenID es una forma de utilizar un único conjunto de 					credenciales de usuario para acceder a varios sitios. Permite que el 		proveedor de servicios asuma el rol de autenticar las credenciales 			del usuario. En lugar de pasar un token de autenticación a un 				proveedor de identidad externo, las aplicaciones web usan OIDC para 		solicitar información adicional y validar la autenticidad del 				usuario.
		- Kerberos:
			- Kerberos es un sistema de autenticación basado en tickets que 		permite que dos o más partes verifiquen mutuamente su identidad en la 		red. Utiliza criptografía de seguridad para evitar el acceso no 			autorizado a la información de identificación transmitida entre el 			servidor, los clientes y el centro de distribución de claves.
	- [AWS IAM Identity Center](https://aws.amazon.com/es/iam/identity-center/)

- CloudFront
	- Entrega segura de contenidos con baja latencia y alta velocidad de 	transferencia.
	- Características: 
		- Reduce la latencia mediante la entrega de datos a través de más de 		450 puntos de presencia (PoP) dispersos por todo el mundo con mapeo 		de red automatizado y enrutamiento inteligente.
		- Mejora la seguridad con cifrado de tráfico y controles de acceso, y 		con AWS Shield Standard defiende de ataques DDoS sin cargo 					adicional.
		- Reduce costes con solicitudes consolidadas, opciones de precios 			personalizables y tasas cero para la transferencia de datos desde los 		orígenes de AWS.
		- Personaliza el código que ejecuta en el borde de la red de entrega 		de contenido (CDN) de AWS mediante características informáticas sin 		servidor para equilibrar el costo, el desempeño y la seguridad.
	- [Amazon CloudFront](https://aws.amazon.com/es/cloudfront/)

- Auto Scaling
	- Permite crear planes de escalado que automatizan cómo grupos de 	diferentes recursos responden a los cambios en la demanda. Puede 	optimizar la disponibilidad, los costos o un equilibrio de ambos.
	Crea automáticamente todas las políticas de escalado y establece 	objetivos según preferencias.
	- Definiendo AutoScaling:
		- Scale OUT: Agrega Instancias de EC2.
		- Scale IN: Remueve instancias de EC2.
		- Asegura cantidad mínima/máxima de instancias.
		- Registrarlas automáticamente a ELB.
	- Autoscaling Group / Grupo de autoescalado:
		- Define las reglas de cuando se debe agregar una instancia EC2.
		- Cantidad de instancias mínimas y máximas.
	- [AWS Auto Scaling](https://aws.amazon.com/es/autoscaling/)

- Route 53
	- Servicio web de sistema de nombres de dominio (DNS) escalable y de alta 	disponibilidad. Route 53 conecta las solicitudes de los usuarios con las 	aplicaciones de Internet que se ejecutan en AWS o en las instalaciones.
	- Características:
		- Dirige a los usuarios finales a su sitio de forma confiable 				mediante servidores de sistema de nombres de dominio (DNS) 					distribuidos a nivel mundial y con escalado automático.
		- Configura el enrutamiento del DNS en cuestión de minutos mediante 		el registro de nombres de dominio y las sencillas herramientas 				visuales de flujo de tráfico.
		- Personaliza sus políticas de enrutamiento del DNS a fin de reducir 		la latencia, mejorar la disponibilidad de las aplicaciones y 				garantizar el cumplimiento.
	- Casos de uso:
		- Administra el tráfico de red de forma global.
		- Crea aplicaciones de alta disponibilidad.
	- [Amazon Route 53](https://aws.amazon.com/es/route53/)
