# spring-boot-docker

**Instalacion**

Generar el jar con maven

`$ mvn install -DskipTests`

Ejecutar con docker compose

`$ docker-compose up -d`

Este comando descarga la imagen y hace el build de docker y deja corriendo la aplicacion como demonio

Si se desea detener la aplicacion ejecutar

`$ docker-compose down`

Si se desea ejecutar el docker en otro proyecto, se deben copiar los acrhivos:

- Dockerfile
- docker-compose.yml

Y se debe cambiar el nombre del jar generado por el maven en el archivo: docker-compose.yml
 