# VYREN# Tienda Online VYREN - Proyecto ASIR2

Bienvenido al repositorio de la tienda online de gorras **VYREN**. 

Este proyecto ha sido desarrollado utilizando **HTML, CSS puro y JavaScript**, sin dependencias ni frameworks externos (no utiliza Bootstrap, Tailwind ni conexiones a bases de datos online).

## 💾 Funcionamiento de la Base de Datos Local
Para cumplir con los requisitos de un entorno totalmente físico y local, el sistema de carrito de compras y la pasarela de pago están programados para almacenar los pedidos en el **LocalStorage** del navegador. 

**Pasos para comprobar los pedidos registrados:**
1. Realiza una compra de prueba en la página.
2. Abre las herramientas de desarrollador pulsando **F12** (o clic derecho > Inspeccionar).
3. Dirígete a la pestaña **Aplicación** (Application).
4. En el menú lateral izquierdo, despliega **Almacenamiento local** (Local Storage) y selecciona la URL de la web.
5. Haz clic en la clave `pedidos_vyren` para ver el JSON con todos los datos del cliente, la tarjeta cifrada, los productos y el total.
