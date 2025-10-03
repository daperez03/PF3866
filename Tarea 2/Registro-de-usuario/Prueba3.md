# Caso de Prueba: Registro de un usuario sin aceptar las políticas

## ID

CT-103

## Objetivo

Verificar que el formulario de registro de usuario genere un error cuando se intente crear un usuario sin aceptar las políticas.

## Precondiciones

- El usuario no debe estar registrado previamente.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Tratamiento: Mr.
- Nombre de pila: Juanito
- Apellido: Vega
- Dirección de correo electrónico: juanvainas3@mailinator.com
- Contraseña: Prueba123

## Pasos

1. Acceder a la [página principal](https://roescr.com/).
2. Hacer click en el botón "Inicio rápido de sesión".
3. Hacer click en el botón "¿No tiene una cuenta? Cree una aquí".
4. Ingresar los datos mencionados en el formulario.
5. Hacer click en el botón "Crear una cuenta".

## Resultado Esperado

- Debe aparecer un mensaje de error indicando que el usuario debe aceptar las políticas.

## Resultado Obtenido

- El botón aparece resaltado en rojo, pero no se muestra un mensaje de error.

## Estado de la prueba

⚠️ Dudoso

## Observaciones

- Aunque el botón se resalta en rojo, el sistema debería mostrar un mensaje explícito indicando cuál es el error.

<video src="Prueba3.mp4" controls>
    Tu navegador no soporta la reproducción de video.
</video>
