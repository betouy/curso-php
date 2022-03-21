# curso-php
### Guia para enteder Docker y como desplegar un servicio web basado en php y mysql

Pre requisito:
- Etender docker
- Instalar docker
- Comprobar docker
- Instalar docker-compose

### Comprobar Docker
Tarea 1:
¿Que es docker?
https://docs.docker.com/get-started/


Instalar Docker engine:
- Instalar docker en windows:
  https://docs.docker.com/desktop/windows/install/

- Instalar docker en ubuntu:
  https://docs.docker.com/engine/install/ubuntu/

Instalar docker en mac:
https://docs.docker.com/desktop/mac/install/

Buscar imagen base:
https://hub.docker.com/search?type=image

Construir un dockerfile:

docker-compose
https://docs.docker.com/compose/install/

Comprobar que el servicio este funcionando
  docker ps
Y nos deberia de devolver:
  CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES

Ejecutar un container
  docker run alpine:latest  echo "Hola Mundo!"
Y nos deberia de devolver:
  Hola Mundo! 


## Tarea 1
Objetivo:

- Crear Dockerfile
- Ejecutar docker build
- Ejecutar docker run
- 
Ir al README.md de la tarea1
