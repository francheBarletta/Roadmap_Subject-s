# Organización del Computador — Plan de estudio personal

Inicio de clases: 11 marzo
Fin de clases: 19 junio

Clases por semana: Miércoles y Viernes
Prioridad: ALTA — Final 3 de Julio

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Mié 17 Junio | Recuperatorio ODC (parciales 1 y 2) |
| Vie 3 Julio | Final ODC (1ra fecha) |
| Jue 24 Julio | Final ODC (2da fecha) |
| Vie 7 Agosto | Final ODC (3ra fecha) |

---

## Estado actual (15 Junio)

- TP1 al TP9: vistos en cursada, base parcial
- TP1, TP3, TP6, TP8: más sólidos — repaso + ejercicios en pizarrón
- TP2, TP4, TP5, TP7, TP9: más flojos — INV profunda primero

---

## Trabajos Prácticos

| # | Tema | Estado |
|---|---|---|
| TP1 | Sistemas numéricos | [~] repaso |
| TP2 | Álgebra de Boole | [~] INV profunda |
| TP3 | Lógica combinacional | [~] repaso |
| TP4 | Direccionamiento y decodificación de memorias | [~] INV profunda |
| TP5 | Circuitos secuenciales | [~] INV profunda |
| TP6 | Assembler LEGv8 básico | [~] repaso |
| TP7 | Assembler LEGv8 avanzado | [~] INV profunda |
| TP8 | Ensamblado y desensamblado | [~] repaso |
| TP9 | Implementación de la ISA | [~] INV profunda |

---

## Ejercicios seleccionados por TP

> 4 ejercicios por día. Se seleccionaron los más representativos de cada concepto.
> El resto del tiempo de cada sesión va a INV profunda.

| TP | Ejercicios | Cantidad |
|---|---|---|
| TP1 | 1, 2, 3, 4, 5, 6, 7, 8, 9 | 9 |
| TP2 | 1, 2, 3, 4, 5 | 5 |
| TP3 | 1, 2, 4, 5, 7, 9, 10 | 7 |
| TP4 | 1, 2, 3, 4, 6, 7, 8 | 7 |
| TP5 | 1, 2, 3, 6, 7, 8, 10, 11, 13 | 9 |
| TP6 | 1, 3, 5, 6, 7, 8, 9, 11 | 8 |
| TP7 | 1, 2, 3, 4, 5, 7, 8 | 7 |
| TP8 | 1, 2, 3, 4, 5, 6, 8 | 7 |
| TP9 | 1, 2, 3, 4, 6, 8, 10 | 7 |
| **Total** | | **76** |

---

## Guía de investigación por TP

> Para cada TP: leer el capítulo del libro → anotar en hoja de investigación con tus propias palabras → ejemplo concreto → recién después los ejercicios.
> Formato de hoja: definición → por qué importa → ejemplo propio → conexión con ejercicios

### TP1 — Sistemas de Numeración
**Libro:** Patterson & Hennessy — Apéndice B (Arithmetic), Sección B.1 a B.3
**Temas a investigar:**
- Representación binaria, hexadecimal y decimal: conversiones en ambas direcciones
- Complemento a 2: cálculo, conversión a decimal, por qué se usa en lugar de signo-magnitud
- Punto flotante IEEE 754: estructura (signo, exponente, mantisa), bias, casos especiales (NaN, ±∞, ±0)
- Overflow y carry en operaciones aritméticas

**Preguntas clave para el final:**
- ¿Por qué el complemento a 2 simplifica las operaciones aritméticas?
- ¿Qué significa que un número IEEE 754 sea normalizado?
- ¿Cuándo ocurre overflow en suma de complemento a 2?

---

### TP2 — Álgebra de Boole
**Libro:** Patterson & Hennessy — Apéndice B, Sección B.2 a B.3
**Temas a investigar:**
- Postulados y teoremas del álgebra booleana: cómo usarlos para simplificar
- Compuertas lógicas: AND, OR, NOT, NAND, NOR y sus tablas de verdad
- Universalidad de NAND y NOR: por qué cualquier función se puede implementar con una sola
- Simplificación algebraica paso a paso

**Preguntas clave para el final:**
- ¿Por qué NAND es universal?
- ¿Cómo implementar OR usando solo compuertas NAND?
- ¿Qué significa simplificar a mínimo número de literales?

---

### TP3 — Lógica Combinacional
**Libro:** Patterson & Hennessy — Apéndice B, Sección B.3 a B.6
**Temas a investigar:**
- Minitérminos y maxitérminos: cómo obtener formas canónicas desde tabla de verdad
- Mapas de Karnaugh: cómo agrupar, reglas de agrupamiento, obtener expresión mínima
- Decodificadores y MUX: funcionamiento, para qué sirven, cómo implementar funciones con ellos
- PLA (Programmable Logic Array): estructura y uso

**Preguntas clave para el final:**
- ¿Cómo pasar de tabla de verdad a suma de minitérminos?
- ¿Por qué los grupos en Karnaugh deben ser potencias de 2?
- ¿Cómo implementar cualquier función con un MUX?

---

### TP4 — Direccionamiento y Decodificación de Memorias
**Libro:** Patterson & Hennessy — Capítulo 5 (Large and Fast: Exploiting Memory Hierarchy), introducción
**Temas a investigar:**
- Mapa de memoria: qué es, cómo se construye, qué son las posiciones imagen
- Conexión en paralelo vs serie: para aumentar ancho de palabra vs capacidad
- Chip Select (CS): cómo seleccionar chips con decodificadores
- Cálculo de líneas de dirección: cuántos bits necesita cada chip

**Preguntas clave para el final:**
- ¿Cuándo se generan posiciones imagen y por qué?
- ¿Cuántos chips de X palabras necesito para construir un sistema de Y palabras?
- ¿Cómo se conectan los chips para aumentar el ancho de datos?

---

### TP5 — Circuitos Secuenciales
**Libro:** Patterson & Hennessy — Apéndice B, Sección B.7 a B.11 (Flip-Flops and Latches)
**Temas a investigar:**
- Flip-flop D: tabla de función, diferencia entre reset síncrono y asíncrono
- Registros: paralelo, shift register unidireccional y bidireccional
- Máquinas de estado: diagrama de estados, tabla de transición, cómo implementar con FF-D
- Contadores: binario, Gray, regresivo
- Detectores de patrones: cómo diseñar la máquina de estados paso a paso

**Preguntas clave para el final:**
- ¿Cuál es la diferencia entre un circuito combinacional y uno secuencial?
- ¿Cómo pasar de un diagrama de estados a una tabla de transición?
- ¿Cuántos flip-flops necesito para n estados?

---

### TP6 — Assembler LEGv8 Básico
**Libro:** Patterson & Hennessy — Capítulo 2 (Instructions: Language of the Computer), Secciones 2.1 a 2.5
**Temas a investigar:**
- Registros de LEGv8: X0-X30, XZR, SP — cuál es el rol de cada uno
- Instrucciones aritméticas: ADD, SUB, ADDI, SUBI — formato y uso
- Instrucciones de memoria: LDUR, STUR — cálculo de direcciones, offset
- Instrucciones lógicas: AND, ORR, EOR, LSL, LSR — operaciones bit a bit
- MOVZ y MOVK: cómo cargar constantes de 64 bits
- Endianness: diferencia entre big-endian y little-endian

**Preguntas clave para el final:**
- ¿Cómo calcular la dirección de A[i] en LEGv8?
- ¿Cuándo usar MOVZ vs MOVK?
- ¿Qué diferencia hay entre LDUR y LDURB?

---

### TP7 — Assembler LEGv8 Avanzado
**Libro:** Patterson & Hennessy — Capítulo 2, Secciones 2.6 a 2.10
**Temas a investigar:**
- Condition codes (flags): N, Z, C, V — qué significa cada uno y cuándo se activan
- Instrucciones de branch condicional: B.EQ, B.NE, B.LT, B.GT, B.LE, B.GE, CBNZ, CBZ
- Diferencia entre instrucciones signed (B.LT) y unsigned (B.LO)
- Implementación de if/else, loops while y for en LEGv8
- Evaluación por cortocircuito con || y &&

**Preguntas clave para el final:**
- ¿Cuándo se usa B.LT vs B.LO?
- ¿Cómo implementar un loop for en LEGv8?
- ¿Qué hace SUBIS y por qué es útil para comparar?

---

### TP8 — Ensamblado y Desensamblado de LEGv8
**Libro:** Patterson & Hennessy — Capítulo 2, Secciones 2.11 a 2.14
**Temas a investigar:**
- Formatos de instrucción: R, I, D, B, CB, IM — campos de cada uno y cantidad de bits
- Cómo ensamblar: pasar de instrucción LEGv8 a binario y hexadecimal
- Cómo desensamblar: pasar de binario/hex a instrucción LEGv8
- Alcance de saltos: cuántas instrucciones puede saltar B vs B.cond
- Far jump: cómo saltar a direcciones lejanas

**Preguntas clave para el final:**
- ¿Cuántos bits tiene el campo de offset en una instrucción CB?
- ¿Cómo saber si una instrucción es tipo R o tipo D mirando el binario?
- ¿Por qué B puede saltar más lejos que B.cond?

---

### TP9 — Implementación de la ISA
**Libro:** Patterson & Hennessy — Capítulo 4 (The Processor), Secciones 4.1 a 4.4
**Temas a investigar:**
- Datapath single-cycle: componentes (PC, memoria de instrucciones, registros, ALU, memoria de datos) y cómo se conectan
- Señales de control: Reg2Loc, ALUSrc, MemtoReg, RegWrite, MemRead, MemWrite, Branch, ALUOp
- Tabla de señales: qué vale cada señal para cada instrucción (R-type, LDUR, STUR, CBZ)
- ALU control: cómo se determina la operación de la ALU
- Latencias: cómo calcular el tiempo de cada instrucción y el período mínimo de reloj
- Fallas stuck-at-0: qué instrucciones se ven afectadas

**Preguntas clave para el final:**
- ¿Qué señal controla si el resultado que se escribe en el registro viene de la ALU o de memoria?
- ¿Por qué el período de reloj lo determina la instrucción más lenta?
- ¿Qué pasa si ALUSrc está stuck-at-0?

---

## Sesiones de estudio programadas

> 4 ejercicios por día + INV profunda
> Los días del 15 al 27 de Junio + Lun 30, Mar 1, Mié 2 (repaso), Jue 3 (FINAL)
> Dom 29: ODC liviano (Final PyE ese día)
> INV = Investigación profunda (leer libro + anotar hoja + preguntas propias)
> Pizarrón = resolver ejercicio sin mirar apuntes, comparar con carpeta

---

### JUNIO — Semana 3 (15 al 22)

**Dom 15**
- INV: TP1 completo — leer Apéndice B.1 a B.3, anotar HI-01
  - Foco: complemento a 2 (por qué funciona), IEEE 754 (estructura y casos especiales)
- Ejercicios en pizarrón: TP1 ej. 1, 2, 3, 4
*Ej 1* — Conversión hexadecimal → binario 32 bits
*Ej 2* — Conversión binario → decimal y hexadecimal
*Ej 3* — Conversión decimal → binario sin signo (16 bits)
*Ej 4* — Complemento a 2 en registros de 8 bits

**Lun 16**
- INV: TP1 continuación — IEEE 754 en profundidad, casos especiales
- Ejercicios en pizarrón: TP1 ej. 5, 6, 7, 8
*Ej 5* — Conversión complemento a 2 → decimal
*Ej 6* — Operaciones aritméticas: overflow y carry
*Ej 7* — Representación en distintos tamaños de registro
*Ej 8* — Conversión decimal → IEEE 754 precisión simple

**Mar 17** ⚠️ — RECUPERATORIO ODC — sesión liviana
- Ejercicios en pizarrón: TP1 ej. 9
*Ej 9* — Conversión IEEE 754 → decimal

**Mié 18**
- INV: TP2 completo — leer Apéndice B.2 a B.3, anotar HI-02
  - Foco: universalidad de NAND, simplificación algebraica paso a paso
- Ejercicios en pizarrón: TP2 ej. 1, 2, 3, 4
*Ej 1* — Simplificación de funciones booleanas
*Ej 2* — Reducción booleana + implementación NAND
*Ej 3* — XOR: tabla de verdad, suma de productos, implementación
*Ej 4* — Universalidad de NAND

**Jue 19**
- INV: TP3 completo — leer Apéndice B.3 a B.6, anotar HI-03
  - Foco: Karnaugh (reglas de agrupamiento), MUX y decodificadores
- Ejercicios en pizarrón: TP2 ej. 5; TP3 ej. 1, 2, 4
*Ej 5* — Universalidad de NOR
*Ej 1* — Detector de paridad: tabla de verdad, canónica, NAND, PLA
*Ej 2* — Detector de error en código 5 bits
*Ej 4* — Minimización con Karnaugh (f1, f2, f3)

**Vie 20**
- INV: TP3 continuación — decodificadores, MUX, sumadores
- Ejercicios en pizarrón: TP3 ej. 5, 7, 9, 10
*Ej 5* — Comparador de 2 bits: tabla de verdad, Karnaugh, compuertas
*Ej 7* — Decodificador 2x4: tablas, minimización, habilitación
*Ej 9* — Sumador completo con decodificador y OR
*Ej 10* — MUX: tabla de verdad, implementación, cascada

**Sáb 21**
- INV: TP4 completo — leer Cap. 5 introducción, anotar HI-04
  - Foco: mapa de memoria, posiciones imagen, conexión paralelo vs serie
- Ejercicios en pizarrón: TP4 ej. 1, 2, 3, 4
*Ej 1* — Capacidad de bloques: ordenar por capacidad y palabras
*Ej 2* — Cantidad de chips necesarios
*Ej 3* — Construcción sistema RAM 4K×16
*Ej 4* — Mapa de memoria con EPROM y RAM

**Dom 22**
- INV: TP4 continuación — Chip Select, decodificadores de dirección
- Ejercicios en pizarrón: TP4 ej. 6, 7, 8
*Ej 6* — Análisis de sistema real: espacio direccionable, mapa, localización
*Ej 7* — Completar diagrama: señales A[..] y D[..], mapa con rangos
*Ej 8* — Capacidad total, mapa, posiciones imagen, nuevo bloque RAM

---

### JUNIO — Semana 4 (23 al 29)

**Lun 23**
- INV: TP5 — Flip-flop D, registros — leer Apéndice B.7 a B.9, anotar HI-05
  - Foco: tabla de función FF-D, diferencia síncrono/asíncrono, shift registers
- Ejercicios en pizarrón: TP5 ej. 1, 2, 3, 6
*Ej 1* — Registro paralelo 4 bits con FF-D
*Ej 2* — Shift Register unidireccional 5 bits
*Ej 3* — Shift Register bidireccional con MUX
*Ej 6* — Contador regresivo 3 bits con reinicio

**Mar 24**
- INV: TP5 continuación — máquinas de estado, contadores, detectores
  - Foco: cómo diseñar máquina de estados paso a paso (diagrama → tabla → ecuaciones → circuito)
- Ejercicios en pizarrón: TP5 ej. 7, 8, 10, 11
*Ej 7* — Circuito secuencial 4 estados con entradas E y X
*Ej 8* — Contador código Gray (dos implementaciones)
*Ej 10* — Detector de paridad en serie
*Ej 11* — Detector del patrón "1011"

**Mié 25**
- INV: TP6 — LEGv8 básico — leer Cap. 2 Secciones 2.1 a 2.5, anotar HI-06
  - Foco: registros, instrucciones aritméticas, acceso a memoria, MOVZ/MOVK
- Ejercicios en pizarrón: TP5 ej. 13; TP6 ej. 1, 3, 5
*Ej 13* — Máquina de estados: detección error "111"
*Ej 1* — Traducción C → LEGv8: operaciones aritméticas básicas
*Ej 3* — Traducción C → LEGv8: operaciones con negativos
*Ej 5* — Traducción C → LEGv8: acceso a arreglos con LDUR/STUR

**Jue 26**
- INV: TP6 continuación — lógica de bits, endianness
- Ejercicios en pizarrón: TP6 ej. 6, 7, 8, 9
*Ej 6* — Traducción LEGv8 → C: arreglos, LSL, LDUR, STUR
*Ej 7* — Traducción LEGv8 → C: punteros y acceso indirecto
*Ej 8* — Operaciones lógicas de bits: LSL, LSR, ORR, ANDI
*Ej 9* — Extracción de campos: Exception Syndrome Register

**Vie 27**
- INV: TP7 — LEGv8 avanzado — leer Cap. 2 Secciones 2.6 a 2.10, anotar HI-07
  - Foco: condition codes, branches, diferencia signed/unsigned, loops
- Ejercicios en pizarrón: TP6 ej. 11; TP7 ej. 1, 2, 3
*Ej 11* — Carga de constantes 64 bits: MOVZ y MOVK
*Ej 1* — Identificar funciones con branches condicionales
*Ej 2* — Seguimiento con SUBIS y B.GE: condition codes
*Ej 3* — Traducción C → LEGv8: if/else con cortocircuito

**Sáb 28**

**Dom 29** *(Final PyE — ODC liviano)*
- INV: TP7 continuación — loops complejos, matrices
- Ejercicios en pizarrón: TP7 ej. 4, 5, 7, 8
*Ej 4* — Análisis de loops: valores finales, traducción C, conteo instrucciones
*Ej 5* — Loops con LDUR: suma de arreglos
*Ej 7* — Suma de matriz 2D con doble loop anidado
*Ej 8* — Pseudoinstrucciones: CMP, CMPI, MOV, NOP, NOT

---

### JULIO — Semana 1 (30 Junio al 3 Julio)

**Lun 30**
- INV: TP8 — Ensamblado y desensamblado — leer Cap. 2 Secciones 2.11 a 2.14, anotar HI-08
  - Foco: formatos R, I, D, B, CB, IM — campos y bits de cada uno
- Ejercicios en pizarrón: TP8 ej. 1, 2, 3, 4
*Ej 1* — Extensión de signo 26 bits a 64 bits
*Ej 2* — Ensamblado: formato I y D → binario y hexadecimal
*Ej 3* — Identificación de tipo e instrucción desde campos
*Ej 4* — Desensamblado: binario → hexadecimal → instrucción

**Mar 1**
- INV: TP8 continuación + TP9 — leer Cap. 4 Secciones 4.1 a 4.4, anotar HI-09
  - Foco: datapath, señales de control, tabla de señales por instrucción
- Ejercicios en pizarrón: TP8 ej. 5, 6; TP9 ej. 1, 2
*Ej 5* — Ejecución de programa desde memoria: seguimiento de registros
*Ej 6* — Instrucciones que no pueden ensamblarse: límites de la ISA
*Ej 1* — Bits en líneas del datapath single-cycle
*Ej 2* — Porcentaje de uso de componentes por instrucción

**Mié 2** — Repaso liviano
- Releer todas las hojas de investigación HI-01 a HI-09
- Ejercicios en pizarrón: TP9 ej. 3, 4, 6, 8
*Ej 3* — Tabla de señales de control por instrucción
*Ej 4* — Fallas stuck-at-0 en señales del datapath
*Ej 6* — Ejecución detallada de instrucción: Sign-extend, ALU, PC, MUX
*Ej 8* — Latencias y período mínimo de reloj

**Jue 3** ⚠️ — FINAL ODC (1ra fecha)

---

## Hojas de investigación (temas a cubrir)

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

## Notas del método

- **INV primero, ejercicios después:** nunca al revés
- **Pizarrón obligatorio:** resolver sin mirar apuntes, comparar con carpeta al terminar
- **Si sale diferente:** corregir y reescribir la versión correcta
- **Si no sale:** volver a la hoja de investigación, identificar qué concepto falla, consultarme
- **Preguntas propias:** al final de cada INV escribir 2-3 preguntas que te haría un examen
- **El objetivo no es hacer todos los ejercicios:** es entender los conceptos de verdad