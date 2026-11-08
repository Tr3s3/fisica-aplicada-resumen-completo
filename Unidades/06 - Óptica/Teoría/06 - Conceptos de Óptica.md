---
tags: [fisica-aplicada, teoria, conceptos, optica]
---

# Conceptos de Óptica

**Volver al módulo:** [[Unidades/06 - Óptica/Teoría/06 - Óptica]] · **Fórmulas de consulta:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica]] · **Lectura esencial:** [[Unidades/06 - Óptica/Teoría/06 - Guía breve de Óptica]]

La pregunta que guía esta unidad es: **¿cómo sabemos hacia dónde sale la luz y qué imagen o patrón veremos?** Primero aprenderemos a seguir su recorrido; después, a interpretar imágenes; finalmente, a explicar las franjas que el recorrido de rayos por sí solo no describe.

## Cómo recorrer esta explicación

No hace falta memorizar toda la nota antes de practicar. Trabaja una etapa, explícala con tus palabras y usa sus enlaces para comprobar y aplicar lo aprendido. Si buscas una primera lectura más corta, empieza por la guía breve.

| Etapa | Qué debes poder explicar | Lectura y práctica inmediata |
|---|---|---|
| 1. Elegir la representación | Qué dibuja un rayo y cuándo hace falta considerar la fase | [[#1. Dos maneras de representar la luz\|Sección 1]]; identifica el fenómeno en los enunciados de O1 y O4 |
| 2. Cruzar una interfaz | Índice, frecuencia, normal y cambio de dirección | [[#2. Índice de refracción: por qué se desvía un rayo\|Sección 2]] y [[#3. De Huygens a la ley de Snell\|sección 3]]; [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total\|O4]] |
| 3. Interpretar lo que se ve | Colores dentro de una placa y profundidad aparente | [[#4. Bloques, profundidad aparente y color\|Sección 4]]; O5–O6 de esa familia |
| 4. Decidir si sale luz | Ángulo crítico y geometría de cada cara | [[#5. Reflexión total interna: cuándo la luz queda atrapada\|Sección 5]]; O10–O11 de esa familia |
| 5. Entender una imagen | Reflexión, prolongaciones, espejo plano y movimiento | [[#6. Reflexión, imágenes planas y camino de la luz\|Sección 6]]; [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos\|O7–O9]] |
| 6. Localizar imágenes en espejos | Foco, distancias con signo, aumento y controles | [[#7. Espejos esféricos: de la geometría al foco\|Sección 7]]; [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos\|O12–O15]] |
| 7. Resolver lentes y sistemas | Dos refracciones, fabricante y objeto de la segunda lente | [[#8. Lentes delgadas: dos refracciones y una sola imagen\|Sección 8]]; [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Lentes delgadas y sistemas\|O16–O19]] |
| 8. Explicar franjas | Fase, coherencia, orden y diferencia de camino | [[#9. Doble rendija: de la superposición a las franjas\|Sección 9]]; [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija\|O1–O3]] |

La etapa 8 puede estudiarse después de las secciones 1–2 si quieres practicar primero la doble rendija del modelo 2023. La tabla organiza los prerrequisitos de aprendizaje; la prioridad para un examen concreto depende de su alcance y de los modelos correspondientes.

> [!info] Convenciones para no confundir símbolos
> $v$ es rapidez de la luz en un medio; $f$ significa **frecuencia** en las secciones 2–4 y **distancia focal** en las secciones 7–8. Son magnitudes distintas: la frecuencia se mide en hertz y la focal en unidades de longitud. El contexto y las unidades permiten distinguirlas. En interferencia, $m$ es un entero de orden; en imágenes, $m$ es el aumento. Cada sección vuelve a definir sus símbolos.

## Apoyos visuales y ejemplos de las fuentes

Las figuras del libro y las diapositivas aparecen junto al concepto que explican. Sus pies identifican la página **del PDF** y la figura o el número impreso de diapositiva; ambas numeraciones pueden ser distintas. Los cálculos que las acompañan están reexplicados para esta guía, conservando los datos de la fuente. Son ejemplos de enseñanza; las etiquetas M/R/C corresponden a la práctica de la unidad.

| Para aclarar esta dificultad | Recurso dentro de la lectura |
|---|---|
| Distinguir el avance de la luz de su oscilación | [[#Leer la figura del libro: frentes y rayos\|Frentes y rayos, figura 33.4]] |
| Pasar de longitudes de onda a índice, rapidez y frecuencia | [[#Ejemplo del libro: el mismo láser en aire y en el ojo\|Ejemplo 33.2]] |
| Reconocer la normal y elegir el ángulo | [[#Ejemplo del libro: agua a vidrio, con reflexión y refracción\|Figura 33.11 y ejemplo 33.1]] |
| Entender por qué el agua parece menos profunda | [[#Ejemplo del libro: profundidad real y profundidad aparente\|Figuras 34.26–34.27 y ejemplo 34.7]] |
| Distinguir refracción, caso crítico y reflexión total | [[#Leer la figura del libro: tres regímenes en la misma interfaz\|Diagrama y fotografía, figura 33.13]] |
| Reconocer una imagen virtual y un foco virtual | [[#Leer el esquema de clase: la luz que llega al ojo\|Espejo plano de clase]] y [[#Leer los esquemas de clase: cóncavo y convexo\|espejos esféricos de clase]] |
| Entender los datos de una imagen proyectada | [[#Ejemplo del libro: proyectar una imagen sobre una pared\|Figura 34.15 y ejemplo 34.1]] |
| Predecir la imagen antes de calcular | [[#Leer los casos de la diapositiva: mover el objeto respecto del foco\|Cuatro casos de lente convergente]] |
| Entender la imagen derecha y reducida de una divergente | [[#Leer la diapositiva: lente divergente e imagen virtual\|Construcción de clase para preparar O20]] |
| Asignar signos a los radios de una lente | [[#Ejemplo del libro: dos radios iguales en tamaño y opuestos en signo\|Figura 34.35 y ejemplo 34.8]] |
| Entender de dónde salen las franjas y qué distancia se mide | [[#Leer el montaje del libro: una fuente común y dos caminos\|Experimento de Young]] y [[#Ejemplo del libro: obtener la longitud de onda a partir de una franja\|ejemplo 35.1]] |

Para estudiar una figura: localiza primero las flechas de propagación, identifica qué líneas son prolongaciones, nombra los datos y anticipa el resultado. Después sigue el cálculo y pasa al ejercicio indicado. Si una figura no se lee bien al ancho de la nota, ábrela para ampliarla en Obsidian.

## Herramientas previas para interpretar los dibujos

### Un triángulo permite conectar un ángulo con una distancia

En un triángulo rectángulo, el lado **opuesto** queda enfrente del ángulo elegido; el **adyacente** lo toca y no es la hipotenusa; la **hipotenusa** está enfrente del ángulo recto. Al cambiar el ángulo de referencia cambian los nombres opuesto y adyacente. Las razones son

$$
\sin\theta=\frac{\text{opuesto}}{\text{hipotenusa}},\qquad
\cos\theta=\frac{\text{adyacente}}{\text{hipotenusa}},\qquad
\tan\theta=\frac{\text{opuesto}}{\text{adyacente}}.
$$

Si el espesor vertical de una placa es $e$ y el rayo forma $\theta$ con su normal vertical, el avance horizontal $x$ es el lado opuesto. Así, $\tan\theta=x/e$ y $x=e\tan\theta$. Por ejemplo, $e=2.0\,\mathrm{cm}$ y $\theta=30^\circ$ dan $x=2.0\tan30^\circ\approx1.15\,\mathrm{cm}$. Si el ángulo dado fuese con la cara horizontal, primero usarías su complementario. Este ejemplo de geometría es elaboración del vault y anticipa O5/O22.

Si buscas un ángulo a partir de una razón, usas la función inversa: de $\sin\theta=0.5$ resulta $\theta=\arcsin(0.5)=30^\circ$ en el intervalo físico de incidencia. $\arcsin$ **no** significa $1/\sin$. Trabaja en grados para sustituir los ángulos de los enunciados; cuando deducimos $\sin\theta\approx\theta$ o $\tan\theta\approx\theta$, ese $\theta$ numérico debe estar en radianes.

### Un dibujo de rayos es un mapa, no necesariamente una escala

Una flecha continua describe el sentido de propagación. Una prolongación hacia atrás sirve para localizar de dónde **parece** venir la luz; no describe luz viajando hacia atrás. Antes de sumar o restar distancias, fíjate desde qué elemento se miden. Una distancia firmada negativa informa de la posición o del tipo de objeto/imagen según la convención; su módulo sigue siendo una longitud positiva.

Los triángulos semejantes tienen ángulos correspondientes iguales y lados proporcionales. Esa es la razón por la que dos alturas y dos distancias se vinculan en $|y'/y|=|s'/s|$. Más adelante añadimos los signos para distinguir arriba/abajo y real/virtual. No hace falta medir el dibujo con una regla: el resultado se calcula con los datos y se comprueba con el esquema.

## 1. Dos maneras de representar la luz

### Qué representa un rayo

La luz es una onda electromagnética: sus campos eléctrico y magnético oscilan mientras la perturbación se propaga. Un **rayo** es una línea con flecha que indica la dirección de propagación. En un medio homogéneo e isótropo —propiedades iguales de un lugar a otro y en todas las direcciones— esa línea es recta. No representa el tamaño del haz ni una curva por la que el campo eléctrico oscila.

Un **frente de onda** reúne puntos que están en la misma fase: por ejemplo, todos los que alcanzan a la vez una cresta del campo. En los medios que estudiaremos, los rayos son perpendiculares a esos frentes. Un frente plano tiene rayos paralelos; uno esférico que se expande desde una fuente tiene rayos que se separan.

Seguimos rayos cuando buscamos el ángulo de salida de la luz o la posición de una imagen. Para encontrar la imagen de un punto, seguimos varios rayos que parten de **ese mismo punto**; después repetimos la idea para los demás puntos del objeto.

### Leer la figura del libro: frentes y rayos

![[imagenes/optica-libro-frentes-y-rayos.png|330]]

*Fuente: [capítulo 33](zotero://open-pdf/library/items/9VRFKAHP?page=3), PDF p. 3, figura 33.4 (página impresa 1123). Recorte de los dos casos.*

Las curvas azules representan frentes de igual fase; las flechas violetas, direcciones de avance. En el caso esférico, los rayos se separan desde la fuente. En el plano son paralelos porque las normales a los frentes planos lo son. La separación entre frentes consecutivos equivalentes representa una longitud de onda, cuando el dibujo muestra una sucesión de esos frentes.

El campo oscila mientras la onda avanza: las curvas azules **no son caminos curvos que recorre un rayo**. Este detalle permite entender después por qué un frente puede girar al cruzar una frontera y cambiar la dirección de sus rayos.

### Cuándo necesitamos la onda

Si dos contribuciones luminosas llegan al mismo lugar, sus campos se suman. El resultado depende de si llegan en la misma parte del ciclo o en partes opuestas. Esa comparación se llama **diferencia de fase** y es la base de la interferencia.

Un trazado de rayos puede mostrar por dónde llegan ambas contribuciones, pero no basta para decidir si el punto será brillante u oscuro: necesitamos comparar sus fases. Por eso usamos:

- **Óptica geométrica:** dirección, reflexión, refracción y formación de imágenes; adecuada cuando los tamaños relevantes son grandes frente a la longitud de onda y no se busca describir franjas.
- **Óptica ondulatoria:** superposición y fase; necesaria para explicar la doble rendija.

No son dos tipos de luz. Son modelos de la misma luz que conservan la información necesaria para preguntas diferentes.

### Los supuestos traducidos a decisiones

| Supuesto | Qué significa | Qué permite hacer |
|---|---|---|
| Medio homogéneo e isótropo | La rapidez no cambia con la posición ni con la dirección dentro del medio | Dibujar tramos rectos y un índice por medio y color |
| Interfaz estacionaria y lisa | La frontera no se mueve y su orientación local está definida | Conservar la frecuencia y medir ángulos respecto de una normal |
| Medio transparente y pérdidas despreciables | No se analiza la absorción de energía en el recorrido | Concentrarse en dirección e imagen; Snell no calcula por sí sola la intensidad |
| Rayos paraxiales | Rayos próximos al eje y con inclinaciones pequeñas respecto de él | Usar las ecuaciones aproximadas de espejos esféricos y lentes |
| Lente delgada | Se puede despreciar su espesor en la localización de objetos e imágenes | Medir las distancias desde un único plano de lente |
| Doble rendija ideal | Misma frecuencia, fase relativa estable y polarización compatible | Predecir máximos y mínimos estables de interferencia |

**Paraxial no significa que todos los ángulos de Snell deban ser pequeños.** Snell permite ángulos grandes en una interfaz; la aproximación paraxial se introduce al simplificar los sistemas que forman imágenes. La aproximación de ángulo pequeño en doble rendija también se declara por separado.

**Comprueba el apoyo visual:** pregunta 34 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Lectura de figuras y ejemplos de las fuentes|autoevaluación de figuras y ejemplos]].

**Pausa y aplicación:** responde la pregunta 1 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]]. Luego lee los enunciados de [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija|O1]] y [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|O4]] y explica qué modelo requiere cada uno antes de calcular.

## 2. Índice de refracción: por qué se desvía un rayo

### Rapidez, frecuencia y longitud de onda

La rapidez indica qué distancia avanza la onda por unidad de tiempo. En el vacío es $c\approx3.00\times10^8\,\mathrm{m/s}$. La frecuencia $f$ cuenta ciclos por segundo y el período $T=1/f$ indica cuánto dura un ciclo.

Durante un período, una cresta avanza una longitud de onda $\lambda$. De distancia dividida por tiempo obtenemos

$$
v=\frac{\lambda}{T}=\lambda f.
$$

El **índice de refracción** se define como

$$
n=\frac{c}{v},\qquad v=\frac{c}{n}.
$$

Es una razón sin unidades. En los medios transparentes ordinarios de estos ejercicios, mayor índice significa menor rapidez. Por ejemplo, $n=1.50$ da $v=(3.00\times10^8)/1.50=2.00\times10^8\,\mathrm{m/s}$.

El material responde al campo electromagnético y modifica la propagación de la onda. No necesitamos describir esa respuesta microscópica para usar $n$: en los problemas, el índice o la rapidez caracterizan su efecto.

### Qué cambia al cruzar la frontera

En una interfaz **estacionaria**, la frecuencia de la onda transmitida coincide con la de la incidente. Las oscilaciones a ambos lados de la frontera deben mantener el mismo ritmo temporal; no puede acumularse indefinidamente una diferencia de ciclos allí.

Como $v=\lambda f$ y $f$ permanece constante:

$$
\lambda_{\mathrm{medio}}=\frac{c}{nf}=\frac{\lambda_0}{n},
\qquad
\frac{\lambda_2}{\lambda_1}=\frac{n_1}{n_2}.
$$

$\lambda_0$ es la longitud de onda en el vacío. Al entrar en un medio de mayor índice, disminuyen la rapidez y la longitud de onda; **no disminuye la frecuencia**. Es posible que el índice dependa del color: para cada frecuencia se usa el índice correspondiente.

### Normal, superficie y ángulo

La **normal** es una recta perpendicular a la superficie justo donde incide el rayo. Los ángulos de incidencia, reflexión y refracción se miden entre el rayo y esa normal. Si el dato está medido desde la superficie, usa su complementario:

$$
\theta_{\mathrm{normal}}=90^\circ-\phi_{\mathrm{superficie}}.
$$

En una superficie curva la normal cambia de punto a punto. Para una cara esférica, pasa por el centro de curvatura.

![[imagenes/optica-refraccion.svg]]

*Observa la referencia de los ángulos: la normal es perpendicular a la frontera. La figura acompaña el paso de aceite a agua de O4; al disminuir el índice, el rayo transmitido se aleja de la normal.*

La refracción es el cambio de propagación al pasar de medio. Si la incidencia es oblicua y cambia el índice, en general cambia la dirección. Si el rayo llega **por la normal**, puede cambiar la rapidez sin desviarse. Por tanto, cambiar de rapidez no implica siempre girar.

### Ejemplo del libro: el mismo láser en aire y en el ojo

**Fuente y datos:** [capítulo 33](zotero://open-pdf/library/items/9VRFKAHP?page=8), ejemplo 33.2, PDF pp. 8–9. Un láser tiene $\lambda_{\mathrm{aire}}=633\,\mathrm{nm}$ y, en el humor acuoso del ojo, $\lambda=474\,\mathrm{nm}$. El humor acuoso es un líquido transparente del ojo. Se aproxima $n_{\mathrm{aire}}=1$ y se buscan el índice del líquido, la rapidez y la frecuencia.

1. **Elegir la idea física.** La interfaz no se mueve: la frecuencia se conserva. Por eso podemos relacionar las longitudes de onda con los índices, sin necesitar un ángulo de incidencia.
2. **Obtener el índice.** De $\lambda_{\mathrm{medio}}=\lambda_0/n$ despejamos $n=\lambda_0/\lambda_{\mathrm{medio}}$:

$$
n\approx\frac{633\,\mathrm{nm}}{474\,\mathrm{nm}}=1.33544\ldots\approx1.34.
$$

3. **Obtener la rapidez.** Usamos el cociente sin redondear en el paso intermedio:

$$
v=\frac{c}{n}\approx\frac{3.00\times10^8}{633/474}\,\mathrm{m/s}
\approx2.25\times10^8\,\mathrm{m/s}.
$$

4. **Obtener la frecuencia con un par coherente de datos.** Usamos rapidez y longitud de onda del aire, o ambas del líquido:

$$
f\approx\frac{c}{\lambda_{\mathrm{aire}}}
=\frac{3.00\times10^8\,\mathrm{m/s}}{633\times10^{-9}\,\mathrm m}
\approx4.74\times10^{14}\,\mathrm{Hz}.
$$

5. **Interpretar.** En el líquido avanza más lentamente y cada ciclo ocupa menos distancia, manteniendo el mismo número de ciclos por segundo. Usar $c/(474\,\mathrm{nm})$ mezclaría la rapidez del vacío con la longitud de onda del líquido y daría una frecuencia incorrecta.

**Aplicación inmediata:** intenta [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O21. Índice desde el cambio de longitud de onda — M · primeros parciales 2023 y 2024|O21]] sin copiar estos pasos; conserva la decisión de qué magnitudes pertenecen al mismo medio.

**Comprueba el apoyo visual:** pregunta 36 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Lectura de figuras y ejemplos de las fuentes|autoevaluación de figuras y ejemplos]].

**Pausa y aplicación:** responde las preguntas 2–3 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]] y la 21 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. En O5, intenta primero convertir el ángulo y obtener los índices a partir de las rapideces.

## 3. De Huygens a la ley de Snell

### La idea física detrás del giro

El principio de Huygens permite construir el avance de un frente: cada punto del frente actúa como origen de ondas secundarias y el nuevo frente es la superficie tangente a ellas. No son nuevas fuentes independientes que cambian arbitrariamente de frecuencia; es una construcción de la propagación de la misma onda.

Imagina un frente oblicuo que va del medio 1 al 2. Su extremo A toca primero la frontera; otro punto B todavía viaja por el medio 1. Durante el mismo intervalo $\Delta t$:

1. B llega a otro punto C de la frontera, recorriendo $BC=v_1\Delta t$.
2. Desde A, la onda ya entró al medio 2 y avanzó $AD=v_2\Delta t$.
3. El nuevo frente refractado CD es tangente a esa onda secundaria; el rayo AD es perpendicular al frente CD.

![[imagenes/optica-huygens-snell.svg]]

*Los dos triángulos comparten AC sobre la interfaz. AB es el frente incidente y CD el refractado; los rayos BC y AD son perpendiculares a esos frentes. El ejemplo representa $v_2<v_1$.*

### De los triángulos a la ecuación

Los ángulos entre los frentes y la interfaz son iguales a los ángulos de los rayos con la normal, porque ambas parejas de rectas son perpendiculares. En los dos triángulos rectángulos:

$$
\sin\theta_1=\frac{BC}{AC}=\frac{v_1\Delta t}{AC},
\qquad
\sin\theta_2=\frac{AD}{AC}=\frac{v_2\Delta t}{AC}.
$$

Al dividir, se cancelan el intervalo y el lado común:

$$
\frac{\sin\theta_1}{\sin\theta_2}=\frac{v_1}{v_2}.
$$

Sustituimos $v_1=c/n_1$ y $v_2=c/n_2$:

$$
\frac{v_1}{v_2}=\frac{c/n_1}{c/n_2}=\frac{n_2}{n_1}
\quad\Longrightarrow\quad
\boxed{n_1\sin\theta_1=n_2\sin\theta_2}.
$$

Esta es la **ley de Snell**, que también se establece experimentalmente. Se aplica localmente en una interfaz lisa entre medios transparentes e isótropos. Una frontera curva requiere su normal local; no es necesario que toda la frontera sea plana.

### Cómo usarla sin perder la interpretación

Para hallar el ángulo transmitido:

$$
\sin\theta_2=\frac{n_1}{n_2}\sin\theta_1,
\qquad
\theta_2=\arcsin\!\left(\frac{n_1}{n_2}\sin\theta_1\right).
$$

El arcoseno recupera el ángulo cuyo seno calculamos. Usa la calculadora en grados si el enunciado trabaja en grados.

- Si $n_2>n_1$, el factor $n_1/n_2<1$: disminuye el ángulo y el rayo se acerca a la normal.
- Si $n_2<n_1$, aumenta el ángulo, siempre que exista rayo transmitido.
- Si el argumento del arcoseno supera 1, no inventes un ángulo: revisa reflexión total en la sección 5.
- Si $\theta_1=0$, resulta $\theta_2=0$ para cualquier par de índices de este modelo.

**Ejemplo de planteo:** del aire ($n_1=1$) a vidrio ($n_2=1.50$), con $\theta_1=30^\circ$:

$$
\sin\theta_2=\frac{1}{1.50}\sin30^\circ=\frac13
\quad\Longrightarrow\quad\theta_2\approx19.5^\circ.
$$

El resultado es menor que $30^\circ$, como se esperaba. Snell determina la dirección; no dice qué fracción de la energía se refleja o transmite.

### Ejemplo del libro: agua a vidrio, con reflexión y refracción

![[imagenes/optica-libro-ejemplo-snell.png|520]]

*Fuente: [capítulo 33](zotero://open-pdf/library/items/9VRFKAHP?page=8), PDF p. 8, figura 33.11 y ejemplo 33.1 (página impresa 1128).*

La luz llega **desde el agua**, $n_a=1.33$, hacia el vidrio, $n_b=1.52$, con incidencia $\theta_a=60^\circ$. La letra $a$ identifica el medio de llegada; $b$, el de transmisión. No se elige el medio inicial por estar arriba o abajo: se sigue la flecha incidente.

1. **Predecir:** como $n_b>n_a$, el rayo transmitido debe acercarse a la normal.
2. **Separar los fenómenos:** la parte reflejada sigue en agua y cumple $\theta_r=\theta_a=60^\circ$. La parte transmitida requiere Snell.
3. **Despejar y sustituir:**

$$
n_a\sin\theta_a=n_b\sin\theta_b
\quad\Longrightarrow\quad
\sin\theta_b=\frac{1.33}{1.52}\sin60^\circ\approx0.758.
$$

$$
\theta_b=\arcsin(0.758\ldots)\approx49.3^\circ.
$$

4. **Comprobar:** $49.3^\circ<60^\circ$, consistente con la predicción. El ángulo transmitido respecto de la superficie sería $90^\circ-49.3^\circ=40.7^\circ$; no es el mismo dato que usa Snell.

**Aplicación inmediata:** resuelve O4, ahora con un paso de índice mayor a menor. Antes del arcoseno, predice si el ángulo aumentará o disminuirá.

**Pausa y aplicación:** responde la pregunta 10 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y resuelve [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|O4]]. Escribe antes del cálculo si esperas que el ángulo aumente o disminuya.

## 4. Bloques, profundidad aparente y color

### Dispersión: cada color tiene su propio recorrido

En muchos materiales, el índice depende de la frecuencia; eso se llama **dispersión**. Dos colores que llegan con el mismo ángulo pueden tener rapideces e índices diferentes y, por Snell, ángulos diferentes dentro del bloque. Calcula cada color por separado: no uses un índice promedio si te piden su separación.

En una placa de espesor $e$, medido perpendicularmente a sus caras, el tramo interno forma un triángulo rectángulo. Si el ángulo interno desde la normal es $\theta$, su avance paralelo a la cara es

$$
\tan\theta=\frac{x}{e}\quad\Longrightarrow\quad x=e\tan\theta.
$$

Para dos rayos que entran por el mismo punto:

$$
\Delta x=e\left|\tan\theta_a-\tan\theta_b\right|.
$$

Esto calcula la **separación de los puntos de salida sobre la segunda cara**. En O5 el espesor se llama $d$; aquí usamos $e$ para distinguirlo de la separación de rendijas de la sección 9.

Si el medio exterior es el mismo a ambos lados y las caras son paralelas, Snell en entrada y salida da

$$
n_{\mathrm{ext}}\sin\theta_i=n_{\mathrm{bloque}}\sin\theta_t,
\qquad
n_{\mathrm{bloque}}\sin\theta_t=n_{\mathrm{ext}}\sin\theta_{\mathrm{salida}}.
$$

Por tanto, $\theta_{\mathrm{salida}}=\theta_i$: cada rayo emergente queda paralelo al incidente, aunque salga por otro punto. Dos colores pueden separarse dentro de la placa y salir paralelos entre sí.

### Separación de salidas y desplazamiento lateral son distancias distintas

El **desplazamiento lateral** de un solo rayo es la distancia perpendicular entre su línea emergente y la prolongación de su línea incidente. En una placa paralela:

$$
a=e\frac{\sin(\theta_i-\theta_t)}{\cos\theta_t}.
$$

Para ver de dónde sale, compara en la cara de salida los avances $e\tan\theta_i$ y $e\tan\theta_t$; su diferencia está medida sobre la cara. Al proyectarla perpendicularmente al rayo emergente, multiplicas por $\cos\theta_i$ y obtienes la expresión anterior. Si solo quieres la magnitud, toma el valor absoluto.

O5 pide la separación **entre dos salidas**, que requiere $\Delta x$, no esta última fórmula. Antes de sustituir, identifica entre qué puntos y en qué dirección se mide la distancia solicitada.

### Por qué un objeto sumergido parece estar más arriba

La luz que sale del objeto cambia de dirección al cruzar la superficie. El ojo recibe los rayos ya refractados y los prolonga hacia atrás como si hubieran viajado rectos. Esas prolongaciones sitúan el objeto en una posición **aparente**. El objeto real no se mueve.

Sea $d_r$ la profundidad real y $d_a$ la aparente. Para un rayo que cruza la superficie a una distancia horizontal $x$ de la vertical del objeto:

$$
\tan\theta_{\mathrm{obj}}=\frac{x}{d_r},
\qquad
\tan\theta_{\mathrm{obs}}=\frac{x}{d_a}.
$$

Dividimos ambas relaciones para eliminar $x$:

$$
\frac{d_a}{d_r}
=\frac{\tan\theta_{\mathrm{obj}}}{\tan\theta_{\mathrm{obs}}}.
$$

Cerca de la normal, los ángulos son pequeños y $\tan\theta\approx\sin\theta$. Snell da $n_{\mathrm{obj}}\sin\theta_{\mathrm{obj}}=n_{\mathrm{obs}}\sin\theta_{\mathrm{obs}}$; al combinar:

$$
\boxed{d_a\approx d_r\frac{n_{\mathrm{obs}}}{n_{\mathrm{obj}}}}.
$$

Al observar desde el aire un objeto en el agua, la razón es aproximadamente $1/1.33<1$: la profundidad aparente es menor. La luz que permite verlo recorre el sentido agua → aire.

La fórmula supone una superficie plana, un medio uniforme a cada lado y observación cercana a la normal. Para rayos muy oblicuos, distintas prolongaciones no dan un único punto imagen exacto: hay que analizar la geometría sin esa simplificación.

### Ejemplo del libro: profundidad real y profundidad aparente

![[imagenes/optica-libro-profundidad-aparente.png|720]]

*Fuente: [capítulo 34](zotero://open-pdf/library/items/N9GX45A9?page=17), PDF p. 17, figuras 34.26–34.27 y ejemplo 34.7 (página impresa 1173). Los ángulos del esquema están exagerados para mostrar el efecto.*

En el dibujo, PQ es una flecha en el fondo y P′Q′ su imagen virtual, más cerca de la superficie. En la fotografía, la parte sumergida de la pajilla parece desplazada respecto de su posición real. No hay un quiebre material de la pajilla: cambió la dirección de los rayos que llegan al observador.

**Datos del ejemplo:** profundidad real $d_r=2.00\,\mathrm m$, agua $n_{\mathrm{obj}}=1.33$ y observación desde aire $n_{\mathrm{obs}}=1.00$, casi perpendicular a la superficie.

1. **Elegir el modelo:** superficie plana y ángulos pequeños respecto de la normal; usamos la relación de profundidad aparente deducida arriba.
2. **Sustituir los índices en su lugar:** el índice del medio del observador va arriba:

$$
d_a\approx(2.00\,\mathrm m)\frac{1.00}{1.33}
\approx1.50\,\mathrm m.
$$

3. **Responder la distancia que se pide:** la profundidad aparente es $1.50\,\mathrm m$. Si preguntaran cuánto se eleva aparentemente el fondo, se resta $d_r-d_a\approx0.50\,\mathrm m$.
4. **Conectar con el signo del libro:** en la figura, $s=2.00\,\mathrm m$ y $s'\approx-1.50\,\mathrm m$. El signo negativo indica imagen virtual en el agua; la **profundidad** $d_a=|s'|$ es una longitud positiva. No son dos resultados incompatibles.

**Aplicación inmediata:** intenta O6 y distingue entre profundidad aparente y elevación aparente antes de operar.

**Pausa y aplicación:** responde la pregunta 5 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]] y las 22–23 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. Practica O5–O6 en [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|la familia de refracción]].

## 5. Reflexión total interna: cuándo la luz queda atrapada

### Del aumento del ángulo al ángulo crítico

Si la luz va de índice mayor a menor ($n_1>n_2$), Snell exige $\theta_2>\theta_1$. Al aumentar la incidencia, llega un límite en que la dirección refractada es paralela a la superficie: $\theta_2=90^\circ$.

Llamamos **ángulo crítico** al ángulo de incidencia que produce ese límite. Sustituyendo $\sin90^\circ=1$ en Snell:

$$
n_1\sin\theta_c=n_2
\quad\Longrightarrow\quad
\sin\theta_c=\frac{n_2}{n_1}
\quad\Longrightarrow\quad
\theta_c=\arcsin\!\left(\frac{n_2}{n_1}\right).
$$

La razón debe ser menor que 1. Si se intenta entrar a un índice mayor, esta condición no puede alcanzarse y no hay reflexión total interna de este tipo.

| Condición, con $n_1>n_2$ | Qué predice el trazado |
|---|---|
| $\theta_i<\theta_c$ | Existe rayo transmitido; también puede haber reflexión parcial |
| $\theta_i=\theta_c$ | Caso límite: dirección refractada rasante |
| $\theta_i>\theta_c$ | No existe rayo transmitido propagante; reflexión total interna |

Para $n_1=1.50$ y $n_2=1.00$, $\theta_c\approx41.8^\circ$. Una incidencia de $30^\circ$ permite transmisión; una de $50^\circ$ produce reflexión total. Decir “viene del vidrio” no basta: hay que comprobar también el ángulo.

“Total” describe la reflexión de la energía incidente en el modelo de medios ideales sin absorción. El modelo ondulatorio permite un campo que decae junto a la interfaz, llamado evanescente; no es un rayo que viaje alejándose por el segundo medio. Para estos ejercicios basta el criterio de Snell.

### Leer la figura del libro: tres regímenes en la misma interfaz

![[imagenes/optica-libro-reflexion-total.png|720]]

*Fuente: [capítulo 33](zotero://open-pdf/library/items/9VRFKAHP?page=10), PDF p. 10, figura 33.13 (página impresa 1130). Recorte del diagrama y de la demostración con láser.*

Sigue los rayos que parten del punto negro en el medio de mayor índice $n_a$. Los rayos 1 y 2 tienen transmisión; el 3 alcanza el límite rasante; el 4 supera el crítico y se refleja dentro. Las líneas verticales discontinuas son normales, no paredes. El número de un rayo solo identifica un caso, no su intensidad.

La fotografía permite reconocer el fenómeno fuera del dibujo: un haz sale refractado por la superficie y otro se refleja internamente. El haz se hace visible por dispersión de parte de la luz hacia la cámara; ver la trayectoria en la foto no significa que todo rayo deba ser visible de costado. Al resolver, decide el régimen con los índices y el ángulo, sin estimar números a partir de la inclinación del dibujo.

### La geometría va antes de la desigualdad

En una guía con un corte oblicuo, si $\phi$ es el ángulo del **rayo con el plano de corte**, la incidencia es $90^\circ-\phi$. Por tanto:

$$
90^\circ-\phi>\theta_c
\quad\Longrightarrow\quad
\phi<90^\circ-\theta_c.
$$

El valor $90^\circ-\theta_c$ es el **umbral límite** que suele pedirse como “máximo”; la reflexión total estricta corresponde a valores menores de $\phi$. Para usar esta relación, el rayo debe viajar en la dirección del eje con el que se midió el corte, como ocurre en O11.

![[imagenes/optica-reflexion-total.svg]]

*En el dibujo, el ángulo del corte está medido desde el eje del rayo. Su complementario es el que se compara con el crítico.*

En un cubo como O10, la normal de la cara lateral es perpendicular a la de la cara superior. Si el rayo interno forma $\theta_t$ con la primera, su incidencia sobre la segunda es $90^\circ-\theta_t$. Aumentar el ángulo externo puede aumentar $\theta_t$ y **disminuir** la incidencia en la cara superior. No trasladamos sin más la desigualdad de una cara a otra: primero expresamos cada ángulo con su normal.

**Pausa y aplicación:** responde la pregunta 4 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]], la 15 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y la 24 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. Resuelve O10–O11 dibujando ambas normales.

## 6. Reflexión, imágenes planas y camino de la luz

### La ley de reflexión y el recorrido físico

En una superficie lisa, el rayo reflejado vuelve al medio de origen y cumple

$$
\theta_r=\theta_i.
$$

Ambos ángulos se miden desde la normal. Si la superficie es rugosa, sus normales locales cambian y los rayos se dispersan; eso no invalida la ley local. Aquí estudiamos reflexión especular, con una dirección reflejada definida.

Tras dos reflexiones en espejos perpendiculares, las dos componentes de dirección en el plano del dibujo cambian de signo sucesivamente. El rayo sale paralelo al incidente y en sentido opuesto, como se comprueba en O7; no tiene por qué volver por la misma recta. La afirmación se refiere a esa geometría plana, no a cualquier recorrido tridimensional.

### Qué significa formar una imagen

Cada punto de un objeto envía luz en muchas direcciones. Para localizar su imagen necesitamos al menos dos rayos de ese punto:

- **Imagen real:** los rayos que salen del elemento óptico se cruzan físicamente. Una pantalla colocada allí puede recibir el patrón enfocado.
- **Imagen virtual:** los rayos salen divergiendo; sus prolongaciones hacia atrás se cruzan. La luz no pasa por ese cruce, de modo que una pantalla colocada allí no registra esa imagen enfocada.

Una imagen virtual puede verse: el ojo recibe el haz y sus propias lentes forman una imagen sobre la retina. “Virtual” no significa invisible. Tampoco significa automáticamente “derecha” en un sistema de varios elementos: real/virtual describe el encuentro de rayos; derecha/invertida describe la orientación.

Los dos o tres rayos que elegimos son una ayuda de construcción. Un punto del objeto emite muchos rayos y, en el modelo ideal, todos los que admite el sistema y que intervienen en esa imagen corresponden al mismo punto imagen. Por eso cubrir parte de un espejo no corta automáticamente la misma parte de la imagen: todavía pueden llegar rayos de cada punto por la parte descubierta, aunque con menos luz. Esta observación se desarrolla en el ejemplo conceptual 34.2 del [capítulo 34, PDF p. 9](zotero://open-pdf/library/items/N9GX45A9?page=9); aquí se usa para entender por qué trazamos pocos rayos representativos.

![[imagenes/optica-imagen-real-virtual.svg]]

*Los ejemplos usan una lente convergente: arriba los rayos se encuentran de verdad; abajo solo lo hacen sus prolongaciones punteadas. El criterio también sirve para espejos, aunque cambie el lado físico de la imagen real.*

### Por qué el espejo plano da distancias iguales

Para un objeto delante de un espejo plano, los rayos reflejados divergen. Al prolongarlos detrás del espejo, la igualdad de ángulos produce triángulos simétricos: la imagen queda a la misma distancia **perpendicular** detrás del plano que el objeto delante.

Si el espejo está en la coordenada $x_m$ y el objeto en $x_o$, la simetría exige

$$
x_i-x_m=x_m-x_o
\quad\Longrightarrow\quad
x_i=2x_m-x_o.
$$

La imagen es virtual, del mismo tamaño y derecha en la dirección vertical del dibujo. El espejo invierte la coordenada perpendicular a su plano; no intercambia por sí solo las coordenadas izquierda y derecha del espacio.

### Leer el esquema de clase: la luz que llega al ojo

![[imagenes/optica-clase-imagen-espejo-plano.png|650]]

*Fuente: [clase de Óptica Geométrica del 09-09-2024](zotero://open-pdf/library/items/7DIU9RYN?page=3), PDF p. 3, diapositiva impresa 25. Recorte del esquema.*

Sigue A → M → ojo: ese es el recorrido real. Al prolongar desde el ojo el rayo recibido, parece venir de A′, detrás del espejo. El segmento discontinuo M–A′ es una prolongación; no describe luz atravesando el espejo. La recta horizontal por M es la normal y los ángulos $\alpha$ se miden desde ella. Los puntos A y A′ quedan a igual distancia perpendicular del espejo.

Por ejemplo, si A está a $30\,\mathrm{cm}$ delante, A′ aparece $30\,\mathrm{cm}$ detrás. La separación objeto–imagen es $60\,\mathrm{cm}$; la distancia imagen–espejo es $30\,\mathrm{cm}$. Este dato numérico es una aplicación didáctica añadida al esquema de clase.

### Cuando se mueve el espejo

Con el objeto fijo y dos posiciones del espejo:

$$
\Delta x_i=2\Delta x_m.
$$

Por ejemplo, si el espejo se aleja $10\,\mathrm{cm}$ del objeto, la imagen se desplaza $20\,\mathrm{cm}$ en el mismo sentido en ese eje. **Respecto del espejo**, su distancia aumenta solo $10\,\mathrm{cm}$. Son comparaciones con referencias distintas.

Si también se mueve el objeto, la forma general es $\Delta x_i=2\Delta x_m-\Delta x_o$. Por eso no se usa el factor 2 sin declarar qué permanece fijo.

![[imagenes/optica-espejos-planos.svg]]

*Lee por separado la posición del espejo y la de la imagen. La simetría permite reconstruir la segunda a partir de la primera y del objeto.*

### Fermat: justificar el punto donde rebota

El principio de Fermat dice que el recorrido real hace **estacionario** el tiempo de viaje: una variación pequeña del camino no lo cambia en primer orden. En la reflexión plana en un medio uniforme, ese recorrido es además el mínimo. No es correcto reemplazar siempre “estacionario” por “mínimo” en cualquier sistema óptico.

Para dos puntos a alturas $h_1$ y $h_2$ sobre un espejo horizontal, separados horizontalmente por $D$, sea $x$ la posición del rebote medida desde la vertical del primero. Las distancias salen de Pitágoras:

$$
\ell_1=\sqrt{x^2+h_1^2},\qquad
\ell_2=\sqrt{(D-x)^2+h_2^2},\qquad
t(x)=\frac{\ell_1+\ell_2}{v}.
$$

La rapidez $v$ es la misma en ambos tramos. Si el medio es aire, se aproxima por $c$. Al derivar e igualar a cero:

$$
\frac{dt}{dx}=\frac1v\left[
\frac{x}{\sqrt{x^2+h_1^2}}
-\frac{D-x}{\sqrt{(D-x)^2+h_2^2}}
\right]=0.
$$

Cada cociente es el seno del ángulo de un rayo con la normal al espejo. Por tanto, $\sin\theta_i=\sin\theta_r$ y, para los ángulos de este recorrido, $\theta_i=\theta_r$.

Si todavía no manejas derivadas, refleja uno de los puntos al otro lado del espejo: el trayecto se convierte en una línea recta, que es la menor distancia entre los puntos desplegados. Ambas justificaciones explican O8. En medios de distintas rapideces se minimiza el tiempo, no simplemente la longitud geométrica total.

**Comprueba el apoyo visual:** pregunta 37 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Lectura de figuras y ejemplos de las fuentes|autoevaluación de figuras y ejemplos]].

**Pausa y aplicación:** responde las preguntas 6–7 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]] y las 25–26 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. Practica [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos|O7–O9]], indicando la referencia usada para cada desplazamiento.

## 7. Espejos esféricos: de la geometría al foco

### Eje, centro, vértice y foco no son el mismo punto

Un espejo esférico es una parte de una esfera. Su **centro de curvatura C** es el centro de esa esfera y su **vértice V**, el punto central de la superficie reflectante. El eje óptico pasa por C y V. El radio de curvatura indica la distancia entre ellos, con el signo que declararemos abajo.

- En un espejo **cóncavo**, la cara reflectante mira hacia el interior de la esfera; rayos paralelos cercanos al eje pueden converger después de reflejarse.
- En uno **convexo**, la cara reflectante mira hacia afuera; esos rayos divergen y sus prolongaciones sitúan un foco virtual detrás del espejo.

El **foco F** es el punto asociado a rayos incidentes paralelos al eje. La imagen de un objeto a distancia finita no queda necesariamente en F. El centro C tampoco es el foco.

### De dónde sale la ecuación del espejo y por qué aparece $R/2$

Considera primero un punto objeto sobre el eje de un espejo cóncavo, más lejos que C ($s>R$). Un rayo llega a una altura pequeña $h$ sobre el vértice. Sean $\alpha$ el ángulo del rayo incidente con el eje, $\beta$ el del reflejado y $\varphi$ el de la normal local, que apunta a C. Llama $i$ al ángulo de incidencia respecto de esa normal. En esta geometría, los ángulos de los triángulos y la igualdad entre incidencia y reflexión dan $\varphi=\alpha+i$ y $\beta=\varphi+i$. De la primera, $i=\varphi-\alpha$; al sustituir en la segunda:

$$
\beta=\varphi+(\varphi-\alpha)
\quad\Longrightarrow\quad
\alpha+\beta=2\varphi.
$$

Cerca del eje, el punto de reflexión puede aproximarse al plano del vértice y los triángulos dan, con ángulos pequeños **en radianes**:

$$
\alpha\approx\frac{h}{s},\qquad
\beta\approx\frac{h}{s'},\qquad
\varphi\approx\frac{h}{R}.
$$

Aquí $s$ es la distancia de objeto y $s'$ la de imagen, medidas desde V. Sustituyendo y dividiendo por $h$:

$$
\frac{h}{s}+\frac{h}{s'}\approx\frac{2h}{R}
\quad\Longrightarrow\quad
\boxed{\frac1s+\frac1{s'}=\frac2R}.
$$

La igualdad final es la ecuación **del modelo paraxial**, obtenida mediante aproximaciones. Para un objeto muy lejano, los rayos llegan casi paralelos y $1/s\to0$; su imagen define el foco:

$$
\frac1f=\frac2R
\quad\Longrightarrow\quad
f=\frac R2,
\qquad
\boxed{\frac1s+\frac1{s'}=\frac1f}.
$$

La construcción se mostró en el caso inicial $s>R$; la convención de distancias con signo permite extender la ecuación a los otros casos paraxiales. Así, $f=R/2$ se deduce para un espejo esférico paraxial; no es una fórmula de lentes. Un espejo esférico con rayos muy alejados del eje no concentra todos los rayos en un mismo punto: esa limitación se llama aberración esférica.

### Qué significan los signos

Usamos la convención de **objeto real positivo e imagen real positiva**. Para espejos:

| Magnitud | Signo positivo | Signo negativo |
|---|---|---|
| $s$ | Objeto real delante, del lado de llegada de la luz | Objeto virtual para el espejo |
| $s'$ | Imagen real delante, del lado de salida de la luz reflejada | Imagen virtual detrás |
| $R$ y $f$ | Espejo cóncavo, centro y foco delante | Espejo convexo, centro y foco detrás |

Como la luz vuelve hacia el lado del objeto, **delante del espejo** es tanto el lado de llegada como el de salida. Esto será distinto en una lente. Las distancias $s$ y $s'$ no son automáticamente coordenadas de un eje positivo hacia la derecha.

Si te dan el radio como una distancia positiva, decide el signo según la forma: por ejemplo, un convexo de radio geométrico $40\,\mathrm{cm}$ tiene $R=-40\,\mathrm{cm}$ y $f=-20\,\mathrm{cm}$ en esta convención.

### Leer los esquemas de clase: cóncavo y convexo

![[imagenes/optica-clase-espejos-concavo-convexo.png|740]]

*Fuente: [clase del 09-09-2024](zotero://open-pdf/library/items/7DIU9RYN?page=4), PDF p. 4, diapositiva impresa 26. Recorte de los dos trazados.*

La diapositiva llama **O** al punto que este apunte llama **V**: es el vértice, donde el eje corta la superficie. C es el centro de la esfera imaginaria de la que se recortó el espejo; F es el foco. El radio geométrico mide de V a C y la distancia focal geométrica, de V a F. En el modelo paraxial, F queda a mitad del camino V–C.

En el cóncavo, el rayo incidente paralelo se refleja pasando físicamente por F. En el convexo, el reflejado se separa del eje y su prolongación hacia atrás pasa por F. **Las flechas de cota de la figura muestran longitudes:** al calcular con la convención del vault asignamos $f,R>0$ al cóncavo y $f,R<0$ al convexo. No se decide el signo por el sentido de una flecha que marca el tamaño de un segmento.

### Aumento: de los triángulos al tamaño

Dibuja un objeto vertical de altura $y$ y un rayo desde su punta hasta el vértice del espejo. La reflexión forma ángulos iguales con el eje. Los triángulos a ambos lados de ese punto relacionan alturas y distancias. Para una imagen real invertida, $y'$ queda debajo del eje y es negativa:

$$
\frac{y'}{y}=-\frac{s'}s.
$$

Definimos el **aumento lateral** como

$$
m=\frac{y'}y=-\frac{s'}s,\qquad y'=my.
$$

No tiene unidades. Su signo indica orientación relativa al objeto; su módulo compara tamaños. Por ejemplo, $m=-0.50$ significa invertida y de mitad de altura. $m=+2$ significa derecha y del doble de altura. Real/virtual y mayor/menor se determinan por separado.

### Despejar sin saltos e interpretar

De la ecuación del espejo:

$$
\frac1{s'}=\frac1f-\frac1s
=\frac{s-f}{fs}
\quad\Longrightarrow\quad
s'=\frac{fs}{s-f}.
$$

Todas las longitudes deben estar en la misma unidad. Puedes trabajar en centímetros: los inversos quedan en $\mathrm{cm^{-1}}$ y al invertir recuperas centímetros.

**Ejemplo didáctico:** cóncavo con $f=+10\,\mathrm{cm}$ y objeto real a $s=30\,\mathrm{cm}$:

$$
s'=\frac{(10)(30)}{30-10}\,\mathrm{cm}=15\,\mathrm{cm},
\qquad m=-\frac{15}{30}=-0.50.
$$

La imagen queda $15\,\mathrm{cm}$ delante del espejo, es real, invertida y menor. Si el objeto se acerca a $s=5\,\mathrm{cm}$:

$$
s'=\frac{(10)(5)}{5-10}\,\mathrm{cm}=-10\,\mathrm{cm},
\qquad m=-\frac{-10}{5}=+2.
$$

Ahora la imagen queda detrás, es virtual, derecha y mayor. El cambio no es una contradicción: el objeto cruzó el foco y cambió el encuentro de los rayos.

### Ejemplo del libro: proyectar una imagen sobre una pared

![[imagenes/optica-libro-espejo-proyeccion.png|640]]

*Fuente: [capítulo 34](zotero://open-pdf/library/items/N9GX45A9?page=8), PDF pp. 8–9, figura 34.15 y ejemplo 34.1 (páginas impresas 1164–1165). Recorte de la figura; las proporciones están esquematizadas.*

Un espejo cóncavo proyecta sobre una pared la imagen de un filamento. El filamento está a $10.0\,\mathrm{cm}$ del espejo y mide $5.00\,\mathrm{mm}$ de alto; la pared está a $3.00\,\mathrm m$ del espejo. Se buscan la focal, el radio y la altura de imagen.

1. **Interpretar antes de calcular:** si se proyecta enfocada en una pared, la imagen es real. Usamos $s=+10.0\,\mathrm{cm}$ y $s'=+300\,\mathrm{cm}$; ambas distancias se miden desde el espejo, no entre pared y filamento.
2. **Despejar la focal:**

$$
\frac1f=\frac1s+\frac1{s'}=\frac{s+s'}{ss'}
\quad\Longrightarrow\quad
f=\frac{ss'}{s+s'}
=\frac{(10.0)(300)}{10.0+300}\,\mathrm{cm}
\approx+9.68\,\mathrm{cm}.
$$

3. **Obtener el radio del espejo:** $R=2f\approx+19.4\,\mathrm{cm}$. El signo positivo concuerda con el cóncavo.
4. **Obtener tamaño y orientación:**

$$
m=-\frac{s'}s=-\frac{300}{10.0}=-30.0,
\qquad y'=my=(-30.0)(5.00\,\mathrm{mm})=-150\,\mathrm{mm}.
$$

5. **Expresar el resultado físico:** imagen de $15.0\,\mathrm{cm}$ de alto, invertida; la altura firmada es negativa. El objeto queda apenas más allá del foco, coherente con una imagen real muy alejada y ampliada. El libro redondea $f$ a $9.7\,\mathrm{cm}$; conservamos cifras intermedias para no alterar el aumento al comprobarlo.

**Aplicación inmediata:** intenta un caso de O12 y luego O14, anticipando si la imagen puede recogerse en una pantalla. La geometría de un convexo exigirá otro signo de focal.

### Cómo anticipar el resultado y dibujarlo

Para un objeto real frente a un **cóncavo**:

| Posición del objeto | Imagen esperada |
|---|---|
| $s>2f$ | Entre F y C, real, invertida y menor |
| $s=2f$ | En C, real, invertida e igual |
| $f<s<2f$ | Más allá de C, real, invertida y mayor |
| $s=f$ | Rayos salientes paralelos: sin imagen a distancia finita |
| $0<s<f$ | Detrás del espejo, virtual, derecha y mayor |

Para un objeto real frente a un **convexo**, la imagen es virtual, derecha y reducida, entre V y su foco virtual. Estas reglas se refieren a un elemento y objeto real; no se trasladan sin revisión a objetos virtuales de sistemas.

En el dibujo, usa dos de estos rayos desde la punta del objeto: paralelo al eje que se refleja por F; dirigido por F que se refleja paralelo; dirigido hacia C que regresa sobre su línea. Si F o C son virtuales, usa las prolongaciones correspondientes.

![[imagenes/optica-espejo-concavo.svg]]

*El esquema distingue C, F y V. La imagen se encuentra donde se cruzan los rayos reflejados de la punta del objeto; un rayo que pasa por F no significa que la imagen esté en F.*

Para dos imágenes, transforma sus distancias con signo a posiciones de un mismo eje y resta: $D=|x_{i,A}-x_{i,B}|$. Si quedan a lados opuestos del espejo, sus distancias al vértice se suman, como en O13.

**Pausa y aplicación:** responde las preguntas 11–13 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] —la 11 permite comparar con lentes— y las 27–28 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. Practica [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos|O12–O15]], prediciendo la clase de imagen antes de usar la calculadora.

## 8. Lentes delgadas: dos refracciones y una sola imagen

### Qué simplifica el modelo

Una lente cambia la dirección de la luz al entrar por una cara y al salir por la otra. La luz transmitida sigue hacia el otro lado; esto distingue su geometría de la del espejo. Si el espesor puede despreciarse frente a las distancias y radios relevantes, agrupamos ambas refracciones en un plano: la **lente delgada**.

También suponemos superficies esféricas o planas, rayos paraxiales y el mismo medio exterior a ambos lados. Con medios exteriores diferentes no basta usar sin cambios las ecuaciones de esta sección.

Una lente **convergente** reúne rayos incidentes paralelos en un foco real; tiene $f>0$. Una **divergente** los separa como si provinieran de un foco virtual; tiene $f<0$. Con igual medio exterior a ambos lados, los dos focos están a la misma distancia geométrica del plano de la lente. La forma por sí sola no decide la convergencia: también importa el índice relativo lente/entorno.

### De dónde sale la ecuación de imagen

Para una lente convergente con objeto real fuera del foco y luz de izquierda a derecha, toma dos rayos desde la punta del objeto:

1. Uno pasa por el centro de la lente y, en el modelo delgado con igual medio exterior, sigue prácticamente recto. Sus triángulos dan $y'/y=-s'/s$.
2. Otro llega paralelo al eje, se desvía hacia el foco de salida y llega a la misma punta imagen. Sus triángulos dan $y'/y=-(s'-f)/f$.

Igualamos esas dos expresiones del aumento:

$$
-\frac{s'}s=-\frac{s'-f}{f}
\quad\Longrightarrow\quad
fs'=ss'-sf.
$$

Dividimos por $fss'$:

$$
\frac1s=\frac1f-\frac1{s'}
\quad\Longrightarrow\quad
\boxed{\frac1s+\frac1{s'}=\frac1f},
\qquad
\boxed{m=-\frac{s'}s=\frac{y'}y}.
$$

La geometría se mostró para una imagen real; las distancias con signo permiten expresar también los otros casos paraxiales. Que la ecuación tenga la misma forma que la del espejo no significa que la luz siga el mismo recorrido.

![[imagenes/optica-lente-convergente.svg]]

*Un rayo central sigue recto y otro paralelo se desvía por el foco de salida. Su intersección localiza la punta de la imagen; la base queda sobre el eje.*

### Signos de lente y posiciones sobre un eje

Para luz que avanza hacia la derecha:

| Magnitud | Signo positivo | Signo negativo |
|---|---|---|
| $s$ | Objeto real a la izquierda, lado de llegada | Objeto virtual a la derecha, hacia donde ya convergen los rayos incidentes |
| $s'$ | Imagen real a la derecha, lado de salida | Imagen virtual a la izquierda |
| $f$ | Lente convergente | Lente divergente |

Si la lente está en $x_L$, una forma segura de pasar de coordenadas a distancias es

$$
s=x_L-x_o,\qquad s'=x_i-x_L.
$$

Una distancia negativa no es una longitud física “imposible”: codifica un lado y el carácter real/virtual. El módulo mide la separación al plano de la lente. Las coordenadas de esta ecuación y los signos de los radios que veremos después tienen referencias declaradas; no se sustituyen unas por otras de memoria.

Para un objeto real, una convergente da imagen real e invertida si $s>f$, rayos paralelos si $s=f$, y virtual, derecha y mayor si $0<s<f$. Las comparaciones con $2f$ son análogas a las del cóncavo, pero la imagen real queda **al otro lado**. Una divergente con objeto real da imagen virtual, derecha y reducida. Una lente convergente no siempre forma imagen real.

### Leer los casos de la diapositiva: mover el objeto respecto del foco

![[imagenes/optica-clase-casos-lente-convergente.png|780]]

*Fuente: [clase del 09-09-2024](zotero://open-pdf/library/items/7DIU9RYN?page=16), PDF p. 16, diapositiva impresa 39. Recorte de las cuatro construcciones.*

Fₒ es el foco del lado del objeto y Fᵢ el del lado de salida. En la etiqueta inferior derecha, S designa la posición de la lente. Los casos suponen **lente convergente, objeto real, rayos paraxiales e igual medio exterior**. Compara dónde queda el objeto con la distancia focal positiva $f$:

- Más allá de $2f$: imagen real, invertida y menor, entre $f$ y $2f$ del otro lado.
- En $2f$: imagen real, invertida e igual, en $2f$ del otro lado.
- Entre $f$ y $2f$: imagen real, invertida y mayor, más allá de $2f$ del otro lado.
- Entre el foco y la lente: los rayos salen divergiendo; sus prolongaciones sitúan una imagen virtual, derecha y mayor del lado del objeto.

El caso $s=f$ queda entre los dos últimos: los rayos salientes son paralelos y no hay imagen a distancia finita. Esta comparación permite detectar un signo incorrecto antes de terminar un ejercicio.

**Aplicación numérica añadida al esquema:** para $f=+10\,\mathrm{cm}$, toma primero $s=20\,\mathrm{cm}$. Resulta $s'=fs/(s-f)=20\,\mathrm{cm}$ y $m=-1$: segundo caso. Con $s=5\,\mathrm{cm}$, resulta $s'=-10\,\mathrm{cm}$ y $m=+2$: cuarto caso. La misma lente puede producir imágenes de distinto tipo porque cambió la ubicación del objeto.

> [!info] Traducir los signos de clase al apunte
> La diapositiva de convenios (PDF p. 2, impresa 24) usa un eje cartesiano: las posiciones a la izquierda del elemento son negativas. Por eso un objeto real a la izquierda tiene $s_{\mathrm{DIN}}<0$. En el vault, para estos ejercicios, la **distancia de objeto real** es $s>0$. Por ejemplo, un objeto a $20\,\mathrm{cm}$ a la izquierda tiene coordenada relativa $-20\,\mathrm{cm}$, pero usamos $s=+20\,\mathrm{cm}$ en $1/s+1/s'=1/f$ y $m=-s'/s$. El esquema físico puede ser el mismo; cambia la definición de los símbolos. Para resolver, usa la ecuación y la tabla de signos de una misma convención, como las de este apunte. Las letras F/F′ o Fₒ/Fᵢ también varían entre láminas: identifica cada foco por el recorrido que lo define.

### Leer la diapositiva: lente divergente e imagen virtual

![[imagenes/optica-clase-lente-divergente-imagen-virtual.png|740]]

*Fuente: [clase del 09-09-2024](zotero://open-pdf/library/items/7DIU9RYN?page=17), PDF p. 17, diapositiva impresa 40. Recorte de la construcción; las cotas señalan separaciones geométricas.*

AB es el objeto real; A′B′ es su imagen. El rayo rojo llega paralelo al eje y sale separándose de él: al prolongar ese tramo saliente hacia atrás, pasa por el foco F′ de la izquierda. El rayo violeta que atraviesa el centro sigue aproximadamente recto. Su encuentro con la prolongación roja localiza A′. Aunque la lámina use colores y segmentos continuos para la construcción, la prolongación roja hacia la izquierda no es un recorrido físico del rayo saliente.

Los rayos que salen a la derecha **no se cruzan físicamente** en A′: de allí el carácter virtual. A′B′ sigue encima del eje y es más pequeña que AB: imagen derecha y reducida. En la convención del vault esto se traduce como $f<0$, $s>0$, $s'<0$ y $0<m<1$. La flecha de cota $s'$ dibujada en la lámina no reemplaza esa asignación de signos.

**Aplicación inmediata:** dibuja primero los dos rayos de O20 y compara la imagen esperada con estas cuatro propiedades antes de despejar.

### Fabricante de lentes: cómo conectamos la forma con la focal

La ecuación de imagen usa una focal conocida. Si el problema da el material y la forma, necesitamos obtenerla. El punto de partida es la relación de una superficie refractora esférica. Para ver su origen, considera una primera cara convexa, con centro a la derecha, objeto sobre el eje a la izquierda e imagen real a la derecha. Un rayo llega a una altura pequeña $h$. Llama $\alpha$ a la inclinación del rayo incidente respecto del eje, $\beta$ a la del transmitido que vuelve al eje y $\varphi$ a la inclinación de la normal hacia el centro de curvatura. La geometría da incidencia $\alpha+\varphi$ y refracción $\varphi-\beta$. Snell exige

$$
n_a\sin(\alpha+\varphi)=n_b\sin(\varphi-\beta).
$$

Para ángulos pequeños en radianes, reemplazamos senos por sus ángulos y reordenamos:

$$
n_a(\alpha+\varphi)\approx n_b(\varphi-\beta)
\quad\Longrightarrow\quad
n_a\alpha+n_b\beta\approx(n_b-n_a)\varphi.
$$

Con $\alpha\approx h/s$, $\beta\approx h/s'$ y $\varphi\approx h/R$, sustituimos y cancelamos $h$. Obtenemos la ecuación del modelo paraxial, que se extiende a los otros casos con distancias firmadas:

$$
\frac{n_a}{s}+\frac{n_b}{s'}=\frac{n_b-n_a}{R}.
$$

Aquí el rayo pasa del índice $n_a$ al $n_b$; el radio es positivo si el centro de curvatura queda hacia la derecha de la superficie, con luz hacia la derecha. Para una lente de índice $n_\ell$ rodeada por un medio $n_m$, aplicamos esa relación dos veces:

$$
\frac{n_m}{s_1}+\frac{n_\ell}{s'_1}=\frac{n_\ell-n_m}{R_1},
\qquad
\frac{n_\ell}{s_2}+\frac{n_m}{s'_2}=\frac{n_m-n_\ell}{R_2}.
$$

En este paso los subíndices indican las **dos caras de una sola lente**, no las dos lentes del sistema de la próxima subsección. Su imagen intermedia es el objeto de la segunda cara. Al despreciar el espesor, $s_2\approx-s'_1$ y esos términos se cancelan al sumar. Llamando $s=s_1$ y $s'=s'_2$:

$$
n_m\left(\frac1s+\frac1{s'}\right)
=(n_\ell-n_m)\left(\frac1{R_1}-\frac1{R_2}\right).
$$

Dividimos por $n_m$ y comparamos con $1/s+1/s'=1/f$:

$$
\boxed{\frac1f=
\left(\frac{n_\ell}{n_m}-1\right)
\left(\frac1{R_1}-\frac1{R_2}\right)}.
$$

La fórmula reúne **contraste de índices** y **curvaturas**. $1/f$ tiene unidades de longitud inversa. Para una cara plana, $R\to\infty$ y $1/R=0$; no se usa $R=0$.

### Cómo decidir los radios y entender un cambio de medio

Con luz de izquierda a derecha, nombra las caras en el orden en que las encuentra la luz. En cada cara, imagina la esfera de la que forma parte y localiza su centro:

- Centro a la derecha de la cara: radio positivo.
- Centro a la izquierda: radio negativo.

Para una biconvexa simétrica: $R_1=+R$ y $R_2=-R$, donde $R>0$ es el radio geométrico común. Entonces

$$
\frac1f=\left(\frac{n_\ell}{n_m}-1\right)\frac2R.
$$

Con $n_\ell=1.50$ y aire $n_m\approx1$, el factor es $0.50$ y $f=R$. Si $R=6\,\mathrm{cm}$, la focal es $+6\,\mathrm{cm}$. En un medio de índice $1.80$, el factor pasa a ser $1.50/1.80-1=-1/6$:

$$
\frac1f=-\frac16\frac2{6\,\mathrm{cm}}
=-\frac1{18\,\mathrm{cm}}
\quad\Longrightarrow\quad f=-18\,\mathrm{cm}.
$$

La misma forma pasa a divergir porque cambió el contraste de índices, como en O16. El índice $1.80$ es el dato conservado de ese TP; no es un valor habitual del agua ordinaria. Si lente y medio tuvieran igual índice, el modelo daría $1/f=0$: sin potencia de enfoque, no una focal nula.

### Ejemplo del libro: dos radios iguales en tamaño y opuestos en signo

![[imagenes/optica-libro-radios-lente.png|720]]

*Fuente: [capítulo 34](zotero://open-pdf/library/items/N9GX45A9?page=22), PDF p. 22, figura 34.35 y ejemplo 34.8 (página impresa 1178). Recorte del trazado con los centros de curvatura.*

C₁ y C₂ son centros de las **esferas de las caras**, no los focos de la lente. Para la primera cara de esta biconvexa, el centro C₁ queda a la derecha de esa cara; para la segunda, C₂ queda a su izquierda. No se comparan ambos centros con el centro de la lente: cada radio se define desde su propia superficie.

**Datos del ejemplo:** lente en aire, índice $n_\ell=1.52$, ambos radios de magnitud $10.0\,\mathrm{cm}$. Se pide la focal para una biconvexa y para una bicóncava del mismo material.

1. **Biconvexa:** con luz hacia la derecha, $R_1=+10.0\,\mathrm{cm}$ y $R_2=-10.0\,\mathrm{cm}$. Sustituimos en el fabricante de lentes delgadas:

$$
\frac1f=(1.52-1)
\left(\frac1{+10.0\,\mathrm{cm}}-\frac1{-10.0\,\mathrm{cm}}\right)
=(0.52)(0.200\,\mathrm{cm^{-1}})
=0.104\,\mathrm{cm^{-1}}.
$$

$$
f=\frac1{0.104\,\mathrm{cm^{-1}}}\approx+9.62\,\mathrm{cm}.
$$

2. **Bicóncava:** se invierten los signos de las curvaturas: $R_1=-10.0\,\mathrm{cm}$ y $R_2=+10.0\,\mathrm{cm}$. El paréntesis vale $-0.200\,\mathrm{cm^{-1}}$, de modo que $1/f=-0.104\,\mathrm{cm^{-1}}$ y $f\approx-9.62\,\mathrm{cm}$.
3. **Interpretar:** la primera converge y la segunda diverge en aire. El libro da $\pm9.6\,\mathrm{cm}$ al redondear. Dos radios con igual **módulo** no se cancelan en el paréntesis cuando sus signos son opuestos: restar un número negativo equivale a sumar su módulo.

**Aplicación inmediata:** usa esta lectura de los radios para O16; luego incorpora el cambio de índice del medio. No uses $f=R/2$, que corresponde al espejo esférico.

### Dos lentes: seguir posiciones antes de volver a calcular

No sumes focales de dos lentes separadas. Resuelve la primera, sitúa su imagen sobre un eje común y usa esa posición para determinar qué recibe la segunda.

Con L1 en $x=0$, L2 en $x=D$ y luz hacia la derecha:

$$
s'_1=\frac{f_1s_1}{s_1-f_1},
\qquad x_{i,1}=s'_1,
\qquad s_2=D-s'_1.
$$

- Si $x_{i,1}<D$, los rayos llegan a L2 divergiendo desde ese punto o como si provinieran de él: $s_2>0$, objeto real para L2.
- Si $x_{i,1}>D$, L2 intercepta los rayos **antes de que converjan**: $s_2<0$, objeto virtual para L2. Es el punto hacia el que se dirigían los rayos, no un objeto material colocado allí.

En el segundo caso, la imagen que habría formado L1 sola no llega a formarse como cruce real: L2 modifica los rayos antes. Aun así, esa posición calculada permite describir exactamente el haz que recibe L2 dentro del modelo.

Resuelve después

$$
s'_2=\frac{f_2s_2}{s_2-f_2},
\qquad x_{i,\mathrm{final}}=D+s'_2.
$$

La posición final se mide desde L2 al usar $s'_2$, y desde el origen global al usar $x_{i,\mathrm{final}}$. Para la orientación y el tamaño:

$$
m_{\mathrm{total}}=
\frac{y_1}{y_o}\frac{y_f}{y_1}=m_1m_2,
\qquad y_f=m_{\mathrm{total}}y_o.
$$

La multiplicación aparece porque la altura intermedia se cancela, no porque los aumentos se sumen.

![[imagenes/optica-sistema-objeto-virtual.svg]]

*El esquema representa el caso de O18: la convergencia que produciría L1 sola queda más allá de L2. Las líneas punteadas muestran esa continuación hipotética; los rayos reales cambian de dirección en L2 y forman otra imagen.*

Si se pide diseñar el sistema desde una imagen final deseada, se puede trabajar hacia atrás: fija $s'_2=x_f-D$, despeja $s_2$, obtén $s'_1=D-s_2$ y por último despeja $s_1$. En O19, la imagen final está entre las lentes, a la izquierda de L2, de modo que $s'_2<0$: es virtual para L2 aunque esté dentro del espacio entre elementos. Ser real o virtual depende del haz saliente de ese elemento.

**Comprueba el apoyo visual:** pregunta 35 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Lectura de figuras y ejemplos de las fuentes|autoevaluación de figuras y ejemplos]].

**Pausa y aplicación:** responde la pregunta 8 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]], la 16 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y las 29–30 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. Practica [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Lentes delgadas y sistemas|O16–O19]]. En sistemas, escribe una línea de posiciones antes de calcular el segundo objeto.

## 9. Doble rendija: de la superposición a las franjas

### Qué se suma y qué significa llegar en fase

Los campos de las dos ondas se suman en cada punto. Si ambas contribuciones oscilan en la misma dirección, podemos representarlas como funciones escalares. Una vuelta completa del ciclo equivale a $2\pi$ radianes de fase; recorrer una longitud de onda adicional añade una vuelta a la diferencia de fase.

Para fuentes inicialmente en fase y un mismo medio de propagación:

$$
\Delta\phi=\frac{2\pi}{\lambda}\Delta r.
$$

$\Delta r=r_2-r_1$ es la diferencia de longitudes de los recorridos hasta el punto observado; no es la distancia entre rendijas ni la posición de la franja.

- Si $\Delta r=m\lambda$, la fase difiere en $2\pi m$: las contribuciones se refuerzan.
- Si $\Delta r=(q+1/2)\lambda$, la fase difiere en un múltiplo impar de $\pi$: se oponen.

Con amplitudes iguales, la oposición puede cancelar el campo y dar un mínimo oscuro ideal. Si las amplitudes son distintas, el mínimo no llega a cero. Lo que se suma primero es el **campo**; la intensidad observada está relacionada con el cuadrado del campo resultante promediado en el tiempo.

Que existan zonas oscuras no significa que desaparezca la energía: el patrón redistribuye la intensidad y aparecen también zonas de refuerzo.

### Coherencia no es lo mismo que estar en fase

Dos fuentes son **coherentes** si tienen la misma frecuencia y mantienen una diferencia de fase estable durante la observación. Esa diferencia puede ser distinta de cero. En el experimento ideal de Young usamos además iluminación que llega en fase a las dos rendijas y polarización compatible, para aplicar las condiciones anteriores sin un corrimiento extra del patrón.

Una fuente común, con la iluminación adecuada de ambas rendijas, proporciona esa relación estable. Dos lámparas independientes ordinarias no mantienen una fase relativa estable aunque se vean del mismo color: el contraste de sus posibles franjas se promedia y no se observa el patrón estable del modelo.

Si las fuentes tuvieran un desfase inicial $\phi_0$, habría que incluirlo junto con la fase por diferencia de camino; las posiciones usuales de máximos no se aplican sin revisar ese término. “Coherentes” por sí solo no asegura un máximo central.

### Leer el montaje del libro: una fuente común y dos caminos

![[imagenes/optica-libro-experimento-young.png|720]]

*Fuente: [capítulo 35.1](zotero://open-pdf/library/items/69KMJR6V?page=5), PDF p. 5, figura 35.5a (página impresa 1211). Recorte del montaje de Young.*

La abertura S₀ ilumina S₁ y S₂ desde una fuente común. En la disposición simétrica mostrada, la luz llega en fase a ambas y estas actúan como fuentes coherentes. Desde allí hay **dos recorridos hasta cada punto** de la pantalla. Las bandas no son sombras de las dos aberturas: resultan de la suma de sus ondas.

En un punto brillante, ambas contribuciones llegan con una diferencia de fase de vueltas completas y se refuerzan; en un punto oscuro ideal, llegan en oposición y se cancelan si sus amplitudes son iguales. Los frentes dibujados permiten reconocer esa comparación de fases. El montaje produce muchas bandas aunque solo haya dos rendijas. Para calcular sus posiciones hacen falta las distancias que definimos a continuación.

### La geometría: de dos recorridos a $d\sin\theta$

Sean $d$ la separación entre rendijas y $L$ la distancia perpendicular a una pantalla plana. Cuando $L\gg d$, los rayos desde ambas rendijas hacia un mismo punto son casi paralelos. La diferencia entre sus recorridos se aproxima por la proyección de la separación $d$ sobre esa dirección:

$$
\Delta r\approx d\sin\theta.
$$

El ángulo $\theta$ se mide desde la dirección perpendicular al plano de las rendijas. Esta aproximación de pantalla lejana se usa antes de la de ángulo pequeño. Sin ella, para rendijas en alturas $\pm d/2$ y punto de pantalla en altura $y$, se pueden calcular las dos distancias con Pitágoras y restarlas:

$$
r_1=\sqrt{L^2+(y-d/2)^2},\qquad
r_2=\sqrt{L^2+(y+d/2)^2}.
$$

Con nuestra elección de signos, $y>0$ corresponde a $r_2-r_1>0$. Para el modelo lejano, las condiciones quedan

$$
\text{máximos: }d\sin\theta_m=m\lambda,
\qquad m=0,\pm1,\pm2,\ldots
$$

$$
\text{mínimos: }d\sin\theta_q=\left(q+\frac12\right)\lambda,
\qquad q\in\mathbb Z.
$$

Los órdenes negativos sitúan franjas al otro lado del centro. El máximo central es $m=0$; el primero a un lado es $m=1$ y el tercero, $m=3$. Para que un orden sea posible debe cumplirse $|m\lambda/d|\le1$; los casos de dirección exactamente rasante no llegan a una posición finita de esta pantalla.

![[imagenes/optica-doble-rendija.svg]]

*Distingue $d$ entre aberturas, $L$ hasta la pantalla y $y$ desde el centro. La franja observada depende de la diferencia entre los dos recorridos, no de uno solo.*

### De la condición angular a la posición sobre la pantalla

La geometría de la pantalla da $\tan\theta=y/L$, es decir, $y=L\tan\theta$. Cerca del centro, $|y|\ll L$ y los ángulos son pequeños; entonces $\sin\theta\approx\tan\theta$. Combinamos paso a paso:

$$
d\sin\theta_m=m\lambda
\quad\Longrightarrow\quad
\sin\theta_m=\frac{m\lambda}{d}
\approx\tan\theta_m=\frac{y_m}{L}
\quad\Longrightarrow\quad
\boxed{y_m\approx\frac{m\lambda L}{d}}.
$$

Si no es pequeño el ángulo, pero sí vale el modelo lejano, conserva

$$
y_m\approx L\tan\!\left[\arcsin\!\left(\frac{m\lambda}{d}\right)\right].
$$

El signo aproximado recuerda que la diferencia de camino ya se aproximó por $d\sin\theta$. No es la solución exacta para cualquier geometría cercana.

### Posición, espaciado y separación de colores

La **posición** $y_m$ se mide desde el centro. El **espaciado entre máximos vecinos** del mismo color es la diferencia entre posiciones consecutivas:

$$
\beta=y_{m+1}-y_m
\approx\frac{(m+1)\lambda L-m\lambda L}{d}
=\boxed{\frac{\lambda L}{d}}.
$$

Así, $y_m\approx m\beta$. La distancia desde el centro hasta el máximo de tercer orden es tres veces el espaciado; el espaciado vecino no se multiplica por 3.

Si buscamos máximos del **mismo orden y del mismo lado** para dos colores, restamos sus posiciones:

$$
\Delta y_m=|y_{m,b}-y_{m,a}|
\approx\frac{|m|L}{d}|\lambda_b-\lambda_a|.
$$

Esa es la distancia pedida en O1. Si comparas franjas de órdenes distintos o a lados opuestos, conserva las posiciones con signo y resta al final. Si dos máximos coinciden, $y_{m_a,a}=y_{m_b,b}$ implica

$$
m_a\lambda_a=m_b\lambda_b,
$$

que permite buscar órdenes enteros como en O3. La coincidencia central $m_a=m_b=0$ siempre existe en este modelo; si se pide la primera coincidencia fuera del centro, se buscan enteros positivos no nulos.

Cada color interfiere con las contribuciones de **ese mismo color** que llegan por las dos rendijas. Los patrones de colores distintos se superponen en intensidad, pero no forman entre sí una interferencia estable a la escala temporal del detector usado en estos ejercicios.

### Unidades, controles y límites del modelo

Convierte antes de operar: $1\,\mathrm{nm}=10^{-9}\,\mathrm m$ y $1\,\mathrm{mm}=10^{-3}\,\mathrm m$. La combinación $\lambda L/d$ debe dar una longitud. Si aumentas $L$ o $\lambda$, crece el espaciado; si aumentas $d$, disminuye.

Las fórmulas describen el patrón ideal de dos aberturas estrechas; el ancho finito de cada rendija puede modificar el brillo mediante difracción. Como los ejercicios seleccionados no dan ese ancho ni piden la envolvente, no añadimos ese cálculo. Si el experimento está en un medio distinto del aire, se usa la longitud de onda **en el medio**, no automáticamente la del vacío.

### Ejemplo del libro: obtener la longitud de onda a partir de una franja

![[imagenes/optica-libro-ejemplo-doble-rendija.png|600]]

*Fuente: [capítulo 35.1](zotero://open-pdf/library/items/69KMJR6V?page=7), PDF p. 7, figura 35.7 y ejemplo 35.1 (página impresa 1213). El libro llama R a la distancia a pantalla; aquí la llamamos L.*

Se conocen $d=0.200\,\mathrm{mm}$, $L=1.00\,\mathrm m$ y la posición de la tercera franja brillante, $y_3=9.49\,\mathrm{mm}$, medida desde el centro. Se busca $\lambda$.

1. **Identificar el orden:** la franja central es $m=0$. La tercera brillante a un lado es $m=3$, no $m=2$ ni $m=4$.
2. **Justificar el modelo:** las dos contribuciones son coherentes y en fase en las rendijas. Además $d/L=2.00\times10^{-4}\ll1$ y $y_3/L=9.49\times10^{-3}\ll1$: podemos usar pantalla lejana y ángulo pequeño.
3. **Despejar antes de sustituir:**

$$
y_m\approx\frac{m\lambda L}{d}
\quad\Longrightarrow\quad
y_m d\approx m\lambda L
\quad\Longrightarrow\quad
\lambda\approx\frac{y_m d}{mL}.
$$

4. **Convertir y calcular:**

$$
\lambda\approx
\frac{(9.49\times10^{-3}\,\mathrm m)(0.200\times10^{-3}\,\mathrm m)}{3(1.00\,\mathrm m)}
=6.3267\ldots\times10^{-7}\,\mathrm m
\approx633\,\mathrm{nm}.
$$

5. **Interpretar y controlar:** $9.49\,\mathrm{mm}$ es la distancia desde el centro hasta la tercera franja; el espaciado vecino es $\beta=y_3/3\approx3.16\,\mathrm{mm}$. Usar $9.49\,\mathrm{mm}$ como espaciado daría una longitud de onda tres veces mayor. Del otro lado, $y_{-3}<0$ y $m=-3$ dan el mismo $\lambda>0$.

**Aplicación inmediata:** en O2 se recorre la relación en el otro sentido: con la longitud de onda conocida se obtiene el espaciado. Después, en O1, calcula una posición para cada color antes de restarlas.

**Comprueba el apoyo visual:** pregunta 38 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Lectura de figuras y ejemplos de las fuentes|autoevaluación de figuras y ejemplos]].

**Pausa y aplicación:** responde la pregunta 9 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]], la 14 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y las 31–33 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]]. Practica [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija|O1–O3]], explicando qué distancia representa cada resultado.

## Cómo justificar el planteo al pasar a la práctica

Una resolución comprensible deja visibles cinco decisiones:

1. **Situación y dibujo:** dirección de la luz, medios, superficie y normal; o eje, focos, objeto y elementos; o rendijas, pantalla y punto observado.
2. **Modelo y supuestos:** por ejemplo, “interfaz plana y estacionaria”, “lente delgada paraxial” o “fuentes en fase y pantalla lejana cerca del centro”.
3. **Relación y razón para elegirla:** Snell relaciona índices y ángulos; la ecuación de imagen relaciona objeto, imagen y focal; la condición de máximo relaciona diferencia de camino y longitud de onda.
4. **Álgebra y sustitución:** fija signos, despeja antes de poner números y conserva las unidades.
5. **Interpretación y control:** hacia dónde se desvía el rayo; dónde queda la imagen y cómo es; desde qué referencia se mide la separación de franjas.

Una frase como “uso $s'=fs/(s-f)$” no alcanza por sí sola. Puedes escribir: “Aproximo el espejo esférico como paraxial; al ser convexo, tomo $f<0$. Con objeto real uso $s>0$ y la ecuación del espejo. El resultado $s'<0$ sitúa la imagen virtual detrás; el aumento positivo menor que uno confirma que es derecha y reducida”. La fórmula queda vinculada a una decisión física verificable.

**Cierre de la unidad:** [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Repaso del módulo|repaso del módulo]] · [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica|resoluciones para comparar después del intento]].

**Comprobar la lectura de los nuevos apoyos:** [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Lectura de figuras y ejemplos de las fuentes|preguntas 34–38 con explicaciones plegables]].

## Fuentes consultadas

- [Capítulo 33, Naturaleza y propagación de la luz](zotero://select/library/items/9VRFKAHP), PDF pp. 3–5: frentes, rayos, índice y Snell; pp. 8–9: ejemplos 33.1–33.2 de refracción e índice; pp. 10–12: reflexión total y guías; pp. 24–25: Huygens y construcción de las leyes de reflexión y refracción.
- [Capítulo 34, Óptica geométrica](zotero://select/library/items/N9GX45A9), PDF pp. 1–3: imágenes y signos; pp. 5–9: espejo esférico, aproximación paraxial, foco y aumento, con ejemplos 34.1–34.2; pp. 14–15: refracción esférica; p. 17: profundidad aparente, ejemplo 34.7; pp. 18–22: lentes delgadas, triángulos de imagen y fabricante de lentes, con ejemplo 34.8.
- [Capítulo 35.1, Interferencia y fuentes coherentes](zotero://select/library/items/69KMJR6V), PDF pp. 2–7: coherencia, superposición, máximos y mínimos, geometría lejana y aproximación de ángulo pequeño.
- [Clase de Óptica Geométrica del 09-09-2024](zotero://select/library/items/7DIU9RYN), PDF pp. 2–4 y 16–17 (diapositivas impresas 24–26 y 39–40): convenio cartesiano, imagen en espejo plano, comparación de espejos y casos de lentes convergentes y divergentes. Los recortes incorporados corresponden a PDF pp. 3–4 y 16–17; la convención se contrasta explícitamente con la del vault.
- [TP 3: Óptica Geométrica 2025](zotero://select/library/items/BTZMSRB8), problemas 1–16, para los tipos de planteo enlazados.
- [Modelo del segundo parcial 2023](zotero://select/library/items/YIXUYDMC), problema 1, para el formato de doble rendija.

Las figuras PNG son recortes de las fuentes identificadas en sus pies. Los ejemplos 33.1, 33.2, 34.1, 34.7, 34.8 y 35.1 conservan los datos del libro; sus explicaciones y pasos de cálculo se redactaron para el vault. El caso conceptual de cubrir parcialmente el espejo procede del ejemplo 34.2. Los restantes ejemplos didácticos y los esquemas SVG son elaboración del vault a partir de estos modelos físicos. No son nuevos enunciados de examen. La procedencia y el alcance de las fuentes se registran en [[Recursos de estudio/Fuentes y cobertura/Fuentes Zotero y probabilidad#Óptica: modelos, TP y fuentes teóricas]].
