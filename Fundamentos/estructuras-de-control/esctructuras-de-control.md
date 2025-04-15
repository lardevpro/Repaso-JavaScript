# Estructuras de Control en Programación

Las **estructuras de control** son instrucciones que permiten modificar el flujo de ejecución de un programa, basándose en condiciones o repeticiones. Son fundamentales para la toma de decisiones y la repetición de tareas en la programación.

## Tipos de Estructuras de Control

1. **Estructuras de Selección (Condicionales)**: Permiten ejecutar un bloque de código u otro según se cumpla o no una condición.
   - **if**: Ejecuta un bloque de código si una condición es verdadera.
   - **else**: Ejecuta un bloque de código si la condición de un `if` es falsa.
   - **else if**: Permite verificar múltiples condiciones dentro de una estructura condicional.

### Ejemplo de `if`, `else` y `else if`

int edad = 18;

if (edad >= 18) { System.out.println("Eres mayor de edad."); } else { System.out.println("Eres menor de edad."); }

markdown
Copiar
Editar

2. **Estructuras de Repetición (Bucles)**: Permiten ejecutar un bloque de código repetidamente mientras se cumpla una condición.
   - **for**: Se utiliza cuando sabemos cuántas veces queremos repetir un bloque de código.
   - **while**: Ejecuta un bloque de código mientras se cumpla una condición.
   - **do while**: Similar a `while`, pero la condición se evalúa después de ejecutar el bloque de código, asegurando que siempre se ejecute al menos una vez.

### Ejemplo de `for`

for (int i = 0; i < 5; i++) { System.out.println("Valor de i: " + i); }

shell
Copiar
Editar

### Ejemplo de `while`

int i = 0; while (i < 5) { System.out.println("Valor de i: " + i); i++; }

cpp
Copiar
Editar

### Ejemplo de `do while`

int i = 0; do { System.out.println("Valor de i: " + i); i++; } while (i < 5);

kotlin
Copiar
Editar

3. **Estructuras de Salida (Interrupción del flujo)**: Permiten controlar el flujo de ejecución, interrumpiendo el ciclo o función de forma anticipada.
   - **break**: Sale de un bucle o switch de forma inmediata.
   - **continue**: Salta la iteración actual y continúa con la siguiente.
   - **return**: Termina la ejecución de una función y devuelve un valor (si es necesario).

### Ejemplo de `break` y `continue`

for (int i = 0; i < 10; i++) { if (i == 5) { break; // Sale del bucle cuando i es 5 } if (i % 2 == 0) { continue; // Salta la iteración si i es par } System.out.println("Valor impar de i: " + i); }

shell
Copiar
Editar

## Resumen
Las estructuras de control son herramientas clave para gestionar el flujo de ejecución de un programa. Estas permiten tomar decisiones, repetir tareas y salir de bucles o funciones cuando sea necesario, facilitando la creación de programas dinámicos y eficientes.
Este archivo .md ofrece una explicación concisa de las principales estructuras de control, con ejemplos prácticos en código. Puedes copiarlo y usarlo tal cual en un archivo Markdown.