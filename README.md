# Simulación de un Historial de Navegación con Stacks y Queues

## Descripción
Este proyecto simula el comportamiento de un navegador web utilizando dos estructuras de datos fundamentales:

- **Pilas (Stack<T>)** → Para manejar el historial de navegación (ir hacia atrás).
- **Colas (Queue<T>)** → Para manejar páginas en espera que se desean visitar después.

## Objetivos
- Comprender el uso de **pilas y colas** en un escenario real.
- Practicar métodos de **inserción y eliminación** en estructuras de datos.
- Simular cómo funcionan navegadores con historial y lista de páginas por visitar.

## Funcionalidades
1. **Visitar nueva página** → Se agrega al historial (Stack).
2. **Ir hacia atrás** → Retrocede a la página anterior eliminando la última visitada.
3. **Agregar página en espera** → Se añade a la cola (Queue).
4. **Visitar siguiente página en espera** → Se extrae de la cola y pasa al historial.
5. **Mostrar historial** → Lista todas las páginas visitadas.
6. **Mostrar páginas en espera** → Lista de URLs pendientes por visitar.

## Ejemplo de ejecución

--- Menú Navegador ---

Visitar nueva página

Ir hacia atrás (Historial)

Agregar página en espera

Visitar siguiente página en espera

Mostrar historial

Mostrar páginas en espera

Salir


## Tecnologías
- Lenguaje: **C#**
- Entorno: **.NET Console Application**

## Autor
Desarrollado como parte de un **laboratorio práctico de estructuras de datos**.
