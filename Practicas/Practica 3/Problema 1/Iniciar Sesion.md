| | |
| - | - |
| **Nombre del caso de uso:** | Iniciar Sesion |
| **Descripción:** |Especifica el modo en que el empleado mobiliario inicia sesion con su nombre de usuario y contraseña|
| **Actores:**  | Empleado mobiliario|
| **Precondiciones:** ||
| | |

| | | | 
| - | - | - | 
| **Curso Normal:** | **Acción del Actor** | **Respuesta del Sistema** |
| | **Paso 1:** El empleado selecciona la opcion iniciar sesion | **Paso 2:** El sistema solicita en pantalla el usuario y contraseña|
| | **Paso 3:**	El empleado ingresa los datos solicitados|**Paso 4:** El sistema verifica los datos ingresados|
| | |**Paso 5:** El sistema registra la sesion iniciada y habilita las acciones del empelado mobiliario|

| | | 
| -- | -- |
| **Curso Alterno:** |**Paso alternativo 4:** Usuario o contraseña invalidos. El sistema informa el error. Vuelve al paso 2.|
| **Postcondición:** |El inicio se sesion se realiza con exito. | 
