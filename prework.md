# Prework: Buenas prácticas y entorno de desarrollo

**command line**
ls: listar directorio
ls -a: archivos ocultos
ls -l: mostrar permisos que tiene el directorio
ls -t: organizar por fecha de modificacion

ls -la: listado de archivos y carpetas ocultas

clear: limpiar pantalla (ctr + l)

pwd: nos muestra la ruta en la que estamos ubicados
mkdir: crear carpeta
cd ..: regresar a la carpeta anterior
cd: regresar al home
history: ver historial. usar ! + número para ir al comando seleccionado

**crear archivos**
touch: crear un archivo con extensión txt
nano: escribir en el archivo .txt
rm: eliminar archivo
rm -rf: eliminar folder

**herramientas básicas**
cat: permite visualizar un archivo completo en la terminal.
* se puede crear copia. cat test.txt > copy_test.txt
more: muestra por partes un archivo dentro de la terminal
tail: muestra las últimas 10 líneas de cada archivo, se puede modificar pasándole el parámetro con el número de líneas -15
open: abre un archivo con el programa que tengamos por defecto

**llaves SSH**
Las llaves SSH nos van a ayudar para autentificarnos con servidores. SSH utiliza criptografía asimétrica, o sea, tenemos dos llaves:

Pública: la llave pública la podemos compartir por internet.
Privada: debes tenerla en un sitio seguro y no debe ser compartida.

Tener una llave SSH nos permitirá una conexión fácil y segura con servidores.

Para crear una llave SSH utilizamos el siguiente comando:
*ssh-keygen -t rsa -b 4096 -C "comentario"*
-t: especifica el algoritmo a utilizar.
-b: especifica la complejidad del algoritmo.
-c: comentario (correo electrónico).
