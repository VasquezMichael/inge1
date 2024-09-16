## Problema 1 : Alquiler de mobiliario 

Suponga que trabaja en una consultora la cual ha sido recientemente contactada por una empresa de alquiler de mobiliario para eventos para la realización de una app. 

De las diferentes entrevistas se ha obtenido la siguiente información: 

El gerente nos dijo que resulta fundamental tener una aplicación móvil que nos permita manejar la agenda de la empresa, sabiendo qué disponibilidad tenemos y permitiendo que nuestros clientes alquilen a través de la app. Para esta primera versión de la app, el gerente nos pidió que sea posible [[Dar de alta]] los diferentes mobiliarios, así como la posibilidad de que los usuarios puedan realizar una reserva de alquiler desde sus dispositivos. Para el detalle de cómo se realiza la carga de los muebles, el gerente nos sugirió hablar con el encargado del departamento de mobiliario. El **encargado** de mobiliario nos comentó que de cada mueble se debe cargar código de inventario, tipo de mueble, fecha de creación, fecha de último mantenimiento, estado (libre, de baja, alquilado) y el precio de alquiler. Además, **no pueden existir códigos repetidos y por el contrato de la franquicia, el precio debe cargarse en dólares**. Para que el encargado pueda dar de alta el mobiliario debe autenticarse en el sistema. El registro de los usuarios de carga no debe modelarse. 
El encargado del departamento de alquileres no comentó acerca de las [[Reservas]] de los alquileres. Por una política comercial de la marca una reserva tiene que **incluir como mínimo 3 muebles**. La reserva debe tener una fecha, lugar del evento, cantidad de días y mobiliario junto a su cantidad. Para realizar una reserva **se debe abonar el 20% del total del alquiler**. [[El pago]] de la reserva **se realiza únicamente con tarjeta de crédito validando número de tarjeta y fondos a través de un servicio del banco**. Luego de efectuado el pago, se emite un número de reserva único que será luego utilizado por el cliente para hacer efectivo el alquiler.

> **Rol de usuarios**
>- Encargado
>- Usuarios

> **Historias de usuario**
>- Dar de alta
>- Reservas
>- Pago