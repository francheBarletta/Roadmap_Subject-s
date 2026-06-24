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

> NUEVO ENFOQUE (desde 21 Junio): PyE es prioridad absoluta. ODC pasa a 2 horas diarias, ritmo más liviano.
> Objetivo redefinido: no dominar todo, sino mantener el hábito y llegar con el contenido visto al menos una vez.
> 2-3 ejercicios por día + INV liviana (lectura corta, sin la profundidad de antes)
> Arranque desde el Lun 22 de Junio (sin sesión el Dom 21, foco en PyE)

---

### JUNIO — Semana 4 (22 al 29)

**Lun 22** *(2 horas)*
- INV breve: TP1 — complemento a 2, IEEE 754 (HI-01)
- Ejercicios: TP1 ej. 1, 2, 3
*Ej 1* — Conversión hexadecimal → binario 32 bits
*Ej 2* — Conversión binario → decimal y hexadecimal
*Ej 3* — Conversión decimal → binario sin signo (16 bits)

**Mar 23** *(2 horas)*
- Ejercicios: TP1 ej. 4, 5, 6
*Ej 4* — Complemento a 2 en registros de 8 bits
*Ej 5* — Conversión complemento a 2 → decimal
*Ej 6* — Operaciones aritméticas: overflow y carry

**Mié 24** *(2 horas)*
- Ejercicios: TP1 ej. 7, 8, 9
*Ej 7* — Representación en distintos tamaños de registro
*Ej 8* — Conversión decimal → IEEE 754 precisión simple
*Ej 9* — Conversión IEEE 754 → decimal

**Jue 25** *(2 horas)*
- INV breve: TP2 — universalidad NAND, simplificación (HI-02)
- Ejercicios: TP2 ej. 1, 2, 3
*Ej 1* — Simplificación de funciones booleanas
*Ej 2* — Reducción booleana + implementación NAND
*Ej 3* — XOR: tabla de verdad, suma de productos, implementación

**Vie 26** *(2 horas)*
- Ejercicios: TP2 ej. 4, 5
*Ej 4* — Universalidad de NAND
*Ej 5* — Universalidad de NOR

**Sáb 27** *(2 horas)*
- INV breve: TP3 — Karnaugh, MUX, decodificadores (HI-03)
- Ejercicios: TP3 ej. 1, 2, 4
*Ej 1* — Detector de paridad: tabla de verdad, canónica, NAND, PLA
*Ej 2* — Detector de error en código 5 bits
*Ej 4* — Minimización con Karnaugh (f1, f2, f3)

**Dom 28** *(2 horas)*
- Ejercicios: TP3 ej. 5, 7
*Ej 5* — Comparador de 2 bits: tabla de verdad, Karnaugh, compuertas
*Ej 7* — Decodificador 2x4: tablas, minimización, habilitación

**Lun 29** *(sin sesión — Final PyE)*

---

### JUNIO/JULIO — Semana 5 (30 Junio al 2 Julio)

**Mar 30** *(2 horas)*
- Ejercicios: TP3 ej. 9, 10
*Ej 9* — Sumador completo con decodificador y OR
*Ej 10* — MUX: tabla de verdad, implementación, cascada

**Mié 1** *(2 horas)*
- INV breve: TP4 — mapa de memoria, posiciones imagen (HI-04)
- Ejercicios: TP4 ej. 1, 2, 3
*Ej 1* — Capacidad de bloques: ordenar por capacidad y palabras
*Ej 2* — Cantidad de chips necesarios
*Ej 3* — Construcción sistema RAM 4K×16

**Jue 2** *(2 horas, último día)*
- Releer hojas de investigación HI-01 a HI-04
- Ejercicios: TP4 ej. 4
*Ej 4* — Mapa de memoria con EPROM y RAM
- Nota: TP5 a TP9 no llegan a verse con este ritmo — esperado y aceptado, el objetivo era el hábito, no completar todo

**Vie 3** ⚠️ — FINAL ODC (1ra fecha) — se rinde con lo visto (TP1 a TP4 + lo ya sabido de antes de TP5-TP9)

---

> **Nota importante:** Este plan cubre TP1 a TP4 sólidamente. TP5 a TP9 quedan con el conocimiento previo de la cursada (parcial), sin repaso profundo nuevo. Esto es consistente con el objetivo redefinido: experiencia y hábito, no aprobación garantizada. Para la 2da fecha (24 Julio) hay tiempo de retomar TP5-TP9 con calma.


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