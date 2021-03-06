# Introduccion a Python

## ¿Qué es Python?
Python es un lenguaje de programación de propósito general, como aplicaciones web, aplicaciones de escritorio, juegos, etc. Para saber más acerca de [Python](https://www.python.org).

----------

## Instalación de Python
Para poder empezar a trabajar vamos a necesitar instalar la herramienta para ello:
 1. Entrar en la página de [Python](https://www.python.org).
 2. Buscamos la parte de "Downloads", es decir, descargas.
![](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Capturas%20de%20pantalla/int-instalacion1.JPG)
 3. Reconoce el sistema operativo y picar en la versión 3.6.x, es decir "Download Ptyhon 3.6.x"
![](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Capturas%20de%20pantalla/int-instalacion2.JPG)
 4. Una vez descargado, hacer doble click.
 5. En una pestaña que aparecerá, le damos a Instalar ahora o "Install now".
![](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Capturas%20de%20pantalla/int-instalacion3.JPG)
 6. La instalación habrá terminado con: "Setup was successful"
![](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Capturas%20de%20pantalla/int-instalacion4.JPG)

----------

## Hola Mundo
Para los que no sepan de programación, el primer programa se llama Hola Mundo y se muestra por pantalla Hola Mundo para probar la correcta instalación.
Para ello buscaremos en Programas IDLE (Python 3.6 32-bit)y se abrirá la consola: "Python 3.6.0 Shell".
A continuación sólo tenemos que escribir: << print("Hola Mundo") >>
![](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Capturas%20de%20pantalla/int-holamundo.JPG)

También podemos ejecutar python desde la consola de Windows (cmd), para ello:
 1. Abrir en el sistema de archivos  y buscar Python para conocer la ruta
 2. Editar las variables de entorno (se puede hacer escribiendo variables en el buscador de Windows)
 3. Añadimos en path la variable que sea el directorio de Python

Para comprobar su funcionamiento, abrimos la terminal y escribimos python.

Tras esto, es conveniente instalar pip que es un instalador de librerias, para ello:
 1. Desde la ruta de python buscamos en Scrips que tengamos ficheros como pip.exe, pip3.6.exe, pip3.exe.
 2. Editar las variables de entorno (se puede hacer escribiendo variables en el buscador de Windows)
 3. Añadimos en path la variable que sea el directorio de Scripts de Python

Para comprobar su funcionamiento, abrimos la terminal y escribimos pip

----------

## Para comenzar
### Números y operadores aritméticos
Podemos desde la consola de python realizar operaciones tales como suma(+), resta (-), multiplicación(*) y división (/), que siguen las reglas de prioridad de las operaciones. También se pueden usar paréntesis, el redondeo(//), la potencia(**).

### Variables
Se pueden almacenar datos mediante asignación como por ejemplo: <<variable = 2>> y para ver su valor, sólo es necesario poner el nombre de la variable por consola.

### Cadenas
Casos especiales de variables como cadenas para tener en cuenta: comillas en la frase mediante \ (\"), saltos de línea (\n).
El método upper() cambia todos los caracteres de la cadena a mayúsculas.

### Condiciones
En el fichero [condicionales.py](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/condicionales.py) se muestra un ejemplo para una condicional if-elseif-else, es importante de no olvidarse de los dos puntos y de la tabulación para que muestren bien las condiciones.

### Funciones
En el fichero [funciones.py](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/funciones.py) se muestra un ejemplo de funciones, para definirlas utilizaremos "def" seguido del nombre de la función. En el ejemplo hay una función sin parámetros y otra con parámetros.

### Listas
En el fichero [listas.py](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/listas.py) se muestran varios ejemplos de creación y tratamiento de listas comentados.

### Bucles
En el fichero [bucles.py](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/bucles.py) se muestran varios ejemplos de bucles.

### Lectura de datos
Para leer datos utilizaremos input(), se puede asiganar a una variable y entre paréntesis un mensaje que mostrar al usuario. Es importante saber que siempre va a devolver una cadena, para convertilo en un número: int(variable).

### Excepciones
El tratamiento de excepciones es muy importante, ya que al usar métodos que no son nuestros o incluso nuestro, se pueden provocar errores que paralicen el programa. Para evitarlo utilizaremos los bloques try-except explicados en el ejemplo de [excepciones.py](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/excepciones.py)

----------

## Editor de texto para ayudarnos
Recomendado en el curso [PyCharm](https://www.jetbrains.com/pycharm/), yo me descargué la versión community ya que es totalmente gratuita. O sino [Atom](https://atom.io/), del que me han dado mejores recomendaciones a la hora de trabajar.

----------

## Ejecutar los programas desde terminal
Primero es necesario tener un fichero con terminación "py" y abrimos la terminal en el directorio donde hayamos guardado el archivo. Y es tan fácil como escribir "python nombre_fichero.py"

----------

# Reto de las vocales
A partir de una cadena de vocales, imprimir a partir de un bucle cada vocal en mayúsculas. Puedes ver la [solución](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/vocales.py)

----------

# La calculadora
En este programa se realizará una calculadora con los conocimientos básicos de python. Se mostrará un listado de las posibles operaciones numeradas (suma, resta, multiplicacion, división) y el usuario elegirá una de ellas. Después se solicitirán dos números y se dará un resultado de la operación. Tras esto, se pedirá al usuario si desea continuar o no. En caso de que diga que si se volverá a repetir el proceso y en caso negativo se terminará el programa. Para ver la [solución](https://github.com/vrdelc/Aprendiendo-Python/blob/master/Introduccion/calculadora.py)
