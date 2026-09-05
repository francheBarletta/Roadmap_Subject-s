# Introducción a la Lógica — Estructuras de orden (Prácticos 1-5)

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Vie 11 Septiembre | **Primer Parcial** |
| Vie 13 Noviembre | Segundo Parcial |
| Vie 20 Noviembre | Tercer Parcial y Recuperatorio |

> Regularidad: aprobar al menos 2 de los 3 parciales (o uno + recuperatorio de otro). Promoción: los 3 parciales ≥6 con promedio ≥7, y todos los TPs ≥6.

---

## Estado actual (3 Septiembre)

- **Práctico 1 completo.** Práctico 2: hecho hasta ej. 3. El miércoles 2/9 y el viernes 4/9 no se avanzó nada más (quedaron pendientes ej. 4, 5, 6, 2c\*).
- Se resuelven **todos** los ejercicios de los 5 prácticos, salvo los que requieran conceptos aún no vistos en el teórico (por ahora: P3 ej. 11, reticulados complementados).
- Los ejercicios marcados con (*) se dejan para el final de cada práctico, como cierre/repaso.
- **Nuevo sistema de prueba (5-8/9):** en vez de "1 materia por día", se estudian Álgebra + PyE + Lógica todos los días del finde. El Domingo queda **exclusivo para Lógica** (4h, sin AED2 ni otra materia — parcial muy cerca). Con 6 ejercicios/día (ritmo humano, no forzado), cierra P2, P3 y P4 en estos 4 días — P5 (7 ejercicios) queda para el miércoles/jueves antes del parcial.
- Desde la semana que viene, el **Martes se suma como día fijo de Lógica** (antes SR/AED2).

---

## Prácticos de ejercicios

| # | Tema | Ejercicios |
|---|---|---|
| P1 | Relaciones | 7 |
| P2 | Posets | 6 (uno con parte * ) |
| P3 | Poset Reticulados | 13 (2 marcados con *) |
| P4 | Complementos, distributividad, álgebras de Boole, átomos e irreducibles | 8 |
| P5 | Teoremas de representación | 7 (1 marcado con *) |

**Total: 41 ejercicios** (37 "normales" + 4 ítems/partes marcados con * para cierre).

---

## Conceptos clave

- [ ] Relaciones: reflexiva, simétrica, antisimétrica, transitiva
- [ ] Relación de equivalencia — clases de equivalencia, partición
- [ ] Relación de orden parcial (y orden parcial estricto)
- [ ] Posets, diagramas de Hasse
- [ ] Elementos maximales/minimales vs. máximo/mínimo
- [ ] Cotas superiores/inferiores, supremo, ínfimo
- [ ] Poset reticulado (lattice) — todo par tiene sup e ínf
- [ ] Isomorfismo de posets/reticulados
- [ ] Reticulados complementados y distributivos — Teorema M3-N5
- [ ] Álgebras de Boole — leyes, propiedades del orden asociado
- [ ] Átomos e irreducibles
- [ ] Teorema de Birkhoff (representación de reticulados distributivos finitos)

---

## Banco de ejercicios y videos

### Práctico 1 — Relaciones

| Ej | Descripción | Video |
|---|---|---|
| 1 | Determinar si la relación dada es de equivalencia sobre {1,...,5}; indicar clases | [Relaciones de equivalencia, clases y conjunto cociente](https://www.youtube.com/watch?v=8GxiX1xHJtk) |
| 2 | Determinar si las relaciones sobre Z son reflexivas, simétricas, antisimétricas o transitivas | [Relaciones de orden parcial 01 — Reflexiva, Antisimétrica, Transitiva](https://www.youtube.com/watch?v=FCIQb4MNrP4) |
| 3 | Usando el ej. 2, determinar si cada relación es de equivalencia y/o de orden | [Relaciones reflexivas, transitivas y simétricas — Ejercicios](https://www.youtube.com/watch?v=5L8oMg1roGE) |
| 4 | Probar que la relación {(x,y) | f(x)=f(y)} es de equivalencia; comparar con 2a | [Clases de equivalencia y conjunto cociente — Ejercicio](https://www.youtube.com/watch?v=bJFBxC5qcUA) |
| 5 | Orden parcial estricto → orden parcial (unión con igualdad); y a la inversa | [Relaciones — propiedades, ejemplos y contraejemplos](https://www.youtube.com/watch?v=-wxZsukZcac) |
| 6 | Listar pares de la relación de equivalencia definida por una partición dada; clases | [Relaciones de equivalencia — Ejercicios resueltos](https://www.youtube.com/watch?v=Yly68pfz2ac) |
| 7 | Relación "Fulano no es más viejo que Mengano": ejemplo donde no es orden parcial | [Relaciones propiedades 04 — reflexiva, simétrica, antisimétrica, transitiva](https://www.youtube.com/watch?v=MMUzadgFLvc) |

### Práctico 2 — Posets

| Ej | Descripción | Video |
|---|---|---|
| 1 | Diagramas de Hasse A,B,C: maximales/minimales, máximo/mínimo, qué cubre a "e", cotas y supremos/ínfimos de conjuntos dados | [Diagrama de Hasse — cota superior, maximales, minimales, máximo, mínimo](https://www.youtube.com/watch?v=BCH9auS9yi8) |
| 2 (a,b) | V o F sobre posets: único maximal ⟹ máximo (finito / general) | [Objetos Maximales y Minimales — Conjuntos Ordenados](https://www.youtube.com/watch?v=RDxwk9Vjth4) |
| 3 | Dar diagramas de Hasse de P={a,b,c,d,e} que satisfagan condiciones sobre sup/ínf | [Estructuras de orden — Elementos maximales, máximo, minimales, mínimo](https://www.youtube.com/watch?v=5NRQPEKluTg) |
| 4 | Poset [0,1)∪[2,3) con orden heredado: V o F sobre existencia de supremos | [Poset de Z — Matemática Discreta](https://www.youtube.com/watch?v=6n6ZgStal4E) |
| 5 | Probar que sup(S) e ínf(S) existen para todo S finito no vacío en un poset reticulado | [Supremo e Ínfimo — Cotas y Conjuntos Ordenados](https://www.youtube.com/watch?v=L3rgqDYANYM) |
| 6 | Diagramas de Hasse de (A,\|) y (B,\|) con divisores de 12; ¿cuáles son reticulados?; calcular 4∧(2∨3); subconjunto de P({a,b,c}) | [Supremo e Ínfimo — Explicación con ejemplo](https://www.youtube.com/watch?v=SslId-CutLQ) |
| 2c* *(cierre)* | ¿Único maximal (sin ser finito) implica máximo? | [Ínfimo, supremo, mínimo y máximo de un conjunto](https://www.youtube.com/watch?v=RM11dDasmgg) |

### Práctico 3 — Poset Reticulados

| Ej | Descripción | Video |
|---|---|---|
| 1 | En el reticulado L2: encontrar v∨x, s∨v y u∨v | [Relaciones de equivalencia \|\| Conjunto Cociente](https://www.youtube.com/watch?v=W6x35jEhHx8) *(video general de relaciones/reticulados, no hay uno específico de esta cuenta)* |
| 2 | Demostrar x∨(y∧z) ≤ (x∨y)∧(x∨z) en todo poset reticulado | [Asesorías — Relaciones de equivalencia, Ejercicio 1](https://www.youtube.com/watch?v=vjjLC7Vh-NI) |
| 3 (a,b,c) | Determinar si los mapeos f dados son isomorfismos de posets; qué falla si no | [Relaciones de EQUIVALENCIA — Definición, Clases y Cociente](https://www.youtube.com/watch?v=ke4FJlEe_EU) |
| 4 (a,b) | Determinar si se dan los isomorfismos indicados (D6 vs P({a,b}); D30 vs P({a,b,c})) | [Ejemplo: relaciones de equivalencia — Ejercicio resuelto](https://www.youtube.com/watch?v=rzz92xgPVuY) |
| 5 | Probar que si f es isomorfismo de posets, f⁻¹ también lo es | [Relación de Equivalencia — Demostrar si R es de Equivalencia](https://www.youtube.com/watch?v=SPMFnKVOww8) |
| 6 | Probar que si m es minimal en P, entonces f(m) es minimal en Q | [Relaciones de equivalencia — Definición y ejemplo](https://www.youtube.com/watch?v=DcTP8ouyjCk) |
| 8 (a,b,c) | Función biyectiva que preserva orden entre L3 y L4 pero no es isomorfismo; no preserva sup/ínf | [Relación de equivalencia, reflexiva, simétrica, transitiva](https://www.youtube.com/watch?v=nBbd6Fuqk8M) |
| 9 | Demostrar x∧(y∧z) = z∧(y∧x) en un reticulado | [Relaciones reflexivas, simétricas y transitivas](https://www.youtube.com/watch?v=KG0Vq337t-Y) |
| 10 | Probar que x∨y es cota superior de {x,y} (desde x≤y ⟺ x∨y=y) | [Propiedades de las relaciones: reflexividad, simetría, antisimetría, transitividad](https://www.youtube.com/watch?v=m85j8bxFqvU) |
| 11 | Decidir cuáles de L1, L2, L3, L4 son complementados | [Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) |
| 13 | Para qué valores de n se tiene que Dn se incrusta en L3 | [Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) |
| 7* *(cierre)* | Cuántos isomorfismos hay de P({a,b,c}) en sí mismo | [Supremo e Ínfimo — Explicación con ejemplo](https://www.youtube.com/watch?v=SslId-CutLQ) |
| 12* *(cierre)* | Si sup(S) existe siempre para todo S⊆P, demostrar que ínf(S) también existe | [Supremo e Ínfimo — Cotas y Conjuntos Ordenados](https://www.youtube.com/watch?v=L3rgqDYANYM) |

### Práctico 4 — Complementos, distributividad, álgebras de Boole, átomos e irreducibles

| Ej | Descripción | Video |
|---|---|---|
| 1 (a,b,c) | Reticulado L1: complementos de a,b,d,0; ¿es complementado?; ¿es distributivo? | [Ley Distributiva del Álgebra de Boole](https://www.youtube.com/watch?v=4ZixcbkHydA) |
| 2 (a-g) | Diagramas L3-L11: incrustaciones, isomorfismo con Dn, cuáles son distributivos, cuáles son álgebra de Boole | [Álgebra Booleana — Introducción, Ejercicios para Aprender](https://www.youtube.com/watch?v=p58C7OWe3Xk) |
| 3 (a,b) | Demostrar x∨(z∧y) ≤ (x∨z)∧y; comprobar igualdad si S es distributivo | [Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) |
| 4 | Demostrar que M3 y N5 no satisfacen la propiedad cancelativa | [Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) |
| 5 | Demostrar: si un reticulado satisface cancelativa, entonces es distributivo (Teorema M3-N5) | [Ley Distributiva del Álgebra de Boole](https://www.youtube.com/watch?v=4ZixcbkHydA) |
| 6 | Determinar átomos e irreducibles de los posets L3, L4, L6, L8, L11 | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 7 (a,b) | Demostrar propiedades de álgebras de Boole: ¬(¬x)=x; ¬(x∧y)=¬x∨¬y | [Álgebra Booleana — Introducción, Ejercicios para Aprender](https://www.youtube.com/watch?v=p58C7OWe3Xk) |
| 8 (a,b,c) | Propiedades del orden asociado a un álgebra de Boole: x≤y ⟺ ¬y≤¬x; etc. | [Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) |

> Nota: P4 es la sección con menos videos específicos disponibles en español (temas muy puntuales de álgebra de Boole abstracta) — varios ejercicios comparten video con otro del mismo práctico.

### Práctico 5 — Teoremas de representación

| Ej | Descripción | Video |
|---|---|---|
| 1 | Probar que todo átomo es irreducible | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 2 (a,b) | Determinar si se cumplen las relaciones de isomorfismo (D2310 vs P(5 elem.); D90 vs P(4 elem.)) | [Ejemplo: relaciones de equivalencia — Ejercicio resuelto](https://www.youtube.com/watch?v=rzz92xgPVuY) |
| 3 | Probar que ∅ es decreciente; si D1 y D2 son decrecientes, D1∪D2 también lo es | [Relaciones de EQUIVALENCIA — Definición, Clases y Cociente](https://www.youtube.com/watch?v=ke4FJlEe_EU) |
| 4 (a,b,c) | Para cada reticulado: hallar At(L), dibujar Hasse de P(At(L)), determinar cuáles son álgebra de Boole | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 5 (a,b,c,d) | Hasse de irreducibles, Hasse de D(Irr(L)), definir el mapa F, usar Birkhoff para ver si es distributivo | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 7 (a,b) | Producto L×M de posets: si L,M son reticulados, L×M también; ídem distributividad | [Asesorías — Relaciones de equivalencia, Ejercicio 1](https://www.youtube.com/watch?v=vjjLC7Vh-NI) |
| 6* *(cierre)* | Dar todos los reticulados distributivos con exactamente 3 elementos irreducibles | [Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) |

---

## Reparto semanal de materias (4 materias)

| Día | Materia(s) |
|---|---|
| Lunes (día completo, sin clase) | PyE y **Lógica** |
| Martes (clase 9-13 PyE + 14-18 Álgebra) | **Lógica** *(antes SR/AED2, cambiado el 1/9 — parcial está cerca)* |
| Miércoles (clase 9-13 **Lógica**, práctico 2h) | Álgebra (tarde) — pero **2h de práctico de Lógica ya están en la cursada de la mañana** |
| Jueves (clase 9-13 PyE + 14-18 Álgebra) | **Lógica** (noche) |
| Viernes (clase 9-13 **Lógica**, práctico 2h) | Libre — pero **2h de práctico de Lógica dentro de la cursada de la mañana** |
| Sábado | **Lógica** y Álgebra (refuerzo) |
| Domingo | PyE y AED2 |

> Ritmo real de Lógica: Lunes ~4h (~6 ejercicios) · Sábado ~4h (~6 ejercicios, refuerzo) · Jueves ~2h (~3 ejercicios) · Miércoles y Viernes 2h de práctico dentro de la cursada (~3 ejercicios cada uno). Capacidad semanal: **21 ejercicios/semana** — la más alta de las 4 materias, porque Lógica cursa 2 días con práctico (Miércoles y Viernes) en vez de uno.

---

## Cronograma día por día

> Se muestran todos los días de la semana. Los días que no son de Lógica solo indican qué materia va ahí, sin detalle.

| Fecha | Día | Contenido |
|---|---|---|
| Vie 14 Ago | Vie | Libre |
| ~~Sáb 15~~ | ~~Sáb~~ | **PERDIDO** (familia de visita) |
| ~~Dom 16~~ | ~~Dom~~ | **PERDIDO** |
| ~~Lun 17~~ | ~~Lun~~ | **PERDIDO** |
| Mar 18 | Mar | AED2 |
| ~~Mié 19~~ | ~~Mié~~ | **PERDIDO** (gripe) |
| ~~Jue 20~~ | ~~Jue~~ | **PERDIDO** (gripe) |
| ~~Vie 21~~ | ~~Vie~~ | **PERDIDO** (descanso post-gripe) |
| Sáb 22 Ago | Sáb | **Lógica** (3h, + Álgebra — arranca de cero) — **P1 ej. 1-5** |
| Dom 23 Ago | Dom | PyE (AED2 no esta semana) |
| Lun 24 Ago | Lun | **Lógica** (~4h, + PyE — cierra P1) — **P1 ej. 6, 7** |
| Mar 25 Ago | Mar | *(no se tocó Lógica ese día — el plan original lo tenía como "día especial", pero no se llegó a resolver nada de P2)* |
| Mié 26 Ago | Mié | Álgebra (no es día de Lógica hoy) |
| ~~Jue 27 Ago~~ | ~~Jue~~ | Libre (paro no docente) |
| Vie 28 Ago | Vie | Álgebra (día de sprint — sin Lógica) |
| Sáb 29 Ago | Sáb | Álgebra (día corrido — sin Lógica) |
| Dom 30 Ago | Dom | **Lógica** — **P2 ej. 1, 2, 3** *(el sprint rindió menos de lo planeado — no se llegó a P3)* |
| Lun 31 Ago | Lun | *(no se tocó Lógica — día de la clase particular de Álgebra)* |
| ~~Mar 1 Sep~~ | ~~Mar~~ | **PERDIDO** (pichones de paloma) |
| Mié 2 Sep | Mié | **Lógica** (tarde — no se llegó a avanzar) — P2 ej. 4, 5, 6, 2c\* quedaron pendientes |
| Jue 3 Sep | Jue | *(Álgebra esta semana, no es día de Lógica)* |
| ~~Vie 4 Sep~~ | ~~Vie~~ | **PERDIDO** (no se avanzó nada) |
| Sáb 5 Sep | Sáb | **P2 ej. 4, 5, 6, 2c\* (cierra P2) · P3 ej. 1, 2** |
| Dom 6 Sep | Dom | **P3 ej. 3, 4, 5, 6, 8, 9** |
| Lun 7 Sep | Lun | **P3 ej. 10, 13, 7\*, 12\* (cierra P3) · P4 ej. 1, 2** |
| Mar 8 Sep | Mar | **P4 ej. 3, 4, 5, 6, 7, 8 (cierra P4)** |
| Mié 9 Sep | Mié | **P5 completo (cierra P5, temario completo)** — **P5 ej. 1, 2, 3, 4, 5, 7, 6\*** |
| Jue 10 Sep | Jue | Repaso general / SR de todo el temario, sin ejercicios nuevos |
| **Vie 11 Sep** | Vie | **PRIMER PARCIAL** |

> **P1 completo.** P2 quedó en el ej. 3 tras varios días sin avance (miércoles y viernes no rindieron). **Nuevo sistema de prueba (5-8/9):** en vez de "1 materia por día", se estudian las 3 materias todos los días del finde — el Domingo queda exclusivo para Lógica (4h). A 6 ejercicios/día (ritmo humano), cierra P2, P3 y P4 en estos 4 días; **P5 completo (7 ejercicios) va el miércoles 9/9**, dejando el jueves 10/9 libre para repaso general antes del parcial (11/9).

### Detalle día por día
**Sáb 22 Ago** *(3h, + Álgebra — se perdieron Mié19/Jue20/Vie21 por gripe, arranca de cero acá)* — P1 ej. 1-5
* *Ej 1* — Determinar si la relación dada es de equivalencia sobre {1,...,5}; indicar clases — 🎥 "Relaciones de equivalencia, clases y conjunto cociente" — https://www.youtube.com/watch?v=8GxiX1xHJtk
* *Ej 2* — Determinar si las relaciones sobre Z son reflexivas, simétricas, antisimétricas o transitivas — 🎥 "Relaciones de orden parcial 01" — https://www.youtube.com/watch?v=FCIQb4MNrP4
* *Ej 3* — Usando el ej. 2, determinar si cada relación es de equivalencia y/o de orden — 🎥 "Relaciones reflexivas, transitivas y simétricas" — https://www.youtube.com/watch?v=5L8oMg1roGE
* *Ej 4* — Probar que la relación {(x,y) | f(x)=f(y)} es de equivalencia; comparar con 2a — 🎥 "Clases de equivalencia y conjunto cociente — Ejercicio" — https://www.youtube.com/watch?v=bJFBxC5qcUA
* *Ej 5* — Orden parcial estricto → orden parcial (unión con igualdad); y a la inversa — 🎥 "Relaciones — propiedades, ejemplos y contraejemplos" — https://www.youtube.com/watch?v=-wxZsukZcac

**Lun 24 Ago** *(~4h, + PyE — cierra P1)* — P1 ej. 6, 7
* *Ej 6* — Listar pares de la relación de equivalencia definida por una partición dada; clases — 🎥 "Relaciones de equivalencia — Ejercicios resueltos" — https://www.youtube.com/watch?v=Yly68pfz2ac
* *Ej 7 (P1)* — Relación "Fulano no es más viejo que Mengano": ejemplo donde no es orden parcial — 🎥 "Relaciones propiedades 04" — https://www.youtube.com/watch?v=MMUzadgFLvc

**Mar 25 Ago** — *no se tocó Lógica ese día (el plan original lo tenía como "día especial", pero no se llegó a resolver nada de P2 — arranca de cero el sábado)*

**Dom 30 Ago** *(sprint — rindió menos de lo esperado)* — P2 ej. 1, 2, 3 *(hecho)*
* *Ej 1 (P2)* — Diagramas de Hasse A,B,C: maximales/minimales, máximo/mínimo, qué cubre a "e", cotas y supremos/ínfimos de conjuntos dados — 🎥 "Diagrama de Hasse — cota superior, maximales, minimales, máximo, mínimo" — https://www.youtube.com/watch?v=BCH9auS9yi8
* *Ej 2 (P2)* — V o F sobre posets: único maximal ⟹ máximo (finito / general) — 🎥 "Objetos Maximales y Minimales — Conjuntos Ordenados" — https://www.youtube.com/watch?v=RDxwk9Vjth4
* *Ej 3 (P2)* — Dar diagramas de Hasse de P={a,b,c,d,e} que satisfagan condiciones sobre sup/ínf — 🎥 "Estructuras de orden — Elementos maximales, máximo, minimales, mínimo" — https://www.youtube.com/watch?v=5NRQPEKluTg

**Lun 31 Ago** — no se tocó Lógica (día de la clase particular de Álgebra).

**Mié 2 Sep** *(tarde — no se llegó a avanzar)* — P2 ej. 4, 5, 6, 2c\* quedaron pendientes

**Vie 4 Sep** — sin avance (no se estudió Lógica ese día).

**Sáb 5 Sep** *(4h — nuevo sistema)* — P2 ej. 4, 5, 6, 2c* (cierra P2) · P3 ej. 1, 2
* *Ej 4 (P2)* — Poset [0,1)∪[2,3) con orden heredado: V o F sobre existencia de supremos — 🎥 "Poset de Z — Matemática Discreta" — https://www.youtube.com/watch?v=6n6ZgStal4E
* *Ej 5 (P2)* — Probar que sup(S) e ínf(S) existen para todo S finito no vacío en un poset reticulado — 🎥 "Supremo e Ínfimo — Cotas y Conjuntos Ordenados" — https://www.youtube.com/watch?v=L3rgqDYANYM
* *Ej 6 (P2)* — Diagramas de Hasse de (A,|) y (B,|) con divisores de 12; ¿cuáles son reticulados?; calcular 4∧(2∨3); subconjunto de P({a,b,c}) — 🎥 "Supremo e Ínfimo — Explicación con ejemplo" — https://www.youtube.com/watch?v=SslId-CutLQ
* *Ej 2c* (P2)* — ¿Único maximal (sin ser finito) implica máximo? — 🎥 "Ínfimo, supremo, mínimo y máximo de un conjunto" — https://www.youtube.com/watch?v=RM11dDasmgg
* *Ej 1 (P3)* — En el reticulado L2: encontrar v∨x, s∨v y u∨v — 🎥 "Relaciones de equivalencia || Conjunto Cociente" — https://www.youtube.com/watch?v=W6x35jEhHx8
* *Ej 2 (P3)* — Demostrar x∨(y∧z) ≤ (x∨y)∧(x∨z) en todo poset reticulado — 🎥 "Asesorías — Relaciones de equivalencia, Ejercicio 1" — https://www.youtube.com/watch?v=vjjLC7Vh-NI

**Dom 6 Sep** *(4h — nuevo sistema)* — P3 ej. 3, 4, 5, 6, 8, 9
* *Ej 3 (P3)* — Determinar si los mapeos f dados son isomorfismos de posets; qué falla si no — 🎥 "Relaciones de EQUIVALENCIA — Definición, Clases y Cociente" — https://www.youtube.com/watch?v=ke4FJlEe_EU
* *Ej 4 (P3)* — Determinar si se dan los isomorfismos indicados (D6 vs P({a,b}); D30 vs P({a,b,c})) — 🎥 "Ejemplo: relaciones de equivalencia — Ejercicio resuelto" — https://www.youtube.com/watch?v=rzz92xgPVuY
* *Ej 5 (P3)* — Probar que si f es isomorfismo de posets, f⁻¹ también lo es — 🎥 "Relación de Equivalencia — Demostrar si R es de Equivalencia" — https://www.youtube.com/watch?v=SPMFnKVOww8
* *Ej 6 (P3)* — Probar que si m es minimal en P, entonces f(m) es minimal en Q — 🎥 "Relaciones de equivalencia — Definición y ejemplo" — https://www.youtube.com/watch?v=DcTP8ouyjCk
* *Ej 8 (P3)* — Función biyectiva que preserva orden entre L3 y L4 pero no es isomorfismo; no preserva sup/ínf — 🎥 "Relación de equivalencia, reflexiva, simétrica, transitiva" — https://www.youtube.com/watch?v=nBbd6Fuqk8M
* *Ej 9 (P3)* — Demostrar x∧(y∧z) = z∧(y∧x) en un reticulado — 🎥 "Relaciones reflexivas, simétricas y transitivas" — https://www.youtube.com/watch?v=KG0Vq337t-Y

**Lun 7 Sep** *(4h — nuevo sistema)* — P3 ej. 10, 13, 7*, 12* (cierra P3) · P4 ej. 1, 2
* *Ej 10 (P3)* — Probar que x∨y es cota superior de {x,y} (desde x≤y ⟺ x∨y=y) — 🎥 "Propiedades de las relaciones: reflexividad, simetría, antisimetría, transitividad" — https://www.youtube.com/watch?v=m85j8bxFqvU
* *Ej 13 (P3)* — Para qué valores de n se tiene que Dn se incrusta en L3 — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig
* *Ej 7* (P3)* — Cuántos isomorfismos hay de P({a,b,c}) en sí mismo — 🎥 "Supremo e Ínfimo — Explicación con ejemplo" — https://www.youtube.com/watch?v=SslId-CutLQ
* *Ej 12* (P3)* — Si sup(S) existe siempre para todo S⊆P, demostrar que ínf(S) también existe — 🎥 "Supremo e Ínfimo — Cotas y Conjuntos Ordenados" — https://www.youtube.com/watch?v=L3rgqDYANYM
* *Ej 1 (P4)* — Reticulado L1: complementos de a,b,d,0; ¿es complementado?; ¿es distributivo? — 🎥 "Ley Distributiva del Álgebra de Boole" — https://www.youtube.com/watch?v=4ZixcbkHydA
* *Ej 2 (P4)* — Diagramas L3-L11: incrustaciones, isomorfismo con Dn, cuáles son distributivos, cuáles son álgebra de Boole — 🎥 "Álgebra Booleana — Introducción, Ejercicios para Aprender" — https://www.youtube.com/watch?v=p58C7OWe3Xk

**Mar 8 Sep** *(4h — nuevo sistema)* — P4 ej. 3, 4, 5, 6, 7, 8 (cierra P4)
* *Ej 3 (P4)* — Demostrar x∨(z∧y) ≤ (x∨z)∧y; comprobar igualdad si S es distributivo — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o
* *Ej 4 (P4)* — Demostrar que M3 y N5 no satisfacen la propiedad cancelativa — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig
* *Ej 5 (P4)* — Demostrar: si un reticulado satisface cancelativa, entonces es distributivo (Teorema M3-N5) — 🎥 "Ley Distributiva del Álgebra de Boole" — https://www.youtube.com/watch?v=4ZixcbkHydA
* *Ej 6 (P4)* — Determinar átomos e irreducibles de los posets L3, L4, L6, L8, L11 — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 7 (P4)* — Demostrar propiedades de álgebras de Boole: ¬(¬x)=x; ¬(x∧y)=¬x∨¬y — 🎥 "Álgebra Booleana — Introducción, Ejercicios para Aprender" — https://www.youtube.com/watch?v=p58C7OWe3Xk
* *Ej 8 (P4)* — Propiedades del orden asociado a un álgebra de Boole: x≤y ⟺ ¬y≤¬x; etc. — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o

**Mié 9 Sep** *(cierra P5, temario completo)* — P5 ej. 1, 2, 3, 4, 5, 7, 6\*
* *Ej 1 (P5)* — Probar que todo átomo es irreducible — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 2 (P5)* — Determinar si se cumplen las relaciones de isomorfismo (D2310 vs P(5 elem.); D90 vs P(4 elem.)) — 🎥 "Ejemplo: relaciones de equivalencia — Ejercicio resuelto" — https://www.youtube.com/watch?v=rzz92xgPVuY
* *Ej 3 (P5)* — Probar que ∅ es decreciente; si D1 y D2 son decrecientes, D1∪D2 también lo es — 🎥 "Relaciones de EQUIVALENCIA — Definición, Clases y Cociente" — https://www.youtube.com/watch?v=ke4FJlEe_EU
* *Ej 4 (P5)* — Para cada reticulado: hallar At(L), dibujar Hasse de P(At(L)), determinar cuáles son álgebra de Boole — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 5 (P5)* — Hasse de irreducibles, Hasse de D(Irr(L)), definir el mapa F, usar Birkhoff para ver si es distributivo — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 7 (P5)* — Producto L×M de posets: si L,M son reticulados, L×M también; ídem distributividad — 🎥 "Asesorías — Relaciones de equivalencia, Ejercicio 1" — https://www.youtube.com/watch?v=vjjLC7Vh-NI
* *Ej 6\* (P5)* — Dar todos los reticulados distributivos con exactamente 3 elementos irreducibles — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig

**Jue 10 Sep** — Repaso general / SR de todo el temario (P1 a P5), sin ejercicios nuevos.
---

## Notas del método

- **Corrida del 1/9:** el domingo 30 el sprint rindió menos de lo esperado (P2 ej. 1-3 nomás), y el lunes 31 se usó para la clase particular de Álgebra en vez de Lógica. Objetivo para el martes 1/9: terminar el Práctico 2 completo.
- **Sprint post-TP (26-28/8):** P1 confirmado completo, con 8/10 en el TP sorpresa del 26/8. El martes 25 no se avanzó nada de P2 (pese a estar planeado como "día especial"). Jueves 27 fue paro no docente (libre).
- **Corrida del 22/8 (gripe):** se perdieron Mié 19, Jue 20 y Vie 21 por gripe. El Sáb 22 se acortó a 3h (repartido con Álgebra) y el Mar 25 se convirtió en un día especial 100% Lógica (sin PyE ni Álgebra) para recuperar terreno.
- **Corrida anterior (17/8):** Sáb 15, Dom 16 y Lun 17 se perdieron por un imprevisto familiar.

- Como es matemática discreta/estructural (pruebas y diagramas, no cálculo numérico), varios videos son de teoría general del tema en vez de resolver exactamente el mismo enunciado — el objetivo es entender la técnica de demostración, no encontrar el ejercicio calcado.
- Encontré un video hecho específicamente para este curso de FaMAF sobre el Teorema de Birkhoff — lo reutilicé en varios ejercicios de átomos/irreducibles/representación porque es el más pertinente posible.
- Cuando lleguen las próximas 2 unidades, se agregan con el mismo formato (tabla banco + detalle inline).
- Ejercicios (*) resueltos al cierre de cada práctico, como pediste — quedan agrupados el Jue 27 y Vie 28 para repasar todo junto antes de las casi 2 semanas de margen hasta el parcial.