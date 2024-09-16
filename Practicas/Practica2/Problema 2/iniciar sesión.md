>**ID**: Ingreso alumno
>
>**TÍTULO**: **Como** alumno **quiero** ingresar en el sistema **para poder** inscribirme a las materias de la Facultad de Informática.

>**REGLAS DE NEGOCIO**:
> - El nombre de usuario debe ser único.
> - La contraseña debe tener más de 6 dígitos

> **CRITERIOS DE ACEPTACIÓN**: (Ingresar al sistema)
> - **Escenario 1**: Ingreso exitoso
> **Dado** que el alumno ingresó su usuario "pepito123" y su contraseña "12345678",
> **Cuando** se ingresa el usuario "pepito123" y la contraseña "12345678",
> **Entonces** el sistema crea una sesion activa para su cuenta.
> 
> - **Escenario 2**: Ingreso invalido por nombre de usuario
> **Dado** que el alumno ingresó su usuario "pepito123" y su contraseña "12345789",
> **Cuando** se ingresa el usuario "pepito123" y la contraseña "12345678",
> **Entonces** el sistema informa que se ingresó un nombre de usuario inválido.
> 
> - **Escenario 3**:  Ingreso invalido por contraseña
> **Dado** que el alumno ingresó su usuario "pepito123" y su contraseña "12343555",
> **Cuando** se ingresa el usuario "pepito123" y la contraseña "12345678",
> **Entonces** el sistema informa que se ingresó una contraseña inválida.
