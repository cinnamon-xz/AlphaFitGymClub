# Caso de uso: Registro y Gestión de Clientes

*Actor:* Recepcionista

*Precondiciones:* El cliente desea registrarse en el gimnasio.

*Flujo principal:*

1.  El recepcionista accede a la página de registro de clientes.
2.  El recepcionista introduce la siguiente información del cliente:
    * Nombre
    * Apellido
    * DNI
    * Teléfono
    * Correo electrónico
    * Dirección
    * Tipo de membresía (Básica, Estándar, Premium)
3.  El recepcionista hace clic en "Registrar".
4.  El sistema muestra un mensaje de "Registro exitoso".

*Capturas de pantalla:*

### Formulario de registro (campos vacíos)

![Formulario de registro (campos vacíos)](capturas/img/registro_1.png)

### Formulario de registro (campos llenos)

![Formulario de registro (campos llenos)](capturas/img/registro_2.png)

### Mensaje de registro exitoso

![Mensaje de registro exitoso](capturas/img/registro_2.png)

*Flujos alternativos:*

* Si algún campo obligatorio está vacío, el sistema muestra un mensaje de error.
* Si el correo electrónico ya está registrado, el sistema muestra un mensaje de error.

*Poscondiciones:*

* El cliente ha sido registrado en el sistema.
* Se ha asignado el tipo de membresía seleccionado.
* Se muestra un mensaje de confirmación de registro exitoso.