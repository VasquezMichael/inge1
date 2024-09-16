> **ID**: Retornar libro
> 
> **TITULO**: **Como** socio **quiero** retornar un libro **para poder** solicitar nuevos préstamos en los siguientes días.
> 

> **CRITERIOS DE ACEPTACIÓN**: (Retornar libro)
> **Escenario 1**: Retorno sin suspensión
> **Dado** que el socio retornó el libro en tiempo,
> **Cuando** la bibliotecaria carga los datos en el sistema,
> **Entonces** el sistema verifica si el prestamo está vencido y guarda el retorno con éxito, informando que se entrego en tiempo.
>
> **Escenario 2**: Retorno con suspensión 
> **Dado** que el socio retornó el libro con retraso,
> **Cuando** la bibliotecaria carga los datos en el sistema,
> **Entonces** el sistema verifica si el prestamo está vencido y guarda el retorno con éxito, informa que se entrego fuera de tiempo y suspende al socio por 15 dias.
>

#Practica-2 #Problema-6