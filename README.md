# AREP-Networking 

 
 

**autor** : Daniel Alberto Rosales Castro 

 
 

Laboratorio sobre Networking. 

 
 

En este laboratorio encontrara los siguientes programas: 

 
 

1) Lector de URls `(ejercicio1)`. 

2) Recolector de datos de una URL `(ejercicio2)`. 

3) Servidor y cliente potencia de números `(ejercicio3.power)`. 

4) Servidor y cliente funciones trigonométricas `(ejercicio4)`. 

5) Servidor web el cual responderá todos los archivos solicitados `(ejercicio4)`. 

6) cliente y Servidor de datagramas el cual retorna la hora cada 5 segundos 

 
## Prerequisitos 
 
Para poder instalar el laboratorio es necesario tener los siguientes proframas instalados:

* Maven
* git



## Instalacion 

 
 

### Maven 

 
 

**Windows:**  

https://experto.dev/instalar-maven-en-windows/ 

 
 

**Linux:** 

https://linuxize.com/post/how-to-install-apache-maven-on-ubuntu-18-04/ 

 
 

### Git 

 
 

**Windows,Linux,MacOS** 

https://gist.github.com/derhuerst/1b15ff4652a867391f03 

 
 
 

Una vez instalado maven y git, descargar el repositorio con el siguiente comando: 

```` 

git clone https://github.com/GrCross/CuanticLibrary 

```` 

## Uso 

El laboratorio se encuentra separado por los diferentes ejercicios enumerados del uno al 5, cada uno de los ejercicios se correrá de la siguiente manera: 

 
 

1) para los ejercicios que son cliente y servidor, correr en primer lugar el servidor 

2) para los ejercicios que solamente poseen una sola clase correr normalmente el archivo. 

 
 

### ejercicio 1 

La variable `eci` contiene la información de la URL. 

 
 

```` 

URL eci = new URL("http://campusvirtual.escuelaing.edu.co:80/moodle/course/view.php?id=304#"); 

```` 

### ejercicio 2 

Para este ejercicio una vez ya lo este corriendo, asignar una URL valida. 

La recolección de los datos se guarda en resultado.html en el root del proyecto. 

 
 

### ejercicio 3 

 
 

El ejercicio 3 se divide en dos partes, la potencia de un numero y las funciones trigonométricas, cada uno tiene su propio cliente y servidor: 

 
 

**Potencia:** 

Una vez este corriendo el servidor y el cliente, escribir por consola un numero, el servidor regresara el mismo numero elevado al cuadrado 

 
 

**Funciones trigonometricas:** 

Una vez este corriendo el servidor y el cliente, se podran realizar las siguientes acciones: 

* ``seno``: ingresar "fun:sin" 

* ``coseno``: ingresar "fun:cos" 

* ``tangente``: ingresar "fun:tan" 

* ``numero``: ingresar un numero para que se le calcule la función que este en ese momento. 

 
 

### ejercicio 4 

Este ejercicio es un servidor el cual responderá a todos los archivos que se le pidan, si este no los encuentra, retornara un html con error ``404``. Los siguientes archivos que se encuentran en la carpeta ``paginas Prueba`` son: 

* HelloWorld.html 

* HelloWorld.jpeg 

* Index.html 

* notFound.html 

 
 

### ejercicio 5 

 
 

Servidor y cliente de datagramas, El servidor retornará su hora cada 5 segundos, mientras que el cliente escucha, aun si el servidor se apaga, el cliente seguirá escuchando. 

 
 ## Build
 * [Maven](https://maven.apache.org/) - Manejador de dependencias
 
 
 ## Autor
 * **Daniel Alberto Rosales Castro** Trabajo inicial
 
 ## Licencia
 
 El laboratorio esta bajo la licencia de la MIT -ver [LICENSE.md](LICENSE.md) para mas detalles
 
 
 
 

 
