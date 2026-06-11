# Historia de Usuario 1: Registro de Productos en el Inventario

**Como** Tendero de la tienda,  
**Quiero** registrar un nuevo producto con su nombre, precio de costo, precio de venta y cantidad inicial,  
**Para** mantener el catálogo de mi tienda actualizado en el sistema.

### Criterios de Aceptación
* **Escenario 1: Registro exitoso de un producto.**
    * **Dado que** estoy en el formulario de "Agregar Producto",
    * **Cuando** ingreso un nombre válido, precio de costo, precio de venta y un stock inicial mayor a cero, y hago clic en "Guardar",
    * **Entonces** el sistema debe almacenar el producto y mostrarlo en la lista general de inventario.
* **Escenario 2: Validación de campos obligatorios vacíos o erróneos.**
    * **Dado que** estoy en el formulario de "Agregar Producto",
    * **Cuando** intento guardar el producto con el campo de nombre vacío o con un stock negativo,
    * **Entonces** el sistema debe mostrar un mensaje de error indicando los campos que debo corregir y no guardará nada.
