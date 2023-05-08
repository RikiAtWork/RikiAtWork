# ORDENES BASICAS DE GIT 
## RESUMEN

---
`git init`
>Crearemos un nuevo repositorio local

`git config --global user.email email@ejemplo.com`

`git config --global user.name "nombre_ejemplo"`
>Establecemos una configuración de usuario, como el email, nombre de usuario o tipo de formato.

`git clone <url>`
>Realiza una copia de la última versión de un proyecto en un repositorio

`git branch`
>Podemos crear ramas, listarlas y eliminarlas.

`git checkout <nombre_rama>`
>Se usa para cambiar de una rama a otra.

`git status`
>Nos dice toda la información sobre la rama actual.

`git add <archivo>`
>Lo usamos para incluir los cambios de un archivo para nuestro siguiente commit

`git commit -m "mensaje"`
>Guarda nuestros cambios, en el cual, luego podemos volver más tarde si lo necesitaramos, es como si fuera un punto de control en un videojuego. También podemos añadir el "-m" para escribir un mensaje identificativo de ese commit

`git push origin <nombre-de-tu-rama>`
>Esto enviará los cambios guardados a nuestro servidor remoto.

`git merge <nombre_rama>`
>Esto fusiona la rama que queremos con su rama padre

`git remote -v`
>Permite ver todos los repositorios remotos

`git tag`
>Etiqueta los commits específicos.

`git log --graph --all`
>Podemos ver el log completo como un gráfico con el registro de commits, ramas, etc...
