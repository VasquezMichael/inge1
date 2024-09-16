| | |
| - | - |
| **Nombre del caso de uso:** |Cargar las carreras |
| **Descripción:** |En este caso se describe el evento en que el el empleado administrativo carga las carreras en el sistema |
| **Actores:**  |Empleado administrativo|
| **Precondiciones:** |Tener una sesion activa !!Preguntar esto!
| | |

| | | | 
| - | - | - | 
| **Curso Normal:** | **Acción del Actor** | **Respuesta del Sistema** |
|| **Paso 1:** El empleado administrativo selecciona la opcion Cargar carrera |**Paso 2:** El sistema solicita los siguientes datos: Nombre de la carrera(No puede repetirse), duracion en años(Maximo 5 años), costo y cantidad maxima de cuotas para el pago|
|| **Paso 3:** El empleado ingresa los datos solicitados|**Paso 4:** El sistema valida los datos solicitados|
|||**Paso 5:** El sistema registra la nueva carrera|
| -- | -- |
| **Curso Alterno:** |**Paso alternativo 4:** Ya existe una carrera con el mismo nombre. Se notifica. Volver al paso 2|**Paso alternativo 4:** La cantidad de años excede el maximo. Se informa. Volver al paso 2|
| "	" ||
| **Postcondición:** |El registro de la carrera se realiza con exito.|| 
