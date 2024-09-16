| | |
| - | - |
| **Nombre del caso de uso:** | Dar de alta un mobiliario |
| **Descripción:** | En este caso de uso se describe el evento en el que el empleado da de alta un mobiliario |
| **Actores:**  | Empleado mobiliario |
| **Precondiciones:** | El empleado debe estar correctamente autenticado |
| | |

| | | | 
| - | - | - | 
| **Curso Normal:** | **Acción del Actor** | **Respuesta del Sistema** |
| | **Paso 1:** El empleado selecciona la opcion dar de alta un mobiliario | **Paso 2:** El sistema solicita en pantalla los siguientes datos: Codigo de inventario, tipo de mueble, fecha de creacion, fecha de ultimo mantenimiento, estado(libre, de baja, alquilado) y el precio de alquiler|
| | **Paso 3:**	El empleado ingresa los datos solicitados|**Paso 4:** El sistema verifica que el codigo no este repetido|
| | |**Paso 5:** El sistema da de alta el mobiliario|

| | | 
| -- | -- |
| **Curso Alterno:** |**Paso alternativo 4:** El codigo se encuentra repetido. El alta no se realiza y se notifica al empleado. Volver al paso 2.|
| **Postcondición:** |El alta del mobiliario se realizo con exito. | 
