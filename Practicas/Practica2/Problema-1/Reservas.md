> **ID**: Reserva de inmueble.
> **Titulo: ** **Como** usuario **quiero** hacer una reserva **para poder** alquilar un inmueble.
> **Reglas de negocio:**
>- Incluir como minimo 3 muebles
>- Abonar el 20% del alquiler

> **Criterios de aceptacion(Reserva de inmueble):
>- **Escenario 1:** Reserva exitosa.
> **Dado** que se incluyo como minimo 3 muebles, se ingreso el numero de tarjeta 1234 la cual es valida y aceptó efectuar el pago del 20%.
> **Cuando** quiere efectuar la reserva.
> **Entonces** el sistema efectua el pago y emite un número de reverva único.

>- **Escenario 2:** Reserva rechazada por cantidad de inmuebles
> **Dado** que se ingreso el numero de tarjeta 1234 la cual es valida, se seleccionó menos de 3 muebles y acepto efectuar el pago del 20%.
> **Cuando** quiere realizar el pago.
> **Entonces** el sistema informa que la cantidad de mubles seleccionados es insuficiente.

> - **Escenario 3**: Reserva fallida por problema de pago 
> **Dado** que el usuario selecciono al menos 3 mobiliarios,  ingresó la tarjeta "1234" la cual rechazó el pago del 20%,
> **Cuando** le da al boton de "reservar",
> **Entonces** el sistema informa que hay problemas con el pago.
