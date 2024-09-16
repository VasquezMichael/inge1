> **ID**: Dar de alta
> **Titulo**: **Como** encargado **quiero** [[autentificarme]] en el sistema **para poder** dar de alta los mobiliarios.
> **Reglas de negocio**:
>- No pueden existir codigos repetidos.
>- El precio debe cargarse en dolares.//Esta no debe estar porque no afecta al sistema, ya que no le daremos la opcion de seleccionar otra moneda.

> **Criterios de aceptacion(Dar de alta)**
>- **Escenario 1**: Dar de alta con exito.
> **Dado** que se ingresa el codigo de inventario "123" el cual no se encuentra repetido. Se ingresa el tipo del mueble, fecha de creacion 1/01/2000, fecha de ultimo mantenimiento 2/02/2000, estado (libre, de baja, alquilado) y el precio de Usd100.
> **Cuando** se ingresa el codigo "123" y se quiere dar de alta.
> **Entonces**  el sistema da de alta un mobiliario. 
>
> - **Escenario 2**: Alta fallida por código de inventario repetido
> **Dado** que el encargado ingresa código de inventario 123 que ya se encuentra en el sistema , tipo de mueble untipo, fecha de creación 12/02/2000, fecha de último mantenimiento 12/02/2010, estado (libre, de baja, alquilado) y el precio de alquiler usd200,
> **Cuando** ingresa el codigo de inventario "123" y le da al boton "dar de alta",
> **Entonces** el sistema informa que el código de inventario ya existe. 
> 

