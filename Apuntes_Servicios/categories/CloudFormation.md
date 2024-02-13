## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/index.md)

### CloudFormation
[![AWS](https://img.shields.io/badge/CloudFormation-c08a44?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/CloudFormation.md)

#### 1. Básico
- Un stack set de una region te permite crear en otras regiones con UNA sola plantilla (en una region)

#### 2. Estados
- Drift: El recurso ha cambiado "por fuera" pero no está reflejado en la plantilla
- Outdated: La plantilla cambio pero al aplicar falló por algún problema de configuración

#### 3. Hooks
- AWS::CodeDeploy::BlueGreen hook

#### 4. Retención del entorno previo
- No hay opcion para retener entornos X tiempo
- En in-place espera hasta 1 hora a ver si la instancia EC2 está ok

#### 5. Target Group
- No confundir con el Deployment Target de CodeDeploy!!
- Se aplica a:
  - Application Load Balancer
  - Gateway Load Balancer
  - Network Load Balancer
- El target group puede ser:
  - Lambda
  - EC2
  - ECS

[![AWS](https://img.shields.io/badge/CloudFormation-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/CloudFormation.md)
