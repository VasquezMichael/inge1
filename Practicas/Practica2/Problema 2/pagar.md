> **ID**: Pago de las cuotas
>
> **TÍTULO**: **Como** alumno **quiero** efectuar el pago de las cuotas **para poder** inscribirme en las materias de la Facultad de Informática.
> 

> **CRITERIOS DE ACEPTACIÓN**: (Pagar con tarjeta)
> -  **Escenario 1**: Pago exitoso
> **Dado** que la conexión con el servidor del banco es exitosa, el número de tarjeta 1234 es válido y la tarjeta tiene saldo,
> **Cuando** el alumno ingresa el número de tarjeta 1234,
> **Entonces** el sistema registra el pago. 
>
> - **Escenario 2**: Pago fallido por número de tarjeta inválido
> **Dado** que la conexión con el servidor del banco es exitosa y el número de tarjeta 1234 es inválido,
> **Cuando** el alumno ingresa el número de tarjeta 1234,
> **Entonces** el sistema informa que el numero de tarjeta es inválido y no realiza el pago. 
> 
> - **Escenario 3**: Pago fallido por saldo insuficiente de tarjeta de crédito 
> **Dado** que la conexión con el servidor del banco es exitosa y el número de tarjeta 1234 es válido y no tiene saldo,
> **Cuando** el alumno ingresa el número de tarjeta 1234,
> **Entonces** el sistema informa que el saldo es insuficiente y no se registra el pago. 
> 
> - **Escenario 4**: Pago fallido por fallo en conexión con el servidor externo del banco
> **Dado**  que la conexión con el servidor del banco es invalida y el número de tarjeta 1234 es válido y tiene saldo,
> **Cuando** el alumno ingresa el número de tarjeta 1234,
> **Entonces** el sistema informa que no se pudo establecer la conexión con el servidor. 

