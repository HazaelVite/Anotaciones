# Cómputo dentro de AWS
## Instancias
### Elastic Computed Cloud (EC2)
- Amazon EC2: Maquinas virtuales seguras y redimensionables
- Amazon EC2 Spot: Cargas de trabajo tolerante a fallas, por hasta el 90% del precio normal
- Amazon EC2 AutoScallin: agregar o eliminar la capacidad informática para satisfacer tus necesidades en demanda
- Amazon EC2 LightSail: (Plataforma en la nube para crear una aplicación o un sitio web)
## Contenedores
- Amazon Elastic Container Services (ECS): servicio para correr contenedores, confiables y escalables
- Amazon Elastic Container Registry (ECR): servicio para almacenar, administrar, e implementar imágenes de contenedores
- Amazon Elastic Kubernetes Service (EKS): servicio de kubernetes
## Serverless
- Amazon Lambda: servicio que nos permite ejecutar código sin servidores
## Edge
### Servicios de borde
- Amazon Outposts: Ejecutar los servicios de AWS en nuestros propios servidores en lugar de Amazon
- Amazon Snow Family: Servicio que te permite tener una gran cantidad de datos, tiene discos desde el tamaño de un disco duro portátil hasta un semirremolque completo lleno de discos de almacenamiento. La familia de Snow tiene una solución útil que tenga que pasar a la nube
- AWS Wavelength: Servicio que permite acceder a los servicios AWS desde dispositivos 5G sin tener que acceder por internet (muy rápido)
- VMWare AWS: Migrar carga de trabajo de VMWare
- AWS Local Zones: Ejecutar las aplicaciones a una latencia más cerca de los usuarios finales

## EC2 Elastic Compute Cloud
- Permite alquilar computadoras virtuales.
- Diferentes tipos de EC2 con diferente CPU (para alto rendimiento), RAM y almacenamiento (para grandes cargas de trabajo).
- Instancias optimizadas en computación (para leer y escribir muy rápido)- 
- El sistema de pago más común: paga por hora o segundo, dependiendo el tipo de instancia
- Ejemplo de precios
```
24 * 0.10 = $2.40
```
### Pagas lo mismo por
- 24 tareas de 1h en una instancia
- 24 instancias de 1h
### Opciones y precios bajo demanda
- Nombre de la instancia: t3.nano (baja potencia)
- Especificaciones: 2 vCPU’s, 0.5 GiB RAM
- Precio: $0.0052/hour
- Nombre de la instancia: t3.xlarge
- Especificaciones: 4 vCPU’s, 16 GiB RAM
- Precio: $0.1664/hour
- Nombre de la instancia: c6g.8xlarge
- Especificaciones: 32 vCPU’s, 64 GiB RAM
- Precio: $1.088/hour
- Nombre de la instancia: X1e.xlarge
- Especificaciones: 128 vCPU’s, 3904 GiB RAM, 2x 1920 GB SSD
- Precio: $26.688/hour

# Aprendiendo sobre Lambda
Supongamos que queremos tener una aplicacion que diariamente envia un mensaje en twitter.
## Requisitos
- API twitter, EC2, SO Linux, lenguajde de programación Python
- Network, Hard drive, Actualizaciones
## AWS Lambda
- Servicio informático sin servidor
- Ejecuta su código en respuesta a eventos.
## Caso de uso
- Subes una imagen y el lamba crea varias resoluciones
## Facturacion por milisegundos
- El precio depende del uso de RAM
- 128MB RAM x 30M eventos por mes.
- $11.63 al mes