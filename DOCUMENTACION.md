DOCUMENTACION GIT

¿Qué es Git?

Git es una herramienta que sirve para guardar los cambios que hacemos en un proyecto. También permite trabajar varias personas en el mismo proyecto sin perder archivos ni cambios. Gracias a Git podemos volver a versiones anteriores si algo sale mal.

Flujo de trabajo de Git

El funcionamiento básico de Git es primero trabajar en los archivos del ordenador, después guardar los cambios en Git y finalmente subirlos a GitHub.

El flujo sería:

Directorio local → Repositorio local → Repositorio remoto

El directorio local es la carpeta del ordenador donde trabajamos.
El repositorio local es donde Git guarda los cambios realizados.
El repositorio remoto es GitHub, donde se suben los archivos a internet.

Comandos usados

Git add

git add .

Este comando sirve para añadir los archivos modificados para que Git detecte los cambios que hemos hecho.

Git commit

git commit -m "mensaje"

Este comando sirve para guardar los cambios realizados en el repositorio local. El mensaje ayuda a saber qué cambios se hicieron.

Git push

git push

Sirve para subir los cambios guardados a GitHub y actualizar el repositorio remoto.

Git pull

git pull

Este comando descarga los cambios del repositorio remoto y actualiza los archivos del ordenador.

Git fetch

git fetch

Sirve para descargar información nueva del repositorio remoto, pero sin aplicarla directamente al proyecto.

Git merge

git merge rama

Este comando une los cambios de una rama con otra para juntar el trabajo realizado.

Conflictos de Git

Un conflicto ocurre cuando dos personas modifican la misma parte de un archivo y Git no sabe qué cambio debe dejar.

Para solucionarlo hay que revisar el archivo, elegir los cambios correctos y después volver a guardar los cambios con un commit.
