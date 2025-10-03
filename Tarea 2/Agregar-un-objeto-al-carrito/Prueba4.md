# Caso de Prueba: Agregar cero productos al carrito de compra

## ID

CT-404

## Objetivo

Verificar que el sistema no permita agregar 0 productos al carrito de compras.

## Precondiciones

- Usuario con sesión iniciada.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Pasos

1. Acceder a la [página principal](https://roescr.com/).
2. Buscar y seleccionar un producto.
3. Hacer click en el producto.
4. Ingresar "0" en el campo de cantidad.

## Resultado Esperado

- Se muestra un mensaje de error indicando que la cantidad debe ser mayor a 0.

## Resultado Obtenido

- No se muestra un mensaje de error, pero no permite ingresar números menores a 1.

## Estado de la prueba

✅ Pasó


## Observaciones

- Sería recomendable mostrar un mensaje de error.

<video src="Prueba4.mp4" controls>
    Tu navegador no soporta la reproducción de video.
</video>

[Ver video](./Prueba4.mp4)
