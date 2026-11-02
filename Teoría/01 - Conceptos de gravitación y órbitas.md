---
tags: [fisica-aplicada, teoria, gravitacion, conceptos]
---

# Conceptos — Gravitación y órbitas

**Recorrido:** [[Teoría/01 - Gravitación y órbitas|Índice]] · [[Teoría/01 - Fórmulas aplicadas de gravitación y órbitas|Fórmulas]] · [[Ejercicios/01 - Gravitación y órbitas|Práctica]] · [[Resoluciones/01 - Gravitación y órbitas|Resoluciones]]

Esta nota desarrolla el hilo físico que conecta los conceptos con las ecuaciones. Para cada relación, busca responder tres preguntas: **qué describe**, **de qué idea sale** y **qué supuesto permite usarla**. Después de comprender ese hilo, usa la nota de [[Teoría/01 - Fórmulas aplicadas de gravitación y órbitas]] como formulario de cálculo.

## Qué debes poder explicar

- Qué expresa la ley universal de gravitación y por qué la distancia se mide entre centros.
- Cómo se pasa de fuerza gravitatoria a campo y luego a peso.
- Por qué la contribución de varias masas se suma como vector.
- Qué cambia al subir sobre un planeta o al medir el peso en un planeta que rota.
- Cómo la gravedad puede mantener un satélite en caída libre alrededor del planeta.
- De dónde salen la energía potencial gravitatoria, la energía de una órbita y la rapidez de escape.
- Qué relación descubrió Kepler y bajo qué condición se puede comparar una órbita con otra.

## 0. El modelo que vamos a usar

La gravitación newtoniana es un modelo para describir la atracción entre masas. En estos ejercicios se supone que las velocidades son mucho menores que la rapidez de la luz y que los campos gravitatorios no son tan intensos como para requerir relatividad.

### De la observación a la ley de Newton

Newton reunió en una sola ley fenómenos que antes parecían distintos: la caída de los objetos cerca de la Tierra y el movimiento de la Luna y los planetas. La ley establece dos dependencias:

1. Si aumenta cualquiera de las masas, aumenta la fuerza; la fuerza es proporcional al producto de las masas.
2. Si aumenta la distancia entre los centros, la fuerza disminuye como el cuadrado de esa distancia.

Al reunirlas, para dos masas puntuales se obtiene la magnitud

$$
F_g=G\frac{Mm}{r^2}.
$$

![[imagenes/ley-gravitacion-dos-masas-libro.png|500]]

*Figura 12.1, recortada del capítulo 12, p. 384 (PDF, p. 2). Cada masa atrae a la otra a lo largo de la línea que las une; las dos fuerzas tienen igual módulo y sentidos opuestos.*

Esta relación es la **ley universal de gravitación**. En este nivel se toma como una ley general de interacción, respaldada por observaciones y experimentos; luego se combina con las leyes de Newton para explicar caídas y órbitas. Por eso el razonamiento va desde la ley gravitatoria hacia la fórmula orbital, y no al revés. Que la ley sea *universal* significa que la misma relación describe la atracción entre cualquier par de masas, aquí o en cualquier otro lugar: la fuerza depende del producto de sus masas y del cuadrado de la distancia que las separa. La constante $G$ fija la intensidad de esa interacción. También es universal dentro del modelo: su valor es el mismo para todos esos pares y lugares, y se determina experimentalmente. Cavendish la midió con una balanza de torsión, observando la atracción diminuta entre esferas de masas y separación conocidas.

> [!note] ¿Por qué la fórmula de una órbita circular no es el punto de partida?
> La rapidez orbital se obtiene para un caso particular: un cuerpo de masa $m$ que recorre un círculo de radio $r$ alrededor de una masa central $M$, mucho mayor que $m$. Suponemos una órbita ideal y que no actúan otras fuerzas radiales. Entonces la segunda ley de Newton dice que la fuerza gravitatoria debe proporcionar la fuerza neta hacia el centro que requiere el movimiento circular:
>
> $$
> G\frac{Mm}{r^2}=m\frac{v^2}{r}.
> $$
>
> Al cancelar $m$ y despejar, resulta $v=\sqrt{GM/r}$. Así se ve el orden: primero usamos la ley gravitatoria y las leyes del movimiento; como consecuencia obtenemos la rapidez necesaria para esa órbita circular. Esa fórmula orbital no explica por sí sola por qué existe la atracción ni demuestra que la misma regla describa otros casos, como una caída o una órbita de otra forma. La derivación detallada aparece en [[#5. Órbita circular: caída libre alrededor del planeta|la sección sobre órbita circular]].

![[imagenes/balanza-cavendish-libro.png|800]]

*Figura 12.4, recortada del capítulo 12, p. 385 (PDF, p. 3). La atracción entre masas desplaza una varilla suspendida; la desviación amplificada por el láser permite medir la fuerza y determinar $G$.*

- $M$ y $m$: masas que se atraen, en kilogramos.
- $r$: distancia entre sus centros, en metros.
- $G\approx6.67\times10^{-11}\,\mathrm{N\,m^2/kg^2}$.
- $F_g$: módulo de la fuerza, en newtons.

La dependencia $1/r^2$ permite anticipar cómo cambia la fuerza sin recalcular todo: al duplicar $r$, la fuerza queda en $1/4$; al triplicar $r$, queda en $1/9$. La fuerza siempre apunta a lo largo de la línea que une los centros y es atractiva.

> [!important] Magnitud y dirección son dos partes del modelo
> La fórmula anterior calcula el **módulo**. Para saber hacia dónde apunta, dibuja la línea entre las masas: cada cuerpo es atraído hacia el otro. Si llamamos $A$ y $B$ a los cuerpos, la tercera ley de Newton dice que la fuerza de $B$ sobre $A$ y la fuerza de $A$ sobre $B$ tienen igual módulo y sentidos opuestos:
>
> $$
> \vec F_{A\leftarrow B}=-\vec F_{B\leftarrow A}.
> $$
>
> Eso **no** significa que tengan igual aceleración. La segunda ley se aplica a cada cuerpo por separado, $\vec a=\vec F/m$. Para dos masas $m_A$ y $m_B$ separadas una distancia $r$, la interacción gravitatoria produce aceleraciones de módulos
>
> $$
> a_A=\frac{Gm_B}{r^2},
> \qquad
> a_B=\frac{Gm_A}{r^2}.
> $$
>
> Cada aceleración apunta hacia el otro cuerpo y su razón es $a_A/a_B=m_B/m_A$. Si las masas son distintas, las aceleraciones también: el cuerpo menos masivo cambia su movimiento más. La fuerza mutua sigue siendo igual en ambos; lo que cambia es cuánto acelera cada masa al recibir esa fuerza.

### Cuándo puede tratarse un cuerpo como una masa puntual

La ley se formula primero para masas puntuales. El teorema de las capas esféricas permite extenderla a una esfera con distribución de masa esféricamente simétrica: aunque la esfera esté hecha de muchas partes, sus atracciones se combinan de modo que, **en un punto exterior**, el resultado es igual al de toda la masa concentrada en el centro. Por eso, para un objeto sobre la superficie o a cierta altura, usamos la distancia del objeto al centro del planeta.

![[imagenes/simetria-esferica-masa-puntual-libro.png|500]]

*Figura 12.2, recortada del capítulo 12, p. 384 (PDF, p. 2). Para puntos exteriores, la fuerza entre dos cuerpos esféricamente simétricos se calcula como si sus masas estuvieran concentradas en sus centros.*

### ¿Y si el punto está dentro del planeta?

Para calcular el campo en un punto interior de una esfera esféricamente simétrica, no se puede usar toda la masa del planeta como si estuviera concentrada en el centro. El teorema de las capas esféricas dice que las capas situadas **más lejos del centro que el punto** se atraen en direcciones que se compensan exactamente: su contribución neta al campo dentro de esas capas es cero. La masa que sí queda encerrada dentro del radio $r$, en cambio, produce el mismo campo que produciría si estuviera concentrada en el centro. Por eso, a una distancia $r<R$ del centro, solo cuenta la masa encerrada $M_{\text{enc}}(r)$:

$$
g(r)=G\frac{M_{\text{enc}}(r)}{r^2},
\qquad 0<r<R.
$$

El campo apunta hacia el centro; sobre un objeto de masa $m$, la fuerza es $F_g=m g(r)$. En el centro, la simetría hace que las atracciones se compensen en todas las direcciones y el campo neto es cero.

**Ejemplo: esfera de densidad uniforme.** Si la masa total es $M$ y el radio es $R$, la masa encerrada crece como el volumen de la esfera interior: $M_{\text{enc}}(r)=M(r/R)^3$. Entonces

$$
g(r)=G\frac{M r}{R^3}=g_{\text{superficie}}\frac{r}{R},
\qquad g_{\text{superficie}}=\frac{GM}{R^2}.
$$

En este modelo idealizado, la gravedad disminuye al acercarse al centro y aumenta linealmente desde cero hasta el valor superficial. Esa variación lineal depende de que la densidad sea uniforme; en un planeta con densidad variable hay que conocer cómo se distribuye la masa para hallar $M_{\text{enc}}(r)$. Para puntos exteriores, en cambio, se usa la masa total $M$ y la distancia al centro. Tampoco se debe medir $r$ desde la superficie si el enunciado entrega una altura.

> [!abstract] Supuestos frecuentes en estos ejercicios
> - Se modelan los planetas y estrellas como esferas simétricas vistas desde fuera.
> - En la aproximación de dos cuerpos para un planeta y un objeto, se conserva su interacción mutua y se omiten las contribuciones gravitatorias de los demás cuerpos.
> - Para una órbita circular ideal, solo actúa la gravedad; se desprecian el aire y los empujes.
> - Para comparar órbitas planetarias, la masa del planeta que orbita es pequeña frente a la masa central; por eso se puede aproximar el astro central como fijo, aunque también acelera.
> - La rapidez de escape es el umbral para llegar muy lejos con rapidez final tendiendo a cero, sin resistencia del aire ni aporte posterior de energía.

> [!note] ¿Qué significa «aislar» un cuerpo y tratarlo como cuerpo de prueba?
> **Aislar el sistema** es decidir qué cuerpos se incluirán explícitamente en el modelo. Por ejemplo, en una aproximación de dos cuerpos estudiamos un satélite y la Tierra, e ignoramos las contribuciones del Sol, la Luna y los demás cuerpos. Sus atracciones siguen existiendo: simplemente no las sumamos en esa aproximación. El campo completo en el punto sería $\vec g_{\text{Tierra}}+\vec g_{\text{Sol}}+\vec g_{\text{Luna}}+\cdots$; el modelo simplificado usa solo $\vec g_{\text{Tierra}}$. Esto es aceptable cuando las contribuciones omitidas son pequeñas para la pregunta, el intervalo de tiempo y la precisión buscada. Si son relevantes, hay que incluirlas.
>
> Llamamos **cuerpo de prueba** al objeto pequeño de masa $m$ que usamos para estudiar el campo de una fuente de masa $M$. Su masa se considera mucho menor que $M$, de modo que el objeto siente la atracción de la fuente sin cambiar de manera apreciable el movimiento de esta. La fuente también siente una fuerza de igual módulo y sentido contrario, pero, al tener mucha más masa, su aceleración $F/M$ es mucho menor que la del objeto, $F/m$. En ejercicios introductorios suele aproximarse la fuente como fija; eso simplifica el movimiento, pero no elimina la fuerza de reacción. Si otros cuerpos tienen efectos importantes, se incluyen sus campos en la suma y luego se calcula la fuerza sobre el objeto con $\vec F=m\vec g_{\text{total}}$.

## 1. De fuerza gravitatoria a campo y peso

### Fuerza: interacción entre dos masas

En la ley de gravitación, $M$ puede ser el planeta y $m$ un objeto cercano. El módulo es

$$
F_g=G\frac{Mm}{r^2}.
$$

Para escribir la dirección de la fuerza con precisión, definimos primero el vector de separación desde la fuente $M$ hasta el objeto $m$. Si sus posiciones son $\vec R_M$ y $\vec R_m$, respectivamente, entonces

$$
\vec r=\vec R_m-\vec R_M,
\qquad
r=|\vec r|.
$$

El vector $\vec r$ apunta desde la fuente hacia el objeto y su módulo $r$ es la distancia entre ellos. El **vector unitario** $\hat{\mathbf r}$ conserva esa dirección, pero se normaliza para que su módulo sea uno:

$$
\hat{\mathbf r}=\frac{\vec r}{|\vec r|}=\frac{\vec r}{r}.
$$

Dividir por el módulo quita las unidades y el tamaño del vector original, pero no su dirección. Por ejemplo, si la fuente está en el origen y el objeto en $(3,4)\,\mathrm{m}$, entonces $\vec r=(3,4)\,\mathrm{m}$, $r=5\,\mathrm{m}$ y $\hat{\mathbf r}=(3/5,4/5)$. La gravedad sobre el objeto apunta en sentido opuesto, hacia la fuente. Si el módulo de esa fuerza es $F_g$, sus componentes son $(-3F_g/5,-4F_g/5)$; los dos signos negativos indican que apunta hacia el origen:

$$
\vec F_g=-G\frac{Mm}{r^2}\hat{\mathbf r}.
$$

El signo menos indica que la fuerza apunta en sentido contrario a $\hat{\mathbf r}$, es decir, hacia la fuente.

### Campo: describir lo que la fuente produce en cada punto

A veces interesa conocer primero el efecto del planeta en un punto, sin elegir todavía qué objeto colocaremos allí. Para eso definimos el **campo gravitatorio** como la fuerza por unidad de masa de prueba:

$$
\vec g=\frac{\vec F_g}{m}.
$$

Al sustituir la ley de gravitación, la masa de prueba se cancela:

$$
\vec g
=\frac{-GMm\,\hat{\mathbf r}/r^2}{m}
=-G\frac{M}{r^2}\hat{\mathbf r}.
$$

Por lo tanto, el módulo del campo de una fuente es

$$
g=G\frac{M}{r^2}.
$$

La cancelación explica dos hechos:

- El campo en un punto depende de la masa que lo produce y de la distancia a ella, no del objeto de prueba.
- Si solo actúa la gravedad, la aceleración de un objeto de prueba es $\vec a=\vec F_g/m=\vec g$. Por eso, dos objetos de masas distintas, comparados por separado en el mismo punto, tienen la misma aceleración gravitatoria aunque sus fuerzas sean distintas: $\vec F_g=m\vec g$ aumenta en proporción a la masa y, al calcular $\vec a=\vec F_g/m$, esa masa se cancela.
- Esta conclusión describe el movimiento de los objetos de prueba en el campo de una fuente tomada como fija o muy poco afectada. No contradice la tercera ley: en cada caso la fuente recibe una fuerza de igual módulo y sentido opuesto. Si se estudia el movimiento de ambos cuerpos, sus aceleraciones se calculan individualmente y dependen de la masa del otro cuerpo que los atrae.

> [!example] Dos situaciones que no deben confundirse
> **Par de cuerpos que interactúan entre sí:** las fuerzas gravitatorias sobre ambos tienen igual módulo y sentidos opuestos. Sus aceleraciones se calculan dividiendo cada fuerza por la masa del cuerpo correspondiente; por eso, en general, son distintas.
>
> **Objetos de prueba en un mismo campo:** comparemos por separado un objeto de $1\,\mathrm{kg}$ y otro de $2\,\mathrm{kg}$ cerca de la superficie terrestre, donde $g\approx9.8\,\mathrm{m/s^2}$. Sus pesos tienen módulos $9.8\,\mathrm{N}$ y $19.6\,\mathrm{N}$, respectivamente, pero al dividir cada peso por su masa ambos dan una aceleración de $9.8\,\mathrm{m/s^2}$ hacia abajo. Se supone que la gravedad es la única fuerza relevante y se desprecia el aire.
>
> En síntesis: **en una interacción mutua, las fuerzas son iguales y opuestas, pero las aceleraciones suelen ser distintas; en un mismo campo, distintas masas reciben fuerzas distintas, pero la aceleración gravitatoria es la misma**, si la gravedad es la única fuerza relevante.

La unidad del campo puede escribirse $\mathrm{N/kg}$ o $\mathrm{m/s^2}$: son equivalentes porque $1\,\mathrm{N}=1\,\mathrm{kg\,m/s^2}$. No confundas $G$, que es una constante universal, con $g$, que es el campo local y cambia de un lugar a otro.

![[imagenes/campo-gravitatorio.svg]]

### Peso: la fuerza gravitatoria sobre un objeto

La fuerza gravitatoria sobre una masa cercana a un planeta se llama su **peso gravitatorio**:

$$
\vec W=\vec F_g=m\vec g,
\qquad
W=mg \quad\text{para los módulos}.
$$

La **inercia** es la propiedad por la que un cuerpo conserva su estado de movimiento: si está en reposo, permanece en reposo; si ya se mueve, mantiene su velocidad —módulo y dirección— mientras la fuerza neta sobre él sea cero. Una fuerza neta cambia esa velocidad y produce aceleración.

La **masa inercial** cuantifica cuánta resistencia ofrece el cuerpo a ese cambio. Lo vemos en la segunda ley de Newton:

$$
\vec F_{\text{neta}}=m\vec a.
$$

Para una misma fuerza neta, un cuerpo con más masa adquiere menos aceleración; para producir la misma aceleración en una masa mayor hace falta una fuerza proporcionalmente mayor. Por ejemplo, una fuerza neta de $2\,\mathrm{N}$ produce $2\,\mathrm{m/s^2}$ en una masa de $1\,\mathrm{kg}$, y $1\,\mathrm{m/s^2}$ en una de $2\,\mathrm{kg}$.

En la ecuación del peso, $\vec W=m\vec g$, la masa también determina cuánta fuerza gravitatoria recibe el objeto. En el modelo newtoniano usamos la misma $m$ para describir su inercia y su interacción gravitatoria. En caída libre ideal, donde la gravedad es la única fuerza, al comparar módulos queda

$$
a=\frac{F_g}{m}=\frac{mg}{m}=g.
$$

Al aumentar la masa, aumentan en la misma proporción tanto la fuerza gravitatoria como la inercia. Así se entiende por qué masas distintas caen con la misma aceleración si se desprecia el aire.

En este modelo clásico, la masa del objeto se mantiene al trasladarlo, mientras que el peso sí cambia si cambia el campo gravitatorio. Por ejemplo, el mismo objeto tiene pesos distintos en la superficie de la Tierra y de Marte.

Cerca de la superficie terrestre solemos usar $g\approx9.8\,\mathrm{m/s^2}$, pero ese valor es una aproximación local. Para calcularlo desde la masa y el radio del planeta se combina la ley de Newton con la definición de campo:

$$
g_{\text{superficie}}
=\frac{F_g}{m}
=\frac{GMm/R^2}{m}
=\frac{GM}{R^2}.
$$

Aquí $R$ es el radio del planeta y $M$ su masa. La última expresión muestra cómo la gravedad superficial depende de la masa y del tamaño del planeta.

## 2. Varias masas: los campos se suman como flechas

En un punto $P$, cada masa fuente produce un campo gravitatorio. El principio de superposición dice que, en el modelo newtoniano, el campo resultante de todas las fuentes **que decidimos incluir** se obtiene sumando sus campos vectorialmente:

$$
\vec g_{\text{total}}=\sum_i\vec g_i.
$$

Esta suma de campos no depende de la masa del objeto que pudiera colocarse en $P$. Estrictamente, lo que sumamos aquí son **campos**, no fuerzas. Si colocamos allí una masa de prueba $m$, cada fuente ejerce una fuerza $\vec F_i=m\vec g_i$ y la fuerza total resulta

$$
\vec F_{\text{total}}=m\vec g_{\text{total}}.
$$

Por ejemplo, el campo completo debido a la Tierra y la Luna en un punto es $\vec g_{\text{Tierra}}+\vec g_{\text{Luna}}$. En una aproximación que ignora la influencia lunar, usamos solo $\vec g_{\text{Tierra}}$; no afirmamos que la Luna deje de atraer. Si el efecto lunar importa para el resultado o la precisión buscada, se agrega su campo vectorial. Así, **superposición** explica cómo combinar las fuentes incluidas y **aislar el sistema** explica por qué una aproximación puede dejar algunas fuentes fuera.

Esto convierte un problema de muchas fuerzas en una suma ordenada:

1. Marca el punto donde se busca el campo y dibuja una flecha desde ese punto hacia cada masa fuente.
2. Calcula cada módulo con $g_i=GM_i/r_i^2$.
3. Asigna ejes y descompón las flechas en componentes con signo.
4. Suma primero las componentes; recién al final calcula el módulo y la dirección del resultado.

En dos dimensiones,

$$
g_x=\sum_i g_{ix},
\qquad
g_y=\sum_i g_{iy},
\qquad
|\vec g|=\sqrt{g_x^2+g_y^2}.
$$

Si dos componentes horizontales son iguales y opuestas, se cancelan. Si apuntan en el mismo sentido, se suman. La simetría puede simplificar el cálculo, pero hay que justificarla mirando la geometría.

El ejemplo del libro muestra la suma de dos fuerzas sobre una estrella pequeña. La resultante se obtiene sumando las componentes de cada vector, no agregando directamente sus módulos.

![[imagenes/superposicion-fuerzas-gravitatorias-libro.png|750]]

*Figura 12.5, recortada del capítulo 12, p. 386 (PDF, p. 4). Las fuerzas $\vec F_1$ y $\vec F_2$ se combinan para producir la fuerza total $\vec F$.*

![[imagenes/campo-no-simetrico.svg]]

> [!example] Qué significa que el campo total sea cero
> En un punto donde dos campos se cancelan, la fuerza gravitatoria neta sobre una masa de prueba también es cero en ese instante. Cada fuente sigue atrayéndola; el resultado cero aparece por la suma de fuerzas opuestas, no porque haya desaparecido la gravedad.

## 3. Altura: por qué usamos $R+h$

La ley de gravitación necesita la distancia entre centros. Para un objeto a altura $h$ sobre un planeta de radio $R$, el radio de la trayectoria desde el centro es

$$
r=R+h.
$$

![[imagenes/orbita-satelite.svg|700]]

*Esquema del vault: la distancia orbital $r$ parte del centro y se compone del radio del planeta $R$ más la altura $h$.*

Al sustituirlo en la expresión del campo,

$$
g(h)=\frac{GM}{(R+h)^2}.
$$

En la superficie, $g_0=GM/R^2$. Dividir ambas expresiones permite comparar el campo a la altura $h$ con el de la superficie sin conocer $G$ ni $M$:

$$
\frac{g(h)}{g_0}
=\frac{GM/(R+h)^2}{GM/R^2}
=\left(\frac{R}{R+h}\right)^2.
$$

Una **razón** es el cociente entre dos cantidades del mismo tipo. El denominador es el valor que elegimos como referencia; por eso, el orden de la división determina la pregunta. En $g(h)/g_0$ comparamos el campo a la altura $h$ con el superficial. Si $h>0$, el objeto está más lejos del centro y $g(h)<g_0$, así que esta razón queda entre $0$ y $1$: indica qué fracción del campo superficial queda a esa altura. Si invertimos el cociente, $g_0/g(h)$, dividimos el valor mayor por el menor y obtenemos cuántas veces el campo superficial supera al de esa altura. Las dos razones son recíprocas.

Para el mismo objeto, $W=mg$, de modo que el cociente de pesos es igual al cociente de campos:

$$
\frac{W(h)}{W_0}=\frac{g(h)}{g_0}.
$$

**Ejemplo de interpretación.** Si $h=R$, el objeto está a $2R$ del centro. Entonces

$$
\frac{g(h)}{g_0}=\left(\frac{R}{2R}\right)^2=\frac14.
$$

El campo a esa altura es **un cuarto** del superficial. Si comparamos en el orden contrario, $g_0/g(h)=4$: el campo superficial es **cuatro veces** el campo a esa altura. La disminución desde la superficie es $1-1/4=3/4$, es decir, un $75\%$ del valor superficial. Estas tres expresiones describen la misma comparación desde preguntas distintas. La altura no es el radio que se introduce directamente en la ley: primero se suma al radio del planeta.

### Por qué cerca del suelo se suele usar $W=mg$ con $g$ constante

Cuando la altura es pequeña comparada con $R$, la distancia al centro cambia muy poco durante el movimiento. El campo también cambia muy poco, y podemos aproximarlo por su valor superficial constante. Esta aproximación sirve para movimientos cotidianos cerca del suelo; para satélites o grandes alturas conviene conservar la dependencia con $r$.

La aproximación local $mgh$ para la energía potencial se obtiene con más detalle en la sección 7.

## 4. Peso aparente en el ecuador de un planeta que rota

El **ecuador** es la línea imaginaria que rodea el planeta por su parte más ancha, en un plano perpendicular al eje de rotación. Está a mitad de camino entre los polos (latitud $0^\circ$); no es una franja material ni una órbita. En el modelo esférico de esta sección, una persona parada allí está a distancia $R$ del centro y, al girar el planeta, recorre una circunferencia de radio $R$ alrededor del eje.

### Qué significa la fuerza normal $N$ y qué registra el instrumento

La **fuerza normal** es la fuerza de contacto que una superficie ejerce sobre un cuerpo; se llama normal porque apunta perpendicularmente a la superficie. Si una persona está parada sobre una báscula horizontal, la báscula empuja a la persona hacia arriba y la persona la comprime hacia abajo. Esas dos fuerzas forman un par de acción y reacción: tienen igual módulo y sentidos opuestos, pero actúan sobre cuerpos distintos. El sensor de la báscula responde a esa compresión y registra su módulo, que coincide con el módulo de la fuerza normal $N$ que actúa sobre la persona.

Por eso el instrumento **no mide directamente la fuerza gravitatoria**. La gravedad tira de la persona hacia el planeta; la superficie la empuja y evita que la atraviese. La lectura depende de cuánto empuje de contacto hace falta para que la persona siga el movimiento que le corresponde. La normal no vale siempre $mg$: vale eso solo en situaciones particulares, por ejemplo, una persona en reposo sobre una superficie horizontal en un modelo sin rotación ni otras aceleraciones verticales.

En ejercicios, «balanza» suele usarse aquí para una báscula con sensor de fuerza. Si la lectura se expresa en newtons, indica directamente $N$. Si una báscula doméstica muestra kilogramos, convierte la fuerza detectada a una masa equivalente, aproximadamente $m_{\text{indicado}}=N/g_{\text{ref}}$, usando como referencia la gravedad terrestre; no está midiendo de nuevo la masa real de la persona. La masa real sigue siendo la misma aunque cambie la lectura.

### Diagrama de fuerzas en el ecuador

Como la persona gira junto con el planeta, su movimiento requiere una aceleración centrípeta dirigida hacia el eje de rotación. En el ecuador, el eje, el centro del planeta y la persona están alineados radialmente; por eso la aceleración apunta también hacia el centro. En el modelo esférico, las fuerzas radiales sobre la persona son la gravedad $mg$ hacia adentro y la normal $N$ de la báscula hacia afuera.

Para mantener la misma convención usada al definir $\hat{\mathbf r}$, tomamos ahora **hacia afuera** (desde el centro hacia la persona) como sentido radial positivo. La gravedad apunta hacia adentro, así que su componente es $-mg$; la normal apunta hacia afuera y su componente es $+N$. La aceleración centrípeta también apunta hacia adentro y su componente es $-a_c$. La segunda ley queda

$$
N-mg=-ma_c.
$$

Al despejar, obtenemos $N=m(g-a_c)$. Aquí $g$ y $a_c$ son **módulos**, por eso se escriben como cantidades positivas; los signos de las componentes ya están incluidos en la ecuación anterior.

Al dividir por la masa de la persona,

$$
g_{\text{aparente}}
=\frac{N}{m}
=g-a_c
=\frac{GM}{R^2}-\frac{v^2}{R}.
$$

La componente radial de la gravedad sí es negativa con esta convención: $g_r=-g$. Pero $g_{\text{aparente}}=N/m$ no es esa componente: es el módulo de la fuerza que la báscula ejerce por unidad de masa y, mientras haya contacto, no puede ser negativo. Si el planeta no rota, $a_c=0$ y la lectura por unidad de masa es $g$. Al aumentar la rotación, disminuye hasta cero cuando $a_c=g$. Si la fórmula diera $N<0$ (es decir, $a_c>g$), significaría que se necesitaría que la superficie tirase de la persona hacia adentro; una báscula común no puede hacerlo, así que la persona perdería contacto y el modelo de «parada sobre la superficie» dejaría de ser válido.

### Del período y la frecuencia a la aceleración centrípeta

El **período** $T$ es el tiempo que tarda el planeta en completar una vuelta. Se mide en segundos (s). La **frecuencia** $f$ cuenta cuántas vueltas completa por segundo; su unidad es el hertz, donde $1\,\mathrm{Hz}=1$ vuelta por segundo. Como una vuelta tarda $T$ segundos, en un segundo se completa $1/T$ de vuelta:

$$
f=\frac{1}{T},
\qquad
T=\frac{1}{f}.
$$

Una vuelta completa barre un ángulo de $2\pi$ radianes. Por eso la rapidez angular, que mide cuántos radianes se recorren por segundo, es

$$
\omega=\frac{2\pi}{T}=2\pi f.
$$

En el ecuador, una persona recorre una circunferencia de radio $R$. En una vuelta recorre su longitud, $2\pi R$, y tarda $T$ segundos; por tanto su rapidez tangencial es

$$
v=\frac{2\pi R}{T}=\omega R.
$$

La rapidez cambia la dirección del movimiento circular, y eso requiere una aceleración centrípeta de módulo $a_c=v^2/R$. Sustituyendo la rapidez recién obtenida:

$$
a_c=\frac{v^2}{R}
=\frac{(2\pi R/T)^2}{R}
=\frac{4\pi^2R}{T^2}.
$$

Usando $f=1/T$ o $\omega=2\pi/T$, la misma relación se escribe

$$
a_c=4\pi^2f^2R=\omega^2R.
$$

Así se ve de dónde sale la corrección por rotación: la gravedad no desaparece; la diferencia entre la gravedad y la normal es la fuerza neta hacia adentro que produce esta aceleración centrípeta. **Para resolver un ejercicio**, convierte primero $T$ a segundos, usa el radio de la trayectoria (en el ecuador, $R$) y calcula $a_c$ con cualquiera de las formas equivalentes. Si se duplica el período, por ejemplo, $a_c$ pasa a ser la cuarta parte, porque depende de $1/T^2$.

![[imagenes/gravedad-rotacion-jupiter.svg]]

El resultado es una lectura de balanza menor que el peso gravitatorio $mg$: parte de la gravedad proporciona la aceleración necesaria para que la persona gire con el planeta, y la balanza sostiene el resto. Aquí $g_{\text{aparente}}=N/m$ describe lo que indica la balanza por unidad de masa; no significa que la atracción gravitatoria real haya disminuido por ese mismo término. Esta fórmula corresponde al ecuador y a un modelo esférico; en otras latitudes la trayectoria circular alrededor del eje tiene otro radio y la dirección centrípeta ya no coincide exactamente con la dirección al centro. El ejercicio de Júpiter del TP usa precisamente esta corrección.

> [!example] Comparación con un planeta que no rota
> Si el planeta no rotara y la persona estuviera quieta, su aceleración sería cero. Entonces $N-mg=0$ y la báscula ejercería una normal $N=mg$. En el ecuador de un planeta que rota, la persona sí acelera hacia el centro, así que la normal debe ser menor: $N=mg-ma_c$. La diferencia $ma_c$ no es una pérdida de gravedad; es la parte de la fuerza gravitatoria que queda como fuerza neta centrípeta.

## 5. Órbita circular: caída libre alrededor del planeta

### De un proyectil a un satélite

Imagina lanzar un proyectil horizontalmente desde una montaña muy alta. La gravedad curva su camino hacia la Tierra. Si se lanza con más rapidez, avanza más antes de tocar el suelo. A gran altura la superficie terrestre también se curva; si el proyectil avanza lo suficiente mientras cae, la superficie puede curvarse alejándose a la misma tasa. Entonces el proyectil sigue cayendo alrededor de la Tierra y queda en órbita.

![[imagenes/trayectorias-orbitales-libro.png|750]]

*Figura 12.14, recortada del capítulo 12, p. 393 (PDF, p. 11). Las trayectorias muestran cómo cambia el resultado al aumentar la rapidez de lanzamiento; el dibujo supone que no hay resistencia del aire.*

La imagen ayuda a entender que una órbita es una forma de caída libre: la gravedad sigue desviando el movimiento hacia la Tierra, pero la velocidad tangencial evita que el satélite llegue al suelo. En la órbita circular ideal, la distancia al centro se mantiene constante.

### Velocidad tangencial: de arco a rapidez

La **velocidad** es una magnitud vectorial: indica tanto qué tan rápido se mueve un objeto como hacia dónde lo hace. La **rapidez** es solo el módulo (el tamaño) de ese vector, sin dirección. Por eso una rapidez nunca es negativa, mientras que la velocidad puede cambiar al cambiar de dirección, aunque su módulo se mantenga igual. En estas notas, cuando una ecuación usa $v$ sin flecha, $v$ representa la rapidez; escribimos $\vec v$ cuando importa la dirección.

La **velocidad instantánea** indica hacia dónde se mueve el objeto en ese instante. Durante un intervalo finito, el objeto avanza una cuerda entre dos puntos de la órbita; al hacer ese intervalo cada vez más corto, la cuerda se aproxima a la tangente. Por eso la velocidad instantánea es tangente a la circunferencia y perpendicular al radio. En una órbita circular uniforme, la rapidez queda constante pero la velocidad cambia continuamente porque gira su dirección.

### De dónde sale la longitud de arco $s=r\theta$

Considera dos puntos de una circunferencia de radio $r$. El ángulo central $\Delta\theta$ indica cuánto giró el radio al pasar de un punto al otro; el arco $\Delta s$ es la distancia medida sobre el borde entre esos puntos. Para relacionarlos, compara ese tramo con la vuelta completa: la circunferencia entera mide $2\pi r$ y corresponde a un giro de $2\pi$ radianes. Como el arco representa la misma fracción de la vuelta que el ángulo representa de un giro completo,

$$
\frac{\Delta s}{2\pi r}
=\frac{\Delta\theta}{2\pi}.
$$

Al multiplicar ambos lados por $2\pi r$, se cancelan los $2\pi$ y queda

$$
\Delta s=r\Delta\theta.
$$

Esto requiere que $\Delta\theta$ esté en **radianes**. Esa unidad se define precisamente como la razón entre la longitud del arco y el radio: $\Delta\theta=\Delta s/r$. Así, un radián es el ángulo que abarca un arco cuya longitud es igual al radio. Si se usa el ángulo en grados, primero hay que convertirlo: $\Delta\theta_{\mathrm{rad}}=(\pi/180)\Delta\theta_{\mathrm{grados}}$.

**Ejemplo.** Para $r=3\,\mathrm{m}$ y un giro de $60^\circ=\pi/3$ rad, el arco mide

$$
\Delta s=r\Delta\theta
=(3\,\mathrm{m})\left(\frac{\pi}{3}\right)
=\pi\,\mathrm{m}\approx3{,}14\,\mathrm{m}.
$$

Son $1/6$ de la circunferencia completa, porque $60^\circ$ es $1/6$ de $360^\circ$. Si el ángulo lleva signo para indicar el sentido de giro, $r\Delta\theta$ es el desplazamiento de arco con signo; la **distancia** recorrida siempre es no negativa y vale $\Delta s=r|\Delta\theta|$.

Para obtener la rapidez tangencial, dividimos la distancia de arco por el tiempo transcurrido y hacemos el intervalo cada vez más pequeño. Con $r$ constante,

$$
v_t=\lim_{\Delta t\to0}\frac{\Delta s}{\Delta t}
=r\left|\frac{d\theta}{dt}\right|
=r\omega.
$$

La rapidez tangencial, por tanto, es cuánto arco recorre el objeto por unidad de tiempo. Aquí $\omega=|d\theta/dt|$ es la rapidez angular, medida en radianes por segundo.

Esta relación vale en cada instante para un movimiento circular de radio fijo. Si el movimiento es uniforme y una vuelta tarda un período $T$, el objeto recorre una circunferencia completa $2\pi r$ en ese tiempo:

$$
\omega=\frac{2\pi}{T},
\qquad
v_t=\frac{2\pi r}{T}.
$$

Si la rapidez cambia durante la vuelta, $2\pi r/T$ da la rapidez tangencial media; la relación instantánea sigue siendo $v_t=r\omega$. En la órbita circular, $v_t$ es la rapidez orbital. La velocidad es tangente, mientras que el radio apunta desde el centro hasta el satélite.

> [!important] No son tres velocidades distintas
> La velocidad vectorial se escribe $\vec v$. Su módulo (la rapidez) se escribe $v$. En una trayectoria circular, esa rapidez es tangencial, así que también puede escribirse $v_t$: $v_t=|\vec v|=v$. Por tanto, $v_t$ no es otro vector ni una rapidez adicional; el subíndice solo destaca que se mide a lo largo de la tangente. En cambio, $\vec a_c$ sí es otra magnitud: es un vector de aceleración que apunta desde el objeto hacia el centro y es perpendicular a $\vec v$. En las fórmulas, $a_c$ sin flecha representa su módulo.

![[imagenes/v-vt-ac-movimiento-circular.svg|900]]

*Esquema propio. La flecha verde representa la velocidad tangencial; la flecha naranja, la aceleración centrípeta. La primera indica hacia dónde se mueve el objeto en ese instante; la segunda, hacia dónde cambia su velocidad.*

### Aceleración centrípeta: del cambio de velocidad al radio

La **velocidad** es un vector, así que puede cambiar aunque su módulo permanezca constante. En el movimiento circular uniforme, dos velocidades en instantes cercanos tienen igual módulo $v_t$, pero direcciones distintas. Como cada velocidad es tangente al círculo, al girar el radio un ángulo pequeño también gira la dirección de la velocidad ese mismo ángulo. En lo que sigue, $\Delta\theta$ representa el tamaño positivo de ese giro, medido en radianes.

Para calcular cuánto difieren los vectores, dibujamos $\vec v_A$ y $\vec v_B$ con el mismo origen. Cada vector mide $v_t$, así que sus puntas quedan sobre una circunferencia de radio $v_t$ en este dibujo de velocidades. El ángulo entre ellos es $\Delta\theta$ y el segmento que une sus puntas representa $\Delta\vec v=\vec v_B-\vec v_A$. Se forma un triángulo isósceles cuyos lados iguales miden $v_t$:

$$
|\Delta\vec v|^2
=v_t^2+v_t^2-2v_t^2\cos(\Delta\theta)
=2v_t^2\bigl(1-\cos\Delta\theta\bigr).
$$

Usando $1-\cos x=2\sin^2(x/2)$ y tomando la raíz positiva para un módulo,

$$
|\Delta\vec v|
=2v_t\sin\left(\frac{\Delta\theta}{2}\right).
$$

Esta es la longitud exacta de la cuerda entre las puntas de las velocidades. Para ver por qué se aproxima a $v_t\Delta\theta$ si el giro es pequeño, dividimos por $v_t\Delta\theta$:

$$
\frac{|\Delta\vec v|}{v_t\Delta\theta}
=\frac{2\sin(\Delta\theta/2)}{\Delta\theta}
=\frac{\sin(\Delta\theta/2)}{\Delta\theta/2}
\longrightarrow 1
\qquad\text{cuando }\Delta\theta\to0.
$$

El último paso usa el límite $\lim_{x\to0}\sin x/x=1$, válido con $x$ en radianes. Por eso, para un ángulo pequeño, $|\Delta\vec v|\approx v_t\Delta\theta$: las dos longitudes son casi iguales, y su razón se acerca a uno. Para un intervalo finito no son exactamente iguales; se vuelven equivalentes en el límite de un intervalo infinitamente pequeño.

El símbolo $\lim_{\Delta t\to0}$ indica que hacemos el intervalo cada vez más corto para obtener la aceleración instantánea. Para una circunferencia de radio fijo, la relación entre arco y ángulo es exacta: $\Delta s=r\Delta\theta$, porque aquí $\Delta\theta$ representa el tamaño positivo del giro. Lo que se aproxima a la longitud del arco cuando el intervalo se hace pequeño es la cuerda que une las dos posiciones. Además, por definición, $\lim_{\Delta t\to0}\Delta s/\Delta t=v_t=v$.

![[imagenes/velocidad-tangencial-cambio-velocidad.svg|900]]

*Esquema propio. A la izquierda se ve que la velocidad sigue la tangente; a la derecha, el cambio entre dos vectores velocidad de igual módulo apunta aproximadamente hacia el centro.*

El paso algebraico consiste en multiplicar y dividir por el radio $r$. Así aparece el producto $r\Delta\theta$, que podemos reemplazar por la longitud del arco $\Delta s$:

$$
\frac{v_t\Delta\theta}{\Delta t}
=\frac{v_t}{r}\,\frac{r\Delta\theta}{\Delta t}
=\frac{v_t}{r}\,\frac{\Delta s}{\Delta t}.
$$

Ahora tomamos el límite cuando $\Delta t$ tiende a cero. El factor $v_t/r$ se mantiene en el instante que analizamos, mientras que $\Delta s/\Delta t$ tiende a la rapidez tangencial $v_t$:

$$
\begin{aligned}
a_c
&=\lim_{\Delta t\to0}\frac{|\Delta\vec v|}{\Delta t}\\
&=\lim_{\Delta t\to0}\frac{v_t\Delta\theta}{\Delta t}\\
&=\frac{v_t}{r}\lim_{\Delta t\to0}\frac{\Delta s}{\Delta t}\\
&=\frac{v_t}{r}\,v_t\\
&=\frac{v_t^2}{r}.
\end{aligned}
$$

La diferencia $\Delta\vec v$ apunta hacia el centro cuando el intervalo se hace muy pequeño; por eso también lo hace esta componente de la aceleración. Se llama **aceleración centrípeta**: “centrípeta” significa dirigida hacia el centro. La fórmula $a_c=v_t^2/r$ da la componente radial de la aceleración en una trayectoria circular.

Cuando decimos que **$a_c$ es toda la aceleración** nos referimos al **movimiento circular uniforme (MCU)**. “Uniforme” significa que la rapidez no cambia: el valor de $v$ —o $v_t$ cuando destacamos que el movimiento es tangente a la circunferencia— permanece constante. Aquí $v$ y $v_t$ representan la **rapidez**, es decir, el módulo de la velocidad vectorial; no indican su dirección. El móvil no acelera ni frena a lo largo de la circunferencia. Sin embargo, su velocidad sí cambia porque cambia continuamente su dirección; ese cambio produce la aceleración centrípeta, que apunta hacia el centro. En el MCU no hay una componente tangencial, así que la aceleración total coincide con la centrípeta: $\vec a=\vec a_c$ y $|\vec a|=a_c=v_t^2/r$.

Si la rapidez también cambia, el movimiento sigue una circunferencia, pero ya no es uniforme. Entonces hay dos componentes de aceleración: la **radial o centrípeta**, $a_c=v_t^2/r$, que cambia la dirección de la velocidad, y la **tangencial**, $a_t=dv_t/dt$, que cambia su rapidez. Como estas componentes son perpendiculares, la aceleración total es su suma vectorial y su módulo es $a=\sqrt{a_c^2+a_t^2}$. Por eso, en ese caso, $a_c$ es solo una parte de la aceleración total.

### De la aceleración a la fuerza centrípeta

La segunda ley de Newton relaciona la aceleración con la **fuerza neta** que la produce: $\sum\vec F=m\vec a$. Para conservar una trayectoria circular, la componente radial neta debe apuntar hacia el centro y tener módulo

$$
F_c=ma_c=m\frac{v_t^2}{r}.
$$

La expresión **fuerza centrípeta** nombra el papel de esa fuerza neta hacia adentro; no describe una interacción adicional. En el modelo de una órbita circular aislada, la única fuerza radial es la atracción gravitatoria, así que la gravedad hace ese papel.

![[imagenes/orbita-circular-fuerza-centripeta-libro.png|500]]

*Figura 12.15, recortada del capítulo 12, p. 394 (PDF, p. 12). En cada posición, la velocidad $\vec v$ es tangente a la órbita; la fuerza gravitatoria $\vec F_g$ y la aceleración $\vec a$ apuntan hacia el centro.*

Al mirar los vectores de la figura:

1. $\vec v$ apunta a lo largo de la tangente, así que es perpendicular al radio.
2. $\vec F_g$ apunta al centro porque la gravedad es atractiva.
3. $\vec a$ apunta en la misma dirección que la fuerza neta, según la segunda ley de Newton.
4. Como $\vec a$ es perpendicular a $\vec v$, cambia la dirección de la velocidad, no su módulo; por eso el movimiento circular puede tener rapidez constante.

Igualamos ahora la gravedad con la fuerza radial neta requerida para la órbita:

$$
\sum F_r=ma_c,
\qquad
G\frac{Mm}{r^2}=m\frac{v^2}{r}.
$$

Se cancela la masa del satélite $m$, porque aparece en ambos lados. Al despejar $v$:

$$
v_{\text{orb}}^2=\frac{GM}{r},
\qquad
v_{\text{orb}}=\sqrt{\frac{GM}{r}}.
$$

La rapidez orbital depende de la masa central $M$ y del radio orbital $r$, pero no de la masa del satélite. Esto ocurre porque una masa mayor siente una fuerza gravitatoria proporcionalmente mayor, pero también necesita proporcionalmente más fuerza para producir la misma aceleración.

Para hallar el período, usamos que una vuelta recorre la circunferencia $2\pi r$. Si tarda $T$, la rapidez es distancia dividida por tiempo:

$$
v_{\text{orb}}=\frac{2\pi r}{T}.
$$

Al sustituir esta rapidez en la ecuación orbital se obtiene

$$
\left(\frac{2\pi r}{T}\right)^2=\frac{GM}{r}
\quad\Longrightarrow\quad
T=2\pi\sqrt{\frac{r^3}{GM}}.
$$

La derivación muestra por qué un radio orbital mayor implica una rapidez circular menor y un período mayor. Ambas conclusiones dependen de que la órbita sea circular y de que la gravedad del cuerpo central domine.

## 6. Energía potencial gravitatoria: de dónde sale el signo negativo

Antes de obtener la energía potencial gravitatoria, conviene distinguir **energía**, **trabajo** y **energía cinética**. La energía es una cantidad escalar que permite llevar la cuenta de los cambios posibles en el movimiento y en la configuración de un sistema. El **trabajo** describe una transferencia de energía causada por una fuerza que actúa mientras hay desplazamiento. Solo contribuye la parte de la fuerza paralela al desplazamiento:

$$
W=\int \vec F\cdot d\vec s,
\qquad
W=Fd\cos\phi\quad\text{si la fuerza es constante}.
$$

El producto punto explica el signo: una fuerza que ayuda al desplazamiento realiza trabajo positivo; una que se opone realiza trabajo negativo; una fuerza perpendicular no realiza trabajo. El trabajo y la energía se miden en joules ($\mathrm J$), y $1\,\mathrm J=1\,\mathrm{N\,m}$.

### De dónde sale la energía cinética $K=\tfrac12mv^2$

La **energía cinética** $K$ es la energía asociada al movimiento de un objeto. Su fórmula no se elige por definición arbitraria: aparece al combinar la segunda ley de Newton con el trabajo. El trabajo neto cambia la rapidez del cuerpo y cumple el teorema trabajo–energía:

$$
W_{\text{neto}}=\Delta K=K_f-K_i.
$$

Para ver de dónde sale la expresión, consideremos el movimiento a lo largo de la trayectoria. La fuerza neta tangencial es $F_{\text{neto},t}=ma_t$, y el trabajo elemental es $dW=F_{\text{neto},t}\,ds$. Como $a_t=dv/dt$ y $v=ds/dt$, resulta $a_t\,ds=v\,dv$. Entonces:

$$
\begin{aligned}
W_{\text{neto}}
&=\int m a_t\,ds
=\int_{v_i}^{v_f}m v\,dv\\
&=\frac12m v_f^2-\frac12m v_i^2.
\end{aligned}
$$

Por eso se define $K=\tfrac12mv^2$: así, el cambio de energía cinética coincide exactamente con el trabajo neto. Se toma $K=0$ cuando el objeto está en reposo respecto del sistema de referencia elegido. La rapidez $v$ es el módulo de la velocidad; por ello $K$ no depende de la dirección instantánea, pero sí del sistema de referencia desde el que se mide el movimiento.

> [!example] Qué significa el teorema trabajo–energía
> Si el trabajo neto sobre un satélite es positivo, su energía cinética final es mayor y aumenta su rapidez. Si es negativo, disminuye. Si el trabajo neto es cero, su rapidez inicial y final tienen el mismo módulo, aunque la dirección de la velocidad pueda haber cambiado.

La gravedad disminuye al alejarse: no es correcto suponer que su magnitud es constante para cualquier cambio de altura. Para hallar la energía potencial en el caso general usamos que la fuerza gravitatoria es conservativa: el trabajo entre dos radios depende solo del punto inicial y final, no de la trayectoria.

Definimos $r$ como la distancia al centro y elegimos positivo el sentido radial hacia afuera. Como la fuerza apunta hacia el centro, su componente radial es negativa:

$$
F_r=-\frac{GMm}{r^2}.
$$

El trabajo de la gravedad al mover el objeto desde $r_1$ hasta $r_2$ es

$$
W_{\text{grav},1\to2}
=\int_{r_1}^{r_2}F_r\,dr
=GMm\left(\frac{1}{r_2}-\frac{1}{r_1}\right).
$$

El cambio de energía potencial se define como el opuesto del trabajo gravitatorio:

$$
\Delta U=U_2-U_1=-W_{\text{grav},1\to2}.
$$

Tomemos el punto inicial en $r_1$ y el final a distancia $r$; luego hacemos que $r_1$ tienda al infinito:

$$
W_{\text{grav},r_1\to r}
=GMm\left(\frac{1}{r}-\frac{1}{r_1}\right)
\xrightarrow{r_1\to\infty}\frac{GMm}{r},
\qquad
U(r)-U(\infty)
=-\lim_{r_1\to\infty}W_{\text{grav},r_1\to r}
=-\frac{GMm}{r}.
$$

Al elegir $U(\infty)=0$, resulta

$$
U(r)=-\frac{GMm}{r}.
$$

El signo negativo indica que el objeto y el planeta forman un sistema ligado: con esta referencia, acercarlos reduce la energía potencial. Al alejar el objeto, la energía potencial aumenta y se acerca a cero. El cero es una elección de referencia; las diferencias de energía potencial son las que determinan el trabajo y el movimiento.

> [!warning] La fuerza y la energía potencial no tienen la misma dependencia con la distancia
> El módulo de la fuerza cambia como $1/r^2$. La energía potencial cambia como $-1/r$. La energía potencial se obtiene acumulando el trabajo de la fuerza a lo largo de un desplazamiento; no se copia la fórmula de la fuerza cambiándole el nombre.

### Cómo se recupera $mgh$ cerca de la superficie

Entre la superficie, en $R$, y una altura $h$, el cambio exacto de energía potencial es

$$
\Delta U
=U(R+h)-U(R)
=GMm\left(\frac{1}{R}-\frac{1}{R+h}\right)
=\frac{GMm\,h}{R(R+h)}.
$$

Si $h\ll R$, entonces $R+h\approx R$ en el denominador. Además, $g_0=GM/R^2$, por lo que

$$
\Delta U\approx\frac{GMm\,h}{R^2}=m g_0 h.
$$

Así se obtiene la fórmula conocida $mgh$: es una aproximación local de la expresión más general, válida cuando el campo cambia muy poco durante el desplazamiento.

## 7. Energía de una órbita y rapidez de escape

### Energía total en una órbita circular

La **energía mecánica** reúne la energía del movimiento y la energía asociada a la configuración gravitatoria del sistema. En este modelo, $K=\tfrac12mv^2$ corresponde al movimiento del satélite y $U=-GMm/r$ a la interacción entre el satélite y el planeta:

$$
E=K+U.
$$

Esta suma se conserva si la gravedad es la única fuerza que realiza trabajo, porque es una fuerza conservativa: la energía puede cambiar de cinética a potencial y viceversa, pero la suma permanece igual. Por ejemplo, al alejarse, el satélite gana energía potencial (que se acerca a cero) y pierde energía cinética. Si un motor, el rozamiento u otra fuerza no conservativa realiza trabajo, la energía mecánica cambia en una cantidad igual al trabajo de esas fuerzas:

$$
\Delta E_{\text{mec}}=W_{\text{no conservativas}}.
$$

En una órbita circular, la relación $v_{\text{orb}}^2=GM/r$ permite escribir

$$
K=\frac12mv_{\text{orb}}^2=\frac{GMm}{2r},
\qquad
U=-\frac{GMm}{r}.
$$

Al sumarlas,

$$
E_{\text{orb}}=-\frac{GMm}{2r}.
$$

El valor negativo indica que el satélite está ligado al planeta bajo la referencia $U(\infty)=0$. Para llegar al infinito y quedar allí en reposo, su energía total debe aumentar hasta cero.

La sustitución muestra el balance: en esa órbita la energía cinética es positiva, $K=GMm/(2r)$, pero la energía potencial negativa tiene el doble de módulo, $U=-GMm/r$. Al sumarlas queda $E=-GMm/(2r)$. No se interpreta el signo negativo como una energía cinética negativa: indica que, con el cero fijado en el infinito, al sistema todavía le falta energía para quedar separado y en reposo allí.

### Rapidez mínima para escapar desde un radio dado

La **rapidez de escape** es el valor umbral del módulo de la velocidad que permite que un cuerpo se aleje indefinidamente de una masa fuente. Para entender qué significa «energía mínima para escapar», primero hay que distinguir dos preguntas:

1. **¿Cuál es la energía mecánica total en el límite de escape?** En el caso mínimo, el cuerpo llega al infinito con rapidez que tiende a cero. Como elegimos $U=0$ en el infinito, allí también $K$ tiende a cero y, por tanto, la energía total límite es $E_f=0$.
2. **¿Cuánta energía hay que agregar desde el estado actual?** Eso depende de la energía que el cuerpo ya tenga. No es lo mismo partir del reposo que estar en una órbita.

El cero no significa que escapar no requiera energía. Significa que, con la referencia de energía potencial elegida, **cero es la frontera entre un estado ligado ($E<0$) y uno no ligado ($E\geq0$)**. Usamos la aproximación habitual de una fuente $M$ fija (o mucho más masiva que $m$), sin resistencia ni empujes posteriores. En ese modelo, la energía mecánica se conserva:

$$
E=K+U=\frac12mv^2-\frac{GMm}{r}.
$$

La masa $M$ es la fuente, $m$ el objeto que escapa y $r$ la distancia inicial al centro de $M$. La rapidez $v$ se mide en el marco donde la fuente se considera en reposo. La energía potencial es negativa porque el cero se fijó en el infinito: a distancia finita, el cuerpo todavía está ligado gravitatoriamente.

### Caso 1: el objeto parte del reposo

Supongamos que el objeto está inicialmente en reposo a distancia $r$. Su energía cinética inicial es cero, pero **su energía mecánica inicial no es cero**, porque todavía tiene energía potencial gravitatoria:

$$
K_i=0,
\qquad
U_i=-\frac{GMm}{r},
\qquad
E_i=-\frac{GMm}{r}.
$$

Para dejarlo justo en el límite de escape, su energía total debe pasar de $E_i$ a $E_f=0$. La energía mínima que hay que entregarle es la diferencia entre esos estados:

$$
\Delta E_{\min}=E_f-E_i
=0-\left(-\frac{GMm}{r}\right)
=\frac{GMm}{r}.
$$

Esta es la **energía adicional requerida desde el reposo**. Si se la entregamos como energía cinética en la posición inicial, el objeto sale con la rapidez límite $v_{\text{esc}}$. En ese instante la energía potencial sigue siendo $-GMm/r$, y el balance para llegar al caso límite es

$$
\underbrace{\frac12m v_{\text{esc}}^2}_{\text{cinética necesaria en }r}
+\underbrace{\left(-\frac{GMm}{r}\right)}_{\text{potencial inicial}}
=\underbrace{0}_{\text{energía total límite en el infinito}}.
$$

Ahora despejamos sin saltar pasos:

$$
\begin{aligned}
\frac12m v_{\text{esc}}^2-\frac{GMm}{r}&=0\\
\frac12m v_{\text{esc}}^2&=\frac{GMm}{r}\\
v_{\text{esc}}^2&=\frac{2GM}{r}\\
v_{\text{esc}}&=\sqrt{\frac{2GM}{r}}.
\end{aligned}
$$

En el segundo paso se suma $GMm/r$ a ambos lados; en el tercero se multiplica por $2/m$. La masa de prueba $m$ aparece en ambos términos y se cancela: la rapidez de escape no depende de la masa del objeto, sino de la masa fuente $M$ y de la distancia $r$. Se toma la raíz positiva porque $v_{\text{esc}}$ es una **rapidez**, una magnitud no negativa.

> [!important] Qué representa cada resultado
> - $E_f=0$ es la energía mecánica total del estado límite de escape.
> - $\Delta E_{\min}=GMm/r$ es lo que se debe agregar si el objeto parte del reposo a distancia $r$.
> - $v_{\text{esc}}=\sqrt{2GM/r}$ es la rapidez total que debe tener inicialmente en ese lugar para que su energía total sea cero.
>
> La energía es una cantidad escalar; la velocidad es un vector. Por eso una energía requerida no se puede interpretar directamente como un aumento de rapidez.

### Caso 2: el objeto ya tiene velocidad

Si el objeto ya se mueve con rapidez inicial $v_i$, ya posee energía cinética. Antes de decidir cuánto aportar, calculamos la energía total de ese estado:

$$
E_i=\frac12m v_i^2-\frac{GMm}{r}.
$$

Si $E_i<0$, todavía falta energía para alcanzar el límite $E_f=0$; el aporte mínimo ideal es

$$
\Delta E_{\min}=E_f-E_i=-E_i
=\frac{GMm}{r}-\frac12m v_i^2.
$$

Si $E_i=0$, el objeto ya está justo en el umbral. Si $E_i>0$, su energía ya supera ese umbral y no necesita energía adicional para quedar en un estado no ligado, aunque la dirección de su movimiento y la forma del cuerpo central importan para que su trayectoria no choque con el planeta. Si el objeto aún está ligado ($E_i<0$) y el aporte se hace instantáneamente en el mismo radio como cambio de energía cinética, la rapidez final límite vuelve a ser $v_{\text{esc}}$; lo que cambia es cuánta energía hubo que agregar para pasar de $v_i$ a ese estado.

No se obtiene el cambio necesario de rapidez restando siempre $v_{\text{esc}}-v_i$: la velocidad tiene dirección, y el cambio de velocidad depende de cómo se orienta el empuje. Solo si el impulso es tangencial y en el mismo sentido que la velocidad inicial, el cambio de rapidez coincide con esa resta.

> [!example] Un satélite que ya está en órbita circular
> En una órbita circular de radio $r$, el satélite ya se mueve con $v_{\text{orb}}=\sqrt{GM/r}$. Por tanto,
>
> $$
> K_i=\frac{GMm}{2r},\qquad
> U_i=-\frac{GMm}{r},\qquad
> E_i=-\frac{GMm}{2r}.
> $$
>
> Para llegar al límite $E_f=0$ hay que agregar
>
> $$
> \Delta E_{\min}=0-E_i=\frac{GMm}{2r}.
> $$
>
> Es la mitad de lo requerido desde el reposo en ese mismo radio, porque el satélite ya tenía energía cinética orbital. Si se entrega como un impulso tangencial en el sentido del movimiento, su rapidez debe pasar de $v_{\text{orb}}$ a $v_{\text{esc}}=\sqrt{2GM/r}$. La energía agregada corresponde a la diferencia de energías cinéticas; no a darle de nuevo toda la energía cinética $\tfrac12m v_{\text{esc}}^2$ como si inicialmente estuviera quieto.

### Receta para resolver un ejercicio de escape

1. **Identifica el estado inicial:** reposo, órbita circular u otra rapidez inicial.
2. **Mide $r$ desde el centro** de la masa fuente; si te dan altura $h$ sobre la superficie, usa $r=R+h$.
3. **Escribe la energía inicial completa:** $E_i=K_i+U_i$, con $K_i=\tfrac12m v_i^2$ y $U_i=-GMm/r$.
4. **Fija el estado final límite:** en el infinito, $U_f=0$ y la rapidez límite tiende a cero, así que $E_f=0$.
5. **Calcula el aporte:** $\Delta E_{\min}=E_f-E_i$. Si piden rapidez de escape desde el reposo, iguala $\tfrac12m v_{\text{esc}}^2-GMm/r=0$ y despeja.
6. **Comprueba qué magnitud pide el enunciado:** rapidez total, energía adicional o cambio de velocidad son resultados distintos.

Este resultado supone que no hay resistencia del aire, motor posterior ni otras fuentes gravitatorias, y que el objeto puede seguir una trayectoria que no atraviese el cuerpo central. Una energía total negativa lo deja ligado; el caso $E=0$ es el escape límite y una energía positiva corresponde a un estado no ligado en el modelo ideal.

## 8. Kepler: del patrón observado a la relación de períodos

Kepler encontró sus leyes al analizar observaciones precisas de las posiciones planetarias. Sus relaciones describían los movimientos, aunque él no conocía la causa de la gravitación. Más tarde, Newton mostró cómo obtener esas leyes a partir del movimiento y de la gravitación. Para el parcial interesa especialmente la tercera ley: relaciona el período orbital con el tamaño de la órbita.

Para una órbita circular, ya tenemos dos relaciones:

$$
v=\frac{2\pi r}{T}
\qquad\text{y}\qquad
v^2=\frac{GM}{r}.
$$

La primera dice que rapidez es distancia recorrida por unidad de tiempo; la segunda viene de igualar la gravedad con la fuerza radial neta. Al combinarlas:

$$
\frac{4\pi^2r^2}{T^2}=\frac{GM}{r}
\quad\Longrightarrow\quad
T^2=\frac{4\pi^2}{GM}r^3.
$$

Para comparar dos cuerpos que orbitan la **misma masa central**, el factor $4\pi^2/(GM)$ es idéntico y se cancela:

$$
\frac{T_1^2}{r_1^3}=\frac{T_2^2}{r_2^3}.
$$

Esta es la forma útil para comparar, por ejemplo, la órbita de Marte con la de la Tierra alrededor del Sol. Las distancias pueden estar en cualquier unidad común si aparecen en un cociente; los períodos también deben estar en una misma unidad.

Para órbitas elípticas, el tamaño relevante es el **semieje mayor** $a$, la mitad del eje más largo de la elipse; en la relación de Kepler se usa $a$ donde en la órbita circular usamos $r$. En un círculo, $a=r$. En estos ejercicios, la masa orbitante se considera pequeña frente a la masa central. Si las dos masas fueran comparables, habría que describir el movimiento de ambas alrededor de su centro de masa e incluir las dos masas en la relación.

> [!warning] Cuándo no cancelar la constante
> Si los dos cuerpos orbitan masas centrales distintas, $GM$ no es el mismo y no se cancela. Antes de usar una razón de Kepler, verifica que ambos períodos y tamaños correspondan al mismo centro de atracción.

## Mapa: qué idea usar en cada tipo de pregunta

| Si el enunciado pide… | Empieza por… | Razón física |
|---|---|---|
| Fuerza entre dos masas | $F_g=GMm/r^2$ y dirección hacia la otra masa | Es la ley de interacción entre dos fuentes. |
| Campo o aceleración debida a varias masas | Calcular cada campo y sumarlo por componentes | La gravedad de varias fuentes se superpone vectorialmente. |
| Peso a distinta altura | $r=R+h$, luego comparar $g$ o $W$ | La ley usa distancia al centro. |
| Lectura de balanza en el ecuador | Segunda ley radial: $N-mg=-ma_c$ (radial positivo hacia afuera) | La persona necesita aceleración centrípeta hacia adentro. |
| Rapidez o período circular | Igualar gravedad con el requerimiento centrípeto | La gravedad curva la trayectoria. |
| Cambio de energía al subir mucho | $\Delta U=-W_{\text{grav}}$ | La fuerza cambia con la distancia; se integra su trabajo. |
| Energía para escapar desde una órbita | Comparar la energía orbital inicial con cero | El estado final límite en el infinito tiene energía total cero. |
| Comparación de períodos | Tercera ley de Kepler, con un mismo centro | Solo entonces la constante asociada a la masa central se cancela. |

## Secuencia sugerida

1. Lee las secciones 0–3 y explica con tus palabras la diferencia entre fuerza, campo y peso.
2. Repasa la caída libre y la órbita circular en las secciones 4–5.
3. Sigue el signo de $W_{\text{grav}}$ y $\Delta U$ en las secciones 6–7.
4. Estudia [[Teoría/01 - Fórmulas aplicadas de gravitación y órbitas]] y anota junto a cada fórmula qué supuesto la permite.
5. Resuelve [[Ejercicios/01 - Gravitación y órbitas]] sin abrir las pistas.
6. Compara con [[Resoluciones/01 - Gravitación y órbitas]] y registra qué decisión física te costó tomar.

## Fuentes consultadas

- [Capítulo 12, Gravitación](zotero://select/library/items/ATATDN6I): ley universal, acción y reacción, simetría esférica y superposición, PDF pp. 2–5 (libro pp. 384–387); campo, peso y variación con la distancia, PDF pp. 6–8 (pp. 388–390); trabajo, energía potencial, aproximación $mgh$ y escape, PDF pp. 8–11 (pp. 390–393); caída libre orbital, rapidez y período, PDF pp. 11–13 (pp. 393–395); leyes de Kepler, PDF pp. 15–17 (pp. 397–399).
- [TP 5: Gravitación, Física Aplicada 2025](zotero://select/library/items/F4BGIQ83), pp. 1–3: superposición, peso en distintos planetas y alturas, gravedad superficial, rotación, Kepler, satélites y energía.
- [Modelo del segundo parcial, Tema A, 11/11/2025](zotero://select/library/items/6GRRT3TK), pp. 1–2 escaneadas: aceleración por dos masas, satélite lunar y formulario entregado.

La guía explica y reorganiza esas ideas para estudiar; no es una transcripción literal del texto fuente.

## Autoevaluación de conceptos

Responde con tus palabras y escribe la relación física que respalda cada respuesta. Abre la explicación plegable solo después de intentarlo.

**1. Si la distancia entre dos masas se duplica, ¿por qué la fuerza queda en la cuarta parte? ¿Desde dónde se mide esa distancia?**

> [!success]- Mostrar explicación
> La ley universal dice $F_g\propto1/r^2$. Al reemplazar $r$ por $2r$, queda $F'_g/F_g=r^2/(2r)^2=1/4$. En planetas y otros cuerpos esféricamente simétricos vistos desde fuera, $r$ se mide entre los centros, no desde la superficie.

**2. ¿Por qué el campo de una fuente no depende del objeto de prueba y cómo se relaciona con su aceleración?**

> [!success]- Mostrar explicación
> Se define $\vec g=\vec F_g/m$. Al sustituir $\vec F_g=-GMm\,\hat{\mathbf r}/r^2$, la masa de prueba se cancela y queda $\vec g=-GM\,\hat{\mathbf r}/r^2$. Si no actúan otras fuerzas, $\vec a=\vec F_g/m=\vec g$. Las fuerzas sobre dos masas de prueba pueden ser distintas porque $F_g=mg$, aunque su aceleración gravitatoria sea la misma.

**3. Un objeto está a una altura igual al radio del planeta. ¿Qué distancia al centro usas y qué fracción del campo superficial tiene?**

> [!success]- Mostrar explicación
> Se usa $r=R+h=2R$. Como $g=GM/r^2$, su razón respecto del campo superficial es $g/g_0=(R/2R)^2=1/4$. La altura es la distancia sobre la superficie; la ley requiere la distancia desde el centro.

**4. ¿Qué dos ideas se combinan para obtener la rapidez orbital circular?**

> [!success]- Mostrar explicación
> La segunda ley de Newton requiere una fuerza neta radial $ma_c=mv^2/r$. En una órbita circular ideal, la gravedad es esa fuerza: $GMm/r^2=mv^2/r$. Al cancelar $m$ queda $v=\sqrt{GM/r}$. La dirección de la velocidad es tangente, mientras la aceleración apunta hacia el centro.

**5. ¿Por qué la energía potencial es negativa y en qué situación se recupera $mgh$?**

> [!success]- Mostrar explicación
> Se elige $U=0$ en el infinito. Al acercar dos masas, la gravedad realiza trabajo positivo y la energía potencial disminuye, por eso $U=-GMm/r<0$. Cerca de la superficie, si $h\ll R$, el cambio exacto $GMm(1/R-1/(R+h))$ se aproxima por $GMmh/R^2=mgh$, usando $g=GM/R^2$.

**6. ¿Cómo cambia el cálculo de energía de escape si el satélite ya está en una órbita circular?**

> [!success]- Mostrar explicación
> El umbral es la energía total final $E_f=0$. En una órbita circular el satélite ya tiene energía cinética y $E_i=-GMm/(2r)$, así que el aporte es la diferencia $\Delta E=E_f-E_i=GMm/(2r)$. No se agrega otra vez toda la energía cinética asociada a $v_{\text{esc}}$: esa rapidez es la rapidez total límite en el radio $r$. Primero identifica la energía que el satélite ya trae y luego calcula cuánto falta.

**7. ¿Cuándo se puede cancelar la constante de la tercera ley al comparar dos órbitas?**

> [!success]- Mostrar explicación
> Cuando ambos cuerpos orbitan la misma masa central y se mantiene el mismo modelo para las órbitas. En ese caso $4\pi^2/(GM)$ es común, de modo que $T_1^2/r_1^3=T_2^2/r_2^3$ (o se usan los semiejes mayores para órbitas elípticas). Si las masas centrales son distintas, el factor no es común.

**8. ¿Por qué la velocidad en una circunferencia es tangente, cómo se obtiene $v_t=2\pi r/T$ y de dónde sale $a_c=v_t^2/r$?**

> [!success]- Mostrar explicación
> En un intervalo muy corto, el desplazamiento entre dos posiciones se aproxima a la tangente; por eso la velocidad instantánea es tangente y perpendicular al radio. Una vuelta recorre $2\pi r$ durante un período $T$, así que $v_t=2\pi r/T$ (para movimiento uniforme). Entre dos instantes cercanos, las velocidades tienen módulo $v_t$ y difieren en un ángulo $\Delta\theta$: $|\Delta\vec v|\approx v_t\Delta\theta$. Para la circunferencia, el arco cumple exactamente $\Delta s=r|\Delta\theta|$; es la cuerda recta entre las posiciones la que se aproxima al arco cuando el intervalo es pequeño. Con $v_t=\lim_{\Delta t\to0}\Delta s/\Delta t$, entonces $a_c=\lim_{\Delta t\to0}|\Delta\vec v|/\Delta t=v_t^2/r$, dirigida hacia el centro.
