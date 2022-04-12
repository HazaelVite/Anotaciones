# Visión general de las TI tradicionales
## Un servidor está compuesto de un
- Cómputo: CPU
- Memoria: RAM
- Almadenamiento: datos
- Base de datos: información almacenada de forma estructurada
- Redes: routers, switch, servidor DNS
- Terminología de IT
- Redes: cables, routers y servidores conectados unos a otros.
- Router: un dispositivo de red que reenvía paquetes de datos entre redes informáticas.
- Switch: toma un paquete y lo envía al servidor/cliente correcto en la red.
## Diseño de infraestructura “tradicional”
- Garage, con un servidor, dos servidores -> oficinas -> data centers
## Problemas del enfoque de IT Tradicional
- Renta
- Mantenimiento
- Reemplazar y agregar hardware
- Escalamiento limitado
- Contratar 24/7 para monitorear
- Desastres naturales

# ¿Qué es la computación en la nube?
Es la entrega bajo demanda de computacion, almacenamiento, db, aplicaciones y otros recursos de TI a traves de una plataforma de servicios
- Suministras el tipo y tamaño exactamente correctos de los recursos informáticos que necesitas.
- Puedes acceder al instante a todos los recursos que necesitas.
- Una forma sencilla de acceder a servidores, almacenamiento, bases de datos y un conjunto de servicios de aplicaciones: poder de computo, almacenamiento y bases de datos.
## Servicios que ya has usado en la nube
- mail Servicio de email en la nube. Pagas solo por tus emails almacenados (no infraestructura)
- Dropbox Servicio de almacenamiento en la nube. Originalmente se construyó en AWS
- Netflix Servicio de video en demanda. Construido en AWS.
## Tipos de modelos de computación en la nube
### Nube Privada
- Servicios de nube usados por una organización (no está expuesta al público).
- Control total.
- Seguridad para aplicaciones sensibles.
- Satisface necesidades comerciales específicas.
### Nube Pública
- Recursos propios en la nube y operados por proveedores de nube de terceros a través de internet. 
- Seis ventajas del cómputo en la nube.
- Google Cloud Platform (GCP), Azure, AWS
### Nube Híbrida
- Mantener algunos servidores en las instalaciones y extender otras capacidades en la nube.
- Control sobre activos sensibles en tu infraestructura privada
- Flexibilidad y rentabilidad de la nube pública.
### 5 características de la computación en la nube
- Autoservicio en demanda
- Amplio acceso a la red
- Múltiples inquilinos y agrupación de recursos
- Elasticidad y escalabilidad
- Servicio medido
### 6 ventajas de la computación en la nube
- Gastos de capital comercial (capex) sobre gastos operativos (opex)
- Economías de escala
- Dejar de adivinar la capacidad
- Incrementar la velocidad y la agilidad
- Dejar de gastar dinero en la ejecución
- Globalizar en minutos
### Problemas resueltos por la nuble
- Flexibilidad: cambia los tipos de recursos cuando sea necesario
- Rentabilidad: pagar sobre la marcha por lo que se usa
- Escalabilidad: acomodar cargas grandes al hacer que el hardware sea más fuerte o agregando nodos adicionales
- Elasticidad: capacidad de escalar cuando sea necesario
- Alta disponibilidad y tolerancia a fallos, crecer en todos los centros de datos
- Agilidad: desarrollar, probar y ejecutar rápidamente aplicaciones en la nube

# Ejemplos de los tipos de computación de la nube
## Infraestructura como servicio (IaaS)
- Azure
- Linode
- Digital ocean
- S2 AWS
## Plataforma como servicio (PaaS)
- Heroku
- Google App Engine
- AWS Elastic Beanstalk
## Software como servicio (SaaS)
- Amazon Rekognition
- Dropbox
- Zoom
- Gmail

# Super resumen de historia AWS
## Línea del tiempo de AWS
- 2002: Internamente lanzado
- 2003: La infraestructura de Amazon es una de sus principales fortalezas idea para comercializar
- 2004: Se lanza al público SQS
- 2006: Se relanza al público SQS, S3 y EC2
- 2007: Se lanza en Europa
- 2009: Se lanza RDS
- 2010: Se lanza route 53
- 2012: Se lanza DynamoDB
- The future… no lo sabemos
## AWS en números
- AWS tuvo $35.02 mil millones en ingresos anuales en 2019.
- AWS representó el 47% del mercado en 2019 (Microsoft es 2º con 22%)
- Mas de 1.000.000 de usuarios activos

# Seguridad e identidad
## Protección a Datos
- Amazon Macie: para descubrir y proteger sus datos sensibles
- AWS Key Management Service: almacena y administra claves de cifrado
- AWS CloudHSM: almacenamiento de claves basado en hardware y el cumplimiento normativo
- AWS Certificate Manager, provisiona, administra e implementa certificados de seguridad TSL y TLS
- AWS Secrets Manager: rotar, gestionar y recuperar secretos como contraseñas
## Protección de la infraestructura
- AWS Shield, para la protección de denegación de servicio
- AWS Web Aplication Firewall, (WAF) filtra el tráfico de sitios web maliciosos
- AWS Firewall Manager, administra las reglas del firewall de forma centralizada
## Detección de amenazas
- Amazon GuarDuty, detecta amenazas automáticamente
- Amazon Inspector, ayuda a analizar la seguridad de la aplicación
- Amazon config, registra y evalúa configuraciones de nuestros recursos
- Amazon CloudTrail, rastrea la actividad del usuario y el uso de las API
## Gestión de identidades
- AWS Identity and Access Management, (IAM) administra de forma segura el acceso a una cuenta, servicios y recursos
- AWS Inicio de sesión único: Implemente el acceso de sesión único (single sign on)
- AWS Cognito administra la identidad dentro de las aplicaciones, se puede hacer el inicio de sesiones moviles
- AWS Servicio de Directorio, implementa y administra un Active Directory Service
- AWS Organizaciones, para gobernar y administrar de forma centralizada en un mismo lugar

# IAM
- Nos ayuda a administrar quién puede acceder a qué en los servicios y recursos de tu cuenta en AWS
- Puedes crear usuarios y grupos
- Establecer permisos permitir o denegar el acceso a los recursos de AWS mediante el uso de políticas


