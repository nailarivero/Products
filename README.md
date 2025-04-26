# Products
Capa de presentación (interfaz de usuario)
app.js
Es la interfaz con el usuario, en este caso, por consola.
-Muestra mensajes
-Lee datos
-Llamar a los métodos del servicio
-Muestra los resultados como una tabla
Lógica de negocio 
services/productoService.js
-Valida y procesa
-Gestiona la lista de productos
Capa de datos
models/producto.js
Representa la estructura del dato
-Define que es un producto.

Ventajas respecto a la arquitectura monolítica
-Cada capa tiene su propia función por lo que el código es mas ordenado.
-Se puede modificar alguna capa sin afectar a las demás.
-Se pueden reutilizar componentes.
