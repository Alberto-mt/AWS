## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/index.md)

### API Gateway

[![AWS](https://img.shields.io/badge/API_Gateway-447ac0?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/API_Gateway.md)

#### 1. Authorizers
- Internos de API Gateway
  - API HTTP de terceros
  - Para cross-account
- Lambda authorizers
#### 2. Básico
- API
  - HTTP
  - REST
  - Websocket (estilo chat)
- Centralizar y enrutar solicitudes (Facade)

#### 3. Deployments
- Canary deployment: un porcentaje del tráfico de API, entre 0,0 y 100,0 inclusive, para la versión canary
- Versionar API Gateway implica nuevos enpoinds, versionar lambdas NO cambia endpoints de API Gateway

#### 4. Flujo
- Method request --> Integration request
- Method response <-- Integration response
- Mapping templates permiten transformar payloads (con limitaciones), por ejemplo JSON a XML o viceversa
- Manipular cabeceras HTTP
  - X-Amz-Invocation-Type: Async
- Velocity template language

#### 5. Otros
- Edge-optimized API endpoint: Para juntar cosas de CloudFront con endpoints de API Gateway
- Cliente invalida cache con: Cache-Control: max-age=0
- Puedes usar lambdas para autenticadores a medida que devuelva una IAM policy y ID de usuario

#### 6. Tarifa
- Se pueden dar de alta API Keys para "cobrar" o "asignar coste"

[![AWS](https://img.shields.io/badge/API_Gateway-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/API_Gateway.md)
