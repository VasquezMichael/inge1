> **ID**: Reservar entrada.
>
> **TÍTULO**: **Como** Cliente  **quiero** reservar entradas **para poder** pagarlas después y concurrir a la función.
>
>  **Reglas de negocio:**
>- Se puede reservar como máximo 2 entradas.
>

> **CRITERIOS DE ACEPTACIÓN**: (Reserva exitosa)
> -  **Escenario 1**: Reserva exitosa
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado el nombre "AAA", DNI "123" y la cantidad de entradas a reservar,
> **Cuando** el empleado ingresa los datos,
> **Entonces** el sistema guarda la reserva para ese cliente, actualizando la cantidad de entradas disponibles hasta 3 horas antes de la función si no se efectua el pago de la reserva.
>
>- **Escenario 2**: Reserva fallida por funcion llena
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado el nombre "AAA", DNI "123" y la cantidad de entradas a reservar,
> **Cuando** el empleado ingresa los datos,
> **Entonces** el sistema informa un error de que no hay más lugares para esa función específica, informando tambien la cantidad de entradas disponibles.
>

