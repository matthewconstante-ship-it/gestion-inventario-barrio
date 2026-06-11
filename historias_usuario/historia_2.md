# Historia de Usuario 2: Alertas de Stock Mínimo

**Como** Tendero de la tienda,  
**Quiero** que el sistema me muestre una alerta visual cuando un producto tenga pocas unidades (menos de 5),  
**Para** saber con anticipación qué productos debo pedirle al proveedor antes de que se agoten.

### Criterios de Aceptación
* **Escenario 1: Visualización de alerta por stock bajo.**
    * **Dado que** un producto específico (ej. "Leche 1L") tiene 4 unidades o menos en el inventario,
    * **Cuando** visualizo la pantalla de "Control de Stock",
    * **Entonces** esa fila del producto debe resaltarse en color rojo o mostrar un icono de advertencia de "Stock Bajo".
