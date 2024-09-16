> **ID**: Inscripcion a materias
> 
> **TITULO**: **Como** alumno **quiero** inscribirme a materias **para poder** cursarlas.
> 
> **REGLAS DE NEGOCIO**:
> - Pago via tarjeta de credito.
>

> **CRITERIOS DE ACEPTACIÓN**: (Inscripcion a materias)
> **Escenario 1**: Inscripcion exitosa
> **Dado** que  el alumno selecciona "Ingenieria en software 1 " e ingresa la tarjeta válida "1234" que acepta el pago,
> **Cuando** se selcciona la materia  "Ingenieria en software 1 " e se ingresa la tarjeta "1234",
> **Entonces** el sistema efectua el pago e imprime dos comprobantes, uno de inscripción y otro de pago.
>  
> **Escenario 2**: Inscripcion erronea por problemas con la tarjeta
> **Dado** el alumno selecciona "Ingenieria en software 1 " e ingresa la tarjeta "2222" la cual es inválida o rechaza el pago
> **Cuando** se selcciona la materia  "Ingenieria en software 1 " e se ingresa la tarjeta "1234",
> **Entonces** el sistema informa que hubo problemas con la tarjeta.
>

