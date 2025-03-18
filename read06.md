## ¿Qué hacen los siguientes comandos?
* `pwd`: Imprime el directorio de trabajo actual (la carpeta en la que te encuentras).
* `ls`: Lista los archivos y directorios en el directorio actual.
* `cd`: Cambia el directorio de trabajo actual.
* `mkdir`: Crea un nuevo directorio (carpeta).
* `touch`: Crea un nuevo archivo vacío.

## ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).
1. `.cd projects`: Cambia el directorio de trabajo actual al directorio llamado "projects".
2. `mkdir new-project`: Crea un nuevo directorio llamado "new-project" dentro del directorio "projects".
3. `touch new-project/newfile.md`: Crea un nuevo archivo vacío llamado "newfile.md" dentro del directorio "new-project".
4. `cd ..`: Cambia el directorio de trabajo actual al directorio principal (el directorio que contiene el directorio "projects").
5. `ls projects/new-project`: Lista los archivos y directorios dentro del directorio "new-project", que se encuentra dentro del directorio "projects". En este caso, mostrará el archivo "newfile.md".

## ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.
El comando que se usaria es:

* `ls -a`

Por que?:

* `ls`: Es el comando básico para listar archivos y directorios.
* `-a`: Es un parámetro (opción) que significa "all" (todos). Le dice al comando ls que muestre todos los archivos y directorios, incluidos los archivos ocultos. los archivos ocultos son aquellos cuyos nombres comienzan con un punto (.).
