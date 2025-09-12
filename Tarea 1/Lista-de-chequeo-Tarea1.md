# Lista de Chequeo para Tarea # 1

## 1. Accesibilidad Inicial y Carga

- [ ] El sitio carga correctamente (sin errores de carga o fallos visibles).
- [ ] El contenido principal aparece rápidamente (menos de 5 segundos).
- [ ] No hay errores evidentes (mensajes técnicos, 404, pantallas en blanco).
- [x] El sitio es _responsivo_ (se adapta a pantallas móviles/tablets).

## 2. Navegación General

- [x] El menú principal es visible y funcional.
- [x] Los enlaces llevan a las páginas correctas.
- [x] El botón "Inicio" o logo lleva a la página principal.
- [ ] Hay forma de volver atrás fácilmente o de reiniciar una acción.

## 3. Flujos Críticos

_(Estos dependerán del tipo de sistema, adaptar según el contexto y/o si aplican)_

- [x] Registro de usuario (campos obligatorios, validación, éxito).
- [x] Inicio de sesión / recuperación de contraseña.
- [x] Cierre de sesión correcto.
- [x] Creación o envío de datos (formularios, publicaciones, etc.).
- [x] Edición de datos existentes (perfil, configuraciones).
- [ ] Proceso de pago / reserva / acción principal del sistema.

## 4. Formularios y Validaciones

- [ ] Los campos requeridos están claramente marcados.
- [x] El sistema valida entradas incorrectas (email inválido, números, etc.).
- [ ] Mensajes de error son comprensibles y útiles.
- [x] Se pueden corregir errores sin reiniciar todo el formulario.
- [x] Los mensajes de éxito aparecen correctamente.

## 5. Contenido y Usabilidad

- [x] Textos sin errores ortográficos o gramaticales.
- [x] Botones y enlaces tienen nombres claros y consistentes ("Guardar", "Cancelar", etc.).
- [x] Las acciones del usuario tienen retroalimentación (mensajes, animaciones tipo _loaders_).
- [ ] No se requieren pasos innecesarios o confusos.
- [x] El sistema es intuitivo sin necesidad de instrucciones externas.

## 6. Compatibilidad Básica

- [x] Probar en al menos dos navegadores (Chrome, Firefox, Edge, Safari).
- [x] Probar en dispositivo móvil vs escritorio (modo responsivo o dispositivo real).
- [x] Probar en resolución más baja (ej. 1024x768) y más alta.

## 7. Manejo de Errores y Casos Límite

- ¿Qué ocurre si el usuario deja todo un formulario vacío?  
    El programa no permite continuar y muestra el mensaje: "Please fill out this field".
- ¿Qué pasa si introduce datos absurdos (nombre de 1000 caracteres, símbolos raros)?  
    En campos como nombre o apellidos no permite más de 20 caracteres y valida las direcciones de correo.
- ¿Qué ocurre si se recarga la página durante una acción?  
    Se pierde la información ingresada antes de recargarla.
- ¿Cómo responde el sistema si se pierde la conexión a Internet?  
    El sistema no responde correctamente.


## 8. Seguridad básica visible (sin análisis técnico)

- [x] Las contraseñas no se ven mientras se escriben (excepto si tienen un recurso para poder verlas, e.g. el "ojito").
- [ ] No se puede navegar hacia páginas privadas sin haber iniciado sesión.
- [x] El usuario no puede ver información de otros usuarios.
- [x] Después de cerrar sesión, no puedes volver con el botón "atrás".

## 9. Feedback y Soporte

- [ ] Los mensajes de ayuda, tooltips o instrucciones están presentes (si aplica).
- [x] Hay términos y condiciones / políticas de privacidad visibles (si aplica).

## 10. Aspecto General y Estabilidad

- [x] Diseño consistente entre secciones.
- [ ] Imágenes y elementos visuales se cargan correctamente.
- [ ] El sitio no se desajusta al hacer zoom (Ctrl + o -).
- [ ] No hay "pantallas muertas" sin contenido o acción clara.