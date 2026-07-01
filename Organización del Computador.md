# Organización del Computador — Plan de estudio personal

Final: 24 Julio (2da fecha)
Backup: 7 Agosto (3ra fecha)
Prioridad: ALTA

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Jue 2 Julio | Primer día de estudio ODC |
| Lun 20 Julio | Final PyE |
| Dom 19 Julio | Libre — descanso pre-final PyE |
| Jue 24 Julio | Final ODC (2da fecha) |
| Jue 7 Agosto | Final ODC (3ra fecha) |

---

## Contexto académico

- Parcial 1 (TP1–TP5): aprobado con 3 — base floja, necesita repaso real
- Parcial 2 (TP6–TP9): desaprobado con 2 — base muy floja, INV profunda obligatoria
- Assembler LEGv8 (TP6–TP9): tema más problemático, requiere más tiempo

---

## Estructura del final (basado en finales 2024 y 2025)

| Tipo | Contenido | TP |
|---|---|---|
| Lógica combinacional | División binaria, circuito desde tabla de verdad | TP1–TP3 |
| Memorias | Mapa de memoria, conexión de chips | TP4 |
| Circuitos secuenciales | Máquina de estados, detector de patrones | TP5 |
| Assembler LEGv8 | Leer, escribir, optimizar, ensamblar código | TP6–TP8 |
| ISA / Datapath | Tabla de señales, modificar arquitectura | TP9 |

---

## Días disponibles

| Período | Días | Carga ODC |
|---|---|---|
| Mié 1 julio | ⛔ libre | — |
| Jue 2 – Vie 3 julio | 2 días completos | 4hs/día |
| Sáb 4 julio | ⛔ perdido | — |
| Dom 5 – Vie 10 julio | mañanas | 2hs/día |
| Sáb 11 – Sáb 19 julio | días completos | 4hs/día |
| Dom 20 julio | Final PyE | — |
| Lun 21 – Mié 23 julio | días completos | 4hs/día |
| Jue 24 julio | ⚠️ FINAL ODC | — |

---

## Ejercicios por TP — selección final

> Se incluyen todos los ejercicios salvo los marcados como opcionales o muy teóricos sin aparición en finales.
> Prioridad máxima a los 5 tipos de problemas del final.

| TP | Ejercicios | Total |
|---|---|---|
| TP1 | 1, 2, 3, 4, 5, 6, 7, 8, 9 | 9 |
| TP2 | 1, 2, 3, 4, 5 | 5 |
| TP3 | 1, 2, 4, 5, 7, 9, 10 | 7 |
| TP4 | 1, 2, 3, 4, 6, 7, 8 | 7 |
| TP5 | 1, 2, 3, 6, 7, 8, 9, 10, 11, 13 | 10 |
| TP6 | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11 | 11 |
| TP7 | 1, 2, 3, 4, 5, 6, 7, 8 | 8 |
| TP8 | 1, 2, 3, 4, 5, 6, 7, 8, 9 | 9 |
| TP9 | 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11 | 11 |
| **Total** | | **77** |

---

## Sesiones programadas

> INV = leer fuente + anotar hoja de investigación en tus palabras
> Pizarrón obligatorio para todos los ejercicios
> 4hs días completos, 2hs días de mañana

---

### JULIO — Semana 1 (2 al 4)

**Mié 1** ⛔ — Sin sesión (descanso)

**Jue 2** *(día completo — 4hs)*
- INV: Sistemas de numeración — binario, hexadecimal, complemento a 2, IEEE 754
  - 📖 Patterson & Hennessy — Apéndice B, Secciones B.1 a B.3
  - 🎥 YouTube: "Two's Complement" — Ben Eater
  - 🎥 YouTube: "IEEE 754 Floating Point" — Computerphile
- Ejercicios: TP1 ej. 1, 2, 3, 4
  - *Ej 1* — Conversión hexadecimal → binario 32 bits
    - 📖 P&H Apéndice B, Tabla B.1 (tabla hex-binario)
  - *Ej 2* — Conversión binario → decimal y hexadecimal
    - 📖 P&H Apéndice B, Sección B.1
  - *Ej 3* — Conversión decimal → binario sin signo 16 bits
    - 📖 P&H Apéndice B, Sección B.1
  - *Ej 4* — Complemento a 2 en registros de 8 bits
    - 📖 P&H Apéndice B, Sección B.2

**Vie 3** *(día completo — 4hs)*
- Ejercicios: TP1 ej. 5, 6, 7, 8, 9
  - *Ej 5* — Complemento a 2 → decimal
    - 📖 P&H Apéndice B, Sección B.2
  - *Ej 6* — Operaciones aritméticas: overflow y carry
    - 📖 P&H Apéndice B, Sección B.6
    - 🎥 YouTube: "Binary Addition and Overflow" — NesoBros
  - *Ej 7* — Representación en distintos tamaños de registro
    - 📖 P&H Apéndice B, Sección B.2
  - *Ej 8* — Decimal → IEEE 754 precisión simple
    - 📖 P&H Apéndice B, Sección B.5
    - 🎥 YouTube: "Floating Point Numbers" — Computerphile
  - *Ej 9* — IEEE 754 → decimal
    - 📖 P&H Apéndice B, Sección B.5

**Sáb 4** ⛔ — Sin sesión

---

### JULIO — Semana 2 (5 al 10) — Mañanas 2hs

**Dom 5** *(mañana — 2hs)*
- INV: Álgebra de Boole — postulados, teoremas, universalidad NAND/NOR
  - 📖 P&H Apéndice B, Secciones B.2 a B.3
  - 🎥 YouTube: "Boolean Algebra" — The Organic Chemistry Tutor
  - 🎥 YouTube: "NAND Gate Universal" — NesoBros
- Ejercicios: TP2 ej. 1, 2
  - *Ej 1* — Simplificación de funciones booleanas
    - 📖 P&H Apéndice B, Sección B.2 — tabla de postulados y teoremas
  - *Ej 2* — Reducción + implementación NAND
    - 📖 P&H Apéndice B, Sección B.3

**Lun 6** *(mañana — 2hs)*
- Ejercicios: TP2 ej. 3, 4, 5
  - *Ej 3* — XOR: tabla de verdad, suma de productos, implementación
    - 📖 P&H Apéndice B, Sección B.3
    - 🎥 YouTube: "XOR Gate" — Ben Eater
  - *Ej 4* — Universalidad de NAND
    - 📖 P&H Apéndice B, Sección B.3
  - *Ej 5* — Universalidad de NOR
    - 📖 P&H Apéndice B, Sección B.3

**Mar 7** *(mañana — 2hs)*
- INV: Lógica combinacional — minitérminos, Karnaugh, MUX, decodificadores
  - 📖 P&H Apéndice B, Secciones B.3 a B.6
  - 🎥 YouTube: "Karnaugh Maps" — The Organic Chemistry Tutor
  - 🎥 YouTube: "Multiplexers" — NesoBros
- Ejercicios: TP3 ej. 1, 2
  - *Ej 1* — Detector de paridad impar: tabla de verdad, canónica, NAND, PLA
    - 📖 P&H Apéndice B, Sección B.4 (PLA) y B.3 (NAND)
    - 🎥 YouTube: "Parity Checker Circuit" — NesoBros
  - *Ej 2* — Detector de error en código 5 bits
    - 📖 P&H Apéndice B, Sección B.4

**Mié 8** *(mañana — 2hs)*
- Ejercicios: TP3 ej. 4, 5
  - *Ej 4* — Minimización con Karnaugh (f1, f2, f3)
    - 📖 P&H Apéndice B, Sección B.3
    - 🎥 YouTube: "Karnaugh Map 4 variables" — The Organic Chemistry Tutor
  - *Ej 5* — Comparador de 2 bits: tabla de verdad, Karnaugh, compuertas
    - 📖 P&H Apéndice B, Sección B.5

**Jue 9** *(mañana — 2hs)*
- Ejercicios: TP3 ej. 7, 9
  - *Ej 7* — Decodificador 2x4: tablas, minimización, habilitación
    - 📖 P&H Apéndice B, Sección B.6
    - 🎥 YouTube: "Decoder Circuit" — NesoBros
  - *Ej 9* — Sumador completo con decodificador y OR
    - 📖 P&H Apéndice B, Sección B.5
    - 🎥 YouTube: "Full Adder Circuit" — Ben Eater

**Vie 10** *(mañana — 2hs)*
- Ejercicios: TP3 ej. 10
  - *Ej 10* — MUX: tabla de verdad, implementación, cascada
    - 📖 P&H Apéndice B, Sección B.6
    - 🎥 YouTube: "Multiplexer Circuit" — NesoBros
- INV: Memorias — mapa de memoria, posiciones imagen, conexión de chips
  - 📖 P&H Capítulo 5, introducción + Sección 5.1
  - 🎥 YouTube: "Memory Map" — NesoBros
  - 🎥 YouTube: "Memory Chip Select" — DrPhilFrost (buscar "memory decoding")

---

### JULIO — Semana 3 (11 al 19) — Días completos

**Sáb 11** *(día completo — 4hs)*
- Ejercicios: TP4 ej. 1, 2, 3, 4
  - *Ej 1* — Capacidad de bloques: ordenar por capacidad y palabras
    - 📖 P&H Capítulo 5, Sección 5.1 — tabla de capacidades
  - *Ej 2* — Cantidad de chips necesarios
    - 📖 P&H Capítulo 5, Sección 5.1
    - 🎥 YouTube: "Memory Organization chips" — NesoBros
  - *Ej 3* — Sistema RAM 4K×16: conexión paralelo y serie
    - 📖 P&H Capítulo 5, Sección 5.1
  - *Ej 4* — Mapa de memoria con EPROM y RAM, posiciones imagen
    - 📖 P&H Capítulo 5, Sección 5.1
    - 🎥 YouTube: "Memory Map Design" — buscar en YouTube

**Dom 12** *(día completo — 4hs)*
- Ejercicios: TP4 ej. 6, 7, 8
  - *Ej 6* — Mapa de memoria complejo con decodificador 4x16
    - 📖 P&H Capítulo 5, Sección 5.1
  - *Ej 7* — Completar señales faltantes en sistema de memoria
    - 📖 P&H Capítulo 5, Sección 5.1
  - *Ej 8* — Capacidad total + mapa + posiciones imagen + implementar nuevo bloque
    - 📖 P&H Capítulo 5, Sección 5.1
- INV: Circuitos secuenciales — FF-D, registros, máquinas de estado, detectores
  - 📖 P&H Apéndice B, Secciones B.7 a B.11
  - 🎥 YouTube: "D Flip Flop" — Ben Eater
  - 🎥 YouTube: "Finite State Machine" — NesoBros
  - 🎥 YouTube: "Sequence Detector FSM" — Neso Academy

**Lun 13** *(día completo — 4hs)*
- Ejercicios: TP5 ej. 1, 2, 3, 6
  - *Ej 1* — Registro paralelo de 4 bits con FF-D
    - 📖 P&H Apéndice B, Sección B.8
    - 🎥 YouTube: "Parallel Register" — NesoBros
  - *Ej 2* — Shift Register unidireccional de 5 bits con FF-D
    - 📖 P&H Apéndice B, Sección B.8
    - 🎥 YouTube: "Shift Register" — Ben Eater
  - *Ej 3* — Shift Register bidireccional con MUX
    - 📖 P&H Apéndice B, Sección B.8
  - *Ej 6* — Contador regresivo de 3 bits con entrada de reinicio
    - 📖 P&H Apéndice B, Sección B.9
    - 🎥 YouTube: "Binary Counter" — NesoBros

**Mar 14** *(día completo — 4hs)*
- Ejercicios: TP5 ej. 7, 8, 9, 10
  - *Ej 7* — Circuito secuencial de 4 estados con entradas E y X
    - 📖 P&H Apéndice B, Sección B.10
    - 🎥 YouTube: "FSM Design with D Flip Flops" — Neso Academy
  - *Ej 8* — Contador código Gray con entrada inc
    - 📖 P&H Apéndice B, Sección B.10
    - 🎥 YouTube: "Gray Code Counter" — NesoBros
  - *Ej 9* — Secuencia 2,3,2,4 con señal inc
    - 📖 P&H Apéndice B, Sección B.10
  - *Ej 10* — Detector de paridad de bit serial
    - 📖 P&H Apéndice B, Sección B.11
    - 🎥 YouTube: "Parity Detector FSM" — Neso Academy

**Mié 15** *(día completo — 4hs)*
- Ejercicios: TP5 ej. 11, 13
  - *Ej 11* — Detector del patrón "1011"
    - 📖 P&H Apéndice B, Sección B.11
    - 🎥 YouTube: "Sequence Detector 1011" — Neso Academy
  - *Ej 13* — Monitor de secuencia de 3 bits con señal ERR_bar
    - 📖 P&H Apéndice B, Sección B.11
- INV: LEGv8 básico — registros, instrucciones aritméticas, acceso a memoria
  - 📖 P&H Capítulo 2, Secciones 2.1 a 2.5
  - 🎥 YouTube: "ARM Assembly Introduction" — Low Level Learning
  - 🎥 YouTube: "LEGv8 Instructions" — buscar "Patterson Hennessy LEGv8"
- Ejercicios: TP6 ej. 1, 2
  - *Ej 1* — C → LEGv8: operaciones aritméticas básicas
    - 📖 P&H Capítulo 2, Sección 2.2 y 2.3
  - *Ej 2* — LEGv8 → C: operaciones aritméticas
    - 📖 P&H Capítulo 2, Sección 2.2 y 2.3

**Jue 16** *(día completo — 4hs)*
- Ejercicios: TP6 ej. 3, 4, 5, 6
  - *Ej 3* — C → LEGv8: negación y resta
    - 📖 P&H Capítulo 2, Sección 2.3
  - *Ej 4* — LEGv8 → C: SUB y negación con XZR
    - 📖 P&H Capítulo 2, Sección 2.3
  - *Ej 5* — C → LEGv8: acceso a arreglos con LDUR/STUR
    - 📖 P&H Capítulo 2, Sección 2.4
    - 🎥 YouTube: "ARM Assembly Arrays" — Low Level Learning
  - *Ej 6* — LEGv8 → C: arreglos con LSL y LDUR
    - 📖 P&H Capítulo 2, Sección 2.4

**Vie 17** *(día completo — 4hs)*
- Ejercicios: TP6 ej. 7, 8, 9, 10
  - *Ej 7* — LEGv8 → C: punteros y acceso indirecto
    - 📖 P&H Capítulo 2, Sección 2.4
  - *Ej 8* — Operaciones lógicas: LSL, ORR, ANDI
    - 📖 P&H Capítulo 2, Sección 2.6
    - 🎥 YouTube: "ARM Logical Instructions" — Low Level Learning
  - *Ej 9* — ESR: extraer campo EC con shift y AND
    - 📖 P&H Capítulo 2, Sección 2.6
  - *Ej 10* — Detectar signo de número en complemento a 2
    - 📖 P&H Capítulo 2, Sección 2.6
- Ejercicios: TP6 ej. 11
  - *Ej 11* — MOVZ y MOVK: cargar constantes de 64 bits
    - 📖 P&H Capítulo 2, Sección 2.10
    - 🎥 YouTube: "ARM MOVZ MOVK" — buscar en YouTube

**Sáb 18** *(día completo — 4hs)*
- INV: LEGv8 avanzado — branches, condition codes, loops, if/else
  - 📖 P&H Capítulo 2, Secciones 2.6 a 2.10
  - 🎥 YouTube: "ARM Assembly Branches" — Low Level Learning
  - 🎥 YouTube: "ARM Condition Codes Flags" — buscar en YouTube
- Ejercicios: TP7 ej. 1, 2, 3, 4
  - *Ej 1* — Leer dos programas y decir qué función realizan
    - 📖 P&H Capítulo 2, Sección 2.7 y 2.8
  - *Ej 2* — Valor final de X10 con branch condicional
    - 📖 P&H Capítulo 2, Sección 2.7
  - *Ej 3* — C → LEGv8: if con operador || cortocircuitado
    - 📖 P&H Capítulo 2, Sección 2.7
    - 🎥 YouTube: "ARM Assembly If Else" — Low Level Learning
  - *Ej 4* — Loops: valores finales, equivalente C, contar instrucciones
    - 📖 P&H Capítulo 2, Sección 2.8

**Dom 19** ⛔ — Libre, descanso pre-final PyE

**Lun 20** ⚠️ — FINAL PyE

**Mar 21** *(día completo — 4hs)*
- Ejercicios: TP7 ej. 5, 6, 7, 8
  - *Ej 5* — Loop con LDUR: sumar elementos de arreglo, contar instrucciones
    - 📖 P&H Capítulo 2, Sección 2.8
  - *Ej 6* — C → LEGv8: loop con LDURB y caracteres ASCII
    - 📖 P&H Capítulo 2, Sección 2.9
    - 🎥 YouTube: "ARM Assembly Strings" — Low Level Learning
  - *Ej 7* — C → LEGv8: loop doble con arreglo bidimensional
    - 📖 P&H Capítulo 2, Sección 2.9
  - *Ej 8* — Pseudoinstrucciones: CMP, MOV, NOP, NOT
    - 📖 P&H Capítulo 2, Sección 2.11
- INV: Ensamblado y desensamblado — formatos R, I, D, B, CB, IM
  - 📖 P&H Capítulo 2, Secciones 2.11 a 2.14
  - 🎥 YouTube: "ARM Instruction Encoding" — buscar en YouTube
  - 🎥 YouTube: "LEGv8 Instruction Formats" — buscar en YouTube

**Mié 22** *(día completo — 4hs)*
- Ejercicios: TP8 ej. 1, 2, 3, 4, 5
  - *Ej 1* — Extensión de signo de números de 26 bits a 64 bits
    - 📖 P&H Capítulo 2, Sección 2.12
  - *Ej 2* — Ensamblar ADDI y STUR a binario y hexadecimal
    - 📖 P&H Capítulo 2, Sección 2.12
    - 🎥 YouTube: "ARM Assembly Encoding" — buscar "LEGv8 machine code"
  - *Ej 3* — Desde campos op/Rm/Rn/Rd identificar instrucción
    - 📖 P&H Capítulo 2, Sección 2.12
  - *Ej 4* — Binario → hexadecimal → instrucción LEGv8
    - 📖 P&H Capítulo 2, Sección 2.12
  - *Ej 5* — Ejecutar programa desde memoria, dar valor final de X1
    - 📖 P&H Capítulo 2, Sección 2.12

**Jue 23** *(día completo — 4hs)*
- Ejercicios: TP8 ej. 6, 7, 8, 9
  - *Ej 6* — Decidir cuáles instrucciones se pueden codificar en LEGv8
    - 📖 P&H Capítulo 2, Sección 2.12 y 2.14
  - *Ej 7* — Ensamblar delay loops completos
    - 📖 P&H Capítulo 2, Sección 2.12
  - *Ej 8* — Alcance de saltos: branch condicional vs incondicional
    - 📖 P&H Capítulo 2, Sección 2.13
    - 🎥 YouTube: "ARM Branch Range Far Jump" — buscar en YouTube
  - *Ej 9* — Far jump: saltar al primer GiB con 2 instrucciones
    - 📖 P&H Capítulo 2, Sección 2.13
- INV: Implementación de la ISA — datapath, señales de control, latencias
  - 📖 P&H Capítulo 4, Secciones 4.1 a 4.4
  - 🎥 YouTube: "Single Cycle Datapath" — Neso Academy
  - 🎥 YouTube: "Control Unit LEGv8" — buscar en YouTube
- Ejercicios: TP9 ej. 1, 2, 3
  - *Ej 1* — Marcar bits de cada línea del datapath
    - 📖 P&H Capítulo 4, Figura 4.17
  - *Ej 2* — Porcentaje de instrucciones que usan cada bloque
    - 📖 P&H Capítulo 4, Sección 4.4
  - *Ej 3* — Completar tabla de señales de control sin mirar el libro
    - 📖 P&H Capítulo 4, Figura 4.22
  - *Ej 4* — Stuck-at-0 faults: qué instrucciones fallan por señal rota
    - 📖 P&H Capítulo 4, Sección 4.4
    - 🎥 YouTube: "Stuck at Fault Digital Circuits" — buscar en YouTube
  - *Ej 5* — Cambiar CBZ a CBNZ agregando una compuerta
    - 📖 P&H Capítulo 4, Sección 4.4
  - *Ej 6* — Ejecutar instrucción 0xf8014062 paso a paso en el datapath
    - 📖 P&H Capítulo 4, Figura 4.17 y Sección 4.4
  - *Ej 7* — Agregar instrucción B incondicional al datapath
    - 📖 P&H Capítulo 4, Sección 4.4
  - *Ej 8* — Calcular latencias para cada tipo de instrucción
    - 📖 P&H Capítulo 4, Sección 4.4
    - 🎥 YouTube: "Single Cycle Datapath Timing" — Neso Academy
  - *Ej 9* — Aumento de velocidad al quitar desplazamiento en LDUR/STUR
    - 📖 P&H Capítulo 4, Sección 4.4
  - *Ej 10* — Aceleración con ciclo de reloj variable
    - 📖 P&H Capítulo 4, Sección 4.4
  - *Ej 11* — Instrucción no documentada: identificar, nombrar, completar tabla
    - 📖 P&H Capítulo 4, Sección 4.4

**Vie 24** ⚠️ — FINAL ODC (2da fecha) — sin sesión

---

## Hojas de investigación ODC

> Una hoja por TP. Formato: definición → por qué importa → ejemplo propio → preguntas clave

- [ ] HI-01: Sistemas numéricos — complemento a 2, IEEE 754, conversiones
- [ ] HI-02: Álgebra de Boole — postulados, universalidad NAND/NOR, simplificación
- [ ] HI-03: Lógica combinacional — Karnaugh, MUX, decodificadores, PLA
- [ ] HI-04: Memorias — mapa de memoria, posiciones imagen, conexión chips
- [ ] HI-05: Circuitos secuenciales — FF-D, registros, máquinas de estado
- [ ] HI-06: LEGv8 básico — registros, instrucciones, acceso a memoria
- [ ] HI-07: LEGv8 avanzado — branches, condition codes, loops
- [ ] HI-08: Ensamblado/desensamblado — formatos, alcance de saltos
- [ ] HI-09: Implementación ISA — datapath, señales de control, latencias

---

## Ejercicios del final que aparecen siempre — practicar especialmente

1. **División binaria por 4** → circuito combinacional con shift derecho (TP3)
2. **Mapa de memoria** con ROM y RAM, indicar inicio/fin de cada bloque (TP4)
3. **Máquina de estados** detector de secuencia numérica (TP5)
4. **Leer/optimizar/ensamblar** código LEGv8 (TP6–TP8)
5. **Tabla de señales ISA** + modificar arquitectura para nueva instrucción (TP9)

---

## Notas del método

- INV primero, ejercicios después — nunca al revés
- Si no sale después de 10 minutos: anotar qué no entendés, seguir con el siguiente
- Pizarrón obligatorio: resolver sin mirar apuntes
- Para assembler: ejecutar mentalmente el código línea por línea con valores concretos
- Para máquinas de estado: siempre empezar por el diagrama de estados antes de la tabla
- Para memorias: siempre empezar por calcular cuántos bits de dirección necesita cada chip