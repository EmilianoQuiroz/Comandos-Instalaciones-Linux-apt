# Comandos-Instalaciones-Linux-apt

![image](https://user-images.githubusercontent.com/78452543/221329296-33713bb2-5b28-4068-a43b-0d69afabe022.png)

Comandos necesarios para sobrevivir en Linux (Cualquier distribución basada en debian).
---------------------------------------------------------------------------------------------------------------------------------------------------------
## Comandos basicos:

¿Que es lo primero que debo hacer en Linux?

+ Actualizacion e instalacion de paquetes:

		 $sudo apt-get update -->Actualizacion de paquetes.
		 $sudo apt-get upgrade -->Instalacion de los paquetes.
 
+ Versiones de programas:

		"Nombre del programa" --version -->Sirve para saber que version del programa indicado tenemos instalada, en caso de que lo tengamos.

+ ¿Como visualizar el consumo de memoria RAM?

		$free -h -->Este comando nos detallara la capacidad de nuestra memoria ram y cuanto estamos consumuendo.

+ ¿Como visualizar informacion del sistema?

		$neofetch -->Este comando nos detalla toda la informacion del sistema. 

+ En caso de no tenerlo instalado puedes hacerlo con el suguiente comando: 

		$sudo apt install neofetch

+ Permisos de super usuaio

		$su -->Luego de ejecutar este comando nos pedira la constraseña de superusuario y listo! ya tenemos permisos de administrador

+ Creacion o modificacion de contraseña.

		$passwd -->Este comando nos permite cambiar nuestra contraseña de superusuario o crearla en el caso de que no la tengamos
+ ¿Como saber en que ruta de archivos me encuentro?

		$pwd -->Este simple comando nos indica la ruta de archivos en la que nos encontramos
+ Distado de carpetas y archivos del directorio en el que me encuentro

		$ls -->Listado de archivos y carpetas
+ Change directory
		
		$cd "Nombre de la carpeta" -->Este comando nos permite cambiar de carpeta.
		$cd .. -->Nos devuelve a la carpeta anterior.
+ Creacion de carpetas.
		
		$mkdir "Nombre de la nueva carpeta" -->Este comando nos permite crear un nuevo directorio en la ruta indicada.
+ ¿Como mover una carpeta?

		$mv /rutaactualdela/carpetaquequiero/mover /rutaalaque/quiero/moverla/carpeta
+ ¿Como copiar una carpeta y pegarla en otra direccion?

		$cp -R /rutaactualde/lacarpeta /rutaendondequiero/pegarlacarpeta
+ ¿Como eliminar una carpeta?
		
		$rm -R /rutaactualde/lacarpeta 
+ ¿Como visualizar el manual de linux?
		
		$man -->Este comando nos lleva al manual de linux junto con todas sus especificaciones
		
---------------------------------------------------------------------------------------------------------------------------------------------------------
# Instalaciones Frecuentes:
---
+ Instalacion de la terminal "terminator".

			$sudo apt-get install terminator -->Es una terminal que permite otras funcionalidades, tales como tener dos terminales en simultaneo.
---
# Google Chrome:
+ PASO 1:
   Ir a la pagina de descargas de Google Chrome: https://www.google.com/intl/es/chrome/?brand=CHBD&gclid=CjwKCAjwsJ6TBhAIEiwAfl4TWNj2J1ialnX6Eb-qQQRiL2-PlxpK13Dna77kvGzELQ3P_a1NxCvDExoChz8QAvD_BwE&gclsrc=aw.ds
+ PASO 2: 
   Abrir una terminal en la ubicacion del archivo descargado.
+ PASO 3:
   Ejecutar los siguientes comandos:
   
   	$ ls --> Para mostrar el archivo dentro de la carpeta.
   	$ sudo dpkg -i "nombre del paquete" --> Para instalar el paquete indicado.
   + Y listo! Se instalaran las dependencias y estaria todo listo para que puedas utilizar Google Chrome!.
---
# Git: 
+ PASO 1:
- Ejecutar en consola
	
			$sudo apt install git
---
# Visual Studio Code:
   - El primer paso es descargar el paquete .deb del enlace de descarga de Visual Studio Code
   https://code.visualstudio.com/docs/?dv=linux64_deb
   - Luego debemos ubicar el paquete en la carpeta en la que se encuentra para abrir una terminal en esa ubicacion.
   - Se deben ejecutar el siguiente comando:
   			
			$ sudo apt install ./"Nombre del paquete" -->De esta manera se instalaran todas las dependencias del paquete.
---
# XAMPP (Debian):
+ Instalacion:
   -
+ ¿Como acceder desde la consola?
   		
		$dir
   		$cd Descargas
   		$ls
   		$cd /opt
   		$ls
   		./manager-linux-x64.run
   
   - Automaticamente se abrira la interfaz de XAMPP
--- 
# Node js: 

- Básicamente la instalación de node js es con la herramienta de NVM 
- Actualizamos los paquetes: 

		 $sudo apt update
		 $sudo apt upgrade
- Instalamos curl para poder instalar NVM
		
		$sudo apt install curl 
- Revisión de secuencia de comandos: 

		$curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh
- Descargamos y ejecutamos 
		
		$curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
- Obtenemos secuencia de comandos 
		
		$source ~/.bashrc
- Preguntamos versiones

		$nvm list-remote
- Instalamos la versión deseada 

		$nvm install vx
- Revisamos la versión instalada
	
		$nvm list
		$sudo apt install npm
---
# React Native CLI.

### Requisitos previos:
- Visual Studio Code
- Android Studio (para usar su emulador)
- Node js
- npm
- Java (en este caso la version 8)
	
		sudo apt-get install openjdk-8-jdk

+ Instalacion de React Native CLI: Ejecutar el siguiente comando en la terminal.

		npm install -g react-native-cli

###
---
# Docker
---
# Intellij IDE: 
   - El primer paso es ir al siguiente link de descarga: 
   https://www.jetbrains.com/es-es/idea/download/download-thanks.html?platform=linux
   - El segundo paso es ubicar el archivo en la carpeta y descomprimir el archivo en esa ubicacion.
   - El tercer paso es entrar a la carpeta descomprimida y abrir una terminal en la carpeta "bin".
   - El segundo paso es ejecutar el siguiente comando: 
   		
			+  ./idea.sh
---
# Error de reconocimiento de la libreria math para programar en C
			
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
