
### Problema 1: El Mayor de Dos Números

Cree una función que reciba dos números enteros como parámetros y retorne el valor del mayor de ellos. Si ambos números son iguales, debe retornar cualquiera de los dos.

* **Prototipo:** `int obtener_mayor(int a, int b);`
* **Ejemplo de prueba:**
* Entrada: `5, 10`  Salida esperada: `10`
* Entrada: `20, 3`  Salida esperada: `20`

---

### Problema 2: Conversor de Temperatura (Celsius a Fahrenheit)

Escriba una función que acepte una temperatura en grados Celsius (como número decimal) y devuelva su equivalente en grados Fahrenheit.
Use la fórmula: $F = (C \times 1.8) + 32$

* **Prototipo:** `float celsius_a_fahrenheit(float celsius);`
* **Ejemplo de prueba:**
* Entrada: `0.0`  Salida esperada: `32.0`
* Entrada: `100.0`  Salida esperada: `212.0`

---

### Problema 3: Detector de Vocales

Implemente una función que determine si un carácter recibido es una vocal (a, e, i, o, u). La función debe detectar tanto mayúsculas como minúsculas.

* Retorne `1` si el carácter es una vocal.
* Retorne `0` si el carácter es una consonante, número o símbolo.
* **Prototipo:** `int es_vocal(char letra);`
* **Ejemplo de prueba:**
* Entrada: `'A'`  Salida esperada: `1`
* Entrada: `'e'`  Salida esperada: `1`
* Entrada: `'z'`  Salida esperada: `0`

---

### Problema 4: Suma de los primeros N números naturales

**Objetivo:** Crear una función que sume todos los números enteros desde 1 hasta `n`.

* **Enunciado:** Escribe una función recursiva `int suma(int n)` que reciba un entero positivo y retorne la suma de 1 a n.
* **Ejemplo:** `suma(5)` debería retornar `15` (5+4+3+2+1).

---

### Problema 5: Cálculo de Potencia

**Objetivo:** Implementar la operación de potencia sin usar la librería `math.h`.

* **Enunciado:** Escribe una función recursiva `int potencia(int base, int exponente)` que calcule el valor de `base` elevado a `exponente`. Asume exponentes positivos.
* **Ejemplo:** `potencia(2, 3)` debería retornar `8`.


---

### Problema 6: Conteo de Dígitos

**Objetivo:** Trabajar con la división entera para reducir el problema.

* **Enunciado:** Escribe una función recursiva `int contarDigitos(int n)` que retorne la cantidad de dígitos que tiene un número entero positivo.
* **Ejemplo:** `contarDigitos(450)` debería retornar `3`.


