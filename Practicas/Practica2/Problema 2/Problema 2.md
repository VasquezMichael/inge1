## Problema 2: Posgrado 

Suponga que trabaja en el área de sistemas de la Facultad de Informática y se le solicitó la automatización del pago de carreras de posgrado. Inicialmente se coordinó una reunión con el director del posgrado y se obtuvo la siguiente información: 

Ya que no se desea seguir cobrando el dinero en la secretaría, es necesario que los alumnos puedan pagar las carreras vía web. Como el director de posgrado no realiza tareas administrativas nos recomendó hablar con el secretario académico. 

De la entrevista con el secretario académico se obtuvo la siguiente información: 

Es necesario **cargar las carreras** a un sistema. En esta primera versión del sistema sólo se nos pidió esta funcionalidad, **sin la modificación ni eliminación**. De cada carrera se conoce: nombre de la carrera **(no puede repetirse)**, duración en años (a partir de la consulta del estatuto de posgrado se obtuvo que **como máximo son 5 años**), costo y cantidad máxima de cuotas para el pago. **La carga de las carreras no la realiza el secretario académico sino un empleado administrativo**. 

Al preguntarle por la dinámica del sistema, el secretario académico nos derivó con el jefe del área administrativa, con el cual hicimos otra entrevista y pudimos obtener la siguiente información:

El requerimiento fue que el alumno ingrese a la web de posgrado y pueda **registrarse** ingresando: nombre, apellido, nombre de usuario **(único)** y contraseña **(más de 6 dígitos)**. Cualquier alumno previamente registrado, puede **iniciar sesión** con su nombre de usuario y contraseña, habilitándose la inscripción a alguna de las carreras. Para ejemplificar esta funcionalidad nos otorgaron acceso al sistema SIGEF, el cual realiza funcionalidades similares para las carreras de grado. Para **inscribirse**, el alumno deberá seleccionar la carrera, ingresar la cantidad de cuotas a **pagar**, ingresar el número de tarjeta y, en caso de que la tarjeta sea válida y tenga fondos, se hará efectivo el cobro y la inscripción. La tarjeta de crédito se valida a través de un servicio del banco con el cual la universidad tiene convenio. Luego de efectuado el cobro, el sistema debe imprimir dos comprobantes, uno de inscripción y otro de pago. La única forma que tiene el alumno de pagar es con tarjeta de crédito.

> **Rol de usuarios**
>- Empleado administrativo
>- Alumnos

> **Historias de usuario**
> - [[Ingenieria de Software/Practica-2/Problema-2/autentificarme]]
>- [[cargar las carreras]]
>- [[Ingenieria de Software/Practica-2/Problema-2/registrarse]]
>- [[Ingenieria de Software/Practica-2/Problema-2/iniciar sesión]]
>- [[Ingenieria de Software/Practica-2/Problema-2/cerrar sesión]]
>- [[inscribirse]]
>- [[pagar]]


#Practica-2