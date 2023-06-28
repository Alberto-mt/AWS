## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/index.md)

### AWS Security Identity Compliance
[![AWS](https://img.shields.io/badge/AWS_Security_Identity_Compliance-447ac0?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/categories/AWS_Security_Identity_Compliance.md)

#### 1. Identidad
##### **AWS Identity and Access Management (IAM)**
- Gestiona de forma segura el acceso a servicios y recursos.
- Permite especificar quién o qué puede acceder a los servicios y recursos en AWS, administrar de forma centralizada los permisos específicos y analizar el acceso para perfeccionar los permisos en todo AWS.
- [AWS Identity and Access Management (IAM)](https://aws.amazon.com/es/iam/)

##### **AWS IAM Identity Center**
- Gestiona de forma segura el acceso a servicios y recursos.
- El Centro de identidades de AWS IAM (sucesor de AWS Single Sign-On) ayuda a crear o conectar con seguridad las identidades de la fuerza laboral y administrar el acceso de manera centralizada en las cuentas y aplicaciones de AWS. El Centro de identidades de IAM es el enfoque recomendado para la autenticación y autorización del personal en AWS, para organizaciones de cualquier tamaño y tipo.
- [AWS IAM Identity Center](https://aws.amazon.com/es/iam/identity-center/)

##### **Amazon Cognito**
- Gestión de identidades para aplicaciones.
- Permite agregar funciones de registro e inicio de sesión para los usuarios y controlar el acceso a sus aplicaciones web y móviles.
- Amazon Cognito brinda un almacenamiento de identidades que es escalable a millones de usuarios, respalda la federación de identidades social y empresarial, y ofrece funciones de seguridad avanzada para proteger a sus clientes y a su empresa.
- Es compatible con múltiples regulaciones de conformidad y se integra con los recursos de desarrollo de frontend y backend.
- [Amazon Cognito](https://aws.amazon.com/es/cognito/)

##### **AWS Directory Service**
- Gestión de Microsoft Active Directory.
- AWS Directory Service for Microsoft Active Directory, también conocido como AWS Managed Microsoft AD, permite que las cargas de trabajo compatibles con directorios y los recursos de AWS utilicen Active Directory administrado en AWS.
- [AWS Directory Service](https://aws.amazon.com/es/directoryservice/)

##### **AWS Resource Access Manager (RAM)**
- Servicio sencillo y seguro para compartir recursos de AWS.
- Permite compartir de forma segura los recursos entre cuentas de AWS, dentro de una organización o unidades organizativas (OU), y con roles y usuarios de IAM para tipos de recursos compatibles.
- [AWS Resource Access Manager (RAM)](https://aws.amazon.com/ram/)

##### **AWS Organizations**
- Gobierno y gestión centralizados de todas las cuentas de AWS.
- Permite crear nuevas cuentas de AWS sin cargo adicional.
- Con las cuentas de una organización, se pueden asignar recursos fácilmente, agrupar cuentas y aplicar políticas de gobernanza a cuentas o grupos.
- [AWS Organizations](https://aws.amazon.com/organizations/)

#### 2. Detección de seguridad
##### **AWS Security Hub**
- Centro unificado de seguridad y cumplimiento.
- Servicio de administración de la posición de seguridad en la nube que revisa las prácticas recomendadas de seguridad, agrega alertas y permite la corrección automatizada.
- [AWS Security Hub](https://aws.amazon.com/es/security-hub/)

##### **Amazon GuardDuty**
- Servicio gestionado de detección de amenazas.
- Servicio de detección de amenazas que supervisa de manera continua sus cargas de trabajo y cuentas de AWS para detectar actividades maliciosas y envía hallazgos detallados de seguridad para su visibilidad y resolución.
- [Amazon GuardDuty](https://aws.amazon.com/es/guardduty/)

##### **Amazon Inspector**
- Analizar la seguridad de las aplicaciones.
- Servicio de administración automatizada de vulnerabilidades que analiza continuamente las cargas de trabajo de AWS en busca de vulnerabilidades de software y exposición involuntaria a la red.
- [Amazon Inspector](https://aws.amazon.com/es/inspector/)

#### 3. Seguridad y protección de infraestructuras
##### **AWS Shield**
- Protección DDoS.
- Servicio de protección contra ataques DDoS que protege las aplicaciones que se ejecutan en AWS.
- [AWS Shield](https://aws.amazon.com/es/shield/)

##### **AWS WAF (Web Applic­ation Firewall)**
- Filtrar el tráfico web malicioso.
- Ayuda a protegerse de los exploits y bots web comunes que podrían afectar la disponibilidad, poner en riesgo la seguridad o consumir demasiados recursos.
- [AWS WAF (Web Applic­ation Firewall)](https://aws.amazon.com/es/waf/)

##### **AWS Firewall Manager**
- Gestión centralizada de reglas de cortafuegos.
- Servicio de administración de seguridad que permite la configuración y la administración centralizadas de reglas de firewalls en todas las cuentas y aplicaciones de AWS Organizations.
- A medida que se crean nuevas aplicaciones, Firewall Manager facilita la incorporación de nuevos recursos y aplicaciones a un esquema de cumplimiento aplicando un conjunto común de reglas de seguridad.
- [AWS Firewall Manager](https://aws.amazon.com/es/firewall-manager/)

#### 4. Seguridad y protección de datos
##### **Amazon Macie**
- Detecta y protege los datos confidenciales a escala.
- Servicio de privacidad y seguridad de datos que utiliza machine learning (ML) y correspondencia de patrones para detectar y proteger datos confidenciales de Amazon S3.
- [Amazon Macie](https://aws.amazon.com/es/macie/)

##### **AWS Key Management Service (AWS KMS)**
- Almacenamiento y gestión de claves.
- Permite crear, administrar y controlar claves criptográficas en las aplicaciones y en servicios de AWS.
- [AWS Key Management Service (AWS KMS)](https://aws.amazon.com/es/kms/)

##### **AWS CloudHSM**
- Almacenamiento de claves basado en hardware para el cumplimiento de la normativa.
- Permite administrar y acceder a sus claves en hardware con validación FIPS, protegidas con instancias HSM de propiedad del cliente y de inquilino único en su propia nube privada virtual (VPC).
- [AWS CloudHSM](https://aws.amazon.com/es/cloudhsm/)

##### **AWS Certificate Manager**
- Provisión, gestión e implantación de certificados SSL/TLS públicos y privados.
- Permite aprovisionar, administrar y desplegar certificados SSL/TLS públicos y privados para su uso con servicios de AWS y sus recursos conectados internos. ACM elimina el arduo proceso manual de compra, carga y renovación de los certificados SSL/TLS.
- [AWS Certificate Manager](https://aws.amazon.com/es/certificate-manager/)

##### **AWS Secrets Manager**
- Rotación, gestión y recuperación de secretos.
- Permite alternar, administrar y recuperar credenciales de bases de datos, claves de API y otros datos confidenciales durante su ciclo de vida.
- [AWS Secrets Manager](https://aws.amazon.com/es/secrets-manager/)

#### 5. Respuesta a incidentes de seguridad
##### **Amazon  Detective**
- Investigar posibles problemas de seguridad.
- Recopila datos de registro de manera automática a partir de sus recursos de AWS y utiliza el machine learning, el análisis estadístico y la teoría de gráficos para crear un conjunto de datos vinculados que puede usar para llevar a cabo fácilmente investigaciones sobre la seguridad más eficientes.
- [Amazon  Detective](https://aws.amazon.com/es/detective/)

#### 6. Conformidad
##### **AWS Artifact**
- Portal de autoservicio gratuito para el acceso bajo demanda a los informes de conformidad de AWS.
- Mejor recurso central para obtener información relacionada con el cumplimiento relevante para uno mismo. Proporciona acceso bajo demanda a informes de seguridad y cumplimiento de AWS e ISV que venden sus productos en AWS Marketplace.
- [AWS Artifact](https://aws.amazon.com/es/artifact/)

[![AWS](https://img.shields.io/badge/Inicio-447ac0?style=for-the-badge&label=&#8684;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Servicios_AWS/categories/AWS_Security_Identity_Compliance.md)
