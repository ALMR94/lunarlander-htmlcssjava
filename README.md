# Lunar-Lander, parte de html, css y javascript
En esta parte del proyecto, he hecho la parte html y css del proyecto. Todavía es una página estática, pero ya se adapta a pantallas grandes y pequeñas. Dicho cambio, se produce cuando el tamaño horizontal de la página baja o sube de 720 píxeles.

Es una página divida en 3 capas, cada una con su nombre (a, b y c). 

## Capa a

En la capa "a" tenemos el marcador con la velocidad, altura y combustible de la nave, dicho marcador tendrá los datos en forma de números, con las unidades al lado de dicho número. A dicho marcador le he puesto como id "cpanel", para luego configurarlo y adaptarlo en sus archivos css, en el que he puesto que sea un 25% de anchura y de altura en escritorio y un 50% en la visualización móvil, con posición relativa (a la página).


## Capa b

En la capa "b" tenemos la zona en la que irá bajando la nave hasta aterrizar en la luna. El div de la nave tiene como id "nave" para así poder editarlo en el archivo css con esa identificación. La imagen está ajustada con altura de 100%, ya que queremos que esté arriba del todo al inicio. Posición centrada y fija. Tamaño en un 20% de la página.


## Capa c

En la capa "c" tenemos lo que más cambia de escritorio a móvil, que es el menú del juego, con las opciones de pausa, reiniciar, ayuda y opciones. "Pause" carga la página de nuevo puesto que tiene un enlace a la misma página, "Restart" igual que "Pause", "Help" nos lleva a la página de instrucciones y "Options" nos lleva a la página de opcionesy configuración del juego. Este menú está formado por cuatro imágenes, con las opciones que ya hemos dicho. Estas imágenes tienen un enlace cada una y el div está identificado con "menu" o "menum" según si es la visualización móvil o la de escritorio para poder ajustar su visualización en cada uno de los dos css. En escritorio, lo he dejado con un tamaño del 60%, ajustándolo a la derecha con float. Aquí el menú movil está desactivado, puesto que no nos interesa que aparezca, así que está con un "display: none".

En la versión móvil el menú tiene un tamaño del 50% (con un 60 quedaba muy grande) y está ajustado a la derecha con float también. Aquí, el menú que se desactiva es el de escritorio, puesto que no nos interesa que aparezca. Las imágenes tambien cambian a otras hechas para la versión móvil, puesto que así es como he decidido que lo haga y para eso he hecho dos menús.

## Fondo y luna
El fondo es imagen png que ocupa toda la pantalla. La luna está identificada como "luna" para luego en css ponerla fijada abajo del todo. En la versión de escritorio tiene una altura del 22% y en la versión móvil la dejo que ocupe un 80% de la página y fijada a la parte de abajo igual. Los márgenes en los dos casos se ajustan automáticamente a la página.

## Javascript
Esta es la parte de JavaScript del proyecto.

En la parte de los marcadores, el fuel va bajando según si damos a enter o en pantalla. La altura también se va actualizando según se mueve la nave. Por último, la velocidad va cambiando a partir de una fórmula que simula la gravedad y la aceleración debido a esta.

En la parte de la nave, la imagen de la nave va cambiando según si le damos a activar el motor o no. Cuando aterriza a más velocidad de la que toca, también se cambia la imagen por el de una explosión. Además, sale el resultado final del juego en forma de alerta, tanto si hemos perdido como si no.

En la parte de la derecha tenemos el menú con distintas opciones, como pausar el juego, reiniciar, ver las instrucciones o ver datos del juego, los dos últimos con enlaces a otra página.

## Versión minimificada
Este es el enlace a la versión minimificada del proyecto:
