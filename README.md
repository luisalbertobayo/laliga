#### LaLiga123 (scouting a la 2ª división de la liga profesional de fútbol de España, temporada 2017 - 2018)

1
El trabajo realizado correponde al equipo de _scouting_ de un equipo de la primera división de la liga profesional de fútbol de España, que desea tener unas estadísticas generales de todos los jugadores de la segunda división de la liga profesional de fútbol para planificar la temporada 2018 - 2019 (ahora temporada en curso).

Para obtener estos datos, se ha recurrido a las estadísticas históricas de LaLiga, en su web:
https://www.laliga.es/estadisticas-historicas/plantillas/segunda/2017-18/
pues es el organismo que regula el fútbol profesional en España y, por ello, es la información más fidedigna al recoger estos datos oficiales de las actas arbitrales.


2
El nombre del dataset donde que recopila los datos es _LaLiga123_17-18_stats_.


3
El dataset generado por el código implementado se guarda en un _.csv_ que contiene las estadísticas por jugador más representativas referentes al juego durante una temporada completa, 2017 - 2018. Estas información es almacenada en 11 columnas, donde cada fila hace referencia a un jugador.


4
Representación gráfica de las 10 primeras filas del dataset _LaLiga123_17-18_stats_.


5
Los atributos reflejados en el dataset corresponden a datos de las siguientes columnas, recogidos de la temporada completa 2017 - 2018:

- Jugador(_Jugador_).
- Partidos jugados (_P.Jug._).
- Partidos completados (_P.Compl._).
- Partidos titular (_P.Tit._).
- Partidos sustituidos (_P.Sust._).
- Minutos (_Min_).
- Tarjetas (_Tarj._).
- Expulsiones (_Expul._).
- Goles marcados (_Goles_).
- Penaltis transformados (_Penalti_).
- Equipo (_Equipo_).

Estos datos han sido generados a partir de la información que ha reflejado cada árbitro a la conclusión de cada partido en el acta arbitral. Posteriormente, LaLiga los ha hecho públicos en su web, filtrando por liga, temporada y equipo.
De esta manera, el código accede directamente a la temporada a estudio, 2017 - 2018, y es capaz de generar el filtrado de todos los equipos que han participado en ella, para acceder a los datos mostrados de cada equipo y almacenarlos en una única tabla dataset, pues lo que interesa es el análisis por jugador.


6
El propietario de los datos es **Liga de Fútbol Profesional** con sede en _Calle Torrelaguna 60, Madrid_, teléfono _912 055 000_, email _prensa@laliga.es_ y _webmaster@laliga.es_. Su actual presidente es Javier Tebas (@tebasjavier).
Agradecimientos a los árbitros por cumplimentar las actas arbitrales y a LaLiga por hacer públicos y permitir acceder a ellos.


7
El propósito de la recopilación de estos datos es conocer qué jugadores has destacado durante la temporada 2017 - 2018, en base a las estadísticas recogidas que facilitan el _scouting_ para el equipo de fútbol implicado.

- Máximos goleadores.
- Ratio goles por partido.
- Ratio goles por minutos jugados.
- Jugadores más amonestados.
- Jugadores con más minutos jugados.
- Partidos totales completados.
