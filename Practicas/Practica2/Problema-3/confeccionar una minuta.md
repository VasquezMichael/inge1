> **ID**: Confeccion de una minuta.
> 
> **TITULO**: **Como** empleado de mesa de entrada **quiero** ingresar datos **para poder** confeccionar una minuta.
> 
> **REGLAS DE NEGOCIO**:
> - Los montos de un contrato no pueden superar los $25.000
> - La duración de un debe ser como máximo de 6 meses.
>

> **CRITERIOS DE ACEPTACIÓN**: (Confeccionar una minuta)
> **Escenario 1**: Confección exitosa
> **Dado** que se ingreso un monto inferior a $25.000 y una duración maxima de 6 meses.
> **Cuando** el empleado de mesa de entradas confecciona la minuta,
> **Entonces** el sistema asocia un número de minuta automaticamente.
>  
> **Escenario 2**: Confección erronea por monto erroneo
> **Dado** que se ingreso un monto superior a $25.000,
> **Cuando** el empleado de mesa de entradas confecciona la minuta,
> **Entonces** el sistema informa que hay un error en el monto.
>
> **Escenario 3**: Confección erronea por duración inválida
> **Dado** que se ingreso una duración de mas de 6 meses,
> **Cuando** el empleado de mesa de entradas confecciona la minuta,
> **Entonces** el sistema informa que hay un error en la duración.
> 

#Practica-2 #Problema-3