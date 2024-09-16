> **ID:** Realizar el pago.
> **TItulo:** **Como** usuario **quiero** realizar el pago **para poder** reservar el inmueble.
> **Reglas de negocio**:
>-  Se realiza unicamente con tarjeta de crédito.
>-  Se debe validar los fondos a traves de un servicio de banco.

> **Criterios de aceptación(Realizar el pago):
>- **Escenario 1:** Pago exitoso.
> **Dado** Dado que no hay fallas en la conexion con el servidor. Que el numero de tarjeta 1234 es valido y cuenta con los fondos suficientes
> **Cuando** Se ingresa el numero de tarjeta 1234 y le da a "Pagar".
> **Entonces** El sistema registra el pago y emite un número de reserva único.

>- **Escenario 2:** Pago rechazado por tarjeta invalida.
> **Dado** que el numero de tarjeta 1234 es invalido y la conexion con el banco es exitosa.
> **Cuando** Se ingresa el número de tarjeta 1234 y quiere realizar el pago.
> **Entonces** El sitema informa que el número de tarjeta es invalido.

>- **Escenario 3:** Pago rechazado por falla en la conexión con el banco.
> **Dado** Que la conexion con el banco no es exitosa.
> **Cuando** Se ingresa los datos de la tarjeta y se quiere efectuar el pago.
> **Entonces** El sistema informa que la conexión con el baco falló.

>- **Escenario 4:** Pago rechazado por fondos insuficientes.
>**Dado**  Dado que no hay fallas en la conexion con el servidor. Que el numero de tarjeta 1234 es valido y no cuenta con los fondos suficientes
>**Cuando** Se ingresa el numero de tarjeta 1234 y se quiere realizar el pago.
>**Entonces** El sistema informa que los fondos son insuficientes.
>

