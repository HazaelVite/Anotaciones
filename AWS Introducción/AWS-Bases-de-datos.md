# Bases de datos en AWS
Colección ordenada de datos. Los datos se almacenan eletrónicamente y se acceden a ellos desde un sistema informático. AWS cuenta con más de quince motores de bases de datos diferentes de todos los tipos
- Seguros
- Altamente disponibles
## Bases de datos relacionales
- **Amazon Aurora:** Base de datos relacional compatible con MySQL y PostgreSQL creada para la nube.
- **Amazon Relational Database Service (Amazon RDS):** Es un servicio de bases de datos relacionales administrado para MySQL, PostgreSQL, MariaDB, Oracle BYOL o SQL Server.
	- Facilita la configuración, el uso y el escalado de varios motores de bases de datos
- **Amazon Redshift:** Utiliza SQL para analizar datos estructurados y semiestructurados en almacenamientos de datos, bases de datos operativas y lagos de datos, con hardware y machine learning diseñado por AWS para ofrecer rendimiento al mejor precio a cualquier escala
## Bases de datos clave-valor
- **Amazon DynamoDB:** Amazon DynamoDB es una base de datos de documentos y valores clave que ofrece un rendimiento de milisegundos de un solo dígito a cualquier escala. Es una base de datos duradera, multiregión, multimaestro y totalmente administrada con seguridad integrada, copia de seguridad y restauración, y almacenamiento en caché en memoria para aplicaciones a escala de Internet
	- Dirigidas aplicaciones de web de alto tráfico, sistemas de comercio electrónico y aplicaciones de juego.
	- Muy rápida y flexible para cualquier escala (NoSQL)
## Bases de datos en memoria
- **Amazon ElastiCahce:** Amazon ElastiCache es un servicio de almacenamiento de caché en memoria completamente administrado que admite casos de uso flexibles y en tiempo real. Se usa para almacenar en caché administración de sesiones, tablas de clasificación de juegos y aplicaciones Geo-Espaciales
	- ElastiCache para Memcached
	- ElastiCache para Redis
## Bases de datos de documentos
- **Amazon DocumentDB** (compatibilidad con MongoDB): Amazon DocumentDB es un servicio de base de datos de larga duración, de alta disponibilidad, rápida, escalable y completamente administrado para operar cargas de trabajo de MongoDB esenciales
- Gestión
	- Contenidos
	- Catálogos
	- Perfiles para usuarios

# RDS 
Servicio de base de datos relacional, puedes crear ejecutar y escalar bd relacionales en la nube
**¿Base de Datos Relacional?** Datos almacenados estan relacionados entre si. 
## Motores de base de datos en RDS
- MySQL
- MariaDB
- Microsoft SQL Server
- PostgreSQL
- Oracle
- Amazon Aurora
## Amazon RDS
- Facilita la configuración de las base de datos: Unos pocos clics en la consola de AWS
- Servicio completamente administrado
- Altamente escalable: Se puede usar en todas las zonas de disponibilidad y algunas bases de datos permiten crear replicas de otras bases de datos de solo lectura y permite mejorar el rendimiento.
- Copias de seguridad automaticas: Permite crear instantaneas y crear una nueva base de datos a partir de la instantanea. Si alguna falla se reemplaza automaticamente (quiza ni lo notes).
- Realmente rentable: Solo pagas por lo que usas, un cargo mensual, puedes detener e iniciar las instancias hasta 7 dias despues.

# Sobre DynamoDB
Es un poco diferente, se conoce como base de datos NoSQL, los datos se recuperar de una forma diferente a SQL.
- Base de datos de documentos de clave - valor.
- Rendimiento de milisegundos de un solo digito.
- Completamente administrado.
- Funciona en múltiples regiones.
- Seguridad, respaldo y restauración integrados.
- Admite picos de 20,000,000 de solicitudes por segundo.
- Realmente rentable
## Casos de uso
- Publicidad
- Juegos
- eCommerce
- Bancos
- Redes sociales
- Media Entertainment
- El propio internet

# ElastiCache
Amazon ElastiCache es un servicio de almacenamiento de caché en memoria completamente administrado que admite casos de uso flexibles y en tiempo real.
## Casos de uso:
- Acelera el rendimiento de las aplicaciones: Accede a los datos con una latencia de microsegundos y un alto rendimiento para que las aplicaciones funcionen rápido.
- Reduce la carga de la base de datos del backend: Almacena los datos en caché para reducir la exigencia sobre la base de datos del backend, lo que permite una mayor escalabilidad de la aplicación y reduce la carga operativa.
- Cree almacenes de datos de baja latencia: Almacena conjuntos de datos no duraderos en la memoria y admite aplicaciones en tiempo real con una latencia de microsegundos.
## Motores
- ElastiCache para Redis
- ElastiCache para Memcached