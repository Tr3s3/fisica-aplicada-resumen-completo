---
tags: [fisica-aplicada, resoluciones, unidad-06, optica, interferencia, refraccion, espejos, lentes]
---

# Resoluciones de óptica

Esta nota reúne las resoluciones de toda la unidad, con las mismas familias e identificadores que el archivo de ejercicios. Intenta primero el enunciado y compara después el principio elegido, el despeje, las unidades y el control final.

**Ejercicios:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica|ejercicios de óptica]] · **Recorrido:** [[Unidades/06 - Óptica/Teoría/06 - Óptica|mapa de la unidad]].

**Etiquetas:** M reproduce un planteo de modelo; R practica una variante de una familia examinada; C cubre contenidos complementarios. Cada ejercicio conserva su fuente y su prioridad de examen o didáctica.

## Índice de familias

| Familia | Ejercicios | Consulta |
|---|---|---|
| [[#Interferencia de doble rendija\|Interferencia de doble rendija]] | O1–O3 | [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija\|Ejercicios de esta familia]] |
| [[#Refracción y reflexión total\|Refracción y reflexión total]] | O4–O6, O10–O11 y O21–O22 | [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total\|Ejercicios de esta familia]] |
| [[#Reflexión y espejos planos\|Reflexión y espejos planos]] | O7–O9 | [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos\|Ejercicios de esta familia]] |
| [[#Espejos esféricos\|Espejos esféricos]] | O12–O15 | [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos\|Ejercicios de esta familia]] |
| [[#Lentes delgadas y sistemas\|Lentes delgadas y sistemas]] | O16–O20 | [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Lentes delgadas y sistemas\|Ejercicios de esta familia]] |

## Interferencia de doble rendija

**Práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija|Interferencia de doble rendija]] · **Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#9. Doble rendija: de la superposición a las franjas]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#7. Doble rendija]].

### O1. Máximos de dos colores

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O1. Máximos de dos colores — M · evidencia media; prioridad didáctica alta|volver a O1]].

#### 1. Interpretar la geometría

Para un máximo de orden $m$, la diferencia de camino debe ser $m\lambda$. En una pantalla alejada, los ángulos son pequeños y la posición medida desde el máximo central satisface $y_m\approx m\lambda L/d$. Calcularemos una posición para cada color y después su diferencia.

![[imagenes/optica-doble-rendija.svg]]

#### 2. Convertir los datos

$$
L=1.50\,\mathrm m,\qquad
d=0.025\,\mathrm{mm}=2.50\times10^{-5}\,\mathrm m,
$$

$$
\lambda_1=430\,\mathrm{nm}=4.30\times10^{-7}\,\mathrm m,\qquad
\lambda_2=510\,\mathrm{nm}=5.10\times10^{-7}\,\mathrm m.
$$

El tercer orden significa $m=3$.

#### 3. Máximo para $\lambda_1$

$$
y_3^{(1)}\approx
\frac{(3)(4.30\times10^{-7}\,\mathrm m)(1.50\,\mathrm m)}
{2.50\times10^{-5}\,\mathrm m}
=7.74\times10^{-2}\,\mathrm m
=7.74\,\mathrm{cm}.
$$

#### 4. Máximo para $\lambda_2$

$$
y_3^{(2)}\approx
\frac{(3)(5.10\times10^{-7}\,\mathrm m)(1.50\,\mathrm m)}
{2.50\times10^{-5}\,\mathrm m}
=9.18\times10^{-2}\,\mathrm m
=9.18\,\mathrm{cm}.
$$

#### 5. Separar las dos posiciones

$$
\Delta y=|y_3^{(2)}-y_3^{(1)}|
=|9.18-7.74|\,\mathrm{cm}
=1.44\,\mathrm{cm}.
$$

El máximo de mayor longitud de onda queda más lejos del centro, porque $y_m$ es proporcional a $\lambda$.

#### 6. Qué significa coherencia

Dos ondas son coherentes si tienen la misma frecuencia y mantienen una diferencia de fase constante. Las dos rendijas iluminadas por una misma componente monocromática producen ondas coherentes. Las componentes de $430\,\mathrm{nm}$ y $510\,\mathrm{nm}$ tienen frecuencias distintas, por lo que no son coherentes entre sí; forman dos patrones de franjas que se superponen visualmente, pero no un término de interferencia cruzada estable.

**Control:** $L/d=6.0\times10^4$; por eso la aproximación de pantalla lejana es adecuada. El orden de magnitud de las posiciones es centímetros, consistente con las franjas descritas.

### O2. Espaciado con una fuente monocromática

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O2. Espaciado de franjas con una fuente monocromática — R · evidencia media; prioridad didáctica alta|volver a O2]].

#### 1. Pasar a SI y elegir la relación

$$
\lambda=532\,\mathrm{nm}=5.32\times10^{-7}\,\mathrm m,\quad
d=0.300\,\mathrm{mm}=3.00\times10^{-4}\,\mathrm m,\quad
L=1.80\,\mathrm m.
$$

La separación entre máximos vecinos no depende del orden:

$$
\beta=\frac{\lambda L}{d}
=\frac{(5.32\times10^{-7})(1.80)}{3.00\times10^{-4}}\,\mathrm m
=3.192\times10^{-3}\,\mathrm m
=3.192\,\mathrm{mm}.
$$

#### 2. Tercer máximo

$$
y_3=3\beta=3(3.192\,\mathrm{mm})=9.576\,\mathrm{mm}.
$$

Hay un máximo simétrico a $-9.576\,\mathrm{mm}$ al otro lado del centro.

#### 3. Primer mínimo oscuro

Para el primer mínimo, la diferencia de camino es $\lambda/2$. En el régimen de ángulos pequeños, su distancia es la mitad del espaciado entre máximos:

$$
y_{\mathrm{oscuro},1}=\frac{\beta}{2}=1.596\,\mathrm{mm}.
$$

Aparece a $+1.596\,\mathrm{mm}$ y $-1.596\,\mathrm{mm}$. La simetría de las posiciones es un control de la geometría.

### O3. Coincidencia de máximos

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O3. Coincidencia de máximos de dos colores — R · evidencia media; prioridad didáctica alta|volver a O3]].

#### 1. Calcular los espaciados

$$
d=2.50\times10^{-4}\,\mathrm m,\quad L=1.50\,\mathrm m,
$$

$$
\beta_1=\frac{(450\times10^{-9})(1.50)}{2.50\times10^{-4}}
=2.70\times10^{-3}\,\mathrm m=2.70\,\mathrm{mm},
$$

$$
\beta_2=\frac{(600\times10^{-9})(1.50)}{2.50\times10^{-4}}
=3.60\,\mathrm{mm}.
$$

#### 2. Exigir que ambos máximos ocupen la misma posición

Para que coincidan en una coordenada $y$, se debe cumplir

$$
m_1\beta_1=m_2\beta_2,
$$

o, equivalentemente, $m_1\lambda_1=m_2\lambda_2$. Con $450m_1=600m_2$, la razón es $m_1/m_2=4/3$. Los menores órdenes positivos son $m_1=4$ y $m_2=3$.

$$
y=4(2.70\,\mathrm{mm})=3(3.60\,\mathrm{mm})=10.8\,\mathrm{mm}.
$$

#### 3. Interpretar la coherencia

Cada láser ilumina las dos rendijas y hace que sus dos ondas de un mismo color tengan una relación de fase estable; así se forma cada patrón. Los colores tienen frecuencias diferentes, por lo que no mantienen una fase relativa fija entre sí. En un detector ordinario se suman sus intensidades. La coincidencia geométrica significa que sus máximos individuales ocupan la misma posición, no que ambos colores formen una sola onda coherente.

**Fuente del formato M:** modelo 2023, problema 1. O2–O3 son variantes R de la misma familia; no se atribuyen a los modelos.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija|ejercicios de esta familia]] · [[#Refracción y reflexión total|siguiente familia: refracción y reflexión total]].

---

## Refracción y reflexión total

**Práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|Refracción y reflexión total]] · **Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica]].

### O4. Del aceite al agua

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O4. Del aceite al agua — R · TP 3, problema 1; prioridad didáctica alta|volver a O4]].

#### 1. Interpretar los ángulos

El rayo va del aceite al agua. Los ángulos del enunciado se interpretan desde la normal a la interfaz. Usamos Snell porque conocemos ambos índices y el ángulo de entrada:

$$n_1\sin\theta_1=n_2\sin\theta_2.$$

#### 2. Despejar antes de sustituir

$$
\sin\theta_2=\frac{n_1}{n_2}\sin\theta_1
=\frac{1.45}{1.33}\sin50^\circ
\approx0.835.
$$

$$\theta_2=\arcsin(0.835)\approx56.63^\circ.$$

Como $n_2<n_1$, el rayo se aleja de la normal; por eso el ángulo aumenta de $50^\circ$ a $56.63^\circ$.

### O5. Dos colores en el hielo

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O5. Dos colores atraviesan un bloque de hielo — R · TP 3, problema 2; prioridad didáctica alta|volver a O5]].

#### 1. Interpretar el ángulo y obtener los índices

El ángulo de $55^\circ$ está dado respecto de la superficie, pero Snell usa la normal:

$$\theta_{\mathrm{aire}}=90^\circ-55^\circ=35^\circ.$$

Para el primer color, la rapidez en hielo es $85\%$ de la rapidez en aire:

$$v_1=0.85c=2.55\times10^8\,\mathrm{m/s},\qquad
n_1=\frac{c}{v_1}=\frac{1}{0.85}=1.1765.$$

Para el segundo:

$$v_2=2.70\times10^8\,\mathrm{m/s},\qquad
n_2=\frac{3.00\times10^8}{2.70\times10^8}=1.1111.$$

#### 2. Refractar cada componente

Tomamos $n_{\mathrm{aire}}\approx1$. Para el color 1:

$$
\sin\theta_1=\frac{1}{1.1765}\sin35^\circ,
\qquad \theta_1\approx29.18^\circ.
$$

Para el color 2:

$$
\sin\theta_2=\frac{1}{1.1111}\sin35^\circ,
\qquad \theta_2\approx31.08^\circ.
$$

La diferencia angular es

$$\Delta\theta=31.08^\circ-29.18^\circ\approx1.90^\circ.$$

El color que viaja más rápido en el hielo tiene menor índice y se desvía menos hacia la normal; queda con el ángulo mayor.

#### 3. Separación al salir del bloque

Los dos colores entran por el mismo punto. Para un espesor perpendicular $d=2.00\,\mathrm{km}=2000\,\mathrm m$, el desplazamiento horizontal de cada rayo dentro del hielo es $x=d\tan\theta$:

$$
x_1=2000\tan29.18^\circ\approx1116.8\,\mathrm m,
\qquad
x_2=2000\tan31.08^\circ\approx1205.5\,\mathrm m.
$$

$$\Delta x=|x_2-x_1|\approx88.7\,\mathrm m.$$

Las caras son paralelas, de modo que los rayos emergen paralelos entre sí; la separación de sus puntos de salida se debe a los distintos ángulos dentro del bloque. El valor grande es razonable porque el bloque tiene $2\,\mathrm{km}$ de espesor.

### O6. Profundidad aparente

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O6. Madera sumergida vista desde arriba — C · TP 3, problema 3; prioridad didáctica alta|volver a O6]].

#### 1. Elegir el modelo adecuado

La persona observa casi perpendicularmente desde aire un objeto bajo una interfaz plana de agua. Usamos la aproximación paraxial:

$$
d_{\mathrm{ap}}\approx
d_{\mathrm{real}}\frac{n_{\mathrm{observador}}}{n_{\mathrm{objeto}}}.
$$

#### 2. Sustituir y dar significado

$$
d_{\mathrm{ap}}\approx
20.0\,\mathrm m\left(\frac{1.000}{1.333}\right)
=15.0\,\mathrm m.
$$

La madera sigue a $20.0\,\mathrm m$ de profundidad real, pero su imagen aparente queda aproximadamente a $15.0\,\mathrm m$. Parece estar $20.0-15.0=5.0\,\mathrm m$ más cerca de la superficie.

### O10. Entrada lateral al cubo y reflexión total arriba

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O10. Entrada lateral y reflexión en la cara superior — R · TP 3, problema 7; prioridad didáctica alta|volver a O10]].

#### 1. Incidencia que conecta los puntos medios

Al viajar del punto medio de una cara lateral al punto medio de la cara superior, el rayo recorre dos catetos iguales. Por tanto, dentro del vidrio forma $45^\circ$ con la normal a la cara lateral.

$$
n_m\sin\theta_m=n_v\sin45^\circ.
$$

$$
\sin\theta_m=\frac{1.50}{1.30}\sin45^\circ\approx0.816,
\qquad \theta_m\approx54.7^\circ.
$$

#### 2. Hallar el límite de reflexión total

En la cara superior la luz pasa del vidrio ($n_v=1.50$) al medio exterior ($n_m=1.30$), así que sí puede existir reflexión total:

$$
\theta_c=\arcsin\left(\frac{n_m}{n_v}\right)
=\arcsin\left(\frac{1.30}{1.50}\right)
\approx60.07^\circ.
$$

Si el ángulo interno en la cara lateral es $\theta_g$, la incidencia sobre la cara superior es $90^\circ-\theta_g$. En el límite:

$$
90^\circ-\theta_g=\theta_c
\quad\Rightarrow\quad
\theta_g=29.93^\circ.
$$

Volvemos a Snell en la cara lateral:

$$
\sin\theta_{m,\max}=
\frac{1.50}{1.30}\sin29.93^\circ,
\qquad \theta_{m,\max}\approx35.1^\circ.
$$

Ese es el valor umbral. Para que haya reflexión total estricta, la incidencia externa debe ser menor que el umbral; en la igualdad, el rayo refractado en la cara superior es rasante.

#### 3. Comprobar el sentido del cambio

Al aumentar la incidencia externa, también aumenta $\theta_g$ dentro del cubo. Entonces disminuye el ángulo que el rayo forma con la normal superior. Si se supera el umbral de $35.1^\circ$, esa incidencia superior baja del crítico y aparece un rayo transmitido por arriba.

### O11. Corte oblicuo de una guía

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O11. Corte oblicuo de una guía de plástico — R · TP 3, problema 8; prioridad didáctica alta|volver a O11]].

#### 1. Conectar el ángulo del corte con la normal

El eje del tubo y el rayo son paralelos. El corte forma $\theta$ con el eje; su normal forma $90^\circ-\theta$ con el eje. Por tanto:

$$\theta_i=90^\circ-\theta.$$

Para reflexión total, $\theta_i>\theta_c$, donde $\sin\theta_c=n_{\mathrm{ext}}/n_p$. En la igualdad, el rayo refractado sale rasante: es el umbral, pero todavía no hay reflexión total estricta.

#### 2. Tubo en aire

$$
\theta_{c,a}=\arcsin\left(\frac{1.00}{1.60}\right)=38.68^\circ.
$$

$$
\theta_{\max,a}=90^\circ-\theta_{c,a}=51.32^\circ.
$$

#### 3. Tubo en agua

$$
\theta_{c,w}=\arcsin\left(\frac{1.33}{1.60}\right)=56.23^\circ,
$$

$$
\theta_{\max,w}=90^\circ-\theta_{c,w}=33.77^\circ.
$$

El agua tiene índice mayor que el aire, de modo que el ángulo crítico aumenta y el corte permitido se vuelve menos oblicuo. Como en el límite el rayo transmitido sale rasante, para reflexión total estricta se requiere $\theta<\theta_{\max}$.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|ejercicios de esta familia]] · [[#Reflexión y espejos planos|siguiente familia: reflexión y espejos planos]].

---

### O21. Índice desde el cambio de longitud de onda

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O21. Índice desde el cambio de longitud de onda — M · primeros parciales 2023 y 2024|volver a O21]].

#### 1. Principio y despeje

En una interfaz estacionaria se conserva la frecuencia. En aire aproximamos $v_a=c$; entonces $f=c/\lambda_0=v/\lambda$. Al combinar $v=c/n$:

$$
\frac{c}{\lambda_0}=\frac{c}{n\lambda}
\quad\Longrightarrow\quad n=\frac{\lambda_0}{\lambda}
=\frac{596}{334}=1.7844.
$$

El índice no tiene unidades; ambas longitudes pueden estar en nm al formar la razón.

#### 2. Frecuencia y rapidez

Para calcular frecuencia, convertimos $\lambda_0=596\times10^{-9}\,\mathrm m$:

$$
f=\frac{3.00\times10^8\,\mathrm{m/s}}{596\times10^{-9}\,\mathrm m}
=5.0336\times10^{14}\,\mathrm{Hz},
\qquad
v=\frac{c}{n}=1.6812\times10^8\,\mathrm{m/s}.
$$

**Control:** también $v=\lambda f$. Menor longitud de onda a igual frecuencia significa menor rapidez. El dibujo debe mostrar frentes más próximos dentro del aceite; no se inventa un ángulo numérico. Se calcula sin redondear el índice a 1.78 en pasos intermedios.

### O22. Refracción sucesiva en dos capas

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O22. Refracción sucesiva en dos capas — R · primer parcial 2025 con geometría explícita|volver a O22]].

#### 1. Justificar las referencias y las dos refracciones

Las normales de las caras paralelas son paralelas. Snell se aplica en cada frontera y conserva la combinación $n\sin\theta$:

$$
\sin\theta_p=\frac{\sin45^\circ}{1.62},\qquad
\sin\theta_v=\frac{1.62}{1.47}\sin\theta_p
=\frac{\sin45^\circ}{1.47}.
$$

Así, $\theta_p=25.88^\circ$ y $\theta_v=28.75^\circ$. En el plástico el rayo se acerca a la normal; al pasar al vidrio, de menor índice, se aleja.

#### 2. Construir la distancia solicitada

En cada tramo, el espesor es el cateto adyacente y el avance horizontal es el opuesto: $x=e\tan\theta$. Como D suma ambos avances:

$$
D=e_p\tan\theta_p+e_v\tan\theta_v
=(2.00\tan25.88^\circ+3.00\tan28.75^\circ)\,\mathrm{cm}
\approx2.616\,\mathrm{cm}.
$$

**Control:** cada espesor multiplica su propio ángulo. D no es la longitud del recorrido oblicuo ni el desplazamiento perpendicular de un rayo emergente. El resultado depende de la geometría añadida y no reconstruye una figura ausente de forma única.

## Reflexión y espejos planos

**Práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos|Reflexión y espejos planos]] · **Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#6. Reflexión, imágenes planas y camino de la luz]].

### O7. Dos espejos en ángulo recto

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O7. Dos espejos en ángulo recto — C · TP 3, problema 4; prioridad didáctica alta|volver a O7]].

#### 1. Dibujar la reflexión y definir el ángulo

El rayo incide en el espejo horizontal, por lo que su normal es vertical. Desde el punto de incidencia hasta el punto medio del espejo vertical hay $11.5\,\mathrm{cm}$ en horizontal y $28.0/2=14.0\,\mathrm{cm}$ en vertical.

![[imagenes/optica-espejos-a-90.svg]]

#### 2. Aplicar la geometría al rayo reflejado

El ángulo de reflexión respecto de la normal forma un triángulo con esos catetos:

$$
\tan\theta_r=\frac{11.5}{14.0}=0.8214,
\qquad
\theta_r=\arctan(0.8214)=39.4^\circ.
$$

La ley de reflexión da $\theta_i=\theta_r$. Por lo tanto, el ángulo de incidencia es

$$\boxed{\theta_i\approx39.4^\circ\text{ desde la normal}.}$$

Si se midiera desde la superficie, el ángulo sería $90^\circ-39.4^\circ=50.6^\circ$; declarar la referencia evita confundir ambas respuestas.

### O8. Tiempo del rayo reflejado

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O8. Tiempo de un rayo que se refleja — C · TP 3, problema 5; prioridad didáctica alta|volver a O8]].

#### 1. Escribir las longitudes de los dos tramos

Llamamos $x$ al desplazamiento horizontal desde la vertical del punto 1 hasta el rebote, y $l-x$ al tramo horizontal restante. Por Pitágoras:

$$
d_1(x)=\sqrt{y_1^2+x^2},\qquad
d_2(x)=\sqrt{y_2^2+(l-x)^2}.
$$

El recorrido total es $D=d_1+d_2$. Como ambos tramos están en el mismo medio y la luz viaja a rapidez $c$:

$$
t(x)=\frac{D(x)}{c}
=\frac{\sqrt{y_1^2+x^2}+\sqrt{y_2^2+(l-x)^2}}{c}.
$$

#### 2. Hallar el punto de rebote físico

El principio de Fermat exige que el tiempo sea estacionario respecto de pequeñas variaciones de la trayectoria. Como $c$ no cambia, basta minimizar $D(x)$:

$$
\frac{dD}{dx}
=\frac{x}{\sqrt{y_1^2+x^2}}
-\frac{l-x}{\sqrt{y_2^2+(l-x)^2}}=0.
$$

Así,

$$
\frac{x}{d_1}=\frac{l-x}{d_2}.
$$

#### 3. Reconocer la ley de reflexión dentro de la derivada

Los ángulos se miden desde la normal vertical. En cada triángulo, seno del ángulo es cateto horizontal sobre hipotenusa:

$$
\sin\theta_i=\frac{x}{d_1},\qquad
\sin\theta_r=\frac{l-x}{d_2}.
$$

La condición de extremo queda $\sin\theta_i=\sin\theta_r$. Como los ángulos están entre $0^\circ$ y $90^\circ$, resulta $\theta_i=\theta_r$. La ley de reflexión aparece aquí como consecuencia geométrica de la trayectoria de tiempo estacionario. En esta configuración plana el extremo corresponde al recorrido mínimo.

### O9. Desplazamiento de la imagen

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O9. Un espejo que se desplaza — C · TP 3, problema 6; prioridad didáctica media|volver a O9]].

#### 1. Usar la simetría del espejo

Tomamos un eje perpendicular al espejo y llamamos $x_m$ a la coordenada del plano, $x_o$ a la del objeto y $x_i$ a la de la imagen. La igualdad de distancias a ambos lados dice

$$x_i-x_m=x_m-x_o.$$

Despejando,

$$x_i=2x_m-x_o.$$

#### 2. Mover el plano de simetría

El objeto no se mueve, de modo que $\Delta x_o=0$. Si el espejo se mueve $\Delta x_m=x$:

$$
\Delta x_i=2\Delta x_m-\Delta x_o=2x.
$$

La imagen se desplaza $2x$ en la misma dirección que el espejo. Una de esas distancias cambia del lado del objeto y otra del lado de la imagen; por eso aparece el factor dos.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos|ejercicios de esta familia]] · [[#Espejos esféricos|siguiente familia: espejos esféricos]].

---

## Espejos esféricos

**Práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos|Espejos esféricos]] · **Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#7. Espejos esféricos: de la geometría al foco]] · **Convenciones:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#5. Espejos esféricos]].

Usamos $s>0$ para objeto real; $s'>0$ para imagen real delante del espejo y $s'<0$ para imagen virtual detrás. El foco de un espejo cóncavo es positivo y el de uno convexo negativo.

### O12. Un espejo cóncavo en cuatro posiciones

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O12. Un espejo cóncavo en cuatro posiciones — R · TP 3, problema 9; prioridad didáctica alta|volver a O12]].

#### 1. Foco y ecuaciones

$$R=1.00\,\mathrm m=100\,\mathrm{cm},\qquad
f=\frac R2=50.0\,\mathrm{cm},\qquad y=40.0\,\mathrm{cm}.$$

En cada caso:

$$\frac1{s'}=\frac1f-\frac1s,\qquad
m=-\frac{s'}s,\qquad y'=my.$$

#### 2. Caso (a): $s=140\,\mathrm{cm}$

$$
\frac1{s'}=\frac1{50}-\frac1{140}
=\frac{14-5}{700}=\frac9{700}\,\mathrm{cm^{-1}},
\qquad s'=77.8\,\mathrm{cm}.
$$

$$m=-\frac{77.8}{140}=-0.556,\qquad
y'=(-0.556)(40.0\,\mathrm{cm})=-22.2\,\mathrm{cm}.$$

Es real, invertida y menor.

#### 3. Caso (b): $s=100\,\mathrm{cm}$

$$
\frac1{s'}=\frac1{50}-\frac1{100}=\frac1{100},
\qquad s'=100\,\mathrm{cm}.
$$

$$m=-1,\qquad y'=-40.0\,\mathrm{cm}.$$

Es real, invertida e igual al objeto; el objeto está en $C=2f$.

#### 4. Caso (c): $s=80.0\,\mathrm{cm}$

$$
\frac1{s'}=\frac1{50}-\frac1{80}
=\frac{8-5}{400}=\frac3{400},
\qquad s'=133.3\,\mathrm{cm}.
$$

$$m=-\frac{133.3}{80.0}=-1.667,\qquad y'=-66.7\,\mathrm{cm}.$$

Es real, invertida y mayor.

#### 5. Caso (d): $s=30.0\,\mathrm{cm}$

$$
\frac1{s'}=\frac1{50}-\frac1{30}
=\frac{3-5}{150}=-\frac1{75},
\qquad s'=-75.0\,\mathrm{cm}.
$$

$$m=-\frac{-75.0}{30.0}=+2.50,\qquad
y'=(2.50)(40.0\,\mathrm{cm})=+100\,\mathrm{cm}.$$

La imagen queda detrás del espejo, por eso es virtual; el aumento positivo indica que es derecha y el módulo mayor que uno indica que es mayor. Esto coincide con colocar el objeto entre el espejo y el foco.

| Distancia de objeto | Distancia de imagen | Aumento | Altura | Descripción |
|---:|---:|---:|---:|---|
| $140\,\mathrm{cm}$ | $+77.8\,\mathrm{cm}$ | $-0.556$ | $-22.2\,\mathrm{cm}$ | Real, invertida, menor |
| $100\,\mathrm{cm}$ | $+100\,\mathrm{cm}$ | $-1.00$ | $-40.0\,\mathrm{cm}$ | Real, invertida, igual |
| $80.0\,\mathrm{cm}$ | $+133.3\,\mathrm{cm}$ | $-1.667$ | $-66.7\,\mathrm{cm}$ | Real, invertida, mayor |
| $30.0\,\mathrm{cm}$ | $-75.0\,\mathrm{cm}$ | $+2.50$ | $+100\,\mathrm{cm}$ | Virtual, derecha, mayor |

### O13. Dos objetos a ambos lados del foco

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O13. Dos objetos a ambos lados del foco — R · TP 3, problema 10; prioridad didáctica alta|volver a O13]].

#### 1. Foco y distancias de objeto

$$R=40.0\,\mathrm{cm},\qquad f=20.0\,\mathrm{cm}.$$

Del diagrama del TP, A se encuentra $10\,\mathrm{cm}$ más lejos del espejo que el foco: $s_A=30\,\mathrm{cm}$. B se encuentra entre el foco y el espejo: $s_B=10\,\mathrm{cm}$.

#### 2. Imagen de A

$$
\frac1{s_A'}=\frac1{20}-\frac1{30}
=\frac1{60},
\qquad s_A'=+60\,\mathrm{cm}.
$$

A forma una imagen real delante del espejo.

#### 3. Imagen de B

$$
\frac1{s_B'}=\frac1{20}-\frac1{10}
=-\frac1{20},
\qquad s_B'=-20\,\mathrm{cm}.
$$

B forma una imagen virtual detrás del espejo. Como las imágenes quedan a lados opuestos del vértice, su separación es

$$|60-(-20)|\,\mathrm{cm}=80\,\mathrm{cm}.$$

### O14. Imagen en un espejo convexo

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O14. Imagen en un espejo convexo — R · TP 3, problema 11; prioridad didáctica alta|volver a O14]].

#### 1. Asignar el signo focal

Para el espejo convexo:

$$R=-40.0\,\mathrm{cm},\qquad f=\frac R2=-20.0\,\mathrm{cm}.$$

El objeto es real y está delante del espejo: $s=+30.0\,\mathrm{cm}$.

#### 2. Resolver la posición

$$
\frac1{s'}=\frac1f-\frac1s
=-\frac1{20}-\frac1{30}
=-\frac5{60}=-\frac1{12},
\qquad s'=-12.0\,\mathrm{cm}.
$$

El signo negativo ubica la imagen detrás del espejo: es virtual.

#### 3. Tamaño y orientación

$$
m=-\frac{s'}s=-\frac{-12.0}{30.0}=+0.400,
\qquad y'=my=(0.400)(6.00\,\mathrm{cm})=+2.40\,\mathrm{cm}.
$$

Es derecha porque $m>0$ y menor porque $|m|<1$. El resultado coincide con la propiedad usual del espejo convexo: imagen virtual, derecha y reducida.

### O15. Imagen real de mitad de tamaño

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O15. Distancia para una imagen real de mitad de tamaño — R · TP 3, problema 12; prioridad didáctica alta|volver a O15]].

#### 1. Focal y aumento con signo

$$R=260\,\mathrm{cm},\qquad f=R/2=130\,\mathrm{cm}.$$

Al ser una imagen real de un espejo cóncavo, es invertida:

$$m=-0.50=-\frac{s'}s\quad\Rightarrow\quad s'=0.50s.$$

#### 2. Sustituir en la ecuación del espejo

$$
\frac1s+\frac1{0.50s}=\frac1{130\,\mathrm{cm}}.
$$

Como $1/(0.50s)=2/s$:

$$
\frac3s=\frac1{130\,\mathrm{cm}}
\quad\Rightarrow\quad
s=390\,\mathrm{cm}.
$$

$$s'=0.50s=195\,\mathrm{cm}.$$

El objeto se ubica a $390\,\mathrm{cm}$ delante del espejo y la imagen real invertida a $195\,\mathrm{cm}$. Es razonable: el objeto queda más allá de $C=260\,\mathrm{cm}$ y la imagen se forma entre $F$ y $C$.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos|ejercicios de esta familia]] · [[#Lentes delgadas y sistemas|siguiente familia: lentes delgadas y sistemas]].

---

## Lentes delgadas y sistemas

**Práctica:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Lentes delgadas y sistemas|Lentes delgadas y sistemas]] · **Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#8. Lentes delgadas: dos refracciones y una sola imagen]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#6. Lentes delgadas]].

Usamos luz de izquierda a derecha. Una distancia de objeto positiva corresponde a un objeto real a la izquierda de la lente; una distancia de imagen positiva, a una imagen real a la derecha. El aumento $m=-s'/s$ determina tamaño y orientación.

### O16. Lente en aire y en un medio de mayor índice

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O16. La misma lente en aire y en un medio de mayor índice — C · TP 3, problema 13; prioridad didáctica alta|volver a O16]].

#### 1. Establecer radios y primera focal

Para una biconvexa simétrica, los centros de curvatura quedan a lados opuestos:

$$R_1=+R,\qquad R_2=-R.$$

La ecuación del fabricante en aire ($n_m\approx1$) es

$$
\frac1f=(n_\ell-1)\left(\frac1{R_1}-\frac1{R_2}\right)
=(1.50-1)\left(\frac1R+\frac1R\right)=\frac1R.
$$

Como $f=6.00\,\mathrm{cm}$, resulta

$$\boxed{R=6.00\,\mathrm{cm}.}$$

#### 2. Cambiar el medio que rodea la lente

En el líquido de índice $n_m=1.80$:

$$
\frac1{f_m}=
\left(\frac{1.50}{1.80}-1\right)
\left(\frac1{6.00}-\frac1{-6.00}\right)\mathrm{cm^{-1}}.
$$

$$
\frac1{f_m}=
\left(-\frac16\right)\left(\frac13\right)\mathrm{cm^{-1}}
=-\frac1{18}\,\mathrm{cm^{-1}},
\qquad f_m=-18.0\,\mathrm{cm}.
$$

El signo negativo indica que se vuelve divergente. El motivo físico es que el vidrio tiene menor índice que el medio: la lente no retrasa la luz más que el entorno, y el efecto total de sus caras invierte su carácter convergente. El dato $n=1.80$ se conserva como lo presenta el TP.

### O17. Objeto e imagen real aumentada

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O17. Objeto e imagen real de una lente convergente — R · TP 3, problema 14; prioridad didáctica alta|volver a O17]].

#### 1. Convertir la frase en una relación con signo

La imagen es real, por lo tanto invertida:

$$m=-2.50=-\frac{s'}s\quad\Rightarrow\quad s'=2.50s.$$

#### 2. Sustituir en la ecuación de lente

$$
\frac1s+\frac1{2.50s}=\frac1{50.0\,\mathrm{cm}}
\quad\Rightarrow\quad
\frac{1.40}{s}=\frac1{50.0\,\mathrm{cm}}.
$$

$$s=70.0\,\mathrm{cm},\qquad s'=2.50(70.0)=175\,\mathrm{cm}.$$

El objeto está a la izquierda y la imagen real a la derecha. La distancia entre ellos suma ambas distancias a la lente:

$$D=s+s'=70.0+175=245\,\mathrm{cm}.$$

### O18. Dos lentes con imagen intermedia

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O18. Dos lentes con una imagen intermedia — R · TP 3, problema 15; prioridad didáctica alta|volver a O18]].

#### 1. Calcular las focales por curvatura

Para la lente 1, $R_1=+4.00\,\mathrm{cm}$ y $R_2=+12.0\,\mathrm{cm}$:

$$
\frac1{f_1}=(1.50-1)\left(\frac14-\frac1{12}\right)\mathrm{cm^{-1}}
=\frac12\left(\frac16\right)=\frac1{12}\,\mathrm{cm^{-1}},
$$

por lo que $f_1=+12.0\,\mathrm{cm}$.

Para la lente 2, $R_1=+4.00\,\mathrm{cm}$ y $R_2=\infty$:

$$
\frac1{f_2}=(1.50-1)\left(\frac14-0\right)\mathrm{cm^{-1}}
=\frac18\,\mathrm{cm^{-1}},
$$

así que $f_2=+8.00\,\mathrm{cm}$.

#### 2. Resolver la primera lente

Con $s_1=14.0\,\mathrm{cm}$:

$$
\frac1{s_1'}=\frac1{12}-\frac1{14}
=\frac{14-12}{168}=\frac1{84}\,\mathrm{cm^{-1}},
\qquad s_1'=84.0\,\mathrm{cm}.
$$

La lente 1 formaría su imagen $84\,\mathrm{cm}$ a su derecha. Pero la lente 2 está a solo $18\,\mathrm{cm}$: cuando los rayos llegan a L2 siguen convergiendo hacia ese punto, ubicado $84-18=66\,\mathrm{cm}$ a la derecha de L2. Para la segunda lente es un objeto virtual:

$$s_2=-66.0\,\mathrm{cm}.$$

#### 3. Resolver la segunda lente

$$
\frac1{s_2'}=\frac1{f_2}-\frac1{s_2}
=\frac18-\left(-\frac1{66}\right)
=\frac{74}{528}=\frac{37}{264}\,\mathrm{cm^{-1}}.
$$

$$s_2'=\frac{264}{37}\,\mathrm{cm}=7.14\,\mathrm{cm}.$$

Es positiva: la imagen final es real y queda $7.14\,\mathrm{cm}$ a la derecha de L2, es decir, a

$$x_{\mathrm{final}}=18.0+7.14=25.1\,\mathrm{cm}$$

de L1.

#### 4. Aumento total y altura final

$$
m_1=-\frac{84.0}{14.0}=-6.00,\qquad
m_2=-\frac{7.14}{-66.0}=+0.1081.
$$

$$
m_{\mathrm{total}}=m_1m_2=-0.649,
\qquad
y_{\mathrm{final}}=m_{\mathrm{total}}y=(-0.649)(3.00\,\mathrm{cm})=-1.95\,\mathrm{cm}.
$$

La imagen final es invertida y reducida, aunque la imagen intermedia sea real para L1 y virtual para L2. La imagen de una etapa no se clasifica de una vez para todo el sistema: su carácter depende de qué dispositivo la recibe después.

### O19. Diseñar la posición del objeto

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O19. Diseñar la posición del objeto para ubicar la imagen final — R · TP 3, problema 16; prioridad didáctica alta|volver a O19]].

#### 1. Fijar la distancia de imagen de la lente 2

La lente 2 está a $50.0\,\mathrm{cm}$ de L1 y la imagen final se ubica en $x=31.0\,\mathrm{cm}$ desde L1. Está $19.0\,\mathrm{cm}$ a la izquierda de L2, por eso es virtual para esa lente:

$$s_2'=31.0-50.0=-19.0\,\mathrm{cm}.$$

#### 2. Recuperar el objeto de L2

Con $f_2=20.0\,\mathrm{cm}$:

$$
\frac1{s_2}=\frac1{f_2}-\frac1{s_2'}
=\frac1{20.0}-\left(-\frac1{19.0}\right)
=\frac{39}{380}\,\mathrm{cm^{-1}}.
$$

$$s_2=\frac{380}{39}=9.74\,\mathrm{cm}.$$

El objeto para L2 está $9.74\,\mathrm{cm}$ a su izquierda. Esa es la posición de la imagen intermedia de L1:

$$s_1'=50.0-9.74=40.26\,\mathrm{cm}.$$

#### 3. Hallar dónde debe estar el objeto original

Para L1, $f_1=10.0\,\mathrm{cm}$:

$$
\frac1{s_1}=\frac1{10.0}-\frac1{40.26}
=0.07516\,\mathrm{cm^{-1}},
\qquad s_1=13.31\,\mathrm{cm}.
$$

El objeto original debe ubicarse $13.31\,\mathrm{cm}$ a la izquierda de L1.

#### 4. Calcular el aumento y explicar la imagen virtual

$$
m_1=-\frac{40.26}{13.31}=-3.025,\qquad
m_2=-\frac{-19.0}{9.74}=+1.950.
$$

$$m_{\mathrm{total}}=m_1m_2\approx-5.90.$$

La imagen final queda invertida y su altura tiene $5.90$ veces el módulo de la altura inicial. Es virtual para L2 porque queda en el lado desde donde llega la luz, a la izquierda de esa lente ($s_2'<0$). “Entre las lentes” describe su coordenada respecto del sistema; “virtual para L2” describe de qué lado aparece al analizar esa lente por separado.

![[imagenes/optica-sistema-dos-lentes.svg]]

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Lentes delgadas y sistemas|ejercicios de esta familia]].

---

**Cierre:** [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Repaso del módulo|autoevaluación final]] · [[Unidades/06 - Óptica/Teoría/06 - Óptica|volver al módulo]].

### O20. Lente divergente con imagen de dos tercios

**Enunciado:** [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#O20. Lente divergente con imagen de dos tercios — M · primeros parciales 2023 y 2024|volver a O20]].

#### 1. Interpretar los datos y los signos

Los rayos paralelos divergen como si provinieran de un foco virtual: $f=-15.0\,\mathrm{cm}$. El objeto es real: $s>0$. La imagen deseada es derecha y reducida: $m=+2/3$, luego $s'=-ms=-(2/3)s<0$.

#### 2. Sustituir y despejar antes de calcular

$$
\frac1s+\frac1{-(2/3)s}=\frac1f
\quad\Longrightarrow\quad
\frac1s-\frac3{2s}=\frac1f
\quad\Longrightarrow\quad
-\frac1{2s}=\frac1f.
$$

Multiplicando por $2sf$, queda $-f=2s$. Por tanto:

$$
s=-\frac f2=+7.50\,\mathrm{cm},\qquad
s'=-\frac23(7.50\,\mathrm{cm})=-5.00\,\mathrm{cm}.
$$

#### 3. Interpretar y construir el diagrama

Para luz hacia la derecha, coloca el objeto a $7.50\,\mathrm{cm}$ a la izquierda de la lente y la imagen a $5.00\,\mathrm{cm}$ a su izquierda. Desde la punta del objeto traza un rayo central recto y otro paralelo al eje que sale divergiendo como si viniera del foco izquierdo. Prolonga ambos hacia atrás: se encuentran en la punta de la imagen virtual, entre objeto y lente. El foco izquierdo está a $15\,\mathrm{cm}$ de la lente.

**Control:** $-s'/s=+2/3$. La imagen resulta virtual, derecha y reducida, como requiere la divergente con objeto real. Una distancia negativa sitúa la imagen; no es un error a corregir con valor absoluto.

