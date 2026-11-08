---
tags: [fisica-aplicada, teoria, lectura-activa, optica]
---

# Guía breve de Óptica: leer y aplicar

Esta guía da lo necesario para **elegir el planteo y comenzar la práctica**. Lee solo el tramo asociado al ejercicio: calcula unos **5–10 minutos de lectura y recuperación por tramo**, sin contar la práctica; los sistemas y las demostraciones pueden requerir más. Tapa el texto, explica la idea con tus palabras, responde la pregunta y pasa al problema antes de seguir leyendo.

## Elige por dónde entrar

| Si el ejercicio pregunta por… | Lee este tramo | Primera práctica |
|---|---|---|
| Rapidez, frecuencia o longitud de onda al cambiar de medio | [[#1. Índice, rapidez y longitud de onda\|Rayo 1]] | O21 (M) |
| Ángulo refractado o recorrido por capas | [[#2. Desvío y recorrido dentro de un material\|Rayo 2]] | O4; luego O5/O22 (R) |
| Reflexión total o profundidad aparente | [[#3. Reflexión total y posición aparente\|Rayo 3]] | O11/O10 (R); O6 (C) |
| Rebotes en espejos planos | [[#Bloque Reflexión — Espejo plano y tiempo de recorrido\|Reflexión]] | O7–O9 (C) |
| Imágenes en un espejo curvo | [[#Bloque Imagen — Espejos curvos\|Imagen]] | O12; luego O14 (R) |
| Una lente y el tamaño o posición de su imagen | [[#1. Una lente: posición, tamaño y orientación\|Sistema 1]] | O20 (M); luego O17 (R) |
| La focal a partir de curvaturas y materiales | [[#2. Cuando no te dan la focal\|Sistema 2]] | O16 (C); preparación de O18 |
| Dos lentes consecutivas | [[#3. Dos lentes: volver a medir desde el segundo elemento\|Sistema 3]] | O18; luego O19 (R) |
| Franjas brillantes u oscuras | [[#Bloque Onda — Franjas de doble rendija\|Onda]] | O1 (M); luego O2–O3 (R) |

Para el **primer parcial**, prioriza O21 y O20 con sus lecturas, y continúa con refracción, reflexión total, espejos y sistemas. Para el **global**, incorpora también doble rendija. M/R/C indican la relación con las fuentes; consulta las prioridades de cada enunciado. Los complementarios completan habilidades del TP.

**Si te trabas:** busca la figura o el ejemplo correspondiente en el [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Apoyos visuales y ejemplos de las fuentes|mapa visual del apunte largo]], o un despeje en [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica|fórmulas aplicadas]]. Vuelve después al mismo ejercicio.

## Bloque Rayo — Refracción y profundidad aparente

### 1. Índice, rapidez y longitud de onda

**Reconócelo:** te dan longitudes de onda o rapideces en dos medios. Una onda avanza una longitud de onda $\lambda$ por ciclo y realiza $f$ ciclos por segundo; por eso $v=\lambda f$. Aquí $v$ es rapidez, en m/s, y $f$ es frecuencia, en Hz.

El índice $n=c/v$ compara la rapidez en el vacío, $c\approx3.00\times10^8\,\mathrm{m/s}$, con la del material: **a mayor índice, menor rapidez**. No tiene unidades. En una frontera estacionaria la frecuencia se conserva: los ciclos llegan y se transmiten al mismo ritmo. Cambian $v$ y $\lambda$:

$$
f=\frac{c}{\lambda_0},\qquad v=\frac cn,\qquad
\lambda=\frac{\lambda_0}{n},\qquad n=\frac{\lambda_0}{\lambda}.
$$

$\lambda_0$ es la longitud de onda en vacío; para O21 se aproxima aire a vacío. Si ambos medios tienen índices distintos de 1, usa $n_1\lambda_1=n_2\lambda_2$. Convierte nm a m al calcular frecuencia: $1\,\mathrm{nm}=10^{-9}\,\mathrm m$. Para una razón de longitudes basta usar la misma unidad arriba y abajo.

**Pregunta:** Si la longitud de onda se reduce a la mitad al entrar en un material desde el vacío, ¿qué ocurre con $n$, $v$ y $f$?

> [!success]- Mostrar explicación
> El índice es $n=\lambda_0/(\lambda_0/2)=2$; la rapidez baja a $c/2$ y la frecuencia se mantiene. No se reduce el número de ciclos por segundo: se reduce el espacio que ocupa cada ciclo.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O21. Índice desde el cambio de longitud de onda — M · primeros parciales 2023 y 2024|O21 (M): cambio de longitud de onda]]. Antes de calcular, escribe qué magnitud se conserva. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Ejemplo del libro: el mismo láser en aire y en el ojo|ejemplo del libro]].

### 2. Desvío y recorrido dentro de un material

**Reconócelo:** el rayo cruza una frontera y te piden dirección o punto de llegada. Dibuja la **normal**, recta perpendicular a la superficie en el punto de entrada. Todos los ángulos de Snell se miden desde ella: si dan un ángulo $\phi$ con la superficie, usa $\theta=90^\circ-\phi$.

La parte del frente de onda que entra primero cambia de rapidez antes que el resto; así cambia la dirección del frente y del rayo. La ley de Snell cuantifica ese giro:

$$
n_1\sin\theta_1=n_2\sin\theta_2
\quad\Longrightarrow\quad
\theta_2=\arcsin\!\left(\frac{n_1}{n_2}\sin\theta_1\right).
$$

$1$ es el medio de partida y $2$ el de llegada. Entra a mayor índice: se acerca a la normal. Entra a menor índice: se aleja, si existe rayo transmitido. **Con incidencia normal sigue recto**, aunque cambie la rapidez. Usa grados si los datos están en grados; si el argumento del arcoseno supera 1, revisa reflexión total.

Para convertir el ángulo en una distancia, dibuja un triángulo. Si $e$ es el espesor perpendicular a una capa y $x$ el avance paralelo a sus caras, $\tan\theta=x/e$, de donde $x=e\tan\theta$. En O22 suma los avances de ambas capas; en O5 resta los de ambos colores. **La longitud inclinada del rayo no es el espesor.** En cada cara usa la normal local; las caras paralelas comparten dirección normal.

**Pregunta:** Al pasar del agua al aire, ¿se acerca o se aleja de la normal? ¿Siempre hay un rayo que sale?

> [!success]- Mostrar explicación
> Como baja el índice, Snell exige un ángulo mayor: se aleja, salvo incidencia normal, que permanece normal. Solo existe transmisión propagante si el seno calculado no supera 1; por encima del ángulo crítico hay reflexión total interna.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O4. Del aceite al agua — R · TP 3, problema 1; prioridad didáctica alta|O4: una frontera]], después [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O5. Dos colores atraviesan un bloque de hielo — R · TP 3, problema 2; prioridad didáctica alta|O5: dos colores]] y [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O22. Refracción sucesiva en dos capas — R · primer parcial 2025 con geometría explícita|O22: dos capas]]. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Ejemplo del libro: agua a vidrio, con reflexión y refracción|normal y Snell en una figura del libro]].

### 3. Reflexión total y posición aparente

Son **dos aplicaciones distintas de la refracción**. Elige según lo que pide el enunciado:

- **¿Puede salir el rayo?** Solo puede haber reflexión total interna si va de mayor a menor índice: $n_1>n_2$. En el límite, el rayo transmitido es rasante, $\theta_2=90^\circ$. Sustituyendo en Snell queda $\sin\theta_c=n_2/n_1$. Hay reflexión total para $\theta_i>\theta_c$; la igualdad es el umbral. En O11, el ángulo con el plano de corte es complementario del ángulo de incidencia. En O10, cambia la normal al pasar de la cara lateral a la superior.
- **¿Dónde parece estar un objeto sumergido?** El ojo prolonga en línea recta los rayos que le llegan refractados. Para una superficie plana y mirada casi perpendicular, la geometría con ángulos pequeños da $d_{\mathrm{ap}}\approx d_{\mathrm{real}}\,n_{\mathrm{obs}}/n_{\mathrm{obj}}$. Los subíndices indican los medios del observador y del objeto. Es una posición aparente; el objeto no se desplaza. Si preguntan cuánto más cerca parece estar, resta $d_{\mathrm{real}}-d_{\mathrm{ap}}$.

**Pregunta:** En una salida de vidrio a aire con $\theta_c=42^\circ$, ¿qué ocurre para incidencias de $30^\circ$, $42^\circ$ y $50^\circ$, medidas desde la normal?

> [!success]- Mostrar explicación
> A $30^\circ$ hay transmisión y también puede haber reflexión parcial; a $42^\circ$ se alcanza el límite rasante; a $50^\circ$ hay reflexión total. Comparar el ángulo con la superficie con $42^\circ$ daría una conclusión incorrecta.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O11. Corte oblicuo de una guía de plástico — R · TP 3, problema 8; prioridad didáctica alta|O11: corte de la guía]], luego [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O10. Entrada lateral y reflexión en la cara superior — R · TP 3, problema 7; prioridad didáctica alta|O10: dos caras perpendiculares]]. Para profundidad aparente, [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O6. Madera sumergida vista desde arriba — C · TP 3, problema 3; prioridad didáctica alta|O6 (C)]]. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#5. Reflexión total interna: cuándo la luz queda atrapada|figura y condiciones de reflexión total]].

## Bloque Reflexión — Espejo plano y tiempo de recorrido

**Reconócelo:** hay un rebote en un espejo plano. La ley $\theta_r=\theta_i$ usa ángulos desde la normal. Para situar una imagen, prolonga hacia atrás los rayos reflejados: parecen salir de un punto **a igual distancia detrás del espejo** que el objeto delante. Esa imagen es virtual: los rayos reales no se reúnen allí. Es derecha y del mismo tamaño.

En un eje perpendicular al espejo, si $x_o$ es la coordenada del objeto y $x_m$ la del espejo, la simetría exige $x_i-x_m=x_m-x_o$, de donde $x_i=2x_m-x_o$.

Si piden justificar el recorrido por el tiempo, como en O8, calcula las dos hipotenusas y divide por la rapidez:

$$
t(x)=\frac{\sqrt{y_1^2+x^2}+\sqrt{y_2^2+(l-x)^2}}{c}.
$$

Aquí $y_1,y_2$ son alturas, $l$ la separación horizontal y $x$ la posición de rebote medida desde la vertical del primer punto. En este caso de medio uniforme y espejo plano, Fermat da el trayecto de tiempo mínimo. Derivar y plantear $dt/dx=0$ conduce a la igualdad de los ángulos; el [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#4. Reflexión y espejos planos|desarrollo algebraico]] está en el formulario.

**Pregunta:** Si el espejo se aleja perpendicularmente de un objeto fijo una distancia $a$, ¿cuánto y hacia dónde se desplaza la imagen?

> [!success]- Mostrar explicación
> Se desplaza $2a$ en el mismo sentido que el espejo: aumenta $a$ la distancia objeto-espejo y otros $a$ la posición de la imagen más allá del espejo. En coordenadas, $\Delta x_i=2\Delta x_m$ porque el objeto está fijo. Si también se mueve el objeto, hay que incluir $-\Delta x_o$.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O7. Dos espejos en ángulo recto — C · TP 3, problema 4; prioridad didáctica alta|O7: geometría del rebote]], [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O9. Un espejo que se desplaza — C · TP 3, problema 6; prioridad didáctica media|O9: espejo móvil]] y [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O8. Tiempo de un rayo que se refleja — C · TP 3, problema 5; prioridad didáctica alta|O8: demostración por tiempo]]. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Leer el esquema de clase: la luz que llega al ojo|rayos y prolongaciones en la diapositiva]].

## Bloque Imagen — Espejos curvos

**Reconócelo:** te dan un espejo cóncavo o convexo y piden posición o tamaño de imagen. El **eje principal** pasa por el vértice y el centro de la esfera. El **foco** es el punto donde se reúnen, o parecen originarse, los rayos que llegan paralelos al eje. Para rayos cercanos al eje y de pequeña inclinación —aproximación paraxial— la geometría da $f=R/2$: $f$ es la distancia focal y $R$ el radio de curvatura, ambos con signo.

Usaremos $s$ para distancia de objeto, $s'$ para distancia de imagen, $y,y'$ para alturas y $m=y'/y$ para aumento. Para objeto real, $s>0$; cóncavo: $f>0$; convexo: $f<0$. La ecuación de imagen y la proporción entre los triángulos del dibujo dan:

$$
\frac1s+\frac1{s'}=\frac1f,
\qquad s'=\frac{fs}{s-f},
\qquad m=-\frac{s'}s,
\qquad y'=my.
$$

**Procedimiento:** asigna el signo de $f$, halla $s'$, calcula $m$ y describe la imagen. $s'>0$: real delante del espejo; $s'<0$: virtual detrás. $m<0$: invertida; $m>0$: derecha. $|m|$ compara tamaños: mayor que 1 amplía y menor que 1 reduce. Conserva una sola unidad en todas las distancias.

Para un dibujo, traza desde la punta del objeto un rayo paralelo al eje y otro hacia el vértice: el primero se refleja pasando por el foco, o como si viniera de él; el segundo se refleja con igual ángulo respecto del eje, que allí es la normal. Cruza los rayos reales o sus prolongaciones. Si $s=f$, salen paralelos y no hay imagen a distancia finita.

**Pregunta:** Una imagen real de un cóncavo, ¿queda delante o detrás? Si mide la mitad que el objeto real, ¿qué aumento debes usar?

> [!success]- Mostrar explicación
> Queda delante, por lo que $s'>0$. Como $s>0$, resulta $m=-s'/s<0$: es invertida. “Mitad de tamaño” indica $|m|=0.50$; con la orientación queda $m=-0.50$. Para hallar distancias desde un aumento, sustituye primero $s'=-ms$ en la ecuación de imagen.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O12. Un espejo cóncavo en cuatro posiciones — R · TP 3, problema 9; prioridad didáctica alta|O12, casos (a) y (d)]] para contrastar real/virtual; luego [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O14. Imagen en un espejo convexo — R · TP 3, problema 11; prioridad didáctica alta|O14: convexo]], [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O15. Distancia para una imagen real de mitad de tamaño — R · TP 3, problema 12; prioridad didáctica alta|O15: aumento dado]] y [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O13. Dos objetos a ambos lados del foco — R · TP 3, problema 10; prioridad didáctica alta|O13: dos imágenes]]. Completa los otros casos de O12 después. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Ejemplo del libro: proyectar una imagen sobre una pared|ejemplo con signos y cálculo]].

## Bloque Sistema — Lentes delgadas

### 1. Una lente: posición, tamaño y orientación

**Reconócelo:** la luz atraviesa una lente. Sus dos refracciones se resumen en la misma ecuación de imagen del bloque anterior si es **delgada**, los rayos son paraxiales y el medio exterior es el mismo a ambos lados. Aquí $f$ significa **distancia focal**, no frecuencia.

Para luz de izquierda a derecha: objeto real a la izquierda, $s>0$; imagen real a la derecha, $s'>0$; imagen virtual a la izquierda, $s'<0$. Lente convergente: $f>0$; divergente: $f<0$. Una imagen real se obtiene al cruzarse los rayos salientes y puede recibirse en una pantalla; para una virtual solo se cruzan sus prolongaciones.

Usa $s'=fs/(s-f)$, $m=-s'/s$ y $y'=my$. **Los lados de la imagen son distintos de los del espejo:** sigue la luz. Para dibujar una lente en aire, traza un rayo por su centro, que sigue aproximadamente recto, y otro paralelo al eje. En una convergente, este último sale hacia el foco de salida; en una divergente sale como si viniera del foco del lado de entrada.

**Pregunta:** Si una lente divergente forma de un objeto real una imagen derecha de $2/3$ de su altura, ¿qué signos tienen $f$, $m$ y $s'$?

> [!success]- Mostrar explicación
> $f<0$, $m=+2/3$ y $s'=-ms<0$. La imagen es virtual y reducida. Sustituye $s'=-ms$ en $1/s+1/s'=1/f$ y despeja $s$; asigna los signos antes de introducir números. El signo positivo de $m$ indica orientación; no convierte la imagen en real.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O20. Lente divergente con imagen de dos tercios — M · primeros parciales 2023 y 2024|O20 (M): divergente y aumento dado]], después [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O17. Objeto e imagen real de una lente convergente — R · TP 3, problema 14; prioridad didáctica alta|O17: convergente]]. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Leer la diapositiva: lente divergente e imagen virtual|imagen virtual en una divergente]] y [[imagenes/optica-imagen-real-virtual.svg|esquema comparativo de imagen real y virtual]].

### 2. Cuando no te dan la focal

**Reconócelo:** dan índices y radios de las caras, o cambian el medio que rodea la lente. La capacidad de desviar depende de las curvaturas **y del contraste entre materiales**. Para lente delgada, rayos paraxiales y mismo medio a ambos lados, el fabricante de lentes resume las dos refracciones:

$$
\frac1f=\left(\frac{n_\ell}{n_m}-1\right)
\left(\frac1{R_1}-\frac1{R_2}\right).
$$

$n_\ell$ es el índice de la lente y $n_m$ el del entorno. Numera las caras por orden de llegada de la luz. Con luz hacia la derecha, un radio es positivo si su centro de curvatura está a la derecha de la cara y negativo si está a la izquierda. Biconvexa simétrica: $R_1=+R$, $R_2=-R$; cara plana: $1/R=0$. **No uses $f=R/2$ para lentes.**

**Pregunta:** ¿Una lente biconvexa sigue siendo convergente al sumergirla en cualquier material?

> [!success]- Mostrar explicación
> No. Para esa forma, el factor de curvatura es positivo. Si $n_m>n_\ell$, el factor $n_\ell/n_m-1$ cambia de signo y $f<0$: se vuelve divergente. Si ambos índices son iguales, no hay contraste y no enfoca. La forma por sí sola no decide el comportamiento.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O16. La misma lente en aire y en un medio de mayor índice — C · TP 3, problema 13; prioridad didáctica alta|O16 (C): cambio de medio]]. Este tramo también prepara el cálculo de focales de O18. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#8. Lentes delgadas: dos refracciones y una sola imagen|origen de la relación y figura de los radios]].

### 3. Dos lentes: volver a medir desde el segundo elemento

**Reconócelo:** la luz atraviesa dos lentes separadas. Resuelve **una lente por vez**: la imagen que produciría L1 sola define el objeto de L2. Si L2 intercepta los rayos antes de que lleguen a ese punto, recibe rayos convergentes y tiene un objeto virtual.

Con L1 en $x=0$, L2 en $x=D$ y luz hacia la derecha:

$$
s_2=D-s'_1,\qquad
s'_2=\frac{f_2s_2}{s_2-f_2},\qquad
x_{\mathrm{final}}=D+s'_2,\qquad m_{\mathrm{total}}=m_1m_2.
$$

$D$ es la separación entre lentes; $s'_1$ se mide desde L1 y $s'_2$ desde L2. La primera resta convierte la posición intermedia en distancia de objeto para L2; la suma final vuelve al eje común. El aumento total es un producto porque cada lente multiplica la altura recibida. Si dan la posición final, empieza por $s'_2=x_{\mathrm{final}}-D$ y resuelve hacia atrás. No sumes las focales.

**Pregunta:** Si la imagen de L1 sola quedaría a la derecha de L2, ¿qué signo tiene $s_2$ y qué significa?

> [!success]- Mostrar explicación
> Como $s'_1>D$, resulta $s_2=D-s'_1<0$: es un objeto virtual para L2. Los rayos llegan convergiendo hacia un punto situado después de L2. Esa condición no determina por sí sola si la imagen final será real o virtual: debes calcular $s'_2$.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O18. Dos lentes con una imagen intermedia — R · TP 3, problema 15; prioridad didáctica alta|O18: resolver hacia adelante]], luego [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O19. Diseñar la posición del objeto para ubicar la imagen final — R · TP 3, problema 16; prioridad didáctica alta|O19: resolver hacia atrás]]. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#8. Lentes delgadas: dos refracciones y una sola imagen|esquema y explicación del objeto virtual]].

## Bloque Onda — Franjas de doble rendija

**Reconócelo:** hay dos rendijas y franjas en una pantalla. Para cada color, las rendijas actúan como fuentes coherentes: mantienen una diferencia de fase estable. Si parten en fase, las crestas se refuerzan cuando la diferencia de caminos es un número entero de longitudes de onda: $\Delta r=m\lambda$. Un desfase de media longitud de onda entre crestas produce un mínimo; la cancelación completa requiere amplitudes iguales.

Con pantalla lejana y cerca del centro, la geometría da $\Delta r\approx dy/L$. Combinándola con la condición de máximo:

$$
y_m\approx\frac{m\lambda L}{d},\qquad
\beta\approx\frac{\lambda L}{d},\qquad
 y_{\mathrm{primer\ mínimo}}\approx\pm\frac{\beta}{2}.
$$

$d$ es la separación de rendijas; $L$, la distancia a pantalla; $y_m$, la posición desde el centro. **Aquí $m$ es orden entero, no aumento:** centro $m=0$, tercer orden $m=3$. $\beta$ es la separación entre máximos vecinos del mismo color. Se requiere $L\gg d$ y $|y|\ll L$; usa la longitud de onda en el medio de propagación y convierte nm y mm a una unidad común.

Para O1, calcula $y_3$ de cada color y resta posiciones. Para O3, la coincidencia exige $m_1\lambda_1=m_2\lambda_2$: busca los menores enteros positivos. Cada color produce su propio patrón; la coincidencia de franjas no significa coherencia entre dos colores distintos.

**Pregunta:** Si aumenta $d$, ¿las franjas se separan o se acercan? ¿La distancia del centro al tercer máximo es igual al espaciado vecino?

> [!success]- Mostrar explicación
> Se acercan: $\beta=\lambda L/d$ disminuye. El tercer máximo está a $3\beta$ del centro; el espaciado vecino es solo $\beta$. Confundir posición y separación introduce un factor de orden incorrecto.

**Pasa a práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O1. Máximos de dos colores — M · evidencia media; prioridad didáctica alta|O1 (M): dos colores]], [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O2. Espaciado de franjas con una fuente monocromática — R · evidencia media; prioridad didáctica alta|O2: máximos y primer mínimo]] y [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O3. Coincidencia de máximos de dos colores — R · evidencia media; prioridad didáctica alta|O3: coincidencia]]. **Apoyo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Leer el montaje del libro: una fuente común y dos caminos|montaje de Young]] y [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Ejemplo del libro: obtener la longitud de onda a partir de una franja|ejemplo de orden, posición y espaciado]].

## Antes de pasar al siguiente tramo

Comprueba que puedes explicar **qué fenómeno reconociste, qué condición permite usar la fórmula y qué significa el resultado**. En la práctica escribe: esquema y datos → principio elegido y justificación → despeje → valores con unidades → interpretación y control. Abre la pista solo si no encuentras el primer paso; compara con la [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica|resolución completa]] después del intento. Si te equivocaste, anota la causa y repite el planteo sin mirar.

## Ruta de profundización

- Origen, supuestos y figuras: [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica]].
- Despejes y controles durante la práctica: [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica]].
- Para comprobar la comprensión al cerrar una familia: [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica|autoevaluación centralizada con respuestas plegables]].
