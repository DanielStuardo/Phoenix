# Phoenix
Phoenix - Game based on the clasical Tekham Phoenix game (1980) with soundtrack of StarFighter, made with Gadget library for C-Linux Debian and derivatives.

Para jugar, debe tener instalada la librería Gadget y compilar. Luego, el juego es un ejecutable independiente de la librería, si se compila con la opción "-static".

# Requisitos.

Debe tener instalada la librería GADGET para GCC de Linux (Debian y sus derivados Ubuntu, Mint, etc).

Debe tener instalados el terminal RXVT, y los programas APLAY y XSET (aunque estos últimos creo que ya vienen de facto).

Con AFPLAY ejecuto los efectos de sonido y la música de fondo.

Con XSET redefino el delay y el rate del teclado, para una mejor experiencia de juego.

# Compilación.

     ./ccpre.sh <directorio>/phoenix -static

# Ejecución.

     ./<directorio>/phoenix.sh [-nop]

donde:

-nop salta la presentación del juego.

# Screenshots.

![Phoenix Game Linux Console](dataPhoenix/Phoenix_scr01.png)
