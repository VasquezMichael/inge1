> **ID:** Registrarse en el sistema
>
>**Titulo:** **Como** persona **quiero** registrarme en el sistema **para poder** comprar bebidas alcoholicas.
>
>**Reglas de negocio:**
>- El mail será utilizado como nombre de usuario por lo tanto debe ser único.
>- Solo se permite que se registren al sitio personas mayores a 18 años.

>**Criterios de aceptacion(Registrarse en el sistema):**
>- **Escenario 1:** Registro exitoso
> **Dado** que el mail ingresado es unico y que se verifico la edad de la persona.
> **Cuando** la persona ingresa el mail unico y su edad veridica. 
> **Entonces** el sistema genera una contraseña que es enviada al mail ingresado en el registro.
>
>- **Escenario 2:** Registro invalido por incumplimiento de edad.
> **Dado** que el mail ingresado es único y que la verificacion de la edad de la persona no cumple los requisitos.
> **Cuando** la persona ingresa un mail unico y su edad veridica.
> **Entonces** el sistema muestra en pantalla el texti de la ley que impide la venta de bebidas alcohólicas a menores.
>
>- **Escenario 3:** Registro invalido por ingreso de mail repetido.
> **Dado** que el mail ingresado no es unico y que se verifico correctamente la edad de la persona.
> **Cuando** la persona ingresa el mail y este resulta ser repetid e ingresa su edad veridica.
>**Entonces** el sistema informa que el mail ingresado no se encuentra disponible.
