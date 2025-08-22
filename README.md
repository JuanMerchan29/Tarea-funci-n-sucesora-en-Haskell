## Operaciones Matemáticas con Sucesor y Antecesor (Python & Haskell)
Introducción

El propósito de este proyecto es mostrar cómo a partir de dos funciones muy simples se pueden construir las operaciones aritméticas básicas: suma, resta, multiplicación y división.

Las funciones clave son:

Sucesor: obtiene el número inmediatamente mayor a uno dado.

Antecesor: obtiene el número inmediatamente menor a uno dado.

A partir de estas dos operaciones elementales, se pueden definir todas las demás, lo que refleja cómo las bases más simples pueden dar origen a procesos más complejos.

# Conceptos 

Sucesor(n): devuelve el número que sigue después de n.

Ejemplo: sucesor(3) = 4

Antecesor(n): devuelve el número que precede a n.

Ejemplo: antecesor(3) = 2

# Operaciones Definidas

Suma(a, b): aplicar sucesor sobre a, b veces.

Resta(a, b): aplicar antecesor sobre a, b veces.

Multiplicación(a, b): realizar sumas repetidas de a.

División(a, b): realizar restas sucesivas de b hasta que a sea menor que b (contando las veces).

# Operaciones Definidas

Suma(a, b): sumar con sucesor hasta que b llegue a cero.

Resta(a, b): restar con antecesor hasta que b sea cero.

Multiplicación(a, b): suma repetida.

División(a, b): resta repetida hasta que a sea menor que b.

# Conclusión

Este ejercicio evidencia que, con únicamente dos funciones básicas, es posible construir todas las operaciones matemáticas elementales.
Aunque los lenguajes de programación ya incluyen estas operaciones de forma nativa, este enfoque resulta útil para comprender desde cero cómo se estructuran las matemáticas en un entorno computacional
