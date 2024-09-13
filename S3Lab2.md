### Resumen del pdf "Contenedores - Taller 2 - V1.10"

Este taller se centra en aprender a subir una imagen de contenedor a **hub.docker.com** y desplegar dicho contenedor en otras computadoras o máquinas virtuales. También se proponen ejercicios adicionales para practicar con otras imágenes y configuraciones.

- Subir imagen a hub.docker.com
  - `$ docker login -u gcolchado`
  - `$ docker tag api-students gcolchado/api-students`
  - `$ docker push gcolchado/api-students`
  - `$ docker logout`

- Desplegar contenedor en otras computadoras
  - `$ docker run -d -p 8000:8000 gcolchado/api-students`
  - `$ docker run -d -p 8000:8000 gcolchado/api-students`

- Ejercicio propuesto
  - Subir imagen **websimple** a **hub.docker.com** y desplegar el contenedor en otras computadoras en el puerto 8080.
  - Crear y subir imagen **webplantilla** a **hub.docker.com**, desplegar el contenedor en otras computadoras en el puerto 8081.

- Continuar con el despliegue de contenedores y la gestión de imágenes en Docker.
