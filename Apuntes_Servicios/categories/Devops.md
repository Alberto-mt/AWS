## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/index.md)

### Devops
[![AWS](https://img.shields.io/badge/Devops-c044b8?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/Devops.md)

#### 1. CodeBuild
- Si quieres evitar commits chungos sobre ramas ANTES de subir, tienes que hacerlo con el CodeBuild agent EN local (no vale un job en el cloud a secas).
- En GitHub puedes configurar un "webhook" para empujar a CodeBuild cuando hay commits

#### 2. CodeCommit

#### 3. CodeDeploy
- Conservar el entorno anterior en green-blue con terminationWaitTimeInMinutes.
- Deployment Target:
  - CloudFormationTarget.
  - ECSTarget.
  - InstanceTarget.
  - LambdaTarget.
- Deployment Types:
  - In Place: Va instancia a instancia (de EC2).
  - Green Blue: Pequeñas variaciones si es EC2, lambda o CloudFormation.

#### 4. CodePipeline
- Básico
  - Puede pulear periodicamente de CodeCommit e iniciar un pipeline.
  - Obligatorio para aprobación manual en devops.
- Deploy providers
  - Casi todo menos Lambda y EC2:
    - Pero puedes poner CloudFormation y que CF despliegue en esos destinos.
- Procesos típicos
  - Build.
  - Deploy.
  - Pull de código:
    - Puede hacer Poll SCM con un demonio.
  - Test
- Subdivisiones
  - Actions:
    - runOrder es un parametro numérico que permite paralelizar acciones dentro del stage.
  - Stages:
    - No puedes hacer opcionales stages sin usar lambda u otra cosa.

[![AWS](https://img.shields.io/badge/Devops-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Apuntes_Servicios/categories/Devops.md)
