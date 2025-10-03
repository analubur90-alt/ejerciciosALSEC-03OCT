Este repositorio contiene el desarrollo de ejercicios del 3 de Octubre. Incluye problemas de LeetCode y un programa en C++ que recibe operaciones aritméticas desde consola.
1. **Two Sum (LeetCode #1)**
   - Problema clásico de búsqueda de dos números en un arreglo cuya suma sea igual a un valor objetivo.
   - Se implementa una solución optimizada con complejidad **O(n)** usando un `unordered_map`.

2. **Palindrome Number (LeetCode #9)**
   - Verificación de si un número entero es un palíndromo.
   - Implementación sin convertir el número a cadena (trabajando con enteros).

3. **Programa con argumentos por consola (Callbacks + operaciones aritméticas)**
   - El programa recibe 3 argumentos:
     - Operando 1
     - Operador (`+`, `-`, `*`, `x`, `/`)
     - Operando 2
   - Ejemplo de uso:
     ```bash
     ./operacion 2 + 5
     ```
     Salida:
     ```
     El resultado de la operación es: 7
     ```
   - Incluye validación de entradas inválidas y manejo de errores (ejemplo: división por cero).
