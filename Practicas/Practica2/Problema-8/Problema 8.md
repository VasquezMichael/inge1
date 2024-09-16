## Problema 8: Teatro 

Se desea modelar un sistema de gestión de ventas de entradas para un teatro. Las personas compran sus entradas a través de una página web, o personalmente. 
El sistema permite, sólo de modo personal en el teatro, la **reserva** de entradas de forma gratuita. El empleado debe ingresar los datos de la obra (fecha, hora, y nombre) junto el nombre y DNI del espectador. En este caso, **sólo se podrá reservar hasta 2 entradas**. Las entradas reservadas no compradas caducarán **tres horas antes** del evento. Para seleccionar el nombre de la obra, el sistema muestra una grilla de funciones disponibles para que el usuario seleccione una.
Para **comprar una entrada vía web**, el sistema muestra la grilla de funciones disponibles. El usuario selecciona una opción, ingresa su DNI, la cantidad de lugares solicitados y selecciona la opción “**pagar**”. El pago se realiza con tarjeta de crédito. Para esto **debe ser autorizada a través del sistema del banco. Este pide el número de tarjeta, vencimiento, y código de seguridad. Verifica todos los campos y autoriza la compra**. Autorizada la tarjeta, se emite un código de compra con el que el cliente podrá retirar sus entradas en la boletería del cine.
Para **comprar una entrada personalmente**, el vendedor de la boletería solicita los datos de la función al cliente, procediendo de un modo similar a la compra web, con la diferencia que en este caso no se muestra el código de compra sino que se imprimen directamente la/s entrada/s. El pago es unicamente con tarjeta de crédito, igual que en el caso anterior. 
Para **retirar las entradas reservadas** previamente, el empleado solicita nombre y DNI del espectador, el sistema valida **que la persona posea entradas reservadas, y que no estén caducas**. El resto del procedimiento se realiza igual que la compra de entradas descriptas anteriormente. Cuando una persona llega con el código de compra, el vendedor debe **ingresar el código** para que el sistema, luego de verificarlo, imprima las entradas correspondientes. 
Además se desea administrar la programación de las salas. El administrador **ingresa la distribución semanal de las obras en las salas** de manera que se encuentre disponible para la realización de la venta de entradas.

>**Rol de usuarios**
>- Vendedor/Empleado
>- Personas
>- Administrador

> **Historias de usuario**
>- [[Reservar entrada]]
>- [[Compra vía web]]
>- [[Compra presencial]]
>- [[Retirar entradas reservadas]]
>- [[Retirar Entrada Web]]
>- [[Ingresar cartelera]]


#Practica-2 