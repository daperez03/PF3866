# Caso de Prueba: Registro de un usuario ya existente

## ID

CT-102

## Objetivo

Verificar que el formulario de registro de usuario genere un error cuando se intenta registrar un usuario ya existente.

## Precondiciones

- El usuario debe estar registrado previamente.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Tratamiento: Mr.
- Nombre de pila: Juanito
- Apellido: Vega
- Dirección de correo electrónico: juanvainas2@mailinator.com
- Contraseña: Prueba123
- Aceptación de términos: Sí

## Pasos

1. Acceder a la [página principal](https://roescr.com/).
2. Hacer click en el botón "Inicio rápido de sesión".
3. Hacer click en el botón "¿No tiene una cuenta? Cree una aquí".
4. Ingresar los datos mencionados en el formulario.
5. Hacer click en el botón "Crear una cuenta".

## Resultado Esperado

- Aparece un mensaje de error indicando que el usuario o correo ya está registrado.

## Resultado Obtenido

- Aparece un mensaje de error indicando que el correo ya está registrado.

## Estado de la prueba

✅ Pasó

## Observaciones

<video src="Prueba2.mp4" controls>
    Tu navegador no soporta la reproducción de video.
</video>
