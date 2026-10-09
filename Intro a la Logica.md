# Introducción a la Lógica y la Computación — Plan de estudio (cuatrimestre 2026)

Unidad 1 (estructuras de orden): primer parcial rendido el 11/9. Unidad 2 (lógica proposicional): prácticos 1 a 5, para el segundo parcial.

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Vie 11 Septiembre | Primer Parcial (estructuras de orden) — **rendido, nota 2.4 (reprobado)** |
| Vie 13 Noviembre | **Segundo Parcial** |
| Vie 20 Noviembre | **Tercer Parcial y Recuperatorio** — el recuperatorio cubre solo el Parcial 1 (Unidad 1, estructuras de orden) |

> Regularidad: aprobar al menos 2 de los 3 parciales (o uno + recuperatorio de otro). Promoción: los 3 parciales ≥6 con promedio ≥7, y todos los TPs ≥6.

---

## Estado actual (8 Octubre)

- **Primer parcial reprobado (2.4).** Se rinden el segundo parcial (13/11) y el recuperatorio (20/11). **El recuperatorio es de la Unidad 1** (confirmado el 8/10): el banco de la unidad 1 queda archivado al final del archivo y se usa en los bloques de repaso.
- **Unidad 2 (lógica proposicional):** 5 filminas de teoría y 5 prácticos (35 ejercicios), **nada empezado todavía**: Lógica no se tocó hasta el 7/10. Arranca el **viernes 9/10**.
- Método para esta unidad: teoría primero (filmina o video + resumen con ejemplos), después el ejercicio; pista antes que solución; las demostraciones no se copian.
- **Ritmo acordado el 7/10:** 1 filmina y medio práctico por día (3 a 4 ejercicios); en Rosario, media filmina y medio práctico por día. Así, las 5 filminas terminan el **Sáb 17 Oct** y los 35 ejercicios el **Vie 23 Oct**, lo que deja del 24/10 al 12/11 como margen de repaso.
- **Bloques de repaso (desde el 15/10):** los jueves 15, 22 y 29/10 (2h cada uno) son repaso del recuperatorio con la Unidad 1; AyED2 pasa a febrero. Del 14 al 19/11, preparación final del recuperatorio.
- Los ejercicios se resuelven y se corrigen en el chat específico de Lógica; este archivo es el plan.

---

## Prácticos de ejercicios (Unidad 2)

| # | Tema | Ejercicios |
|---|---|---|
| P1 | Sintaxis de la lógica proposicional | 6 (6b* de cierre) |
| P2 | Semántica. Noción de consecuencia | 7 |
| P3 | Consecuencia y derivación | 6 |
| P4 | Más sobre derivación | 7 (3b* de cierre) |
| P5 | Conjuntos consistentes | 9 |

**Total: 35 ejercicios.** Los marcados con (*) son de cierre y opcionales.

---

## Conceptos clave (Unidad 2)

- [ ] Alfabeto Σ y conjunto PROP (definición inductiva); ¬φ como abreviatura de φ→⊥
- [ ] Definiciones recursivas sobre fórmulas (ocurrencias, longitud, subfórmulas) e inducción estructural
- [ ] Sustitución φ[ψ/pᵢ]
- [ ] Asignaciones y semántica ⟦φ⟧f; modelos de un conjunto de fórmulas
- [ ] Consecuencia semántica Γ |= φ y validez |= φ
- [ ] Deducción natural: reglas (→I, →E, ∧I/E, ∨I/E, ⊥E, RAA) y cancelación de hipótesis
- [ ] Derivabilidad Γ ⊢ φ y Teorema de Corrección
- [ ] Conjuntos consistentes e inconsistentes
- [ ] Consistentes maximales y Completitud

---

## Banco de ejercicios — Unidad 2: Lógica proposicional

### Práctico 1 — Sintaxis de la lógica proposicional

| Ej | Descripción | Video / pista |
|---|---|---|
| 1 | Para las cadenas dadas decidir cuáles están en Σ*, cuáles en PROP y cuáles en ninguno: (a) p0→p1; (b) ((p∧p)→p); (c) (φ∨ψ); (d) (((p1→p2)→p1)→p2) | *(sin video específico; filmina de la cátedra)* · 💡 chequeá símbolo por símbolo contra el alfabeto (variables pᵢ, ⊥, conectivos, paréntesis) y después contra la definición inductiva de PROP |
| 2 | Demostrar que toda φ∈PROP tiene tantos “(” como “)”, y que la cantidad total de paréntesis es el doble de la cantidad de conectivos distintos de ⊥ que ocurren | [MÉTODO de INDUCCIÓN para demostrar PROPOSICIONES](https://www.youtube.com/watch?v=bNB2Mb3O5C4) *(video general del tema)* · 💡 inducción estructural sobre φ: una base (pᵢ, ⊥) y un paso por cada forma de construir fórmulas |
| 3 | Definir recursivamente ocur(k,φ): la cantidad de ocurrencias de pₖ en φ, para cada φ∈PROP | *(sin video específico; filmina de la cátedra)* · 💡 un caso por cada cláusula de PROP; en la variable, distinguí pᵢ con i=k de i≠k |
| 4 | Definir recursivamente la función “longitud”: cantidad de símbolos de una proposición, incluyendo paréntesis | *(sin video específico; filmina de la cátedra)* · 💡 en (φ□ψ) contá los 2 paréntesis y el conectivo, más la longitud de cada subfórmula |
| 5 | Definir recursivamente S:PROP→P(PROP) tal que S(φ) sea el conjunto de subfórmulas de φ (ej.: S(⊥)={⊥}, S((p0∧p1))={p0,p1,(p0∧p1)}) | *(sin video específico; filmina de la cátedra)* · 💡 S de una fórmula compuesta = {la fórmula} ∪ S de cada una de sus partes |
| 6 | (a) Calcular φ[((p7→⊥)→p3)/p7] para dos fórmulas dadas. (b)(*) Definir recursivamente la sustitución G(φ,ψ,pᵢ)=φ[ψ/pᵢ] — (b) es de cierre, opcional | *(sin video específico; filmina de la cátedra)* · 💡 sustituí cada ocurrencia de p7 por la fórmula completa con sus paréntesis; para (b) un caso por cláusula de PROP (pᵢ vs pⱼ con j≠i) |

### Práctico 2 — Semántica. Noción de consecuencia

| Ej | Descripción | Video / pista |
|---|---|---|
| 1 | Dadas asignaciones parciales f, g, h, calcular la semántica ⟦φ⟧ de las fórmulas indicadas (a-c) | [Tablas de verdad | Ejemplo 1](https://www.youtube.com/watch?v=ZK8QUphO4MA) · 💡 evaluá de adentro hacia afuera con las tablas de cada conectivo; ¬φ es φ→⊥ |
| 2 | Decidir si existe una asignación f que modele cada conjunto: (a) {p0}; (b) {p0,¬p1,p2,¬p3,…}; (c) PROP; (d) {p0,p0→¬p1,p1} | [TABLAS DE VERDAD | OPERADORES LÓGICOS | lógica proposicional | ejercicios resueltos](https://www.youtube.com/watch?v=pttgIlBLm-s) *(video general del tema)* · 💡 f modela Γ si ⟦φ⟧f=1 para toda φ∈Γ: mirá si el conjunto fuerza valores contradictorios en alguna variable |
| 3 | Demostrar: (a) |= ((¬(¬φ))→φ); (b) |= φ si y sólo si ∅ |= φ | *(sin video específico; filmina de la cátedra)* · 💡 usá la definición de |= (toda asignación modela φ); en (b) toda asignación modela a ∅ |
| 4 | Decidir cuáles son ciertas y demostrarlas con la definición de consecuencia (o dar una asignación que la refute): (a) {p0→p1} |= ¬p0∨p1; (b) {p0} |= (p0∧p1); (c) {p0,p0→(p1∨p2)} |= p2 | *(sin video específico; filmina de la cátedra)* · 💡 para refutar buscá una f que haga verdaderas todas las hipótesis y falsa la conclusión |
| 5 | Demostrar: (a) si Γ⊆Δ y Γ |= φ entonces Δ |= φ; (b) si Γ |= φ y {φ} |= ψ entonces Γ |= ψ | *(sin video específico; filmina de la cátedra)* · 💡 tomá una asignación que modele Δ (o Γ) y seguí la definición paso a paso |
| 6 | Determinar φ[(¬p0)/p0] para dos fórmulas dadas (a-b) | *(sin video específico; filmina de la cátedra)* · 💡 igual que P1 ej. 6a: reemplazá cada p0 por (¬p0) |
| 7 | Dada una asignación f, hallar g tal que ⟦φ⟧g = ⟦φ[⊥/p0]⟧f para toda φ∈PROP; caracterizar las φ con ⟦φ⟧f = ⟦φ⟧g | *(sin video específico; filmina de la cátedra)* · 💡 definí g igual que f salvo en p0 y probá por inducción sobre φ |

### Práctico 3 — Consecuencia y derivación

| Ej | Descripción | Video / pista |
|---|---|---|
| 1 | Probar que |= φ→ψ si y sólo si {φ} |= ψ | *(sin video específico; filmina de la cátedra)* · 💡 una dirección por vez, con la tabla del condicional y la definición de |= |
| 2 | Si φ satisface {φ} |= ⊥, ¿cómo es la tabla de verdad de φ? | *(sin video específico; filmina de la cátedra)* · 💡 ¿qué asignaciones modelan φ si de φ se sigue ⊥, que nunca vale 1? |
| 3 | Completar dos derivaciones agregando la regla usada en cada paso y los corchetes de las hipótesis canceladas (se cancelan todas las posibles; ¬φ abrevia φ→⊥) | [7. Ejercicios Resueltos Deducción Natural. Lógica Proposicional](https://www.youtube.com/watch?v=1L2KP-kyYjU) *(video general del tema)* · 💡 identificá cada paso por la forma de la fórmula (→I, →E, ⊥E…); las hipótesis se cancelan en →I y en RAA |
| 4 | Encontrar derivaciones: (a) {φ∧γ, φ→(ψ∧γ)} ⊢ ψ; (b) {φ→(ψ→γ)} ⊢ ψ→(φ→γ); (c) {φ} ⊢ ¬(¬φ∧¬ψ); (d) ⊢ (φ→ψ)→((φ→(ψ→γ))→(φ→γ)) | [Ejercicio de deducción natural en Lóg. Proposicional. Examen feb. 2013](https://www.youtube.com/watch?v=d-9vhwLR6fY) *(video general del tema)* · 💡 trabajá hacia atrás desde la conclusión: si es una implicación, suponé el antecedente y buscá el consecuente |
| 5 | Lo siguiente ya fue demostrado en esta guía: {¬(p2→p5)} ⊢ ¬(¬(¬(p2→p5)) ∧ ¬(p3→((¬p2)∧p5))). ¿En qué ejercicio? | *(sin video específico; filmina de la cátedra)* · 💡 compará la forma con la del ítem 4c, sustituyendo φ y ψ por fórmulas adecuadas |
| 6 | Determinar cuáles son válidas y, para las que lo son, dar derivaciones: (a) {¬φ,ψ→φ} |= γ→(ψ→⊥); (b) {¬φ} |= ψ→(φ∧¬ψ); (c) {¬φ} |= ψ→(φ→¬ψ) | [Métodos de demostración: Reducción al absurdo](https://www.youtube.com/watch?v=3jqzuqDHOkQ) *(video general del tema)* · 💡 primero decidí con la semántica (¿hay una asignación que modele las hipótesis y falle la conclusión?); después derivá |

### Práctico 4 — Más sobre derivación

| Ej | Descripción | Video / pista |
|---|---|---|
| 1 | Completar dos derivaciones (ramas que faltan, reglas y corchetes) para (¬φ∧¬ψ)→¬(φ∨ψ) y para φ∨¬φ; se cancelan todas las hipótesis | [7. Ejercicios Resueltos Deducción Natural. Lógica Proposicional](https://www.youtube.com/watch?v=1L2KP-kyYjU) *(mismo video que otro ejercicio del tema)* · 💡 ∨E necesita un caso por cada rama de la disyunción; la segunda usa RAA |
| 2 | Derivaciones: (a) {¬φ∨ψ} ⊢ φ→ψ (con ∨E); (b) {¬φ∨¬ψ} ⊢ ¬(φ∧ψ); (c) {φ→ψ} ⊢ ¬φ∨ψ; (d) {¬(φ∧ψ)} ⊢ ¬φ∨¬ψ | [Ejercicio de deducción natural en Lóg. Proposicional. Examen feb. 2013](https://www.youtube.com/watch?v=d-9vhwLR6fY) *(mismo video que otro ejercicio del tema)* · 💡 en (c) y (d) la última regla es RAA: suponé la negación de la conclusión y derivá ⊥, no intentes ∨I directo |
| 3 | Con RAA encontrar derivaciones: (a) ⊢ φ↔¬¬φ; (b)(*) ⊢ ((φ→ψ)→φ)→φ — (b) es de cierre, opcional | [Métodos de demostración: Reducción al absurdo](https://www.youtube.com/watch?v=3jqzuqDHOkQ) · 💡 ↔ son dos implicaciones: una dirección sale con →I/→E y la otra con RAA |
| 4 | Encontrar derivaciones: (a) ⊢ (φ→ψ)∨(ψ→φ); (b) ⊢ ((φ→ψ)∧(¬φ→ψ))→ψ | [Métodos de demostración: Reducción al absurdo](https://www.youtube.com/watch?v=3jqzuqDHOkQ) *(mismo video que otro ejercicio del tema)* · 💡 (b) es una prueba por casos sobre φ∨¬φ (ejercicio 1); (a) probablemente RAA |
| 5 | Sean Δ,Γ⊆PROP y φ∈PROP. Demostrar: (a) si Δ∖{φ}⊆Γ entonces Δ⊆Γ∪{φ}; (b) comprobar que sin unir {φ} la afirmación no es cierta; (c) si Δ⊆Γ y Δ⊢φ entonces Γ⊢φ | *(sin video específico; filmina de la cátedra)* · 💡 (a) y (b) son teoría de conjuntos; en (c) la misma derivación sirve con más hipótesis disponibles |
| 6 | Demostrar: (a) ⊢φ implica ⊢ψ→φ; (b) si φ⊢ψ y ¬φ⊢ψ entonces ⊢ψ; (c) Γ∪{φ}⊢ψ implica Γ∖{φ}⊢(φ→φ)∧(φ→ψ); (d) Γ∪{φ}⊢ψ implica Γ⊢φ→(ψ∨¬φ) | *(sin video específico; filmina de la cátedra)* · 💡 armá una derivación nueva a partir de la que te dan, con →I, ∧I, ∨I; en (b) usá φ∨¬φ |
| 7 | Demostrar los casos inductivos (∨I) y (∨E) de la prueba del Teorema de Corrección | [Demostrar una fórmula por INDUCCIÓN MATEMÁTICA │ ejercicio 2](https://www.youtube.com/watch?v=8z4t-MTuyuc) *(video general del tema)* · 💡 hipótesis inductiva: las premisas de la regla son consecuencia semántica de sus hipótesis; probá que la conclusión también (en ∨E separá por casos según qué disyunto valga 1) |

### Práctico 5 — Conjuntos consistentes

| Ej | Descripción | Video / pista |
|---|---|---|
| 1 | Demostrar (con derivaciones o citando resultados del teórico): (a) Γ⊢¬⊥; (b) {p0}⊬p1; (c) {⊥}⊢φ∧¬φ; (d) {¬p0,¬(p1∧¬p2)}⊬p2→p0 | *(sin video específico; filmina de la cátedra)* · 💡 para ⊬ usá Corrección: si Γ⊢φ entonces Γ|=φ, y buscá una asignación que lo contradiga |
| 2 | Decidir cuáles de los siguientes conjuntos son consistentes (a-f), incluyendo los infinitos (“pares implican impares”, {p2n}∪{¬p3n+1}, {p2n}∪{¬p4n+1}) | *(sin video específico; filmina de la cátedra)* · 💡 consistente ⟺ tiene modelo: buscá una asignación que satisfaga todas; en los infinitos mirá qué variables fuerza cada familia |
| 3 | Decidir si son verdaderos o falsos y justificar: (a) Γ consistente ⟹ ⊥∉Γ; (b) Γ consistente ⟹ ⊥ no ocurre en ninguna fórmula de Γ; (c) Γ inconsistente ⟹ existe φ con φ∈Γ y ¬φ∈Γ | *(sin video específico; filmina de la cátedra)* · 💡 para (b) pensá qué fórmulas con ⊥ son tautologías; para (c) pensá un conjunto inconsistente donde la contradicción aparece recién al derivar |
| 4 | Demostrar que “Γ⊢¬φ” equivale a “Γ∪{φ} es inconsistente” | *(sin video específico; filmina de la cátedra)* · 💡 →I y →E con ⊥, una dirección por vez |
| 5 | Demostrar que Γ⁺ := {φ∈PROP : ⊥ no ocurre en φ} es consistente (ayuda: una f explícita con ⟦φ⟧f=1 para toda φ∈Γ⁺) | *(sin video específico; filmina de la cátedra)* · 💡 probá por inducción que una asignación constante hace verdaderas a las fórmulas sin ⊥ |
| 6 | Probar que todo Γ consistente maximal realiza la disyunción: φ∨ψ∈Γ si y sólo si φ∈Γ ó ψ∈Γ | *(sin video específico; filmina de la cátedra)* · 💡 usá que un maximal consistente es cerrado por derivación y que para toda φ vale φ∈Γ o ¬φ∈Γ |
| 7 | Sea Γ consistente maximal con {p0,¬(p1→p2),p3∨p2}⊆Γ. Decidir si están en Γ: (a) ¬p0; (b) (¬p1)∨p2; (c) p3; (d) p2→p5; (e) p1∨p6 | *(sin video específico; filmina de la cátedra)* · 💡 usá Completitud: Γ tiene un modelo f; ¿qué fuerzan p0, ¬(p1→p2) y p3∨p2 sobre f? |
| 8 | Dar al menos dos conjuntos Γ consistentes maximales distintos que contengan {p0,¬(p1→p2),p3∨p2} | *(sin video específico; filmina de la cátedra)* · 💡 un maximal consistente es el conjunto de fórmulas verdaderas bajo una asignación; variá la asignación en lo que quede libre |
| 9 | Decidir si son consistentes maximales: (a) {φ∈PROP : {p0,p1,p3,…}⊢φ}; (b) las tautologías | *(sin video específico; filmina de la cátedra)* · 💡 maximal ⟺ para toda φ, φ∈Γ o ¬φ∈Γ: chequeá si eso se cumple |

> **Sobre los videos de esta unidad:** casi no hay videos en español que resuelvan estos enunciados. De los 35 ejercicios, 11 tienen un video de referencia (7 videos distintos, de deducción natural, tablas de verdad, reducción al absurdo e inducción; algunos se repiten y todos son de tema general, no resuelven el enunciado exacto). Los otros 24 se apoyan en la filmina de la cátedra más una pista.

---

## Reparto semanal de materias (4 materias)

| Día | Materia(s) |
|---|---|
| Lunes (día completo, sin clase) | **Lógica, Álgebra y PyE** |
| Martes (clase 9-13 PyE + 14-18 Álgebra) | **Lógica** |
| Miércoles (clase 9-13 Lógica) | **Álgebra** |
| Jueves (clase 9-13 PyE + 14-18 Álgebra) | **Repaso de recuperatorios** (Lógica U1) — AyED2 pasa a febrero |
| Viernes (clase 9-13 Lógica) | Libre — sin materia |
| Sábado (día completo, sin clase) | **Lógica, Álgebra y PyE** |
| Domingo (día completo, sin clase) | **PyE** + **repaso de recuperatorios** (Álgebra) — AyED2 pasa a febrero |

> **Cómo se calculan los ejercicios por día:** unos 3 ejercicios cada 2 h de práctico (los prácticos en clase, el particular y las noches) y hasta 4 en los días completos (Sáb, Dom y Lun) de PyE y Álgebra. Las primeras 2 h de cada clase son teoría en vivo, no ejercicios. Cuando una materia se queda sin ejercicios nuevos, los días siguientes quedan como repaso: ese es el margen real antes del examen.

---

## Cronograma día por día

> Los días anteriores al 6/10 se conservan tal cual estaban (Unidad 1, agosto-septiembre); desde el 6/10 sigue el plan de la Unidad 2.

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
| Sáb 5 Sep | Sáb | **P2 ej. 4, 5, 6, 2c\* (cierra P2) · P3 ej. 1, 2** *(hecho)* |
| ~~Dom 6 Sep~~ | ~~Dom~~ | **PERDIDO** (solo teoría/resumen, sin ejercicios) |
| Lun 7 Sep | Lun | **P3 ej. 3, 4, 5, 6, 8, 9, 10** |
| Mar 8 Sep | Mar | **P3 ej. 13, 7\*, 12\* (cierra P3) · P4 ej. 1, 2, 3, 4** |
| Mié 9 Sep | Mié | **P4 ej. 5, 6, 7, 8 (cierra P4) · P5 ej. 1** |
| Jue 10 Sep | Jue | **P5 ej. 2, 3, 4, 5, 7, 6\* (cierra P5, temario completo)** |
| **Vie 11 Sep** | Vie | **PRIMER PARCIAL** |
| Sáb 12 Sep → Lun 5 Oct | — | Sin plan registrado en este archivo. **Vie 11 Sep: Primer Parcial — reprobado (2.4).** Se pasó a la Unidad 2. |
| **— Desde acá: plan nuevo (corrida del 5/10) —** | | |
| Mar 6 Oct | Mar | otras: Álgebra, PyE |
| Mié 7 Oct | Mié | **Lógica** — sin avance hoy (día de Álgebra) · otras: Álgebra |
| Jue 8 Oct | Jue | otras: Álgebra, PyE (día sin avance en todo) |
| Vie 9 Oct | Vie | Viaje a Rosario (bus 16:15) · **Lógica** (2h) — Filmina 1 · P1 ej. 1, 2, 3 |
| Sáb 10 Oct | Sáb | Rosario · **Lógica** (~3h) — ½ filmina 2 · P1 ej. 4, 5, 6 |
| Dom 11 Oct | Dom | Rosario · **Lógica** (~3.5h) — ½ filmina 2 · P2 ej. 1, 2, 3, 4 |
| Lun 12 Oct | Lun | Rosario · otras: Álgebra |
| Mar 13 Oct | Mar | Libre — vuelve de Rosario (se pierden las clases de PyE y Álgebra) |
| Mié 14 Oct | Mié | **Lógica** (~3h) — Filmina 3 · P2 ej. 5, 6, 7 · otras: Álgebra |
| Jue 15 Oct | Jue | **Lógica** (2h, bloque de repaso) — repaso del recuperatorio (Unidad 1): ver bloques de repaso al final · otras: Álgebra, PyE |
| Vie 16 Oct | Vie | **Lógica** (~3h) — Filmina 4 · P3 ej. 1, 2, 3 |
| Sáb 17 Oct | Sáb | **Lógica** (~3.5h) — Filmina 5 (cierra la teoría) · P3 ej. 4, 5, 6 · otras: Álgebra, PyE |
| Dom 18 Oct | Dom | otras: PyE, repaso recup. Álgebra |
| Lun 19 Oct | Lun | **Lógica** (~2.5h) — P4 ej. 1, 2, 3, 4 · otras: Álgebra, PyE |
| Mar 20 Oct | Mar | **Lógica** (2h) — P4 ej. 5, 6, 7 · otras: Álgebra, PyE |
| Mié 21 Oct | Mié | **Lógica** (~3h) — P5 ej. 1, 2, 3, 4, 5 · otras: Álgebra |
| Jue 22 Oct | Jue | **Lógica** (2h, bloque de repaso) — repaso del recuperatorio (Unidad 1): ver bloques de repaso al final · otras: Álgebra, PyE |
| Vie 23 Oct | Vie | **Lógica** (~2.5h) — P5 ej. 6, 7, 8, 9 |
| Sáb 24 Oct | Sáb | **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra, PyE |
| Dom 25 Oct | Dom | otras: PyE, repaso recup. Álgebra |
| Lun 26 Oct | Lun | **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra, PyE |
| Mar 27 Oct | Mar | **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra, PyE |
| Mié 28 Oct | Mié | **Lógica** (2h) — repaso / SR / parciales viejos *(tarde cedida a PyE)* · otras: Álgebra |
| Jue 29 Oct | Jue | **Lógica** (2h, bloque de repaso) — repaso del recuperatorio (Unidad 1): ver bloques de repaso al final · otras: Álgebra, PyE |
| Vie 30 Oct | Vie | **Lógica** (2h) — repaso / SR / parciales viejos |
| Sáb 31 Oct | Sáb | **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra, PyE |
| Dom 1 Nov | Dom | otras: PyE |
| Lun 2 Nov | Lun | **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra, PyE |
| Mar 3 Nov | Mar | **PARCIAL 2 de PyE** · **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra |
| Mié 4 Nov | Mié | **Lógica** (2h) — repaso / SR / parciales viejos · otras: Álgebra |
| Jue 5 Nov | Jue | **PARCIAL 2 de Álgebra** |
| Vie 6 Nov | Vie | **Lógica** (2h) — repaso / SR / parciales viejos |
| Sáb 7 Nov | Sáb | **Lógica** (2h) — repaso / SR / parciales viejos |
| Dom 8 Nov | Dom | otras: repaso recup. Álgebra |
| Lun 9 Nov | Lun | **Lógica** (2h) — repaso / SR / parciales viejos |
| Mar 10 Nov | Mar | **Lógica** (2h) — repaso / SR / parciales viejos |
| Mié 11 Nov | Mié | **Lógica** (2h) — repaso / SR / parciales viejos |
| Jue 12 Nov | Jue | repaso final antes del parcial, sin ejercicios nuevos |
| Vie 13 Nov | Vie | **PARCIAL 2 de Lógica** |
| Sáb 14 Nov | Sáb | **Lógica** (~1.5h) — recuperatorio (Unidad 1): temas flojos del primer parcial corregido · otras: Álgebra, PyE |
| Dom 15 Nov | Dom | **Lógica** (2h) — recuperatorio (Unidad 1): ejercicios tipo parcial · otras: PyE |
| Lun 16 Nov | Lun | otras: Álgebra, PyE (liviano) |
| Mar 17 Nov | Mar | otras: Álgebra, **RECUPERATORIO de PyE** |
| Mié 18 Nov | Mié | **Lógica** (2h) — recuperatorio (Unidad 1): simulacro con un parcial viejo, con tiempo · otras: Álgebra |
| Jue 19 Nov | Jue | **Lógica** (1.5h, noche) — repaso liviano del recuperatorio · **Recuperatorio de Álgebra** |
| Vie 20 Nov | Vie | **Tercer parcial y recuperatorio de Lógica** |

---

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
* *Ej 1 (P3)* — En el reticulado L2: encontrar v∨x, s∨v y u∨v — 🎥 "Video lección Retículos y álgebras de Boole — parte 2" *(general, no resuelve la cuenta exacta)* — https://www.youtube.com/watch?v=cn5_iePGK9o · pista: leer del diagrama las cotas superiores comunes de cada par y tomar la menor
* *Ej 2 (P3)* — Demostrar x∨(y∧z) ≤ (x∨y)∧(x∨z) en todo poset reticulado — 🎥 "Video lección Retículos y álgebras de Boole — parte 1" *(general)* — https://www.youtube.com/watch?v=R9zzpsSIVig · pista: x≤x∨y, y∧z≤y≤x∨y, y∧z≤z≤x∨z ⟹ y∧z≤(x∨y)∧(x∨z)

**Dom 6 Sep** — perdido, solo se hizo resumen teórico (sin ejercicios).

**Lun 7 Sep** *(~5.5h — 3-5pm, 5:45-7:45pm, 8:30-10pm)* — P3 ej. 3, 4, 5, 6, 8, 9, 10
* *Ej 3 (P3)* — Determinar si los mapeos f dados son isomorfismos de posets; qué falla si no — 🎥 "Video lección Retículos y álgebras de Boole — parte 1" *(general)* — https://www.youtube.com/watch?v=R9zzpsSIVig · pista: chequear biyectividad + que x≤y ⟺ f(x)≤f(y) en ambos sentidos
* *Ej 4 (P3)* — Determinar si se dan los isomorfismos indicados (D6 vs P({a,b}); D30 vs P({a,b,c})) — 🎥 "Video lección Retículos y álgebras de Boole — parte 2" *(general)* — https://www.youtube.com/watch?v=cn5_iePGK9o · pista: f(d) = conjunto de primos que dividen a d

**Mar 8 Sep** *(~5.5h — mismo formato que el lunes)* — P3 ej. 13, 7*, 12* (cierra P3) · P4 ej. 1, 2, 3, 4
* *Ej 5 (P3)* — Probar que si f es isomorfismo de posets, f⁻¹ también lo es — 🎥 "Video lección Retículos y álgebras de Boole — parte 1" *(general)* — https://www.youtube.com/watch?v=R9zzpsSIVig · pista: f⁻¹ ya es biyectiva; usar que f preserva orden en ambos sentidos
* *Ej 6 (P3)* — Probar que si m es minimal en P, entonces f(m) es minimal en Q — 🎥 "Video lección Retículos y álgebras de Boole — parte 2" *(general)* — https://www.youtube.com/watch?v=cn5_iePGK9o · pista: por el absurdo, usando sobreyectividad de f
* *Ej 8 (P3)* — Función biyectiva que preserva orden entre L3 y L4 pero no es isomorfismo; no preserva sup/ínf — 🎥 "Video lección Retículos y álgebras de Boole — parte 1" *(general)* — https://www.youtube.com/watch?v=R9zzpsSIVig · pista: preservar orden en un solo sentido no alcanza
* *Ej 13 (P3)* — Para qué valores de n se tiene que Dn se incrusta en L3 — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig

**Mié 9 Sep** *(~4.25h — 2:30-4:30pm, 7:30-8:45pm, 9-10pm)* — P4 ej. 5, 6, 7, 8 (cierra P4) · P5 ej. 1
* *Ej 1 (P4)* — Reticulado L1: complementos de a,b,d,0; ¿es complementado?; ¿es distributivo? — 🎥 "Ley Distributiva del Álgebra de Boole" — https://www.youtube.com/watch?v=4ZixcbkHydA
* *Ej 2 (P4)* — Diagramas L3-L11: incrustaciones, isomorfismo con Dn, cuáles son distributivos, cuáles son álgebra de Boole — 🎥 "Álgebra Booleana — Introducción, Ejercicios para Aprender" — https://www.youtube.com/watch?v=p58C7OWe3Xk
* *Ej 3 (P4)* — Demostrar x∨(z∧y) ≤ (x∨z)∧y; comprobar igualdad si S es distributivo — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o
* *Ej 4 (P4)* — Demostrar que M3 y N5 no satisfacen la propiedad cancelativa — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig
* *Ej 5 (P4)* — Demostrar: si un reticulado satisface cancelativa, entonces es distributivo (Teorema M3-N5) — 🎥 "Ley Distributiva del Álgebra de Boole" — https://www.youtube.com/watch?v=4ZixcbkHydA
* *Ej 6 (P4)* — Determinar átomos e irreducibles de los posets L3, L4, L6, L8, L11 — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 7 (P4)* — Demostrar propiedades de álgebras de Boole: ¬(¬x)=x; ¬(x∧y)=¬x∨¬y — 🎥 "Álgebra Booleana — Introducción, Ejercicios para Aprender" — https://www.youtube.com/watch?v=p58C7OWe3Xk
* *Ej 8 (P4)* — Propiedades del orden asociado a un álgebra de Boole: x≤y ⟺ ¬y≤¬x; etc. — 🎥 "Retículos y álgebras de Boole — parte 2" — https://www.youtube.com/watch?v=cn5_iePGK9o
* *Ej 1 (P5)* — Probar que todo átomo es irreducible — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs

**Jue 10 Sep** *(~5h — 2:30-4:30pm, 5-7pm, 7:15-8:15pm)* — P5 ej. 2, 3, 4, 5, 7, 6* (cierra P5, temario completo)
* *Ej 2 (P5)* — Determinar si se cumplen las relaciones de isomorfismo (D2310 vs P(5 elem.); D90 vs P(4 elem.)) — 🎥 "Video lección Retículos y álgebras de Boole — parte 2" *(general)* — https://www.youtube.com/watch?v=cn5_iePGK9o · pista: mismo criterio que P3 ej.4
* *Ej 3 (P5)* — Probar que ∅ es decreciente; si D1 y D2 son decrecientes, D1∪D2 también lo es — 🎥 "Video lección Retículos y álgebras de Boole — parte 1" *(general)* — https://www.youtube.com/watch?v=R9zzpsSIVig · pista: vacuamente cierto en ∅; para la unión, usar la definición en el conjunto al que pertenece x
* *Ej 4 (P5)* — Para cada reticulado: hallar At(L), dibujar Hasse de P(At(L)), determinar cuáles son álgebra de Boole — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 5 (P5)* — Hasse de irreducibles, Hasse de D(Irr(L)), definir el mapa F, usar Birkhoff para ver si es distributivo — 🎥 "Teorema de Representación de Birkhoff — ILC FAMAF" — https://www.youtube.com/watch?v=Kr-qM-TqlLs
* *Ej 7 (P5)* — Producto L×M de posets: si L,M son reticulados, L×M también; ídem distributividad — 🎥 "Video lección Retículos y álgebras de Boole — parte 2" *(general)* — https://www.youtube.com/watch?v=cn5_iePGK9o · pista: construir sup/ínf componente a componente
* *Ej 6* (P5)* — Dar todos los reticulados distributivos con exactamente 3 elementos irreducibles — 🎥 "Retículos y álgebras de Boole — parte 1" — https://www.youtube.com/watch?v=R9zzpsSIVig

> **Desde acá: plan nuevo (corrida del 5/10).** Todo lo de arriba es historial, tal cual estaba.

**Mié 7 Oct** — Lógica sin avance *(día de Álgebra: clases copiadas + particular 17-19)*
* *Tarea* — Hoy no se tocó Lógica. La teoría de la unidad 2 (5 filminas) y los 5 prácticos arrancan el viernes 9/10, con ritmo de 1 filmina y medio práctico por día (media filmina y medio práctico en Rosario).

**Vie 9 Oct** *(2h)* — Filmina 1 · P1 ej. 1, 2, 3  ·  _filmina 1 en la clase de 9 a 11 + práctico en clase 11-13_
* *Teoría* — Filmina 1 de la unidad 2: leer, resumir y anotar con ejemplos (en clase, teoría en vivo de 9 a 11).
* *Ej 1 (P1)* — Para las cadenas dadas decidir cuáles están en Σ*, cuáles en PROP y cuáles en ninguno: (a) p0→p1; (b) ((p∧p)→p); (c) (φ∨ψ); (d) (((p1→p2)→p1)→p2) — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: chequeá símbolo por símbolo contra el alfabeto (variables pᵢ, ⊥, conectivos, paréntesis) y después contra la definición inductiva de PROP
* *Ej 2 (P1)* — Demostrar que toda φ∈PROP tiene tantos “(” como “)”, y que la cantidad total de paréntesis es el doble de la cantidad de conectivos distintos de ⊥ que ocurren — 🎥 "MÉTODO de INDUCCIÓN para demostrar PROPOSICIONES" *(video general del tema)* — https://www.youtube.com/watch?v=bNB2Mb3O5C4 · 💡 Pista: inducción estructural sobre φ: una base (pᵢ, ⊥) y un paso por cada forma de construir fórmulas
* *Ej 3 (P1)* — Definir recursivamente ocur(k,φ): la cantidad de ocurrencias de pₖ en φ, para cada φ∈PROP — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: un caso por cada cláusula de PROP; en la variable, distinguí pᵢ con i=k de i≠k

**Sáb 10 Oct** *(~3h)* — ½ filmina 2 · P1 ej. 4, 5, 6  ·  _Rosario, mañana_
* *Teoría* — Filmina 2, primera mitad: leer y resumir con ejemplos (Rosario, ritmo reducido).
* *Ej 4 (P1)* — Definir recursivamente la función “longitud”: cantidad de símbolos de una proposición, incluyendo paréntesis — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: en (φ□ψ) contá los 2 paréntesis y el conectivo, más la longitud de cada subfórmula
* *Ej 5 (P1)* — Definir recursivamente S:PROP→P(PROP) tal que S(φ) sea el conjunto de subfórmulas de φ (ej.: S(⊥)={⊥}, S((p0∧p1))={p0,p1,(p0∧p1)}) — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: S de una fórmula compuesta = {la fórmula} ∪ S de cada una de sus partes
* *Ej 6 (P1)* — (a) Calcular φ[((p7→⊥)→p3)/p7] para dos fórmulas dadas. (b)(*) Definir recursivamente la sustitución G(φ,ψ,pᵢ)=φ[ψ/pᵢ] — (b) es de cierre, opcional — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: sustituí cada ocurrencia de p7 por la fórmula completa con sus paréntesis; para (b) un caso por cláusula de PROP (pᵢ vs pⱼ con j≠i)

**Dom 11 Oct** *(~3.5h)* — ½ filmina 2 · P2 ej. 1, 2, 3, 4  ·  _Rosario, mañana/noche_
* *Teoría* — Filmina 2, segunda mitad: cerrar el resumen con ejemplos (Rosario, ritmo reducido).
* *Ej 1 (P2)* — Dadas asignaciones parciales f, g, h, calcular la semántica ⟦φ⟧ de las fórmulas indicadas (a-c) — 🎥 "Tablas de verdad | Ejemplo 1" — https://www.youtube.com/watch?v=ZK8QUphO4MA · 💡 Pista: evaluá de adentro hacia afuera con las tablas de cada conectivo; ¬φ es φ→⊥
* *Ej 2 (P2)* — Decidir si existe una asignación f que modele cada conjunto: (a) {p0}; (b) {p0,¬p1,p2,¬p3,…}; (c) PROP; (d) {p0,p0→¬p1,p1} — 🎥 "TABLAS DE VERDAD | OPERADORES LÓGICOS | lógica proposicional | ejercicios resueltos" *(video general del tema)* — https://www.youtube.com/watch?v=pttgIlBLm-s · 💡 Pista: f modela Γ si ⟦φ⟧f=1 para toda φ∈Γ: mirá si el conjunto fuerza valores contradictorios en alguna variable
* *Ej 3 (P2)* — Demostrar: (a) |= ((¬(¬φ))→φ); (b) |= φ si y sólo si ∅ |= φ — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: usá la definición de |= (toda asignación modela φ); en (b) toda asignación modela a ∅
* *Ej 4 (P2)* — Decidir cuáles son ciertas y demostrarlas con la definición de consecuencia (o dar una asignación que la refute): (a) {p0→p1} |= ¬p0∨p1; (b) {p0} |= (p0∧p1); (c) {p0,p0→(p1∨p2)} |= p2 — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: para refutar buscá una f que haga verdaderas todas las hipótesis y falsa la conclusión

**Mié 14 Oct** *(~3h)* — Filmina 3 · P2 ej. 5, 6, 7  ·  _práctico en clase 11-13_
* *Teoría* — Filmina 3 de la unidad 2: teoría en vivo de 9 a 11 y completar el resumen a la tarde.
* *Ej 5 (P2)* — Demostrar: (a) si Γ⊆Δ y Γ |= φ entonces Δ |= φ; (b) si Γ |= φ y {φ} |= ψ entonces Γ |= ψ — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: tomá una asignación que modele Δ (o Γ) y seguí la definición paso a paso
* *Ej 6 (P2)* — Determinar φ[(¬p0)/p0] para dos fórmulas dadas (a-b) — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: igual que P1 ej. 6a: reemplazá cada p0 por (¬p0)
* *Ej 7 (P2)* — Dada una asignación f, hallar g tal que ⟦φ⟧g = ⟦φ[⊥/p0]⟧f para toda φ∈PROP; caracterizar las φ con ⟦φ⟧f = ⟦φ⟧g — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: definí g igual que f salvo en p0 y probá por inducción sobre φ

**Vie 16 Oct** *(~3h)* — Filmina 4 · P3 ej. 1, 2, 3  ·  _filmina en clase 9-11 + práctico en clase 11-13_
* *Teoría* — Filmina 4 de la unidad 2: teoría en vivo de 9 a 11 y resumen con ejemplos.
* *Ej 1 (P3)* — Probar que |= φ→ψ si y sólo si {φ} |= ψ — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: una dirección por vez, con la tabla del condicional y la definición de |=
* *Ej 2 (P3)* — Si φ satisface {φ} |= ⊥, ¿cómo es la tabla de verdad de φ? — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: ¿qué asignaciones modelan φ si de φ se sigue ⊥, que nunca vale 1?
* *Ej 3 (P3)* — Completar dos derivaciones agregando la regla usada en cada paso y los corchetes de las hipótesis canceladas (se cancelan todas las posibles; ¬φ abrevia φ→⊥) — 🎥 "7. Ejercicios Resueltos Deducción Natural. Lógica Proposicional" *(video general del tema)* — https://www.youtube.com/watch?v=1L2KP-kyYjU · 💡 Pista: identificá cada paso por la forma de la fórmula (→I, →E, ⊥E…); las hipótesis se cancelan en →I y en RAA

**Sáb 17 Oct** *(~3.5h)* — Filmina 5 (cierra la teoría) · P3 ej. 4, 5, 6  ·  _sábado_
* *Teoría* — Filmina 5 de la unidad 2: cierra la teoría; hacer un resumen general de las 5 filminas.
* *Ej 4 (P3)* — Encontrar derivaciones: (a) {φ∧γ, φ→(ψ∧γ)} ⊢ ψ; (b) {φ→(ψ→γ)} ⊢ ψ→(φ→γ); (c) {φ} ⊢ ¬(¬φ∧¬ψ); (d) ⊢ (φ→ψ)→((φ→(ψ→γ))→(φ→γ)) — 🎥 "Ejercicio de deducción natural en Lóg. Proposicional. Examen feb. 2013" *(video general del tema)* — https://www.youtube.com/watch?v=d-9vhwLR6fY · 💡 Pista: trabajá hacia atrás desde la conclusión: si es una implicación, suponé el antecedente y buscá el consecuente
* *Ej 5 (P3)* — Lo siguiente ya fue demostrado en esta guía: {¬(p2→p5)} ⊢ ¬(¬(¬(p2→p5)) ∧ ¬(p3→((¬p2)∧p5))). ¿En qué ejercicio? — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: compará la forma con la del ítem 4c, sustituyendo φ y ψ por fórmulas adecuadas
* *Ej 6 (P3)* — Determinar cuáles son válidas y, para las que lo son, dar derivaciones: (a) {¬φ,ψ→φ} |= γ→(ψ→⊥); (b) {¬φ} |= ψ→(φ∧¬ψ); (c) {¬φ} |= ψ→(φ→¬ψ) — 🎥 "Métodos de demostración: Reducción al absurdo" *(video general del tema)* — https://www.youtube.com/watch?v=3jqzuqDHOkQ · 💡 Pista: primero decidí con la semántica (¿hay una asignación que modele las hipótesis y falle la conclusión?); después derivá

**Lun 19 Oct** *(~2.5h)* — P4 ej. 1, 2, 3, 4  ·  _tarde_
* *Ej 1 (P4)* — Completar dos derivaciones (ramas que faltan, reglas y corchetes) para (¬φ∧¬ψ)→¬(φ∨ψ) y para φ∨¬φ; se cancelan todas las hipótesis — 🎥 "7. Ejercicios Resueltos Deducción Natural. Lógica Proposicional" *(mismo video que otro ejercicio del tema)* — https://www.youtube.com/watch?v=1L2KP-kyYjU · 💡 Pista: ∨E necesita un caso por cada rama de la disyunción; la segunda usa RAA
* *Ej 2 (P4)* — Derivaciones: (a) {¬φ∨ψ} ⊢ φ→ψ (con ∨E); (b) {¬φ∨¬ψ} ⊢ ¬(φ∧ψ); (c) {φ→ψ} ⊢ ¬φ∨ψ; (d) {¬(φ∧ψ)} ⊢ ¬φ∨¬ψ — 🎥 "Ejercicio de deducción natural en Lóg. Proposicional. Examen feb. 2013" *(mismo video que otro ejercicio del tema)* — https://www.youtube.com/watch?v=d-9vhwLR6fY · 💡 Pista: en (c) y (d) la última regla es RAA: suponé la negación de la conclusión y derivá ⊥, no intentes ∨I directo
* *Ej 3 (P4)* — Con RAA encontrar derivaciones: (a) ⊢ φ↔¬¬φ; (b)(*) ⊢ ((φ→ψ)→φ)→φ — (b) es de cierre, opcional — 🎥 "Métodos de demostración: Reducción al absurdo" — https://www.youtube.com/watch?v=3jqzuqDHOkQ · 💡 Pista: ↔ son dos implicaciones: una dirección sale con →I/→E y la otra con RAA
* *Ej 4 (P4)* — Encontrar derivaciones: (a) ⊢ (φ→ψ)∨(ψ→φ); (b) ⊢ ((φ→ψ)∧(¬φ→ψ))→ψ — 🎥 "Métodos de demostración: Reducción al absurdo" *(mismo video que otro ejercicio del tema)* — https://www.youtube.com/watch?v=3jqzuqDHOkQ · 💡 Pista: (b) es una prueba por casos sobre φ∨¬φ (ejercicio 1); (a) probablemente RAA

**Mar 20 Oct** *(2h)* — P4 ej. 5, 6, 7  ·  _noche_
* *Ej 5 (P4)* — Sean Δ,Γ⊆PROP y φ∈PROP. Demostrar: (a) si Δ∖{φ}⊆Γ entonces Δ⊆Γ∪{φ}; (b) comprobar que sin unir {φ} la afirmación no es cierta; (c) si Δ⊆Γ y Δ⊢φ entonces Γ⊢φ — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: (a) y (b) son teoría de conjuntos; en (c) la misma derivación sirve con más hipótesis disponibles
* *Ej 6 (P4)* — Demostrar: (a) ⊢φ implica ⊢ψ→φ; (b) si φ⊢ψ y ¬φ⊢ψ entonces ⊢ψ; (c) Γ∪{φ}⊢ψ implica Γ∖{φ}⊢(φ→φ)∧(φ→ψ); (d) Γ∪{φ}⊢ψ implica Γ⊢φ→(ψ∨¬φ) — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: armá una derivación nueva a partir de la que te dan, con →I, ∧I, ∨I; en (b) usá φ∨¬φ
* *Ej 7 (P4)* — Demostrar los casos inductivos (∨I) y (∨E) de la prueba del Teorema de Corrección — 🎥 "Demostrar una fórmula por INDUCCIÓN MATEMÁTICA │ ejercicio 2" *(video general del tema)* — https://www.youtube.com/watch?v=8z4t-MTuyuc · 💡 Pista: hipótesis inductiva: las premisas de la regla son consecuencia semántica de sus hipótesis; probá que la conclusión también (en ∨E separá por casos según qué disyunto valga 1)

**Mié 21 Oct** *(~3h)* — P5 ej. 1, 2, 3, 4, 5  ·  _práctico en clase 11-13_
* *Ej 1 (P5)* — Demostrar (con derivaciones o citando resultados del teórico): (a) Γ⊢¬⊥; (b) {p0}⊬p1; (c) {⊥}⊢φ∧¬φ; (d) {¬p0,¬(p1∧¬p2)}⊬p2→p0 — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: para ⊬ usá Corrección: si Γ⊢φ entonces Γ|=φ, y buscá una asignación que lo contradiga
* *Ej 2 (P5)* — Decidir cuáles de los siguientes conjuntos son consistentes (a-f), incluyendo los infinitos (“pares implican impares”, {p2n}∪{¬p3n+1}, {p2n}∪{¬p4n+1}) — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: consistente ⟺ tiene modelo: buscá una asignación que satisfaga todas; en los infinitos mirá qué variables fuerza cada familia
* *Ej 3 (P5)* — Decidir si son verdaderos o falsos y justificar: (a) Γ consistente ⟹ ⊥∉Γ; (b) Γ consistente ⟹ ⊥ no ocurre en ninguna fórmula de Γ; (c) Γ inconsistente ⟹ existe φ con φ∈Γ y ¬φ∈Γ — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: para (b) pensá qué fórmulas con ⊥ son tautologías; para (c) pensá un conjunto inconsistente donde la contradicción aparece recién al derivar
* *Ej 4 (P5)* — Demostrar que “Γ⊢¬φ” equivale a “Γ∪{φ} es inconsistente” — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: →I y →E con ⊥, una dirección por vez
* *Ej 5 (P5)* — Demostrar que Γ⁺ := {φ∈PROP : ⊥ no ocurre en φ} es consistente (ayuda: una f explícita con ⟦φ⟧f=1 para toda φ∈Γ⁺) — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: probá por inducción que una asignación constante hace verdaderas a las fórmulas sin ⊥

**Vie 23 Oct** *(~2.5h)* — P5 ej. 6, 7, 8, 9  ·  _práctico en clase 11-13_
* *Ej 6 (P5)* — Probar que todo Γ consistente maximal realiza la disyunción: φ∨ψ∈Γ si y sólo si φ∈Γ ó ψ∈Γ — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: usá que un maximal consistente es cerrado por derivación y que para toda φ vale φ∈Γ o ¬φ∈Γ
* *Ej 7 (P5)* — Sea Γ consistente maximal con {p0,¬(p1→p2),p3∨p2}⊆Γ. Decidir si están en Γ: (a) ¬p0; (b) (¬p1)∨p2; (c) p3; (d) p2→p5; (e) p1∨p6 — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: usá Completitud: Γ tiene un modelo f; ¿qué fuerzan p0, ¬(p1→p2) y p3∨p2 sobre f?
* *Ej 8 (P5)* — Dar al menos dos conjuntos Γ consistentes maximales distintos que contengan {p0,¬(p1→p2),p3∨p2} — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: un maximal consistente es el conjunto de fórmulas verdaderas bajo una asignación; variá la asignación en lo que quede libre
* *Ej 9 (P5)* — Decidir si son consistentes maximales: (a) {φ∈PROP : {p0,p1,p3,…}⊢φ}; (b) las tautologías — *(sin video específico; apoyate en la filmina correspondiente)* · 💡 Pista: maximal ⟺ para toda φ, φ∈Γ o ¬φ∈Γ: chequeá si eso se cumple

### Bloques de repaso del recuperatorio (Unidad 1: estructuras de orden)

> El lugar de AyED2 de los jueves pasa a repaso de la Unidad 1. Con el primer parcial corregido (2.4) se arma la lista de temas flojos; el banco de la Unidad 1 está al final del archivo.

* **Jue 15 Oct** *(2h)* — Ver el parcial corregido: listar los ejercicios perdidos y el tema de cada uno. Repasar el primer tema flojo.
* **Jue 22 Oct** *(2h)* — Segundo tema flojo + 2 ejercicios del banco de la Unidad 1.
* **Jue 29 Oct** *(2h)* — Tercer tema flojo + 2 ejercicios del banco de la Unidad 1.
* **Sáb 14 Nov** *(~1.5h)* — Temas flojos del parcial corregido. **Dom 15 Nov** *(2h)* — ejercicios tipo parcial.
* **Mié 18 Nov** *(2h)* — Simulacro con un parcial viejo, con tiempo. **Jue 19 Nov** *(1.5h, noche)* — repaso liviano. **Vie 20 Nov** — recuperatorio.

---

## Notas del método

- **Teoría primero:** antes de cada ejercicio, filmina o video y resumen con ejemplos; lo que falte en el resumen se agrega al resolver. Es lo que cambió entre el primer parcial y los parciales de PyE y Álgebra, y funcionó.
- **Clase en vivo:** las primeras 2 h de cada clase son teoría para anotar e interpretar; el tramo de práctico es para ejercicios (unos 3 cada 2 h).
- **Pista antes que solución:** si una demostración no sale, se vuelve a la definición y se pide una pista; no se copia.
- **Cierre con margen:** las 5 filminas terminan el Sáb 17 Oct y los 35 ejercicios el Vie 23 Oct; del Sáb 24 Oct al 12/11 quedan los slots como repaso, parciales viejos y filminas nuevas que salgan en clase. Es un ritmo exigente (1 filmina + medio práctico por día): si un día se pierde, se corre al siguiente slot en vez de compensarlo a la noche.
- **Después del 13/11:** del 14 al 19/11 se prepara el recuperatorio del 20/11, que es de la Unidad 1 (bloques de repaso al final del cronograma).
- **Corrida del 8/10 (noche):** Lógica no se tocaba el 8/10 igual. AyED2 pasa a febrero y los jueves 15, 22 y 29/10 son repaso de la Unidad 1 para el recuperatorio.
- (*) Los ejercicios de cierre se hacen solo si sobra tiempo.

---

## Archivo — Unidad 1 (estructuras de orden, primer parcial)

> Se conserva todo lo armado para el primer parcial (banco, cronogramas y notas) como historial y por si el recuperatorio es de esta unidad. Los encabezados quedaron un nivel más abajo.

### Prácticos de ejercicios

| # | Tema | Ejercicios |
|---|---|---|
| P1 | Relaciones | 7 |
| P2 | Posets | 6 (uno con parte * ) |
| P3 | Poset Reticulados | 13 (2 marcados con *) |
| P4 | Complementos, distributividad, álgebras de Boole, átomos e irreducibles | 8 |
| P5 | Teoremas de representación | 7 (1 marcado con *) |

**Total: 41 ejercicios** (37 "normales" + 4 ítems/partes marcados con * para cierre).

---

### Conceptos clave

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

### Banco de ejercicios y videos

#### Práctico 1 — Relaciones

| Ej | Descripción | Video |
|---|---|---|
| 1 | Determinar si la relación dada es de equivalencia sobre {1,...,5}; indicar clases | [Relaciones de equivalencia, clases y conjunto cociente](https://www.youtube.com/watch?v=8GxiX1xHJtk) |
| 2 | Determinar si las relaciones sobre Z son reflexivas, simétricas, antisimétricas o transitivas | [Relaciones de orden parcial 01 — Reflexiva, Antisimétrica, Transitiva](https://www.youtube.com/watch?v=FCIQb4MNrP4) |
| 3 | Usando el ej. 2, determinar si cada relación es de equivalencia y/o de orden | [Relaciones reflexivas, transitivas y simétricas — Ejercicios](https://www.youtube.com/watch?v=5L8oMg1roGE) |
| 4 | Probar que la relación {(x,y) | f(x)=f(y)} es de equivalencia; comparar con 2a | [Clases de equivalencia y conjunto cociente — Ejercicio](https://www.youtube.com/watch?v=bJFBxC5qcUA) |
| 5 | Orden parcial estricto → orden parcial (unión con igualdad); y a la inversa | [Relaciones — propiedades, ejemplos y contraejemplos](https://www.youtube.com/watch?v=-wxZsukZcac) |
| 6 | Listar pares de la relación de equivalencia definida por una partición dada; clases | [Relaciones de equivalencia — Ejercicios resueltos](https://www.youtube.com/watch?v=Yly68pfz2ac) |
| 7 | Relación "Fulano no es más viejo que Mengano": ejemplo donde no es orden parcial | [Relaciones propiedades 04 — reflexiva, simétrica, antisimétrica, transitiva](https://www.youtube.com/watch?v=MMUzadgFLvc) |

#### Práctico 2 — Posets

| Ej | Descripción | Video |
|---|---|---|
| 1 | Diagramas de Hasse A,B,C: maximales/minimales, máximo/mínimo, qué cubre a "e", cotas y supremos/ínfimos de conjuntos dados | [Diagrama de Hasse — cota superior, maximales, minimales, máximo, mínimo](https://www.youtube.com/watch?v=BCH9auS9yi8) |
| 2 (a,b) | V o F sobre posets: único maximal ⟹ máximo (finito / general) | [Objetos Maximales y Minimales — Conjuntos Ordenados](https://www.youtube.com/watch?v=RDxwk9Vjth4) |
| 3 | Dar diagramas de Hasse de P={a,b,c,d,e} que satisfagan condiciones sobre sup/ínf | [Estructuras de orden — Elementos maximales, máximo, minimales, mínimo](https://www.youtube.com/watch?v=5NRQPEKluTg) |
| 4 | Poset [0,1)∪[2,3) con orden heredado: V o F sobre existencia de supremos | [Poset de Z — Matemática Discreta](https://www.youtube.com/watch?v=6n6ZgStal4E) |
| 5 | Probar que sup(S) e ínf(S) existen para todo S finito no vacío en un poset reticulado | [Supremo e Ínfimo — Cotas y Conjuntos Ordenados](https://www.youtube.com/watch?v=L3rgqDYANYM) |
| 6 | Diagramas de Hasse de (A,\|) y (B,\|) con divisores de 12; ¿cuáles son reticulados?; calcular 4∧(2∨3); subconjunto de P({a,b,c}) | [Supremo e Ínfimo — Explicación con ejemplo](https://www.youtube.com/watch?v=SslId-CutLQ) |
| 2c* *(cierre)* | ¿Único maximal (sin ser finito) implica máximo? | [Ínfimo, supremo, mínimo y máximo de un conjunto](https://www.youtube.com/watch?v=RM11dDasmgg) |

#### Práctico 3 — Poset Reticulados

| Ej | Descripción | Video |
|---|---|---|
| 1 | En el reticulado L2: encontrar v∨x, s∨v y u∨v | [Video lección Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) *(general, no resuelve la cuenta exacta)* — pista: leer del diagrama las cotas superiores comunes de cada par |
| 2 | Demostrar x∨(y∧z) ≤ (x∨y)∧(x∨z) en todo poset reticulado | [Video lección Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) *(general)* — pista: x≤x∨y, y∧z≤y, monotonía |
| 3 (a,b,c) | Determinar si los mapeos f dados son isomorfismos de posets; qué falla si no | [Video lección Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) *(general, no resuelve la cuenta exacta)* — pista: chequear biyectividad + orden en ambos sentidos |
| 4 (a,b) | Determinar si se dan los isomorfismos indicados (D6 vs P({a,b}); D30 vs P({a,b,c})) | [Video lección Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) *(general, no resuelve la cuenta exacta)* — pista: f(d) = conjunto de primos que dividen a d |
| 5 | Probar que si f es isomorfismo de posets, f⁻¹ también lo es | [Video lección Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) *(general, no resuelve la cuenta exacta)* — pista: f⁻¹ ya es biyectiva; usar orden en ambos sentidos |
| 6 | Probar que si m es minimal en P, entonces f(m) es minimal en Q | [Video lección Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) *(general, no resuelve la cuenta exacta)* — pista: por el absurdo, usando sobreyectividad |
| 8 (a,b,c) | Función biyectiva que preserva orden entre L3 y L4 pero no es isomorfismo; no preserva sup/ínf | [Video lección Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) *(general, no resuelve la cuenta exacta)* — pista: preservar orden en un solo sentido no alcanza |
| 9 | Demostrar x∧(y∧z) = z∧(y∧x) en un reticulado | [Video lección Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) *(general, no resuelve la cuenta exacta)* — cubre asociatividad/conmutatividad de ∧ y ∨ |
| 10 | Probar que x∨y es cota superior de {x,y} (desde x≤y ⟺ x∨y=y) | [Video lección Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) *(general, no resuelve la cuenta exacta)* — pista: sale directo de la definición de supremo |
| 11 | Decidir cuáles de L1, L2, L3, L4 son complementados | [Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) |
| 13 | Para qué valores de n se tiene que Dn se incrusta en L3 | [Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) |
| 7* *(cierre)* | Cuántos isomorfismos hay de P({a,b,c}) en sí mismo | [Supremo e Ínfimo — Explicación con ejemplo](https://www.youtube.com/watch?v=SslId-CutLQ) |
| 12* *(cierre)* | Si sup(S) existe siempre para todo S⊆P, demostrar que ínf(S) también existe | [Supremo e Ínfimo — Cotas y Conjuntos Ordenados](https://www.youtube.com/watch?v=L3rgqDYANYM) |

#### Práctico 4 — Complementos, distributividad, álgebras de Boole, átomos e irreducibles

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

#### Práctico 5 — Teoremas de representación

| Ej | Descripción | Video |
|---|---|---|
| 1 | Probar que todo átomo es irreducible | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 2 (a,b) | Determinar si se cumplen las relaciones de isomorfismo (D2310 vs P(5 elem.); D90 vs P(4 elem.)) | [Video lección Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) *(general, no resuelve la cuenta exacta)* — pista: mismo criterio que P3 ej.4 |
| 3 | Probar que ∅ es decreciente; si D1 y D2 son decrecientes, D1∪D2 también lo es | [Video lección Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) *(general, no resuelve la cuenta exacta)* — pista: vacuamente cierto en ∅ |
| 4 (a,b,c) | Para cada reticulado: hallar At(L), dibujar Hasse de P(At(L)), determinar cuáles son álgebra de Boole | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 5 (a,b,c,d) | Hasse de irreducibles, Hasse de D(Irr(L)), definir el mapa F, usar Birkhoff para ver si es distributivo | [Teorema de Representación de Birkhoff — ILC FAMAF](https://www.youtube.com/watch?v=Kr-qM-TqlLs) |
| 7 (a,b) | Producto L×M de posets: si L,M son reticulados, L×M también; ídem distributividad | [Video lección Retículos y álgebras de Boole — parte 2](https://www.youtube.com/watch?v=cn5_iePGK9o) *(general)* — pista: construir sup/ínf componente a componente |
| 6* *(cierre)* | Dar todos los reticulados distributivos con exactamente 3 elementos irreducibles | [Retículos y álgebras de Boole — parte 1](https://www.youtube.com/watch?v=R9zzpsSIVig) |

---

### Reparto semanal de materias (4 materias)

| Día | Materia(s) |
|---|---|
| Lunes (día completo, sin clase) | PyE y **Lógica** |
| Martes (clase 9-13 PyE + 14-18 Álgebra) | **Lógica** *(antes SR/AED2, cambiado el 1/9 — parcial está cerca)* |
| Miércoles (clase 9-13 **Lógica**, práctico 2h) | Álgebra (tarde) — pero **2h de práctico de Lógica ya están en la cursada de la mañana** |
| Jueves (clase 9-13 PyE + 14-18 Álgebra) | **Repaso de recuperatorios** (Lógica U1) — AyED2 pasa a febrero |
| Viernes (clase 9-13 **Lógica**, práctico 2h) | Libre — pero **2h de práctico de Lógica dentro de la cursada de la mañana** |
| Sábado | **Lógica** y Álgebra (refuerzo) |
| Domingo | PyE y AED2 |

> Ritmo real de Lógica: Lunes ~4h (~6 ejercicios) · Sábado ~4h (~6 ejercicios, refuerzo) · Jueves ~2h (~3 ejercicios) · Miércoles y Viernes 2h de práctico dentro de la cursada (~3 ejercicios cada uno). Capacidad semanal: **21 ejercicios/semana** — la más alta de las 4 materias, porque Lógica cursa 2 días con práctico (Miércoles y Viernes) en vez de uno.

---

> **P1 y P2 completos y sólidos.** El domingo 6/9 fue de solo teoría (resumen), sin ejercicios — se reorganizó todo. **Esta semana (7-10/9), Álgebra y PyE quedan reducidas a la mañana (1.5h c/u) y Lógica se lleva el resto del día** — con las horas reales del calendario (Lun/Mar ~5.5h, Mié ~4.25h, Jue ~5h), los 25 ejercicios pendientes (P3: 10 + P4: 8 + P5: 7) cierran el jueves 10/9, dejando el temario completo un día antes del parcial (11/9).

### Notas del método

- **Corrida del 1/9:** el domingo 30 el sprint rindió menos de lo esperado (P2 ej. 1-3 nomás), y el lunes 31 se usó para la clase particular de Álgebra en vez de Lógica. Objetivo para el martes 1/9: terminar el Práctico 2 completo.
- **Sprint post-TP (26-28/8):** P1 confirmado completo, con 8/10 en el TP sorpresa del 26/8. El martes 25 no se avanzó nada de P2 (pese a estar planeado como "día especial"). Jueves 27 fue paro no docente (libre).
- **Corrida del 22/8 (gripe):** se perdieron Mié 19, Jue 20 y Vie 21 por gripe. El Sáb 22 se acortó a 3h (repartido con Álgebra) y el Mar 25 se convirtió en un día especial 100% Lógica (sin PyE ni Álgebra) para recuperar terreno.
- **Corrida anterior (17/8):** Sáb 15, Dom 16 y Lun 17 se perdieron por un imprevisto familiar.

- Como es matemática discreta/estructural (pruebas y diagramas, no cálculo numérico), varios videos son de teoría general del tema en vez de resolver exactamente el mismo enunciado — el objetivo es entender la técnica de demostración, no encontrar el ejercicio calcado.
- Encontré un video hecho específicamente para este curso de FaMAF sobre el Teorema de Birkhoff — lo reutilicé en varios ejercicios de átomos/irreducibles/representación porque es el más pertinente posible.
- Cuando lleguen las próximas 2 unidades, se agregan con el mismo formato (tabla banco + detalle inline).
- Ejercicios (*) resueltos al cierre de cada práctico, como pediste — quedan agrupados el Jue 27 y Vie 28 para repasar todo junto antes de las casi 2 semanas de margen hasta el parcial.