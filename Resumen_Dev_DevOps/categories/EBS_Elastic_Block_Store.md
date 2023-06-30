## AWS Services
[![AWS](https://img.shields.io/badge/AWS_Services-ff9900?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/index.md)

### EBS - Elastic Block Store
[![AWS](https://img.shields.io/badge/EBS_Elastic_Block_Store-c08a44?style=for-the-badge&logo=amazon&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/categories/EBS_Elastic_Block_Store.md)

#### EBS - Elastic Block Store
- Almacenamiento de bloques para las instancias. Es un "Volumen" de almacenamiento de red para la instancia. Solo se puede usar en una 
instancia a la vez. Solo para una AZ. Persisten aunque termine la instancia.
- Características:
  - **AZ** >> Solo se puede usar en una Availability Zone.
  - **Capacity** >> Se define en GigaBytes y en IOPS.
  - **IOPS** (Input/output Operations Per Second) >> Rendimiento de los discos. Número de operaciones de entrada y salida por segundo.
  - **Root** >> Disco Duro para "arranque" (boot) de la instancia. Se pueden agregar más volumenes.
- Tipos:
  - **SDD** (Solid State Drive):
    - Cargas de trabajo transaccionales.
    - Rendimiento: IOPS - Soportan hasta 16TB-64TB.
  - **HDD** (Hard Drive Disk):
    - Cargas de trabajo intensivas.
    - Rendimiento: Gigabytes - Soportan hasta 16TB.  
- [AWS EBS](https://aws.amazon.com/es/ebs/)

[![AWS](https://img.shields.io/badge/Inicio-c08a44?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/AWS/blob/main/Resumen_Dev_DevOps/categories/EBS_Elastic_Block_Store.md)
