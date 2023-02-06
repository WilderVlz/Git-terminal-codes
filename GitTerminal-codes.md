# global config


<!-- nos muestra la version de git actualmente instalada -->
* git version 2.32.0 (Apple Git-132)

<!-- nos permite crear un nombre de usuario en git -->
* git config-global user.name "wilder Ruiz"

<!-- nos permite agregar un correo electronico a git -->
* git config-global user.email wilderruizrpg@gmail.com

<!-- nos permite agregar nuestro editor de codigo en este caso Vscode -->
* git config --global core.editor "code --wait"

<!-- nos permite ver nuestro archivo de configuracion global dentro de nuestro editor de codigo -->
* git config-global-e


* git config-global core.autocrif input

* git config -h

* usage: git config [<options>]


---

# saltos de linea

<!-- En windows -->
 
<!-- El desarrollador de windows cuando quiera subir el codigo obligatoriamente va a tener que eliminar el CR || Agregarlo cuando quiera bajar codigo -->
 * carriage Return || CR

 * Line Feed || LF

* git config-global core.autocrif true



 <!-- En Linux || Mac -->
 
 * Line Feed || LF

* git config-global core.autocrif input


---

# comandos de git

* ls 
    * nos permite listar todos los archivos que tengamos dentro de el directorio en el que nos encontramos

* ls -a
    * nos permite mostrar todos los directorios y archivos que tenemos ocultos 


* pwd 
    * nos muestra el nombre del directorio en el que estamos actualmente con toda su ruta

* cd || nombre de directorio
    * nos permite movernos entre diretorios 

* cd ..
    * nos permite salirnos de un directorio

* mv || nombre archivo || nuevo nombre
    * nos permite cambiar el nombre de un archivo

* rm || nombre del archivo
    * nos permite eliminar un archivo

* mkdir 
    * nos permite crear directorios 

* code .
    * nos permite ejecutar la carpeta en la nos encontramos con nuestro editor de codigo

---

# iniciar proyectos

* git init
    * nos permite iniciar un repositorio vacio en nuestra carpeta

* git status 
    * nos permite ver el estado actual de nuestro repositorio
* git status -s
    * nos permite obtener el estado actual de nuestro repositorio de manera mas limpia y organizada
* git diff
    * nos permite ver los cambios realizados de manera mas grafica
* git diff --staged
    * nos permite ver los cambios realizados que ahora se encuentran en la etapa de stage


<!-- Para agregar varios archivos a la etapa de stage se debe poner el nombre de cada archivo separado por un espacio -->
* git add || nombre del archivo || .la extencion del archivo || .
    * nos permite agregar un archivos sin commits todavia
---

* *si se realizó un cambio en un archivo despues de agregarlo a la etapa de stage, se debe agregar nuevamente con **git add** a la etapa de stage.*
---
* git commit -m "aportes de los cambios realizados"
    * nos permite comprometer nuestros archivos

* git commit 
    * nos permite ejecutar nuestro editor de codigo y agregar las notas de los cambios desde alli

* git restore || nombre del archivo
    * nos permite recuperar un archivo eliminado anteriormente
* git mv || nombre archivo || nuevo nombre
    * esto nos permite cambiar directamente el nombre de un archivo en el stage 
* git log 
    * nos permite acceder a todo nuestro historial en el repositorio que hayamos creado
* git log --oneline 
    * nos permite ver el historial de nuestro repositorio de manera mas ordenada y resumida

* git branch
    * nos permite ver en que rama nos encontramos trabajando actualmente

* git checkout -b || nombre de la rama
    * nos permite crear una rama por fuera de la rama principal del proyecto 

* cat || nombre del archivo 
    * nos permite ver el contenido del archivo 

* git merge || nombre de la rama
    * nos permite traernos los cambios realizados en una rama secundaria a la rama pricipal

* git push -u origin || nombre de la rama
    * esto nos permite subir archivos desde una rama secundaria a gitHub