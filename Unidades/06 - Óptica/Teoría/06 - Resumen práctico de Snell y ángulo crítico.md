---
tags: [fisica-aplicada, unidad-06, optica, refraccion, reflexion-total, resumen-practico]
aliases: [Cómo resolver Snell y reflexión total]
---

# Snell y ángulo crítico: cómo resolver los ejercicios

**Objetivo:** decidir qué ángulo usar, calcular la refracción y reconocer cuándo ocurre reflexión interna total. Cubre los planteos de **O4, O23, O11, O10 y O22**: una interfaz, comparación agua/aire, corte oblicuo, dos caras perpendiculares y capas paralelas.

**Volver:** [[Unidades/06 - Óptica/Teoría/06 - Óptica|Óptica]] · **Otro resumen:** [[Unidades/06 - Óptica/Teoría/06 - Resumen práctico de espejos|ejercicios de espejos]].

## 1. Primer paso: medios, sentido y normal

Antes de sustituir números:

1. Dibuja la **interfaz**, la superficie que separa los medios.
2. Traza la **normal**, perpendicular a esa superficie en el punto de incidencia.
3. Dibuja una flecha sobre el rayo: llama **medio 1 al de donde viene** y **medio 2 al que puede pasar**.
4. Anota $n_1,n_2$ y convierte todos los ángulos a su referencia correcta.

$n$ es el índice de refracción y no tiene unidades. Usa los valores del enunciado. Los ángulos de incidencia $\theta_i$, reflexión $\theta_r$ y transmisión $\theta_t$ se miden **desde la normal local**, entre $0^\circ$ y $90^\circ$.

$$\boxed{\theta_{\text{desde la normal}}=90^\circ-\phi_{\text{desde la superficie}}}.$$

Por ejemplo, $30^\circ$ con la superficie significa **$60^\circ$ de incidencia**. Si el rayo alcanza otra cara, dibuja la normal de esa nueva cara.

![[imagenes/optica-refraccion.svg|620]]

*Identifica el rayo que llega, el que regresa al medio 1 y el que pasa al medio 2. La línea discontinua es la referencia angular; el esquema es orientativo, no sirve para medir los ángulos del ejercicio.*

## 2. Elegir entre reflexión y refracción

| Lo que te piden | Relación que corresponde |
|---|---|
| Dirección del rayo que se refleja | $\theta_r=\theta_i$ |
| Dirección del rayo que cruza la interfaz | $n_1\sin\theta_i=n_2\sin\theta_t$ |
| Si la luz puede salir o queda totalmente reflejada | Comparar índices y, si $n_1>n_2$, comparar $\theta_i$ con $\theta_c$ |
| Ángulo límite para que no salga | Calcular $\theta_c$ y relacionarlo con la geometría del dibujo |

**Reflexión y refracción pueden ocurrir simultáneamente.** “No hay reflexión total” significa que existe un rayo transmitido; no obliga a que desaparezca toda reflexión. Snell determina direcciones, no qué porcentaje de luz toma cada camino.

## 3. Snell: método para una interfaz

Para los medios transparentes e isótropos de estos ejercicios:

$$
\boxed{n_1\sin\theta_i=n_2\sin\theta_t}
\quad\Longrightarrow\quad
\boxed{\theta_t=\arcsin\!\left(\frac{n_1}{n_2}\sin\theta_i\right)}.
$$

Usa la calculadora en **DEG** cuando los datos están en grados. Primero calcula el argumento $q=(n_1/n_2)\sin\theta_i$; después aplica el arcoseno:

- **$0\le q<1$:** existe rayo transmitido; calcula $\theta_t$.
- **$q=1$:** $\theta_t=90^\circ$, salida rasante en el límite.
- **$q>1$:** no existe ángulo transmitido real; si los datos y referencias son correctos, hay reflexión interna total.

El símbolo $\arcsin$ o la función $\sin^{-1}$ de la calculadora significa **“buscar el ángulo cuyo seno es…”**. No significa $1/\sin$.

### Control antes y después del cálculo

| Cambio de medio | Qué esperar para incidencia oblicua con transmisión |
|---|---|
| $n_2>n_1$ | $\theta_t<\theta_i$: se acerca a la normal |
| $n_2<n_1$ | $\theta_t>\theta_i$: se aleja de la normal |
| $n_2=n_1$ | $\theta_t=\theta_i$: no se desvía |

Si $\theta_i=0^\circ$, el rayo sigue sobre la normal aunque cambie el índice.

### Ejemplo de la materia: aceite a agua — O4

$n_1=1.45$, $n_2=1.33$, $\theta_i=50^\circ$. Como el índice disminuye, esperamos que el rayo se aleje de la normal, si puede transmitirse.

$$
\sin\theta_t=\frac{1.45}{1.33}\sin50^\circ\approx0.835<1.
$$

$$\boxed{\theta_t\approx56.63^\circ\text{ desde la normal}}.$$

El resultado es mayor que $50^\circ$, como esperábamos. Si pidieran el ángulo con la superficie, sería $90^\circ-56.63^\circ=33.37^\circ$.

### Si la incógnita es otra

Despeja la misma ley antes de sustituir:

$$
n_2=n_1\frac{\sin\theta_i}{\sin\theta_t},\qquad
\theta_i=\arcsin\!\left(\frac{n_2}{n_1}\sin\theta_t\right).
$$

La primera expresión requiere $\sin\theta_t\ne0$: una entrada normal, con ambos ángulos nulos, no permite hallar el índice a partir de esos ángulos.

## 4. Ángulo crítico: decidir si hay reflexión total

Al pasar a un medio de **menor índice**, el rayo transmitido se aleja de la normal. El límite ocurre cuando sale rozando la interfaz: $\theta_t=90^\circ$. En Snell:

$$
n_1\sin\theta_c=n_2\sin90^\circ=n_2
\quad\Longrightarrow\quad
\boxed{\theta_c=\arcsin\!\left(\frac{n_2}{n_1}\right)}.
$$

> [!important] Las dos condiciones se exigen juntas
> Para reflexión interna total: **$n_1>n_2$ y $\theta_i>\theta_c$**. El índice grande corresponde al medio en el que viaja el rayo antes de llegar a la interfaz.

| Situación | Conclusión |
|---|---|
| $n_1\le n_2$ | No hay reflexión interna total en este sentido de propagación |
| $n_1>n_2$ y $\theta_i<\theta_c$ | Hay transmisión; usa Snell para hallar su dirección |
| $n_1>n_2$ y $\theta_i=\theta_c$ | Umbral: dirección transmitida rasante |
| $n_1>n_2$ y $\theta_i>\theta_c$ | Reflexión interna total; $\theta_r=\theta_i$ |

**Procedimiento si preguntan “¿sale o se refleja totalmente?”:** identifica el sentido → compara índices → calcula el crítico si corresponde → escribe la desigualdad con la incidencia. Esa comparación es la justificación del resultado.

### Ejemplo del parcial: vidrio rodeado de agua o aire — O23

El rayo viaja dentro de vidrio, $n_v=1.52$, y llega a $55^\circ$ con la normal. Cambia el medio exterior, manteniendo esa incidencia:

| Exterior | Ángulo crítico | Comparación y resultado |
|---|---|---|
| Agua, $n=1.33$ | $\arcsin(1.33/1.52)=61.04^\circ$ | $55^\circ<61.04^\circ$: emerge al agua |
| Aire, $n=1.00$ | $\arcsin(1.00/1.52)=41.14^\circ$ | $55^\circ>41.14^\circ$: reflexión total |

Si además piden la dirección en el agua:

$$\theta_t=\arcsin\!\left(\frac{1.52}{1.33}\sin55^\circ\right)=69.42^\circ.$$

En aire no calcules un ángulo transmitido: el argumento sería mayor que 1. Allí el rayo se refleja con **$\theta_r=55^\circ$**.

**¿Dónde es más fácil confinarlo?** En aire: el crítico es menor y más ángulos de incidencia lo superan. El ángulo crítico depende de los índices; cambiar la incidencia no cambia $\theta_c$.

## 5. Corte oblicuo: el ángulo pedido no es la incidencia — O11

El rayo sigue el eje de una guía de plástico. El enunciado llama $\phi$ al ángulo entre **el rayo y el plano del corte**. Aquí usamos $\phi$ para distinguirlo de la incidencia; en O11 se llama $\theta$.

Como la normal es perpendicular al corte:

$$\theta_i=90^\circ-\phi.$$

Para que haya reflexión total:

$$
90^\circ-\phi>\theta_c
\quad\Longrightarrow\quad
\boxed{\phi<90^\circ-\theta_c}.
$$

En O11, $n_p=1.60$:

| Medio exterior | $\theta_c$ | Límite del ángulo del corte |
|---|---|---|
| Aire, $n=1.00$ | $38.68^\circ$ | $\phi_{\mathrm{lim}}=51.32^\circ$ |
| Agua, $n=1.33$ | $56.23^\circ$ | $\phi_{\mathrm{lim}}=33.77^\circ$ |

El TP pide el “máximo”: informa ese **valor límite** y aclara que la reflexión total estricta exige un ángulo de corte **menor**. En la igualdad la transmisión es rasante.

**Control:** al aumentar $\phi$, disminuye la incidencia desde la normal. Por eso aumentar el ángulo de corte puede hacer que se pierda la reflexión total.

## 6. Dos caras perpendiculares: cambia la normal — O10

Entra luz por la cara lateral de un cubo y luego alcanza la cara superior. Distingue tres ángulos:

- $\alpha$: incidencia externa en la cara lateral.
- $\beta$: ángulo dentro del vidrio desde la normal lateral.
- $\gamma$: incidencia dentro del vidrio desde la normal superior.

![[imagenes/optica-cubo-reflexion.svg|620]]

*Las normales de ambas caras son perpendiculares. El ángulo de entrada dentro del cubo y la incidencia superior son complementarios.*

$$\boxed{\gamma=90^\circ-\beta}.$$

El método combina **dos fronteras**, cada una con su planteo:

1. Entrada lateral: $n_m\sin\alpha=n_v\sin\beta$.
2. Cara superior: calcula $\theta_c=\arcsin(n_m/n_v)$ para el paso vidrio → exterior.
3. En el umbral superior, $\gamma=\theta_c$; por geometría, $\beta_{\mathrm{lim}}=90^\circ-\theta_c$.
4. Vuelve a la entrada para encontrar el ángulo externo límite:

$$
\alpha_{\mathrm{lim}}=
\arcsin\!\left[\frac{n_v}{n_m}\sin(90^\circ-\theta_c)\right].
$$

En O10, $n_m=1.30$, $n_v=1.50$: $\theta_c=60.07^\circ$, $\beta_{\mathrm{lim}}=29.93^\circ$ y **$\alpha_{\mathrm{lim}}\approx35.1^\circ$**.

**En esta geometría**, mientras el rayo alcance la cara superior, la reflexión total ocurre para $\alpha<35.1^\circ$. Al aumentar $\alpha$, aumenta $\beta$ y disminuye $\gamma$; superar el límite hace que la incidencia superior baje del crítico y aparezca transmisión. El ángulo que se compara con $\theta_c$ es **$\gamma$**, no $\alpha$.

Si piden conectar los centros de ambas caras, los catetos internos son iguales: $\beta=45^\circ$. Entonces:

$$\alpha=\arcsin\!\left(\frac{1.50}{1.30}\sin45^\circ\right)\approx54.7^\circ.$$

En ese recorrido, $\gamma=45^\circ<60.07^\circ$: el rayo puede salir por arriba. Este caso y el umbral son preguntas distintas del ejercicio.

## 7. Varias capas paralelas: Snell en cada frontera — O22

Si las caras son paralelas, sus normales también lo son. Puedes encadenar:

$$n_a\sin\theta_a=n_p\sin\theta_p=n_v\sin\theta_v.$$

Para cada capa calcula **su propio ángulo**. Si después piden una distancia sobre una cara, usa el triángulo del tramo: con espesor perpendicular $e$,

$$\tan\theta=\frac{x}{e}\quad\Longrightarrow\quad\boxed{x=e\tan\theta}.$$

En O22: aire con $n_a=1$, entrada a $45^\circ$, plástico de $n_p=1.62$, $e_p=2.00\,\mathrm{cm}$, y vidrio de $n_v=1.47$, $e_v=3.00\,\mathrm{cm}$:

$$
\theta_p=\arcsin\frac{\sin45^\circ}{1.62}=25.88^\circ,\qquad
\theta_v=\arcsin\frac{\sin45^\circ}{1.47}=28.75^\circ.
$$

Como $D$ se define como el avance horizontal total:

$$D=e_p\tan\theta_p+e_v\tan\theta_v\approx2.616\,\mathrm{cm}.$$

**Dos controles:** no uses un índice promedio y no confundas $e\tan\theta$ con la longitud oblicua del recorrido, $e/\cos\theta$. La definición de $D$ y las caras paralelas son los supuestos explicitados en O22 para reconstruir la figura ausente del modelo 2025.

Si aparecen **dos colores**, repite Snell con el índice de cada color. En la placa de O5, las salidas se separan $\Delta x=e|\tan\theta_a-\tan\theta_b|$. Si el medio inicial y final es el mismo y las caras son paralelas, cada rayo emerge paralelo a su incidente.

## 8. Qué revisar antes de entregar

- ¿Ordené $n_1,n_2$ según el sentido real del rayo?
- ¿Medí el ángulo desde la normal de la cara que estoy analizando?
- ¿Puse la calculadora en grados y comprobé el argumento antes del arcoseno?
- ¿El acercamiento o alejamiento de la normal coincide con el cambio de índice?
- Para reflexión total, ¿justifiqué **tanto** $n_1>n_2$ **como** $\theta_i>\theta_c$?
- Si piden un máximo o mínimo, ¿convertí la condición del crítico al ángulo que realmente pide el enunciado?

**Para practicar:** entra a [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|la familia de refracción y reflexión total]]. Sigue **O4 → O23 → O11 → O10 → O22**; O5 añade dos colores. Si no te dan el índice directamente, [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#1. Rapidez e índice|consulta cómo obtenerlo a partir de rapidez o longitudes de onda]].

**Base de este resumen:** síntesis de las [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Refracción y reflexión total|resoluciones del módulo]], con O23 del primer parcial 2026, los problemas 1, 7 y 8 del TP 3 y la reconstrucción O22. Para profundizar: [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#3. De Huygens a la ley de Snell|origen de Snell]] y [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#5. Reflexión total interna: cuándo la luz queda atrapada|origen del ángulo crítico]].
