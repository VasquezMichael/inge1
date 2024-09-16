| | |
| - | - |
| **Nombre del caso de uso:** |Pago de la reserva |
| **Descripción:** |Este CU describe como se realiza el pago de la reserva |
| **Actores:**  |Usuario, servidor del banco |
| **Precondiciones:** | Se debe ejecutar el CU Realizar reserva |
| | |

| | | | 
| - | - | - | 
| **Curso Normal:** | **Acción del Actor** | **Respuesta del Sistema** |
| | **Paso 2:** El usuario ingresa el numero de tarjeta|**Paso 1:** El sistema solicita el numero de tarjeta|
| | **Paso 5:** El servidor del banco valida los datos y fondos suficientes |**Paso 3:** El sistema establece conexion con el servidor del banco|
| | **Paso 6:** El servidor del banco retorna el resultado |**Paso 4:** El sistema envia los datos de la tarjeta al servidor del banco	|
| ||**Paso 7:** El sistema recibe que los datos de la tarjeta son correctos|
| | |**Paso 8:** El sistema recibe que los fondos son suficientes. |
| | |**Paso 9:** El sistema registra el pago y cierra la conexion con el servidor del banco|
| -- | -- |
| **Curso Alterno:** |**Paso alternativo 3:** Falla la conexion con el servidor del banco. Se informa el error. Fin CU|**Paso alternativo 7:** La validacion es incorrecta. Se informa el error de validacion. Fin CU.|
| "	" |**Paso alternativo 8:** Fondos insuficientes. Se informa el problema. Fin CU.|
| **Postcondición:** |Se efectuo y registro el pago a traves de la tarjeta.|| 
