---
tags: [fisica-aplicada, unidad-06, optica, espejos, resumen-practico]
aliases: [Cómo resolver ejercicios de espejos]
---

# Espejos: cómo resolver los ejercicios

**Objetivo:** pasar del enunciado al planteo, calcular la imagen y explicar el resultado. El núcleo son los espejos cóncavos y convexos de **O12–O15**; al final está el método para los planos de **O7–O9**.

**Volver:** [[Unidades/06 - Óptica/Teoría/06 - Óptica|Óptica]] · **Otro resumen:** [[Unidades/06 - Óptica/Teoría/06 - Resumen práctico de Snell y ángulo crítico|Snell y ángulo crítico]].

## 1. Reconocer el problema y fijar los signos

Si preguntan **dónde se forma una imagen, cuánto mide o cómo es**, necesitas la ecuación del espejo y el aumento. Si preguntan **por dónde rebota un rayo en una superficie plana**, empieza por la ley de reflexión y la geometría.

En los ejercicios esféricos de esta guía el objeto es **real y está delante del espejo**. “Delante” es el lado desde el que llega la luz; “detrás” es el otro lado, aunque el dibujo cambie de orientación.

| Magnitud | Qué representa | Signo en la convención de la materia |
|---|---|---|
| $s$ | Distancia del objeto al vértice | $s>0$ para el objeto real de estos ejercicios |
| $s'$ | Distancia de la imagen al vértice | $s'>0$: real, delante; $s'<0$: virtual, detrás |
| $f$ | Distancia focal | Cóncavo: positiva; convexo: negativa |
| $R$ | Radio de curvatura con signo | Cóncavo: positivo; convexo: negativo |
| $y$, $y'$ | Alturas respecto del eje principal | Toma $y>0$; $y'<0$ indica imagen invertida |
| $m$ | Aumento, $y'/y$ | Positivo: derecha; negativo: invertida; sin unidades |

> [!important] El radio del enunciado suele ser una magnitud
> “Convexo de radio $40\,\mathrm{cm}$” exige escribir **$R=-40\,\mathrm{cm}$**, por lo que $f=-20\,\mathrm{cm}$. Asigna el signo antes de calcular.

## 2. Método para cualquier espejo esférico

Trabaja con el modelo de **rayos paraxiales**, cercanos al eje principal. Usa una misma unidad en todas las distancias: puedes resolver todo en cm.

1. **Dibuja** el espejo, el eje y el objeto. Marca el vértice $V$, el foco $F$ y el centro de curvatura $C$; $F$ queda a mitad de camino entre $V$ y $C$.
2. **Anota los datos con signo:** $s$, $R$ o $f$, y $y$ si piden altura. Calcula $f=R/2$ cuando dan el radio.
3. **Calcula la posición** de la imagen:

$$
\frac1s+\frac1{s'}=\frac1f
\quad\Longrightarrow\quad
\frac1{s'}=\frac{s-f}{fs}
\quad\Longrightarrow\quad
\boxed{s'=\frac{fs}{s-f}}.
$$

4. **Calcula aumento y altura**, conservando el signo de $s'$:

$$
\boxed{m=-\frac{s'}s},\qquad \boxed{y'=my}.
$$

5. **Traduce los números:** $s'$ indica el lado y si es real o virtual; $m$ indica orientación y tamaño.

| Resultado | Interpretación |
|---|---|
| $s'>0$ / $s'<0$ | Real delante / virtual detrás |
| $m>0$ / $m<0$ | Derecha / invertida respecto del objeto |
| $\lvert m\rvert>1$ / $=1$ / $<1$ | Mayor / igual / menor que el objeto |

Una imagen real reúne los rayos reflejados y puede recibirse en una pantalla situada allí. En una virtual, se cruzan las **prolongaciones** de los rayos detrás del espejo.

> [!tip] Plantilla de respuesta
> “$s'=\ldots\,\mathrm{cm}$: la imagen queda a … cm delante/detrás del espejo y es real/virtual. Como $m=\ldots$, es derecha/invertida y … veces la altura del objeto; $y'=\ldots\,\mathrm{cm}$”. Si la altura es negativa, describe su tamaño con $|y'|$ y explica que está invertida.

## 3. Predecir el resultado antes de hacer cuentas

Para un **cóncavo**, $f>0$ y $C$ está a $2f$. Compara la distancia $s$ con esas dos referencias:

| Posición del objeto real | Posición de la imagen | Características |
|---|---|---|
| $s>2f$ | $f<s'<2f$ | Real, invertida, menor |
| $s=2f$ | $s'=2f$ | Real, invertida, igual |
| $f<s<2f$ | $s'>2f$ | Real, invertida, mayor |
| $s=f$ | Sin posición finita; rayos reflejados paralelos | Imagen en el infinito en el modelo |
| $0<s<f$ | $s'<0$, detrás | Virtual, derecha, mayor |

Para un **convexo con objeto real**, el resultado siempre debe ser **virtual, derecho y menor**: $s'<0$, $0<m<1$. La imagen queda entre el vértice y el foco virtual, detrás del espejo.

**Por qué cambia el cóncavo al pasar por el foco:** en $s'=fs/(s-f)$ el numerador es positivo. Si $s>f$, el denominador es positivo; si $s<f$, es negativo. El cambio de lado de la imagen sale de la misma ecuación.

## 4. Dos ejemplos que fijan el procedimiento

### Cóncavo con objeto dentro del foco — O12 d

Datos: $R=+100\,\mathrm{cm}$, $s=30.0\,\mathrm{cm}$, $y=40.0\,\mathrm{cm}$. Primero $f=+50.0\,\mathrm{cm}$. Como $s<f$, ya esperamos una imagen virtual, derecha y mayor.

$$
s'=\frac{(50.0)(30.0)}{30.0-50.0}\,\mathrm{cm}
=-75.0\,\mathrm{cm}.
$$

$$
m=-\frac{-75.0}{30.0}=+2.50,\qquad
y'=(2.50)(40.0\,\mathrm{cm})=+100\,\mathrm{cm}.
$$

**Respuesta:** imagen a $75.0\,\mathrm{cm}$ detrás del espejo, virtual, derecha y de altura $100\,\mathrm{cm}$; mide 2.50 veces el objeto. El signo y el tamaño coinciden con la predicción.

### Convexo — O14

Datos: radio de magnitud $40.0\,\mathrm{cm}$, $s=30.0\,\mathrm{cm}$, $y=6.00\,\mathrm{cm}$. Por ser convexo, $f=-20.0\,\mathrm{cm}$.

$$
s'=\frac{(-20.0)(30.0)}{30.0-(-20.0)}\,\mathrm{cm}
=-12.0\,\mathrm{cm},
\qquad m=-\frac{-12.0}{30.0}=+0.400.
$$

$$y'=(0.400)(6.00\,\mathrm{cm})=+2.40\,\mathrm{cm}.$$

**Respuesta:** a $12.0\,\mathrm{cm}$ detrás, virtual, derecha y reducida. Está entre el vértice y el foco, situado a $20.0\,\mathrm{cm}$ detrás: control correcto.

## 5. Si dan el tamaño de la imagen y piden ubicar el objeto

La pista del enunciado es “imagen de la mitad”, “dos veces más alta” o un aumento dado. **Convierte primero esa frase en $m$ con signo.** Para estos objetos reales:

- Imagen real de mitad de altura: $m=-0.50$.
- Imagen derecha dos veces más alta: $m=+2$; en un cóncavo será virtual.
- Si solo dicen “doble de tamaño” sin orientación ni real/virtual, el dato fija $|m|=2$: hay que distinguir las dos posibilidades.

Usa el aumento para expresar una distancia en función de la otra:

$$
m=-\frac{s'}s\quad\Longrightarrow\quad s'=-ms.
$$

Luego sustituye en la ecuación del espejo. Por ejemplo, en **O15**, $R=260\,\mathrm{cm}$, $f=130\,\mathrm{cm}$ e imagen real de mitad de altura:

$$
m=-0.50\quad\Longrightarrow\quad s'=0.50s.
$$

$$
\frac1s+\frac1{0.50s}=\frac1{130\,\mathrm{cm}}
\quad\Longrightarrow\quad
\frac3s=\frac1{130\,\mathrm{cm}}.
$$

Así, **$s=390\,\mathrm{cm}$ y $s'=195\,\mathrm{cm}$**. El objeto queda más allá de $C=260\,\mathrm{cm}$; la imagen, entre $F$ y $C$, como corresponde a una imagen reducida.

Si quieres el despeje general para $m\ne0$:

$$\boxed{s=f\left(1-\frac1m\right)},\qquad s'=-ms.$$

## 6. Si hay dos objetos o piden una separación — O13

**Resuelve cada objeto por separado con el mismo espejo.** Estar a $10\,\mathrm{cm}$ del foco no equivale a estar a $10\,\mathrm{cm}$ del espejo.

En O13, $f=20\,\mathrm{cm}$. Un objeto está $10\,\mathrm{cm}$ más allá del foco y otro $10\,\mathrm{cm}$ entre el foco y el espejo:

$$s_A=20+10=30\,\mathrm{cm},\qquad s_B=20-10=10\,\mathrm{cm}.$$

$$
s'_A=\frac{20\cdot30}{30-20}=+60\,\mathrm{cm},\qquad
s'_B=\frac{20\cdot10}{10-20}=-20\,\mathrm{cm}.
$$

Para medir la separación, toma el vértice como origen y el sentido positivo hacia delante del espejo. Las coordenadas de las imágenes coinciden entonces con sus $s'$:

$$\boxed{D=|s'_A-s'_B|=|60-(-20)|\,\mathrm{cm}=80\,\mathrm{cm}}.$$

Quedan a lados opuestos, por eso se suman sus distancias físicas al espejo. Si quedan del mismo lado, se restan. **Conservar los signos hasta el final resuelve ambos casos.**

Si piden la separación entre un objeto y su propia imagen, en ese mismo eje usa $D=|s-s'|$.

## 7. Cómo hacer el dibujo de rayos

![[imagenes/optica-espejo-concavo.svg|650]]

*Ejemplo del vault: objeto más allá de $C$ en un cóncavo; los rayos reflejados se cruzan entre $F$ y $C$. La flecha de imagen queda invertida.*

Desde la **punta del objeto**, traza dos rayos:

1. Uno paralelo al eje. En el cóncavo se refleja pasando por $F$; en el convexo se refleja de modo que su prolongación detrás del espejo pase por $F$.
2. Otro hacia el vértice. Allí el eje es la normal: refleja el rayo formando el mismo ángulo con el eje, al otro lado de este.

Donde se cruzan los rayos reflejados está la punta de una imagen real. Si divergen, prolonga ambos hacia atrás con líneas discontinuas: su cruce da una imagen virtual. Marca el sentido de propagación y compara el dibujo con el signo de $s'$ y de $y'$.

## 8. Espejos planos: los tres planteos del TP

### Dirección del rayo — O7

La ley es **$\theta_r=\theta_i$**, ambos desde la normal. Dibuja el triángulo del tramo reflejado y determina su ángulo con esa normal.

En O7, la normal al espejo horizontal es vertical. Los catetos son $11.5\,\mathrm{cm}$ horizontal y $14.0\,\mathrm{cm}$ vertical:

$$\tan\theta_r=\frac{11.5}{14.0}\quad\Longrightarrow\quad\theta_i=\theta_r=39.4^\circ.$$

Si te piden el ángulo desde la superficie, responde el complementario: $50.6^\circ$.

### Tiempo o punto de rebote — O8

Con alturas $y_1,y_2$, separación horizontal $l$ y rebote en $x$, cada tramo es una hipotenusa:

$$D(x)=\sqrt{y_1^2+x^2}+\sqrt{y_2^2+(l-x)^2},\qquad t(x)=\frac{D(x)}c.$$

Si piden demostrar la ley de reflexión, plantea $dt/dx=0$. Resulta $x/\sqrt{y_1^2+x^2}=(l-x)/\sqrt{y_2^2+(l-x)^2}$: esas fracciones son $\sin\theta_i$ y $\sin\theta_r$. La [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O8. Tiempo del rayo reflejado|resolución O8]] desarrolla la derivada.

### Imagen y movimiento del espejo — O9

La imagen de un objeto real está a igual distancia detrás del plano: **virtual, derecha e igual**. Usa coordenadas sobre un único eje perpendicular al espejo:

$$x_i=2x_m-x_o,\qquad \Delta x_i=2\Delta x_m-\Delta x_o.$$

$x_i,x_m,x_o$ son posiciones de imagen, espejo y objeto. Si el objeto está fijo, $\Delta x_o=0$: **la imagen se desplaza el doble que el espejo, en el mismo sentido**. Esta expresión supone traslación perpendicular sin giro.

## 9. Qué revisar antes de entregar

- ¿Usé $f=R/2$ y asigné el signo según el espejo?
- ¿Medí $s$ desde el espejo y unifiqué cm o m?
- ¿Conservé el signo de $s'$ al calcular $m=-s'/s$?
- ¿Separé las tres descripciones: real/virtual, derecha/invertida y mayor/menor?
- ¿El resultado concuerda con la posición respecto del foco y con el dibujo?
- Si $s=f$, ¿indiqué rayos paralelos, sin dividir por cero ni inventar una distancia finita?

**Para practicar:** entra a [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos|O12–O15]] y sigue **O14 → O12 → O15 → O13**. Los [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos|O7–O9]] completan los espejos planos.

**Base de este resumen:** síntesis de los planteos del TP 3 recogidos en las [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Espejos esféricos|resoluciones de esféricos]] y [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Reflexión y espejos planos|planos]]. Convención y supuestos: [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#5. Espejos esféricos|fórmulas del módulo]].
