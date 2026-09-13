# Sistema Mural Bíblico — Septiembre 2026

Paquete final para GitHub Pages de la Iglesia Cristiana Visión Internacional Apaxco.

## Incluye
- `index.html`: página web automática.
- `config.json`: contenidos y programación semanal.
- `audios/`: cuatro devocionales en audio.
- `qr_alabanza.png` y `qr_devocional.png`: códigos QR permanentes.
- `logo_iglesia_transparente.svg`: logotipo sin fondo, en tamaño vectorial.
- `logo_iglesia_transparente.png`: respaldo PNG transparente.
- `playlists_septiembre_2026.csv`: catálogo de 48 canciones.
- `PLAYLISTS_SPOTIFY_PARA_CREAR.md`: guía con las cuatro playlists.

## URLs permanentes de los QR
Alabanza: `?tipo=alabanza`
Devocional: `?tipo=devocional`

## Programación automática
- Semana 1: 06–12 septiembre
- Semana 2: 13–19 septiembre
- Semana 3: 20–26 septiembre
- Semana 4: 27–30 septiembre

La página usa la zona horaria `America/Mexico_City`. Los QR no necesitan cambiar cada semana.

## Para activar Spotify
Crear las cuatro playlists como públicas y después colocar sus URL públicas en `config.json`, en los campos `spotify_url` de cada semana.


## Playlists públicas de Spotify

Las cuatro playlists públicas están integradas en la página. La página incluye un reproductor/visualizador de Spotify y un botón para abrir cada playlist. Los cambios que hagas directamente en Spotify se reflejarán en el contenido mostrado por el reproductor.


## Playlists
Las playlists se muestran mediante el embed público de Spotify y están vinculadas por semana. Si cambias las canciones en Spotify, la página conserva el mismo enlace y muestra la versión actualizada de esa playlist.
