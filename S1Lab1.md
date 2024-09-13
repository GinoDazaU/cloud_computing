### Resumen del pdf "Virtualización con Máq. Vir. - Taller 1 - V1.20"

El taller 1 se enfoca en la creación y manejo de una Máquina Virtual en AWS (EC2), proporcionando una introducción a AWS Academy y enseñando a los estudiantes a acceder y manejar la máquina virtual, practicar comandos básicos de Linux y ejecutar programas en diversos lenguajes de programación.

- Crear máquina virtual en AWS EC2
- Acceder a la máquina virtual

  - `$ ssh -i ./.ssh/labsuser.pem ubuntu@reemplazarIP`
  - `$ ssh -i labsuser.pem ubuntu@reemplazarIP`
- Comandos basicos de Linux
  - `ls -la`
  - `man ls`
  - `pwd`
  - `mkdir lab5`
  - `cd lab5`
  - `pico holamundo.cpp`
  - `cp holamundo.cpp /home/ubuntu/lab5`
  - `mv holamundo.cpp hola.cpp`
  - `cat hola.cpp`
  - `rm hola.cpp`
  - `clear`
  - `exit`
  - `sudo shutdown -r now`
  - `sudo shutdown -h now`

- Ejecutar programas en C++, Python y Node.js
  - `$ g++ -o hola.exe holamundo.cpp`
  - `$ ./hola.exe`
  - `$ python3 holamundo.py`
  - `$ node holamundo.js`

- Continuar ejecutando más comandos avanzados en Linux
