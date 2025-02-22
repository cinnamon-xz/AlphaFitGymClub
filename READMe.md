# Simulación de Sistema de Gestión de Gimnasio

Este proyecto simula un sistema de gestión de gimnasio con las siguientes funcionalidades principales:

* Registro y gestión de clientes
* Control de asistencia mediante código QR
* Administración de pagos y vencimientos
* Gestión de mantenimiento de equipos

## Descripción del Proyecto

Este proyecto es una simulación de un sistema de gestión de gimnasio. Se han creado interfaces web básicas para representar las funcionalidades clave de un sistema real. El objetivo es demostrar la comprensión de los casos de uso y la capacidad de simular interfaces de usuario.

## Casos de Uso

### 1. Registro y Gestión de Clientes

* Permite registrar nuevos clientes con información básica como nombre, apellido, DNI, teléfono, correo electrónico, dirección y tipo de membresía (Básica, Estándar, Premium).
* Simula la gestión de clientes existentes.

### 2. Control de Asistencia mediante Código QR

* Simula el registro de asistencia de los clientes mediante códigos QR.
* Permite ingresar un código QR simulado y registrar la asistencia.

### 3. Administración de Pagos y Vencimientos

* Permite filtrar los pagos por cliente y estado (Pagado, Pendiente).
* Permite visualizar una lista de pagos con información del cliente, monto, vencimiento y estado.
* Permite registrar un nuevo pago ingresando el nombre del cliente, monto y fecha de vencimiento.

### 4. Gestión de Mantenimiento de Equipos

* Permite visualizar el estado de los equipos del gimnasio (Disponible, Mantenimiento, En uso).
* Permite actualizar el estado de un equipo seleccionado.

## Instrucciones de Uso

1.  Abre los archivos HTML en tu navegador web para visualizar las interfaces.
2.  Utiliza los formularios y botones para interactuar con las interfaces.
3.  Para el control de asistencia QR, ingresa cualquier texto en el campo "Código QR" para generar un código QR simulado.
4.  Las capturas de pantalla de cada caso de uso se encuentran en la carpeta capturas/.

## Capturas de Pantalla

### Registro de Clientes

![Formulario de registro (campos vacíos)](capturas/img/registro_1.png)
![Formulario de registro (campos llenos)](capturas/img/registro_2.png)

### Control de Asistencia QR

![Lector de QR](capturas/img/asistencia_1.png)
![Asistencia registrada](capturas/img/asistencia_2.png)

### Administración de Pagos

![Formulario de registro de pagos](capturas/img/pago_1.png)
![Mensaje de pago registrado](capturas/img/pago_2.png)
![Formulario de registro de pagos lleno](capturas/img/pago_3.png)

### Mantenimiento de Equipos

![Lista de equipos](capturas/img/mantenimiento_1.png)
![Mensaje de estado actualizado](capturas/img/mantenimiento_2.png)

## Tecnologías Utilizadas

* HTML
* JavaScript (con la librería qrcodejs)