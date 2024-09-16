>**ID**: Ingreso alumno
>
>**TÍTULO**: **Como** alumno **quiero** ingresar en el sistema **para poder** inscribirme a las materias de la Facultad de Informática.
>**REGLAS DE NEGOCIO**:
> - El nombre de usuario debe ser único.
> - La contraseña debe tener más de 6 dígitos

> **CRITERIOS DE ACEPTACIÓN**: (Ingresar al sistema)
> - **Escenario 1**: Ingreso exitoso
> **Dado** un nombre usuario unico y una contraseña de mas de 6 digitos,
> **Cuando** el alumno ingresa su usuario y contraseña,
> **Entonces** el sistema le da acceso a la inscripcion.
> 
> - **Escenario 2**: Ingreso invalido por nombre de usuario
> **Dado** un nombre usuario que no es unico y una contraseña de mas de 6 digitos
> **Cuando** el alumno ingresa su usuario y contraseña
> **Entonces** el sistema no le da acceso por nombre no unico de usuario.
>
> - **Escenario 3**:  Ingreso invalido por contraseña
> **Dado** un usuario unico y una contraseña de menos de 6 digitos
> **Cuando** el alumno ingresa su usuario y contraseña
> **Entonces** el sistema no le da acceso por error de contraseña.
>

#Practica-2 #Problema-2