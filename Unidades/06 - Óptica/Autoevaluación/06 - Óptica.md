---
tags: [fisica-aplicada, autoevaluacion, optica]
---

# Autoevaluación — Óptica

**Módulo:** [[Unidades/06 - Óptica/Teoría/06 - Óptica]] · **Conceptos:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica]] · **Fórmulas:** [[Unidades/06 - Óptica/Teoría/06 - Fórmulas aplicadas de Óptica]].

Responde sin mirar las explicaciones. En las respuestas cuantitativas, di primero qué modelo eliges y por qué. Cada explicación muestra la decisión física que es fácil pasar por alto.

## Conceptos

### 1. ¿Cuándo usarías rayos y cuándo necesitarías considerar que la luz es una onda?

> [!success]- Mostrar explicación
> El modelo de rayos es útil para seguir la dirección de la luz y localizar imágenes en espejos y lentes cuando los tamaños característicos son grandes respecto de la longitud de onda. Para interferencia, difracción o separación de franjas, hay que sumar ondas y considerar sus fases. Son descripciones complementarias de la misma luz.

### 2. ¿Desde dónde se miden los ángulos en la ley de reflexión y en la ley de Snell?

> [!success]- Mostrar explicación
> Desde la normal, que es perpendicular a la superficie en el punto de incidencia. Medirlos desde la superficie produce el ángulo complementario. La fórmula solo es coherente si todos los ángulos se miden con la misma referencia.

### 3. Si la luz entra a un material con mayor índice, ¿qué ocurre con su rapidez, longitud de onda y frecuencia?

> [!success]- Mostrar explicación
> Como $n=c/v$, mayor índice significa menor rapidez. La frecuencia se conserva en una interfaz estacionaria porque la fuente mantiene la frecuencia de oscilación; entonces $\lambda=v/f$ disminuye. No cambian todas las magnitudes a la vez.

### 4. ¿Qué condición debe cumplirse para que exista un ángulo crítico?

> [!success]- Mostrar explicación
> La luz debe intentar pasar del medio de mayor índice al de menor índice: $n_1>n_2$. Al aumentar el ángulo, el rayo refractado se acerca a $90^\circ$; ese límite define $\sin\theta_c=n_2/n_1$. Para $\theta_i>\theta_c$ ocurre reflexión total.

### 5. ¿Por qué un objeto bajo el agua parece menos profundo?

> [!success]- Mostrar explicación
> Al pasar de agua a aire los rayos se alejan de la normal. El ojo los prolonga rectos hacia atrás y los atribuye a un punto más próximo a la superficie. Es una posición aparente; el objeto no se desplaza.

### 6. ¿Qué diferencia a una imagen real de una virtual?

> [!success]- Mostrar explicación
> Los rayos convergen físicamente en una imagen real, que puede proyectarse en una pantalla. En una virtual, los rayos no pasan por el punto imagen; solo sus prolongaciones parecen provenir de él. El signo de $s'$ codifica esa diferencia según la convención declarada.

### 7. ¿Qué información da el signo del aumento $m$?

> [!success]- Mostrar explicación
> Con $m=y'/y$, un aumento negativo indica imagen invertida y uno positivo, imagen derecha. El módulo indica tamaño relativo: $|m|>1$ significa ampliada; $|m|<1$, reducida.

### 8. ¿Por qué una lente biconvexa puede dejar de ser convergente al sumergirla?

> [!success]- Mostrar explicación
> La convergencia depende de la diferencia entre índice de la lente y del medio, como muestra el factor $n_\ell/n_m-1$. Si el medio supera el índice del vidrio, ese factor cambia de signo y también puede invertirse el signo de la distancia focal.

### 9. ¿Qué caracteriza a dos fuentes coherentes?

> [!success]- Mostrar explicación
> Tienen la misma frecuencia y una diferencia de fase constante en el tiempo. Para ondas luminosas transversales también se suele requerir polarización compatible. En doble rendija, una fuente común proporciona esa relación estable entre las ondas de ambas aberturas.

## Fórmulas

### 10. Un rayo pasa de $n_1=1.50$ a $n_2=1.00$. ¿Qué relación usarías y qué alerta debes revisar al despejar el ángulo transmitido?

> [!success]- Mostrar explicación
> Uso Snell: $\sin\theta_2=(n_1/n_2)\sin\theta_1$. Como el rayo va de un índice mayor a uno menor, el argumento puede superar 1 si el ángulo de entrada supera el crítico. En ese caso no hay ángulo transmitido real: se evalúa reflexión total.

### 11. Una lente convergente tiene $f=12\,\mathrm{cm}$ y un objeto real está a $s=36\,\mathrm{cm}$. ¿Qué distancia de imagen predice el modelo?

> [!success]- Mostrar explicación
> Ecuación de lente delgada: $1/s'=1/f-1/s=1/12-1/36=1/18\,\mathrm{cm^{-1}}$, así que $s'=18\,\mathrm{cm}$. Es positiva: imagen real al lado de salida. El aumento es $m=-18/36=-0.5$, invertida y reducida.

### 12. ¿Qué significa $s'=-8\,\mathrm{cm}$ para un espejo cóncavo en esta guía?

> [!success]- Mostrar explicación
> La imagen está $8\,\mathrm{cm}$ detrás del espejo y es virtual. No significa que el resultado sea un error algebraico: para un objeto entre el foco y el espejo, el cóncavo puede formar una imagen virtual derecha.

### 13. ¿Por qué no se puede usar $f=R/2$ sin revisar de qué lado está el foco?

> [!success]- Mostrar explicación
> La relación admite radios con signo. Para un espejo cóncavo el radio y el foco son positivos en la convención adoptada; para uno convexo ambos son negativos. Además, el modelo supone rayos paraxiales y superficies esféricas.

### 14. Para una doble rendija, ¿qué fórmula da la distancia entre máximos vecinos y cómo cambia al duplicar $d$?

> [!success]- Mostrar explicación
> $\beta=\lambda L/d$. Si se duplica la separación de rendijas dejando $\lambda$ y $L$ fijos, $\beta$ se reduce a la mitad. La fórmula viene de combinar la diferencia de camino $d\sin\theta=m\lambda$ con la aproximación $y/L\approx\sin\theta$.

### 15. ¿Cómo relacionas el ángulo de un corte de fibra medido desde el eje con el de incidencia medido desde la normal?

> [!success]- Mostrar explicación
> Si el eje del rayo forma $\theta$ con el plano de corte, la normal forma $90^\circ-\theta$ con el rayo; por tanto ese es el ángulo incidente. El criterio de reflexión total usa ese ángulo, no $\theta$ directamente.

### 16. En un sistema de dos lentes, ¿cómo determinas el objeto de la segunda?

> [!success]- Mostrar explicación
> Calculas la posición de la imagen de la primera lente en un eje común y la mides desde la segunda. Si queda a la derecha de la segunda mientras la luz viaja a la derecha, los rayos que llegan siguen convergiendo hacia ese punto: es objeto virtual y $s_2<0$.

## Repaso del módulo

### 17. En el modelo 2023, ¿por qué los máximos de $510\,\mathrm{nm}$ quedan más lejos del centro que los de $430\,\mathrm{nm}$?

> [!success]- Mostrar explicación
> La posición de orden $m$ es proporcional a $\lambda$: $y_m=m\lambda L/d$. Con iguales $m$, $L$ y $d$, la mayor longitud de onda produce mayor distancia al centro.

### 18. ¿Qué significa el “tercer orden” en una doble rendija?

> [!success]- Mostrar explicación
> Es $m=3$ en la condición de máximo $\Delta r=m\lambda$. No es el número de rendijas ni el número de franjas entre el máximo central y el siguiente. El índice de orden cuenta cuántas longitudes de onda de diferencia de camino corresponden al máximo.

### 19. Si la imagen intermedia de L1 queda más allá de L2, ¿por qué el objeto de L2 tiene distancia negativa?

> [!success]- Mostrar explicación
> La luz llega a L2 antes de alcanzar el punto donde convergería. Al entrar, los rayos ya se dirigen hacia un punto situado del lado de salida de L2. Ese punto es objeto virtual para L2; la distancia al objeto se asigna negativa en la convención.

### 20. ¿Qué control harías para decidir si una solución de espejo o lente tiene sentido físico?

> [!success]- Mostrar explicación
> Comprueba signos antes de describir: $s'>0$ corresponde a imagen real en el lado que indica la convención; el signo de $m$ debe concordar con la orientación. Compara además el resultado con la geometría: para un objeto real en un cóncavo o una lente convergente, situarlo entre foco y elemento da imagen virtual y derecha; situarlo en el foco produce rayos salientes paralelos y ninguna imagen a distancia finita. Esas reglas requieren el elemento y el tipo de objeto indicados.

## Comprobaciones por etapa

Usa estas preguntas al terminar las etapas de la teoría extensa. Cada respuesta debe incluir la condición que permite usar la relación y la interpretación del resultado.

### 21. ¿Puede cambiar la rapidez de la luz sin que se desvíe el rayo?

> [!success]- Mostrar explicación
> Sí. Si llega por la normal a una interfaz, Snell da $\theta_1=\theta_2=0$. Cambian $v$ y $\lambda$ cuando cambia el índice, pero no la dirección ni la frecuencia en una interfaz estacionaria. El cambio de rapidez por sí solo no garantiza desviación.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#2. Índice de refracción: por qué se desvía un rayo]].

### 22. Dos colores salen por puntos distintos de una placa paralela. ¿Deben salir en direcciones distintas? ¿Qué distancia calcula $e|\tan\theta_a-\tan\theta_b|$?

> [!success]- Mostrar explicación
> Con igual medio exterior a ambos lados, cada rayo emergente vuelve a ser paralelo al incidente. Si ambos colores llegaban en la misma dirección, también salen paralelos entre sí. La fórmula calcula la separación sobre la segunda cara de los puntos de salida, para rayos que entran por el mismo punto; no el desplazamiento perpendicular de un solo rayo respecto de su línea incidente.

### 23. Un objeto está a $3.00\,\mathrm m$ bajo agua de índice $1.33$. ¿Qué profundidad aparente estimas desde el aire y qué supuesto lo permite?

> [!success]- Mostrar explicación
> Para observación casi normal y superficie plana, $d_a\approx d_r n_{\mathrm{aire}}/n_{\mathrm{agua}}=3.00/1.33\approx2.26\,\mathrm m$. Parece estar unos $0.74\,\mathrm m$ más cerca de la superficie. La aproximación sustituye la razón de tangentes por la de senos para ángulos pequeños. El objeto sigue a $3.00\,\mathrm m$.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#4. Bloques, profundidad aparente y color]].

### 24. En un cubo, ¿aumentar el ángulo externo en la cara lateral siempre favorece la reflexión total en la cara superior?

> [!success]- Mostrar explicación
> No. En la geometría plana de O10, aumentar el ángulo externo aumenta el ángulo interno $\theta_t$ respecto de la normal lateral. La incidencia en la cara superior es su complementario, $90^\circ-\theta_t$, y disminuye. La reflexión total se decide con este último ángulo y con los índices a ambos lados de esa cara. Por eso hay que dibujar una normal para cada interfaz.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#5. Reflexión total interna: cuándo la luz queda atrapada]].

### 25. Si una imagen es virtual, ¿cómo puede verse? ¿Una pantalla colocada en su posición la captaría enfocada?

> [!success]- Mostrar explicación
> Se ve porque el ojo recibe rayos que divergen como si provinieran de esa posición y sus propias lentes los enfocan en la retina. Los rayos del elemento que forma la imagen virtual no se cruzan en el punto virtual; una pantalla puesta allí no recoge esa imagen enfocada. El criterio real/virtual se refiere al encuentro de los rayos salientes, no a la posibilidad de verla.

### 26. Un espejo se desplaza $5\,\mathrm{cm}$ y el objeto queda fijo. ¿Cuánto se mueve la imagen respecto de la habitación y cuánto cambia su distancia al espejo?

> [!success]- Mostrar explicación
> Para movimiento perpendicular al espejo, $\Delta x_i=2\Delta x_m=10\,\mathrm{cm}$ en el eje de la habitación. La distancia imagen-espejo cambia solo $5\,\mathrm{cm}$, aumentando si el espejo se aleja del objeto y disminuyendo si se acerca. Son referencias distintas. Si se moviese también el objeto, habría que usar $\Delta x_i=2\Delta x_m-\Delta x_o$.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#6. Reflexión, imágenes planas y camino de la luz]].

### 27. ¿La imagen de un objeto en un espejo cóncavo queda siempre en su foco? ¿Se puede usar $f=R/2$ para una lente?

> [!success]- Mostrar explicación
> El foco describe la convergencia de rayos incidentes paralelos al eje, como los de un punto objeto muy lejano. Para un objeto a distancia finita hay que usar $1/s+1/s'=1/f$. La relación $f=R/2$ corresponde al espejo esférico paraxial; una lente tiene dos caras refractoras y su focal depende también de los índices, por lo que requiere el fabricante de lentes o una focal dada.

### 28. Para un espejo cóncavo con objeto real, ¿por qué “imagen real de mitad de altura” se traduce como $m=-0.50$?

> [!success]- Mostrar explicación
> “Mitad” fija el módulo $|m|=0.50$. La imagen real de un objeto real en ese espejo es invertida, así que el signo es negativo. Como $m=-s'/s$, resulta $s'=0.50s$. Al sustituir en la ecuación de imagen, $1/s+2/s=1/f$, se obtiene $s=3f$ y $s'=1.5f$. La orientación, el tamaño y el carácter real son datos diferentes que deben ser compatibles.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#7. Espejos esféricos: de la geometría al foco]].

### 29. ¿Por qué una biconvexa simétrica tiene radios de signos opuestos? ¿Qué ocurre si lente y medio tienen igual índice?

> [!success]- Mostrar explicación
> Con luz hacia la derecha, el centro de curvatura de la primera cara queda a su derecha y el de la segunda a su izquierda: $R_1=+R$, $R_2=-R$. Si $n_\ell=n_m$, el factor $n_\ell/n_m-1$ se anula: $1/f=0$, sin potencia de enfoque en el modelo. Eso no significa $f=0$; significa focal infinita, porque las interfaces no tienen contraste de índice.

### 30. L1 está en $x=0$ y L2 en $x=20\,\mathrm{cm}$. La imagen de L1 sola estaría en $x=50\,\mathrm{cm}$. ¿Qué objeto recibe L2 y qué significa físicamente?

> [!success]- Mostrar explicación
> $s_2=20-50=-30\,\mathrm{cm}$: objeto virtual para L2. Los rayos llegan a ella convergiendo hacia un punto que aún está $30\,\mathrm{cm}$ más adelante. L2 modifica el haz antes de ese cruce; no hace falta un objeto material en ese punto ni llega a formarse allí la imagen de L1 sola. La posición final se obtiene con $x_f=20\,\mathrm{cm}+s'_2$, no confundiendo $s'_2$ con una coordenada global.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#8. Lentes delgadas: dos refracciones y una sola imagen]].

### 31. ¿Dos fuentes coherentes tienen que estar en fase? ¿Cuándo usamos directamente $d\sin\theta=m\lambda$?

> [!success]- Mostrar explicación
> Coherentes significa misma frecuencia y fase relativa estable; esa fase puede ser distinta de cero. Las posiciones habituales de máximos suponen además fuentes en fase, propagación en el mismo medio y pantalla lejana; para luz se necesita polarización compatible. Un desfase inicial distinto de cero desplaza las condiciones de máximo. La cancelación total en un mínimo requiere además amplitudes iguales.

### 32. ¿Qué diferencia hay entre pantalla lejana y ángulo pequeño en doble rendija?

> [!success]- Mostrar explicación
> $L\gg d$ permite aproximar los dos recorridos por direcciones casi paralelas y usar $\Delta r\approx d\sin\theta$. La condición adicional $|y|\ll L$ permite $\sin\theta\approx\tan\theta=y/L$, y con ella $y_m\approx m\lambda L/d$. A ángulos mayores todavía puede valer la primera aproximación: se usa $y_m\approx L\tan[\arcsin(m\lambda/d)]$. Ninguna de esas expresiones sustituye la geometría exacta de campo cercano.

### 33. Si el espaciado vecino es $\beta=2\,\mathrm{mm}$, ¿dónde queda el máximo de tercer orden? ¿Y cómo compararías dos colores?

> [!success]- Mostrar explicación
> Cerca del centro, el máximo de tercer orden queda en $y_{+3}=3\beta=6\,\mathrm{mm}$ o en $y_{-3}=-6\,\mathrm{mm}$ según el lado. El espaciado vecino sigue siendo $2\,\mathrm{mm}$. Para dos colores del mismo orden y lado, resto sus posiciones: $\Delta y_m\approx |m|L|\lambda_b-\lambda_a|/d$. Para coincidencia de órdenes distintos igualo posiciones: $m_a\lambda_a=m_b\lambda_b$, descartando los órdenes cero si se pide una coincidencia fuera del centro.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#9. Doble rendija: de la superposición a las franjas]].

## Lectura de figuras y ejemplos de las fuentes

Estas preguntas comprueban la interpretación de los nuevos recortes y ejemplos. Intenta reconstruir el dibujo y justificar la primera relación sin mirar la teoría; después abre la explicación.

### 34. En la figura de frentes de onda, ¿las curvas azules son trayectorias curvas de la luz? ¿Qué indican las flechas violetas?

> [!success]- Mostrar explicación
> Las curvas reúnen puntos en una misma fase y representan frentes de onda. Las flechas son rayos: indican la dirección de propagación y son perpendiculares a los frentes en los medios homogéneos e isótropos del modelo. Un frente esférico puede avanzar con rayos rectos que se separan radialmente. La oscilación del campo, el frente y la trayectoria del rayo son ideas diferentes.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Leer la figura del libro: frentes y rayos]].

### 35. Un objeto está a 20 cm a la izquierda de una lente convergente. La diapositiva usa una coordenada negativa y el vault una distancia positiva. ¿Son situaciones físicas distintas?

> [!success]- Mostrar explicación
> Es la misma posición descrita con dos definiciones. Con un eje positivo a la derecha y origen en la lente, la coordenada relativa del objeto es $-20\,\mathrm{cm}$. En la convención de objeto real positivo del vault, se usa $s=+20\,\mathrm{cm}$. Si la focal es $f=+10\,\mathrm{cm}$, $s'=fs/(s-f)=+20\,\mathrm{cm}$ y $m=-s'/s=-1$: imagen real al otro lado e invertida. Sustituir la coordenada $-20$ en esa misma ecuación sin traducirla mezclaría convenciones. Se elige una convención con sus ecuaciones, sin cambiar solo un signo aislado.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Leer los casos de la diapositiva: mover el objeto respecto del foco]].

### 36. El láser tiene 633 nm en aire y 474 nm en el líquido del ojo. ¿Por qué no se calcula su frecuencia como c dividido por 474 nm?

> [!success]- Mostrar explicación
> Porque $474\,\mathrm{nm}$ es la longitud de onda en el líquido, cuya rapidez es $v=c/n<c$. Hay que usar $f=v/\lambda_{\mathrm{líquido}}$ o, aproximando el aire como vacío, $f\approx c/\lambda_{\mathrm{aire}}\approx4.74\times10^{14}\,\mathrm{Hz}$. El índice es $n\approx633/474\approx1.34$ y la rapidez, $v\approx2.25\times10^8\,\mathrm{m/s}$. Los dos pares de rapidez y longitud de onda dan la misma frecuencia si conservas la precisión intermedia, porque el paso por la interfaz estacionaria no cambia el ritmo de oscilación.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Ejemplo del libro: el mismo láser en aire y en el ojo]]. Después intenta O21.

### 37. Si cubres la mitad de un espejo que proyecta una imagen, ¿desaparece necesariamente la mitad de esa imagen?

> [!success]- Mostrar explicación
> No. En el modelo geométrico ideal, la parte descubierta puede seguir recibiendo rayos de todos los puntos del objeto y formando sus puntos imagen. La imagen completa puede mantenerse con menos brillo. Los dos o tres rayos principales son una selección útil para dibujar, no los únicos rayos físicos. Esta afirmación supone que la parte libre permite esos recorridos; un obstáculo que bloquee por completo el haz de un punto concreto sí puede impedir ver ese punto. No se identifica automáticamente una mitad del espejo con una mitad del objeto.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Qué significa formar una imagen]], con la observación del ejemplo conceptual 34.2.

### 38. La tercera franja está a 9.49 mm del centro, con d = 0.200 mm y L = 1.00 m. ¿Qué distancia es el espaciado vecino y cómo obtienes la longitud de onda?

> [!success]- Mostrar explicación
> En el modelo de pantalla lejana y ángulo pequeño, $y_3=3\beta$, así que $\beta=9.49/3\approx3.16\,\mathrm{mm}$. La tercera franja corresponde a $m=3$ y $\lambda\approx y_3d/(3L)$. Al convertir ambos milímetros a metros, $\lambda\approx(9.49\times10^{-3})(0.200\times10^{-3})/[3(1.00)]\,\mathrm m\approx6.33\times10^{-7}\,\mathrm m=633\,\mathrm{nm}$. No se usa $9.49\,\mathrm{mm}$ como distancia entre dos franjas vecinas. Las condiciones se comprueban con $d/L\ll1$ y $y_3/L\ll1$.

**Volver a leer:** [[Unidades/06 - Óptica/Teoría/06 - Conceptos de Óptica#Ejemplo del libro: obtener la longitud de onda a partir de una franja]]. Después intenta O2.

## Pasa a la práctica

- Doble rendija: [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Interferencia de doble rendija|Interferencia de doble rendija]]
- Refracción y reflexión total: [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Refracción y reflexión total|Refracción y reflexión total]]
- Reflexión y espejos planos: [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Reflexión y espejos planos|Reflexión y espejos planos]]
- Espejos esféricos: [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Espejos esféricos|Espejos esféricos]]
- Lentes delgadas y sistemas: [[Unidades/06 - Óptica/Práctica/06 - Ejercicios de óptica#Lentes delgadas y sistemas|Lentes delgadas y sistemas]]
