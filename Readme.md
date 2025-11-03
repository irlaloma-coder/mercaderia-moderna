# Mercaderías Modernas – Gestión de Inventario en C

---

## Descripción del Proyecto

Este proyecto consiste en un programa en C para la **gestión de inventarios** de la PYME “Mercaderías Modernas”.  
El programa permite:

- Mostrar inventario de productos.
- Registrar ventas.
- Actualizar precios de productos.

Se implementaron **variables, constantes y sentencias de control** (`if-else`, `switch`, `while`, `do-while`, `for`) para gestionar la lógica del sistema sin usar estructuras complejas, apuntadores o arreglos multidimensionales.

---

## Flujo del Programa

1. Al iniciar, el sistema muestra un menú con las opciones:  
   1. Mostrar inventario  
   2. Registrar venta  
   3. Actualizar precio  
   4. Salir  

2. **Mostrar inventario**: se listan los productos, cantidades disponibles y precios.  
3. **Registrar venta**: se selecciona un producto y se ingresa la cantidad vendida; se valida disponibilidad.  
4. **Actualizar precio**: se selecciona un producto y se asigna un nuevo precio.  
5. **Salir**: termina la ejecución del programa.

---

## Requisitos

- Compilador C (GCC recomendado)  
- Sistema operativo Windows, macOS o Linux  
- Terminal o consola para ejecutar el programa

---

## Instrucciones de Ejecución

1. Guardar el archivo como `mercaderias_mod.c`.  
2. Abrir terminal y compilar:  
   ```bash
   gcc mercaderias_mod.c -o mercaderias_mod.exe
