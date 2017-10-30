# guess-a-number
*Escribe un programa PHP que permita al jugador introducir tres números. 
Dos de ellos serán los límites inferior y superior de un rango, el tercero 
será un número situado dentro de dicho rango. Cuando el programa reciba los 
datos generará un número secreto aleatorio entre los límites inferior y superior 
y lo comparará con el tercer valor. Finalmente se informará al usuario si ha acertado 
el número aleatorio o no. En la página devuelta también figurará el número aleatorio 
y el introducido por el usuario.*

Rama: "guess-a-number-basic"

Orientaciones:

1. Generación de números aleatorios

2. Estructura de control condicional

# guess-a-number-2
*Desarrolla un nuevo programa basado en el anterior en el que el jugador puede 
realizar varios intentos para descubrir el número. Al entrar en el juego la 
aplicación solicita el valor mínimo y máximo del rango de valores y el número máximo 
de intentos. El juego comienza y el jugador va introduciendo una a una sus jugadas. 
La aplicación le devuelve un mensaje informando del resultado de la jugada. Si la 
jugada es un fallo, la aplicación informará al jugador de si su apuesta es superior 
o inferior al número secreto. El juego acaba cuando el jugador acierta el número o 
llega al máximo de intentos.
Al final del juego se invitará al jugador a iniciar un nuevo juego.

Rama: "guess-a-number-repeat"

Orientaciones:

1. Uso de sesiones

# guess-a-number-3
*Desarrolla el ejercicio **guess-a-number-2** utilizando el paradigma de orientación a objetos.*

Rama: "guess-a-number-repeat-oo"

Orientaciones:

1. Uso del paradigma de OO

# guess-a-number-4
*Desarrolla el ejercicio **guess-a-number-3** utilizando el motor de vistas twig.*

Rama: "guess-a-number-repeat-oo-twig"

Orientaciones:

1. Uso del motor de vistas twig

# guess-a-number-5
*Desarrolla un nuevo programa basado en el anterior en el que el jugador podrá 
registrarse en la plataforma del juego de manera automática. Para empezar a jugar
iniciará una sesión con la aplicación y se le dará la oportunidad de iniciar una
partida nueva o continuar con alguna partida que haya dejado inconclusa.
Mientras juega una partida el jugador puede dejar dicha partida sin acabar y comenzar 
otra o incluso cerrar su sesión con la aplicación y acabarla en otro momento.

Rama: "guess-a-number-repeat-bd"

Orientaciones:

1. Uso de la librería PDO