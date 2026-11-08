---
tags: [fisica-aplicada, teoria, formulas, optica]
---

# Fórmulas aplicadas de Óptica

**Contexto y origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica]] · **Volver al módulo:** [[Unidades/06 - Óptica/Teoría/06 - Óptica]]

Antes de elegir una fórmula, identifica qué buscas: dirección de un rayo, posición y tamaño de una imagen o ubicación de una franja. Dibuja la referencia de los ángulos o de las distancias. Los signos se asignan antes de sustituir, no para acomodar el resultado.

## 1. Rapidez e índice

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#2. Índice de refracción: por qué se desvía un rayo|rapidez, ciclos y longitud de onda]].

$$
v=\lambda f,\qquad n=\frac{c}{v},\qquad v=\frac{c}{n},\qquad
\lambda_{\mathrm{medio}}=\frac{\lambda_0}{n}.
$$

- $n$: índice sin unidades; $c\approx3.00\times10^8\,\mathrm{m/s}$; $v$: rapidez en el medio.
- Aquí $f$ es **frecuencia**, en $\mathrm{Hz}=\mathrm{s^{-1}}$; $\lambda$ y $\lambda_0$ son longitudes de onda en el medio y en el vacío.
- En una interfaz estacionaria se conserva $f$: $\lambda_2/\lambda_1=n_1/n_2$. Los índices corresponden al color considerado.
- Si la rapidez es un $p\%$ menor que $c$, usa $v=(1-p/100)c$ y luego $n=c/v$. No restes ese porcentaje al índice.
- **Control:** mayor índice implica menor rapidez y menor longitud de onda para una misma frecuencia.

**Autoevaluación:** pregunta 3 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]] y 21 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## 2. Refracción: ley de Snell

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#3. De Huygens a la ley de Snell|construcción con frentes de onda]]. **Cuándo usarla:** un rayo cruza una interfaz lisa entre medios transparentes e isótropos; se conocen índices y algún ángulo.

$$
n_1\sin\theta_1=n_2\sin\theta_2,
\qquad
\theta_2=\arcsin\!\left(\frac{n_1}{n_2}\sin\theta_1\right).
$$

Todos los ángulos se miden desde la **normal local**. Si el dato es $\phi$ desde la superficie, $\theta=90^\circ-\phi$. La ley no requiere ángulos pequeños. Calculadora en el modo angular que corresponda.

- Mayor índice de llegada: menor ángulo desde la normal, salvo incidencia normal que sigue normal.
- Menor índice de llegada: mayor ángulo si existe transmisión. Si el argumento del arcoseno supera 1, comprueba reflexión total.
- Para hallar un índice: $n_2=n_1\sin\theta_1/\sin\theta_2$, si $\sin\theta_2\ne0$. Una incidencia exactamente normal no permite determinar el índice a partir de los ángulos nulos.

### Placa de caras paralelas

**Desarrollo:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#4. Bloques, profundidad aparente y color|geometría del espesor y de las salidas]]. Sea $e$ el espesor perpendicular a las caras:

$$
x=e\tan\theta_t,\qquad
\Delta x=e\left|\tan\theta_a-\tan\theta_b\right|.
$$

$\Delta x$ compara los puntos de salida de dos rayos que entran por el mismo punto. En O5 el espesor se llama $d$. Si el medio exterior es igual a ambos lados, cada rayo emerge paralelo a su incidente. La separación sobre la cara es distinta del desplazamiento perpendicular de un solo rayo respecto de la prolongación incidente:

$$
|a|=e\frac{|\sin(\theta_i-\theta_t)|}{\cos\theta_t}.
$$

No necesitas $a$ para O5. Decide primero qué distancia se pide.

**Autoevaluación:** pregunta 10 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y 22 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## 3. Profundidad aparente y reflexión total

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#4. Bloques, profundidad aparente y color|triángulos de la profundidad aparente]] y [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#5. Reflexión total interna: cuándo la luz queda atrapada|límite de Snell]].

Para una superficie plana y observación casi normal:

$$
d_{\mathrm{ap}}\approx d_{\mathrm{real}}\frac{n_{\mathrm{obs}}}{n_{\mathrm{obj}}}.
$$

$\mathrm{obs}$ identifica el medio del observador y $\mathrm{obj}$ el del objeto. Se basa en $\sin\theta\approx\tan\theta$; no es exacta para observación oblicua. Si te piden cuánto más cerca parece estar, calcula $d_{\mathrm{real}}-d_{\mathrm{ap}}$.

Para reflexión total, primero exige $n_1>n_2$:

$$
\theta_c=\arcsin\!\left(\frac{n_2}{n_1}\right),\qquad
\theta_i>\theta_c.
$$

En la igualdad está el umbral rasante. Para una guía cuyo rayo sigue el eje, con $\phi$ entre el eje y el plano de corte:

$$
\theta_i=90^\circ-\phi,
\qquad
\phi<90^\circ-\theta_c.
$$

Ese último valor es el límite que suele llamarse “máximo”. En dos caras perpendiculares, el ángulo interno respecto de una normal es complementario del de la otra. Expresa esa relación antes de decidir cómo cambia la condición al aumentar el ángulo externo.

**Autoevaluación:** preguntas 4–5 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]], 15 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y 23–24 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## 4. Reflexión y espejos planos

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#6. Reflexión, imágenes planas y camino de la luz|ley de reflexión, simetría y Fermat]].

$$
\theta_r=\theta_i,\qquad x_i=2x_m-x_o.
$$

Los ángulos se miden desde la normal. Las coordenadas $x_i,x_m,x_o$ se miden en un mismo eje perpendicular al espejo: imagen, espejo y objeto, respectivamente.

$$
\Delta x_i=2\Delta x_m-\Delta x_o.
$$

Si el objeto está fijo, $\Delta x_o=0$ y $\Delta x_i=2\Delta x_m$. No uses el factor 2 sin esa condición. La imagen plana queda a igual distancia detrás del espejo que el objeto delante; es virtual, derecha y de igual tamaño.

Para justificar el rebote en un espejo horizontal, con alturas $h_1,h_2$, separación horizontal $D$ y posición de rebote $x$:

$$
t(x)=\frac{\sqrt{x^2+h_1^2}+\sqrt{(D-x)^2+h_2^2}}{v}.
$$

Con rapidez uniforme, la condición $dt/dx=0$ da

$$
\frac{x}{\sqrt{x^2+h_1^2}}
=\frac{D-x}{\sqrt{(D-x)^2+h_2^2}}
\quad\Longrightarrow\quad\theta_i=\theta_r.
$$

También puedes desplegar el recorrido usando la imagen especular de un extremo. El principio general de Fermat es de tiempo estacionario; en este caso plano y uniforme corresponde al mínimo.

**Autoevaluación:** preguntas 6–7 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Conceptos|Conceptos]] y 25–26 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## 5. Espejos esféricos

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#7. Espejos esféricos: de la geometría al foco|geometría paraxial, foco y aumento]]. En esta sección $f$ es **distancia focal** y $m$ es **aumento**.

| Magnitud | Signo usado |
|---|---|
| $s$ | Positivo para objeto real delante del espejo |
| $s'$ | Positivo: imagen real delante; negativo: virtual detrás |
| $R,f$ | Positivos: cóncavo; negativos: convexo |
| $y,y'$ | Alturas con signo respecto del eje; usualmente se toma el objeto hacia arriba |

Para rayos paraxiales y espejo esférico:

$$
f=\frac R2,\qquad
\frac1s+\frac1{s'}=\frac1f,\qquad
m=\frac{y'}y=-\frac{s'}s.
$$

Si el enunciado da el radio como una magnitud positiva, asigna primero el signo del espejo. Despejes:

$$
s'=\frac{fs}{s-f},\qquad
s=\frac{fs'}{s'-f},\qquad y'=my.
$$

Para resolver desde un aumento dado, usa $s'=-ms$ y sustituye:

$$
\frac1s-\frac1{ms}=\frac1f
\quad\Longrightarrow\quad
s=f\left(1-\frac1m\right),
$$

para valores finitos con $m\ne0$. Para un cóncavo con objeto real, “imagen real de mitad de altura” significa $m=-0.50$, no $+0.50$.

**Controles:** conserva las mismas unidades en $s,s',f,R$; $m$ no tiene unidades. Para objeto real, un convexo da $s'<0$ y $0<m<1$. En cóncavo, $s=f$ da rayos paralelos, sin distancia de imagen finita. Para separar dos imágenes usa coordenadas en un mismo eje y $D=|x_{i,A}-x_{i,B}|$.

**Autoevaluación:** preguntas 12–13 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y 27–28 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## 6. Lentes delgadas

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#8. Lentes delgadas: dos refracciones y una sola imagen|triángulos, dos caras y sistemas]]. Se supone lente delgada, rayos paraxiales y mismo medio exterior a ambos lados.

$$
\frac1s+\frac1{s'}=\frac1f,\qquad
s'=\frac{fs}{s-f},\qquad
m=-\frac{s'}s=\frac{y'}y.
$$

Para luz hacia la derecha, $s>0$ sitúa un objeto real a la izquierda; $s<0$, un objeto virtual a la derecha. $s'>0$ indica imagen real a la derecha; $s'<0$, virtual a la izquierda. $f>0$ es convergente y $f<0$, divergente. **La imagen real sale al lado opuesto que en un espejo:** interpreta el recorrido, no solo el signo.

Con la lente en coordenada $x_L$:

$$
s=x_L-x_o,\qquad s'=x_i-x_L.
$$

$m<0$: invertida respecto del objeto correspondiente; $m>0$: derecha. $|m|$ compara alturas. Los despejes de la sección anterior también sirven para esta ecuación, con los lados físicos propios de la lente.

### Fabricante de lentes

Úsala si necesitas la focal a partir de índices y curvaturas:

$$
\frac1f=
\left(\frac{n_\ell}{n_m}-1\right)
\left(\frac1{R_1}-\frac1{R_2}\right).
$$

- $n_\ell$: índice de la lente; $n_m$: índice del mismo medio exterior en ambos lados.
- Luz hacia la derecha: el radio de cada cara es positivo si su centro de curvatura está a la derecha; negativo si está a la izquierda. Numera las caras en el orden de llegada de la luz.
- Biconvexa simétrica: $R_1=+R$, $R_2=-R$, con $R>0$ geométrico; entonces $1/f=2(n_\ell/n_m-1)/R$ y $R=2f(n_\ell/n_m-1)$.
- Cara plana: $R=\infty$, por tanto $1/R=0$.
- Índices iguales: $1/f=0$, sin enfoque. Cambiar el medio puede invertir el signo de $f$.

No uses $f=R/2$ para una lente: esa relación corresponde a espejos esféricos paraxiales.

### Sistema de dos lentes

Con L1 en $x=0$, L2 en $x=D$ y luz hacia la derecha:

$$
s_2=D-s'_1,\qquad
s'_2=\frac{f_2s_2}{s_2-f_2},\qquad
x_{i,\mathrm{final}}=D+s'_2,\qquad
m_{\mathrm{total}}=m_1m_2.
$$

1. Halla $s'_1$ y sitúa la imagen de L1 sola en el eje.
2. Si $s'_1>D$, resulta $s_2<0$: L2 recibe rayos que ya convergen, objeto virtual para L2.
3. Calcula la segunda imagen, su posición global y la altura $y_f=m_{\mathrm{total}}y_o$.
4. Si se fija la imagen final, usa $s'_2=x_f-D$ y resuelve hacia atrás.

No sumes las focales. Incluso para lentes delgadas **en contacto**, con el mismo medio, la relación es $1/f_{\mathrm{eq}}=1/f_1+1/f_2$, no $f_1+f_2$; los sistemas separados de O18–O19 se resuelven por etapas.

**Autoevaluación:** pregunta 11 y 16 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y 29–30 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## 7. Doble rendija

**Origen:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#9. Doble rendija: de la superposición a las franjas|fase, geometría y posiciones]]. Aquí $m$ es un **orden entero**, no un aumento.

Para fuentes coherentes **en fase**, con polarización compatible y propagación en el mismo medio:

$$
\Delta\phi=\frac{2\pi}{\lambda}\Delta r.
$$

En pantalla lejana, $L\gg d$:

$$
\Delta r\approx d\sin\theta.
$$

Condiciones de interferencia:

$$
\begin{aligned}
\text{máximo: }&\Delta r=m\lambda,\quad m\in\mathbb Z,\\
\text{mínimo: }&\Delta r=\left(q+\frac12\right)\lambda,\quad q\in\mathbb Z.
\end{aligned}
$$

Una cancelación total en los mínimos requiere amplitudes iguales. La coherencia significa fase relativa estable; no garantiza por sí sola fase inicial cero.

Si además estás cerca del centro, $|y|\ll L$, entonces $\sin\theta\approx\tan\theta=y/L$:

$$
y_m\approx\frac{m\lambda L}{d},\qquad
\beta\approx\frac{\lambda L}{d},\qquad
\Delta y_{m,a,b}\approx\frac{|m|L|\lambda_a-\lambda_b|}{d}.
$$

- $d$: separación entre rendijas; $L$: distancia perpendicular a pantalla; $y_m$: posición desde el centro.
- $\beta$: distancia entre máximos vecinos del mismo color.
- La última fórmula compara el mismo orden al mismo lado para dos colores. En otros casos resta las posiciones con sus signos.
- Para coincidencia de máximos: $m_a\lambda_a=m_b\lambda_b$. Si se pide fuera del centro, descarta la solución $m_a=m_b=0$.
- Para hallar longitud de onda desde el espaciado: $\lambda\approx\beta d/L$.

Sin aproximación de ángulo pequeño, pero manteniendo pantalla lejana:

$$
\theta_m\approx\arcsin\!\left(\frac{m\lambda}{d}\right),\qquad
y_m\approx L\tan\theta_m.
$$

Revisa $|m\lambda/d|\le1$; la dirección exactamente rasante no da posición finita en la pantalla. Para campo cercano, calcula $r_2-r_1$ con la geometría completa en lugar de $d\sin\theta$.

**Unidades y controles:** nm a m ($10^{-9}$), mm a m ($10^{-3}$); $\lambda L/d$ es longitud. “Tercer orden” significa $m=3$, mientras que $\beta$ no lleva ese factor. Duplicar $L$ o $\lambda$ duplica el espaciado; duplicar $d$ lo divide por dos. Usa la longitud de onda en el medio de propagación.

**Autoevaluación:** pregunta 14 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Fórmulas|Fórmulas]] y 31–33 de [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Comprobaciones por etapa|Comprobaciones por etapa]].

## Comprobaciones rápidas

- Snell: comprueba medios y normal antes del arcoseno.
- Espejos y lentes: el signo sitúa la imagen según el recorrido propio del elemento; $|m|$ y el signo de $m$ responden preguntas diferentes.
- Para objeto real, cóncavo o lente convergente: entre el foco y el elemento la imagen es virtual y derecha; en el foco no hay imagen a distancia finita. No traslades esa descripción a cualquier objeto virtual o elemento divergente.
- Sistemas: cada distancia se mide desde su elemento; la posición final requiere un eje común.
- Franjas: distingue posición desde el centro, espaciado vecino y separación de dos colores.

**Cierre:** [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Repaso del módulo|repaso del módulo]] · [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica|práctica]].
