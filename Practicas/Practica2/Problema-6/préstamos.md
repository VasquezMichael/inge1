> **ID**: Prestar libro.
> 
> **TITULO**: **Como** bibliotecaria **quiero** buscar socios en el sistema **para poder** dar un préstamo cuando me lo soliciten.
> 
> **REGLAS DE NEGOCIO**:
> - Se realizan exclusivamente a socios habilitados
> - Que el socio no tenga préstamos vencidos
> - Solo libros en buen estado
>

## Preguntar
> **CRITERIOS DE ACEPTACIÓN**: (Prestar libro)
> 
> **Escenario 1**: Préstamo exitoso
> **Dado** que la bibliotecaria verificó en el sistema que el socio esta habilitado y no tiene prestamos vencidos,
> **Cuando** la bibliotecaria verifica que el libro está en buen estado y efectua el préstamo,
> **Entonces** el sistema guarda el préstamo y genera un vencimiento para este.
>
> **Escenario 2**: Préstamo fallido por libro deteriorado
> **Dado** que la bibliotecaria verificó en el sistema que el socio está habilitado y no tiene préstamos vencidos,
> **Cuando** la bibliotecaria verifica que el libro se encuentra deteriorado ,
> **Entonces** la bibliotecaria decide no efectuar el préstamo,
>
> **Escenario 3**: Préstamo fallido por socio inhabilitado
> **Dado** que el socio se encuentra inhabilitado,
> **Cuando** la bibliotecaria verifica al socio,
> **Entonces** la bibliotecaria no efectua el préstamo.
>
> **Escenario 4**: Préstamos fallido por préstamos vencidos
> **Dado** que el socio tiene préstamos vencidos,
> **Cuando** la bibliotecaria verifica al socio,
> **Entonces** la bibliotecaria no efectua el préstamo.
>

#Practica-2 #Problema-6