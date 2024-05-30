Proyecto de API para ecommerce.

Consignas cumplidas:
El servidor ha sido inicializado en el puerto 8080 y responde correctamente a las siguientes solicitudes:

GET localhost:8080/api/products<br><br>
GET localhost:8080/api/products?limit=# (reemplazar el numeral por el número deseado)<br><br>
GET localhost:8080/api/products/:pid<br><br>
POST localhost:8080/api/products/ (se verifica que el producto cumpla con los campos obligatorios y se genera un ID único y un status por defecto automáticamente)<br><br>
PUT localhost:8080/api/products/:pid (al actualizar se verifica que el ID no se cambie)<br><br>
DELETE localhost:8080/api/products/:pid<br><br>
GET localhost:8080/api/carts/:cid<br><br>
POST localhost:8080/api/carts/<br><br>
POST localhost:8080/api/carts/:cid/product/:pid (se verifica si el producto ya existe e incrementa la propiedad quantity en caso de ser necesario)
