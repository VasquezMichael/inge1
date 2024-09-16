> **ID**: Retirar entradas compradas via web
>
> **TÍTULO**: **Como** Cliente  **quiero** retirar entradas compradas por internet **para poder** ir a una función.
>
>  **Reglas de negocio:**
>- El cliente tiene que tener el código de compra generado vía web
>

> **CRITERIOS DE ACEPTACIÓN**: (Retiro de entradas reservadas)
> -  **Escenario 1**: Retiro exitoso
> **Dado** que el cliente proporcionó el código de compra "123HZS203" que es válido,
> **Cuando** el empleado ingresa el código de compra en el sistema, 
> **Entonces** el sistema imprime las entradas correspondientes.
>
>- **Escenario 2**: Retiro fallido por código erroneo
> **Dado** que el cliente proporcionó el código de compra "123HZS000" que es erroneo,
> **Cuando** el empleado ingresa el código de compra en el sistema, 
> **Entonces** el sistema imprime que el código de compra es erroneo o no existe.
>
 ## preguntar 
> 
>- **Escenario 3**: Retiro fallido por código de compra caducado
> **Dado** que el cliente proporcionó el código de compra "123HZS000" que es de una función antigua,
> **Cuando** el empleado ingresa el código de compra en el sistema, 
> **Entonces** el sistema imprime que el código de compra es de una función antigua, dando informacion de la función.
>
