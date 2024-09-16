> **ID**: Registrar alumnos.
>
> **TÍTULO**: **Como** alumno **quiero** registrarme en el sistema **para poder** inscribirme a las materias de la Facultad de Informática.
>
> **REGLAS DE NEGOCIO**: 
> - El nombre de usuario debe ser único.
> - La contraseña debe tener más de 6 dígitos.
>

> **CRITERIOS DE ACEPTACIÓN**: (Registrarse en el sistema)
> -  **Escenario 1**: Registro exitoso
> **Dado** que el alumno ingresó el nombre de usuario "pepito123" el cual se encuentra disponible, la contraseña "12345678" que tiene más de 6 dígitos, su nombre "pepe" y su apellido "argento",
> **Cuando**  se ingresa el nombre de usuario "pepito123" y la contraseña "12345678",
> **Entonces** el sistema crea el usuario para el alumno. 
>
> - **Escenario 2**: Registro fallido por nombre repetido
> **Dado**que el alumno ingresó el nombre de usuario "pepito123" el cual no se encuentra disponible, la contraseña "12345678" que tiene más de 6 dígitos, su nombre "pepe" y su apellido "argento",
> **Cuando** se ingresa el nombre de usuario "pepito123" y la contraseña "12345678",
> **Entonces** el sistema informa que el nombre de usuario no está disponible. 
> 
> - **Escenario 3**: Registro fallido por contraseña inválida
> **Dado**que el alumno ingresó el nombre de usuario "pepito123" el cual no se encuentra disponible, la contraseña "12345" que tiene más de 6 dígitos, su nombre "pepe" y su apellido "argento",
> **Cuando** se ingresa el nombre de usuario "pepito123" y la contraseña "12345678",
> **Entonces** el sistema informa que la contraseña tiene que tener mas de 6 dígitos. 

