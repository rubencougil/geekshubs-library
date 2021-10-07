# 📚 GeeksHubs Library Demo App

![Pull Request](https://github.com/rubencougil/geekshubs-library/workflows/Pull%20Request/badge.svg)
![Publish](https://github.com/rubencougil/geekshubs-library/workflows/Publish/badge.svg)

API REST para gestionar libros.

## Cómo funciona

La API se ha implementado con una pequeña aplicación en Go. Para persistir la información utiliza una Base de Datos MySQL.
Hay un archivo `docker-compose` que al ejecutarse levantará dos servicios:

* Aplicación `:8080`
* Base de Datos MySQL `:3306`

Si necesitas realizar cambios en la aplicación y quieres lanzarla directamente en tu máquina local necesitas instalar el intérprete de Go y después ejecutar: 

`make run`

* **IMPORTANTE:** Fíjate en la configuración de conexión de la Base de Datos al principio del archivo `Makefile`

y para lanzar los tests

`make test`

## API 

La documentación de la API se encuentra [aquí](https://documenter.getpostman.com/view/255227/TVejgpWn)
