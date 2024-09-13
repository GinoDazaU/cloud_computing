### Resumen del pdf "Contenedores - Taller 1 - V1.10"

Este taller se enfoca en la instalación y uso básico de Docker en Ubuntu. Los estudiantes aprenderán a instalar Docker, ejecutar comandos básicos para la gestión de contenedores, crear una imagen de un contenedor para una página web y una API REST con Python, además de detener y gestionar contenedores.

- Instalar Docker en Ubuntu
  - `$ docker -v`

- Comandos básicos de Docker
  - `$ docker build`
  - `$ docker run`
  - `$ docker images`
  - `$ docker ps`
  - `$ docker stop`
  - `$ docker start`
  - `$ docker rm`
  - `$ docker exec`

- Contenedor de página web
  - `$ docker build -t websimple .`
  - `$ docker run -d -p 8080:80 websimple`
  - `$ docker stop CONTAINER ID`
  - `$ docker ps`
  - `$ docker start CONTAINER ID`
  - `$ docker rm CONTAINER ID`

- Contenedor de API REST Python3
  - `$ docker build -t api-students .`
  - `$ docker run -p 8000:8000 api-students`
  - `$ docker run -d -p 8000:8000 api-students`
  - `$ docker exec -it CONTAINER_ID /bin/bash`

- Continuar con el uso de Docker para crear y gestionar contenedores de servicios web y APIs
