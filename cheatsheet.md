Configuración Básica
Configurar Nombre que salen en los commits

mkdir nombre_directorio
Crea un directorio

touch nombre_archivo
Crea un archivo

rm nombre_archivo
Elimina un archivo

rmdir nombre_directorio
Elimina una carpera vacía

rmdir -r  nombre_directorio
Elimina una carpeta y su contenido

ls
Lista los archivos dentro de una carpeta

ls -R 
Muestra las carpetas y los archivos contenidos en ellos de manera recursiva

pwd 
Muestra la carpeta en la que se está trabajando actualmente

mv ruta/archivo1 ruta/archivo2
Renombra archivos (archivo2 no debe existir o será sobreescrito)

mv ruta/directorio1 ruta/directorio2
Renombra la carpeta1 como carpeta2 (carpeta 2 no debe existir)

mv ruta/directorio1 ruta/directorio2
Mueve contenido de carpeta1 a carpeta2 (carpeta 2 debe existir)

clear
Limpia la pantalla de la terminal

cd
Cambia de carpeta

cd ..
Sube un nivel de carpeta

git config --global user.name "dasdo"
Configurar Email

git config --global user.email dasdo1@gmail.com
Marco de colores para los comando

git config --global color.ui true
Iniciando repositorio
Iniciamos GIT en la carpeta donde esta el proyecto

git init
Clonamos el repositorio de github o bitbucket

git clone url
Añadimos todos los archivos para el commit

git add .
Hacemos el primer commit

git commit -m "Texto que identifique por que se hizo el commit"
subimos al repositorio

git push origin main
GIT CLONE
Clonamos el repositorio de github o bitbucket

git clone url
Clonamos el repositorio de github o bitbucket ?????

git clone url git-demo
GIT ADD
Añadimos todos los archivos para el commit

git add .
Añadimos el archivo para el commit

git add archivo
Añadimos todos los archivos para el commit omitiendo los nuevos

GIT COMMIT
Cargar los cambios realizados

git commit -m "Texto que identifique por que se hizo el commit"
Agregar y Cargar los cambios realizados

GIT PUSH
Subimos al repositorio

git push origin branch
Subimos un tag

GIT LOG
Muestra los logs de los commits

git log
Muestras los cambios en los commits

GIT DIFF
Muestra los cambios realizados a un archivo

git diff

GIT REMOTE
Agregar repositorio remoto

git remote add origin url
Cambiar de remote

GIT BRANCH
Crea un branch

git branch nameBranch
Lista los branches

git branch -b nombre-rama
Crea una rama y te cambia a la misma

git branch
Comando -d elimina el branch y lo une al master

GIT REBASE
Los rebase se usan cuando trabajamos con branches esto hace que los branches se pongan al día con el master sin afectar al mismo

Une el branch actual con el mastar, esto no se puede ver como un merge

git rebase
Cuando se produce un conflicto no das las siguientes opciones:

cuando resolvemos los conflictos --continue continua la secuencia del rebase donde se pauso

OTROS COMANDOS
Lista un estado actual del repositorio con lista de archivos modificados o agregados

git status
Quita del HEAD un archivo y le pone el estado de no trabajado

git pull origin nameBranch
Cambiar de branch

git checkout nameBranch/tagname
Une el branch actual con el especificado

git merge nameBranch
Verifica cambios en el repositorio online con el local

git fetch
Borrar un archivo del repositorio

git rm archivo 
Fork
Descargar remote de un fork

git remote add upstream url
Merge con master de un fork

git fetch upstream
git merge upstream/master