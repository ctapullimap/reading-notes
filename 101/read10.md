# READ 10: Arreglos y Control de Flujo

## Reflexiona y Practica

### Preguntas y Respuestas

---

#### 1. ¿Qué es “Control Flow” (Control de Flujo)?

El **control de flujo** en programación se refiere al orden en el que se ejecutan las instrucciones de un programa. Por defecto, las instrucciones se ejecutan secuencialmente, una tras otra. Sin embargo, mediante estructuras de control como condicionales (`if`, `else if`, `else`), bucles (`for`, `while`, `do...while`) y declaraciones de salto (`break`, `continue`), podemos alterar este flujo para tomar decisiones y repetir acciones según ciertas condiciones. Esto permite que el programa responda de manera dinámica a diferentes situaciones y entradas, ejecutando código específico según sea necesario.

---

#### 2. ¿Qué es una “function” (Función) de JavaScript?

Una **función** en JavaScript es un bloque de código reutilizable que realiza una tarea específica o calcula un valor. Las funciones permiten estructurar el código de manera modular, facilitando la lectura, mantenimiento y reutilización. Se pueden definir con la palabra clave `function`, seguida de un nombre, paréntesis que pueden contener parámetros, y un bloque de código entre llaves `{}`.

**Ejemplo de una función:**

**javascript

function saludar(nombre) {
    return "¡Hola, " + nombre + "!";
}

console.log(saludar("Ana")); // Output: ¡Hola, Ana!

#### 3. ¿Cuántas veces se ejecutará un bucle “while”?

Un bucle `while` se ejecutará **mientras** la condición especificada sea verdadera (`true`). Antes de cada iteración, se evalúa la condición; si es verdadera, se ejecuta el bloque de código dentro del bucle. Este proceso se repite hasta que la condición sea falsa (`false`). Por lo tanto, el número de veces que se ejecuta un bucle `while` depende de cuándo y cómo se actualizan las variables involucradas en la condición dentro del bucle. Si la condición nunca se vuelve falsa, el bucle puede convertirse en un bucle infinito.

**Ejemplo:**

**javascript
let contador = 0;

while (contador < 5) {
    console.log("El contador es: " + contador);
    contador++;
}

#### 4. ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?

Para agregar un elemento al final de un array en JavaScript, utilizaría el método `push()`. Este método añade uno o más elementos al final del array y devuelve la nueva longitud del array.

**Sintaxis:**

**javascript
array.push(elemento1, elemento2, ..., elementoN);
