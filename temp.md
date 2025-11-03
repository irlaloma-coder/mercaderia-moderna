# Método Caso: Mercadería Moderna – Gestión de Inventarios en C

## 1. Introducción
Este programa en C está diseñado para la PYME “Mercaderías Modernas” con el objetivo de gestionar de manera eficiente su inventario de productos.  
El sistema utiliza variables, constantes y sentencias de control (`if-else`, `switch`, `for`, `while`, `do-while`) para registrar ventas, actualizar existencias y generar estadísticas de los productos.  
Se incluyen ejemplos de datos cualitativos (opiniones del personal) y cuantitativos (cantidad de productos vendidos) para demostrar cómo se integran ambos tipos de información en la toma de decisiones.

---

## 2. Objetivos del programa
- Registrar ventas de productos y actualizar automáticamente el inventario.
- Aplicar sentencias de control para procesar datos de manera estructurada.
- Generar reportes simples de inventario y ventas.
- Integrar información cualitativa y cuantitativa para análisis interno.
- Garantizar claridad en el flujo de información y facilidad de mantenimiento del código.

---

## 3. Funcionalidades principales
1. **Registro de ventas**: Permite ingresar el código de un producto, la cantidad vendida y actualiza automáticamente el inventario.  
2. **Consulta de inventario**: Muestra el estado actual de existencias de todos los productos.  
3. **Registro de opiniones del personal**: Se pueden agregar comentarios sobre cada producto.  
4. **Generación de estadísticas básicas**: Cantidad vendida, productos agotados y productos con más movimiento.  

---

## 4. Compilación y ejecución
1. Abrir la terminal en la carpeta del proyecto.
2. Compilar con GCC:
   ```bash
   gcc mercaderia_moderna.c -o mercaderia_moderna.exe
