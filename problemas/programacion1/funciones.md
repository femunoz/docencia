
### Problema 1: Suma de los primeros N números naturales

**Objetivo:** Crear una función que sume todos los números enteros desde 1 hasta `n`.

* **Enunciado:** Escribe una función recursiva `int suma(int n)` que reciba un entero positivo y retorne la suma de 1 a n.
* **Ejemplo:** `suma(5)` debería retornar `15` (5+4+3+2+1).

```c
int suma(int n) {
    // Caso Base: Si llegamos a 0 (o 1), la suma termina.
    if (n == 0) {
        return 0;
    }
    // Caso Recursivo: n actual más la suma de los anteriores
    else {
        return n + suma(n - 1);
    }
}

```

---

### Problema 2: Cálculo de Potencia

**Objetivo:** Implementar la operación de potencia sin usar la librería `math.h`.

* **Enunciado:** Escribe una función recursiva `int potencia(int base, int exponente)` que calcule el valor de `base` elevado a `exponente`. Asume exponentes positivos.
* **Ejemplo:** `potencia(2, 3)` debería retornar `8`.

```c
int potencia(int base, int exponente) {
    // Caso Base: Cualquier número elevado a 0 es 1
    if (exponente == 0) {
        return 1;
    }
    // Caso Recursivo: base multiplicada por la potencia con un grado menos
    else {
        return base * potencia(base, exponente - 1);
    }
}

```

---

### Problema 3: Conteo de Dígitos

**Objetivo:** Trabajar con la división entera para reducir el problema.

* **Enunciado:** Escribe una función recursiva `int contarDigitos(int n)` que retorne la cantidad de dígitos que tiene un número entero positivo.
* **Ejemplo:** `contarDigitos(450)` debería retornar `3`.

```c
int contarDigitos(int n) {
    // Caso Base: Si el número es menor a 10, solo tiene 1 dígito.
    if (n < 10) {
        return 1;
    }
    // Caso Recursivo: 1 (por el dígito actual) + cuenta del resto del número
    else {
        return 1 + contarDigitos(n / 10);
    }
}

```

---

**💡 Tip Pedagógico para ED:**
Estos ejercicios son perfectos para hacer el "traza de escritorio" (prueba de escritorio) en la pizarra. Dibujar la "Pila de Llamadas" (Stack) visualmente ayuda mucho a que los estudiantes entiendan que la recursividad consume memoria y cómo se van resolviendo los retornos en cadena inversa.
