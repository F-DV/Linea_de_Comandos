## Linea_de_Comandos
Algunos comandos curso de linea de comandos de platzi

-------
- ls : listar archivos o carpetas
- ls -l : Detalles de los archivos o carpetas
- ls -lh: listar archivos o carpetas con detalles mas faciles de leer
- pwd : muestra la direccion de la ruta absoluta en donde estamos
- cd nombreDirectorio: Permite movernos entre directorios.
- cd .. : retrocede entre directorios.
- cd rutaAbsoluta: se mueve rapidamente a la ruta que le indiquemos
- mkdir: Crea un directorio (podemos crear varios a la vez)
- cd ~ : Moverse al home directamente
- ls -la : muestra todos los archivos incluyendo archivos ocultos
- ls -lS : me ordena todos los documentos o direcotios por tamaño
- ls -lr : Me orneda en reversa.
- tree : muestra todos los dorectorios en forma de arbol
- tree -L 2 : muestra el arbol soloen dos niveles
- touch NombreArchivo: Crea un Archivo (podemos crear varios a la vez).
- cp nombreArchivo nuevonombreArchivo : copia archivo. 
- mv nombrearchivo .. : mueve el archivo hacia atras.
- mv nombreArchivo NuevoNombreArchivo: Renombra Archivos o Directorios.
- mv NombreDirectorio NombreDirectorioAMoverlo : mieve un archivo o directorio hacia otro.
- head nombreArchivo -n 15 : Abre las primeras 15 lineas del archivo de texto
- tail nombreArchivo -n 15: muestra las ultimas 15 lineas del texto
- less NombreArchivo: Permite abrir el archivo en un editor desdela terminal
- xdg-open NombreArchivo : Abre el archivo en un editor de codigo como VSCode
- nautilus : abre graficamente la carpeta en la que estamos.
- nautilus /Document : Abre graficamente la carpeta que le indiquemos en la ruta
- type nombreDecomando : Muestra la naturaleza del comando
- alias l = ls : genera un aliasa un comando (se borra al cerrarla terminal).
- help comando : Muestra ayuda del comando
- man comando : abre un manual del comando.
- info comando : muestra el manual del comando mas resumido.
- whatis : Muestra para que es un comando rapidamente.
                PELIGRO!! COMANDO RM
- rm -i nombreArchivo : Borra Archivo.
- rm -ri NombreDirectorio : Borra directorio

-------

#WildCards: Busca y filtra en el sistema

- ls *.txt : Muestra todos los archivos que termines en la extencion que especifiquemos.
- ls nombre* : Muestra todos los archivos que empiezen por ese nombre
- ls nombre? : muestra el archivo que empieze en ese nombre y tenca solo 2 caracters despues(cuantos caracteres por ?).
- ls [[:upper:]]* :Muestra todos los archivos que empiezan con mayuscula.(busca en 2 niveles de nuestro sistema)
- ls [[:upper:]]*: Muestra todos los archivos que inician con minusculas.
- ls -d [[:upper:]]* : Busca en solo 1 nivel.
- ls [ad]* : Busca los archivos que empiezen con a o con d



-------

#Atajos de teclado
- file + TAB : Autocompleta el nombre del archivo que coincida con el texto que iniciemos
- 
