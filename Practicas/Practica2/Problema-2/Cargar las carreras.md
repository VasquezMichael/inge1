> **ID: ** Cargar carreras.
> 
> **Titulo:** **Como** empleado administrativo **quiero** [[autentificarme]] en el sistema **para poder** cargar las carreras.
> 
> **Reglas de negocio: **
>- No deben poder modificarse ni eliminarse. (Nol es una regla de negocio) 
>- El nombre de la carrera no puede repetirse.
>- Duracion de la carrera: maximo 5 años.

> **Criterios de aceptación (Cargar carreras): **
>- **Escenario 1:** Carga de carreras exitosa.
> **Dado** que el nombre de la carrera no se repite y la duracion no supera los 5 años.
> **Cuando** el empleado ingresa al sistema y quiere cargar las carreras.(Poner todos los campos con ejemplos)
> **Entonces** el sistema realiza el alta de las carreras con éxito.

>- **Escenario 2:** Carga de carreras fallida por nombre de la carrera repetida.
>**Dado** que el nombre de la carrera se repite y la duracion no supera los 5 años.
>**Cuando** el empleado ingresa al sistema y quiere cargar las carreras.
>**Entonces** el sistema informa que la carrera se encuentra repetida.

>- **Escenario 3:** Carga de carreras fallida por exceder la cantidad de años.
>**Dado** que el nombre de la carrera no se repite y que la duracion de años supera el limite.
>**Cuando** el empleado ingresa al sistema y quiere cargar las carreras.
>**Entonces** el sistema informa que la cantidad de años supera el limite.
>