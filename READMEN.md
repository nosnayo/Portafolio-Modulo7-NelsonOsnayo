## NELSON OSNAYO
### AVANCE DE PORTAFOLIO MÓDULO 7
***
Para el desarrollo de su ecommerce debe implementar la comunicación 
con su base de datos PostgresSql a través de una API Rest, utilizar un ORM y 
además se deben poder realizar las mismas operaciones simuladas en la 
base de datos del módulo 5, usando verbos HTTP para la compra de 
productos y descuento de estos un inventario. 

### Instrucciones: 
1 .Api rest 
Las rutas que deberás crear son las siguientes: 
/GET: Devuelve la aplicación cliente (página principal). 
/producto POST: Recibe los datos de un nuevo producto y los almacena en PostgreSQL. 
/productos GET: Devuelve todos los productos registrados con su inventario o stock. 
/producto PUT: Recibe los datos modificados de un producto registrado y los actualiza. 
/producto DELETE: Recibe el id de un producto registrado y lo elimina. 
/venta POST: Recibe los datos para realizar una nueva venta. Se debe  ocupar una transacción SQL en la consulta a la base de datos. 
/ventas GET: Devuelve todas las ventas almacenadas en la base de datos en formato de lista o tabla. 

### EJECUCION DEL PROYECTO
Para ejecutar el proyecto, sigue los siguientes pasos:
- Clona este repositorio a tu máquina local.
- Instala las dependencias usando el comando npm install.
- Ejecuta el comando node server.js para iniciar el servidor.
- Abre tu navegador y visita http://localhost:puerto para ver la página principal.


NOTA: Los registros de BD del proyecto estan configurado en el archivo .env con acceso a dato de https://api.elephantsql.com/:
mas detalle de la configuración en archivo .env

### Credenciales usuario:
admin@gmail.com
admin

### RUTAS
/admin/agregar  : ACCESO A agregar nuevos productos.
/admin/home     : ACCESO a menu Admin.
