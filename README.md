# Proyecto de Repertorio

Este proyecto es una aplicación web sencilla que permite gestionar un repertorio de canciones. Se puede agregar, editar, eliminar y consultar 
canciones, las cuales se almacenan en un archivo JSON (`canciones.json`). La aplicación está dividida en dos partes: el backend (servidor Express) 
y el frontend (página web con HTML, CSS y JavaScript).


###  Funcionalidad
API (Backend)
El backend permite interactuar con las canciones a través de las siguientes rutas:

GET /canciones: Devuelve todas las canciones del repertorio.

GET /canciones/:id: Devuelve una canción específica por su ID.

POST /canciones: Permite agregar una nueva canción al repertorio.

PUT /canciones/:id: Permite editar una canción existente.

DELETE /canciones/:id: Permite eliminar una canción.

Frontend (Interfaz de Usuario)
La interfaz permite:

Ver la lista de canciones en una tabla.
Agregar nuevas canciones al repertorio.
Editar canciones existentes.
Eliminar canciones.
