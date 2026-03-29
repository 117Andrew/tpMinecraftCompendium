# Propuesta TP DSW

## Grupo
### Integrantes
* 51026 Albanesi, Julian Andres
* 51340 - Mendoza Sardiña, Andres Emilio

### Repositorios
* [fullstack app](https://github.com/117Andrew/tpMinecraftCompendium.git)

## Tema
### Descripción
Una pagina dedicada para construcciones decorativas y de carecter tecnico para el videojuego minecraft. Con el fin de poder compartir distintos diseños a la comudidad del videojuego, mediante archivos, imagenes y/o videos

### Modelo
![imagen del modelo](./Imgs/MD_MinecraftCompendium.png)

## Alcance Funcional 
Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tag <br>2. CRUD Usuario|
|CRUD dependiente|1. CRUD Publicacion {depende de} CRUD Usuario <br>2. CRUD Imagen {depende de} CRUD Publicacion <br>3. CRUD Archivo {depende de} CRUD Publicacion|
|Listado<br>+<br>detalle| 1. Listado de publicaciones filtrado por categoria de publicacion, muestra titulo e imagen; => detalle muestra fecha de publicacion, categoria, cantidad de descargas y link asociado a la publicacion|
|CUU/Epic|1. Login del usuario<br>2. Crear publicacion<br>3. Modificar publicacion|

