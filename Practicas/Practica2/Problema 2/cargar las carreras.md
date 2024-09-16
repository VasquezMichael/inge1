> **ID**: Cargar carreras.
>
> **TÍTULO**: **Como** empleado administrativo **quiero** cargar las carreas en el sistema **para poder** habilitar la inscripciones.
> 
> **REGLAS DE NEGOCIO**: 
> - El nombre de las carreras no puede repetirse.
> - La duración en años es como máximo 5.
> - No se pueden modificar o eliminar carreras, solo ingresar.

> **CRITERIOS DE ACEPTACIÓN**: (Carga de carreras)
> -  **Escenario 1**: Carga exitosa
> **Dado**  que el empleado administrativo ingreso el nombre de la carrera "Taller de programación" que no esta repetido, duración en años "4" que es menor al maximo, costo "usd100" y cantidad máxima de cuotas para el pago "12",
> **Cuando** se ingresa la carrera "Taller de programación" con duracion de "4" años,
> **Entonces** el sistema realiza el alta de la carrera en el sistema. 
>
> - **Escenario 2**: Carga fallida por nombre repetido
> **Dado** que el empleado administrativo ingreso el nombre de la carrera "Taller de programación" el cual ya se encuentra en el sistema, duración en años "4" que es menor al maximo, costo "usd100" y cantidad máxima de cuotas para el pago "12",
> **Cuando**  se ingresa la carrera "Taller de programación" con duracion de "4" años,
> **Entonces** el sistema informa que el nombre de la carrera ya existe. 
> 
> - **Escenario 3**: Carga fallida por duración de carrera inválida
> **Dado** que el empleado administrativo ingreso el nombre de la carrera "Taller de programación" que no está repetido, duración en años "6" que es mayor al maximo, costo "usd100" y cantidad máxima de cuotas para el pago "12",
> **Cuando** se ingresa la carrera "Taller de programación" con duracion de "6" años,
> **Entonces** el sistema informa que la cantidad de años es inválida.
> 


