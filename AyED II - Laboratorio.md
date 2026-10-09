# Algoritmos y Estructuras de Datos II — Laboratorio (Lab 0 a Lab 6)

---

## Fechas clave

| Fecha | Evento |
|---|---|
| ~~Mié 2 Diciembre 2026~~ | ~~Llamado 1~~ — *ya no es meta* |
| ~~Mié 16 Diciembre 2026~~ | ~~Llamado 2~~ — *pasa a febrero* |
| **Febrero 2027** | **Nuevo objetivo** — llamado a confirmar (fechas de febrero todavía sin publicar acá) |

> No cursás la materia este cuatrimestre: la estudiás en paralelo; el final pasó de diciembre a febrero (decisión del 8/10). Este plan cubre el bloque de laboratorio (se programa y compila en C con los flags estrictos de la cátedra: `-Wall -Wextra -pedantic -std=c99`, y en varios labs también `-Werror`); el teórico-práctico está en su propio archivo y se estudia en la misma sesión.

---

## Estado actual (8 Octubre)

- **Decisión del 8/10: AyED2 pasa a febrero.** Tras las notas del primer parcial (Lógica, PyE y Álgebra reprobados), todo el tiempo hasta el 20/11 va a los segundos parciales y a los recuperatorios. El Llamado 1 (2/12) y el Llamado 2 (16/12) ya no son meta.
- **Nada resuelto de AyED2 todavía.** Los intentos de septiembre no se sostuvieron y el plan del 15/10 no llegó a arrancar. Los jueves y domingos que eran de AyED2 son ahora **bloques de repaso de recuperatorios** (ver los archivos de Lógica, Álgebra y PyE).
- Las sesiones del plan anterior (15/10 al 8/12) quedan **tachadas** en el cronograma y en el detalle como banco de referencia: los ejercicios y videos se vuelven a fechar cuando se arme el plan de febrero.
- **Plan de febrero: a definir el 20/11**, cuando se sepa cómo quedó el resto (después de los recuperatorios). Con diciembre y enero libres de parciales hay margen para un ritmo sostenible.

---

## Laboratorios

| # | Fecha original | Tema | Ejercicios |
|---|---|---|---|
| Lab 0 | 13/3 | Repaso de C: structs, un solo ciclo, matrices/booleanos | 3 |
| Lab 1 | 20/3 | Ordenación: fixstring, insertion sort, quick sort, partition, comparación, strings | 6 |
| Lab 2 | 3/4 | Divide y vencerás: k-ésimo elemento, cima (secuencial y binaria), comparación | 4 |
| Lab 3 | 10/4 | Tipos de datos: arreglos multidimensionales y structs (datos climáticos) | 1 (2 partes grandes) |
| Lab 4 | 8/5 | Punteros y memoria dinámica: punteros 101, params `out`, `malloc`/`free`, cadenas | 4 |
| Lab 5 (Parte 1) | 22/5 | TADs: Par, Contador, Lista (con encapsulamiento en C) | 3 |
| Lab 6 | 5/6 | Programación dinámica en C: moneda, mochila, panadería, fábrica de autos | 4 (el ítem c de panadería está eliminado por la cátedra) |

**Total: 25 ejercicios** (con sub-partes) en los mismos 16 domingos que el teórico-práctico.

---

## Conceptos clave

- [ ] Compilación con flags estrictos, guía de estilo, prohibido `break`/`continue`/`goto`/`return` a mitad de función
- [ ] `struct`, arreglos multidimensionales, `enum` en C
- [ ] Ordenación en C: insertion sort, quick sort (`partition` top-down y con partición propia), comparación empírica de algoritmos
- [ ] Divide y vencerás: k-ésimo elemento (quickselect), búsqueda de "cima" secuencial vs. binaria
- [ ] Redirección de `stdout`, lectura robusta de archivos con `fscanf`
- [ ] Punteros: referenciación (`&`), desreferenciación (`*`), simular parámetros `out`/`in-out`
- [ ] Memoria dinámica: `malloc`, `free`, Stack vs. Heap, `sizeof`, padding de structs, memory leaks (`valgrind`)
- [ ] Cadenas en C: arreglos de `char`, terminador `'\0'`, manejo sin `string.h`
- [ ] TADs en C: encapsulamiento con tipos opacos, separación spec/implementación, constructores/destructores/operaciones
- [ ] Programación dinámica en C: tablas, `print_table()` para debugging, testing con casos base y borde

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

> AyED2 está en pausa hasta febrero: sus jueves y domingos son ahora bloques de repaso de recuperatorios (jueves: Lógica U1; domingos: Álgebra).

---

## Cronograma día por día

> Las sesiones anteriores al 15/10 quedan como historial del plan anterior (6/9 al 12/10): figuraban planificadas pero no se llegaron a estudiar, AyED2 seguía en cero. Desde el 15/10 sigue el plan nuevo.

| Fecha | Día | Contenido |
|---|---|---|
| ~~Dom 16 Ago~~ | ~~**PERDIDO**~~ (familia de visita) |
| ~~Dom 23 Ago~~ | ~~**PERDIDO**~~ (semana de gripe) |
| ~~Dom 30 Ago~~ | ~~**PERDIDO**~~ (semana del sprint) |
| ~~Mar 1 Sep~~ | ~~**PERDIDO**~~ (fusionado, ver corrida anterior) |
| ~~Jue 3 Sep~~ | ~~**PERDIDO**~~ (no se estudió nada) |
| Dom 6 Sep | Lab0 |
| Jue 10 Sep | Lab0 (cierra) |
| Dom 13 Sep | Lab1 |
| Jue 17 Sep | Lab1 |
| Dom 20 Sep | Lab1 |
| Jue 24 Sep | Lab1 |
| Dom 27 Sep | Lab1 (cierra) |
| Jue 1 Oct | Lab2 |
| Dom 4 Oct | Lab2 |
| Jue 8 Oct | Lab2 |
| Dom 11 Oct | Lab2 |
| **— Desde acá: plan nuevo (corrida del 5/10) —** | | |
| Jue 15 Oct | Jue | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 0 · ej. 1, 2~~ *(pasa a febrero)* · otras: Álgebra, PyE · lugar cedido al repaso de recuperatorios (Lógica) |
| Vie 16 Oct | Vie | otras: Lógica |
| Sáb 17 Oct | Sáb | otras: Lógica, Álgebra, PyE |
| Dom 18 Oct | Dom | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 0 (cierra) · ej. 3a, 3b~~ *(pasa a febrero)* · otras: PyE · lugar cedido al repaso de recuperatorios (Álgebra) |
| Lun 19 Oct | Lun | otras: Lógica, Álgebra, PyE |
| Mar 20 Oct | Mar | otras: Lógica, Álgebra, PyE |
| Mié 21 Oct | Mié | otras: Lógica, Álgebra |
| Jue 22 Oct | Jue | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 1 · ej. 0, 1A~~ *(pasa a febrero)* · otras: Álgebra, PyE · lugar cedido al repaso de recuperatorios (Lógica) |
| Vie 23 Oct | Vie | otras: Lógica |
| Sáb 24 Oct | Sáb | otras: Lógica, Álgebra, PyE |
| Dom 25 Oct | Dom | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 1 · ej. 1B, 1C~~ *(pasa a febrero)* · otras: PyE · lugar cedido al repaso de recuperatorios (Álgebra) |
| Lun 26 Oct | Lun | otras: Lógica, Álgebra, PyE |
| Mar 27 Oct | Mar | otras: Lógica, Álgebra, PyE |
| Mié 28 Oct | Mié | otras: Lógica, Álgebra |
| Jue 29 Oct | Jue | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 1 · ej. 2A, 2B~~ *(pasa a febrero)* · otras: Álgebra, PyE · lugar cedido al repaso de recuperatorios (Lógica) |
| Vie 30 Oct | Vie | otras: Lógica |
| Sáb 31 Oct | Sáb | otras: Lógica, Álgebra, PyE |
| Dom 1 Nov | Dom | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 1 · ej. 3, 4~~ *(pasa a febrero)* · otras: PyE |
| Lun 2 Nov | Lun | otras: Lógica, Álgebra, PyE |
| Mar 3 Nov | Mar | **PARCIAL 2 de PyE** · otras: Lógica, Álgebra |
| Mié 4 Nov | Mié | otras: Lógica, Álgebra |
| Jue 5 Nov | Jue | **PARCIAL 2 de Álgebra** · ~~**AyED2 laboratorio** (~2.5h en total) — Lab 1 (cierra) · ej. 5a, 5b~~ *(pasa a febrero)* |
| Vie 6 Nov | Vie | otras: Lógica |
| Sáb 7 Nov | Sáb | otras: Lógica, Álgebra |
| Dom 8 Nov | Dom | ~~**AyED2 laboratorio** (~2.5h en total) — Lab 2 · ej. 1A, 1B~~ *(pasa a febrero)* · lugar cedido al repaso de recuperatorios (Álgebra) |
| Lun 9 Nov | Lun | AyED2 en pausa por los parciales · otras: Lógica, Álgebra |
| Mar 10 Nov | Mar | AyED2 en pausa por los parciales · otras: Lógica |
| Mié 11 Nov | Mié | AyED2 en pausa por los parciales · otras: Lógica |
| Jue 12 Nov | Jue | AyED2 en pausa por los parciales |
| Vie 13 Nov | Vie | **PARCIAL 2 de Lógica** · AyED2 en pausa por los parciales |
| Sáb 14 Nov | Sáb | AyED2 en pausa por los parciales |
| Dom 15 Nov | Dom | AyED2 en pausa por los parciales |
| Lun 16 Nov | Lun | AyED2 en pausa por los parciales |
| Mar 17 Nov | Mar | AyED2 en pausa por los parciales |
| Mié 18 Nov | Mié | AyED2 en pausa por los parciales |
| Jue 19 Nov | Jue | Recuperatorios de Álgebra · AyED2 en pausa por los parciales |
| Vie 20 Nov | Vie | **Tercer parcial y recuperatorio de Lógica** · AyED2 en pausa por los parciales |
| Sáb 21 Nov | Sáb | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 2 · ej. 1C, 1D, 2A~~ *(pasa a febrero)* |
| Dom 22 Nov | Dom | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 2 · ej. 2B, 2C, 2D~~ *(pasa a febrero)* |
| Lun 23 Nov | Lun | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 2 · ej. 3A, 3B, 3C~~ *(pasa a febrero)* |
| Mar 24 Nov | Mar | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 2 (cierra) · Lab 3 · ej. 3D, 4, Parte A~~ *(pasa a febrero)* |
| Mié 25 Nov | Mié | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 3 (cierra) · Lab 4 · ej. Parte B, 1, 2a~~ *(pasa a febrero)* |
| Jue 26 Nov | Jue | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 4 · ej. 2b, 2c, 2d~~ *(pasa a febrero)* |
| Vie 27 Nov | Vie | Libre — sin materia |
| Sáb 28 Nov | Sáb | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 4 · ej. 3a, 3b, 4a~~ *(pasa a febrero)* |
| Dom 29 Nov | Dom | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 4 (cierra) · ej. 4b, 4c, 4d~~ *(pasa a febrero)* |
| Lun 30 Nov | Lun | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 5 · ej. Lab 5 Ej 1a-c, 1d, 1e~~ *(pasa a febrero)* |
| Mar 1 Dic | Mar | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 5 · ej. 2a, 2b, 3a~~ *(pasa a febrero)* |
| Mié 2 Dic | Mié | ~~AyED2 Llamado 1 (no se rinde)~~ *(pasa a febrero)* |
| Jue 3 Dic | Jue | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 5 (cierra) · Lab 6 · ej. 3b, 3c, Lab 6 Ej 1a-c~~ *(pasa a febrero)* |
| Vie 4 Dic | Vie | Libre — sin materia |
| Sáb 5 Dic | Sáb | ~~**AyED2 laboratorio** (~3.5h en total) — Lab 6 (cierra) · ej. 2, 3a, b, 4a, b~~ *(pasa a febrero)* |
| Dom 6 Dic | Dom | **AyED2** — solo teórico / repaso del laboratorio |
| Lun 7 Dic | Lun | **AyED2** — solo teórico / repaso del laboratorio |
| Mar 8 Dic | Mar | **AyED2** — solo teórico / repaso del laboratorio |
| Mié 9 Dic | Mié | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Jue 10 Dic | Jue | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Vie 11 Dic | Vie | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Sáb 12 Dic | Sáb | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Dom 13 Dic | Dom | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Lun 14 Dic | Lun | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Mar 15 Dic | Mar | ~~**AyED2** — repaso general, SR y simulacros antes del Llamado 2~~ *(pasa a febrero)* |
| Mié 16 Dic | Mié | ~~**AyED2 Llamado 2**~~ *(pasa a febrero)* |

---

## Detalle día por día

**Dom 6 Sep** *(2 sub-ítems)* — Lab0
* *Lab 0, Ej 1* — `check_bound()`: cota superior/inferior + búsqueda en un único ciclo, usando `struct bound_data` — 🎥 "Programación en C: STRUCTS y vectores de STRUCTS" — https://www.youtube.com/watch?v=kdKHZsxdHz4
* *Lab 0, Ej 2* — Leer y entender el tictactoe incompleto: implementar `has_free_cell()` y `get_winner()` — 🎥 "Arreglos bidimensionales C# — Colecciones y Arreglos" — https://www.youtube.com/watch?v=dXchlGBS0FQ

**Jue 10 Sep** *(2 sub-ítems)* — Lab0 (cierra)
* *Lab 0, Ej 3a* — Tictactoe generalizado a tablero 4x4 (4 en línea para ganar) — 🎥 "C #20 — Arreglo Bidimensional" — https://www.youtube.com/watch?v=dei49_2PltI
* *Lab 0, Ej 3b* — Extender a tablero 5x5 cambiando el mínimo de código posible — (mismo video que 3a, es una generalización directa)

**Dom 13 Sep** *(2 sub-ítems)* — Lab1
* *Lab 1, Ej 0* — Tipo `fixstring` con `typedef`: `fstring_length`, `fstring_eq`, `fstring_less_eq`, sin usar `string.h` — 🎥 "Programación en C: STRINGS | Como almacenar cadenas de caracteres" — https://www.youtube.com/watch?v=pJHNYeAKogA
* *Lab 1, Ej 1A* — Completar `insert()` para insertion sort usando `goes_before()` — 🎥 "Paso a paso a través de la función de ordenamiento por inserción" — https://www.youtube.com/watch?v=jRa1HqG9YaI

**Jue 17 Sep** *(2 sub-ítems)* — Lab1
* *Lab 1, Ej 1B* — Imprimir el arreglo en cada paso con `array_dump()`, verificar contra el teórico
* *Lab 1, Ej 1C* — Agregar chequeo de invariante del `for` con `assert()` y `array_is_sorted()`

**Dom 20 Sep** *(2 sub-ítems)* — Lab1
* *Ej 2A* — Implementar `quick_sort_rec()` (top-down), usando `partition()` ya provisto — 🎥 "Quick Sort — algoritmo de ordenamiento explicado al detalle" — https://www.youtube.com/watch?v=YzHDIvxOQcI
* *Ej 2B* — Completar `main()` llamando a `quick_sort()`

**Jue 24 Sep** *(2 sub-ítems)* — Lab1
* *Ej 3* — Implementar `partition()` desde cero (sin la versión precompilada) — 🎥 "Improving Quicksort with Median of 3 and Cutoffs" — https://www.youtube.com/watch?v=1Vl2TB7DoAM
* *Ej 4* — Comparar selection/insertion/quick sort: tiempo, comparaciones e intercambios — 🎥 "¿Cómo funciona la notación asintótica?" — https://www.youtube.com/watch?v=HcDV5MGGrRE

**Dom 27 Sep** *(2 sub-ítems)* — Lab1 (cierra)
* *Ej 5a* — Ordenar un arreglo de `fixstring` alfabéticamente con quick sort — 🎥 "Manejo de Cadenas en C: Funciones de string.h" — https://www.youtube.com/watch?v=PxiCY5EQdTQ
* *Ej 5b* — Ordenar el mismo arreglo por longitud de las cadenas

**Jue 1 Oct** *(2 sub-ítems)* — Lab2
* *Ej 1A* — Resolver el k-ésimo elemento (ejercicio 5 del práctico 1.2) — 🎥 "Quick Select" — https://www.youtube.com/watch?v=aOhyCdxGJvY
* *Ej 1B* — Implementar `k_esimo()` en C, adaptado a índices desde 0

**Dom 4 Oct** *(2 sub-ítems)* — Lab2
* *Ej 1C* — Imprimir pasos intermedios y verificar contra el video de la cátedra
* *Ej 1D* — Testing: al menos 10 casos de test (arreglo de 1 elemento, ordenados/desordenados, todos los k)

**Jue 8 Oct** *(2 sub-ítems)* — Lab2
* *Ej 2A* — Resolver "tiene cima" y "cima" con búsqueda secuencial (ejercicios 2a, 2b del práctico 1.3) — 🎥 "Estructura de Datos — Método Búsqueda Binaria" — https://www.youtube.com/watch?v=u3J-fe4UFsA
* *Ej 2B* — Implementar `tiene_cima()` y `cima()` en `cima.c`, adaptado a índices desde 0

**Dom 11 Oct** *(2 sub-ítems)* — Lab2
* *Ej 2C* — Imprimir pasos intermedios y verificar contra el video de la cátedra
* *Ej 2D* — Testing: al menos 10 casos de test para cada función

> **Desde acá: plan nuevo (corrida del 5/10).** Todo lo de arriba es historial, tal cual estaba.

> **Corrida del 8/10: todo lo de abajo (15/10 al 8/12) pasa a febrero.** Se conserva como banco de referencia; los ejercicios y videos se vuelven a fechar cuando se arme el plan de febrero.

**Jue 15 Oct** *(~2.5h en total)* — Lab 0 · ej. 1, 2
* *Lab 0, Ej 1* — `check_bound()`: cota superior/inferior + búsqueda en un único ciclo, usando `struct bound_data` — 🎥 "Programación en C: STRUCTS y vectores de STRUCTS" — https://www.youtube.com/watch?v=kdKHZsxdHz4
* *Lab 0, Ej 2* — Leer y entender el tictactoe incompleto: implementar `has_free_cell()` y `get_winner()` — 🎥 "Arreglos bidimensionales C# — Colecciones y Arreglos" — https://www.youtube.com/watch?v=dXchlGBS0FQ

**Dom 18 Oct** *(~2.5h en total)* — Lab 0 (cierra) · ej. 3a, 3b
* *Lab 0, Ej 3a* — Tictactoe generalizado a tablero 4x4 (4 en línea para ganar) — 🎥 "C #20 — Arreglo Bidimensional" — https://www.youtube.com/watch?v=dei49_2PltI
* *Lab 0, Ej 3b* — Extender a tablero 5x5 cambiando el mínimo de código posible — (mismo video que 3a, es una generalización directa)

**Jue 22 Oct** *(~2.5h en total)* — Lab 1 · ej. 0, 1A
* *Lab 1, Ej 0* — Tipo `fixstring` con `typedef`: `fstring_length`, `fstring_eq`, `fstring_less_eq`, sin usar `string.h` — 🎥 "Programación en C: STRINGS | Como almacenar cadenas de caracteres" — https://www.youtube.com/watch?v=pJHNYeAKogA
* *Lab 1, Ej 1A* — Completar `insert()` para insertion sort usando `goes_before()` — 🎥 "Paso a paso a través de la función de ordenamiento por inserción" — https://www.youtube.com/watch?v=jRa1HqG9YaI

**Dom 25 Oct** *(~2.5h en total)* — Lab 1 · ej. 1B, 1C
* *Lab 1, Ej 1B* — Imprimir el arreglo en cada paso con `array_dump()`, verificar contra el teórico
* *Lab 1, Ej 1C* — Agregar chequeo de invariante del `for` con `assert()` y `array_is_sorted()`

**Jue 29 Oct** *(~2.5h en total)* — Lab 1 · ej. 2A, 2B
* *Ej 2A* — Implementar `quick_sort_rec()` (top-down), usando `partition()` ya provisto — 🎥 "Quick Sort — algoritmo de ordenamiento explicado al detalle" — https://www.youtube.com/watch?v=YzHDIvxOQcI
* *Ej 2B* — Completar `main()` llamando a `quick_sort()`

**Dom 1 Nov** *(~2.5h en total)* — Lab 1 · ej. 3, 4
* *Ej 3* — Implementar `partition()` desde cero (sin la versión precompilada) — 🎥 "Improving Quicksort with Median of 3 and Cutoffs" — https://www.youtube.com/watch?v=1Vl2TB7DoAM
* *Ej 4* — Comparar selection/insertion/quick sort: tiempo, comparaciones e intercambios — 🎥 "¿Cómo funciona la notación asintótica?" — https://www.youtube.com/watch?v=HcDV5MGGrRE

**Jue 5 Nov** *(~2.5h en total)* — Lab 1 (cierra) · ej. 5a, 5b
* *Ej 5a* — Ordenar un arreglo de `fixstring` alfabéticamente con quick sort — 🎥 "Manejo de Cadenas en C: Funciones de string.h" — https://www.youtube.com/watch?v=PxiCY5EQdTQ
* *Ej 5b* — Ordenar el mismo arreglo por longitud de las cadenas

**Dom 8 Nov** *(~2.5h en total)* — Lab 2 · ej. 1A, 1B
* *Ej 1A* — Resolver el k-ésimo elemento (ejercicio 5 del práctico 1.2) — 🎥 "Quick Select" — https://www.youtube.com/watch?v=aOhyCdxGJvY
* *Ej 1B* — Implementar `k_esimo()` en C, adaptado a índices desde 0

**Sáb 21 Nov** *(~3.5h en total)* — Lab 2 · ej. 1C, 1D, 2A
* *Ej 1C* — Imprimir pasos intermedios y verificar contra el video de la cátedra
* *Ej 1D* — Testing: al menos 10 casos de test (arreglo de 1 elemento, ordenados/desordenados, todos los k)
* *Ej 2A* — Resolver "tiene cima" y "cima" con búsqueda secuencial (ejercicios 2a, 2b del práctico 1.3) — 🎥 "Estructura de Datos — Método Búsqueda Binaria" — https://www.youtube.com/watch?v=u3J-fe4UFsA

**Dom 22 Nov** *(~3.5h en total)* — Lab 2 · ej. 2B, 2C, 2D
* *Ej 2B* — Implementar `tiene_cima()` y `cima()` en `cima.c`, adaptado a índices desde 0
* *Ej 2C* — Imprimir pasos intermedios y verificar contra el video de la cátedra
* *Ej 2D* — Testing: al menos 10 casos de test para cada función

**Lun 23 Nov** *(~3.5h en total)* — Lab 2 · ej. 3A, 3B, 3C
* *Ej 3A* — Resolver "cima" con búsqueda binaria (ejercicio 2c del práctico 1.3) — 🎥 "Aprende Divide y Vencerás — Elemento mínimo y máximo de un vector" — https://www.youtube.com/watch?v=0lZmuVkRT44
* *Ej 3B* — Implementar `cima_log()`, adaptado a índices desde 0
* *Ej 3C* — Imprimir pasos intermedios y verificar contra el video de la cátedra

**Mar 24 Nov** *(~3.5h en total)* — Lab 2 (cierra) · Lab 3 · ej. 3D, 4, Parte A
* *Ej 3D* — Testing: al menos 10 casos de test
* *Ej 4* — Comparar complejidad y tiempos de `cima()` vs `cima_log()`, graficar en Sheets — 🎥 "Complejidad algoritmos recursivos" — https://www.youtube.com/watch?v=qNDaGZNI6s8
* *Parte A* — Completar la carga de datos climáticos de Córdoba en `weather_table.c`/`weather.c` (robusto ante entradas mal formateadas) — 🎥 "Programación en C: STRUCTS y vectores de STRUCTS" — https://www.youtube.com/watch?v=kdKHZsxdHz4

**Mié 25 Nov** *(~3.5h en total)* — Lab 3 (cierra) · Lab 4 · ej. Parte B, 1, 2a
* *Parte B* — Librería `weather_utils`: menor temperatura mínima histórica, mayor temperatura máxima por año, mes de mayor lluvia por año — verificar contra la tabla de resultados esperados
* *Ej 1* — Punteros 101: completar `main.c` usando `&` y `*`, sin reasignar `x`, `m`, `a` directamente — 🎥 "Punteros y Paso por Referencia" — https://www.youtube.com/watch?v=jxHeXMPcD_c
* *Ej 2a* — Traducir `absolute()` a C con prototipo `void absolute(int x, int y)` — comparar resultado con el lenguaje del teórico

**Jue 26 Nov** *(~3.5h en total)* — Lab 4 · ej. 2b, 2c, 2d
* *Ej 2b* — Traducir con prototipo `void absolute(int x, int *y)` (puntero de salida real)
* *Ej 2c* — Responder: ¿`int *y` es parámetro `in`, `out` o `in/out`? ¿Qué tipos de parámetros tiene disponibles C?
* *Ej 2d* — Implementar `swap()` con parámetros `in/out` usando punteros

**Sáb 28 Nov** *(~3.5h en total)* — Lab 4 · ej. 3a, 3b, 4a
* *Ej 3a* — Tamaño en bytes de cada campo de `data_t` + tamaño total (padding) — 🎥 "Fundamentos de C: uso de malloc y free (reservar y liberar memoria)" — https://www.youtube.com/watch?v=MtRV51dCwCc
* *Ej 3b* — `data_t` en memoria dinámica con `malloc`/`free`, incluyendo `array_from_file()` con punteros
* *Ej 4a* — Librería `strfuncs`: `string_length`, `string_filter`, `string_is_symmetric` — 🎥 "Manejo de Cadenas en C: Funciones de string.h" — https://www.youtube.com/watch?v=PxiCY5EQdTQ

**Dom 29 Nov** *(~3.5h en total)* — Lab 4 (cierra) · ej. 4b, 4c, 4d
* *Ej 4b* — Detectar y corregir problemas de `scanf()` en `checkpal.c`, reemplazar por `fgets()`
* *Ej 4c* — Encontrar el bug de `string_clone()` con `valgrind --track-origins=yes` y `gdb`, corregirlo y eliminar memory leaks — 🎥 "Memoria dinámica en C (malloc, free, memory leaks)" — https://www.youtube.com/watch?v=NxE2O-NLOus
* *Ej 4d* — Completar `string_clone()` usando `<string.h>` (sin `strdup()`)

**Lun 30 Nov** *(~3.5h en total)* — Lab 5 · ej. Lab 5 Ej 1a-c, 1d, 1e
* *Lab 5 Ej 1a-c* — TAD Par: implementar con tupla, con arreglo, analizar si logra encapsulamiento — 🎥 "¿Qué es un TAD? Tipos Abstractos de Datos explicados en 5 min" — https://www.youtube.com/watch?v=PIWAKf26NCk
* *Ej 1d* — TAD Par con puntero, agregar manejo de memoria dinámica (constructor/destructor)
* *Ej 1e* — TAD Par polimórfico (`Pair of A`), adaptar la implementación anterior a la nueva interfaz

**Mar 1 Dic** *(~3.5h en total)* — Lab 5 · ej. 2a, 2b, 3a
* *Ej 2a* — Implementar TAD Contador cumpliendo la especificación (con `assert()` en las precondiciones) — 🎥 "Tipo de Datos Abstractos — Qué es y tutorial" — https://www.youtube.com/watch?v=UJltNyYpMuM
* *Ej 2b* — Usar el TAD Contador para chequear paréntesis balanceados
* *Ej 3a* — Especificar el TAD Lista en `list.h` (constructores, operaciones, `typedef list_elem`) — 🎥 "Fundamentos de programación. Tipos Abstractos de Datos (TAD)" — https://www.youtube.com/watch?v=Kd8Tna-5e-Y

**Jue 3 Dic** *(~3.5h en total)* — Lab 5 (cierra) · Lab 6 · ej. 3b, 3c, Lab 6 Ej 1a-c
* *Ej 3b* — Implementar `list.c` con punteros (listas enlazadas), garantizando encapsulamiento
* *Ej 3c* — Completar `array_to_list()` y `average()` en `main.c`
* *Lab 6 Ej 1a-c* — `change()` con programación dinámica para el problema de la moneda + tests + `print_table()` — 🎥 "Cambio con monedas — Programación Dinámica C#" — https://www.youtube.com/watch?v=w69MsdS2oK8

**Sáb 5 Dic** *(~3.5h en total)* — Lab 6 (cierra) · ej. 2, 3a, b, 4a, b
* *Ej 2* — `knapsack()` con programación dinámica para el problema de la mochila + tests + `print_table()` — 🎥 "Programación Dinámica: Método Mochila — Ejemplo 1 Paso a Paso" — https://www.youtube.com/watch?v=QFjeujVWufE
* *Ej 3a, b* — Problema de la panadería con programación dinámica + tests (**el ítem c está eliminado por la cátedra — no hacer**) — 🎥 "Cambio de Monedas | Programación Dinámica" — https://www.youtube.com/watch?v=vdDBU3BJNPE
* *Ej 4a, b* — Problema de la fábrica de automóviles (dos líneas de ensamblaje) con programación dinámica + tests — 🎥 "Programación Dinámica: Devolución de Cambio de Monedas" — https://www.youtube.com/watch?v=Sf4OKx1Wz9w

---

## Notas del método

- **Corrida del 8/10 (noche):** AyED2 se pasa a febrero tras las notas del primer parcial. El plan 15/10–8/12 queda como banco de referencia (tachado en el cronograma). Los jueves y domingos de AyED2 son repaso de recuperatorios hasta el 20/11; el plan de febrero se arma después.
- **Corrida del 5/10:** AyED2 se retoma el jueves 15/10 tras la pausa por los parciales. El ritmo vuelve a ser liviano (2 + 2 por sesión) en la fase 1, y la fase 2 es una propuesta que se confirma el 20/11.
- **Objetivo:** Llamado 2 (16/12); el Llamado 1 ya no es meta.
- El único ítem eliminado por la cátedra es el (c) del Ejercicio 3 del Lab 6 (panadería con backtracking): no se implementa.
- Varios videos son de la técnica general y no del enunciado exacto: el objetivo es entender el mecanismo.
- Cuando llegue la Parte 2 del Lab 5 (si existe), se agrega con el mismo formato.

### Historial de corridas anteriores

- **Corrida del 6/9 — segundo bajón de ritmo:** el jueves 3/9 tampoco se estudió nada. Se bajó el ritmo a **2 sub-ítems/sesión** (antes ~4) y el laboratorio se sumó al Jueves también (fusionado con el teórico-práctico ese día) — solo Domingo a este ritmo hubiera tardado ~6 meses. El temario cierra el 3/12.
- **Corrida del 1/9:** tras varios corrimientos fallidos (16/8, 23/8, 30/8, 1/9), se había bajado a ~4 sub-ítems/domingo — no llegó a sostenerse ni una semana.
- El único ítem explícitamente eliminado por la cátedra es el (c) del Ejercicio 3 del Lab 6 (panadería con backtracking) — no se implementa.
- Varios videos son sobre el concepto general en C (o incluso en otro lenguaje) en vez de la consigna exacta — el objetivo es entender el mecanismo (punteros, malloc, TADs, DP) antes de programarlo en el lenguaje específico de la cátedra.
- El temario ya no apunta al Llamado 1 como objetivo — apunta al Llamado 2, con margen real de por medio.
- Cuando consigas la Parte 2 del Lab 5 (si existe), se agrega con el mismo formato.