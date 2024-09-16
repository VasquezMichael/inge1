| | |
| - | - |
| **Nombre del caso de uso:** |Realizar reserva |
| **Descripción:** | En este caso se describe el evento en que el usuario realiza una reserva |
| **Actores:**  | Usuario |
| **Precondiciones:** |  |
| | |

| | | | 
| - | - | - | 
| **Curso Normal:** | **Acción del Actor** | **Respuesta del Sistema** |
| | **Paso 1:** El usuario selecciona la opcion de realizar una reserva |**Paso 2:** El sistema solicita en pantalla los siguientes datos: Fecha, lugar del evento, cant dias y mobiliario junto a su cantidad (min 3)|
| | **Paso 3:**	El usuario selecciona un min de 3 muebles e ingresa los datos solicitados|**Paso 4:** El sistema verifica la cant de muebles y que los datos sean correctos|
| | **Paso 6:** Si el usuario confirma la operacion.|**Paso 5:** El sistema calcula el 20% del alquiler y solicita la confirmacion del usuario|
| | ||
| | |**Paso 7:** El sistema ejecuta el caso Pago de la reserva|
| | | 
| -- | -- |
| **Curso Alterno:** |**Paso alternativo 4:** Cantidad de mobiliarios invalida. La reserva no se realiza. Se vuelve al CU 2 |**Paso alternativo 7:** El pago no se realiza. Se notifica al usuario. Fin de CU |
| **Postcondición:** |La reserva es realizada con exito.| 
