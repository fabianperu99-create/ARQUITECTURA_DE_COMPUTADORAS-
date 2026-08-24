# Practica 1: Compuertas Lógicas Básicas

## Objetivo
Implementar y comprobar el funcionamiento de las compuertas lógicas AND, 
OR y XOR utilizando circuitos integrados de la serie 74HC.

## Materiales
- 1x Arduino UNO
- 1x 74HC08 - Quad 2-Input AND Gate
- 1x 74HC32 - Quad 2-Input OR Gate  
- 1x 74HC86 - Quad 2-Input XOR Gate
- 1x Protoboard
- 1x DIP Switch de 4 pines
- 2x LEDs + 2x Resistencias 220Ω
- Cables de conexión

## 1. Compuerta AND - 74HC08
La salida es 1 únicamente cuando ambas entradas son 1.
![AND](capturas/compuerta_AND.png)

**Tabla de verdad:**
| A | B | Y = A·B |
|---|---|---------|
| 0 | 0 |    0    |
| 0 | 1 |    0    |
| 1 | 0 |    0    |
| 1 | 1 |    1    |

## 2. Compuerta OR - 74HC32
La salida es 1 cuando al menos una entrada es 1.
![OR](capturas/compuerta_OR.png)

**Tabla de verdad:**
| A | B | Y = A+B |
|---|---|---------|
| 0 | 0 |    0    |
| 0 | 1 |    1    |
| 1 | 0 |    1    |
| 1 | 1 |    1    |

## 3. Compuerta XOR - 74HC86
La salida es 1 cuando las entradas son diferentes.
![XOR](capturas/compuerta_XOR.png)

**Tabla de verdad:**
| A | B | Y = A⊕B |
|---|---|---------|
| 0 | 0 |    0    |
| 0 | 1 |    1    |
| 1 | 0 |    1    |
| 1 | 1 |    0    |

## Conclusión
Se verificó el funcionamiento de las 3 compuertas básicas.
La compuerta XOR es la base para los sumadores en la ALU de un procesador.
