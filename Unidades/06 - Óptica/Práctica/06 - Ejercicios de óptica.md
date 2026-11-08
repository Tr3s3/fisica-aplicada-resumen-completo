---
tags: [fisica-aplicada, ejercicios, unidad-06, optica, interferencia, refraccion, espejos, lentes]
---

# Ejercicios de óptica

Esta nota reúne los 22 ejercicios de la unidad, agrupados por familias. Lee la referencia teórica del bloque, intenta el planteo sin ayuda y abre la pista solo si te trabas. Después compara tu procedimiento con la resolución correspondiente.

**Resoluciones:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica|resoluciones de óptica]] · **Recorrido:** [[Unidades/06 - Óptica/Teoría/06 - Óptica|mapa de la unidad]].

**Etiquetas:** M reproduce un planteo de modelo; R practica una variante de una familia examinada; C cubre contenidos complementarios. Cada ejercicio conserva su fuente y su prioridad de examen o didáctica.

## Índice de familias

| Familia | Ejercicios | Consulta |
|---|---|---|
| [[#Interferencia de doble rendija\|Interferencia de doble rendija]] | O1–O3 | [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Interferencia de doble rendija\|Resoluciones de esta familia]] |
| [[#Refracción y reflexión total\|Refracción y reflexión total]] | O4–O6, O10–O11 y O21–O22 | [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Refracción y reflexión total\|Resoluciones de esta familia]] |
| [[#Reflexión y espejos planos\|Reflexión y espejos planos]] | O7–O9 | [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Reflexión y espejos planos\|Resoluciones de esta familia]] |
| [[#Espejos esféricos\|Espejos esféricos]] | O12–O15 | [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Espejos esféricos\|Resoluciones de esta familia]] |
| [[#Lentes delgadas y sistemas\|Lentes delgadas y sistemas]] | O16–O20 | [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Lentes delgadas y sistemas\|Resoluciones de esta familia]] |

## Interferencia de doble rendija

**Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#9. Doble rendija: de la superposición a las franjas]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#7. Doble rendija]] · **Resoluciones:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Interferencia de doble rendija|Interferencia de doble rendija]].

> [!info] Qué significan las etiquetas
> **M** conserva el tipo y los datos centrales de un modelo consultado. **R** varía una familia presente en un modelo. **C** cubre desde un TP una habilidad sin aparición identificada en los modelos. La prioridad de examen se declara por separado: en los cuatro modelos de segundo parcial, la doble rendija aparece una vez.

**Práctica prioritaria basada en el modelo**

### O1. Máximos de dos colores — M · evidencia media; prioridad didáctica alta

Una fuente produce luz de dos longitudes de onda, $\lambda_1=430\,\mathrm{nm}$ y $\lambda_2=510\,\mathrm{nm}$. Se usa para iluminar dos rendijas separadas $d=0.025\,\mathrm{mm}$; la pantalla está a $L=1.50\,\mathrm m$.

![[imagenes/optica-doble-rendija.svg]]

**Se pide**

1. Calcula la posición del máximo brillante de tercer orden para cada longitud de onda.
2. Determina la separación entre esos dos máximos.
3. Explica qué significa que las ondas que interfieren sean coherentes. Aclara si los dos colores distintos son coherentes entre sí.

> [!tip]- Pista de planteo
> Convierte $d$ y ambas longitudes de onda a metros. Para cada color usa $y_m\approx m\lambda L/d$ con $m=3$; luego resta las posiciones. Distingue las dos ondas que llegan desde las rendijas para un mismo color de las componentes de frecuencias diferentes de la fuente.

**Fuente:** modelo del segundo parcial 2023, problema 1.
**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O1. Máximos de dos colores|resolución O1]].

### O2. Espaciado de franjas con una fuente monocromática — R · evidencia media; prioridad didáctica alta

Un láser de longitud de onda $\lambda=532\,\mathrm{nm}$ ilumina dos rendijas separadas $d=0.300\,\mathrm{mm}$. Una pantalla se coloca a $L=1.80\,\mathrm m$.

**Se pide**

1. Calcula la separación $\beta$ entre máximos brillantes vecinos.
2. ¿A qué distancia del máximo central aparece el máximo brillante de tercer orden?
3. ¿A qué distancia del centro aparece el primer mínimo oscuro a cada lado?

> [!tip]- Pista de planteo
> En el régimen de ángulos pequeños, $\beta=\lambda L/d$. El máximo de orden $m$ está a $y_m=m\beta$. El primer mínimo está a media separación desde el centro, no a una separación completa.

**Familia de origen:** variante de interferencia de doble rendija del modelo 2023, problema 1.
**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O2. Espaciado con una fuente monocromática|resolución O2]].

### O3. Coincidencia de máximos de dos colores — R · evidencia media; prioridad didáctica alta

Dos láseres, uno de $\lambda_1=450\,\mathrm{nm}$ y otro de $\lambda_2=600\,\mathrm{nm}$, iluminan por separado el mismo montaje de doble rendija. La separación entre rendijas es $d=0.250\,\mathrm{mm}$ y la pantalla se encuentra a $L=1.50\,\mathrm m$.

**Se pide**

1. Calcula el espaciado de franjas de cada color.
2. Encuentra el primer máximo no central donde coinciden máximos de ambos patrones. Indica el orden de cada color y la distancia al centro.
3. Explica por qué dos colores distintos no forman entre sí una única onda coherente, aunque se puedan superponer sus patrones.

> [!tip]- Pista de planteo
> En una misma posición, las condiciones de máximo exigen $m_1\lambda_1=m_2\lambda_2$. Busca los menores enteros positivos que cumplen esa razón. Cada láser por separado ilumina ambas rendijas y produce su propio patrón coherente.

**Familia de origen:** variante de interferencia de doble rendija del modelo 2023, problema 1.
**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O3. Coincidencia de máximos|resolución O3]].

### Clave breve — Interferencia de doble rendija

> [!example]- Abrir después del intento
> **O1.** $y_3(430\,\mathrm{nm})=7.74\,\mathrm{cm}$; $y_3(510\,\mathrm{nm})=9.18\,\mathrm{cm}$; separación $1.44\,\mathrm{cm}$. Fuentes coherentes tienen igual frecuencia y diferencia de fase constante. Los dos colores no son mutuamente coherentes; cada color sí genera un patrón al dividirse entre las dos rendijas.
>
> **O2.** $\beta=3.192\,\mathrm{mm}$; $y_3=9.576\,\mathrm{mm}$; primer mínimo a $1.596\,\mathrm{mm}$ del centro en cada lado.
>
> **O3.** $\beta_1=2.70\,\mathrm{mm}$, $\beta_2=3.60\,\mathrm{mm}$. Coinciden por primera vez en órdenes $m_1=4$ y $m_2=3$, a $10.8\,\mathrm{mm}$ del centro. Las intensidades de las dos fuentes de diferente frecuencia se suman sin un patrón de interferencia cruzada estable.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Interferencia de doble rendija|resoluciones de esta familia]] · [[#Refracción y reflexión total|siguiente familia: refracción y reflexión total]].

---

## Refracción y reflexión total

**Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#3. De Huygens a la ley de Snell]] · [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#4. Bloques, profundidad aparente y color]] · [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#5. Reflexión total interna: cuándo la luz queda atrapada]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica]] · **Resoluciones:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Refracción y reflexión total|Refracción y reflexión total]].

> [!info] Clasificación
> Con los primeros parciales 2023–2026 y el global 2023 incorporados al cotejo, O4–O5 y O10–O11 pasan a **R**: entrenan familias examinadas de refracción, cambio de medio y reflexión total. O6 sigue siendo **C** de profundidad aparente. O21 es **M** de los primeros parciales 2023/2024 y O22 es **R** del primer parcial 2025, cuyo dibujo no está disponible. Las fuentes completas están en la auditoría.

### O4. Del aceite al agua — R · TP 3, problema 1; prioridad didáctica alta

Un rayo pasa desde una capa de aceite con índice de refracción $n_1=1.45$ hacia agua con $n_2=1.33$. El ángulo de incidencia es $\theta_1=50^\circ$.

![[imagenes/optica-refraccion.svg]]

**Se pide:** calcula el ángulo $\theta_2$ del rayo dentro del agua. Explica si se acerca o se aleja de la normal.

> [!tip]- Pista de planteo
> Usa $n_1\sin\theta_1=n_2\sin\theta_2$. El ángulo de incidencia se mide desde la normal. Antes del arcoseno revisa que el valor obtenido para $\sin\theta_2$ no supere 1.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O4. Del aceite al agua|resolución O4]].

### O5. Dos colores atraviesan un bloque de hielo — R · TP 3, problema 2; prioridad didáctica alta

Un bloque de hielo tiene espesor $d=2.00\,\mathrm{km}$. Desde el aire llega un haz bicromático con un ángulo de $55^\circ$ respecto de la superficie del hielo. Un color se propaga dentro del hielo un $15\%$ más lento que en el aire; el otro viaja a $2.70\times10^8\,\mathrm{m/s}$. Supón $v_{\mathrm{aire}}=c=3.00\times10^8\,\mathrm{m/s}$, caras paralelas y que ambos rayos entran por el mismo punto.

**Se pide**

1. Halla la rapidez y el índice de cada color en el hielo.
2. Calcula los ángulos de ambos rayos dentro del hielo y su separación angular.
3. Calcula la distancia entre los puntos donde salen por la segunda cara.

> [!tip]- Pista de planteo
> Convierte primero el ángulo: $55^\circ$ desde la superficie equivale a $35^\circ$ desde la normal. Halla $n=c/v$ para cada color y usa Snell en la entrada. Dentro del bloque, el desplazamiento horizontal es $x=d\tan\theta$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O5. Dos colores en el hielo|resolución O5]].

### O6. Madera sumergida vista desde arriba — C · TP 3, problema 3; prioridad didáctica alta

Un trozo de madera se encuentra a $20.0\,\mathrm m$ por debajo de la superficie del agua. Una persona en el aire mira casi perpendicularmente hacia abajo. Usa $n_{\mathrm{agua}}=1.333$ y $n_{\mathrm{aire}}=1.000$.

**Se pide:** estima la profundidad aparente del trozo de madera y cuánto más cerca de la superficie parece estar.

> [!tip]- Pista de planteo
> Es una aproximación de observación cercana a la normal: $d_{\mathrm{ap}}\approx d_{\mathrm{real}}(n_{\mathrm{aire}}/n_{\mathrm{agua}})$. No cambies la profundidad real: estás calculando la posición aparente que reconstruye el ojo.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O6. Profundidad aparente|resolución O6]].

### O10. Entrada lateral y reflexión en la cara superior — R · TP 3, problema 7; prioridad didáctica alta

Un rayo llega desde un medio de índice $n_m=1.30$ al centro de la cara lateral de un cubo de vidrio de índice $n_v=1.50$. Dentro del cubo, el rayo llega al centro de la cara superior. Como ambas caras tienen el mismo lado, el tramo interno une los puntos medios y forma $45^\circ$ con la normal a la cara lateral.

![[imagenes/optica-cubo-reflexion.svg]]

**Se pide**

1. Calcula el ángulo externo de incidencia que permite que el rayo salga por el centro de la cara superior.
2. Encuentra el ángulo externo límite que separa los casos con y sin reflexión total en la cara superior.
3. Indica qué pasa si el ángulo externo supera ese límite.

> [!tip]- Pista de planteo
> En (1), usa Snell en la cara lateral con ángulo interno de $45^\circ$. En (2), primero calcula $\theta_c$ para vidrio a medio externo. Relaciona la incidencia sobre la cara superior con el ángulo interno de entrada: son complementarios. La igualdad es el umbral rasante; para reflexión total estricta, el ángulo externo debe quedar apenas por debajo del umbral.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O10. Entrada lateral al cubo y reflexión total arriba|resolución O10]].

### O11. Corte oblicuo de una guía de plástico — R · TP 3, problema 8; prioridad didáctica alta

Un haz viaja dentro de un tubo de plástico con $n_p=1.60$, paralelo al eje del tubo. La cara de salida se corta oblicuamente. En la figura, $\theta$ es el ángulo agudo entre el eje del tubo y el plano de corte.

![[imagenes/optica-reflexion-total.svg]]

**Se pide:** calcula el máximo $\theta$ que permite reflexión total interna cuando el tubo está en (a) aire, $n_a=1.00$, y (b) agua, $n_w=1.33$.

> [!tip]- Pista de planteo
> La reflexión total se define con el ángulo de incidencia medido desde la normal a la cara, no desde la pared. A partir del dibujo, expresa ese ángulo como $90^\circ-\theta$ y compáralo con $\theta_c$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O11. Corte oblicuo de una guía|resolución O11]].

### O21. Índice desde el cambio de longitud de onda — M · primeros parciales 2023 y 2024

Luz de longitud de onda $596\,\mathrm{nm}$ en aire entra en un aceite donde su longitud de onda es $334\,\mathrm{nm}$. Aproxima $n_{\mathrm{aire}}=1$ y $c=3.00\times10^8\,\mathrm{m/s}$.

**Se pide:** dibuja la interfaz y señala las dos longitudes de onda; calcula el índice del aceite, la frecuencia y la rapidez dentro del aceite. Explica qué magnitud se conserva. No se da un ángulo: el dibujo es cualitativo y no permite calcular una desviación numérica.

> [!tip]- Pista de planteo
> La frecuencia se conserva: $c/\lambda_0=v/\lambda$. Combina con $n=c/v$ para obtener $n=\lambda_0/\lambda$. Usa las longitudes de onda en metros al calcular la frecuencia.

**Fuente:** [primer parcial 2023, P4](zotero://select/library/items/XB579CRN) y [primer parcial 2024, P5](zotero://select/library/items/67PJMB4S), mismo enunciado repetido.
**Resolución:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O21. Índice desde el cambio de longitud de onda|O21]].

### O22. Refracción sucesiva en dos capas — R · primer parcial 2025 con geometría explícita

Desde el aire, un rayo llega a $45^\circ$ **con la normal** a una capa de plástico de espesor perpendicular $e_p=2.00\,\mathrm{cm}$ e índice $n_p=1.62$. Debajo hay una capa de vidrio de espesor $e_v=3.00\,\mathrm{cm}$ e índice $n_v=1.47$. Las tres interfaces son planas y paralelas. Define $D$ como el avance horizontal entre el punto de entrada superior y el punto donde el rayo alcanza la base del vidrio. Usa $n_a=1$.

> [!info] Supuestos añadidos
> El texto del modelo 2025 pregunta por una distancia D sin conservar su figura. Se especifican aquí la normal, las caras paralelas y qué representa D para obtener un problema determinado. Es una reconstrucción **R**; no se atribuye esta definición de D a la figura perdida.

**Se pide:** calcula los ángulos en plástico y vidrio; determina D; explica por qué no puedes usar un único índice para las dos capas. Haz tu esquema antes de calcular.

> [!tip]- Pista de planteo
> Usa Snell en cada frontera. Para caras paralelas, $n_a\sin\theta_a=n_p\sin\theta_p=n_v\sin\theta_v$. Cada avance es $e\tan\theta$ y los avances de los dos tramos se suman.

**Fuente:** [primer parcial 2025, P3](zotero://select/library/items/KUYP7UCC), con los supuestos identificados arriba.
**Resolución:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O22. Refracción sucesiva en dos capas|O22]].

### Clave breve — Refracción y reflexión total

> [!example]- Abrir después del intento
> **O4.** $\theta_2\approx56.63^\circ$; se aleja de la normal porque el índice disminuye.
>
> **O5.** $v_1=2.55\times10^8\,\mathrm{m/s}$, $n_1=1.1765$; $v_2=2.70\times10^8\,\mathrm{m/s}$, $n_2=1.1111$. En hielo: $\theta_1\approx29.18^\circ$, $\theta_2\approx31.08^\circ$, separación $1.90^\circ$. Distancia de salida $\approx88.7\,\mathrm m$.
>
> **O6.** Profundidad aparente $\approx15.0\,\mathrm m$; parece estar $5.0\,\mathrm m$ más cerca de la superficie.
>
> **O10.** Incidencia externa del inciso (1): $\approx54.7^\circ$. Crítico vidrio-medio: $\theta_c\approx60.1^\circ$; el rayo interno de entrada debe estar en el límite de $29.9^\circ$, correspondiente a $\theta_{\mathrm{ext}}\approx35.1^\circ$.
>
> **O11.** En aire: $\theta_{\max}\approx51.3^\circ$. En agua: $\theta_{\max}\approx33.8^\circ$.
>
> **O21.** $n=1.7844$, $f=5.0336\times10^{14}\,\mathrm{Hz}$, $v=1.6812\times10^8\,\mathrm{m/s}$.
>
> **O22.** $\theta_p=25.88^\circ$, $\theta_v=28.75^\circ$; $D=2.616\,\mathrm{cm}$ con la definición explícita del enunciado.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Refracción y reflexión total|resoluciones de esta familia]] · [[#Reflexión y espejos planos|siguiente familia: reflexión y espejos planos]].

---

## Reflexión y espejos planos

**Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#6. Reflexión, imágenes planas y camino de la luz]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#4. Reflexión y espejos planos]] · **Resoluciones:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Reflexión y espejos planos|Reflexión y espejos planos]].

> [!info] Clasificación
> O7–O9 son **C**, adaptados de los problemas 4–6 del TP 3 de Óptica Geométrica 2025. La reflexión especular es base para todos los espejos; las otras consignas permiten practicar el uso geométrico de esa ley.

### O7. Dos espejos en ángulo recto — C · TP 3, problema 4; prioridad didáctica alta

Dos espejos planos forman una esquina de $90^\circ$: el primero es horizontal y el segundo vertical. Un rayo incide en el espejo horizontal a $11.5\,\mathrm{cm}$ de la esquina. El espejo vertical mide $28.0\,\mathrm{cm}$; se quiere que el rayo reflejado llegue a su punto medio.

![[imagenes/optica-espejos-a-90.svg]]

**Se pide:** encuentra el ángulo de incidencia respecto de la normal al primer espejo.

> [!tip]- Pista de planteo
> Desde el punto de incidencia hasta el objetivo, la separación horizontal es $11.5\,\mathrm{cm}$ y la vertical es la mitad de $28.0\,\mathrm{cm}$. Dibuja el triángulo del rayo reflejado y convierte al ángulo desde la normal.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O7. Dos espejos en ángulo recto|resolución O7]].

### O8. Tiempo de un rayo que se refleja — C · TP 3, problema 5; prioridad didáctica alta

Dos puntos están a alturas $y_1$ y $y_2$ sobre un espejo plano horizontal y separados horizontalmente por una distancia $l$. Un rayo parte del punto 1, se refleja una sola vez y llega al punto 2. El punto de reflexión se encuentra a distancia horizontal $x$ desde la vertical del punto 1. La luz se propaga a rapidez $c$.

![[imagenes/optica-reflexion-minimo.svg]]

**Se pide**

1. Demuestra que la distancia recorrida es $D=\sqrt{y_1^2+x^2}+\sqrt{y_2^2+(l-x)^2}$ y, por tanto, que el tiempo es $t=D/c$.
2. Encuentra la condición sobre $x$ para que el tiempo sea estacionario.
3. Interpreta esa condición en términos de los ángulos de incidencia y reflexión.

> [!tip]- Pista de planteo
> Los dos tramos son hipotenusas de triángulos rectángulos. Para minimizar el tiempo, deriva $D(x)$ y plantea $dD/dx=0$; $c$ es constante. Relaciona cada fracción de la derivada con el seno de un ángulo medido desde la normal.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O8. Tiempo del rayo reflejado|resolución O8]].

### O9. Un espejo que se desplaza — C · TP 3, problema 6; prioridad didáctica media

Un objeto puntual permanece fijo delante de un espejo plano. El espejo se desplaza una distancia $x$ perpendicular a su superficie, sin girar.

![[imagenes/optica-espejos-planos.svg]]

**Se pide:** demuestra que la imagen del objeto se desplaza una distancia $2x$ en el mismo sentido que el espejo.

> [!tip]- Pista de planteo
> Usa un eje perpendicular al espejo. Si la coordenada del espejo es $x_m$ y la del objeto $x_o$, la imagen está al otro lado y a la misma distancia del plano.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O9. Desplazamiento de la imagen|resolución O9]].

### Clave breve — Reflexión y espejos planos

> [!example]- Abrir después del intento
> **O7.** $\theta_i=\arctan(11.5/14.0)\approx39.4^\circ$ desde la normal.
>
> **O8.** $D(x)=\sqrt{y_1^2+x^2}+\sqrt{y_2^2+(l-x)^2}$; $t=D/c$. La condición de extremo es $\frac{x}{\sqrt{y_1^2+x^2}}=\frac{l-x}{\sqrt{y_2^2+(l-x)^2}}$, que equivale a $\sin\theta_i=\sin\theta_r$ y luego a $\theta_i=\theta_r$.
>
> **O9.** Con $x_i=2x_m-x_o$, al variar el espejo $\Delta x_i=2\Delta x_m=2x$.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Reflexión y espejos planos|resoluciones de esta familia]] · [[#Espejos esféricos|siguiente familia: espejos esféricos]].

---

## Espejos esféricos

**Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#7. Espejos esféricos: de la geometría al foco]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#5. Espejos esféricos]] · **Resoluciones:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Espejos esféricos|Espejos esféricos]].

> [!info] Clasificación
> O12–O15 son **R**: los TP practican variantes de imágenes en espejos, familia presente en el primer parcial 2024 (cóncavo) y el global 2023 (convexo). Se conserva la procedencia del TP; no se afirma que esos datos sean los de un modelo.

### O12. Un espejo cóncavo en cuatro posiciones — R · TP 3, problema 9; prioridad didáctica alta

Un espejo cóncavo tiene radio de curvatura $R=1.00\,\mathrm m$. Frente a él se coloca un objeto de altura $y=40.0\,\mathrm{cm}$. Analiza por separado estas distancias al espejo: (a) $1.40\,\mathrm m$, (b) $1.00\,\mathrm m$, (c) $0.80\,\mathrm m$ y (d) $0.30\,\mathrm m$.

![[imagenes/optica-espejo-concavo.svg]]

**Se pide** para cada posición: distancia de imagen, aumento, altura de imagen y clasificación como real/virtual, derecha/invertida y mayor/menor. Haz además un diagrama de rayos sencillo.

> [!tip]- Pista de planteo
> Calcula primero $f=R/2=0.50\,\mathrm m$. Convierte todas las distancias a cm o m, sin mezclarlas. Para cada caso usa $1/s+1/s'=1/f$ y luego $m=-s'/s$, $y'=my$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O12. Un espejo cóncavo en cuatro posiciones|resolución O12]].

### O13. Dos objetos a ambos lados del foco — R · TP 3, problema 10; prioridad didáctica alta

Un espejo cóncavo tiene radio $R=40.0\,\mathrm{cm}$ y, por tanto, foco a $20.0\,\mathrm{cm}$ del vértice. Según la geometría del TP, el objeto A está a $10.0\,\mathrm{cm}$ más lejos que el foco (a $30.0\,\mathrm{cm}$ del espejo) y el objeto B a $10.0\,\mathrm{cm}$ entre el foco y el espejo (a $10.0\,\mathrm{cm}$ del espejo).

**Se pide:** encuentra las posiciones de ambas imágenes y la distancia física entre ellas.

> [!tip]- Pista de planteo
> Resuelve cada objeto con la misma ecuación, conservando el signo de $s'$. Una imagen real queda delante del espejo; una virtual, detrás. Para hallar la distancia entre puntos a lados opuestos, suma las distancias al vértice.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O13. Dos objetos a ambos lados del foco|resolución O13]].

### O14. Imagen en un espejo convexo — R · TP 3, problema 11; prioridad didáctica alta

Un objeto de altura $y=6.00\,\mathrm{cm}$ está a $s=30.0\,\mathrm{cm}$ delante de un espejo esférico convexo de radio $R=40.0\,\mathrm{cm}$.

**Se pide**

1. Determina la distancia de imagen usando la ecuación del espejo.
2. Calcula la altura de imagen.
3. Indica si es real o virtual, derecha o invertida, mayor o menor.
4. Comprueba cualitativamente tu resultado con una construcción de rayos.

> [!tip]- Pista de planteo
> Un espejo convexo tiene foco virtual: usa $f=-R/2$. Mantén el signo de la imagen al calcular el aumento; no tomes valores absolutos hasta describir la separación física.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O14. Imagen en un espejo convexo|resolución O14]].

### O15. Distancia para una imagen real de mitad de tamaño — R · TP 3, problema 12; prioridad didáctica alta

Un espejo cóncavo tiene radio de curvatura $R=260\,\mathrm{cm}$. Se quiere que la imagen sea real y tenga la mitad de la altura del objeto.

**Se pide:** determina la distancia a la que debe colocarse el objeto y la posición de la imagen.

> [!tip]- Pista de planteo
> Una imagen real formada por un espejo cóncavo es invertida. Por eso “mitad de tamaño” significa $m=-0.50$, no $+0.50$. Usa primero $m=-s'/s$ para expresar $s'$ en función de $s$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O15. Imagen real de mitad de tamaño|resolución O15]].

### Clave breve — Espejos esféricos

> [!example]- Abrir después del intento
> **O12.** $f=50\,\mathrm{cm}$. (a) $s'=77.8\,\mathrm{cm}$, $m=-0.556$, $y'=-22.2\,\mathrm{cm}$, real/invertida/menor. (b) $s'=100\,\mathrm{cm}$, $m=-1$, $y'=-40.0\,\mathrm{cm}$, real/invertida/igual. (c) $s'=133.3\,\mathrm{cm}$, $m=-1.667$, $y'=-66.7\,\mathrm{cm}$, real/invertida/mayor. (d) $s'=-75.0\,\mathrm{cm}$, $m=+2.50$, $y'=+100\,\mathrm{cm}$, virtual/derecha/mayor.
>
> **O13.** $s'_A=+60\,\mathrm{cm}$; $s'_B=-20\,\mathrm{cm}$; separación $80\,\mathrm{cm}$.
>
> **O14.** $f=-20\,\mathrm{cm}$, $s'=-12\,\mathrm{cm}$, $m=+0.400$, $y'=+2.40\,\mathrm{cm}$; virtual, derecha y menor.
>
> **O15.** $s=390\,\mathrm{cm}$; $s'=195\,\mathrm{cm}$.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Espejos esféricos|resoluciones de esta familia]] · [[#Lentes delgadas y sistemas|siguiente familia: lentes delgadas y sistemas]].

---

## Lentes delgadas y sistemas

**Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#8. Lentes delgadas: dos refracciones y una sola imagen]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica#6. Lentes delgadas]] · **Resoluciones:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Lentes delgadas y sistemas|Lentes delgadas y sistemas]].

> [!info] Clasificación
> O16 sigue siendo **C**: fabricante de lentes y cambio de medio no se identificaron como habilidad explícita de los modelos. O17–O19 son **R** de imagen y sistema de lentes; el primer parcial 2026 incluye dos convergentes. O20 reproduce la lente divergente de los primeros parciales 2023 y 2024 (**M**).

### O16. La misma lente en aire y en un medio de mayor índice — C · TP 3, problema 13; prioridad didáctica alta

Una lente delgada biconvexa de vidrio tiene $n_\ell=1.50$ y radios iguales. En aire, su distancia focal es $f=+6.00\,\mathrm{cm}$.

**Se pide**

1. Calcula el radio común de sus dos caras.
2. Luego sumérgela en un medio transparente de índice $n_m=1.80$. Calcula la nueva distancia focal y decide si la lente converge o diverge.

> [!warning] Dato del TP conservado literalmente
> El enunciado original llama “agua” al medio con $n=1.8$, valor no habitual para agua ordinaria. Aquí se conserva el dato del TP para no cambiar el resultado; en un examen usa el índice que indique el problema.

> [!tip]- Pista de planteo
> Para biconvexa simétrica, con luz de izquierda a derecha, $R_1=+R$ y $R_2=-R$. Aplica la ecuación del fabricante en aire y después con el índice relativo $n_\ell/n_m$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O16. Lente en aire y en un medio de mayor índice|resolución O16]].

### O17. Objeto e imagen real de una lente convergente — R · TP 3, problema 14; prioridad didáctica alta

Una lente convergente tiene distancia focal $f=50.0\,\mathrm{cm}$. Forma una imagen real $2.50$ veces más alta que el objeto.

**Se pide:** calcula la distancia entre el objeto y su imagen.

> [!tip]- Pista de planteo
> En una imagen real, $m=-2.50$. Usa $m=-s'/s$ para conectar las distancias y luego sustituye en $1/s+1/s'=1/f$. La separación entre objeto e imagen es $s+s'$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O17. Objeto e imagen real aumentada|resolución O17]].

### O18. Dos lentes con una imagen intermedia — R · TP 3, problema 15; prioridad didáctica alta

Un objeto de altura $y=3.00\,\mathrm{cm}$ está a $14.0\,\mathrm{cm}$ a la izquierda de la lente 1. Las dos lentes están en aire, son delgadas, tienen vidrio de índice $n_\ell=1.50$ y están separadas $18.0\,\mathrm{cm}$. La luz viaja de izquierda a derecha.

- Lente 1: menisco convergente, radios firmados $R_1=+4.00\,\mathrm{cm}$ y $R_2=+12.0\,\mathrm{cm}$.
- Lente 2: plano-convexa, radios firmados $R_1=+4.00\,\mathrm{cm}$ y $R_2=\infty$.

![[imagenes/optica-sistema-dos-lentes.svg]]

**Se pide**

1. Calcula la distancia focal de cada lente con la ecuación del fabricante.
2. Encuentra la imagen final y clasifícala.
3. Calcula el aumento total y la altura final.
4. Dibuja rayos principales y marca la imagen intermedia.

> [!tip]- Pista de planteo
> Primero determina $f_1$ y $f_2$. Resuelve la lente 1 con $s_1=14\,\mathrm{cm}$. La posición de esa imagen debe medirse desde la lente 2 para determinar $s_2$; si queda del lado de salida de la lente 2, $s_2$ es negativo.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O18. Dos lentes con imagen intermedia|resolución O18]].

### O19. Diseñar la posición del objeto para ubicar la imagen final — R · TP 3, problema 16; prioridad didáctica alta

Dos lentes convergentes se encuentran a $50.0\,\mathrm{cm}$ de distancia. La primera tiene $f_1=10.0\,\mathrm{cm}$ y la segunda $f_2=20.0\,\mathrm{cm}$. Se desea que la imagen final quede entre las lentes, a $31.0\,\mathrm{cm}$ a la derecha de la primera.

![[imagenes/optica-sistema-dos-lentes.svg]]

**Se pide**

1. Determina a qué distancia a la izquierda de la primera lente debe ponerse el objeto.
2. Calcula el aumento total e indica si la imagen final está derecha o invertida respecto del objeto.
3. Explica por qué la imagen final es virtual para la segunda lente aunque quede dentro del espacio entre lentes.

> [!tip]- Pista de planteo
> La imagen final está $50-31=19\,\mathrm{cm}$ a la izquierda de la segunda lente; por tanto $s'_2=-19\,\mathrm{cm}$. Resuelve la lente 2 hacia atrás para hallar dónde debe estar su objeto intermedio; esa posición fija $s'_1$ y permite calcular $s_1$.

**Para comparar después:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O19. Diseñar la posición del objeto|resolución O19]].

### O20. Lente divergente con imagen de dos tercios — M · primeros parciales 2023 y 2024

Una lente delgada divergente recibe rayos paralelos y los hace salir como si provinieran de un punto a $15.0\,\mathrm{cm}$ del centro de la lente. Se quiere formar una imagen virtual y derecha de $2/3$ de la altura de un objeto real.

**Se pide:** determina dónde colocar el objeto, localiza la imagen y dibuja dos rayos principales. Justifica los signos de la focal, el aumento y la distancia de imagen. Los dos últimos datos de posición y signos ayudan a justificar la construcción solicitada por el modelo.

> [!tip]- Pista de planteo
> La observación con rayos paralelos da $f=-15.0\,\mathrm{cm}$. Derecha y de dos tercios significa $m=+2/3$. Combina $s'=-ms$ con $1/s+1/s'=1/f$.

**Fuente:** [primer parcial 2023, P3](zotero://select/library/items/XB579CRN) y [primer parcial 2024, P2](zotero://select/library/items/67PJMB4S), mismo enunciado repetido.
**Resolución:** [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#O20. Lente divergente con imagen de dos tercios|O20]].

### Clave breve — Lentes delgadas y sistemas

> [!example]- Abrir después del intento
> **O20.** $f=-15.0\,\mathrm{cm}$; $s=+7.50\,\mathrm{cm}$; $s'=-5.00\,\mathrm{cm}$; $m=+2/3$, virtual, derecha y reducida.
>
> **O16.** $R=6.00\,\mathrm{cm}$; en el medio $f=-18.0\,\mathrm{cm}$, por lo tanto la lente se vuelve divergente.
>
> **O17.** $s=70.0\,\mathrm{cm}$, $s'=175\,\mathrm{cm}$; distancia objeto-imagen $245\,\mathrm{cm}$.
>
> **O18.** $f_1=12.0\,\mathrm{cm}$, $f_2=8.00\,\mathrm{cm}$; la primera imagen queda a $84.0\,\mathrm{cm}$ de L1. Para L2, $s_2=-66.0\,\mathrm{cm}$ y $s'_2=7.14\,\mathrm{cm}$. Imagen final real a $25.1\,\mathrm{cm}$ de L1; $m_\mathrm{total}=-0.649$ y $y'=-1.95\,\mathrm{cm}$: invertida y reducida.
>
> **O19.** $s_2=9.74\,\mathrm{cm}$; $s'_1=40.26\,\mathrm{cm}$; objeto a $s_1=13.31\,\mathrm{cm}$ de L1. $m_\mathrm{total}\approx-5.90$: imagen invertida y 5.90 veces más alta.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/06 - Óptica/Resoluciones/06 - Resoluciones de óptica#Lentes delgadas y sistemas|resoluciones de esta familia]].

---

**Cierre:** [[Unidades/06 - Óptica/Autoevaluación/06 - Óptica#Repaso del módulo|autoevaluación final]] · [[Unidades/06 - Óptica/Teoría/06 - Óptica|volver al módulo]].
