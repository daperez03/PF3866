# [ROES](https://roescr.com/)
![Logo](https://roescr.com/img/cms/Logo/Logo%20ROES%20152x40%20px.png)

## Funcionalidades críticas seleccionadas

### Registro de usuario

1. [Registro exitoso de un usuario](./Registro-de-usuario/Prueba1.md)
2. [Registro de un usuario ya existente](./Registro-de-usuario/Prueba2.md)
3. [Registro de un usuario sin aceptar las políticas](./Registro-de-usuario/Prueba3.md)
4. [Leer las políticas al registrar un usuario](./Registro-de-usuario/Prueba4.md)

### Inicio de sesión

1. [Inicia sesión exitosamente](./Inicio-de-sesion/Prueba1.md)
2. [Inicia sesión con un usuario que no existe](./Inicio-de-sesion/Prueba2.md)
3. [Iniciar sesión sin contraseña](./Inicio-de-sesion/Prueba3.md)
4. [Iniciar sesión con un correo invalido](./Inicio-de-sesion/Prueba4.md)

### Recuperación de contraseña

1. [Recupera contraseña exitosamente](./Recuperacion-de-contrasena/Prueba1.md)
2. [Recupera contraseña con un correo invalido](./Recuperacion-de-contrasena/Prueba2.md)

### Agregar un objeto al carrito

1. [Agregar un producto al carrito de compra rápidamente](./Agregar-un-objeto-al-carrito/Prueba1.md)
2. [Agregar un producto al carrito de compra](./Agregar-un-objeto-al-carrito/Prueba2.md)
3. [Agregar dos productos al carrito de compra](./Agregar-un-objeto-al-carrito/Prueba3.md)
4. [Agregar cero productos al carrito de compra](./Agregar-un-objeto-al-carrito/Prueba4.md)
5. [Eliminar un producto del carrito de compras](./Agregar-un-objeto-al-carrito/Prueba5.md)
6. [Eliminar un producto del carrito de compras rápidamente](./Agregar-un-objeto-al-carrito/Prueba6.md)


## Política de validación

<!-- ¿qué hacer si alguna prueba falla? y ¿qué porcentaje de 
estas pruebas debe pasar para considerar válido un 
deployment?  -->

Las pruebas smoke se aplican sobre las funcionalidades más críticas del sistema, aquellas cuyo fallo impactaría directamente el flujo de compra y la experiencia del usuario. Por ello, se establecen las siguientes políticas estrictas para validar cualquier despliegue:

1. **Ejecución obligatoria de pruebas:**  
	Todas las pruebas smoke deben ejecutarse en cada ciclo de despliegue, sin excepción. La omisión de alguna prueba invalida el proceso de validación.

2. **Registro de usuario:**  
	Todas las pruebas relacionadas con el registro de usuario deben aprobarse estrictamente. No se permite ningún fallo en este flujo, ya que afecta la captación de nuevos clientes.

3. **Inicio de sesión:**  
	Las pruebas 1, 2 y 3 del flujo de inicio de sesión deben cumplirse sin errores. Esto garantiza que los usuarios puedan acceder al sistema en condiciones normales y ante errores comunes.

4. **Recuperación de contraseña:**  
	El sistema debe permitir recuperar la contraseña exitosamente. Si esta funcionalidad falla, el despliegue no puede ser aprobado.

5. **Funciones rápidas de carrito:**  
	Al menos una de las dos funciones que hay para agregar o eliminar producto del carrito debe funcionar correctamente. El fallo de ambas implica la suspensión del despliegue.

6. **Criterio de bloqueo de despliegue:**  
	Si alguna de las condiciones anteriores no se cumple, el despliegue debe ser bloqueado inmediatamente. El objetivo es evitar pérdidas económicas y proteger la reputación del negocio.

7. **Documentación y revisión:**  
	Los resultados de todas las pruebas deben ser documentados de forma clara y accesible. Antes de aprobar el despliegue, un responsable debe revisar y validar los resultados.

8. **Porcentaje de aprobación:**  
	No se establece un porcentaje mínimo de pruebas aprobadas: todas las pruebas críticas indicadas deben cumplirse. El despliegue solo se considera válido si se cumplen todos los criterios anteriores.
