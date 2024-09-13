### Resumen del pdf "Virtualización con Máq. Vir. - Taller 2 - V1.20"

El taller 2 se enfoca en el manejo de usuarios, grupos y permisos en Linux, utilizando una Máquina Virtual en AWS (EC2). Los estudiantes aprenden a crear usuarios y grupos, modificar permisos sobre archivos, y monitorear espacio y procesos en ejecución.

- Acceder a la máquina virtual en AWS EC2
  - `$ ssh -i ./.ssh/labsuser.pem ubuntu@reemplazarIP`
  - `$ ssh -i labsuser.pem ubuntu@reemplazarIP`
  
- Crear usuarios y grupos en Linux
  - `$ cat /etc/passwd`
  - `$ useradd -m jperez`
  - `$ passwd jperez`
  - `$ userdel jperez`
  - `$ su jperez`
  - `$ id`
  - `$ groupadd estudiantes`
  - `$ groupadd tesistas`
  - `$ useradd -m jperez -g estudiantes -G tesistas`
  - `$ groupadd investigadores`
  - `$ usermod jperez -a -G investigadores`

- Cambiar permisos sobre archivos
  - `$ chmod 664 archivo`
  - `$ chmod 660 archivo`

- Monitorear espacio ocupado y procesos en ejecución
  - `$ top`
  - `$ htop`

- Continuar gestionando más configuraciones avanzadas de usuarios, grupos y permisos en Linux
