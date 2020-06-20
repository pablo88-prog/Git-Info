###**PROGRAMACIÓN II**###

##**Trabajo Práctico sobre Git**##

#**Preguntas**#

***1. ¿Qué es git?***

Es una herramienta que nos permite hacer modificaciones a nuestro código y que sea más fácil la administración de las distintas versiones de cada código que se vaya desarrollado.

***2. ¿Por qué queremos utilizar git?***

Para poder administrar los cambios que vamos realizando a nuestros programas. Además de que podemos acceder al código de nuestro programa en cualquier lugar y compartirlo con otros desarrolladores que pueden enriquecer ése código.

***3. ¿Qué es el bash que instala git?***

Git Bash es la línea de comandos de Git para Windows, a través de él se comunica con el sistema operativo.

***4. ¿Describa los estados(working directory, staging area, repository)?***

-**Working directory:** es el área en la que se trabaja con todos los archivos.

-**Staging area:** cuando se tiene definido los archivos a guardar se pasan a ésta área donde se guardan temporalmente.

-**Repository:** aquí se guardan definitivamente la versión del proyecto que se trabaja.

***5. Describa el flujo para crear un nuevo repositorio git.***

Para crear un nuevo repositorio se comienza accediendo desde la consola al directorio dónde vamos a guardar nuestro proyecto y luego escribimos el comando *“git init”* y dentro de la carpeta de nuestro proyecto se crea una carpeta de git para administrar los cambios de nuestro código.

***6. Describa el flujo para agregar un archivo simple al repositorio.***

Para agregar un archivo debemos escribir en la línea de comandos de la consola *“git add”* y el nombre del archivo que queremos agregar a nuestro proyecto.

***7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.*** 

Para cambiar un archivo debo dirigirme al editor de código abrir el archivo aplicar los cambios, luego abrir la consola buscar el directorio con el archivo y luego escribir el comando *“git add”* y el nombre del archivo modificado para guardar los cambios.

***8. ¿Cómo hago para ignorar un archivo o carpeta?***

Para ignorar un archivo o carpeta me dirijo a mí editor de código y creo un archivo que tenga el nombre *“.gitignore”* y dentro de éste escribimos el nombre de las carpetas y archivos que deseamos ignorar.

***9. Expique que es un branch. Dé un pequeño ejemplo de cómo haría uno.***

Un branch es un espacio o entorno particular en el que cada desarrollador puedan trabajar en un mismo proyecto con otros desarrolladores y que los cambios que aplique no afecten a los archivos originales. Para crear un branch en la consola de comandos escribo *“git branch”* más el nombre que queremos darle al nuevo branch.

***10. ¿Qué hago con 'git add'?***

Con el comando *“git add”* se guarda un snapshot del contenido en el área de trabajo en un momento dado. Luego se podrá guardar definitivamente con el comando *“git commit”*.

***11. ¿Cómo cambiamos de un branch a otro?***

Para cambiar entre un branch y otro escribimos el comando *“git checkout”* más el nombre del branch en el que queremos ubicarnos, en la consola.