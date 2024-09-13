### Resumen del pdf "Virtualización con Máq. Vir. - Taller 4 - V1.00"

Este taller introduce el concepto de "Infraestructura como código" (IaC) y el uso del servicio AWS CloudFormation para automatizar la creación y eliminación de máquinas virtuales en AWS EC2. Los estudiantes realizarán ejercicios para crear máquinas virtuales, implementar sitios web simples, y eliminar estas instancias usando la consola web y la AWS CLI.

- Crear una máquina virtual con AWS CloudFormation
  - `$ aws cloudformation create-stack --stack-name "nombre-de-la-pila" --template-body file://ruta-del-archivo-plantilla.yaml`

- Crear una máquina virtual con websimple y webplantilla
  - `$ aws cloudformation create-stack --stack-name "crear-mv-con-webs" --template-body file://plantilla_crear_mv_con_webs.yaml --parameters ParameterKey=InstanceName,ParameterValue="MV con 2 Webs"`

- Eliminar máquinas creadas
  - `$ aws cloudformation delete-stack --stack-name "nombre-de-la-pila"`

- Crear y eliminar una pila desde AWS CLI
  - `$ aws cloudformation create-stack --stack-name "crear-mv-con-webs" --template-body file://plantilla_crear_mv_con_webs.yaml --parameters ParameterKey=InstanceName,ParameterValue="MV con 2 Webs"`
  - `$ aws cloudformation describe-stacks --stack-name "crear-mv-con-webs"`
  - `$ aws cloudformation delete-stack --stack-name "crear-mv-con-webs"`
  - `$ aws cloudformation describe-stacks --stack-name "crear-mv-con-webs"`

- Continuar con la automatización y gestión de infraestructura en AWS usando IaC
