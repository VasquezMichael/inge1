> **ID**: Pagar factura.
>
> **TÍTULO**: **Como** cliente **quiero** realizar un pago **para poder** tener la factura al dia.
>**Regla de Negocio:**
>- Facturas al dia.


> **CRITERIOS DE ACEPTACIÓN**: (Pagar con tarjeta)
> -  **Escenario 1**: Pago exitoso
> **Dado** que el cliente no tiene ningun vencimiento de factura y la conexion es valida,
> **Cuando** el sistema verifica,
> **Entonces** el empleado o gerente le cobra el monto original.
>
> - **Escenario 2**: Pago fallido por vencimiento
> **Dado** que el cliente tiene vencida la primera  factura,
> **Cuando** el sistema verifica,
> **Entonces** el empleado o gerente le recarga al monto original. 
> 
> - **Escenario 3**: Pago fallido por vencimiento de 2da fecha
> **Dado** que el cliente tiene vencida la segunda factura y la conexion es valida,
> **Cuando** el sistema verifica,
> **Entonces** el empleado o gerente le informa que no se puede pagar por vencimiento de factura.
> 
> - **Escenario 4**: Pago fallido por fallo en conexión con la central
> **Dado** que el cliente no tiene ningun vencimiento de factura y la conexion es invalida,
> **Cuando** el sistema verifica,
> **Entonces** el sistema informa error de conexion.
