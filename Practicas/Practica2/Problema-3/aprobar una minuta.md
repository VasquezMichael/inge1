> **ID**: Aprobar una minuta.
> 
> **TITULO**: **Como** empleado de rendiciones **quiero** evaluar las minutas **para poder** determinar su aprobación.
> 
> **REGLAS DE NEGOCIO**:
> - La persona tiene que tener menos de 3 contratos aprobados.
> - El CUIT de la persona tiene que estar habilitado por la AFIP.
>

> **CRITERIOS DE ACEPTACIÓN**: (Aprobar una minuta)
> **Escenario 1**: Aprobación exitosa
> **Dado** que la persona a contratar tiene menos de 3 contratos vigentes, y tiene el CUIT habilitado por la AFIP,
> **Cuando** el empleado de rendiciones aprueba,
> **Entonces** el sistema válida la minuta.
>  
> **Escenario 2**: Aprobación fallida por cantidad superior de contratos 
> **Dado** que la persona tiene más de 3 contratos vigentes,
> **Cuando** el empleado de rendiciones desaprueba la minuta,
> **Entonces** el sistema inválida la minuta.
>
> **Escenario 3**: Aprobación fallida por CUIT inválido
> **Dado** que la persona tiene menos de 3 contratos y un CUIT inválido,
> **Cuando** el empleado de mesa de rendiciones desaprueba la minuta,
> **Entonces** el sistema inválida la minuta.
> 

#Practica-2 #Problema-3