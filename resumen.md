# Documentación del Proyecto: XML y DTD de Jugadores y Clubes de Fútbol T1_P1

Este proyecto está diseñado para relacionar la información sobre jugadores de fútbol y sus clubes con un archivo **DTD** y un archivo **XML**. El objetivo es representar los datos de los jugadores, sus atributos y las relaciones con los clubes a los que pertenecen.

## DTD 

Define la estructura de los datos en el archivo XML, especificando los elementos y atributos que deben contener tanto los jugadores como los clubes de fútbol.

- **Jugadores:** Cada jugador tiene varios atributos como `idJugador`, `refClub`, que relaciona al jugador con su club y `imagenJugador`  que es un atributo opcional para las imágenes del jugador. Los elementos principales del jugador incluyen:
    - `nombre`: El nombre del jugador.
    - `edad`: La edad del jugador.
    - `nacionalidad`: El país de origen.
    - `posiciones`: La posición que puede juegar el jugador.
    - `pierna_habil`: La pierna dominante.
    - `estilo_juego`: El estilo característico del jugador.
    - `palmares`: Los logros del jugador en forma de trofeos.
    - `apodo`: Un alias o apodo del jugador que no todos tienen por eso es opcional.


- **Clubes:** Los clubes también tienen atributos como `idClub`, `imagenClub` que este es opcional para las imágenes. Sus elementos incluyen:
    - `nombre_club`: El nombre del club.
    - `historia`: Información histórica relevante del club.
    - `estilo_juego_club`: El estilo de juego típico del club.
    - `estadio`: El nombre del estadio.
    - `colores`: Los colores representativos del club.
    - `trofeos_club`: Los trofeos obtenidos por el club.


## XML

Contiene datos de ejemplo sobre varios jugadores de fútbol y sus respectivos clubes. Este archivo sigue la estructura definida por el DTD y se valida contra él para garantizar la correcta representación de los datos.

Por eso podemos ver de forma coerente las relaciones entre jugadores y club con todas sus caracteristicas.
