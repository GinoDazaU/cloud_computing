### Resumen del pdf "Virtualización con Máq. Vir. - Taller 3 - V1.10"

Este taller está centrado en la publicación de páginas web estáticas y la implementación de APIs REST en una Máquina Virtual en AWS (EC2). Los estudiantes aprenderán a crear y gestionar páginas web simples y plantillas, así como implementar APIs REST con Python y Node.js, además de apagar la máquina virtual de forma segura.

- Acceder a la máquina virtual en AWS EC2
  - `$ ssh -i ./.ssh/labsuser.pem ubuntu@reemplazarIP`
  - `$ ssh -i labsuser.pem ubuntu@reemplazarIP`

- Página web estática simple
  - `$ sudo git clone https://github.com/reemplazar/websimple.git`

- Página web estática plantilla
  - `$ sudo git clone https://github.com/reemplazar/webplantilla.git`

- API REST con Python
  - `$ git clone https://github.com/reemplazar/api-students.git`
  - `$ pip3 install flask`
  - `$ python3 db.py`
  - `$ python3 app.py`

- API REST con Node.js (propuesto)
  - **Buscar ejemplo en internet e implementarlo**
  - **Abrir puerto necesario en la máquina virtual**
  - **Crear la base de datos SQLite**
  - **Ejecutar la API y probar con Postman**

- Apagar la máquina virtual
  - `$ sudo shutdown -h now`
  - **O detener la instancia desde la consola de AWS**

- Continuar con la gestión y desarrollo de APIs y sitios web estáticos en AWS
