## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/index.md)

### Cognito
[![AWS](https://img.shields.io/badge/Cognito-c08a44?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/Cognito.md)

#### 1. Pools
- Si usa SAML externo, y va a ir a servicios AWS no tiene sentido el user pool
- User Pools Authenticates and Identity Pools Authorizes (sobre otros servicios de AWS)
- Si autentica a usuarios NO de la organización es user pool (si luego quiere ir a servicios a AWS necesitara credentials de un Identity Pool)

#### 2. Post authentication Lambda trigger

#### 3. Variables con metadatos
- sub es el sujeto logado
- aud es "The user pool app client that authenticated your user."
- "Amazon Cognito identity" se puede usar para especificar prefijo de ruta accesible de S3 en una condicion de IAM

[![AWS](https://img.shields.io/badge/Cognito-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/Cognito.md)
