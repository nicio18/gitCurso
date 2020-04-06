# gitCurso
Mi primer proyecto en git - Orecchia Cristian
1. ¿Qué es git?
Es un sistema de control de versiones, un programa que administra las distintas versiones del programador.

2. ¿Por qué queremos utilizar git?
Se utiliza git porque un programador con esta herramienta puede controlar un proyecto que va a crecer a medida que en el tiempo va haciendo cambios en su proyecto. Es decir a medida que el proyecto va creciendo se van cambiando archivos y configuraciones.

3. ¿Qué es el bash que instala git?
Es una terminal, es un procesador de comandos con los conceptos de unix.

4. Describa los estados (working directory, staging area, repository)
Working Directory: Es donde el programador trabaja con todos lo archivos.
Stagin area: Es donde se agregan los archivos prepara para guardar.
Repository: Una vez que se decide el programador a guardar se guarda aqui.

5. Describa el flujo para crear un nuevo repositorio git.
Para crear un repositorio en git:
a -Nos ubicamos en la carpeta donde estamos trabajando nuestro proyecto mediante el bash
b -Ejecutamos el comando git init el cual da comienzo al proyecto.
c -Ejecutamos el comando commit el cual crea un punto de control.
d -Ejecutamos el comando git remote add origin [direccion en "github.com" donde se va a guardar el proyecto]
e -Ejecutamos el comando git push -u origin master.

6. Describa el flujo para agregar un archivo simple al repositorio.
Agregamos los archivos mediante el comando git add "nombre del archivo" o bien git add .(punto) para agregar todos los archivos juntos.

7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.
a- Mediante el comando git checkout -- <nombre del archivo> revertimos los cambios de los archivos
b- Ejecutamos el comando git add <nombre del archivo> para guardar el archivo.
c- Ejecutamos el comando git commit para guardar en el repositorio.

8. ¿Cómo hago para ignorar un archivo o carpeta?
Para ignorar un archivo o una carpeta se agrega en el proyecto un archivo nuevo llamadao .gitignore. Dentro colocamos todas las carpetas y archivos que necesitamos que git ignore y no los incluya en el proyecto que se va a guardar.
Luego se agrega mediante el comando add .gitignore y por ultimo ejecutamos git commit para guardar el archivo .gitignore.

9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.
Un branch es una version alternativa del proyecto principal. Por ejemplo por medio del comando git branch <nombre del proyecto alternativo> creo esta version del proyecto, y luego con el comando git checkout <nombre del proyecto alternativo> para cambiar a esta version.

10. ¿Qué hago con `git add .`?
Con git add . agrego todos los archivos todos los archivos de nuestro proyecto.

11. ¿Cómo cambiamos de un branch a otro?
Primero ejecutamos el comando git branch para ver en que rama estamos (proyecto principal o alternativo). Y luego ejecutamos el comando git checkout <nombre del proyecto alternativo> o bien git checkout master para ir a la rama principal.

12. Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.

Markdown es un lenguaje de marcado ligero que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida.
