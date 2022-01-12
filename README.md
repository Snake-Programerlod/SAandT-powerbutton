# SAandT_pi-power-button-master
 Este repositorio tiene como finalidad realizar la instalacion de los scripts para implementar el boton de encendido y apagado de una raspberry con cualquier distribucion de linux.
 
# Instrucciones de instalacion.
 
  Primero se debera inciar la terminal de linux en la raspberry, ya sea desde la misma raspberry o en su defecto contandola por SSH utilizando putty o cualquier otro programa que permita este tipo de conexion.
  
  Posteriormente a ello se deberan ejecutar los siguientes pasos.
  
  1.- Clonar el repositorio, para la instalacion.

  git clone https://github.com/Snake-Programerlod/SAandT-powerbutton.git

  2.- Dar permisos a los archivos de instalacion y desinstalacion.

  chmod 744 ./SAandT-powerbutton/script/install
  
  chmod 744 ./SAandT-powerbutton/script/uninstall

  3.- Ejecutar el comando de instalacion

  ./SAandT-powerbutton/script/install

  4.- Reiniciar Raspberry.

  sudo reebot

  5.- Para desinstalar el codio del boton de encendido y apagado, ejecutar el siguiente comando

  ./SAandT-powerbutton/script/unistall

# Diagrama de conexion.

https://github.com/Snake-Programerlod/SAandT-powerbutton/blob/main/diagrams/pinout.png


