# spring-boot-docker

**Instalacion**

Generar el jar con maven

`$ mvn install -DskipTests`

Ejecutar con docker compose

`$ docker-compose up -d`

Si se desea ejecutar el docker en otro proyecto, se deben copiar los acrhivos:

- Dockerfile
- docker-compose.yml

Y se debe cambiar el nombre del jar generado por el maven en el archivo: docker-compose.yml
 