> **ID**: Asociar alumno.
> 
> **TITULO**: **Como** bibliotecaria **quiero** asociar alumnos **para poder** otorgarles un carnet de socio.
> 
> **REGLAS DE NEGOCIO**:
> - Se debe presentar DNI y certificado de alumno regular
>

> **CRITERIOS DE ACEPTACIÓN**: (Asociar alumno)
> **Escenario 1**: Asociación exitosa
> **Dado** que el alumno presentó el DNI "111" y el certificado de alumno regular,
> **Cuando** la bibliotecaria le da a "registrar como socio",
> **Entonces** el sistema genera un número de socio, lo guarda en el sistema e imprime un carnet con el respectivo numero de socio.

 ### Preguntar si esto va.
> **Escenario 2**: Asociación fallida por falta de documentación
> **Dado** que al alumno no presentó DNI o certificado de alumno regular,
> **Cuando** la bibliotecaria quiere asociar al alumno,
> **Entonces** le informa al alumno que le falta documentación y no puede registrarlo como socio.
>

#Practica-2 #Problema-6