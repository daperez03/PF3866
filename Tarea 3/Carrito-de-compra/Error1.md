# 🐞 Reporte de Bug

## ID  
**BUG-C001**

## Título  
**Carrito de compra - Falta etiquetas en algunos botones**

## Estado  
- [x] Nuevo  
- [ ] En revisión  
- [ ] En desarrollo  
- [ ] Resuelto  
- [ ] Cerrado  

## Reportado por  
**Daniel Pérez Morera**

## Fecha de detección  
**2025-10-22**

## Prioridad  
- ⚪ **Baja** (estética o detalle menor)

## Descripción  
El botón que se utiliza para aumentar o disminuir la cantidad de un producto en el carrito no contiene texto o etiqueta visible que describa su función.  
Este error afecta la accesibilidad del sitio, ya que las herramientas lectoras de pantalla no pueden identificar correctamente la acción del botón.  

**Error detectado:** Los botones deben tener texto discernible.

## Pasos para reproducir  
1. Iniciar sesión con un usuario válido.  
2. Agregar un producto al carrito.  
3. Hacer clic en el carrito y luego en `Ver Carrito`.  
4. Observar los botones para aumentar o disminuir la cantidad del producto.

## Resultado esperado  
Los botones para aumentar o disminuir la cantidad de un producto deben incluir un texto o etiqueta accesible que describa claramente su función (por ejemplo: “Aumentar cantidad” / “Disminuir cantidad”).

## Resultado obtenido  
Los botones para aumentar o disminuir la cantidad no tienen un texto o etiqueta accesible que indique su función.

## Evidencia  
- **Capturas de pantalla:**  
  ![Error 1.1](./Error1.1.png)  
  ![Error 1.2](./Error1.2.png)  
- **Tiquetes de `Axe Dev Tools`:**  
  - [Tiquete 1](https://axe.deque.com/issues/8e4fe2dc-f3f8-45db-bd61-b5d2d8600cf2)
  - [Tiquete 2](https://axe.deque.com/issues/f29e1966-ac5e-4554-9bbb-bf521e2b8802)

## Entorno de pruebas  
- **Navegador:** Microsoft Edge 141  
- **Dispositivo:** Escritorio  
- **Sistema operativo:** Windows 11  
- **URL o versión del sistema:** [https://roescr.com/carrito?action=show](https://roescr.com/carrito?action=show)

## Notas adicionales  
Se recomienda agregar etiquetas accesibles para cumplir con los criterios de accesibilidad **WCAG 2.1 Nivel AA**, específicamente la regla **button-name**.