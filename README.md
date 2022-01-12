# SAandT Power Button
 Este repositorio tiene como finalidad realizar la instalación de los scripts para implementar el botón de encendido y apagado de una raspberry con cualquier distribución de Linux.
 
# Instrucciones de instalacion.
 
  Primero se debera iniciar la terminal de Linux en la raspberry, ya sea desde el mismo dispositivo o en su defecto conectándola por SSH utilizando PUTTY o cualquier otro programa que permita este tipo de conexión.
  
  Posteriormente a ello se deberán ejecutar los siguientes pasos.
  
  1.- Clonar el repositorio, para la instalación.

  `git clone https://github.com/Snake-Programerlod/SAandT-powerbutton.git`

  2.- Dar permisos a los scripts de instalación y desinstalación.

  `chmod 744 ./SAandT-powerbutton/script/install`
  
  `chmod 744 ./SAandT-powerbutton/script/uninstall`

  3.- Ejecutar el comando de instalación

  `./SAandT-powerbutton/script/install`

  4.- Reiniciar Raspberry.

  `sudo reebot`

  5.- Para desinstalar el código del botón de encendido y apagado, ejecutar el siguiente comando

  `./SAandT-powerbutton/script/unistall`

# Materiales y diagrama de conexión.

 Para realizar este tutorial es necesario contar con un botón normalmente abierto, ósea que al momento de presionarlo cierre el circuito entre el pin 5 y 6 de nuestra raspberry como se muestra en el siguiente diagrama.

![Connection Diagram](https://wiki.batocera.org/_media/batocera_pin56.png)

> Agradecimientos a los desarrolladores iniciales de este proyecto SilentNightx y CrashCr
