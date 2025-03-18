## ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

JavaScript maneja varios tipos de datos, que se dividen en dos categorías principales: primitivos y objetos.

* **Tipos de datos primitivos**:
    * **Number**: Representa valores numéricos, tanto enteros como decimales.
    * **String**: Representa secuencias de caracteres, es decir, texto.
    * **Boolean**: Representa valores lógicos, verdadero (true) o falso (false).
    * **Undefined**: Indica que una variable ha sido declarada pero no se le ha asignado un valor.
    * **Null**: Representa la ausencia intencional de cualquier valor objeto.
    * **Symbol**: (Introducido en ECMAScript 2015) Representa un valor único e inmutable.
    * **BigInt**: (Introducido en ECMAScript 2020) Representa valores numéricos enteros que son demasiado grandes para el tipo Number.
* **Objetos**:
    * Los objetos son colecciones de propiedades, donde cada propiedad es una asociación de clave-valor. Esto incluye arrays y funciones.

## ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?

Las estructuras condicionales if y else se utilizan para tomar decisiones en un programa de JavaScript.

* `if`: Ejecuta un bloque de código si una condición especificada es verdadera.
* `else`: Ejecuta un bloque de código alternativo si la condición del `if` es falsa.

Su propósito es permitir que el programa siga diferentes caminos de ejecución dependiendo de si se cumplen ciertas condiciones.

## ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

JavaScript tiene varios tipos de operadores:

* **Aritméticos**: Se utilizan para realizar cálculos matemáticos (+, -, *, /, %).
* **De asignación**: Se utilizan para asignar valores a variables (=, +=, -=, *=, /=).
* **De comparación**: Se utilizan para comparar valores (==, ===, !=, !==, >, <, >=, <=).
* **Lógicos**: Se utilizan para combinar condiciones lógicas (&&, ||, !).
* **De cadena**: Se utilizan para concatenar cadenas (+).
* **Condicional (ternario)**: Es una manera corta de escribir una sentencia if else.


Los operadores aritméticos se utilizan para realizar cálculos matemáticos básicos:

* `+`: Suma.
* `-`: Resta.
* `*`: Multiplicación.
* `/`: División.
* `%`: Módulo (resto de una división).

## ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

En JavaScript, las variables se declaran usando las palabras clave `var`, `let` o `const`.

* var:
    * Tiene un alcance de función o global.
    * Puede ser redeclarada y reasignada.
    * Tiene hoisting (la declaración de la variable se eleva al principio del alcance).
* let:
    * Tiene un alcance de bloque.
    * Puede ser reasignada, pero no redeclarada.
    * No tiene hoisting de la misma manera que var.
* const:
    * Tiene un alcance de bloque.
    * No puede ser redeclarada ni reasignada.
    * No tiene hoisting de la misma manera que var.
    * Se utiliza para declarar constantes, es decir, valores que no cambiarán.


La principal diferencia entre `var`, `let` y `const` radica en su alcance y mutabilidad. `let` y `const` fueron introducidos en ECMAScript 2015 para proporcionar un comportamiento más predecible y evitar algunos de los problemas asociados con `var`.
