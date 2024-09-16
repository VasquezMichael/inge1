> **ID**: Registrar Usuario.
>
> **TÍTULO**: **Como** cliente  **quiero** registrarme en el sistema **para poder** subir fotos y retirarlas en local.
> Reglas de negocio:
> -Usuario unico.

> **CRITERIOS DE ACEPTACIÓN**: (Registro)
> -  **Escenario 1**: Registro exitoso
> **Dado** que se ingreso los datos personales con un mail UNICO y  un nombre UNICO de usuario "juan",
> **Cuando** el cliente intenta registrarse,
> **Entonces** el sistema lo registra.
>
> - **Escenario 2**: Carga fallida por nombre repetido
> **Dado** que se ingreso los datos personales con un mail UNICO y  un nombre REPETIDO de usuario "juan",
> **Cuando** el cliente intenta registrarse,
> **Entonces** el sistema informa que el nombre de usuario ya existe. 
> 
> - **Escenario 3**: Carga fallida por mail repetido
> **Dado** que se ingreso los datos personales con un mail REPETIDO y  un nombre UNICO de usuario "juan",
> **Cuando** el cliente intenta registrarse,
> **Entonces**  el sistema informa que el mail ya existe
> 


#Practica-2 #Problema-2