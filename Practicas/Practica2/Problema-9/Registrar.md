> **ID**: Registrar cobro.
>
> **TÍTULO**: **Como** gerente **quiero** acceder a la central **para poder** registrar los cobros.
>**Regla de Negocio:**
>- Clave maestra.
>


> **CRITERIOS DE ACEPTACIÓN**: (Registro de cobro)
> -  **Escenario 1**: Registro exitoso
> **Dado** que el gerente tiene una correcta clave maestra, la conexion a la central es valida y el envio de transacciones se realizo una vez,
> **Cuando** el gerente ingresa la clave maestra,
> **Entonces** el sistema le permite visualizar las estadisticas y servicios cobrados.
>
> - **Escenario 2**: Registro fallido por clave invalida
> **Dado** que el gerente tiene una incorrecta clave maestra, la conexion a la central es valida y el envio de transacciones se realizo una vez,
> **Cuando** el gerente ingresa la clave maestra,
> **Entonces** el sistema no le permite visualizar las estadisticas y servicios cobrados.
> 
> - **Escenario 3**: Registro fallido por conexion invalida a la central
> **Dado** que el gerente tiene una correcta clave maestra, la conexion a la central es invalida y el envio de transacciones se realizo una vez,
> **Cuando** el gerente ingresa la clave maestra,
> **Entonces** el sistema no le permite visualizar las estadisticas y servicios cobrados.
> 
> - **Escenario 4**: Registro fallido por fallo en envio de transacciones
> **Dado** que el gerente tiene una correcta clave maestra, la conexion a la central es valida y el envio de transacciones se realizo mas de una vez,
> **Cuando** el gerente ingresa la clave maestra,
> **Entonces** el sistema no le permite visualizar las estadisticas y servicios cobrados.
