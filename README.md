# Tripleten web_project_around_auth
## Nombre del proyecto: Sitio Web Around the US - Tripleten
### Descripción del proyecto: 

Creación de funcionalidad de registro, verificación y cierre de sesión con Express.js

  * Se crean las páginas de registro e inicio de sesión
  * Se configuran las hojas de estilo de dichas páginas
  * Se agregan las funcionalidades de autenticación y verificación

***

### Tecnologías usadas:
  El sitio web esta diseñado con las siguientes tecnologías:

  * El lenguaje de programación para escribir la lógica y funcionalidad del frontend es **express.js** y la del backend es **Node Js**.

***

### Despliegue en la web:
  La página web esta desplegada en Github Pages y se aloja en el siguiente link: **AGREGAR link**
***


## Rutas:

* **GET /users**: Obtiene todos los usuarios.

* **GET /users/:id**: Obtiene un usuario específico por el Id.

* **POST /users**: Crea un usuario.

* **PATCH /users/me**: Actualiza información del usuario.

* **PATCH /users/me/avatar**: Actualiza el avatar del usuario.

* **GET /cards**: Obtiene todas las tarjetas.

* **POST /cards**: Crea una tarjeta.

* **DELETE /cards/:cardId**: Elimina una tarjeta específica.

* **PUT /cards/:cardId/likes**: Agrega un like a una tarjeta.

* **DELETE /cards/:cardId/likes**: Elimina un like de una tarjeta.
