## Laboratorios de Python – Fundamentos
Descripción

Este repositorio contiene la solución a los laboratorios correspondientes a las primeras secciones del curso de Python. En estos ejercicios se trabajan conceptos básicos como:

Uso de la función print()
Manejo de cadenas y literales
Operadores matemáticos
Variables y expresiones

- Sección 1 – Función print()

Laboratorio: Trabajando con la función print()
Código:
print("¡Hola, Mundo!")
print("Ivan")
Preguntas

¿Qué pasa al quitar las comillas?
Se genera un error de tipo:

NameError

porque Python interpreta el texto como una variable no definida.

¿Qué pasa al quitar los paréntesis?

Se genera un error de tipo:

SyntaxError

porque la función print requiere paréntesis en Python 3.

Laboratorio: print() y sus argumentos
Código
print("Programming", "Essentials", "in", sep="***", end="...")
print("Python")

Laboratorio: Dando formato a la salida
Código
print("    *\n   * *\n  *   *\n *     *\n***   ***\n  *   *\n  *   *\n  *****")

- Sección 2 – Literales

Laboratorio: Literales de Python - Cadenas
Código
print("\"Estoy\"\"\"aprendiendo\"\"\"\"\"Python\"\"\"")

- Sección 3 – Operadores

Ejercicios de operadores
Ejercicio 1
5 + 3 * 2

Resultado: 11
Explicación: primero se multiplica (3 * 2 = 6), luego se suma (5 + 6).

Ejercicio 2
8 / 2 + 4 * 3

Resultado: 16.0
Explicación: división y multiplicación primero → 4 + 12.

Ejercicio 3
(7 + 3) * 2 - 5

Resultado: 15

Ejercicio 4
10 - 4 + 2 * 3

Resultado: 12

Ejercicio 5
(10 / 2) * (3 + 2) - 4

Resultado: 21.0

Ejercicio 6
2 + 3 * (4 - 1)

Resultado: 11

Ejercicio 7
5 * 2 ** 3

Resultado: 40

Ejercicio 8
6 + 4 / 2 ** 2

Resultado: 7.0

Ejercicio 9
10 % 3 + 2 * 5

Resultado: 11

Ejercicio 10
(8 + 2) * 3 ** 2

Resultado: 90

Ejercicio 11
7 + 2 * (3 + 5) / 4

Resultado: 11.0

Ejercicio 12
2 ** 3 * 4 / 2

Resultado: 16.0

Ejercicio 13
9 - 6 + 3 ** 2

Resultado: 12

Ejercicio 14
(7 - 2) * 5 + 3 ** 2

Resultado: 34

Ejercicio 15
4 * 2 ** 3 / 8 + 1

Resultado: 5.0

- Sección 4 – Variables

Laboratorio: Variables
Código
john = 3
mary = 5
adam = 6

print(john, mary, adam)

total_apples = john + mary + adam

print(total_apples)

print("Número total de manzanas:", total_apples)

Laboratorio: Convertidor simple
Código:
kilometers = 12.25
miles = 7.38

miles_to_kilometers = miles * 1.61
kilometers_to_miles = kilometers / 1.61

print(miles, "millas son", round(miles_to_kilometers, 2), "kilómetros")
print(kilometers, "kilómetros son", round(kilometers_to_miles, 2), "millas")

Laboratorio: Operadores y expresiones
Código:
x = 0
x = float(x)

y = 3 * x**3 - 2 * x**2 + 3 * x - 1

print("y =", y)

Conclusiones:
- Python permite trabajar fácilmente con texto y números usando print().
- Los operadores tienen prioridad que afecta el resultado de las expresiones.
- Las variables permiten almacenar y reutilizar datos.
- Es importante entender los tipos de datos (int, float, string).
- Los errores son parte del aprendizaje y ayudan a comprender mejor el lenguaje.

