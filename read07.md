## ¿Qué es el control de versiones?
Es un sistema que registra los cambios realizados en un archivo1 o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones específicas más adelante.
## ¿Qué es “clone” en Git?
Es el proceso de crear una copia local de un repositorio remoto.
## ¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?

Se puedes usar `git add .` para agregar todos los archivos modificados en el directorio actual y sus subdirectorios, o `git add nombre_del_archivo` para agregar un archivo específico.

## ¿Cuál es el comando para enviar la captura de los archivos modificados a Github?
El proceso de enviar los archivos modificados a GitHub implica dos pasos:
1. "Commit": Primero, debes crear una "captura" (commit) de los archivos modificados localmente. El comando para esto es:
    * `git commit -m "Mensaje descriptivo del commit"`

2. "Push": Luego, debes enviar (push) el commit al repositorio remoto en GitHub. El comando para esto es:
    * `git push origin nombre_de_la_rama`
    * "origin" suele ser el nombre del repositorio remoto, y "nombre_de_la_rama" es la rama en la que se está trabajando (por ejemplo, "main" o "master").
