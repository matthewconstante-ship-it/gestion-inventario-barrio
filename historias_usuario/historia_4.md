# Historia de Usuario 4: Registro de Tendero (Crear Cuenta)

**Como** Dueño de una tienda de barrio,  
**Quiero** crear una cuenta en la aplicación ingresando mi nombre, el de mi tienda, un correo electrónico y una contraseña,  
**Para** poder tener un espacio privado y seguro donde gestionar mi propio inventario.

### Criterios de Aceptación
* **Escenario 1: Registro exitoso.**
    * **Dado que** estoy en la pantalla de "Crear Cuenta",
    * **Cuando** completo todos los campos obligatorios con datos válidos y hago clic en "Registrarse",
    * **Entonces** el sistema debe crear mi usuario, enviarme un correo de confirmación (simulado) y redirigirme al panel principal.
* **Escenario 2: Intento de registro con un correo ya existente.**
    * **Dado que** ya existe un usuario registrado con el correo "juan@tienda.com",
    * **Cuando** un nuevo usuario intenta registrarse usando ese mismo correo,
    * **Entonces** el sistema debe detener el proceso y mostrar una alerta en pantalla que diga: "Este correo electrónico ya se encuentra registrado".
