La idea de este ejercicio que practiquen comandos en la consola y revisar que tengan instalado VSCode y git.

Deberán ir anotando los comandos y pasos que usen en cada paso.

Abrir la consola e imprimir la ubicación actual.
El comando que se utiliza es: PWD
/c/Users/davor

Crear una carpeta llamada ejercicios en el escritorio desde la consola, si no estas en la ruta del escritorio, muevete a ella.

 cd OneDrive
 cd escritorio
 mkdir ejercicios
 cd ejercicios

Cambiar la ubicación a la nueva carpeta que crearon.
pwd
/c/Users/davor/OneDrive/escritorio/ejercicios

Abrir la carpeta con VSCode.
code .
En VSCode crear una carpeta ejercicio1.
abrir carpeta, crear nueva carpeta en el escritorio y abrirla

Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
seleccionar la carpeta, luego clic en nuevo archivo y guardar con el nombre
Configurar nombre e email globalmente en git.
$ git config --global user.name edriascos888

$ git config --global user.email davoriascos888@hotmail.com

Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
git init
Initialized empty Git repository in C:/Users/davor/OneDrive/Escritorio/ejercicio1/.git/
git add .

Crear un primer commit con el mensaje “Versión Inicial”.
$ git commit -m 'Versión Inicial'
[master (root-commit) b292974] Versión Inicial
 1 file changed, 31 insertions(+)
 create mode 100644 README.md

Agregar al README.md los comandos que ejecutaron en cada paso.
Agregado el código de comandos---
Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”
git add .
$ git commit -m "Agrega solución primer ejercicio"
[master f74af29] Agrega solución primer ejercicio
 1 file changed, 1 insertion(+), 1 deletion(-)

Publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1.
$ git remote add origin https://github.com/DavidRia868/aspirantes-mir-ejercicio-1.git
$ git branch -M main

Enviar el link del repositorio en Github a su mentor(a).https://github.com/DavidRia868/aspirantes-mir-ejercicio-1
