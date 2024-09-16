> **ID: ** Iniciar sesión.
>
> **TItulo: ** **Como** persona **quiero** iniciar sesion en el sistema **para poder** generar una compra de bebidas alcoholicas.
>
> **Reglas de negocio:**
>- El mail ingresado debe ser unico y conidir con el utilizado en el registro.
>
> **Criterios de aceptacion (Iniciar sesion):**
>- **Escenario 1: Login exitoso.**
> **Dado** que la persona ingreso una direccion mail valida y esta corresponde a su usuario.
> **Cuando** la persona ingresa el usuario correcto y se loguea.
> **Entonces** el sistema muestra en pantalla una lista de bebidas.
> 
>- **Escenario 2: Login error.**
> **Dado** que la persona ingresa una direccion de mail invalida.
> **Cuando** la persona ingresa su usuario y quiere loguearse.
> **Entonces** el sistema informa que el usuario ingresado no es valido.