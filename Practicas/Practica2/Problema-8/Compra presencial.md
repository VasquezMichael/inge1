> **ID**: Comprar entrada.
>
> **TÍTULO**: **Como** Cliente  **quiero** comprar entradas **para poder** ir a una función.
>
>  **Reglas de negocio:**
>- El pago se realiza solo por tarjeta de crédito
>

> **CRITERIOS DE ACEPTACIÓN**: (Compra exitosa)
> -  **Escenario 1**: Compra exitosa
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó los datos de esta al empleado junto a la cantidad de entradas "2",
> **Cuando** el empleado ingresa la compra,
> **Entonces** el sistema pide los datos para el pago, se conecta con el sistema del banco el cual autoriza el pago,se efectúa el pago e imprime las entradas y actualiza la cantidad de entradas disponibles del sistema.
>
>- **Escenario 2**: Compra fallida por cantidad de entradas no disponible 
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado los datos de la misma junto a la cantidad de entradas "4",
> **Cuando** el empleado ingresa la compra al sistema,
> **Entonces** el sistema informa un error por insuficientes lugares para esa función específica, informando tambien la cantidad de entradas disponibles para esa función.
>
>- **Escenario 3**: Compra fallida por falla en el pago
> **Dado** que el cliente seleccionó una función en la grilla y le proporcionó al empleado los datos de la misma, junto a la cantidad de entradas "1",
> **Cuando** el empleado ingresa la compra al sistema,
> **Entonces** el sistema pide los datos de la tarjeta para el pago, se conecta con el sistema del banco para verificar el pago, el cual no autorizó el pago, el sistema informa que el banco no autorizó el pago.
>
>- **Escenario 4**: Compra fallida por falla de conexion con el sistema del banco
> **Dado** que el cliente seleccionó una función en la grilla, le proporcionó al empleado los datos de la misma y la cantidad de entradas "3",
> **Cuando** el empleado ingresa la compra al sistema,
> **Entonces** el sistema informa que hubo un error al conectar con el sistema del banco.
