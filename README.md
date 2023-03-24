# ACTUALIZACIÓN DE UBUNTU

## Proceso de instalación de la máquina virtual de Ubuntu 22.04

1. Descargamos desde la página de [Osboxes](https://www.osboxes.org/ubuntu/) el Ubuntu 22.04. Un vez instalado, abrimos VirtualBox y le damos a la opción "Crear" y le ponemos un nombre a la máquina, en este caso "Ubuntu 2".
![Actualización1](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_1.png)


2. Ponemos nombre a la máquina virtual, le configuramos una memoria base de 4096 MB.
![Actualización2](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_2.png)


3. Elegimos la opción de usar un disco virtual, en este caso el que hemos descargado anteriormente en Osboxes: Ubuntu 22.04.
![Actualización3](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_3.png)


4. El resumen que sale antes de crear la máquina es el siguiente:
![Actualización4](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_4.png)


5. Una vez creada la máquina virtual, la iniciamos con los usuarios y contraseñas siguientes:
* username: osboxes
* password: osboxes.org
* Root account password: osboxes.org
![Actualización5](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_5.png)


## Proceso de modificación del idioma.

1. Presionamos  el menú y después el icono de "Settings".
![Actualización6](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_6.png)


2. Dentro de "Settings", buscamos la opción "Language and Region" y seleccionamos el idioma español.
![Actualización7](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_7.png)

## Proceso de actualización desde la linea de comandos

1. En el escritorio de Ubuntu, vamos a la terminal haciendo clic en el icono del terminal en el panel o simplemente pulsando Ctrl+Alt+T.
![Actualización8](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_8.png)


2. En la terminal escribimos "sudo apt update", escribimos la contraseña de nuestro usuario.
![Actualización9](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_9.png)


3. Cuando el comando termine de ejecutarse, Ubuntu nos mostrará una lista de paquetes que pueden ser actualizados. Para ver estos paquetes escribimos "apt list --upgradable" y por último escibrimos "apt upgrade" para actualizar estos paquetes.
![Actualización10](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_10.png)


## Proceso de actualización desde el interfaz gráfico

1. Vamos al menú y buscamos "Actualización de software".
![Actualización11](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_11.png)


2. Una vez presionado el icono "Actualización de software", se comprobará si hay actualizaciones disponibles.
![Actualización12](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_12.png)


3. Reiniciamos el equipo para finalizar la instalación de las actualizaciones.
![Actualización13](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_13.png)


4. Por último, nos saldrá un mensaje que nos confirme que el sofware de nuestro equipo está actualizado.
![Actualización14](https://github.com/neusmartinez/Actualizacion-Ubuntu/blob/main/ACTUALIZAR_UBUNTU_14.png)
