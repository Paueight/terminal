### Comandos aprendidos Octubre 2
* `ls`: Sirve para visualizar los archivos que hay dentro de un directorio.
* `ls -l`: Sirve para visualizar los archivos que hay dentro de un directorio pero en forma de lista.
* `ls -r`: Sirver para visualizar los archivos que hay dentro de un directorio en forma inversa.
* `rm`: Sirve para eliminar un archivo.
* `cd`: Sirve para ir a Home.
* `cd [Carpeta]`: Sirve para navegar entre carpetas.
* `cd..`:Sirve para regresar a la carpeta anterior.
* `clear`: Sirve para limpiar la terminal.
* `pwd`: Nos indica la ruta en la que nos encontramos.
* `mkdir`: Sirve para crear una carpeta en la ruta en la que nos encontramos.

### Comandos aprendidos Octubre 4
* `mv`: Sirve para mover o renombrar archivos o carpetas.
[Ejemplo: mv aisha.txt Documentos/Haiku/terminal]
:file_folder:
* `cp`: Sirve para copiar un archivo a otra carpeta. :page_facing_up: :arrow_right: :open_file_folder:
* `touch`: Sirve para crear un archivo. :page_facing_up:

### Comandos aprendidos Octubre 9
* `ln -s`:    :link:
* `rm`: Sirve para borrar archivos. :scissors:
* `rm -r /`: Sirve para borrar el directorio raiz. (Tamales Antonio!! Brujaaa Madreeee!!) :gun:
* `rm /*`: Sirve para borrar lo que hay dentro del directorio. :open_file_folder: :gun:
* `rm -rf`: Sirve para borrar directorios y su contenido. :open_file_folder: :x:
* `man`: Sirve para revisar la documentación de los comandos. :interrobang:
* `bc`: Funciona como calculadora. :five: :heavy_plus_sign: :eight:
* `more`: Funciona para imprimir el contenido de un texto. :fax:
* `tail`: Imprime las ultimas 10 lineas de un texto. :pencil: :end:
* `head`: Imprime las primeras 10 lineas de un texto. :page_facing_up: :soon:
* `cat`: Imprime de manera instantatnea el contenido de un texto. :page_with_curl:
* `wc`: Obtenemos el número de lineas, palabras y caracteres de un texto. :chart_with_upwards_trend:
* `wc -l`: Obtenemos el número de lineas de un texto. :clipboard:t-get
* `wc -c`: Obtenemos el número de caracteres de un texto. :page_facing_up:
* `wc -w`: Obtenemos el número de palabras de un texto. :hash:

### Comandos aprendidos Octubre 10
* `git commit --amend -m ""`: Funciona para corregir el commit.
* `vim`: Obtenemos un editor de texto en la terminal.
* `which`: Nos indica en donde se esta ejecutando el comando.
* `top`: Nos indica los procesos que se estan ejecutando.
* `Kill -9`: Mata el proceso seleccionado que se esta ejecutando.
* `man ps`: Manual de ps. :smile:
* `echo`: Sirve para la impresion de un texto en pantalla.
* `""`: Sirve para indicar espacios.

### Comandos desconocidos :blush:
* `oclock`: Muestra un reloj análogo con la hora actual. :clock4:
* `apt`: Es una herramienta de empaquetado de aplicaciones que nos ayuda a simplificar la instalación y desinstalación de programas. :cd:
* `pix`: Sirve para visualizar archivos de imagen. :fireworks:
* `SoX`: Lee y escribe archivos de audio. :headphones:
* `rev`: Imprime en orden inverso el contenido de un archivo. :page_facing_up:

### Comandos aprendidos Octubre 11 :bulb:
* `fortune`: Funciona como galleta de la suerte. :cookie:
* `yes`: Muestra una cadena indefinidamente hasta que el proceso sea eliminado. :bomb:
* `figlet`: Funciona para transformar palabras con fuentes ascii que se encuentran en /usr/share/figlet. :a:
* `sl`: En lugar de escribir ls si escribimos sl obtendremos una locomotora. :steam_locomotive:
* `cowsay`: Obtenemos una vaquita ascii con texto. :cow:
* `toilet --gay`: Obtenemos textos ascii con color. :art:
* `aafire`: Terminal en llamas. :fire: :smile:
* `cmatrix`: Obtenemos una pantalla matrix. ![image](/arte/matrix.png)
* ![image](/arte/junior.png)
* ![image](/arte/locomotora.png)
* ![image](/arte/gatito.png)

### Comandos de aplicaciones instaladas
* `supertuxkart`: Supertux. :penguin:
* `stellarium`: Stellarium. :sunny: :star: :full_moon_with_face:
* `inkscape`: Inkscape. :art: :pencil:

### Comandos aprendidos `>`, `|` y `<` Octubre 12
* `>`: Sirve para guardar la salida de un comando en un archivo. :arrow_right:
* `|`: Sirve para separar comandos que realizan acciones que se conectan. :hocho: :arrow_right: :tomato: :poultry_leg: :arrow_right: :egg: :arrow_right: :stew:
* `<`: Sirve para leer un archivo. :page_facing_up:

### Comandos del ejercicio algebraico
* `bc input-algebra.bc > output-algebra.txt`
* `cat input-algebra.bc | bc > output-algebra.txt`
* `bc < input-algebra.bc > output-algebra.txt`

### Comandos del ejercicio "Ola ke ase"
* `touch ola.txt` --> ola ke ase
* `cowsay < ola.txt`

### Comandos aprendios Octubre 13
* `grep`: Sirve para hacer busquedas en un texto.
* `grep $`: Sirve para buscar especificamente una palabra.
* `.`: Sirve para borrar varios archivos o carpetas en una sola linea.
* `cat *`: Imprime todo.
* `-r`: Recursivamente.
* `-e`: Expresión.
* `-n`: El número de linea en la que se encuentra la palabra buscada.
* `-v`: Identifica caracteres en especifico para no imprimirlos.
* `^`: Busca todas las lineas que contengan un caracter en especifico al inicio.

### Actividad con grep
* `cat` 4-grep-lorem.txt `|` `grep` dolor `>` 4-output-grep.txt `|` `wc -l` `>>` 4-output-grep.txt
* `cat` 4-grep-lorem.txt `|` `grep` Lorem `>` 4-output-grep-2.txt `|` `wc -l` `>>` 4-output-grep-2.txt
* `cat` 4-grep-lorem.txt `|` `grep` `^`Lorem `>` 4-output-grep-2.txt `|` `wc -l` `>>` 4-output-grep-2.txt

### Comandos aprendidos Octubre 16
* `find`: Buscar.
 * `-name`: Nombre.
 * `-type`: Tipo de archivo.
 * `-exec`: Indica la accion que va a realizar.
   * `md5`: Sirve para crear identificadores.
   * `{}`: Archivo. Indica en que archivo se va a imprimir la busqueda.
   * `\;`: Indica que la busqueda ha terminado.
* `split`: Separa un archivo en partes iguales.

### Actividad con split
* `split -l 100 4-grep-lorem.txt ./5-find-aa_`

### Comandos aprendidos Octubre 17
* `script`: Es un archivo de tareas las cuales se ejecutan automaticamente.
* `chmod 744`Nombre del archivo: Se utiliza para obtener permisos.
* `#!/bin/bash`: Se utiliza como interprete.
* `./`: Ejecuta un archivo en el lugar actual.
* `printenv`: Nos ayuda a visualizar las variables disponibles.

### Actividad con script
1. `touch` Hi.txt
2. atom Hi.txt
3. `./`Hi.txt
4. `chmod 744` Hi.txt
5. `./`Hi.txt
6. Hola, paueight
