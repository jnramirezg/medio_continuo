# Taller de aplicación de conocimientos acumulados

Con este taller se pretende evaluar los conocimientos adquiridos de las secciones 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 4.10, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9 y 9.10 del main.pdf. A partir de una aplicación de la teoría de Euler-Bernoulli se busca reforzar los conocimiento previos a mecánica de sólidos y todos adquiridos hasta el momento en la asignatura.

## Condiciones generales

- Calificación máxima 6.0.
- Su calificación será el 15% de la asignatura, es decir, el examen 5 solo será del 15% evaluando los temas vistos del capítulo 5.
- Con esta modificación, la forma de calcular el beneficio del taller de aplicación (software) deberá tener en cuenta todas las combinaciones de exámenes que sumen entre 30% y 35%.
- El número de ejercicio asignado corresponde al consignado por cada estudiante en este [archivo](https://docs.google.com/spreadsheets/d/10dXXVYqDi_RnkPKeYG-pzM-5e6u3kO7PCjtUGvMa34c/edit#gid=0).
- El modelo de viga que le corresponde a cada estudiante fue subido al classroom.
- El taller está disponible a partir de las 00:00h del 26 de noviembre de 2022.
- Fecha límite de entrega: martes 06 de diciembre de 2022 a las 23:59h.
- Se solicita que todos los cálculos sean detallados, que no estén fuera de contexto. Cada paso debe ir acompañado de un texto que soporte por qué se hacen las cosas.
- La parte procedimental y las respuestas se pueden presentar a mano (en hoja blanca) o hechas en computador siempre y cuando sean presentadas las ecuaciones con la notación real.

## Estructura principal del taller
Los pasos del 1 al 6 deberán realizarse con todas las variables simbólicas (no se puede remplazar ninguna variable). En los procedimientos se pueden hacer usando cualquier herramienta adicional, pero en el trabajo deberá quedar consignado el paso a paso con su respectiva explicación.

### A. Análisis
Dada una viga con sección transversal constante, se deben hacer dos análisis:
- Con módulo de elasticidad costante para toda la viga, $E$, realizando todos los cálculos, análisis y gráficas en términos de las variables simbólicas.
- Con módulo de elasticidad variable de forma lineal realizando todos los cálculos, análisis y gráficas en términos de las variables simbólicas. Suponer que la viga tiene un módulo de elasticidad $E_1$ a la izquieda y $E_2$ a la derecha (variación lineal). Tener en cuenta que $E_1 < E_2$
1. **Cálculo de reacciones:**
- Cálcular las ecuaciones de todas las reacciones en los apoyos de la viga (mostrar procedimiento y diagramas de cuerpo libre).
2. **Determinación de condiciones de frontera:**
- Definir cuáles son las condiciones de frontera de la ecuación diferencial.
- En las vigas que son descritas con funciones a trozos se debe considerar que $\theta(x)$ por la izquierda es igual $\theta(x)$ por la derecha para un mismo punto.
3. **Cálculo y análisis de la gráfica de cortantes:**
- Hallar la(s) ecuacion(es) que describen $V(x)$.
- Determinar los $V(x)$ máximos y mínimos y sus posiciones $x$.
- Gráficar esquemáticamente $V(x)$ con las concavidades adecuadas y sus puntos característicos.
- ¿Cuál es la interpretación física de un diagrama de cortantes $V(x)$? (concepto visto en estática).
4. **Cálculo y análisis de la gráfica de momentos:**
- Hallar la(s) ecuacion(es) que describen $M(x)$.
- Determinar los $M(x)$ máximos y mínimos y sus posiciones $x$.
- Gráficar esquemáticamente $M(x)$ con las concavidades adecuadas y sus puntos característicos.
- ¿Cuál es la interpretación física de un diagrama de momentos flectores $M(x)$? (concepto visto en estática y m. sólidos).
5. **Cálculo y análisis de la gráfica de giros:**
- Hallar la(s) ecuacion(es) que describen $\theta(x)$.
- Determinar los $\theta(x)$ máximos y mínimos y sus posiciones $x$.
- Gráficar esquemáticamente $\theta(x)$ con las concavidades adecuadas y sus puntos característicos.
6. **Cálculo y análisis de la gráfica de deflexiones:4**
- Hallar la(s) ecuacion(es) que describen $v(x)$.
- Gráficar esquemáticamente $v(x)$ con las concavidades adecuadas y sus puntos característicos.
- Hallar la ecuación de la deflexión máxima $v_{máx}$ en cada luz y su posición $x$. ¿Cuál es la mayor de todas?
- Explicar para cada una de las variables simbólicas cómo modifican las deflexiones máximas. Ejemplo: como $E$ está en el denominador, provoca que la deflexión disminuya proporcionalmente. 
### B. Diseño
Las vigas tienen los siguientes parámetros:
- $L_1=6m$
- $L_2=4m$
- $L=10m$
- $w=-10kN/m$
- $q=-25kN/m$
- $P=- 200kN$
- $P_1 = -100kN$
- $P_2 = - 150kN$
- $q_1=-10kN/m$
- $q_2=-40kN/m$
- $q_3=-20kN/m$
- $f'c=21MPa$

Los pasos del 7 al 16 se realizan adaptando el programa [27- Diseño de concreto](https://github.com/jnramirezg/mecanica_de_solidos/blob/main/codigo/27-diseno_concreto_reforzado.ipynb), pero las respuestas a las preguntas y el análisis deben ir dentro del trabajo en .pdf.

7. **Dimensionamiento de la viga:**
- Se debe "diseñar" las dimensiones de la viga, de tal forma que $b$ y $h$ sean suficientes evitar que la deflexión máxima de la viga sea mayor que $luz-libre/360$ (exigido por los códigos de construcción). Nota: Recuerde que la luz libre es la distancia entre dos apoyos, es decir, hay vigas con varios apoyos; por lo tanto, se debe evaluar varias veces).
- ¿Qué ocurre si se define un valor de $h$ menor que $b$? ¿Es acertado hacer esto desde la ingeniería? ¿Por qué? Explicar el concepto matemático detalladamente.
- Teniendo en cuenta las ecuaciones, en la vida práctica cómo se pueden aumentar la rigidez de la viga (discutir aspectos del material y de la geometría).
8. **Revisión de hipótesis fundamentales:**
- Se debe hacer un análisis del cumplimiento de las hipótesis fundamentales de la teoría EB.
9. **Propiedades:**
- Establecer las propiedades geométricas y elásticas del material.
10. **Gráficas de cortantes, momentos, rotaciones y deflexiones:**
Con los valores reemplazados, usando la librería matplotlib de Python:
- Graficar $V(x)$.
- Graficar $M(x)$.
- Graficar $\theta(x)$.
- Graficar $v(x)$.
11. **Cálculo de esfuerzos:**
- Presentar las ecuaciones.
- ¿Qué hipótesis/restricciones tienen en cuenta estas ecuaciones usadas? 
12. **Cálculo de deformaciones:**
- Presentar las ecuaciones.
- ¿Qué hipótesis/restricciones tienen en cuenta estas ecuaciones usadas? 
13. **Cálculo de esfuerzos y direcciones principales:**
- Presentar las ecuaciones.
- ¿Qué hipótesis/restricciones tienen en cuenta estas ecuaciones usadas? 
14. **Análisis de las gráficas de esfuerzos:**
- Hacer un esquema (a mano) donde se señalen los puntos característicos (máximos, mínimos, valores nulos) de $\sigma_x$.
- Interpretar a partir del concepto físico de esfuerzos los puntos característicos de $\sigma_x$.
- Hacer un esquema (a mano) donde se señalen los puntos característicos (máximos, mínimos, valores nulos) de $\sigma_y$.
- Interpretar a partir del concepto físico de esfuerzos los puntos característicos de $\sigma_y$.
- Hacer un esquema (a mano) donde se señalen los puntos característicos (máximos, mínimos, valores nulos) de $\tau_{xy}$.
- Interpretar a partir del concepto físico de esfuerzos los puntos característicos de $\tau_{xy}$.

15. **Análisis de las gráficas de deformaciones:**
- Hacer un esquema (a mano) donde se señalen los puntos característicos (máximos, mínimos, valores nulos) de $\varepsilon_x$.
- De acuerdo con la ecuación de $\varepsilon_x$ ¿cuál(es) es(son) la(s) variable(s) dominante(s) que genera(n) la forma del gráfico?
- Interpretar a partir del concepto físico de deformaciones los puntos característicos de $\varepsilon_x$.
- Hacer un esquema (a mano) donde se señalen los puntos característicos (máximos, mínimos, valores nulos) de $\varepsilon_y$ y $\varepsilon_z$.
- De acuerdo con la ecuación de $\varepsilon_y$ y $\varepsilon_z$ ¿cuál(es) es(son) la(s) variable(s) dominante(s) que genera(n) la forma del gráfico? ¿Por qué los gráficos de $\varepsilon_y$ y $\varepsilon_z$ son similares?
- Hacer un esquema (a mano) donde se señalen los puntos característicos (máximos, mínimos, valores nulos) de $\gamma_{xy}$.
- De acuerdo con la ecuación de $\varepsilon_y$ ¿cuál(es) es(son) la(s) variable(s) dominante(s) que genera(n) la forma del gráfico?
- Interpretar a partir del concepto físico de deformaciones los puntos característicos de $\gamma_{xy}$.

16. **Análisis de las gráficas de esfuerzos y direcciones principales, y $tau_{máx}$**
- Hacer un esquema (a mano) que muestre el agrietamiento esperado en la viga.
- Hacer un esquema (a mano) que muestre los puntos de probabilidad de falla inicial de la viga.
- ¿Cuál es la interpretación física de $\sigma_1$ y $\theta_1$ en el concreto reforzado?
- ¿Cuál es la interpretación física de $\sigma_2$ y $\theta_2$ en el concreto reforzado?
- ¿Cuál es la interpretación física de $\tau_{máx}$? en el concreto reforzado? En particular para la viga dada ¿qué interpretación genera?
17. **Alternativa de diseño (esquemático):**
- Siguiendo el ejemplo de clase
18. **Diseño convencional (esquemático):**
Siguiendo el ejemplo de clase realizar un diseño esquemático del acero (no poner dimensiones, sino graficar en una escala aproximada) en el que se muestre:
- Las zonas de mayor y menor concentración de flejes.
- Las zonas de mayor y menos concentración de barras longitudinales de acero.
19. **Conclusiones:**
Se deben escribir varias conclusiones generales de la interpretación de los gráficos, ecuaciones y fenómenos físicos. Algunas preguntas orientadoras (obligatorio responder):
- ¿Qué diferencia hay entre $\tau_{máx}$ y $\tau_{xy}$ en un punto $x$.
- ¿Cómo diferenciar una viga estatícamente determinada y una hiperestática?
- ¿Por qué no es importante el signo positivo o negativo de una fuerza cortante o de un esfuerzo cortante?.
- ¿Por qué es importante diferenciar momentos flectores positivos y negativos?
- ¿Por qué el diagrama de momentos $M(x)$ se dibuja invertido? ¿Qué representa?
- ¿Qué relación tiene $M(x)$ con $\sigma_1$ y sus direcciones $\theta_1$? 
- ¿Qué relación tiene $V(x)$ con $\sigma_1$ y sus direcciones $\theta_1$?
- ¿Qué ocurre si se hace $\sigma_y=0$ para toda la viga?
- ¿Cuál es la importancia de las curvas de nivel en los gráficos?

## Archivos requeridos
Los archivos deberán ser subidos al classroom de forma independiente (no comprimidos). No se aceptan trabajos por ningún otro medio.

- Un archivo .pdf con los procedimientos, cálculos y respuestas solicitados. Deberá estar escaneado con buena calidad y completamente legible. 
- Un archivo .ipynb con el notebook correspondiente.
- Se advierte que los procedimientos matemáticos sin contexto ni explicación adecuada serán penalizados drásticamente.

## Bonificaciones
- Si presenta todo el trabajo en formato Latex (incluso todo desarrollado en Jupyter notebook) recibirá una bonificación de [+1.0]. Las gráficas esquemáticas pueden ser fotografías.

## Penalizaciones
- Todo trabajo enviado después de la hora límite recibirá una penalización de **[-0.5]** por cada hora de retraso.
- Si el modelo que analiza y utiliza es diferente al asignado, la calificación será **0.0.**
- **[-1.5]** si presenta el trabajo en hojas que no sean completamente blancas, pues esto dificulta muchísimo la calificación.
