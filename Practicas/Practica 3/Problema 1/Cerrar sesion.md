| | |
| - | - |
| **Nombre del caso de uso:** | Cerrar Sesion |
| **Descripción:** |Especifica el modo en que el empleado mobiliario cierra la sesion en el sistema|
| **Actores:**  |Empleado mobiliario|
| **Precondiciones:** ||
| | |

| | | | 
| - | - | - | 
| **Curso Normal:** | **Acción del Actor** | **Respuesta del Sistema** |
| | **Paso 1:** El empleado selecciona la opcion cerrar sesion | **Paso 2:** El sistema solicita la confirmacion del empleado|
| | **Paso 3:**	El empleado confirma la operacion|**Paso 4:** El sistema cierra la sesion y deshabilita las opciones del empleado|


| | | 
| -- | -- |
| **Curso Alterno:** |**Paso alternativo 3:** El empleado cancela la operacion. Fin CU|
| **Postcondición:** |La sesión ha sido cerrada, las opciones para usuarios registrados son deshabilitadas y se eliminan los datos de sesión.| 
