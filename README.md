# Espacio de Pantano - Mecánicas del Minijuego

Este proyecto está inspirado en el minijuego *Face Lift* de *Mario Party*, en el cual los jugadores deben deformar el rostro de un personaje para que coincida con una imagen de referencia. En este juego, la cara aparece estirada o distorsionada, y el objetivo es ajustarla correctamente. A diferencia del juego original, que permite hasta cuatro jugadores, este minijuego ha sido diseñado para un solo jugador.

### Mecánicas del Minijuego

Para implementar las mecánicas del minijuego, se desarrollaron cinco scripts principales:

1. **CustomCursor**: Este script agrega una textura personalizada al cursor, que se presenta en forma de mano, mejorando la interacción del jugador.
   
2. **DeformPlane**: Este script se encarga de deformar la cara de Luigi de forma aleatoria. A partir de esta deformación, se toman como referencia las posiciones de los vértices para realizar la comparación con la imagen de referencia.

3. **PlayerInteraction**: Permite al jugador interactuar con cada vértice del plano de la cara de Luigi. Además, genera un sonido cada vez que el jugador hace clic en un vértice.

4. **ScoreManager**: Este script gestiona el puntaje del jugador, mostrando el puntaje final después de comparar los dos planos: el de referencia y el modificado por el jugador. El puntaje comienza en 0 y aumenta hasta el valor máximo obtenido. También reproduce un sonido cuando se actualiza el puntaje.

5. **TimerManager**: Controla el tiempo restante del minijuego, iniciando desde 30 segundos hasta llegar a 0. Además, se añaden dos sonidos: uno para el reloj que cuenta el tiempo y otro que suena cuando el tiempo se termina, mostrando el mensaje de *finish*.

### Animaciones en los Assets

Se realizaron varias animaciones para darle un toque similar al minijuego original. Las animaciones afectan los siguientes elementos:

-Quad de la imagen de Luigi con una escala.  
-En la imagen del letrero con una escala.  
-En el texto de Player1 con una escala.  
-En el texto de Start con una escala.  
-En el texto de Puntuacion con una escala.  
-En el texto de Time con una escala.  
-En el finish con una escala y posicion.  


## Video Explicativo
Haz clic en la miniatura para ver un video explicativo del minijuego:  


