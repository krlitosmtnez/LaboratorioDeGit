# Prueba de laboratorio Git

Este archivo readme repasa los pasos realizados en la prueba de laboratorio centrada en Git. Todo el proyecto se ha realizado desde Visual Studio Code.

* Creación de carpeta LABORATORIOGIT en local.

* Iniciamos Visual Studio Code, y abrimos un nuevo proyecto con dicha carpeta como referencia.

* Desde el terminal integrado en Visual Studio Code navegamos hasta la carpeta e iniciamos el repositorio Git con el comando **git init**

* Creación de archivo index.html para que el repositorio tenga algo de contenido.

* Creación del repositorio en GitHub.

* Copiamos la dirección SSH para conectar el proyecto con el repositorio almacenado en GitHub.

* Procedemos con la conexión ejecutando el comando **git remote add origin git@github.com:krlitosmtnez/LaboratorioDeGit.git**

* Ahora hay que subir los archivos al servidor con el comando Push.

* Primero, commiteamos en local para tener todo preparado con **git add .** Y luego **git push -u origin master** para subir la primera versión a GitHub

* Creación de una nueva rama con **git branch development**

* Modificación del archivos readme.md para introducir cambios, actualizarlos y subir la nueva versión en formato rama a Github.

* Subiremos la rama con el comando **git push --set-upstream origin development**

* Pasamos a la rama Master con **git checkout master**

* Realizamos merge de los cambios de la  rama development para unificarlos en la rama master con el comando **git merge development**

* Actualizamos el repositorio con todos los cambios realizados **git push**