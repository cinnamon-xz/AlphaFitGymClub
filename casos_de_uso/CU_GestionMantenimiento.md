# Caso de uso: Gestión de Mantenimiento de Equipos

*Actor:* Encargado de mantenimiento

*Precondiciones:* Un equipo necesita mantenimiento o se ha reparado.

*Flujo principal:*

1.  El encargado accede a la página de gestión de mantenimiento.
2.  El encargado visualiza la lista de equipos con sus estados actuales (Disponible, Mantenimiento, En uso).
3.  El encargado selecciona un equipo de la lista para actualizar su estado.
4.  El encargado elige el nuevo estado del equipo (Disponible, Mantenimiento, En uso).
5.  El encargado hace clic en "Actualizar Estado".
6.  El sistema muestra un mensaje de "Estado actualizado".

*Capturas de pantalla:*

### Lista de equipos

![Lista de equipos](capturas/img/mantenimiento_1.png)

### Mensaje de estado actualizado

![Mensaje de estado actualizado](capturas/img/mantenimiento_2.png)

*Flujos alternativos:*

* Si no se selecciona un equipo o estado, el sistema muestra un mensaje de error.

*Poscondiciones:*

* Se actualiza el estado del equipo seleccionado en el sistema.
* Se muestra un mensaje de confirmación de actualización de estado exitosa.