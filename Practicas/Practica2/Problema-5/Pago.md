> **ID**: Pago via tarjeta.
>
> **TÍTULO**: **Como** usuario **quiero** efectuar el pago  **para poder** retirar las fotos.
> 

> **CRITERIOS DE ACEPTACIÓN**: (Pagar con tarjeta)
> -  **Escenario 1**: Pago exitoso
> **Dado** que la conexión con el servidor del banco es exitosa, el número de tarjeta 1234 es válido y la tarjeta tiene saldo,
> **Cuando** el alumno ingresa el número de tarjeta 1234
> **Entonces** el sistema registra el pago y le otorga un codigo para retirar las fotos. 
>
> - **Escenario 2**: Pago fallido por número de tarjeta inválido
> **Dado** que la conexión con el servidor del banco es exitosa y el número de tarjeta 1234 es inválido,
> **Cuando** el alumno quiere realizar el pago,
> **Entonces** el sistema informa que no se pudoregistra el pago y no le otorga un codigo para retirar las fotos. 
> 
> - **Escenario 3**: Pago fallido por saldo insuficiente de tarjeta de crédito 
> **Dado** que la conexión con el servidor del banco es exitosa y el número de tarjeta 1234 es válido y no tiene saldo,
> **Cuando** el alumno quiere realizar el pago,
> **Entonces** el sistema informa que no se pudoregistra el pago y no le otorga un codigo para retirar las fotos. 
> 
> - **Escenario 4**: Pago fallido por fallo en conexión con el servidor externo del banco
> **Dado** que no se pudo realizar la conexión con el servidor del banco,
> **Cuando** el alumno quiere realizar el pago,
> **Entonces** el sistema informa que no se pudoregistra el pago y no le otorga un codigo para retirar las fotos. 

#Practica-2 #Problema-2