> **ID**: Comprar entrada web.
>
> **TÍTULO**: **Como** Cliente  **quiero** comprar entradas por internet **para poder** ir a una función.
>
>  **Reglas de negocio:**
>- El pago se realiza solo por tarjeta de crédito
>

> **CRITERIOS DE ACEPTACIÓN**: (Compra exitosa)
> -  **Escenario 1**: Compra exitosa
> **Dado** que el cliente seleccionó una función en la grilla e ingresó el nombre "AAA", DNI "123" y la cantidad de entradas "2", 
> **Cuando** el cliente aprieta pagar,
> **Entonces** el sistema se conecta con el sistema del banco para realizar el pago, una vez autorizado el pago, se emite un código de compra para el cliente y se informa, ademas actualiza la cantidad de entradas disponibles del sistema.
>
>- **Escenario 2**: Compra fallida por cantidad de entradas no disponible 
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado el nombre "AAA", DNI "123" y la cantidad de entradas "6",
> **Cuando** el cliente aprieta pagar,
> **Entonces** el sistema informa un error de que no hay suficientes lugares para esa función específica, informando tambien la cantidad de entradas disponibles para esa función.
>
>- **Escenario 3**: Compra fallida por falla en el pago
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado el nombre "AAA", DNI "123" y la cantidad de entradas "2",
> **Cuando** el cliente aprieta pagar,
> **Entonces** el sistema se conecta con el sistema del banco para realizar el pago, éste no autorizo el pago y sistema informa que el banco no autorizó el pago.
>
>- **Escenario 4**: Compra fallida por falla de conexion con el sistema del banco
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado el nombre "AAA", DNI "123" y la cantidad de entradas "3",
> **Cuando** el cliente aprieta pagar,
> **Entonces** el sistema informa que hubo un error al conectar con el sistema del banco.

