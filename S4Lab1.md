### Resumen del pdf "Contenedores - Taller 3 - V1.10"

Este taller está orientado a aprender a crear y ejecutar una aplicación multi contenedor usando **Docker Compose**. Los estudiantes trabajarán con múltiples servicios en contenedores y analizarán los archivos de configuración como `compose.yml` y los **Dockerfile**. Al finalizar, los estudiantes podrán desplegar una aplicación que consiste en una página web y una API REST.

- Analizar la aplicación multi contenedor.
- Crear un repositorio en GitHub y subir los archivos `compose.yml` y **Dockerfile**.
  - `$ git clone https://github.com/reemplazar/compose-repo.git`

- Ejecutar la aplicación multi contenedor.
  - `$ cd /home/ubuntu/compose`
  - `$ docker compose up -d`

- Analizar imágenes y contenedores en ejecución.
  - `$ docker images`
  - `$ docker ps`
  - `$ docker compose logs`

- Probar la aplicación con Postman:
  - `http://IP_DIRECCION:8080` (página web)
  - `http://IP_DIRECCION:8000/students` (API)

- Detener la aplicación multi contenedor.
  - `$ docker compose down`

- Ejercicio propuesto:
  - Agregar una nueva página web plantilla en el puerto 8081 a la aplicación multi contenedor y probarla.

- Continuar trabajando con aplicaciones multi contenedor y **Docker Compose**.
