# Historia de Usuario 3: Registro de Ventas y Descuento de Stock

**Como** Tendero de la tienda,  
**Quiero** registrar los productos que se lleva un cliente en una venta diaria,  
**Para** cobrar el total correcto y que el sistema descuente automáticamente esas unidades del inventario.

### Criterios de Aceptación
* **Escenario 1: Procesar una venta con éxito.**
    * **Dado que** he seleccionado 2 productos del inventario en la pantalla de ventas,
    * **Cuando** presiono el botón "Confirmar Venta",
    * **Entonces** el sistema debe mostrar el total a cobrar, registrar la venta en el historial y restar las cantidades vendidas del stock actual del producto.
