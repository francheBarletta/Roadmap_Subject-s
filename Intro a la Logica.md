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

## Estado actual (14 Agosto)

- Nada resuelto todavía. Arranca el Sábado 15.
- Se resuelven **todos** los ejercicios de los 5 prácticos.
- Los ejercicios marcados con (*) se dejan para el final de cada práctico, como cierre/repaso.

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
| Martes (clase 9-13 PyE + 14-18 Álgebra) | AED2 |
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
| Lun 24 Ago | Lun | **Lógica** (~4h, + PyE — cierra P1) — **P1 ej. 6, 7** + **P2 ej. 1, 2, 3, 4** |
| Mar 25 Ago | Mar | **Lógica** (día especial 100% Lógica, sin PyE ni Álgebra — cierra P2 salvo 2c\*) — **P2 ej. 5, 6** + **P3 ej. 1, 2, 3, 4** |
| Mié 26 Ago | Mié | **Lógica** (práctico, 2h) — **P3 ej. 5, 6, 8** |
| Jue 27 Ago | Jue | **Lógica** (~2h) — **P3 ej. 9, 10, 11** |
| Vie 28 Ago | Vie | **Lógica** (práctico, 2h — cierra P3 salvo 7\*, 12\*) — **P3 ej. 13** + **P4 ej. 1, 2** |
| Sáb 29 Ago | Sáb | **Lógica** (~4h, + Álgebra — cierra P4) — **P4 ej. 3, 4, 5, 6, 7, 8** |
| Dom 30 Ago | Dom | PyE y AED2 |
| Lun 31 Ago | Lun | **Lógica** (~4h, + PyE) — **P5 ej. 1, 2, 3, 4, 5, 7** |
| Mar 1 Sep | Mar | AED2 |
| Mié 2 Sep | Mié | **Lógica** (práctico, 2h — cierre general del temario) — **P2 ej. 2c\*** + **P3 ej. 7\*, 12\*** + **P5 ej. 6\*** |
| Jue 3 Sep → Vie 11 Sep | — | Sin ejercicios nuevos (temario completo). Repaso, TPs del aula virtual. |
| **Vie 11 Sep** | Vie | **PRIMER PARCIAL** |

> Semana de la gripe: se perdieron Mié 19, Jue 20 y Vie 21 (enfermedad), y el Mar 25 se dedicó 100% a Lógica (sin PyE ni Álgebra ese día) para recuperar terreno — el Sáb 22 también se acortó a 3h (en vez de 4h) para repartir el recorte con Álgebra. El temario ahora cierra el **Mié 2 Sep** (antes Lun 31 Ago) — quedan ~9 días de margen antes del Primer Parcial (11 Sep), bastante ajustado pero todavía alcanza.

### Detalle día por día
**Sáb 22 Ago** *(3h, + Álgebra — se perdieron Mié19/Jue20/Vie21 por gripe, arranca de cero acá)* — P1 ej. 1-5
* *Ej 1* — Determinar si la relación dada es de equivalencia sobre {1,...,5}; indicar clases — 🎥 "Relaciones de equivalencia, clases y conjunto cociente" — https://www.youtube.com/watch?v=8GxiX1xHJtk
* *Ej 2* — Determinar si las relaciones sobre Z son reflexivas, simétricas, antisimétricas o transitivas — 🎥 "Relaciones de orden parcial 01" — https://www.youtube.com/watch?v=FCIQb4MNrP4
* *Ej 3* — Usando el ej. 2, determinar si cada relación es de equivalencia y/o de orden — 🎥 "Relaciones reflexivas, transitivas y simétricas" — https://www.youtube.com/watch?v=5L8oMg1roGE
* *Ej 4* — Probar que la relación {(x,y) | f(x)=f(y)} es de equivalencia; comparar con 2a — 🎥 "Clases de equivalencia y conjunto cociente — Ejercicio" — https://www.youtube.com/watch?v=bJFBxC5qcUA
* *Ej 5* — Orden parcial estricto → orden parcial (unión con igualdad); y a la inversa — 🎥 "Relaciones — propiedades, ejemplos y contraejemplos" — https://www.youtube.com/watch?v=-wxZsukZcac

**Lun 24 Ago** *(~4h, + PyE — cierra P1)* — P1 ej. 6, 7 · P2 ej. 1, 2, 3, 4
* *Ej 6* — Listar pares de la relación de equivalencia definida por una partición dada; clases — 🎥 "Relaciones de equivalencia — Ejercicios resueltos" — https://www.youtube.com/watch?v=Yly68pfz2ac
* *Ej 7 (P1)* — Relación "Fulano no es más viejo que Mengano": ejemplo donde no es orden parcial — 🎥 "Relaciones propiedades 04" — https://www.youtube.com/watch?v=MMUzadgFLvc
* *Ej 1 (P2)* — Diagramas de Hasse A,B,C: maximales/minimales, máximo/mínimo, qué cubre a "e", cotas y sup/ínf — 🎥 "Diagrama de Hasse — cota superior, maximales, minimales" — https://www.youtube.com/watch?v=BCH9auS9yi8
* *Ej 2 (P2)* — V o F sobre posets: único maximal ⟹ máximo (finito / general) — 🎥 "Objetos Maximales y Minimales" — https://www.youtube.com/watch?v=RDxwk9Vjth4
* *Ej 3 (P2)* — Dar diagramas de Hasse de P={a,b,c,d,e} con condiciones sobre sup/ínf — 🎥 "Estructuras de orden — maximales, mínimo" — https://www.youtube.com/watch?v=5NRQPEKluTg
* *Ej 4 (P2)* — Poset [0,1)∪[2,3): V o F sobre existencia de supremos — 🎥 "Poset de Z" — https://www.youtube.com/watch?v=6n6ZgStal4E

**Mar 25 Ago** *(día especial 100% Lógica, sin PyE ni Álgebra — cierra P2 salvo 2c\*)* — P2 ej. 5, 6 · P3 ej. 1, 2, 3, 4
* *Ej 5 (P2)* — Probar que sup(S) e ínf(S) existen para todo S finito no vacío en un poset reticulado — 🎥 "Supremo e Ínfimo — Cotas y Conjuntos Ordenados" — https://www.youtube.com/watch?v=L3rgqDYANYM
* *Ej 6 (P2)* — Hasse de (A,\|) y (B,\|) con divisores de 12; ¿reticulados?; calcular 4∧(2∨3); subconjunto de P({a,b,c}) — 🎥 "Supremo e Ínfimo — Explicación con ejemplo" — https://www.youtube.com/watch?v=SslId-CutLQ
* *Ej 1 (P3)* — En L2: encontrar v∨x, s∨v y u∨v — 🎥 "Relaciones de equivalencia \|\| Conjunto Cociente" — https://www.youtube.com/watch?v=W6x35jEhHx8
* *Ej 2 (P3)* — Demostrar x∨(y∧z) ≤ (x∨y)∧(x∨z) en todo poset reticulado — 🎥 "Relaciones de equivalencia — Ejercicio 1" — https://www.youtube.com/watch?v=vjjLC7Vh-NI
* *Ej 3* — Determinar si los mapeos f dados son isomorfismos de posets; qué falla si no — 🎥 "Relaciones de EQUIVALENCIA — Definición, Clases y Cociente" — https://www.youtube.com/watch?v=ke4FJlEe_EU
* *Ej 4* — Determinar si se dan los isomorfismos indicados (D6 vs P({a,b}); D30 vs P({a,b,c})) — 🎥 "Ejemplo: relaciones de equivalencia" — https://www.youtube.com/watch?v=rzz92xgPVuY

**Mié 26 Ago** *(práctico, 2h)* — P3 ej. 5, 6, 8
* *Ej 5* — Probar que si f es isomorfismo de posets, f⁻¹ también lo es — 🎥 "Relación de Equivalencia — Demostrar si R es de Equivalencia" — https://www.youtube.com/watch?v=SPMFnKVOww8
* *Ej 6* — Probar que si m es minimal en P, entonces f(m) es minimal en Q — 🎥 "Relaciones de equivalencia — Definición y ejemplo" — https://www.youtube.com/watch?v=DcTP8ouyjCk
* *Ej 8* — Función biyectiva que preserva orden entre L3 y L4 pero no es isomorfismo; no preserva sup/ínf — 🎥 "Relación de equivalencia, reflexiva, simétrica, transitiva" — https://www.youtube.com/watch?v=nBbd6Fuqk8M

**Jue 27 Ago** *(~2h)* — P3 ej. 9, 10, 11
* *Ej 9* — Demostrar x∧(y∧z) = z∧(y∧x) en un reticulado — 🎥 "Relaciones reflexivas, simétricas y transitivas" — https://www.youtube.com/watch?v=KG0Vq337t-Y
* *Ej 10* — Probar que x∨y es cota superior de {x,y} — 🎥 "Propiedades de las relaciones: reflexividad, simetría, antisimetría, transitividad" — https://www.youtube.com/watch?v=m85j8bxFqvU
* *Ej 11* — Decidir cuáles de L1, L2, L3, L4 son complementados — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o

**Vie 28 Ago** *(práctico, 2h — cierra P3 salvo 7\*, 12\*)* — P3 ej. 13 · P4 ej. 1, 2
* *Ej 13* — Para qué valores de n se tiene que Dn se incrusta en L3 — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig
* *Ej 1* — Reticulado L1: complementos de a,b,d,0; ¿complementado?; ¿distributivo? — 🎥 "Ley Distributiva del Álgebra de Boole" — https://www.youtube.com/watch?v=4ZixcbkHydA
* *Ej 2* — Diagramas L3-L11: incrustaciones, isomorfismo con Dn, distributivos, álgebra de Boole — 🎥 "Álgebra Booleana — Introducción" — https://www.youtube.com/watch?v=p58C7OWe3Xk

**Sáb 29 Ago** *(~4h, + Álgebra — cierra P4)* — P4 ej. 3, 4, 5, 6, 7, 8
* *Ej 3* — Demostrar x∨(z∧y) ≤ (x∨z)∧y; comprobar igualdad si distributivo — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o
* *Ej 4* — Demostrar que M3 y N5 no satisfacen la propiedad cancelativa — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig
* *Ej 5* — Demostrar: cancelativa ⟹ distributivo (Teorema M3-N5) — 🎥 "Ley Distributiva del Álgebra de Boole" — https://www.youtube.com/watch?v=4ZixcbkHydA
* *Ej 6* — Determinar átomos e irreducibles de los posets L3, L4, L6, L8, L11 — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 7 (P4)* — Demostrar propiedades de álgebras de Boole: ¬(¬x)=x; ¬(x∧y)=¬x∨¬y — 🎥 "Álgebra Booleana — Introducción" — https://www.youtube.com/watch?v=p58C7OWe3Xk
* *Ej 8 (P4)* — Propiedades del orden asociado a un álgebra de Boole — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o

**Lun 31 Ago** *(~4h, + PyE)* — P5 ej. 1, 2, 3, 4, 5, 7
* *Ej 1 (P5)* — Probar que todo átomo es irreducible — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 2 (P5)* — Relaciones de isomorfismo (D2310 vs P(5 elem.); D90 vs P(4 elem.)) — 🎥 "Ejemplo: relaciones de equivalencia" — https://www.youtube.com/watch?v=rzz92xgPVuY
* *Ej 3 (P5)* — Probar que ∅ es decreciente; unión de decrecientes es decreciente — 🎥 "Relaciones de EQUIVALENCIA — Definición, Clases y Cociente" — https://www.youtube.com/watch?v=ke4FJlEe_EU
* *Ej 4 (P5)* — Para cada reticulado: hallar At(L), Hasse de P(At(L)), determinar álgebras de Boole — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 5 (P5)* — Hasse de irreducibles, Hasse de D(Irr(L)), definir mapa F, usar Birkhoff — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 7 (P5)* — Producto L×M de posets: reticulado y distributividad — 🎥 "Relaciones de equivalencia — Ejercicio 1" — https://www.youtube.com/watch?v=vjjLC7Vh-NI

**Mié 2 Sep** *(práctico, 2h — cierre general del temario)* — P2 ej. 2c\* · P3 ej. 7\*, 12\* · P5 ej. 6\*
* *Ej 2c\* (P2)* — ¿Único maximal (sin ser finito) implica máximo? — 🎥 "Ínfimo, supremo, mínimo y máximo de un conjunto" — https://www.youtube.com/watch?v=RM11dDasmgg
* *Ej 7\* (P3)* — Cuántos isomorfismos hay de P({a,b,c}) en sí mismo — 🎥 "Supremo e Ínfimo — Explicación con ejemplo" — https://www.youtube.com/watch?v=SslId-CutLQ
* *Ej 12\* (P3)* — Si sup(S) existe siempre para todo S⊆P, demostrar que ínf(S) también existe — 🎥 "Supremo e Ínfimo — Cotas y Conjuntos Ordenados" — https://www.youtube.com/watch?v=L3rgqDYANYM
* *Ej 6\* (P5)* — Dar todos los reticulados distributivos con exactamente 3 elementos irreducibles — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig

---

## Notas del método

- **Corrida del 22/8 (gripe):** se perdieron Mié 19, Jue 20 y Vie 21 por gripe. El Sáb 22 se acortó a 3h (repartido con Álgebra) y el Mar 25 se convirtió en un día especial 100% Lógica (sin PyE ni Álgebra) para recuperar terreno. El cierre general pasó del Lun 31 Ago al Mié 2 Sep.
- **Corrida anterior (17/8):** Sáb 15, Dom 16 y Lun 17 se perdieron por un imprevisto familiar. Todo el cronograma se corrió respetando el ritmo real de cada tipo de día (2h en Mié/Jue/Vie, ~4h en Sáb/Lun) en vez de simplemente trasladar el contenido de un día a otro con distinta capacidad.

- Como es matemática discreta/estructural (pruebas y diagramas, no cálculo numérico), varios videos son de teoría general del tema en vez de resolver exactamente el mismo enunciado — el objetivo es entender la técnica de demostración, no encontrar el ejercicio calcado.
- Encontré un video hecho específicamente para este curso de FaMAF sobre el Teorema de Birkhoff — lo reutilicé en varios ejercicios de átomos/irreducibles/representación porque es el más pertinente posible.
- Cuando lleguen las próximas 2 unidades, se agregan con el mismo formato (tabla banco + detalle inline).
- Ejercicios (*) resueltos al cierre de cada práctico, como pediste — quedan agrupados el Jue 27 y Vie 28 para repasar todo junto antes de las casi 2 semanas de margen hasta el parcial.