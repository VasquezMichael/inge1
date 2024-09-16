> **ID**:Verificar CUIT .
> 
> **TITULO**: **Como** sistema de confeccion de minutas **quiero** enviar datos **para poder** verificar la validez del CUIT.
> 
> **REGLAS DE NEGOCIO**:
> - Que el token sea correcto
>

> **CRITERIOS DE ACEPTACIÓN**: (Verificar CUIT)
> **Escenario 1**: Verificación exitosa
> **Dado** que la conexion con el servidor es correcta y el token es correcto,
> **Entonces** el servidor responde si el CUIT está habilitado o no.
>  
> **Escenario 2**: Verificación fallida por token inválido 
> **Dado** que la conexión con el servidor es correcta y el token ingresado es inválido,
> **Cuando** el sistema quiere verificar el CUIT,
> **Entonces** el servidor te tira error por token inválido.
>
> **Escenario 3**: Verificación fallida por error de conexión con el servidor
> **Dado** que la conexion con el servidor falló,
> **Entonces** el sistema informa un error de conexion con el servidor de la AFIP.
> 

#Practica-2 #Problema-3