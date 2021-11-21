Host de la página web: https://pr1morfeo.000webhostapp.com/

# MORFEO21

Nuestro proyecto consiste en una página web para poder controlar las reservas de mesas en un restaurante. Nos ayuda a llevar un control del historial de las mesas que están disponibles, las reservadas, si hay incidencias...

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

Mira **Deployment** (Despliegue) para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_

Para poder visualizar nuestra página web tenemos que instalar XAMPP (https://www.apachefriends.org/es/index.html)

También necesitaremos con editor de texto como puede ser:
* **Visual Studio Code** - (https://code.visualstudio.com/)
* **Sublime Text** - (https://www.sublimetext.com/)


### Instalación 🔧
Una vez tengamos instalado XAMPP, debemos ir a la ruta donde tenemos instalado XAMPP y dirigirnos a la carpeta htdocs. En mi caso es: C:\xampp\htdocs

En la carpeta htdocs pegamos todos los archivos descargados de este repositorio.

Dentro del programa de XAMPP, activamos la opción de Apache para poder visualizar la página web y el de MYSQL para detectar la base de datos.

Editamos el archivo config.php rellenando los siguientes datos:

```
<?php 
 define("SERVIDOR","XXXX");
 define("USUARIO","XXXX");
 define("PASSWORD","XXXX");
 define("BD","XXXX");
```

Abrimos nuestor navegador, y en la barra de navegación introducimos lo siguiente: localhost/PR1
Esto nos llevará a la página web

## Despliegue 📦

Para subir la página web a un host nos registraremos en 000webhost(https://www.000webhost.com/)

Una vez registrados, iniciaremos sesión y vamos a Create New Site.

Añadimos el nombre que queremos ponerle a nuestro dominio.

Después, en la zona de configuración de la página vamos a la sección de File Manager.

Encontraremos un par de carpetas creadas.

En la carpeta *public_html* añadiremos todos los archivos de la página web.

Una vez añadidos todos los archivos, tendremos que añadir la base de datos. Para eso, nos dirigimos a Tools->Database manager.

Creamos la BD y le ponemos el nombre, el usuario y la contraseña deseados.

Después volvemos a la zona de los ficheros y entramos en config.php que está dentro de public_html->services.

Ahí configuramos el archivo según las credenciales que hemos indicado anteriormente

```
<?php 
    //Definimos parametros de la bbdd
 define("SERVIDOR","XXXX");
 define("USUARIO","XXXX");
 define("PASSWORD","XXXX");
 define("BD","XXXX");
```

Después ya tendriamos nuestra página web disponible!!

Para acceder a la página principal necesitamos iniciar sesión, por eso aquí abajo te dejo un usuario de prueba: 



**Usuario:** admin

**Contraseña:** admin


## Construido con 🛠️

* [PHP] - Lenguaje de programación
* [JS] - Para la validación de formularios
* [HTML & CSS] - Para el diseño y la forma del contenido 


## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/LauraFernandez18/PR1/wiki)

## Versionado 📌

Actualmente solo tenemos disponible la primera versión de nuestra página web. (https://github.com/LauraFernandez18/PR1/releases/tag/v1)

## Autores ✒️

* **Marc Díaz** - *PHP y BD* - [marcdcc](https://github.com/marcdcc)
* **Gerard Gómez** - *PHP y BD* - [100007217](https://github.com/100007217)
* **Laura Fernández** - *PHP, JS y CSS* - [laurafernandez18](https://github.com/LauraFernandez18)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/dannylarrea/MORFEO21/contributors) quíenes han participado en este proyecto. 


## Expresiones de Gratitud 🎁

* Agradecimientos a mis compañeros de proyecto por el gran trabajo en equipo y a los profesores por su ayuda ❤
