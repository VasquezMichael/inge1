>**ID:**Comprar bebidas.
>
>**Titulo:** **Como** usuario **quiero** seleccionar las bebidas **para poder** comprarlas.
>
>**Reglas de negocio:**
>- El usuario debe [[Iniciar sesion]]
>- Si el usuario es premium se debe realizar un 20% de descuento.
>- Si el usuario selecciona una compra con un monto de a lo sumo $4500
>- Si el usuario es premium y compra por un monto superior a $4500 se deben aplicar ambos descuentos.

>**Criteorios de aceptación**(Comprar bebidas):
>- **Escenario 1:** Copra de usuario común con monto menor a $4500 exitosa.
>**Dado** que el usuario selecciona una compra con un monto menor a $4500 y no es premium.
>**Cuando** el usuario selecciona las bebidas que quiere comprar.
>**Entonces** el sistema informa el monto de la compra.
>
>- **Escenario 2:** Compra de usuario premium con monto menor a $4500 exitosa.
>**Dado** que el usuario selecciona una compra con un monto menor a $4500 y es premium.
>**Cuando** el usuario selecciona las bebidas que quiere comprar.
>**Entonces** el sistema informa el monto total menos el 20% de descuento.
>
>- **Escenario 3:** Compra de usuario común con monto min de $4500.
>**Dado** que el usuario común selecciona una compra con un monto de por lo menos $4500.
>**Cuando** el usuario selecciona las bebidas que quiere comprar.
>**Entonces** el sistema informa el monto total menos el 10% de descuento.
>
>- **Escenario 4:** Compra de usuario premium con monto de compra de por lo menos $4500
>**Dado** que el usuario premium selecciona una compra con un monto de por lo menos $4500
>**Cuando** el usuario selecciona las bebidas que quiere comprar.
>**Entonces** el sistema informa el monto total menos el 30% de descuento.