> **ID**: Validar token.
>
> **TÍTULO**: **Como** sistema **quiero** acceder a la central **para poder** validar token.
>**Regla de Negocio:**
>- Token
>


> **CRITERIOS DE ACEPTACIÓN**: (Conexion exitosa)
> -  **Escenario 1**: Conexion exitosa
> **Dado** que el token es valido y la conexion a la central es valida,
> **Cuando** la central verifica el token,
> **Entonces** el sistema envia el requerimiento
>
> - **Escenario 2**: Conexion fallida 
> **Dado** que el token es valido y la conexion a la central es invalida,
> **Cuando**  la centra verifica el token,
> **Entonces** el sistema invalida la conexion
> 
> - **Escenario 3**: Registro fallido por token invalido
> **Dado** que el token es invalido y la conexion a la central es valida,
> **Cuando**  la central verifica el token,
> **Entonces**  la centra invalida el token.
> 