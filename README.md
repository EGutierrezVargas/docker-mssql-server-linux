# Instalación de MSSQL SERVER LINUX EN DOCKER #

#### Requerimientos ####

* [Docker](https://www.docker.com/)

#### Configurar el ambiente de desarrollo ####

* Clonar el repositorio. 
* Instalamos el ambiente de desarrollo: 
  `docker-compose up -d`
  
#### Comandos disponibles ####

* `docker-compose start` iniciar el ambiente de desarrollo.
* `docker-compose stop` detener el ambiente de desarrollo.
* `docker-compose down` detener y eliminar el ambiente de desarrollo.
* `docker ps -a` verificar que contenedor está corriendo.

### Restaurar un backup de una base de datos ###
docker cp archivoraiz nombredelcontenedor:ruta(/var/opt/mssql/)
* `docker cp Bk_dbname.bak mssql-server:/var/opt/mssql/backup.bak`
