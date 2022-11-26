# Taller de aplicación de conocimientos acumulados

Con este taller se pretende evaluar los conocimientos adquiridos de las secciones 4.4, 4.5, 4.6, 4.7, 4.8, 4.9, 4.10, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 9.7, 9.8, 9.9 y 9.10 del main.pdf. A partir de una aplicación de la teoría de Euler-Bernoulli se busca reforzar los conocimiento previos a mecánica de sólidos y todos adquiridos hasta el momento en la asignatura.

## Condiciones generales

- Calificación máxima 6.0
- Su calificación será el 15% de la asignatura, es decir, el examen 5 solo será del 15% evaluando los temas vistos del capítulo 5.
- Con esta modificación, la forma de calcular el beneficio del taller de aplicación (software) deberá tener en cuenta todas las combinaciones de exámenes que sumen entre 30% y 35%.
- El número de ejercicio asignado corresponde al consignado por cada estudiante en este [archivo](https://docs.google.com/spreadsheets/d/10dXXVYqDi_RnkPKeYG-pzM-5e6u3kO7PCjtUGvMa34c/edit#gid=0)
- El modelo de viga que le corresponde a cada estudiante fue subido al classroom.
- El taller está disponible a partir de las 00:00h del 26 de noviembre de 2022.
- Fecha límite de entrega: martes 06 de diciembre de 2022 a las 23:59h.
- Se solicita que todos los cálculos sean detallados, que no estén fuera de contexto. Cada paso debe ir acompañado de un texto que soporte por qué se hacen las cosas.
- La parte procedimental y las respuestas se pueden presentar a mano (en hoja blanca) o hechas en computador siempre y cuando sean presentadas las ecuaciones con la notación real.

## Estructura principal del taller
Los pasos del 1 al 6 deberán realizarse con todas las variables simbólicas (no se puede remplazar ninguna variable). Los procedimientos se pueden hacer usando cualquier herramienta adicional, pero en el trabajo deberá quedar consignado el paso a paso con su respectiva explicación.

### Análisis
Dada una viga de concreto reforzado, se deben hacer dos análisis:
- Con módulo de elasticidad costante para toda la viga, $E$, realizando todos los cálculos, análisis y gráficas.
- Con módulo de elasticidad variable de forma lineal realizando todos los cálculos, análisis y gráficas en términos de las variables simbólicas. Suponer que el concreto tiene una resistencia $f'c=21MPa$ a la izquieda y $f'c=28MPa$ a la derecha (variación lineal).
1. Cálculo de reacciones y determinación de condiciones de frontera:
2. Cálculo y análisis de la gráfica de cortantes:
3. Cálculo y análisis de la gráfica de momentos:
4. Cálculo y análisis de la gráfica de giros:
5. Cálculo y análisis de la gráfica de deflexiones:

### Diseño
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
7. Dimensionamiento de la viga: 
- Se debe "diseñar" las dimensiones de la viga, de tal forma que $b$ y $h$ sean suficientes evitar que la deflexión máxima de la viga sea mayor que $luz_libre/360$ (exigido por los códigos de construcción). Nota: Recuerde que la luz libre es la distancia entre dos apoyos, es decir, hay vigas con varios apoyos; por lo tanto, se debe evaluar varias veces).
- ¿Qué ocurre si se define un valor de $h$ menor que $b$? ¿Es acertado hacer esto desde la ingeniería? ¿Por qué? Explicar el concepto matemático detalladamente.
- Teniendo en cuenta las ecuaciones, en la vida práctica cómo se pueden aumentar la rigidez de la viga (discutir aspectos del material y de la geometría).
8. Revisión de hipótesis fundamentales: 
- se debe hacer un análisis del cumplimiento de las hipótesis fundamentales de la teoría EB.
9. Propiedades:
10. Gráficas de cortantes, momentos, rotaciones y deflexiones:
11. Cálculo de esfuerzos:
- Presentar las ecuaciones.
- ¿Qué hipótesis/restricciones tienen en cuenta estas ecuaciones usadas? 
12. Cálculo de deformaciones: 
- Presentar las ecuaciones.
- ¿Qué hipótesis/restricciones tienen en cuenta estas ecuaciones usadas? 
13. Cálculo de esfuerzos y direcciones principales:
- Presentar las ecuaciones.
- ¿Qué hipótesis/restricciones tienen en cuenta estas ecuaciones usadas? 
14. Análisis de las gráficas de esfuerzos:
15. Análisis de las gráficas de deformaciones:
16. Análisis de las gráficas de esfuerzos y direcciones principales:
17. Alternativas de diseño (esquemáticas):
18. Diseño convencional (esquemático):
19. Conclusiones:
- ¿Qué diferencia hay entre $tau_{máx}$ y $tau_{xy}$ en un punto $x$.

## Archivos requeridos
Los archivos deberán ser subidos al classroom de forma independiente (no comprimidos). No se aceptan trabajos por ningún otro medio.

- Un archivo .pdf con los procedimientos, cálculos y respuestas solicitados. Deberá estar escaneado con buena calidad y completamente legible. 
- Un archivo .ipynb con el notebook correspondiente.
- Se advierte que los procedimientos matemáticos sin contexto ni explicación adecuada serán penalizados drásticamente.

## Bonificaciones
- Si presenta todo el trabajo en formato Latex (incluso todo desarrollado en Jupyter notebook) recibirá una bonificación de [+1.0].

## Penalizaciones
- Todo trabajo enviado después de la hora límite recibirá una penalización de [-0.5] por cada hora de retraso.
- Si el modelo que analiza y utiliza es diferente al asignado, la calificación será 0.0.
- [-1.5] si presenta el trabajo en hojas que no sean completamente blancas, pues esto dificulta muchísimo la calificación.
