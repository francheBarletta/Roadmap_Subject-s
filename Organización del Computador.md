# Organización del Computador — Plan de estudio personal

Inicio de clases: 11 marzo
Fin de clases: 19 junio

Clases por semana: Miércoles y Viernes
Prioridad: MEDIA

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Vie 5 Junio | 2do Parcial ODC |
| Mié 17 Junio | Recuperatorio ODC (parciales 1 y 2) |
| Vie 3 Julio | Final ODC (1ra fecha) |
| Jue 24 Julio | Final ODC (2da fecha) |
| Vie 7 Agosto | Final ODC (3ra fecha) |

---

## Estado actual (6 Mayo)

- Última clase cursada: Clase 2 (IEEE754, intro Álgebra de Boole)
- TP1 al TP4: completados ✓
- TP5 (Circuitos Secuenciales): pendiente — entra en recuperatorio
- TP6 al TP9: pendientes (2do parcial)

---

## Trabajos Prácticos

| # | Tema | Estado |
|---|---|---|
| TP1 | Sistemas numéricos | [x] hecho |
| TP2 | Álgebra de Boole | [x] hecho |
| TP3 | Lógica combinacional | [x] hecho |
| TP4 | Direccionamiento y decodificación de memorias | [x] hecho |
| TP5 | Circuitos secuenciales | [ ] pendiente (recuperatorio) |
| TP6 | Assembler LEGv8 básico | [ ] |
| TP7 | Assembler LEGv8 avanzado | [ ] |
| TP8 | Ensamblado y desensamblado | [ ] |
| TP9 | Implementación de la ISA | [ ] |

---

## Conceptos clave

### Bloque 1 — Recuperatorio (17 Junio)
- [ ] Representación de números negativos (complemento a 2)
- [ ] Punto flotante IEEE 754
- [ ] Álgebra de Boole y simplificación
- [ ] Mapas de Karnaugh
- [ ] Lógica combinacional (MUX, decodificadores, PLA)
- [ ] Direccionamiento de memorias
- [ ] **Flip-flops tipo D**
- [ ] **Registros y shift registers**
- [ ] **Circuitos secuenciales y máquinas de estado**

### Bloque 2 — 2do Parcial (5 Junio)
- [ ] Assembler LEGv8 básico (instrucciones aritméticas, acceso a memoria)
- [ ] Assembler LEGv8 avanzado (branches, loops, flags)
- [ ] Ensamblado y desensamblado (formatos R, I, D, B, CB)
- [ ] Implementación de la ISA (datapath, control, señales)

---

## Sesiones de estudio programadas

> ODC aparece en el calendario en los siguientes días: Jue, Mié, Sáb (primera materia), y como segunda materia los Mar, Mié, Dom
> Lun: ODC primera materia (junto con Álgebra)
> Vie: sin ODC (PyE)
> INV = Sesión de investigación (leer libro + anotar en hoja de investigación)
> SR = Sesión de Spaced Repetition
> Libro de referencia: Computer Organization and Design — ARM Edition (Patterson & Hennessy)

---

### MAYO — Semana 1 (7 al 11)

**Sáb 9** *(Parcial 2)*
- Tema: TP6 — Legv8: Assembler de LEGv8 básico (ej. 1, 2, 3, 4)
INV:
*Ej 1* — Traducción C → LEGv8: operaciones aritméticas básicas (ADD, ADDI)
*Ej 2* — Traducción LEGv8 → C: operaciones aritméticas
*Ej 3* — Traducción C → LEGv8: operaciones con negativos (SUB, negación)
*Ej 4* — Traducción LEGv8 → C: SUB y negación

**Dom 10**
Depresion xd

### MAYO — Semana 2 (12 al 18)

**Lun 11** *(Parcial 2)*
Depresion xd

**Mar 12** 
Depresion xd

**Mié 13** 
Depresion xd

**Jue 14** 
Depresion xd

**Sáb 16** *(Parcial 2)*
Free

**Dom 17**
---

### MAYO — Semana 3 (19 al 25)

**Lun 18** *(Parcial 1)*

**Mar 19** *(Parcial 2)*

**Mié 20** *(Parcial 2)*

**Jue 21** *(Parcial 1)*
- Tema: TP6 — Legv8: Assembler de LEGv8 básico (ej. 5, 6, 7, 8)
INV:
*Ej 5* — Traducción C → LEGv8: acceso a arreglos con LDUR/STUR
*Ej 6* — Traducción LEGv8 → C: operaciones con arreglos, LSL, LDUR, STUR
*Ej 7* — Traducción LEGv8 → C: punteros y acceso a memoria indirecto
*Ej 8* — Operaciones lógicas de bits: LSL, LSR, ORR, ANDI

**Vier  22**
- Tema: TP6 — Legv8: Assembler de LEGv8 básico (ej. 9, 10, 11, 12)
INV:
*Ej 9* — Extracción de campos de un registro: Exception Syndrome Register (ESR)
*Ej 10* — Detección de signo en complemento a 2
*Ej 11* — Carga de constantes de 64 bits: MOVZ y MOVK
*Ej 12* — Endianness: little-endian vs big-endian con LDURB

**Sáb 23** 
Fracaso

**Dom 24**
- Tema: TP7 — Assembler LEGv8 Avanzado: (ej 1, 2, 3)
- INV:
*Ej 1* — Identificación de funciones con branches condicionales (valor absoluto, multiplicación)
*Ej 2* — Seguimiento de programa con SUBIS y B.GE: condition codes
*Ej 3* — Traducción C → LEGv8: if/else con evaluación por cortocircuito (||)
- Tema: TP7 — Assembler LEGv8 Avanzado: (ej 4, 5, 6, )
- INV: 
*Ej 4* — Análisis de loops: valores finales, traducción a C, conteo de instrucciones
---

### MAYO — Semana 4 (26 al 31)

**Lun 25** 
- Tema: TP7 — (ej 5, 6)
*Ej 5* — Loops con LDUR: suma de arreglos, comparación de implementaciones
*Ej 6* — Traducción C → LEGv8: búsqueda de caracteres en string con LDURB
- Tema: TP7 — (ej 7)
*Ej 7* — Traducción C → LEGv8: suma de matriz 2D con doble loop anidado

- Tema: TP5 — FlipFlop con reset, (ej 1, 2, 3 ,4) 
- INV:
*Ej 1* — Registro de entrada/salida en paralelo de 4 bits con FF-D
*Ej 2* — Shift Register unidireccional de 5 bits con FF-D
*Ej 3* — Shift Register bidireccional de 4 bits con FF-D y MUX 2:1
*Ej 4* — Registro paralelo con swapping de bits usando FF-D y MUX
- Tema: TP5 — (ej. 5, 6, 7, 8)
- INV:
*Ej 5* — Shift Register de 4 bits con señales de control C1/C0 (reset, desplazamiento, hold, carga)
*Ej 6* — Contador regresivo de 3 bits con entrada de reinicio R
*Ej 7* — Circuito secuencial de 4 estados con entradas E y X (avance/retroceso)
*Ej 8* — Contador de código Gray de 3 bits con entrada inc (dos implementaciones)

**Mar 26** *(Parcial 1)*
- Tema: TP8 — (ej 1, 2, 3)
- INV:
*Ej 1* — Extensión de signo de 26 bits a 64 bits (complemento a 2)
*Ej 2* — Ensamblado de instrucciones: formato I y D → binario y hexadecimal
*Ej 3* — Identificación de tipo de instrucción y desensamblado desde campos

**Mié 27** *(Parcial 2)*
- Tema: TP5 — (ej 9, 10, 11, 12) 
- INV:
*Ej 9* — Circuito secuencial con secuencia de salida 2,3,2,4 con entrada inc
*Ej 10* — Detector de paridad en serie (bit a bit)
*Ej 11* — Detector del patrón "1011" sin solapamiento
*Ej 12* — Análisis de diagrama de estados: identificar patrones detectados + trazar salida
*Ej 13* — Máquina de estados para detección de error "111" en secuencia de 3 bits

**Jue 28** *(Parcial 2)*
- Tema: TP8 — (ej 4, 5, 6, 7, 8)
- INV: 
**Ej 4** — Desensamblado: binario → hexadecimal → instrucción LEGv8
**Ej 5** — Ejecución de programa desde memoria: seguimiento de registros
**Ej 6** — Instrucciones que no pueden ensamblarse en LEGv8: análisis de límites de la ISA
**Ej 7** — Ensamblado de delay loops con MOVZ, SUBI, CBNZ, SUBIS, B.NE
**Ej 8** — Alcance de instrucciones de salto: conditional branch vs branch incondicional, far jump
- Tema: TP9 — (ej 1, 2)
- INV: Leer acceso a memoria LEGv8, arreglos, operaciones lógicas (HI-06, HI-07)
- INV:
*Ej 1* — Identificación de bits en líneas del datapath single-cycle
*Ej 2* — Porcentaje de uso de componentes según distribución de instrucciones
- Repaso TP1

**Sáb 30** *(Parcial 1)*
- Tema: TP9 — (ej 3, 4)
*Ej 3* — Tabla de señales de control por instrucción (Reg2Loc, ALUSrc, MemtoReg, etc.)
*Ej 4* — Análisis de fallas stuck-at-0 en señales del datapath
- Tema: TP9 — (ej. 5, 6, 7)
- INV: 
*Ej 5* — Modificación del datapath: cambio de CBZ a CBNZ
*Ej 6* — Ejecución detallada de una instrucción: Sign-extend, ALU control, PC, MUX, entradas
*Ej 7* — Extensión del datapath: agregar instrucción B (salto incondicional)

**Dom 31**
- Tema: TP9 
- INV:
*Ej 8* — Cálculo de latencias por tipo de instrucción y período mínimo de reloj
*Ej 9* — Impacto de simplificación de instrucciones de carga en velocidad de procesamiento
*Ej 10* — Aceleración con ciclo de reloj variable adaptado a cada instrucción
*Ej 11* — Instrucción no documentada: identificar comportamiento desde señales de control

---

### JUNIO — Semana 1 (1 al 7)

> ⚠️ SEMANA CRÍTICA — 2do Parcial Vie 5

**Lun 1**

**Mar 2**

**Mié 3** 
- Repaso

**Jue 4** 
- Repaso

**Vie 5** ⚠️ — 2DO PARCIAL ODC — sin sesión

**Sáb 6** — libre (Free en el calendario)

**Dom 7** *(ODC + Álgebra)*
- Repaso TP1–TP5 para recuperatorio
- No material nuevo

---

### JUNIO — Semana 2 (8 al 14)

**Lun 8** *(solo PyE este día — sin ODC)*

**Mar 9** 
- Repaso

**Mié 10** *(primera materia del día)*
- Repaso

**Jue 11** *(primera materia del día)*
- Repaso

**Sáb 13** *(primera materia del día)*
- Repaso

**Dom 14** *(ODC + Álgebra)*
- Repaso

---

### JUNIO — Semana 3 (15 al 21)

**Lun 15** *(primera materia del día)*
- Repaso

**Mar 16** ⚠️ — RECUPERATORIO ÁLGEBRA — sin sesión ODC

**Mié 17** ⚠️ — RECUPERATORIO ODC — sin sesión

---

## Hojas de investigación (temas a cubrir)

> Una hoja por tema. Fuente principal: Patterson & Hennessy + búsqueda web.
> Formato sugerido: definición → por qué importa → ejemplo concreto → conexión con ejercicios del TP

- [ ] HI-01:
- [ ] HI-02:
- [ ] HI-03:
- [ ] HI-04:
- [ ] HI-05:
- [ ] HI-06:
- [ ] HI-07:
- [ ] HI-08:
- [ ] HI-09:
- [ ] HI-10:

---

## Notas del método

- Ciclo de estudio: INV (leer + anotar) → ejercicios del TP → SR
- Las sesiones INV son previas a los ejercicios: primero entender el concepto, después aplicarlo
- Hoja de investigación: una por tema, guardada como referencia permanente
- SR: misma caja de zapatos que Álgebra, compartimentos separados por materia
- Cuando un ejercicio no sale: volver a la hoja de investigación del tema, no frustrarse