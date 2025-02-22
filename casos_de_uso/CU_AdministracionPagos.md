# Caso de uso: Administración de Pagos y Vencimientos

*Actor:* Recepcionista

*Precondiciones:* El cliente tiene una membresía activa.

*Flujo principal:*

1.  El recepcionista accede a la página de administración de pagos.
2.  El recepcionista puede filtrar los pagos por cliente y estado (Pagado, Pendiente).
3.  El recepcionista visualiza la lista de pagos con información del cliente, monto, vencimiento y estado.
4.  El recepcionista puede registrar un nuevo pago ingresando el nombre del cliente, monto y fecha de vencimiento.
5.  El sistema muestra un mensaje de "Pago registrado" al registrar un nuevo pago.

*Capturas de pantalla:*

### Formulario de registro de pagos

![Formulario de registro de pagos](capturas/img/pago_1.png)

### Mensaje de pago registrado

![Mensaje de pago registrado](capturas/img/pago_2.png)

### Formulario de registro de pagos lleno

![Formulario de registro de pagos lleno](capturas/img/pago_3.png)

*Flujos alternativos:*

* Si no se encuentran pagos con los filtros aplicados, el sistema muestra un mensaje indicando que no hay resultados.
* Si algún campo obligatorio del formulario de registro está vacío, el sistema muestra un mensaje de error.

*Poscondiciones:*

* Se visualiza la lista de pagos filtrada según los criterios seleccionados.
* Se registra un nuevo pago en el sistema.
* Se muestra un mensaje de confirmación de registro de pago exitoso.