> **ID**: Retirar entradas reservadas
>
> **TÍTULO**: **Como** Cliente  **quiero** retirar entradas reservadas **para poder** ir a una función.
>
>  **Reglas de negocio:**
>- El pago se realiza solo por tarjeta de crédito
>

> **CRITERIOS DE ACEPTACIÓN**: (Retiro de entradas reservadas)
> -  **Escenario 1**: Retiro exitoso
> **Dado** que el cliente proporcionó su DNI "123", y el empleado verifica en el sistema que haya reservas para esa persona y que no esten caducas,
> **Cuando** el empleado ingresa los datos de la tarjeta de crédito,
> **Entonces** el sistema se conecta con el sistema del banco para realizar el pago, una vez autorizado el pago, se imprimen las entradas reservadas.
>
>- **Escenario 2**: Retiro fallido por reserva caducada
> **Dado** que el cliente proporcionó su DNI "123", y el empleado verifica en el sistema que haya reservas para esa persona y éstas ya caducarón,
> **Cuando** el empleado busca la reserva para la función,
> **Entonces** el sistema informa que no hay reservas disponibles de la persona para esa función.
> 
>- **Escenario 3**: Retiro fallido por fallo en el pago 
**Dado** que el cliente proporcionó su DNI "123", y el empleado verifica en el sistema que hay reservas para esa persona y que no esten caducas,
> **Cuando** el empleado encuentra la reserva para la función e ingresa los datos de la tarjeta de crédito,
> **Entonces** el sistema se conecta con el sistema del banco para realizar el pago, este no autorizó el pago, el sistema informa que no se autorizo el pago.
>
>- **Escenario 4**: Retiro fallido por fallo de conexion con el sistema del banco
>**Dado** que el cliente proporcionó su DNI "123", y el empleado verifica en el sistema que hay reservas para esa persona y que no esten caducas,
> **Cuando** el empleado encuentra la reserva para la función e ingresa los datos de la tarjeta de crédito,
> **Entonces** el sistema informa que no se puede conectar con el sistema del banco.
> 
