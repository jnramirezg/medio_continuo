# Taller de aplicación: Interpretación de gráficos modelado de estructuras en tensión/deformación plana utilizando un software profesional

## Introducción

Se busca contrastar la teoría aprendida y la práctica mediante el uso de un software profesional de análisis estructural, se requiere hacer el análisis de los desplazamientos, diagramas de esfuerzo, deformación, esfuerzos principales, esfuerzos de von Mises, esfuerzos de Tresca (o en su defecto el esfuerzo cortante máximo $\tau_{max}$) de una estructura que se pueda modelar en **tensión plana** o **deformación plana**. 

Se espera que el estudiante explore, comente, discuta los conceptos aprendidos en clase, los conceptos nuevos vistos en el software y que proponga soluciones a los problemas propuestos.

El trabajo cuenta con un componente *individual* y uno *grupal*. Los grupos serán de máximo cuatro (3) estudiante.

| Actividad                                                                   | Fecha límite                    |
| ---                                                                         | ---                             |
| Creación de aula de [GOOGLE CLASSROOM](https://classroom.google.com/)       | viernes 28 de octubre de 2022 a las 23:59h   |
| Definición de modelo, software y grupo                                      | domingo 13 de noviembre de 2022 a las 23:59h |
| Entrega de trabajo individual (**<font color='green'>+3.9</font>**)         | Lunes 28 de noviembre de 2022 a las 23:59h |
| Entrega de trabajo grupal (**<font color='green'>+2.1</font>**)             | Martes 29 de noviembre de 2022 a las 23:59h   |

* El taller opcional será calificado hasta **<font color='green'>+6.0</font>** y habrá algunas *penalizaciones*.

* Se creará un salón en [GOOGLE CLASSROOM](https://classroom.google.com/) donde los estudiantes harán sus entregas. Los estudiantes serán añadidos a la plataforma el viernes 28 de octubre de 2022.


## Problema propuesto

* Se debe analizar mediante un programa profesional un sólido (estructura simple) por **tensión plana** o **deformación plana** (que se pueda modelar).

* Los integrantes de un mismo grupo deberán modelar el mismo sólido bajo la misma configuración de carga y propiedades constitutivas, y será único del grupo, todos los grupos deben tener sólidos y configuraciones diferentes (**El profesor aceptará o no el sólido a modelar**). 

* En un archivo de GOOGLE SLIDES, especificado en el GOOGLE CLASSROOM, subirán el esquema o la foto de la estructura que analizarán. La estructura debe estar hecha de un material isótropo u ortótropo (es su decisión); las propiedades del material deberán sacarlas de internet y referenciarlas en sus respectivos trabajos.

### Sobre el software

Absolutamente todos los estudiantes del salón deberán usar un software diferente, y entre los estudiantes de un mismo grupo no deben haber programas de la misma casa, es decir, que en un mismo grupo no pueden haber estudiantes empleando **SAP2000** y **ETABS**, ya que ambos pertenecen a la casa CSI.

### Notificación

Una vez los estudiantes sean añadidos al salón de GOOGLE CLASSROOM, y la información sea publicada, podrán comenzar a registrar el software a utilizar. Si registran un software se asume que harán el trabajo, así que sean consientes de que si registran un software pero luego no hacen nada, le están quitando la oportunidad a alguien más de emplear dicho programa.

Habrá plazo hasta el **domingo 13 de noviembre de 2022 a las 11:59 p.m.** para que los estudiantes concreten el software a emplear y su modelo de estudio, y para la conformación de los grupos. Luego de esta fecha, no se aceptarán modificaciones.

## Se solicita
* Explicar detalladamente como se modelaron las condiciones de frontera (condiciones de apoyo, cargas).

* Calcular las reacciones en los apoyos.

* Hacer el cálculo de los diagramas de esfuerzo, deformación, esfuerzos principales con sus respectivas inclinaciones, esfuerzos de von Mises, esfuerzos de Tresca (el esfuerzo cortante máximo τₘₐₓ), desplazamientos y rotaciones. Si su programa no puede graficar lo anteriormente pedido, debería cambiar de programa, ya que podría perder la oportunidad de contabilizar algunos puntos.

* **TRABAJO INDIVIDUAL**: cada integrante del grupo debe hacer los dos videos:
  * VIDEO 1 (máximo 15 minutos): en este video se debe explicar en detalle el modelado de la estructura escogida. Se deben mostrar los resultados sin interpretarlos. Se recomienda que el estudiante explore muy bien todas las funcionalidades del programa para la presentación de resultados (posprocesado). 
  * VIDEO 2 (máximo 20 minutos): en este video se debe hacer una reseña crítica de las capacidades teóricas y las hipótesis fundamentales que hace el programa en cuanto al **ANÁLISIS DE ESTRUCTURAS EN TENSIÓN/DEFORMACIÓN PLANA** (es decir, en cuanto a la matemática interna para el cálculo de desplazamientos, esfuerzos y deformaciones). OJO: no es mostrar como se utiliza el software, sino más mirar los manuales de referencia y mostrar que teorías, hipótesis, suposiciones, capacidades y limitaciones que tiene el programa escogido y que se utilizaron para calcular la estructura. Entregar, adicionalmente, el archivo PDF utilizado en la presentación de este video. Se sugiere para la presentación tomar capturas de pantalla de los manuales de referencia del programa en cuestión. OJO: no confunda esto con la información comercial. Lo que se está solicitando está dentro de los manuales de referencia.
  
    Algunos ejemplos de buenos análisis son:
     * STRUSOFT FEM-DESIGN (análisis de losas): https://www.youtube.com/watch?v=xxPzgIl-mEg
     * MIDAS GEN (análisis de vigas): https://www.youtube.com/watch?v=p06pnzg2ZPg
  * En cada uno de los videos incluir una ventana pequeña en una de las esquinas donde se vea usted hablando sobre el software.
  * El video se debe subir a GOOGLE CLASSROOM, no a YouTube.

* **TRABAJO GRUPAL**: presentar un informe escrito que contenga el análisis de los resultados. Recuerde explicar detalladamente como varían las cantidades en el espacio, donde están las cantidades máximas y mínimas, como se relacionan unas gráficas con otras, etc. No es solo ubicar donde están los colores, o los máximos y los mínimos, sino decir, **por qué razón se produce esa coloración**, entendiendo como la estructura está cargada, está apoyada, se deforma, etc. Se sugiere [**este (descargue archivo .PDF)**](https://github.com/diegoandresalvarez/solidos/blob/master/talleres/solidos1/ejemplo_analisis_graficos.pdf) formato para presentar los resultados. En este informe se debe realizar la comparación de los resultados de los programas utilizados en su grupo, en caso que haya decidido hacer este trabajo grupalmente.

  NOTA 1: recuerde que se está evaluando el análisis de resultados. Por ejemplo con γxy: ¿qué quiere decir esta deformación? ¿cómo se está comportando en este punto la estructura dado ese valor de γxy? ¿por qué razón se produce? No es solo ubicar los máximos y los mínimos de dicha cantidad.

  NOTA 2: extensión máxima del informe 25 páginas. Incluya en el informe las gráficas obtenidas por todos los integrantes del grupo.

  NOTA 3: en ocasiones, cuando se tienen puntos de singularidad, esos valores son tan altos, que terminan opacando los colores en la estructura, mostrándolos como uno solo. En este caso, se sugiere usar una opción del software que limita los colores a mostrar a un rango. 

  NOTA 4: suba este informe a GOOGLE CLASSROOM en formato PDF.


* Se solicita subir todos los archivos asociados al trabajo (.XLSX, .PDF, .MP4, .MKV, etc) directamente a GOOGLE CLASSROOM. Por favor no los empaquete en un archivo .ZIP o .RAR.

* Active en el software de captura de pantalla la opción para ver el ratón.

Se espera que cada uno lea a fondo el manual del usuario del software. No se queden con los videos de YouTube. En el manual del usuario generalmente existe información importante sobre las hipótesis de modelado que hace cada software.

Se sugiere aprender a manejar un programa de edición de videos. Esto les facilitará mucho su realización.

## Consejos
* Muy probablemente usted utilice un programa basado en el método de los elementos finitos para hacer su análisis. En tal caso, se sugiere mirar [estas](https://github.com/diegoandresalvarez/elementosfinitos/blob/master/diapositivas/05e_generando_una_buena_malla.pdf) diapositivas, la cual contiene consejos de como hacer un buen mallado.

* En caso que requiera un programa de elementos finitos, la siguiente lista puede ser útil: http://feacompare.com/ Tenga en cuenta que muchos programas pagos tienen versiones de prueba que pueden ser de utilidad para el presente taller.

## Criterios de evaluación
NOTA MAXIMA 6.0. Tenga en cuenta que la nota tiene un componente individual (los videos) y otro grupal (el informe escrito).

* **VIDEO 1**: Modelado de la estructura (30% = 1.8)
  * **+0.1** Modeló adecuadamente las condiciones de frontera
  * **+0.1** Calculó las reacciones en los apoyos
  * **+0.1** Calculó el diagrama de los desplazamientos y de la estructura deformada
  * **+0.1** Calculó los diagramas de las deformaciones ɛx, ɛy, ɛz, γxy *y* los esfuerzos σx, σy, σz, τxy (si falta alguno de estos gráficos, si se grafican sin curvas de nivel o sin escalas de colores discretas, y si no se ubican los máximos y los mínimos **no** se otorgarán puntos).
  * **+0.1** Calculó el diagrama de las rotaciones.
  * **+0.1** Calculó el diagrama de las dilataciones cúbicas.
  * **+0.2** Calculó el diagrama de esfuerzos σ1, σ2 *y* sus respectivas inclinaciones (los diagramas de σ1 y σ2 sin sus respectivas inclinaciones no otorgarán puntos)
  * **+0.1** Calculó el diagrama de esfuerzos de von Mises y/o Tresca y/o τₘₐₓ 
  * **+0.2** Usa el consejo de como hacer buenas mallas
  * **+0.7** Expone adecuadamente las capacidades del software en cuanto a la presentación de resultados (postprocesado). Se requiere para este punto que usted explore las opciones que le de el software para la presentación de resultados y gráficos: por curvas de nivel, rangos de colores, diferentes diagramas, cortes en las secciones que muestren como varían las cantidades, opciones para integrar los esfuerzos y obtener las fuerzas cortantes y los momentos flectores equivalentes, etc.
  NOTA: si usted usa un software que no calcula las cantidades anteriormente solicitadas, podría perder puntos. En tal caso, se sugiere cambiar de programa.

* **VIDEO 2 + PDF PRESENTACION**: Reseña de las capacidades/hipótesis/suposiciones/limitaciones del software (35% = 2.1)
  * **+0.7** Hace un recuento de las teorías que soporta el programa, haciendo recortes del manual de referencia.
  * **+0.7** Intenta entender las fórmulas del manual de referencia al verificar su equivalencia con las que se vieron en clase (en ocasiones toca convertir esas ecuaciones a nuestra nomenclatura para poder entenderlas, ya que los programas son usualmente mucho más generales y soportan más casos que los vistos en clase) y/o usan una nomenclatura diferente.
  * **+0.7** Explica las ventajas/capacidades y limitaciones/suposiciones que hace el programa en cuanto al análisis estructural?

* **INFORME ESCRITO**: Análisis de resultados (35% = 2.1): ¿interpreta gráficos? ¿Analiza como varían las cantidades en el espacio? ¿Ubica máximos y mínimos? ¿Relaciona gráficos entre sí?
  * **+0.4** Diagramas de los desplazamientos del sólido y las deformaciones ɛx, ɛy, ɛz, γxy, dilatación cúbica, rotación. 
  * **+0.4** Diagramas de esfuerzos σx, σy, σz, τxy. 
  * **+0.2** Diagramas de esfuerzos σ1, σ2 con sus inclinaciones (si no tiene las inclinaciones θ₁ y θ₂, se tendrá un 0.0 en este punto). 
  * **+0.2** Sugiere como se podría poner el refuerzo óptimo al interior de la estructura asumiendo que esta es de concreto reforzado? (si no calculó las inclinaciones θ₁, se tendrá un 0.0 en este punto).
  * **+0.2** Sugiere la forma como la estructura se agrieta, asumiendo que esta es de concreto reforzado? (si no calculó las inclinaciones θ₂, se tendrá un 0.0 en este punto).
  * **+0.3** Diagramas de esfuerzos de von Mises, de Tresca y/o τₘₐₓ
  * **+0.4** Reacciones en los apoyos, fuerzas puntuales y momentos flectores equivalentes. Nota. Las fuerzas puntuales y los momentos flectores equivalentes en las reacciones se encuentran usando en el software una opción llamada "Integrate over surface".
  * **+0.5** Si realizan el informe en LaTex.

### Penalizaciones

* **-0.5** Mala calidad en el sonido. Por favor use un micrófono auxiliar (por ejemplo, un manos libres) y evite usar el micrófono del portátil para hacer el video.

* **-1.0** Mala calidad de vídeo. Mínimo 1080p. Recuerde que no tenemos limitación en el almacenamiento en GOOGLE CLASSROOM. En caso que su equipo no sea capaz de hacer videos con resolución 1080p, infórmelo previamente.

* **-1.0** Si modela la estructura como 3D a pesar que es una de tensión/deformación plana. Se debe usar necesariamente la funcionalidad de tensión/deformación plana del programa de elementos finitos.

* **-2.0** Si se sube el video a YouTube. Los videos los debe subir directamente a GOOGLE CLASSROOM.

* **-3.0** Si se usa un software diferente al registrado.

* **-1.0** Si se modela una estructura diferente a la registrada.

* **-1.0** En cada video si no se incluye en el video un recuadro donde se donde se vea usted hablando sobre el software. En caso de que no tenga cámara de video podría utilizar aplicaciones como [DroidCam](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam) o [DroidCam OBS](https://play.google.com/store/apps/details?id=com.dev47apps.obsdroidcam), con los cuales se puede utilizar su celular como cámara para el computador.

* La califiación grupal será 0.0 si el grupo que entrega no coincide con el consignado en el classroom en la fecha límite. Tampoco serán recibidos trabajos individuales de estudiantes que no se inscribieron en el classroom en las fechas límites establecidas.

* **-0.5** en la parte correspondiente del trabajo por cada hora de retraso en la entrega.










