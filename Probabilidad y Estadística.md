# Probabilidad y Estadística — Plan de estudio (recursada 2026)

Prioridad: ALTA — dos parciales, se cursa desde cero a full profundidad.

---

## Fechas clave

| Fecha | Evento |
|---|---|
| Mar 29 Septiembre | **Parcial 1** — Guías 1 a 4 |
| Mar 10 Noviembre | **Parcial 2** — Guías 5 a 8 |

---

## Estado actual (26 Agosto)

- Recursada: se vuelve a cursar la materia completa, a full profundidad (no repaso liviano).
- G1 ej. 1-3 confirmados. Ej. 4-6 ya se habían hecho pero se retoman el domingo para afianzar mejor la base — no se avanzó nada más esta semana (dedicada a Lógica y luego Álgebra).
- Domingo 30 es el día de sprint dedicado a PyE (8h) dentro de la semana Vie=Álgebra / Sáb=Lógica / Dom=PyE / Lun=AyED2. Parcial 1 confirmado el 29/9.

---

## Guías de ejercicios

| # | Tema | Ejercicios | Parcial |
|---|---|---|---|
| G1 | Probabilidad, prob. condicional, independencia | 18 | 1 |
| G2 | Variables aleatorias discretas | 18 (ej. 0–17) | 1 |
| G3 | Variables aleatorias continuas | 17 | 1 |
| G4 | Distribuciones conjuntas y muestras aleatorias | 16 | 1 |
| G5 | Estimación puntual | 10 | 2 |
| G6 | Intervalos de confianza (una muestra) | 9 | 2 |
| G7 | Pruebas de hipótesis (una muestra) | 17 | 2 |
| G8 | Pruebas de hipótesis (dos muestras) | 8 | 2 |

**Total: 113 ejercicios.**

---

## Conceptos clave

### Bloque 1 — Parcial 1 (G1–G4)
- [ ] Espacio muestral, eventos, axiomas de probabilidad, técnicas de conteo
- [ ] Probabilidad condicional y Teorema de Bayes
- [ ] Independencia de eventos
- [ ] VA discretas: fmp, fda, esperanza, varianza, transformaciones
- [ ] Distribuciones discretas: Binomial, Poisson, Hipergeométrica, Binomial Negativa
- [ ] VA continuas: fdp, fda, esperanza, varianza
- [ ] Distribuciones continuas: Uniforme, Normal, Exponencial, Gamma, Weibull, log-normal, chi-cuadrado
- [ ] Distribuciones conjuntas: marginales, independencia, covarianza, correlación
- [ ] TLC y aproximación normal a Binomial/Poisson

### Bloque 2 — Parcial 2 (G5–G8)
- [ ] Estimadores insesgados, error estándar
- [ ] Método de momentos y máxima verosimilitud (+ propiedad de invarianza)
- [ ] Intervalos de confianza: media (Z y T), varianza (chi²), proporción
- [ ] Pruebas de hipótesis: H0, Ha, región de rechazo, error tipo I y II
- [ ] Estadísticos Z y T, p-valor
- [ ] Pruebas de dos muestras: independientes y apareadas

---

## Banco de ejercicios y videos

*(INV = investigar teoría primero, resolver en pizarra sin apuntes, después comparar. Un mismo video puede repetirse entre ejercicios que comparten técnica.)*

### Guía 1 — Probabilidad, prob. condicional, independencia

| Ej | Descripción | Video |
|---|---|---|
| 1 | Biblioteca: listar resultados posibles, eventos A/B/C, uniones e intersecciones | [Experimento aleatorio, espacio muestral y probabilidad](https://www.youtube.com/watch?v=fTIS83G7aC8) |
| 2 | Demostrar P(B−A)=P(B)−P(A) si A⊆B; relación entre P(A), P(A∩B), P(A∪B) | [Demostración: teoremas de probabilidad — vacío, unión y complemento](https://www.youtube.com/watch?v=nDl0mhVkNeM) |
| 3 | Licitaciones: uniones e intersecciones de 3 eventos | [Probabilidades de 3 eventos](https://www.youtube.com/watch?v=ipqWoW4yqik) |
| 4 | Asignación de contratos a empresas (conteo + probabilidad) | [Técnicas de conteo — ejercicios resueltos](https://www.youtube.com/watch?v=v3TFHZsqhME) |
| 5 | Colectivos con grietas: selección de muestra sin reposición | [Probabilidad, permutaciones y combinaciones — ejercicios](https://www.youtube.com/watch?v=lNQIT9Hir5I) |
| 6 | Comisión de 2 entre 5 miembros: combinatoria + años de experiencia | [Permutaciones y combinaciones — Nivel 1](https://www.youtube.com/watch?v=QXO3u6Ak4rU) |
| 7* | Reuniones ordenadas con 8 ayudantes: permutaciones | [Variaciones, combinaciones, permutaciones — Nivel 1](https://www.youtube.com/watch?v=ynxsVxVZ9Vw) |
| 8 | Cubos entre dos cajas: extracción secuencial | [Bayes — problema 3 resuelto](https://www.youtube.com/watch?v=850a--CribU) |
| 9 | Tabla de camisas por talle/modelo/manga: conjunta y condicional desde tabla | [Teorema de Bayes — ejercicios resueltos](https://www.youtube.com/watch?v=ENiTI9Rgs-c) |
| 10 | Demostraciones de propiedades de probabilidad condicional | [Teorema de Bayes — ejercicios resueltos (selectividad)](https://www.youtube.com/watch?v=G_4k4qxZRP4) |
| 11 | Prueba diagnóstica de enfermedad: Bayes con falsos +/− | [Teorema de Bayes — probabilidades, ejercicios resueltos](https://www.youtube.com/watch?v=CP4ToX5Tyvw) |
| 12 | Demostrar independencia de eventos complementarios | [Eventos independientes — ejercicios resueltos](https://www.youtube.com/watch?v=Ny8NBX7ZLcw) |
| 13 | Tablas de madera sin reposición: ¿A y B independientes? | [Sucesos independientes — ejercicios resueltos](https://www.youtube.com/watch?v=_vl-2RsrpgQ) |
| 14 | Reparto de 52 cartas entre 4 jugadores | [Permutaciones y combinaciones — Nivel 2A](https://www.youtube.com/watch?v=ns7uwSVPLJk) |
| 15 | Leucoplasia oral: fumar y alcohol, ¿independientes? | [Eventos dependientes e independientes — fácil](https://www.youtube.com/watch?v=wOwwPD-O5sY) |
| 16 | Empresas de correo: probabilidad total + Bayes | [Teorema de Bayes — explicación y ejercicio resuelto](https://www.youtube.com/watch?v=KrvsiHh1ThA) |
| 17* | Costura de avión con remaches: independencia + resolver p | [Probabilidad de eventos dependientes — fácil](https://www.youtube.com/watch?v=iUOnVO7yAfA) |
| 18* | Carrera de caballos: eventos compuestos | [Combinaciones, permutaciones y variaciones — Ejemplo 1](https://www.youtube.com/watch?v=h4IfRXoVcpo) |

### Guía 2 — Variables aleatorias discretas

| Ej | Descripción | Video |
|---|---|---|
| 0 | Definir función de probabilidad y una VA en experimento de listas aleatorias | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 1 | Identificar cuál tabla es una fmp válida; calcular P, obtener FDA | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 2 | fmp de líneas telefónicas en uso: calcular probabilidades de eventos | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 3 | FDA dada por tramos: obtener la fmp y probabilidades | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 4 | Nº de determinaciones hasta encontrar grupo O+ (fmp tipo geométrica) | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 5 | Recorrido aleatorio de Silvina: fmp y FDA de destinos y segmentos | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 6 | Esperanza de un dado y de 1/X; decisión retirarse o jugar | [Esperanza y varianza VA discreta](https://www.youtube.com/watch?v=oB48B-WUwJk) |
| 7 | Congeladores: E(X), E(X²), V(X), transformación lineal y no lineal | [Esperanza y varianza VA discreta](https://www.youtube.com/watch?v=oB48B-WUwJk) |
| 8 | Esperanza/varianza de la VA del ej. 4; costo esperado y su varianza | [Esperanza y varianza VA discreta](https://www.youtube.com/watch?v=oB48B-WUwJk) |
| 9 | Binomial: automovilistas que se detienen en un cruce | [Binomial](https://www.youtube.com/watch?v=-XxZGvNClkg) |
| 10* | Binomial: raquetas de tenis, prob. dentro de 1 DE, sin reposición | [Binomial](https://www.youtube.com/watch?v=-XxZGvNClkg) |
| 11 | Binomial + Hipergeométrica: reparaciones de TV sin garantía | [Binomial/Hiperg./Poisson – cuándo usar cada una](https://www.youtube.com/watch?v=JWRTMeJg70I) |
| 12 | Hipergeométrica: refrigeradores con compresor defectuoso | [Hipergeométrica](https://www.youtube.com/watch?v=3pDDo0LvRHo) |
| 13 | Binomial Negativa: serie de partidos Boca–River | [Binomial Negativa](https://www.youtube.com/watch?v=LgNSqHil6w0) |
| 14 | Poisson: número de tornados observados en un año | [Poisson](https://www.youtube.com/watch?v=PMX75m4-s9A) |
| 15 | Poisson: suma de dos Poisson independientes (autos en estacionamiento) | [Poisson](https://www.youtube.com/watch?v=PMX75m4-s9A) |
| 16* | Poisson: ganancia esperada con transformación cuadrática | [Poisson](https://www.youtube.com/watch?v=PMX75m4-s9A) |
| 17 | Demostrar E(X) y V(X) de Hipergeométrica y Binomial Negativa | [Binomial/Hiperg./Poisson – cuándo usar cada una](https://www.youtube.com/watch?v=JWRTMeJg70I) |

### Guía 3 — Variables aleatorias continuas

| Ej | Descripción | Video |
|---|---|---|
| 1 | fdp lineal (x/2): probabilidades, FDA, E(X), V(X), cobro esperado h(X) | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 2 | FDA cúbica dada: hallar probabilidades y la fdp | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 3 | fdp con constante k (kx²): percentil 75, E(X), σ | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 4 | Uniforme: tiempo de preparación de laboratorio [25,35] | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 5 | Normal N(80,100): probabilidades básicas con tabla Z | [Distribución Normal](https://www.youtube.com/watch?v=T7_ktqfVseU) |
| 6 | Normal: diámetro de árboles, percentiles, binomial aproximada | [Distribución Normal](https://www.youtube.com/watch?v=T7_ktqfVseU) |
| 7 | Normal: hallar µ y σ desde percentiles de resistencia | [Distribución Normal](https://www.youtube.com/watch?v=T7_ktqfVseU) |
| 8 | Transformación lineal de Normal; Celsius a Fahrenheit | [Distribución Normal](https://www.youtube.com/watch?v=T7_ktqfVseU) |
| 9 | Normal: mezcla de dos máquinas, tornillos aceptables | [Distribución Normal](https://www.youtube.com/watch?v=T7_ktqfVseU) |
| 10 | Normal: dureza Rockwell, aceptación + binomial aproximada | [Distribución Normal](https://www.youtube.com/watch?v=T7_ktqfVseU) |
| 11 | Exponencial: distancia recorrida por canguros | [Distribución Exponencial](https://www.youtube.com/watch?v=PEib2DsJ2k4) |
| 12 | Exponencial: sistema en serie, mínimo de 5 exponenciales | [Distribución Exponencial](https://www.youtube.com/watch?v=PEib2DsJ2k4) |
| 13 | Sistema de bombas de combustible: Poisson/Exponencial | [Distribución Exponencial](https://www.youtube.com/watch?v=PEib2DsJ2k4) |
| 14* | Gamma: tiempo semanal de máquina no funcional, pérdida esperada | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) *(buscar además "distribución Gamma ejercicios")* |
| 15* | Weibull: tiempo de devolución de un producto defectuoso | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) *(buscar además "distribución Weibull ejercicios")* |
| 16* | Log-normal: tiempo de respuesta de un servidor web | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) *(buscar además "distribución log-normal ejercicios")* |
| 17* | Chi-cuadrado: variabilidad en tiempo de ejecución de un algoritmo | [Distribución chi cuadrado — introducción](https://www.youtube.com/watch?v=Y1bhoKrEL_c) |

### Guía 4 — Distribuciones conjuntas y muestras aleatorias

| Ej | Descripción | Video |
|---|---|---|
| 1 | Conjunta discreta (dos cajas del súper): marginales, independencia | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 2 | fdpc kxy en triángulo: k, marginales, E y V, independencia | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 3 | fdpc k(x+y) en cuadrado: k, P(X+Y<5), marginales, covarianza | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 4 | Poisson independientes: fmp conjunta, P(a lo sumo 1 error) | [Poisson](https://www.youtube.com/watch?v=PMX75m4-s9A) |
| 5 | Exponenciales independientes: fdp conjunta, duración de bombillas | [Distribución Exponencial](https://www.youtube.com/watch?v=PEib2DsJ2k4) |
| 6 | Demostrar que suma de Binomiales independientes es Binomial (Vandermonde) | [Binomial](https://www.youtube.com/watch?v=-XxZGvNClkg) |
| 7 | Demostrar E(XY)=E(X)E(Y) si independientes; área esperada de un rectángulo | [Densidad VA continua](https://www.youtube.com/watch?v=Z3AKFyTzsEA) |
| 8 | Tabla conjunta con parámetros a,b: covarianza cero pero no independencia | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 9 | Combinaciones lineales de Y1, Y2 con covarianza dada | [Función de prob. VA discreta](https://www.youtube.com/watch?v=GaRyczJN3WM) |
| 10 | TLC: densidad de sedimento, tamaño muestral necesario | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |
| 11 | TLC: tiempo de procesamiento de 100 pedidos | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |
| 12 | TLC/Binomial: estudiantes sin errores tipográficos | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |
| 13 | TLC/Binomial: ejes de acero fuera de especificación | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |
| 14 | TLC/Poisson: aproximación normal para media 100 | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |
| 15 | TLC: diferencia de medias muestrales de dos aceros | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |
| 16 | TLC: consumo calórico diario promedio en un año | [Teorema Central del Límite](https://www.youtube.com/watch?v=UV0F6E5PGP4) |

### Guía 5 — Estimación puntual

| Ej | Descripción | Video |
|---|---|---|
| 1 | Poisson: estimador insesgado de λ, error estándar, comparar estimadores | [Estimación puntual — momentos y MV](https://www.youtube.com/watch?v=p59Rik4oHkQ) |
| 2 | Vigas y cilindros de concreto: estimar µ1, µ2, σ1, σ2 y su diferencia | [Estimación puntual — momentos y MV](https://www.youtube.com/watch?v=p59Rik4oHkQ) |
| 3 | Fumadores con/sin filtro: estimador insesgado de p1−p2 | [Estimación puntual — momentos y MV](https://www.youtube.com/watch?v=p59Rik4oHkQ) |
| 4 | Demostrar que X̄² no es insesgado para µ²; hallar k para el estimador corregido | [Estimación puntual — momentos y MV](https://www.youtube.com/watch?v=p59Rik4oHkQ) |
| 5 | fdp con parámetro θ: demostrar que 3X̄ es insesgado, calcular su varianza | [Estimación puntual — momentos y MV](https://www.youtube.com/watch?v=p59Rik4oHkQ) |
| 6 | Método de momentos: fdp (θ+1)xᶿ, estimación con 10 datos | [Estimación puntual — momentos y MV](https://www.youtube.com/watch?v=p59Rik4oHkQ) |
| 7 | Momentos y MV: espesor de pintura, percentil 90, P(X<1.5) | [MV — ejemplo Normal](https://www.youtube.com/watch?v=BOp7n09I3uY) |
| 8 | MV Exponencial: tiempo de respuesta de una terminal | [MV — ejemplo Binomial](https://www.youtube.com/watch?v=RbaW4lhgGc8) |
| 9 | MV Normal: resistencia de soldaduras, percentil 95, propiedad de invarianza | [MV — ejemplo Normal](https://www.youtube.com/watch?v=BOp7n09I3uY) |
| 10 | MV Uniforme[0,θ]: distribución de Y=máx(Xi), sesgo, estimadores insesgados | [MV — introducción](https://www.youtube.com/watch?v=Ypy-6Jnk0Gw) |

### Guía 6 — Intervalos de confianza (una muestra)

| Ej | Descripción | Video |
|---|---|---|
| 1 | IC media, σ conocido: motor de inducción, distintos n y confianza | [IC media — σ conocido](https://www.youtube.com/watch?v=91gR7Up9LZc) |
| 2 | Frecuencia de resonancia: nivel de confianza, zα/2, comparar intervalos | [IC media — σ conocido](https://www.youtube.com/watch?v=91gR7Up9LZc) |
| 3 | IC media, n grande y σ desconocido: densidad de capa de tinte | [IC media — T de Student](https://www.youtube.com/watch?v=lJ1V3SJRgio) |
| 4 | IC proporción: propietarios de armas de fuego | [IC para una proporción](https://www.youtube.com/watch?v=Ca3XN4h2tgw) |
| 5 | IC media: contenido de ácido según laboratorio | [IC media — T de Student](https://www.youtube.com/watch?v=lJ1V3SJRgio) |
| 6 | IC media y varianza: pulsaciones de triatletas (n=40 y n=9) | [IC para la varianza (chi²)](https://www.youtube.com/watch?v=RmFOZOOJ6_Q) |
| 7 | IC media T: recalcular con otro nivel de confianza | [IC media — T de Student](https://www.youtube.com/watch?v=lJ1V3SJRgio) |
| 8 | IC media y desviación estándar: tiempo de reacción de nadadores | [IC para la varianza (chi²)](https://www.youtube.com/watch?v=RmFOZOOJ6_Q) |
| 9* | IC para θ en Uniforme[0,θ]: dos formas, comparar longitud | [IC media — σ conocido](https://www.youtube.com/watch?v=91gR7Up9LZc) |

### Guía 7 — Pruebas de hipótesis (una muestra)

| Ej | Descripción | Video |
|---|---|---|
| 1 | Prueba Z bilateral: calibración de balanza, error tipo I y II | [Prueba de hipótesis — media, Z](https://www.youtube.com/watch?v=RS5F_bhNugw) |
| 2 | Nivel de significación desde la región de rechazo dada | [Prueba de hipótesis — media, Z](https://www.youtube.com/watch?v=RS5F_bhNugw) |
| 3 | Prueba Z bilateral: punto de fusión de aceite, error tipo II | [Prueba de hipótesis — media, Z](https://www.youtube.com/watch?v=RS5F_bhNugw) |
| 4 | Comparar la prueba de hipótesis con el IC del ej. 5 de G6 | [Prueba de hipótesis — media, Z](https://www.youtube.com/watch?v=RS5F_bhNugw) |
| 5 | Prueba unilateral: tiempo de escape de trabajadores petroleros | [Prueba de hipótesis — media, T](https://www.youtube.com/watch?v=p6n7d2ZLAxg) |
| 6 | Prueba n≥40: expansión lateral de una aleación, error tipo II | [Prueba de hipótesis — media, Z](https://www.youtube.com/watch?v=RS5F_bhNugw) |
| 7 | Prueba t bilateral: diámetro de ruedas, distintos casos de tobs | [Prueba de hipótesis — media, T](https://www.youtube.com/watch?v=p6n7d2ZLAxg) |
| 8 | Prueba t unilateral: desgaste de un eje, error tipo II | [Prueba de hipótesis — media, T](https://www.youtube.com/watch?v=p6n7d2ZLAxg) |
| 9 | Prueba t: contenido de sodio en galletas (norma CAA) | [Prueba de hipótesis — media, T](https://www.youtube.com/watch?v=p6n7d2ZLAxg) |
| 10 | Prueba t bilateral + IC: lecturas de radón | [Prueba de hipótesis — media, T](https://www.youtube.com/watch?v=p6n7d2ZLAxg) |
| 11 | Prueba de proporción: preferencia entre dos empresas de cable | [Prueba de hipótesis — proporción](https://www.youtube.com/watch?v=EsTm9MGZacI) |
| 12 | Prueba de proporción: donantes de sangre tipo A | [Prueba de hipótesis — proporción](https://www.youtube.com/watch?v=EsTm9MGZacI) |
| 13 | Prueba de proporción (p-valor): robots vs. humanos ensamblando cables | [p-valor en pruebas de hipótesis](https://www.youtube.com/watch?v=47vZXLESRWc) |
| 14 | Comparar p-valor con distintos niveles de significación (6 pares) | [p-valor en pruebas de hipótesis](https://www.youtube.com/watch?v=47vZXLESRWc) |
| 15 | Calcular p-valor con estadístico Z, distintas alternativas | [p-valor en pruebas de hipótesis](https://www.youtube.com/watch?v=47vZXLESRWc) |
| 16 | Acotar p-valor: ganancia de peso de terneros con hormonas | [p-valor en pruebas de hipótesis](https://www.youtube.com/watch?v=47vZXLESRWc) |
| 17 | Acotar p-valor con estadístico T, distintos casos | [Prueba de hipótesis — media, T](https://www.youtube.com/watch?v=p6n7d2ZLAxg) |

### Guía 8 — Pruebas de hipótesis (dos muestras)

| Ej | Descripción | Video |
|---|---|---|
| 1 | Síndrome de Raynaud: prueba unilateral, σ1 y σ2 conocidos | [PH diferencia de medias — indep.](https://www.youtube.com/watch?v=3Rozok2NjNY) |
| 2 | Fuerza de unión de espigas de madera: prueba unilateral, σ conocidos | [PH diferencia de medias — indep.](https://www.youtube.com/watch?v=3Rozok2NjNY) |
| 3 | Calcio en suero con/sin vitamina D: varianzas iguales desconocidas | [PH diferencia de medias — varianzas desiguales](https://www.youtube.com/watch?v=mSKZCstzNOU) |
| 4 | Creatinina medida con dos métodos (A y B) — muestras apareadas | [PH diferencia de medias — apareadas](https://www.youtube.com/watch?v=_4iR54x3s4I) |
| 5 | Glóbulos blancos: infectados vs. sanos, prueba unilateral | [PH diferencia de medias — varianzas desiguales](https://www.youtube.com/watch?v=mSKZCstzNOU) |
| 6 | Frecuencia cardíaca antes/después de un experimento — apareada | [PH diferencia de medias — apareadas](https://www.youtube.com/watch?v=_4iR54x3s4I) |
| 7 | Carboxihemoglobina en fumadores vs. no fumadores — muestras grandes | [PH diferencia de medias — indep.](https://www.youtube.com/watch?v=3Rozok2NjNY) |
| 8 | Niveles de DDE en cáncer de mama — apareada, n grande | [PH diferencia de medias — apareadas](https://www.youtube.com/watch?v=_4iR54x3s4I) |

---

## Reparto semanal de materias (4 materias)

| Día | Materia(s) |
|---|---|
| Lunes (día completo, sin clase) | **PyE y Lógica** |
| Martes (clase 9-13 PyE + 14-18 Álgebra, noche libre) | AED2 |
| Miércoles (clase 9-13 Lógica, tarde libre) | Álgebra |
| Jueves (clase 9-13 PyE + 14-18 Álgebra, noche libre) | Lógica |
| Viernes | Libre — sin materia |
| Sábado | Lógica y Álgebra (refuerzo) |
| Domingo | **PyE y AED2** (refuerzo) |

→ PyE mantiene **Lunes y Domingo** como días fuertes de ejercicios/INV.

## Cronograma día por día

> Se muestran TODOS los días de la semana para que se vea completo — los días que no son de PyE (Martes, Miércoles, Jueves, Viernes, Sábado) solo indican qué materia va ahí, sin detalle (ese detalle vive en el plan de esa materia, no en este archivo). INV obligatoria antes de cada guía nueva de PyE. Ejercicios con * quedan como repaso para el parcial.

### Rumbo al Parcial 1 — 29 Septiembre (G1 a G4, 69 ejercicios)

> Ritmo real: Lunes y Domingo ~4h de PyE cada uno (~6 ejercicios); Martes y Jueves 2h de práctico dentro de la cursada (~3 ejercicios); Miércoles, Viernes y Sábado NO son días de PyE.

| Fecha | Día | Contenido |
|---|---|---|
| ~~Sáb 15 Ago~~ | ~~Sáb~~ | ~~Lógica y Álgebra~~ — **PERDIDO** |
| ~~Dom 16 Ago~~ | ~~Dom~~ | **PERDIDO** (imprevisto familiar) |
| ~~Lun 17 Ago~~ | ~~Lun~~ | **PERDIDO** |
| Mar 18 Ago | Mar | **PyE** — INV-01 · **G1 ej. 1-6** *(hecho — pero se retoma desde ej.4 el domingo para afianzar)* |
| ~~Jue 20 Ago~~ | ~~Jue~~ | **PERDIDO** (gripe) |
| Vie 21 Ago | Vie | Libre — sin materia |
| Sáb 22 Ago | Sáb | Lógica y Álgebra |
| ~~Mar 25 Ago~~ | ~~Mar~~ | **No se avanzó** (semana dedicada a Lógica para el TP) |
| Mié 26 Ago | Mié | Álgebra (no es día de PyE hoy) |
| ~~Jue 27 Ago~~ | ~~Jue~~ | Libre (paro no docente) |
| Vie 28 Ago | Vie | Álgebra (día de sprint — sin PyE) |
| Sáb 29 Ago | Sáb | Lógica (día de sprint — sin PyE) |
| Dom 30 Ago | Dom | **PyE** (8h — sprint) — **G1 ej. 4-15**, retomando desde el 4 para afianzar |
| Lun 31 Ago | Lun | AyED2 (día de sprint — sin PyE) |
| Mar 1 Sep → Mar 29 Sep | — | Retoma el cronograma semanal normal (Mar/Jue/Dom/Lun) desde G1 ej. 16 en adelante — se detalla cuando se confirme el avance real del domingo. |
| **Mar 29 Sep** | Mar | **FINAL PARCIAL 1 — sin sesión** |

> **Restart en G1 ej.4:** aunque ya se había llegado hasta el ej.6, se decidió retomar desde el ej.4 para afianzar mejor el contenido, en vez de seguir avanzando sin base sólida. El domingo 30 es el día de sprint dedicado a PyE (8h) dentro de la semana Vie=Álgebra / Sáb=Lógica / Dom=PyE / Lun=AyED2. Con el Parcial 1 confirmado el 29/9, sigue habiendo margen amplio aun con el restart.

#### Detalle día por día — próximas sesiones
**Mar 18 Ago** *(práctico, 2h — INV-01 + ejercicios, llegó hasta el ej. 6)* — G1 ej. 1, 2, 3, 4, 5, 6
* *Ej 1* — Biblioteca: listar resultados posibles, eventos A/B/C, uniones e intersecciones — 🎥 "Experimento Aleatorio, Espacio Muestral, Evento o Suceso y Probabilidades" — https://www.youtube.com/watch?v=fTIS83G7aC8
* *Ej 2* — Demostrar P(B−A)=P(B)−P(A) si A⊆B; relación P(A), P(A∩B), P(A∪B) — 🎥 "Demostración. Teoremas de Probabilidad: Vacío, Unión y Complemento" — 
https://www.youtube.com/watch?v=nDl0mhVkNeM
* *Ej 3* — Licitaciones: uniones e intersecciones de 3 eventos — 🎥 "Probabilidades de 3 eventos" — https://www.youtube.com/watch?v=ipqWoW4yqik
* *Ej 4* — Asignación de contratos a empresas: conteo y probabilidad — 🎥 "Técnicas de conteo — ejercicios resueltos" — https://www.youtube.com/watch?v=v3TFHZsqhME
* *Ej 5* — Colectivos con grietas: selección de muestra sin reposición — 🎥 "Probabilidad, permutaciones y combinaciones — ejercicios resueltos" — 
https://www.youtube.com/watch?v=lNQIT9Hir5I
* *Ej 6* — Comisión de 2 entre 5 miembros: combinatoria + años de experiencia — 🎥 "Permutaciones y Combinaciones — Ejercicios Resueltos Nivel 1" — 
https://www.youtube.com/watch?v=QXO3u6Ak4rU

**Dom 30 Ago** *(8h — sprint, retoma desde ej.4 para afianzar)* — G1 ej. 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15
* *Ej 4* — Asignación de contratos a empresas (conteo + probabilidad) — 🎥 "Técnicas de conteo — ejercicios resueltos" — https://www.youtube.com/watch?v=v3TFHZsqhME
* *Ej 5* — Colectivos con grietas: selección de muestra sin reposición — 🎥 "Probabilidad, permutaciones y combinaciones — ejercicios" — https://www.youtube.com/watch?v=lNQIT9Hir5I
* *Ej 6* — Comisión de 2 entre 5 miembros: combinatoria + años de experiencia — 🎥 "Permutaciones y combinaciones — Nivel 1" — https://www.youtube.com/watch?v=QXO3u6Ak4rU
* *Ej 7* — Reuniones ordenadas con 8 ayudantes: permutaciones — 🎥 "Variaciones, combinaciones, permutaciones — Nivel 1" — https://www.youtube.com/watch?v=ynxsVxVZ9Vw
* *Ej 8* — Cubos entre dos cajas: extracción secuencial — 🎥 "Bayes — problema 3 resuelto" — https://www.youtube.com/watch?v=850a--CribU
* *Ej 9* — Tabla de camisas por talle/modelo/manga: conjunta y condicional desde tabla — 🎥 "Teorema de Bayes — ejercicios resueltos" — https://www.youtube.com/watch?v=ENiTI9Rgs-c
* *Ej 10* — Demostraciones de propiedades de probabilidad condicional — 🎥 "Teorema de Bayes — ejercicios resueltos (selectividad)" — https://www.youtube.com/watch?v=G_4k4qxZRP4
* *Ej 11* — Prueba diagnóstica de enfermedad: Bayes con falsos +/− — 🎥 "Teorema de Bayes — probabilidades, ejercicios resueltos" — https://www.youtube.com/watch?v=CP4ToX5Tyvw
* *Ej 12* — Demostrar independencia de eventos complementarios — 🎥 "Eventos independientes — ejercicios resueltos" — https://www.youtube.com/watch?v=Ny8NBX7ZLcw
* *Ej 13* — Tablas de madera sin reposición: ¿A y B independientes? — 🎥 "Sucesos independientes — ejercicios resueltos" — https://www.youtube.com/watch?v=_vl-2RsrpgQ
* *Ej 14* — Reparto de 52 cartas entre 4 jugadores — 🎥 "Permutaciones y combinaciones — Nivel 2A" — https://www.youtube.com/watch?v=ns7uwSVPLJk
* *Ej 15* — Leucoplasia oral: fumar y alcohol, ¿independientes? — 🎥 "Eventos dependientes e independientes — fácil" — https://www.youtube.com/watch?v=wOwwPD-O5sY

### Rumbo al Parcial 2 — 10 Noviembre (G5 a G8, 44 ejercicios)

| Fecha | Día | Contenido |
|---|---|---|
| Mié 23 Sep | Mié | Álgebra |
| Jue 24 Sep | Jue | Lógica |
| Vie 25 Sep | Vie | Libre — sin materia |
| Sáb 26 Sep | Sáb | Lógica y Álgebra |
| Dom 27 Sep | Dom | **PyE** — Descanso post-parcial (no forzar) |
| Lun 28 Sep | Lun | **PyE** (+ Lógica) — INV-06: estimadores, momentos, MV · **G5 ej. 1–6** |
| Mar 29 Sep | Mar | AED2 |
| Mié 30 Sep | Mié | Álgebra |
| Jue 1 Oct | Jue | Lógica |
| Vie 2 Oct | Vie | Libre — sin materia |
| Sáb 3 Oct | Sáb | Lógica y Álgebra |
| Dom 4 Oct | Dom | **PyE** — **G5 ej. 7–10** (cierra Guía 5) · INV-07: IC (Z/T, chi², proporciones) · **G6 ej. 1–3** |
| Lun 5 Oct | Lun | **PyE** (+ Lógica) — **G6 ej. 4–9** (cierra Guía 6) |
| Mar 6 Oct | Mar | AED2 |
| Mié 7 Oct | Mié | Álgebra |
| Jue 8 Oct | Jue | Lógica |
| Vie 9 Oct | Vie | Libre — sin materia |
| Sáb 10 Oct | Sáb | Lógica y Álgebra |
| Dom 11 Oct | Dom | **PyE** — INV-08: pruebas de hipótesis, p-valor, error I/II · **G7 ej. 1–6** |
| Lun 12 Oct | Lun | **PyE** (+ Lógica) — **G7 ej. 7–12** |
| Mar 13 Oct | Mar | AED2 |
| Mié 14 Oct | Mié | Álgebra |
| Jue 15 Oct | Jue | Lógica |
| Vie 16 Oct | Vie | Libre — sin materia |
| Sáb 17 Oct | Sáb | Lógica y Álgebra |
| Dom 18 Oct | Dom | **PyE** — **G7 ej. 13–17** (cierra Guía 7) · INV-09: dos muestras (indep./apareadas) · **G8 ej. 1–2** |
| Lun 19 Oct | Lun | **PyE** (+ Lógica) — **G8 ej. 3–8** (cierra Guía 8 — temario completo del parcial listo) |
| Mar 20 Oct | Mar | AED2 |
| Mié 21 Oct | Mié | Álgebra |
| Jue 22 Oct | Jue | Lógica |
| Vie 23 Oct | Vie | Libre — sin materia |
| Sáb 24 Oct | Sáb | Lógica y Álgebra |
| Dom 25 Oct | Dom | **PyE** — Repaso general G5–G6 |
| Lun 26 Oct | Lun | **PyE** (+ Lógica) — Repaso general G7–G8 |
| Mar 27 Oct | Mar | AED2 |
| Mié 28 Oct | Mié | Álgebra |
| Jue 29 Oct | Jue | Lógica |
| Vie 30 Oct | Vie | Libre — sin materia |
| Sáb 31 Oct | Sáb | Lógica y Álgebra |
| Dom 1 Nov | Dom | **PyE** — Repaso + parciales viejos |
| Lun 2 Nov | Lun | **PyE** (+ Lógica) — Repaso + parciales viejos |
| Mar 3 Nov | Mar | AED2 |
| Mié 4 Nov | Mié | Álgebra |
| Jue 5 Nov | Jue | Lógica |
| Vie 6 Nov | Vie | Libre — sin materia |
| Sáb 7 Nov | Sáb | Lógica y Álgebra |
| Dom 8 Nov | Dom | **PyE** — Repaso final, SR completo, fórmulas |
| Lun 9 Nov | Lun | **PyE** (+ Lógica) — Repaso final, copiar y repasar pizarrón |
| **Mar 10 Nov** | Mar | **FINAL PARCIAL 2 — sin sesión** |

---

## Hojas de investigación PyE

> Una hoja por tema. Fuente: Devore + apuntes de clase + búsqueda web.

- [ ] HI-PyE-01: Axiomas, técnicas de conteo, probabilidad condicional y Bayes
- [ ] HI-PyE-02: Variables aleatorias discretas — fmp, fda, esperanza, varianza
- [ ] HI-PyE-03: Distribuciones discretas — tabla comparativa (Binomial, Poisson, Hipergeom., Binomial Neg.)
- [ ] HI-PyE-04: Variables aleatorias continuas — fdp, fda, Normal, Exponencial, otras
- [ ] HI-PyE-05: Distribuciones conjuntas, covarianza, correlación, TLC
- [ ] HI-PyE-06: Estimadores — insesgado, método de momentos, máxima verosimilitud
- [ ] HI-PyE-07: Intervalos de confianza — Z vs T, chi-cuadrado, proporciones
- [ ] HI-PyE-08: Pruebas de hipótesis — estructura, p-valor, errores tipo I y II
- [ ] HI-PyE-09: Pruebas dos muestras — independientes vs apareadas

---

## Notas del método

- **Sprint post-TP (26-30/8):** decidió retomar desde G1 ej.4 (en vez de seguir desde el 7) para afianzar mejor la base, tras sentir que no había aprendido bien esos ejercicios la primera vez. El martes 25 no se avanzó nada (semana dedicada a Lógica para el TP sorpresa). Jueves 27 es paro no docente (libre). El domingo 30 es el día de sprint dedicado a PyE (8h) dentro de la semana Vie=Álgebra / Sáb=Lógica / Dom=PyE / Lun=AyED2.
- **Corrección de fecha:** el Parcial 1 es el **29 de septiembre**, no el 22.
- **Corrida del 22/8 (gripe):** se perdió el Jue 20 por gripe.
- **Corrida anterior (17/8):** Sáb 15, Dom 16 y Lun 17 se perdieron por un imprevisto familiar.

- Recursada a full profundidad: no se asume nada previo, cada guía nueva arranca con INV completa.
- INV → ejercicios → SR es el ciclo completo para cada guía.
- SR: caja de zapatos con compartimento propio de PyE.
- Cuando un ejercicio no sale: volver a la hoja de investigación, identificar qué fórmula o concepto falta.
- Ejercicios marcados con * quedan como repaso para el parcial (no son prioridad en la primera pasada).
- Practicar siempre concluir en palabras en los ejercicios de pruebas de hipótesis e IC, no solo calcular.
- El ritmo semanal asumido arriba es un punto de partida — ajustar según cómo venga el resto de las materias del cuatrimestre.