# TP Final. Batalla Naval (68HC11)
## Contenido
1. [Informacion General](#informacion-general)
2. [Uso](#uso)
3. [Aclaraciones](#aclaraciones)
4. [Recomendaciones](#recomendaciones)
### Informacion General
***
Se desarrollo un juego de la Batalla Naval con el microprocesador 68HC11. Este juego le permite a dos jugadores (P1 y P2) jugar de manera alternada por turno al juego. Para ello se uso un teclado matricial de 16 Teclas (para ingresar los datos), un Display (para mostrar en tiempo real las operaciones) y un Bitmap de 6x6 en el cual se ven los disparos realizados

## Uso
***
Para su utilizacion el usuario una vez que tiene en sus manos el codigo debera de colocar la ubicacion de sus embarcaciones y la respectiva orientacion de los cargueros. En este juego existen dos tipos de embarcaciones:

* Submarino: (1 posicion)
* Carguero: (2 posiciones) con orientacion NORTH, SOUTH, WEST y EAST

Una vez que ya haya cargado el codigo en el correspondiente Software le debera de dar Inicio al codigo. Una vez inicializado despliega el de los menus el "Puerto C" el cual contiene un teclado matricial de 16 teclas en el cual se precionara el jugador actual, luego se elegira una fila y columna disparar y por ultimo se precionara la tecla de disparo. Estas operacion se ven reflejadas en tiempo real en el display que muestra la palabra de "HUNDIDO" en el caso de que se hundio la embarcacion, "TOCADO" en el caso de que el disparo fue a una de las parte del carguero (pero no lo derribo) y por utlimo "AGUA" si en la coordenada disparada no se encontraba ninguna embarcacion.

Luego de terminar el turno del Primer jugador se debera de precionar la tecla de "P2" y repetir la misma secuencia


# Aclaraciones
***
A continuacion se aclaran diferentes situaciones a tener en cuenta:
1. **Ganador:** Una vez que el jugador contrario se quede sin embarcaciones en pie, se mostrara en display una frase celebrando la victoria del jugador ganador

> Una vez que hubo algun ganador se debera de precionar la tecla RESET en el teclado para iniciar un nuevo juego.


# Recomendaciones
***
A continuacion se detallan acciones que se recomiendan llevar a cabo para un correcto funcionamiento de la Calculadora.
1. Se recomienda no apretar demasiado rapido los digitos del teclado.
