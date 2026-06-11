# Historia de Usuario 5: Inicio de Sesión Seguro

**Como** Tendero registrado en la plataforma,  
**Quiero** iniciar sesión con mi correo electrónico y contraseña,  
**Para** acceder de manera segura a los datos confidenciales de mis productos y ventas.

### Criterios de Aceptación
* **Escenario 1: Inicio de sesión correcto.**
    * **Dado que** mi usuario ya está activo en el sistema,
    * **Cuando** ingreso mi correo y contraseña correctos en el formulario de Login y presiono "Ingresar",
    * **Entonces** el sistema debe validar mis datos y darme acceso directo al panel de control de mi inventario.
* **Escenario 2: Validación de credenciales incorrectas.**
    * **Dado que** estoy en la pantalla de Login,
    * **Cuando** ingreso un correo o una contraseña que no coinciden con los registros del sistema,
    * **Entonces** el sistema debe denegar el acceso y mostrar un mensaje de error: "Usuario o contraseña incorrectos".
