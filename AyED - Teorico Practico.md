# Algoritmos y Estructuras de Datos II — Teórico-Práctico (Prácticos 1-3)

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Mié 2 Diciembre 2026 | **Llamado 1** |
| Mié 16 Diciembre 2026 | Llamado 2 |

> No cursás la materia este cuatrimestre — la estudiás en paralelo para rendir el final en diciembre. El único día de la semana dedicado a AED2 es el **Domingo**, con 4h totales repartidas en 2h de laboratorio + 2h de teórico-práctico. Este plan cubre solo el bloque de teórico-práctico (2h/domingo, ~3-4 ejercicios).

---

## Estado actual (1 Septiembre)

- Nada resuelto todavía. Tras varios corrimientos fallidos del sprint, seguimos en cero — se reorganizó con un ritmo más liviano (3 ejercicios/sesión) y un segundo día semanal (Jueves) para compensar sin sobrecargar cada sesión. Arranca el jueves 3/9.
- Prácticos disponibles: **Práctico 1** (Parte 1, 2 y 3), **Práctico 2** (Parte 1, 2 y 3), **Práctico 3** (Parte 1: voraces, Parte 2: voraces en grafos, Parte 3: backtracking, Parte 4: programación dinámica).
- **Práctico 0** (introducción al lenguaje de la materia) queda como lectura de referencia — no tiene ejercicios a resolver de cero (trae las soluciones incluidas), pero conviene repasarlo antes de arrancar porque define la sintaxis (`proc`, `fun`, `array`, `for`, `while`, etc.) que se usa en todos los prácticos siguientes.
- Por el desfasaje entre el ritmo real (~3 ejercicios/domingo) y los ejercicios totales de los 3 prácticos (70), se acordó **saltear los ejercicios "de aplicación" repetitivos** dentro de cada sección (mismo criterio/técnica aplicado a distintos disfraces) para bajar el total a 59 y que entre en las 16 semanas disponibles.

---

## Prácticos de ejercicios

| # | Tema | Ejercicios (tras los saltos acordados) |
|---|---|---|
| P1 - Parte 1 | Arreglos: inicialización, ordenamiento (selección/inserción), complejidad de loops | 8 (de 10 — se saltea ej. 2 y 9, mecánicos/redundantes) |
| P1 - Parte 2 | Merge sort, quick sort, variantes de partition | 6 (todos) |
| P1 - Parte 3 | Complejidad: recursión, búsqueda binaria, notación asintótica | 6 (de 8 — se saltean ej. 7\* y 8\*, marcados "adicionales" en el enunciado) |
| P2 - Parte 1 | Matrices, tipos enumerados, tuplas, punteros, orden lexicográfico | 7 (todos) |
| P2 - Parte 2 | TADs Lista y Conjunto (spec + implementación) | 6 (todos) |
| P2 - Parte 3 | TADs Pila, Cola, Árbol binario, Diccionario/ABB | 7 (de 8 — se saltea ej. 8, redundante con 6 y 7 sobre ABB) |
| P3 - Parte 1 | Algoritmos voraces (demostraciones + aplicación) | 6 (de 9 — se saltean ballenas, submarino y troncos: mismo criterio de selección voraz que combustible/teléfono/hornos) |
| P3 - Parte 2 | Voraces sobre grafos: Prim, Dijkstra | 3 (todos) |
| P3 - Parte 3 | Backtracking | 6 (de 9 — se saltean panadería-harina, artesano y autos-ensamblaje: mismas variantes de "elegir/no elegir") |
| P3 - Parte 4 | Programación dinámica | 4 (todos) |

**Total: 59 ejercicios** en los 15 domingos que quedan (23 Ago a 29 Nov) tras perder el domingo 16/8 — sin domingo de repaso libre antes del Llamado 1 (se consumió con el corrimiento).

---

## Conceptos clave

- [ ] Sintaxis del lenguaje: `proc`/`fun`, parámetros `in`/`out`/`in-out`, `array`, tipos `enumerate`, `tuple`, `pointer`
- [ ] Ordenamiento: selección, inserción, merge sort, quick sort (partition, mediana de 3, partición en 3 vías)
- [ ] Complejidad: sumatorias, recurrencias, notación asintótica (❁, ≈), comparación de órdenes
- [ ] Divide y vencerás: búsqueda binaria, mínimo/máximo recursivo
- [ ] TADs lineales: Lista (con punteros y con arreglo), Pila, Cola (con O(1))
- [ ] TADs no lineales: Árbol binario, Diccionario/ABB, Conjunto
- [ ] Algoritmos voraces: criterio de selección, demostración de (no) optimalidad
- [ ] Voraces sobre grafos: Prim (árbol de expansión mínima), Dijkstra (camino mínimo)
- [ ] Backtracking: espacio de soluciones, poda
- [ ] Programación dinámica: recurrencia, tabla, dirección de llenado, reconstrucción de la solución

---

## Reparto semanal de materias (4 materias)

| Día | Materia(s) |
|---|---|
| Lunes (día completo, sin clase) | PyE y Lógica |
| Martes (clase 9-13 PyE + 14-18 Álgebra) | Libre de AED2 |
| Miércoles (tarde libre, ~4h) | Álgebra |
| Jueves (clase 9-13 PyE + 14-18 Álgebra) | Lógica (noche) + **AED2 Teórico-Práctico (2h, día liviano nuevo)** |
| Viernes | Libre — sin materia |
| Sábado (~4h) | Lógica y Álgebra (refuerzo) |
| Domingo (4h) | **AED2**: 2h Laboratorio + **2h Teórico-Práctico** (este plan) + PyE |

> Ritmo del teórico-práctico de AED2: **2h/domingo → ~3-4 ejercicios**. Con 16 domingos disponibles entre el 16/8 y el 29/11, y 59 ejercicios a cubrir, el ritmo real queda en ~3.9 ejercicios/domingo (14 domingos de 4 ejercicios + 1 de 3), con el último domingo (29/11) libre para repaso general antes del Llamado 1 del 2/12.

---

## Cronograma día por día

> Se muestran todos los domingos del cronograma. Los demás días de la semana no tienen AED2 (van a otras materias, ver reparto arriba).

| Fecha | Contenido |
|---|---|
| ~~Dom 16 Ago~~ | ~~**PERDIDO**~~ (familia de visita) |
| ~~Dom 23 Ago~~ | ~~**PERDIDO**~~ (semana de gripe) |
| ~~Dom 30 Ago~~ | ~~**PERDIDO**~~ (semana del sprint) |
| ~~Mar 1 Sep~~ | ~~**PERDIDO**~~ (seguimos en cero, se reorganiza todo con ritmo más liviano) |
| Jue 3 Sep | **P1.1 ej. 1, 3, 4** |
| Dom 6 Sep | **P1.1 ej. 5, 6, 7** |
| Jue 10 Sep | **P1.1 ej. 8, 10 (cierra P1 Parte 1) · P1.2 ej. 1** |
| Dom 13 Sep | **P1.2 ej. 2, 3, 4** |
| Jue 17 Sep | **P1.2 ej. 5, 6 (cierra P1 Parte 2) · P1.3 ej. 1** |
| Dom 20 Sep | **P1.3 ej. 2, 3, 4** |
| Jue 24 Sep | **P1.3 ej. 5, 6 (cierra P1) · P2.1 ej. 1** |
| Dom 27 Sep | **P2.1 ej. 2, 3, 4** |
| Jue 1 Oct | **P2.1 ej. 5, 6, 7 (cierra P2 Parte 1)** |
| Dom 4 Oct | **P2.2 ej. 1, 2, 3** |
| Jue 8 Oct | **P2.2 ej. 4, 5, 6 (cierra P2 Parte 2)** |
| Dom 11 Oct | **P2.3 ej. 1, 2, 3** |
| Jue 15 Oct | **P2.3 ej. 4, 5, 6** |
| Dom 18 Oct | **P2.3 ej. 7 (cierra P2) · P3.1 ej. 1, 2** |
| Jue 22 Oct | **P3.1 ej. 3, 5, 6** |
| Dom 25 Oct | **P3.1 ej. 9 (cierra P3 Parte 1) · P3.2 ej. 1, 2** |
| Jue 29 Oct | **P3.2 ej. 3 (cierra P3 Parte 2) · P3.3 ej. 1, 2** |
| Dom 1 Nov | **P3.3 ej. 4, 5, 7** |
| Jue 5 Nov | **P3.3 ej. 9 (cierra P3 Parte 3) · P3.4 ej. 1, 2** |
| Dom 8 Nov | **P3.4 ej. 3, 4 (cierra el temario completo)** |
| Dom 15 Nov → Mié 2 Dic | — | Sin ejercicios nuevos (temario completo desde el 8/11). Repaso general, TPs pendientes, margen amplio antes del Llamado 1. |
| **Mié 2 Dic** | **LLAMADO 1** |

> **Corrida del 1/9:** seguíamos en cero con AED2 tras varios corrimientos fallidos del sprint — se reorganizó todo con un ritmo más liviano (3 ejercicios/sesión en vez de 4-5) y un segundo día en la semana (Jueves, antes libre) para no perder margen. Arranca el jueves 3/9. El temario completo cierra el **domingo 8/11**, dejando más de **3 semanas de repaso** antes del Llamado 1 (2/12) — mucho más margen que en cualquier versión anterior del plan.

## Detalle día por día
**Jue 3 Sep** *(2h)* — P1.1 ej. 1, 3, 4
* *Ej 1* — Inicializar cada componente del arreglo con 0, usando `do` — 🎥 "CLASE 25 - Arreglos: recorrer elementos" — https://www.youtube.com/watch?v=KGU8k6V2-VI
* *Ej 3* — Determinar si un arreglo está ordenado — 🎥 "Recorrer un Arreglo en C++" — https://www.youtube.com/watch?v=lCD6kjj4mu4
* *Ej 4* — Ordenar arreglos con el algoritmo de selección, mostrando cada paso — 🎥 "Algoritmo de Selección — Explicación y Ejemplo Paso a Paso" — https://www.youtube.com/watch?v=1TLehzzoauU

**Dom 6 Sep** *(2h)* — P1.1 ej. 5, 6, 7
* *Ej 5* — Calcular el número de asignaciones a `t` en loops anidados (sumatorias) — 🎥 "¿Cómo funciona la notación asintótica?" — https://www.youtube.com/watch?v=HcDV5MGGrRE
* *Ej 6* — Descifrar un algoritmo (selecciona el máximo y hace swap), reescribirlo con nombres adecuados — 🎥 "Algoritmos de ordenación – Selección" — https://www.youtube.com/watch?v=ZMO3Fow05tg
* *Ej 7* — Ordenar arreglos con el algoritmo de inserción, mostrando comparaciones e intercambios — 🎥 "Paso a paso a través de la función de ordenamiento por inserción" — https://www.youtube.com/watch?v=jRa1HqG9YaI

**Jue 10 Sep** *(2h)* — P1.1 ej. 8, 10 (cierra P1 Parte 1) · P1.2 ej. 1
* *Ej 8* — Calcular el orden de asignaciones a `t` en distintos `do`-loops (incisos a-d) — 🎥 "Complejidad algoritmos recursivos" — https://www.youtube.com/watch?v=qNDaGZNI6s8
* *Ej 10* — Descifrar otro algoritmo (similar a inserción), reescribir con nombres adecuados — 🎥 "PseInt - Arreglos para n edades" — https://www.youtube.com/watch?v=cTavUffMwIA
* *Ej 1* — Ordenar arreglos con merge sort + secuencia de llamadas a `merge_sort_rec` — 🎥 "Merge Sort — explicado al detalle" — https://www.youtube.com/watch?v=kOgzXagXpTg

**Dom 13 Sep** *(2h)* — P1.2 ej. 2, 3, 4
* *Ej 2* — Procedimiento "intercalar cada" + versión iterativa del merge sort — 🎥 "Merge Sort | Ordenamiento por mezcla" — https://www.youtube.com/watch?v=ACFZn_xQcz8
* *Ej 3* — Ordenar arreglos con quick sort + secuencia de llamadas a `quick_sort_rec` — 🎥 "Quick Sort — algoritmo de ordenamiento explicado al detalle" — https://www.youtube.com/watch?v=YzHDIvxOQcI
* *Ej 4* — Variante de `partition` con pivote = mediana de tres — 🎥 "Improving Quicksort with Median of 3 and Cutoffs" — https://www.youtube.com/watch?v=1Vl2TB7DoAM

**Jue 17 Sep** *(2h)* — P1.2 ej. 5, 6 (cierra P1 Parte 2) · P1.3 ej. 1
* *Ej 5 (P1.2)* — Encontrar el elemento que quedaría en la posición k si el arreglo estuviera ordenado (quickselect) — 🎥 "Quick Select" — https://www.youtube.com/watch?v=aOhyCdxGJvY
* *Ej 6 (P1.2)* — Modificar `partition` para separar en 3 segmentos (menores, iguales, mayores al pivot) — 🎥 "Sort Colors — Dutch National Flag Algorithm" — https://www.youtube.com/watch?v=ph-PeeYo7cU
* *Ej 1 (P1.3)* — Calcular el orden de complejidad de f1 y f2 (recursivos con múltiples llamadas) — 🎥 "Aprende Divide y Vencerás — Subarreglo Máximo" — https://www.youtube.com/watch?v=UxtAqHOb8aw

**Dom 20 Sep** *(2h)* — P1.3 ej. 2, 3, 4
* *Ej 2 (P1.3)* — Determinar/encontrar la "cima" de un arreglo: búsqueda secuencial vs. binaria — 🎥 "Estructura de Datos — Método Búsqueda Binaria" — https://www.youtube.com/watch?v=u3J-fe4UFsA
* *Ej 3* — Analizar la eficiencia del mínimo de un arreglo por divide y vencerás — 🎥 "Aprende Divide y Vencerás — Elemento mínimo y máximo de un vector" — https://www.youtube.com/watch?v=0lZmuVkRT44
* *Ej 4* — Ordenar (❁, ≈) funciones de complejidad, sin calcular límites — 🎥 "¿Qué es la BÚSQUEDA BINARIA y por qué es tan GENIAL?" — https://www.youtube.com/watch?v=L7BPRzPzZtY

**Jue 24 Sep** *(2h)* — P1.3 ej. 5, 6 (cierra P1) · P2.1 ej. 1
* *Ej 5* — Determinar valores de K y L para que un procedimiento tenga el orden pedido — 🎥 "Tutorial: Algoritmo Búsqueda Binaria (Python)" — https://www.youtube.com/watch?v=8B4FH1BtaiA
* *Ej 6* — Escribir algoritmos con complejidades dadas (sin usar multiplicación ni logaritmos) — 🎥 "Algoritmo de búsqueda binaria" — https://www.youtube.com/watch?v=C9U6PqM5r-c
* *Ej 1* — Mínimo de una matriz + arreglo con el mínimo de cada fila — 🎥 "Arreglos bidimensionales C# — Colecciones y Arreglos" — https://www.youtube.com/watch?v=dXchlGBS0FQ

**Dom 27 Sep** *(2h)* — P2.1 ej. 2, 3, 4
* *Ej 2* — Tipos enumerados + arreglo multidimensional (datos climáticos de Córdoba), 5 incisos — 🎥 "Métodos de ENUMS en Java" — https://www.youtube.com/watch?v=FzCPx6sIctQ
* *Ej 3* — Tupla `person`: calcular promedio de edad/peso + ordenar alfabéticamente — 🎥 "Estructuras en C++ — Ordenar arreglo de estructuras" — https://www.youtube.com/watch?v=MdEmmTlO8NA
* *Ej 4* — Punteros: intercambiar valores referidos vs. intercambiar los punteros — 🎥 "Punteros y Paso por Referencia" — https://www.youtube.com/watch?v=jxHeXMPcD_c

**Jue 1 Oct** *(2h)* — P2.1 ej. 5, 6, 7 (cierra P2 Parte 1)
* *Ej 5 (P2.1)* — `lex_less`, `lex_less_or_equal` y `lex_compare` entre dos arreglos — 🎥 "Orden Diccionario o Lexicográfico" — https://www.youtube.com/watch?v=ES9hKdMLh0w
* *Ej 6 (P2.1)* — Suma de dos matrices — 🎥 "PYTHON — Lección 14: MATRICES" — https://www.youtube.com/watch?v=OyNXw80YgXc
* *Ej 7 (P2.1)* — Producto de dos matrices — 🎥 "C #20 — Arreglo Bidimensional" — https://www.youtube.com/watch?v=dei49_2PltI

**Dom 4 Oct** *(2h)* — P2.2 ej. 1, 2, 3
* *Ej 1 (P2.2)* — Completar la implementación del TAD Lista dada en el teórico, usando punteros — 🎥 "Tipo abstracto de datos, tipo de datos y estructura de datos" — https://www.youtube.com/watch?v=eexIZrYtlnI
* *Ej 2* — Implementar el TAD Lista usando un arreglo de tamaño N — 🎥 "Fundamentos de programación. Tipos Abstractos de Datos (TAD)" — https://www.youtube.com/watch?v=Kd8Tna-5e-Y
* *Ej 3* — `add_at`: agregar un elemento en la posición n (usando copy, take, drop) — 🎥 "Listas Enlazadas — Insertar datos al final y luego de uno" — https://www.youtube.com/watch?v=JeJUL54w_kk

**Jue 8 Oct** *(2h)* — P2.2 ej. 4, 5, 6 (cierra P2 Parte 2)
* *Ej 4* — TAD Tablero deportivo: especificación + 2 implementaciones con tupla de contadores — 🎥 "¿Qué es un TAD? Tipos Abstractos de Datos explicados en 5 min" — https://www.youtube.com/watch?v=PIWAKf26NCk
* *Ej 5* — Especificar el TAD Conjunto finito (vacío, agregar, pertenece, unión, intersección, diferencia) — 🎥 "Tipo de Datos Abstractos — Qué es y tutorial" — https://www.youtube.com/watch?v=UJltNyYpMuM
* *Ej 6 (P2.2)* — Implementar el TAD Conjunto con lista ordenada sin repetidos (invariante de representación) — 🎥 "Unión e intersección de conjuntos" — https://www.youtube.com/watch?v=X6KOFt74Vwg

**Dom 11 Oct** *(2h)* — P2.3 ej. 1, 2, 3
* *Ej 1 (P2.3)* — Implementar el TAD Pila usando `type Stack of T = List of T` — 🎥 "Stack, Pila — Estructuras de Datos en C#" — https://www.youtube.com/watch?v=-OtrauxqkeI
* *Ej 2 (P2.3)* — Implementar el TAD Pila con nodos y punteros — 🎥 "C++: inserción al principio (pila) en listas simplemente enlazadas" — https://www.youtube.com/watch?v=KE1x4a6U7os
* *Ej 3 (P2.3)* — TAD Cola con arreglo (básica) + versión con todas las operaciones en O(1) — 🎥 "Filas/Colas — Implementación con un vector" — https://www.youtube.com/watch?v=1ohpRRDFKIw

**Jue 15 Oct** *(2h)* — P2.3 ej. 4, 5, 6
* *Ej 4* — Completar la implementación del Árbol Binario con punteros (`left`/`right`) — 🎥 "Construcción de Árboles binarios a partir de sus recorridos" — https://www.youtube.com/watch?v=KY_6Xduq8jc
* *Ej 5* — Especificar el TAD Diccionario + implementarlo como ABB (invariante: binario de búsqueda) — 🎥 "Árbol binario de búsqueda C++ (insertar, recorridos y buscar)" — https://www.youtube.com/watch?v=xind74PvxA0
* *Ej 6* — En un ABB con nodos 1-1000, determinar qué secuencias de comparación NO son válidas al buscar 363 — 🎥 "Estructuras de datos — 13. Árboles binarios de búsqueda (parte 1)" — https://www.youtube.com/watch?v=G1VS5FbtMS4

**Dom 18 Oct** *(2h)* — P2.3 ej. 7 (cierra P2) · P3.1 ej. 1, 2
* *Ej 7* — Determinar el ABB resultante de insertar una secuencia dada de 12 números — 🎥 "El Árbol Binario de Búsqueda" — https://www.youtube.com/watch?v=mTMrszfrNtI
* *Ej 1* — Demostrar que el voraz de la mochila sin fragmentación no siempre es óptimo — 🎥 "Problema de la mochila fraccionada (Algoritmos voraces)" — https://www.youtube.com/watch?v=7xQQaVbw1cc
* *Ej 2* — Dar cambio: probar o dar contraejemplo sobre cuándo el voraz es óptimo — 🎥 "El problema de las monedas — Algoritmo de greedy" — https://www.youtube.com/watch?v=GhliJTFE-Wk

**Jue 22 Oct** *(2h)* — P3.1 ej. 3, 5, 6
* *Ej 3* — Viaje en auto con autonomía A: mínimo número de cargas de combustible — 🎥 "Algoritmos Voraces | Programación Greedy" — https://www.youtube.com/watch?v=ALtJncFD8N8
* *Ej 5* — Teléfono satelital: a cuántos amigos prestárselo según períodos de viaje (intervalos) — 🎥 "Algoritmos voráces, planificación de tareas, selección de actividades" — https://www.youtube.com/watch?v=dX7UNf3koEM
* *Ej 6 (P3.1)* — Facturas en el horno: criterio voraz para extraerlas todas en su punto (tiempos min/max) — 🎥 "Algoritmo Voraz — Problema 2: Planificación de tareas" — https://www.youtube.com/watch?v=XWhhgsjUJh8

**Dom 25 Oct** *(2h)* — P3.1 ej. 9 (cierra P3 Parte 1) · P3.2 ej. 1, 2
* *Ej 9 (P3.1)* — Limonada con happy hour: minimizar el gasto eligiendo bar cada hora — 🎥 "Análisis de algoritmos: Programación voraz — Selección de actividades y Mochila voraz" — https://www.youtube.com/watch?v=YSSqVQ62u98
* *Ej 1 (P3.2)* — Ejecutar el algoritmo de Prim paso a paso sobre 2 grafos — 🎥 "Algoritmo de Prim: Encuentra el Árbol de Expansión Mínima con Facilidad" — https://www.youtube.com/watch?v=PJGuqIm5y9k
* *Ej 2 (P3.2)* — Ejecutar el algoritmo de Dijkstra paso a paso sobre los mismos 2 grafos — 🎥 "Explicación Algoritmo de Dijkstra para encontrar el camino más corto" — https://www.youtube.com/watch?v=jC4B7HQ5ikU

**Jue 29 Oct** *(2h)* — P3.2 ej. 3 (cierra P3 Parte 2) · P3.3 ej. 1, 2
* *Ej 3 (P3.2)* — Ciudades alcanzables con L litros de nafta (usando Dijkstra) — 🎥 "Grafos: Camino mínimo con algoritmo de DIJKSTRA" — https://www.youtube.com/watch?v=gq3cTlBMJhs
* *Ej 1 (P3.3)* — Backtracking del problema de la moneda: devolver qué monedas se usan — 🎥 "Backtracking — Introducción — Problema de la Moneda" — https://www.youtube.com/watch?v=MMEFM6ZQcIM
* *Ej 2 (P3.3)* — País con monedas 15, 23, 29: qué recuerdo comprar conservando más monedas — 🎥 "Explicando Backtracking | Fuerza Bruta Pero Elegante" — https://www.youtube.com/watch?v=ip2jC_kXGtg

**Dom 1 Nov** *(2h)* — P3.3 ej. 4, 5, 7
* *Ej 4 (P3.3)* — Globo aerostático: mínimo valor a arrojar para perder P kg — 🎥 "El problema de la mochila con backtracking" — https://www.youtube.com/watch?v=S0uc0LGJu-M
* *Ej 5 (P3.3)* — Teléfono satelital con alquiler por día: máximo valor alcanzable — 🎥 "FIUBA — Programación dinámica: Weighted Interval Scheduling" — https://www.youtube.com/watch?v=nPADw26j0sE
* *Ej 7 (P3.3)* — Mochila con dos capacidades W1 y W2: valor máximo alcanzable — 🎥 "Algorítmia — Backtracking. Mochila" — https://www.youtube.com/watch?v=vdVpRjO7g84

**Jue 5 Nov** *(2h)* — P3.3 ej. 9 (cierra P3 Parte 3) · P3.4 ej. 1, 2
* *Ej 9 (P3.3)* — Juego -U↑P%: máximo y mínimo puntaje recorriendo una grilla — 🎥 "Programación dinámica: Ejemplo 1 — Ruta más corta" — https://www.youtube.com/watch?v=2j1QWktKknY
* *Ej 1 (P3.4)* — Programación dinámica para el problema del cambio (a partir de la recursión top-down) — 🎥 "Cambio con monedas — Programación Dinámica C#" — https://www.youtube.com/watch?v=w69MsdS2oK8
* *Ej 2* — ¿Se puede completar la tabla "de abajo hacia arriba" o "de derecha a izquierda"? — 🎥 "Programación Dinámica: Devolución de Cambio de Monedas" — https://www.youtube.com/watch?v=Sf4OKx1Wz9w

**Dom 8 Nov** *(2h)* — P3.4 ej. 3, 4 (cierra el temario completo)
* *Ej 3* — Programación dinámica del cambio a partir de otras 2 definiciones recursivas (a, b) — 🎥 "Cambio de Monedas | Programación Dinámica" — https://www.youtube.com/watch?v=vdDBU3BJNPE
* *Ej 4* — Convertir a programación dinámica los ejercicios de backtracking 3-9, devolviendo la solución (no solo el valor) — 🎥 "Programación Dinámica: Método Mochila — Ejemplo 1 Paso a Paso" — https://www.youtube.com/watch?v=QFjeujVWufE


---

## Notas del método

- **Corrida del 1/9 — reorganización completa:** tras varios corrimientos fallidos del sprint (16/8, 23/8, 30/8, 1/9 todos perdidos), seguíamos en cero. Se decidió bajar el ritmo a 3 ejercicios/sesión (antes 4-5, sentido como "avaricioso") y sumar el Jueves como segundo día semanal — antes libre de AED2, ahora una sesión liviana más. Con Domingo + Jueves (6 ej./semana), el temario cierra el 8/11, dejando más de 3 semanas de margen antes del Llamado 1 — mucho mejor que cualquier versión anterior.
- Historial de corridas previas (16/8, 22/8, 28/8): todas fallaron en sostenerse — de ahí la decisión de bajar el ritmo en vez de seguir corriendo fechas.

- El déficit entre el ritmo real y el total de ejercicios se resolvió **salteando ejercicios de aplicación repetitivos** dentro de cada práctico (misma técnica en distintos disfraces) en vez de acelerar el ritmo o recortar prácticos completos — así se mantienen todos los temas del programa, aligerando solo la cantidad de variantes de cada uno.
- Varios videos son de la técnica general (partition, ABB, backtracking) en vez del enunciado exacto — como en Álgebra y Lógica, el objetivo es entender el mecanismo, no encontrar el ejercicio calcado.
- Con el nuevo ritmo hay margen real de repaso antes del Llamado 1 — si algún día rinde menos de lo esperado, hay colchón para absorberlo sin tener que reorganizar todo de nuevo.
- Cuando lleguen los prácticos 4 en adelante (si se suman), se agregan con el mismo formato (tabla banco + detalle inline).