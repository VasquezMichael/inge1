>**ID:** Dar de alta un viaje.
>
>**Titulo:** **Como** usuario **quiero** dar de alta un viaje **para poder** abaratar costos.
>
>**Reglas de negocio:**
>- Los viajes no pueden superponerse.
>- No se debe adeudar calificaciones.

>**Criterios de aceptacion(Dar de alta un viaje):**
>- **Escenario 1:** Alta de viaje exitoso.
>**Dado** que el viaje propuesto no se superpone con otros y que el usuario no adeuda calificaciones.
>**Cuando** el usuario quiere dar de alta el viaje.
>**Entonces** el sistema informa que el viaje fue dado de alta con exito.
>
>- **Escenario 2:** Alta de viaje rechazada por superposición.
>**Dado**  que el viaje propuesto se superpone con otros y que el usuario no adeuda calificaciones.
>**Cuando** el usuario quiere dar de alta el viaje.
>**Entonces** el sistema informa que el viaje se superpone con otros.
>
>- **Escenario 3:** Alta de viaje rechazada por adeudar calificaciones.
>**Dado**  que el viaje propuesto no se superpone con otros y que el usuario adeuda calificaciones.
>**Cuando** el usuario quiere dar de alta el viaje.
>**Entonces** el sistema informa que no es posible realizar la operacion porque el usuario adeuda calificaciones.
