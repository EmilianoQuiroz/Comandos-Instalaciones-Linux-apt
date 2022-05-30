# Comandos-Instalaciones-Linux-apt
Comandos para la instalación  de programas en Linux (Cualquier distribución basada en debían).
---------------------------------------------------------------------------------------------------------------------------------------------------------
# COMANDOS IMPORTANTES:

¿Que es lo primero que debo hacer en Linux?

Actualizacion e instalacion de paquetes:

+ $sudo apt-get update -->Actualizacion de paquetes.
+ $sudo apt-get upgrade -->Instalacion de los paquetes.
 
Versiones de programas:

+ "Nombre del programa" --version -->Sirve para saber que version del programa indicado tenemos instalada, en caso de que lo tengamos.

¿Como visualizar el consumo de memoria RAM?

- $free -h -->Este comando nos detallara la capacidad de nuestra memoria ram y cuanto estamos consumuendo.

¿Como visualizar informacion del sistema?

- $neofetch -->Este comando nos detalla toda la informacion del sistema. 

En caso de no tenerlo instalado puedes hacerlo con el suguiente comando: 

+ $sudo apt install neofetch

Permisos de super usuaio

+ $su -->Luego de ejecutar este comando nos pedira la constraseña de superusuario y listo! ya tenemos permisos de administrador

Creacion o modificacion de contraseña.

+ $passwd -->Este conmando nos permite cambiar nuestra contraseña de superusuario o crearla en el caso de que no la tengamos


---------------------------------------------------------------------------------------------------------------------------------------------------------
# Instalaciones Frecuentes:
---
+ Instalacion de la terminal "terminator".

	+ $sudo apt-get install terminator -->Es una terminal que permite otras funcionalidades, tales como tener dos terminales en simultaneo.
---
# Google Chrome:
+ PASO 1:
   Ir a la pagina de descargas de Google Chrome: https://www.google.com/intl/es/chrome/?brand=CHBD&gclid=CjwKCAjwsJ6TBhAIEiwAfl4TWNj2J1ialnX6Eb-qQQRiL2-PlxpK13Dna77kvGzELQ3P_a1NxCvDExoChz8QAvD_BwE&gclsrc=aw.ds
+ PASO 2: 
   Abrir una terminal en la ubicacion del archivo descargado.
+ PASO 3:
   Ejecutar los siguientes comandos:
   
   + $ ls --> Para mostrar el archivo dentro de la carpeta.
   + $ sudo dpkg -i "nombre del paquete" --> Para instalar el paquete indicado.
   + Y listo! Se instalaran las dependencias y estaria todo listo para que puedas utilizar Google Chrome!.
---
# Git: 
+ PASO 1:
	- Ejecutar en consola: 
   		- $sudo apt install git
---
# Visual Studio Code:
   - El primer paso es descargar el paquete .deb del enlace de descarga de Visual Studio Code
   https://code.visualstudio.com/docs/?dv=linux64_deb
   - Luego debemos ubicar el paquete en la carpeta en la que se encuentra para abrir una terminal en esa ubicacion.
   - Se deben ejecutar el siguiente comando:
   - $ sudo apt install ./"Nombre del paquete"
   - De esta manera se instalaran todas las dependencias del paquete.
---
# XAMPP (Debian):
+ Instalacion:
   -
+ ¿Como acceder desde la consola?
   - $dir
   - $cd Descargas
   - $ls
   - $cd /opt
   - $ls
   - ./manager-linux-x64.run
   - Automaticamente se abrira la interfaz de XAMPP
--- 
# Node js: 
---
# Intellij IDE: 
   - El primer paso es ir al siguiente link de descarga: 
   https://www.jetbrains.com/es-es/idea/download/download-thanks.html?platform=linux
   - El segundo paso es ubicar el archivo en la carpeta y descomprimir el archivo en esa ubicacion.
   - El tercer paso es entrar a la carpeta descomprimida y abrir una terminal en la carpeta "bin".
   - El segundo paso es ejecutar el siguiente comando: 
    +  ./idea.sh
   - Esto nos abrira una ventana que nos ŕegunta si estamos de acuerdo con las politicas de Intellij IDEA, luego de dar a aceptar ya podremos usar el          IDE.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---
# Problemas frecuentes.
---
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Instalaciones que ya incluje

+ Python3 (V 3.8.10)

---------------------------------------------------------------------------------------------------------------------------------------------------------

TODOS ESTOS COMANDOS E INSTALACIONES APLICAN A LAS DISTRIBUCIONES DEBIAN, UBUNTU, LUBUNTU, KUBUNTU, SUBUNTU, LINUX LITE, KALI LINUX Y LINUX MINT.

---------------------------------------------------------------------------------------------------------------------------------------------------------
