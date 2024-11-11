# JavaScript: Conceptos Fundamentales

## 1. Tipos de Datos en JavaScript

JavaScript ofrece varios tipos de datos que se pueden utilizar para almacenar y manipular información. Estos tipos de datos se dividen principalmente en dos categorías: primitivos y objetos.

### Tipos de Datos Primitivos

- **String**: Representa una cadena de texto.
  ```javascript
  let texto = "Hola, mundo";

* Number: Representa números, tanto enteros como decimales.

  let numero = 42;

* Boolean: Representa un valor verdadero o falso.

  let esVerdadero = true;

* Undefined: Indica que una variable ha sido declarada pero no se le ha asignado un valor.

   let indefinido;

* Null: Representa la ausencia intencional de un valor.

  let vacio = null;

* Symbol: Un valor único e inmutable, utilizado como identificador único.

  let simbolo = Symbol("descripcion");
  
## Tipo de Dato Objeto

* Object: Colección de propiedades y valores.

let persona = {
    nombre: "Juan",
    edad: 30
};

* Array: Lista ordenada de valores.

let lista = [1, 2, 3, 4, 5];

## 2. Estructuras Condicionales: if y else

* Las estructuras condicionales permiten ejecutar diferentes bloques de código basados en ciertas condiciones.
  
* Uso de if y else
let edad = 18;

if (edad >= 18) {
    console.log("Eres mayor de edad");
} else {
    console.log("Eres menor de edad");
}
* Propósito: Las estructuras condicionales permiten que un programa tome decisiones y ejecute diferentes caminos de código según las condiciones evaluadas.

## 3. Operadores en JavaScript

# Tipos de Operadores

* Aritméticos: Realizan operaciones matemáticas.

- let suma = 5 + 3;        // 8
- let resta = 5 - 3;       // 2
- let multiplicacion = 5 * 3; // 15
- let division = 15 / 3;   // 5
- let modulo = 5 % 2;      // 1

* Comparación: Comparan dos valores.
- let esIgual = (5 == "5");     // true
- let esEstrictamenteIgual = (5 === "5"); // false

* Lógicos: Operan sobre valores booleanos.
- let y = true && false;  // false
- let o = true || false;  // true
- let no = !true;         // false

## 4. Declaración de Variables: var, let y const

var
* Alcance: Función.
* Mutabilidad: Permite redeclaración y reasignación

let
* Alcance: Bloque.
* Mutabilidad: Permite reasignación pero no redeclaración.

let edad = 25;
edad = 26;  // Reasignación permitida

const
* Alcance: Bloque.
* Mutabilidad: No permite reasignación ni redeclaración

const PI = 3.14;
// PI = 3.14159;  // Error: no se puede reasignar

# Diferencias Principales: var tiene un alcance de función y permite redeclaración, mientras que let y const tienen un alcance de bloque, con let permitiendo reasignación y const siendo inmutable.
