# Algoritmos y Estructuras de Datos II — Laboratorio (Lab 0 a Lab 6)

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Mié 2 Diciembre 2026 | **Llamado 1** |
| Mié 16 Diciembre 2026 | Llamado 2 |

> Mismo domingo que el teórico-práctico, otro bloque de 2h (el domingo tiene 4h totales: 2h laboratorio + 2h teórico-práctico). A diferencia del teórico-práctico (papel/pizarra), acá se programa y compila en C de verdad, con los flags estrictos de la cátedra (`-Wall -Wextra -pedantic -std=c99`, y en varios labs también `-Werror`).

---

## Estado actual (6 Septiembre)

- Nada resuelto todavía. El jueves 3/9 tampoco se estudió nada — se decidió bajar el ritmo a **2 sub-ítems/sesión** (antes ~4) y sumarle el Jueves (fusionado con el teórico-práctico ese día), ya que solo Domingo a 2/sesión hubiera tardado ~6 meses. Arranca el domingo 6/9.
- Laboratorios disponibles: **Lab 0** (repaso C), **Lab 1** (ordenación), **Lab 2** (divide y vencerás), **Lab 3** (tipos de datos), **Lab 4** (punteros y memoria dinámica), **Lab 5 Parte 1** (TADs — puede faltar la Parte 2), **Lab 6** (programación dinámica).
- Los ejercicios que ya vienen con solución provista por la cátedra (como el ítem eliminado del Lab 6) se saltean — solo se repasa la solución en vez de resolverla de cero.

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

## Reparto semanal (comparte Domingo y Jueves con el teórico-práctico)

| Bloque | Contenido |
|---|---|
| Domingo y Jueves, 2 sub-ítems c/u | Este plan (Lab 0 a Lab 6) |
| Domingo y Jueves, 2 ejercicios c/u | Ver `AyED_-_Teorico_Practico.md` |

> Tras fallar el jueves 3/9, el laboratorio se sumó también al Jueves (antes solo Domingo) y bajó el ritmo a 2 sub-ítems/sesión. El temario cierra el 3/12, un día después del Llamado 1 pero con margen antes del Llamado 2.

---

## Cronograma día por día

| Fecha | Contenido |
|---|---|
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
| Jue 15 Oct | Lab2 |
| Dom 18 Oct | Lab2 |
| Jue 22 Oct | Lab2 (cierra) · Lab3 |
| Dom 25 Oct | Lab3 (cierra) · Lab4 |
| Jue 29 Oct | Lab4 |
| Dom 1 Nov | Lab4 |
| Jue 5 Nov | Lab4 |
| Dom 8 Nov | Lab4 |
| Jue 12 Nov | Lab4 (cierra) |
| Dom 15 Nov | Lab5 |
| Jue 19 Nov | Lab5 |
| Dom 22 Nov | Lab5 |
| Jue 26 Nov | Lab5 (cierra) |
| Dom 29 Nov | Lab6 |
| Jue 3 Dic | Lab6 (cierra) |
| **Mié 2 Dic** | **LLAMADO 1** (temario ya completo desde el 3/12... en realidad desde antes, ver nota) |
| **Mié 16 Dic** | **LLAMADO 2** |

> **Reorganización del 3/9 — ritmo bajado y Jueves sumado:** tras fallar el jueves 3/9, se decidió empezar despacio: **2 sub-ítems/sesión**, ahora en Domingo **y Jueves** (antes solo Domingo, lo que hubiera tardado ~6 meses). El temario completo (52 sub-ítems) cierra el **3 de diciembre**, un día después del Llamado 1 pero con margen cómodo antes del Llamado 2.

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

**Jue 15 Oct** *(2 sub-ítems)* — Lab2
* *Ej 3A* — Resolver "cima" con búsqueda binaria (ejercicio 2c del práctico 1.3) — 🎥 "Aprende Divide y Vencerás — Elemento mínimo y máximo de un vector" — https://www.youtube.com/watch?v=0lZmuVkRT44
* *Ej 3B* — Implementar `cima_log()`, adaptado a índices desde 0

**Dom 18 Oct** *(2 sub-ítems)* — Lab2
* *Ej 3C* — Imprimir pasos intermedios y verificar contra el video de la cátedra
* *Ej 3D* — Testing: al menos 10 casos de test

**Jue 22 Oct** *(2 sub-ítems)* — Lab2 (cierra) · Lab3
* *Ej 4* — Comparar complejidad y tiempos de `cima()` vs `cima_log()`, graficar en Sheets — 🎥 "Complejidad algoritmos recursivos" — https://www.youtube.com/watch?v=qNDaGZNI6s8
* *Parte A* — Completar la carga de datos climáticos de Córdoba en `weather_table.c`/`weather.c` (robusto ante entradas mal formateadas) — 🎥 "Programación en C: STRUCTS y vectores de STRUCTS" — https://www.youtube.com/watch?v=kdKHZsxdHz4

**Dom 25 Oct** *(2 sub-ítems)* — Lab3 (cierra) · Lab4
* *Parte B* — Librería `weather_utils`: menor temperatura mínima histórica, mayor temperatura máxima por año, mes de mayor lluvia por año — verificar contra la tabla de resultados esperados
* *Ej 1* — Punteros 101: completar `main.c` usando `&` y `*`, sin reasignar `x`, `m`, `a` directamente — 🎥 "Punteros y Paso por Referencia" — https://www.youtube.com/watch?v=jxHeXMPcD_c

**Jue 29 Oct** *(2 sub-ítems)* — Lab4
* *Ej 2a* — Traducir `absolute()` a C con prototipo `void absolute(int x, int y)` — comparar resultado con el lenguaje del teórico
* *Ej 2b* — Traducir con prototipo `void absolute(int x, int *y)` (puntero de salida real)

**Dom 1 Nov** *(2 sub-ítems)* — Lab4
* *Ej 2c* — Responder: ¿`int *y` es parámetro `in`, `out` o `in/out`? ¿Qué tipos de parámetros tiene disponibles C?
* *Ej 2d* — Implementar `swap()` con parámetros `in/out` usando punteros

**Jue 5 Nov** *(2 sub-ítems)* — Lab4
* *Ej 3a* — Tamaño en bytes de cada campo de `data_t` + tamaño total (padding) — 🎥 "Fundamentos de C: uso de malloc y free (reservar y liberar memoria)" — https://www.youtube.com/watch?v=MtRV51dCwCc
* *Ej 3b* — `data_t` en memoria dinámica con `malloc`/`free`, incluyendo `array_from_file()` con punteros

**Dom 8 Nov** *(2 sub-ítems)* — Lab4
* *Ej 4a* — Librería `strfuncs`: `string_length`, `string_filter`, `string_is_symmetric` — 🎥 "Manejo de Cadenas en C: Funciones de string.h" — https://www.youtube.com/watch?v=PxiCY5EQdTQ
* *Ej 4b* — Detectar y corregir problemas de `scanf()` en `checkpal.c`, reemplazar por `fgets()`

**Jue 12 Nov** *(2 sub-ítems)* — Lab4 (cierra)
* *Ej 4c* — Encontrar el bug de `string_clone()` con `valgrind --track-origins=yes` y `gdb`, corregirlo y eliminar memory leaks — 🎥 "Memoria dinámica en C (malloc, free, memory leaks)" — https://www.youtube.com/watch?v=NxE2O-NLOus
* *Ej 4d* — Completar `string_clone()` usando `<string.h>` (sin `strdup()`)

**Dom 15 Nov** *(2 sub-ítems)* — Lab5
* *Lab 5 Ej 1a-c* — TAD Par: implementar con tupla, con arreglo, analizar si logra encapsulamiento — 🎥 "¿Qué es un TAD? Tipos Abstractos de Datos explicados en 5 min" — https://www.youtube.com/watch?v=PIWAKf26NCk
* *Ej 1d* — TAD Par con puntero, agregar manejo de memoria dinámica (constructor/destructor)

**Jue 19 Nov** *(2 sub-ítems)* — Lab5
* *Ej 1e* — TAD Par polimórfico (`Pair of A`), adaptar la implementación anterior a la nueva interfaz
* *Ej 2a* — Implementar TAD Contador cumpliendo la especificación (con `assert()` en las precondiciones) — 🎥 "Tipo de Datos Abstractos — Qué es y tutorial" — https://www.youtube.com/watch?v=UJltNyYpMuM

**Dom 22 Nov** *(2 sub-ítems)* — Lab5
* *Ej 2b* — Usar el TAD Contador para chequear paréntesis balanceados
* *Ej 3a* — Especificar el TAD Lista en `list.h` (constructores, operaciones, `typedef list_elem`) — 🎥 "Fundamentos de programación. Tipos Abstractos de Datos (TAD)" — https://www.youtube.com/watch?v=Kd8Tna-5e-Y

**Jue 26 Nov** *(2 sub-ítems)* — Lab5 (cierra)
* *Ej 3b* — Implementar `list.c` con punteros (listas enlazadas), garantizando encapsulamiento
* *Ej 3c* — Completar `array_to_list()` y `average()` en `main.c`

**Dom 29 Nov** *(2 sub-ítems)* — Lab6
* *Lab 6 Ej 1a-c* — `change()` con programación dinámica para el problema de la moneda + tests + `print_table()` — 🎥 "Cambio con monedas — Programación Dinámica C#" — https://www.youtube.com/watch?v=w69MsdS2oK8
* *Ej 2* — `knapsack()` con programación dinámica para el problema de la mochila + tests + `print_table()` — 🎥 "Programación Dinámica: Método Mochila — Ejemplo 1 Paso a Paso" — https://www.youtube.com/watch?v=QFjeujVWufE

**Jue 3 Dic** *(2 sub-ítems)* — Lab6 (cierra)
* *Ej 3a, b* — Problema de la panadería con programación dinámica + tests (**el ítem c está eliminado por la cátedra — no hacer**) — 🎥 "Cambio de Monedas | Programación Dinámica" — https://www.youtube.com/watch?v=vdDBU3BJNPE
* *Ej 4a, b* — Problema de la fábrica de automóviles (dos líneas de ensamblaje) con programación dinámica + tests — 🎥 "Programación Dinámica: Devolución de Cambio de Monedas" — https://www.youtube.com/watch?v=Sf4OKx1Wz9w

---

## Notas del método

- **Corrida del 6/9 — segundo bajón de ritmo:** el jueves 3/9 tampoco se estudió nada. Se bajó el ritmo a **2 sub-ítems/sesión** (antes ~4) y el laboratorio se sumó al Jueves también (fusionado con el teórico-práctico ese día) — solo Domingo a este ritmo hubiera tardado ~6 meses. El temario cierra el 3/12.
- **Corrida del 1/9:** tras varios corrimientos fallidos (16/8, 23/8, 30/8, 1/9), se había bajado a ~4 sub-ítems/domingo — no llegó a sostenerse ni una semana.
- El único ítem explícitamente eliminado por la cátedra es el (c) del Ejercicio 3 del Lab 6 (panadería con backtracking) — no se implementa.
- Varios videos son sobre el concepto general en C (o incluso en otro lenguaje) en vez de la consigna exacta — el objetivo es entender el mecanismo (punteros, malloc, TADs, DP) antes de programarlo en el lenguaje específico de la cátedra.
- El temario ya no apunta al Llamado 1 como objetivo — apunta al Llamado 2, con margen real de por medio.
- Cuando consigas la Parte 2 del Lab 5 (si existe), se agrega con el mismo formato.