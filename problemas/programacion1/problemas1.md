
# Guía de Ejercicios: Introducción a Funciones en C

**Instrucciones:** Implemente las siguientes funciones en lenguaje C. Para cada ejercicio, respete el prototipo sugerido y asegúrese de que la función retorne el valor correcto en lugar de imprimirlo en pantalla (salvo que se indique lo contrario).

### Ejercicio 1: El Mayor de Dos Números

Cree una función que reciba dos números enteros como parámetros y retorne el valor del mayor de ellos. Si ambos números son iguales, debe retornar cualquiera de los dos.

* **Prototipo:** `int obtener_mayor(int a, int b);`
* **Ejemplo de prueba:**
* Entrada: `5, 10`  Salida esperada: `10`
* Entrada: `20, 3`  Salida esperada: `20`



### Ejercicio 2: Conversor de Temperatura (Celsius a Fahrenheit)

Escriba una función que acepte una temperatura en grados Celsius (como número decimal) y devuelva su equivalente en grados Fahrenheit.
Use la fórmula: $F = (C \times 1.8) + 32$

* **Prototipo:** `float celsius_a_fahrenheit(float celsius);`
* **Ejemplo de prueba:**
* Entrada: `0.0`  Salida esperada: `32.0`
* Entrada: `100.0`  Salida esperada: `212.0`



### Ejercicio 3: Detector de Vocales

Implemente una función que determine si un carácter recibido es una vocal (a, e, i, o, u). La función debe detectar tanto mayúsculas como minúsculas.

* Retorne `1` si el carácter es una vocal.
* Retorne `0` si el carácter es una consonante, número o símbolo.
* **Prototipo:** `int es_vocal(char letra);`
* **Ejemplo de prueba:**
* Entrada: `'A'`  Salida esperada: `1`
* Entrada: `'e'`  Salida esperada: `1`
* Entrada: `'z'`  Salida esperada: `0`


