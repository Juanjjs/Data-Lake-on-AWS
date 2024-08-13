# Data-Lake-on-AWS
Implementación de un Data lake mediante Amazon Athena, AWS Glue (crawlers), Amazon S3, AWS Lake Formation, entre otros.

Un lago de datos o Data Lake, consta de las siguientes etapas:
- Configurar el almacenamiento
- Mover los datos
- Preparar y catalogar los datos
- Definir las políticas de seguridad
- Hacer que los datos estén disponibles para su consumo

# Etapa 1. Almacenamiento
El eje central de un Data Lake es Amazon S3. Allí, se almacena toda la información mediante el uso de buckets y carpetas.

# Etapa 2. Ingesta
Mediante Amazon Kinesis Data Firehose o inyección directa de los datos por consola de AWS.

# Etapa 3. Catálogo
Mediante consultas básicas de SQL en la interfaz de Amazon Athena.

# Etapa 4. Políticas de acceso
Es posible configurar Amazon Cognito y el servicio de usuario IAM.

# Etapa 5. 

