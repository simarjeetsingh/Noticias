# Página web de noticias
###Proyeco final Lenguajes de marcas: Página web de notícias auto rellenableble con el scroll

Especificaciones del cliente:
* La maquetación (layer design) debe dejar 300 px de espacio a la derecha de la pantalla para publicidad si la pantalla es suficientemente ancho. Todo otro diseño es libre.
* Para dispositivos móviles, la publicidad irá fijada en la parte inferior o bien sólo aparecerá en la parte superior (y desaparecerá al hacer scroll) con un alto de 90px. - Puedes elegir la opción. Todo otro diseño es libre.
* Los datos son: título (entorno a 8 palabras), imgbig (url al json, imagen en la carpeta), imgmid (url al json, imagen en la carpeta), descripción (mínimo de 300 caracteres), fecha y hora (datetime) .
* Todas las noticias deben tener el mismo formato y mostrar los datos especificados de forma elegante a todo dispositivo.

### Trabajos realizados
* La página principal **index.html** carga con 3 notícias y al hacer scroll (un poco antes de llegar al bottom), carga 3 notícas más desde el json hasta dos veces.
* Publicidad a la dercha con 300px de width para versión escritorio, 180px para tablets.
* Publicidad en top de la página con un 90px de altura, que desaparece al hacer el scroll.
* Las primeras dos notícias del index.html, tienen enlace a otro .html, donde se muestra la nóticia en detalles (con la image-respnsive grande y un video-responsive de 16:9)
* El index.html incluye un enlace a rss.xml, para el *Rss feed.*
* Las tres pagínas contienen etiquetas *OpenGraph* para compartir la notícia.

###Versión Escritorio:

![Versión escritorio](/img/escritorio.png)

####ersión Móvil

![Alt text](/img/movil.png)
