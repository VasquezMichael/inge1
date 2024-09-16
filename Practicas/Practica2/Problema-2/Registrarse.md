>**ID:** Registrar alumno.
>
>**Titulo:** **Como** alumno **quiero* registrarme en el sistema **para poder** inscrimirme en las materias de la facultad.
>
>**Reglas de negocio:**
>-  El nombre de usuario debe ser único.
>-  La contraseña debe tener más de 6 dígitos.

> **CRITERIOS DE ACEPTACIÓN**: (Registrarse en el sistema)
> -  **Escenario 1**: Registro exitoso
> **Dado** que el nombre de usuario se encuentra disponible, y la contraseña tiene más de 6 dígitos,
> **Cuando** el alumno quiere registrarse,
> **Entonces** el sistema crea el usuario para el alumno. 
>
> - **Escenario 2**: Registro fallido por nombre repetido
> **Dado** que el nombre de usuario ya existente
> **Cuando** el alumno quiere registrarse,
> **Entonces** el sistema informa que el nombre de usuario es inválido. 
> 
> - **Escenario 3**: Registro fallido por contraseña inválida
> **Dado** que el nombre de usuario es válido, y la contraseña tiene menos de 6 dígitos,
> **Cuando** el alumno quiere registrarse,
> **Entonces** el sistema informa que la contraseña no es válida.
> 