## Comandos Git Indispensables

Git es una herramienta poderosa para el control de versiones. Aquí hay algunos comandos esenciales que todo desarrollador debería conocer:

### Configuración Inicial

* `git config --global user.name "Tu Nombre"`: Configura tu nombre de usuario para los commits.
* `git config --global user.email "tu.email@ejemplo.com"`: Configura tu correo electrónico para los commits.
* `git init`: Inicializa un nuevo repositorio Git en el directorio actual.

### Trabajo Básico

* `git status`: Muestra el estado del directorio de trabajo y del área de preparación.
* `git add <archivo>`: Agrega un archivo al área de preparación.
* `git add .`: Agrega todos los cambios al área de preparación.
* `git commit -m "Mensaje del commit"`: Crea un nuevo commit con los cambios preparados.
* `git log`: Muestra el historial de commits.

### Ramas (Branches)

* `git branch`: Lista todas las ramas locales.
* `git branch <nombre_rama>`: Crea una nueva rama.
* `git checkout <nombre_rama>`: Cambia a la rama especificada.
* `git checkout -b <nombre_rama>`: Crea y cambia a una nueva rama.
* `git merge <nombre_rama>`: Fusiona la rama especificada con la rama actual.
* `git branch -d <nombre_rama>`: Elimina la rama especificada (si está fusionada).

### Remotos

* `git remote add origin <URL_repositorio_remoto>`: Agrega un repositorio remoto.
* `git remote -v`: Lista los repositorios remotos configurados.
* `git push origin <nombre_rama>`: Sube los commits de la rama local al repositorio remoto.
* `git pull origin <nombre_rama>`: Descarga los cambios del repositorio remoto y los fusiona con la rama local.
* `git clone <URL_repositorio_remoto>`: Clona un repositorio remoto en tu máquina local.

### Deshacer Cambios

* `git checkout -- <archivo>`: Descarta los cambios en el archivo especificado.
* `git reset HEAD <archivo>`: Remueve el archivo del área de preparación.
* `git reset --hard <commit>`: Revierte el directorio de trabajo al commit especificado (¡cuidado, esto borra cambios!).

### Colaboración

* `git fetch`: Descarga los cambios de un repositorio remoto sin fusionarlos.
* `git pull`: Descarga y fusiona los cambios de un repositorio remoto.
* `git push`: Carga los cambios de tu repositorio local a un repositorio remoto.

### Otros Comandos Útiles

* `git diff`: Muestra las diferencias entre el directorio de trabajo y el área de preparación.
* `git stash`: Guarda temporalmente los cambios no confirmados.
* `git stash pop`: Aplica los cambios guardados con `git stash`.

Estos comandos te proporcionarán una base sólida para trabajar con Git. ¡Practica y experimenta para dominar el control de versiones!