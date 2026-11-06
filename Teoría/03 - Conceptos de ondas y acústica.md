---
tags: [fisica-aplicada, teoria, conceptos, ondas-acustica]
---

# Conceptos — Ondas mecánicas y acústica

**Volver al módulo:** [[Teoría/03 - Ondas y acústica]] · **Relaciones y derivaciones:** [[Teoría/03 - Fórmulas aplicadas de ondas y acústica]] · **Práctica:** [[Ejercicios/03 - Ondas y acústica]]

> [!abstract] La idea que organiza el tema
> Una onda mecánica es una perturbación que se transmite de una parte del medio a la siguiente. **Avanza el patrón; los puntos del medio se mueven localmente y, si la fuente repite su movimiento, oscilan cerca de su equilibrio.** Esa transmisión requiere materia y transporta energía, aunque no lleve las mismas partículas desde la fuente hasta el receptor.

## 1. Antes de las fórmulas: qué avanza y qué oscila

Imagina una fila de personas que se pasan un empujón: el gesto avanza por la fila, pero cada persona solo se mueve un poco y vuelve a su lugar. En una cuerda, cada tramo tira del siguiente. En el aire, las moléculas empujan a sus vecinas y forman **compresiones** —partículas más juntas— y **rarefacciones** —partículas más separadas—.

![[imagenes/parametros-onda-mecanica.svg]]

La parte superior del dibujo es una **onda transversal**: cada punto de la cuerda oscila arriba y abajo mientras el patrón avanza horizontalmente. La parte inferior representa el **sonido longitudinal**: las partículas oscilan en la misma dirección en que avanza la perturbación. El sonido en aire, agua y otros fluidos es longitudinal.

> [!important] No confundas estos dos movimientos
> - **Rapidez de la onda $v$:** cuánto avanza el patrón por segundo.
> - **Velocidad de una partícula $u$:** cómo se mueve una partícula concreta del medio en ese instante.
>
> La onda puede avanzar hacia la derecha aunque una partícula esté moviéndose hacia la izquierda. La curva dibujada es una instantánea de una magnitud frente a la posición; no es el camino que recorre una partícula.

## 2. Los parámetros de una onda, uno por uno

Una fuente que repite su movimiento produce una perturbación periódica. Cada símbolo responde una pregunta distinta:

| Parámetro | Qué significa en palabras | Cómo reconocerlo o medirlo |
|---|---|---|
| **Amplitud $A$** | Máxima separación respecto del equilibrio. Indica cuán grande es la oscilación. | Desde la línea de equilibrio hasta un máximo. Debe aclararse de qué magnitud: desplazamiento $s_{\max}$ o presión $\Delta p_{\max}$. |
| **Longitud de onda $\lambda$** | Distancia que ocupa una repetición completa del patrón. | Cresta a cresta, valle a valle o compresión a compresión. Se mide en metros. |
| **Período $T$** | Tiempo que tarda una partícula en completar una oscilación. | Tiempo entre dos máximos sucesivos en el mismo punto. Se mide en segundos. |
| **Frecuencia $f$** | Cuántas oscilaciones completas ocurren por segundo. | Es el inverso del período: $f=1/T$. Se mide en hertz ($1\,\mathrm{Hz}=1\,\mathrm{s^{-1}}$). |
| **Rapidez de propagación $v$** | Cuánto avanza una misma fase del patrón por segundo. | Distancia recorrida por la onda dividida por el tiempo. En el sonido depende de las propiedades del medio. |
| **Desplazamiento $s$** | Posición instantánea de una partícula respecto de su equilibrio. | Puede ser positivo, negativo o cero; $s_{\max}$ es su amplitud. No es la distancia que viajó la onda. |
| **Variación de presión $\Delta p$** | Cuánto sube o baja la presión del aire respecto de su valor de equilibrio. | En sonido, presión positiva indica compresión y presión negativa indica rarefacción. No es la presión atmosférica total. |

> [!note] ¿Qué determina cada parámetro?
> La **fuente** marca el ritmo: fija $f$ y $T$. El **medio** determina qué tan rápido viaja la perturbación, es decir, $v$. La combinación de ese ritmo con esa rapidez fija cuánto espacio avanza cada ciclo: $\lambda=v/f$. La amplitud inicial depende de cuánto se mueve la fuente; al propagarse, puede disminuir por pérdidas o porque la energía se reparte en una región mayor.

### Componentes de la onda en dos gráficos

![[imagenes/componentes-onda-grafica.svg]]

En el gráfico superior se mira **toda la forma de onda en un instante**: allí se mide $\lambda$. En el inferior se sigue **un punto del medio a medida que pasa el tiempo**: allí se mide $T$, y de él se obtiene $f=1/T$. La altura desde el equilibrio es la amplitud en ambos gráficos.

### La relación central: una longitud de onda por período

Observa un punto fijo de la cuerda o del aire. Cuando ese punto completa un ciclo, transcurre un período $T$. Durante ese mismo tiempo, el patrón que pasa por allí avanza una repetición completa, es decir, una longitud de onda $\lambda$. Por definición de rapidez:

$$
v=\frac{\text{distancia recorrida por el patrón}}{\text{tiempo}}
=\frac{\lambda}{T}.
$$

Como $f=1/T$, también se escribe:

$$
\boxed{v=\frac{\lambda}{T}=\lambda f},\qquad
\boxed{T=\frac1f},\qquad
\boxed{\lambda=\frac{v}{f}}.
$$

Esta es la relación más usada para interpretar ejercicios. Si la onda pasa a otro medio, normalmente **la fuente conserva la frecuencia**, pero el medio cambia $v$; por eso se ajusta $\lambda=v/f$.

### ¿De dónde salen $k$ y $\omega$?

La función sinusoidal es una manera compacta de decir qué desplazamiento tiene cada punto en cada instante. En esta función, $A$ es la amplitud de desplazamiento, es decir, $A=s_{\max}$:

$$
s(x,t)=A\cos(kx-\omega t+\phi_0).
$$

No agrega un movimiento nuevo: registra el patrón repetitivo que ya describimos. Cada parte del argumento del coseno se interpreta así:

- **$kx$** cuenta el cambio de fase al cambiar de posición. Una separación $\lambda$ completa una repetición, equivalente a un giro de fase de $2\pi$; por eso $k\lambda=2\pi$ y $\boxed{k=2\pi/\lambda}$.
- **$\omega t$** cuenta el cambio de fase con el tiempo. Un ciclo dura $T$ y también equivale a $2\pi$; por eso $\omega T=2\pi$ y $\boxed{\omega=2\pi/T=2\pi f}$.
- **$\phi_0$** indica en qué estado empieza la oscilación cuando $x=0$ y $t=0$.
- **El signo entre los términos** indica la dirección. Si seguimos una cresta, su fase conserva el mismo valor. En $kx-\omega t=\text{constante}$, al aumentar $t$ también debe aumentar $x$: la onda va hacia $+x$. Con $kx+\omega t$, $x$ debe disminuir y la onda va hacia $-x$.

En una onda sinusoidal, la partícula oscila localmente. Su velocidad es la variación temporal del desplazamiento. Al derivar $s(x,t)$ respecto del tiempo, aparece el factor $\omega$:

$$
u(x,t)=\frac{\partial s}{\partial t}
=\omega A\sin(kx-\omega t+\phi_0),
\qquad u_{\max}=\omega A.
$$

Esta rapidez máxima pertenece a las **partículas** y no reemplaza a $v=\lambda f$, que describe el avance del **patrón**.

> [!tip] Cómo leer un gráfico
> - Si el eje horizontal es $x$ y el tiempo está fijo, la distancia entre repeticiones es $\lambda$.
> - Si el eje horizontal es $t$ y miras un punto fijo, el tiempo entre repeticiones es $T$.
> - La altura desde el equilibrio es una amplitud, pero identifica primero si el gráfico muestra desplazamiento, presión u otra magnitud.

### Cómo llevar estos parámetros a un ejercicio

1. **Traduce lo pedido.** “Distancia entre compresiones” pide $\lambda$; “oscilaciones por segundo” pide $f$; “máximo desplazamiento de las partículas” pide $s_{\max}$.
2. **Separa los datos por tipo.** Anota si son del patrón ($v,\lambda,f,T$), del movimiento local ($s,u$) o del sonido ($\Delta p,B,\rho$).
3. **Elige la conexión física.** Para $v,\lambda,f,T$, usa $v=\lambda f$ y $T=1/f$. Para presión y desplazamiento en sonido sinusoidal, usa $\Delta p_{\max}=Bk s_{\max}$, con $k=2\pi f/v$.
4. **Despeja antes de sustituir.** Así se ve qué dato falta y reduces errores algebraicos.
5. **Comprueba unidades y sentido.** $\lambda$ debe quedar en metros; $T$, en segundos; $f$, en hertz. Si $v$ no cambia y aumenta $f$, entonces $\lambda$ debe disminuir.

### Ejemplo breve: de la frecuencia a la longitud de onda y al desplazamiento

Una onda sonora en aire tiene $f=1000\,\mathrm{Hz}$, $v=344\,\mathrm{m/s}$, amplitud de presión $\Delta p_{\max}=3.0\times10^{-2}\,\mathrm{Pa}$ y módulo volumétrico $B=1.42\times10^5\,\mathrm{Pa}$. ¿Qué valores tienen $T$, $\lambda$, $k$ y $s_{\max}$?

**1. Período.** La frecuencia indica cuántas veces se repite el ciclo cada segundo:

$$
T=\frac1f=\frac1{1000\,\mathrm{s^{-1}}}=1.00\times10^{-3}\,\mathrm{s}.
$$

**2. Longitud de onda.** En ese milisegundo el patrón avanza una longitud de onda:

$$
\lambda=\frac{v}{f}=\frac{344\,\mathrm{m/s}}{1000\,\mathrm{s^{-1}}}=0.344\,\mathrm{m}.
$$

**3. Cambio espacial de fase.** Una longitud de onda equivale a $2\pi$ radianes:

$$
k=\frac{2\pi}{\lambda}=\frac{2\pi}{0.344\,\mathrm m}=18.3\,\mathrm{rad/m}.
$$

**4. Desplazamiento máximo de las partículas.** En sonido, la presión responde a cuánto se comprime o expande el aire. Para una onda sinusoidal $\Delta p_{\max}=Bk s_{\max}$; despejamos:

$$
s_{\max}=\frac{\Delta p_{\max}}{Bk}
=\frac{3.0\times10^{-2}\,\mathrm{Pa}}
{(1.42\times10^5\,\mathrm{Pa})(18.3\,\mathrm{m^{-1}})}
\approx1.16\times10^{-8}\,\mathrm m.
$$

**Interpretación.** El sonido repite su patrón cada $0.344\,\mathrm m$, pero cada partícula de aire solo se desplaza unos $11.6\,\mathrm{nm}$ desde el equilibrio. La distancia recorrida por la onda y el desplazamiento local de las partículas son cosas distintas. Este es el planteo del [[Ejercicios/03 - Ondas y acústica#14. Desplazamiento de partículas a partir de presión — M|ejercicio 14]] y su solución paso a paso está en [[Resoluciones/03 - Ondas y acústica#14. Desplazamiento de partículas a partir de presión|la resolución]].

> [!tip] Comprobación de fase
> En un instante fijo, dos puntos con la misma fase están separados por $\lambda$. En una posición fija, el patrón vuelve a la misma fase después de un tiempo $T$.

## 3. Por qué el medio determina la rapidez

Para que una perturbación se propague, cada parte del medio debe ejercer una fuerza restauradora sobre las partes vecinas. La rapidez resulta de un balance entre **rigidez** —qué tan eficazmente se transmite la deformación— e **inercia** —cuánta materia hay que acelerar—. Por eso los parámetros del material determinan $v$.

Para una onda longitudinal en un fluido:

$$
v=\sqrt{\frac{B}{\rho}},
$$

donde $B$ es el módulo volumétrico y $\rho$ la densidad. Un módulo $B$ grande significa que cuesta comprimir el medio; una densidad grande significa más inercia por unidad de volumen.

La relación $v=\sqrt{B/\rho}$ sale de aplicar la segunda ley de Newton a un pequeño elemento de fluido. La diferencia de presión entre sus extremos es la fuerza neta; al combinar esa fuerza con la masa $\rho A\,\Delta x$ del elemento y con $\Delta p\approx-B\,\partial s/\partial x$, se obtiene:

$$
\rho\frac{\partial^2 s}{\partial t^2}
=B\frac{\partial^2 s}{\partial x^2}.
$$

Esta es la ecuación de onda estándar, cuya forma es $\partial^2s/\partial t^2=v^2\,\partial^2s/\partial x^2$. Comparar los coeficientes da $v^2=B/\rho$. Así aparece la raíz: la rigidez del medio compite con su inercia.

En un gas ideal, el sonido comprime y expande el gas con rapidez. Hay poco tiempo para intercambiar calor durante cada ciclo, así que el modelo usa compresiones aproximadamente adiabáticas. Para un cambio adiabático pequeño, $pV^\gamma=\text{constante}$ implica $B=\gamma p$, donde $p$ es la presión de equilibrio. Esto incorpora la razón de calores específicos $\gamma=C_p/C_v$:

$$
v=\sqrt{\frac{\gamma p}{\rho}}
=\sqrt{\frac{\gamma R T}{M}}.
$$

La segunda forma usa la ecuación de estado del gas ideal. $T$ debe estar en kelvin y $M$ en $\mathrm{kg/mol}$. En una varilla delgada, la deformación longitudinal se describe con el módulo de Young $Y$:

$$
v\approx\sqrt{\frac{Y}{\rho}}.
$$

Aquí $Y$ relaciona esfuerzo longitudinal con deformación; al combinar su respuesta elástica con la inercia por volumen de la varilla se obtiene la rapidez de una onda longitudinal. Estas expresiones son modelos para medios y geometrías concretos; no se intercambian sin mirar qué material describe el problema. Si el enunciado ya proporciona la rapidez, se usa ese valor.

### Frecuencia y longitud de onda al cambiar de medio

La frecuencia la fija la fuente. Cuando la onda pasa a otro medio, la perturbación en la frontera debe oscilar al ritmo de la fuente, por lo que la frecuencia se mantiene. Como la rapidez nueva depende del nuevo medio, cambia la longitud de onda:

$$
\lambda=\frac{v}{f}.
$$

Por eso el sonido puede tener una longitud de onda diferente en el aire y en el fluido del oído aunque ambos vibren con la misma frecuencia. En el sonar, la frecuencia emitida se combina con la rapidez del sonido en agua para obtener la longitud de onda submarina.

![[imagenes/sonar-en-agua-tp-2021.png]]

*Esquema de un sonar: el pulso viaja por el agua, se refleja en un objeto y vuelve al detector. Imagen recortada de la práctica de sonido, ejercicio 3, p. 1.*

## 4. Presión y desplazamiento en el sonido

La presión acústica $\Delta p$ es la diferencia entre la presión local y la presión de equilibrio. Si el aire está a presión atmosférica y la onda produce una variación pequeña, el dato acústico es esa variación, no la presión atmosférica completa.

Sea $s(x,t)$ el desplazamiento longitudinal de las partículas. Si las partículas vecinas se desplazan casi igual, el aire apenas se deforma. Si una partícula se desplaza más que la de al lado, cambia la separación entre ellas y aparece compresión o rarefacción. Para deformaciones pequeñas, la deformación relativa local es aproximadamente:

$$
\frac{\Delta V}{V}\approx\frac{\partial s}{\partial x}.
$$

El módulo volumétrico mide la resistencia del material a una compresión:

$$
B=-\frac{\Delta p}{\Delta V/V}.
$$

El signo menos refleja que comprimir —disminuir el volumen— aumenta la presión. Al combinar las dos ideas:

$$
\Delta p\approx-B\frac{\partial s}{\partial x}.
$$

La presión no depende del desplazamiento de una partícula por sí sola, sino de cómo cambia ese desplazamiento de una partícula a la siguiente. Por eso desplazamiento y presión no alcanzan sus máximos en el mismo lugar. Para una onda sinusoidal, sus perfiles están desplazados un cuarto de longitud de onda ($\lambda/4$), que equivale a un cuarto de ciclo.

![[imagenes/onda-desplazamiento-presion-fase.svg]]

En la figura, $s(x)$ y $\Delta p(x)$ se representan frente a la posición en un instante. La curva dibujada no es el camino de las partículas. Una presión positiva máxima marca una compresión máxima: las partículas cercanas tienden a converger; una presión negativa extrema marca una rarefacción.

Al comparar amplitudes se obtiene:

$$
\Delta p_{\max}=Bk\,s_{\max}.
$$

Además, para el sonido $B=\rho v^2$ y $\omega=vk$. La misma relación puede escribirse como:

$$
\Delta p_{\max}=\rho v\omega s_{\max}
=\rho v\,u_{\max}.
$$

Estas formas sirven para convertir una amplitud de presión en desplazamiento. En cada ejercicio verifica si te dieron amplitud máxima o presión eficaz, y qué propiedades del medio conoces.

### Qué cambia al llegar al oído

La onda de presión hace oscilar el tímpano; los huesecillos transmiten la vibración al fluido del oído interno. La frecuencia de la señal se conserva en la transmisión, mientras que la amplitud puede cambiar. En el modelo simplificado de la práctica, los huesecillos concentran la fuerza sobre un área menor: como $p=F/A$, una misma fuerza sobre menor área produce mayor presión. Después se vuelve a usar la relación presión-desplazamiento, ahora con la rapidez y las propiedades del fluido interno. Esta interpretación usa las suposiciones geométricas dadas por el ejercicio; no pretende describir toda la biomecánica del oído.

## 5. La onda lleva energía: intensidad acústica

La **intensidad** $I$ mide la potencia media que cruza una superficie por unidad de área perpendicular a la propagación:

$$
I=\frac{\text{potencia media}}{\text{área}},
\qquad [I]=\mathrm{W/m^2}.
$$

En una onda sonora progresiva, el aire se mueve un poco mientras la presión local cambia. La energía que cruza una superficie depende de ambos cambios: una presión acústica que empuja una partícula que se mueve realiza trabajo. Para una onda sinusoidal progresiva, presión y velocidad local de las partículas están en fase; la intensidad media se obtiene promediando el producto $\Delta p\,u$ durante un ciclo.

El promedio de una sinusoide al cuadrado es la mitad de su amplitud al cuadrado. Con $u_{\max}=\omega s_{\max}$ y $\Delta p_{\max}=\rho v u_{\max}$ resulta:

$$
I=\frac{1}{2}\Delta p_{\max}u_{\max}
=\frac{(\Delta p_{\max})^2}{2\rho v}
=\frac{1}{2}\rho v\,u_{\max}^2.
$$

Esto explica por qué, en el mismo medio, duplicar la amplitud de presión cuadruplica la intensidad: la intensidad depende del cuadrado de la amplitud.

Si el dato es presión eficaz (RMS), $p_{\mathrm{rms}}=\Delta p_{\max}/\sqrt{2}$, entonces:

$$
I=\frac{p_{\mathrm{rms}}^2}{\rho v}.
$$

Las dos expresiones son equivalentes; la diferencia aparece porque una usa amplitud máxima y la otra valor eficaz.

## 6. Potencia, distancia y reparto de energía

Una fuente puntual ideal que emite por igual en todas direcciones reparte la misma potencia acústica $P_{\mathrm{ac}}$ sobre una superficie esférica. A distancia $r$, el área de esa esfera es $4\pi r^2$, por lo que:

$$
I(r)=\frac{P_{\mathrm{ac}}}{4\pi r^2}.
$$

Al alejarse al doble de distancia, la misma potencia se reparte sobre cuatro veces el área y la intensidad cae a la cuarta parte. Este resultado supone una fuente puntual, emisión isotrópica y pérdidas por absorción u obstáculos despreciables.

La conexión con decibeles es útil: dividir la intensidad por cuatro reduce el nivel en $10\log_{10}4\approx6.02\,\mathrm{dB}$. No significa que la fuente haya reducido su potencia; se reparte sobre una superficie mayor.

## 7. Decibeles: expresar razones de intensidad

El oído responde a intensidades que abarcan muchos órdenes de magnitud. La escala de nivel sonoro comprime ese rango mediante un logaritmo:

$$
\beta=10\log_{10}\left(\frac{I}{I_0}\right),
\qquad I_0=10^{-12}\,\mathrm{W/m^2}.
$$

$I_0$ es una intensidad de referencia cercana al umbral de audición alrededor de $1000\,\mathrm{Hz}$. El logaritmo recibe una razón sin unidades. El nivel $\beta$ se expresa en decibeles (dB); no es una intensidad lineal.

- Si la intensidad se multiplica por $10$, el nivel sube $10\,\mathrm{dB}$.
- Si se duplica, sube $10\log_{10}2\approx3.01\,\mathrm{dB}$.
- Si se divide por $4$, baja $10\log_{10}4\approx6.02\,\mathrm{dB}$.

Para recuperar la intensidad desde un nivel:

$$
I=I_0\,10^{\beta/10}.
$$

### Varias fuentes: cuándo sumar intensidades

Si las fuentes son independientes o no mantienen una diferencia de fase estable, sus intensidades medias se suman. Después se convierte la intensidad total a dB:

$$
I_{\mathrm{tot}}=\sum_i I_i,\qquad
\beta_{\mathrm{tot}}=10\log_{10}\left(\frac{I_{\mathrm{tot}}}{I_0}\right).
$$

No se suman directamente los números de decibeles. En cambio, si las fuentes son coherentes —como dos parlantes conectados al mismo generador y en fase—, las presiones se superponen punto a punto y el resultado depende de la diferencia de camino. Ese caso se analiza con interferencia.

## 8. Superposición e interferencia

Cuando dos ondas pasan por el mismo lugar, el desplazamiento o la presión resultante es la suma de las contribuciones instantáneas. Esto se llama **principio de superposición**. Al sumar ondas sinusoidales, la diferencia de fase determina si se refuerzan o se cancelan.

Para dos fuentes coherentes que emiten en fase, una diferencia de camino

$$
\Delta r=|r_A-r_B|
$$

produce:

- **Interferencia constructiva** cuando $\Delta r=m\lambda$, con $m=0,1,2,\ldots$: las ondas llegan en fase.
- **Interferencia destructiva** cuando $\Delta r=(m+\tfrac12)\lambda$: una llega aproximadamente en oposición de fase a la otra.

Como $\lambda=v/f$, también se pueden encontrar las frecuencias que satisfacen cada condición. Primero se calcula la diferencia de camino con la geometría del dibujo; luego se iguala a los múltiplos de media o una longitud de onda que corresponden.

![[imagenes/interferencia-altavoces-tp-2021.png]]

*Dos parlantes alimentados por la misma fuente y un punto de observación. El esquema del ejercicio 12 de la práctica de sonido (p. 2) permite obtener la diferencia de caminos.*

### Sonido reflejado por una pared rígida

Una onda que llega a una pared se refleja y se superpone con la onda incidente. En el modelo ideal de pared rígida, la presión acústica reflejada llega en fase con la presión incidente en la superficie: allí hay un máximo de presión. Al separarse de la pared, hay puntos donde la suma de ambas presiones se anula. Los nodos de presión más cercanos quedan a:

$$
x=\frac{\lambda}{4},\ \frac{3\lambda}{4},\ \frac{5\lambda}{4},\ldots
$$

medidos perpendicularmente desde la pared. En esos puntos ideales la presión acústica resultante es cero. Es el modelo detrás de una pregunta sobre lugares donde no se escucha el sonido reflejado; en un recinto real, absorción, geometría y otras reflexiones impiden un silencio perfecto.

## 9. Doppler empieza por los frentes de onda

El efecto Doppler acústico es el cambio de frecuencia recibida cuando fuente u observador se mueven respecto del aire. El aire importa porque es el medio de propagación y fija el marco desde el que se mide la rapidez $v$ del sonido.

### Una fuente en movimiento cambia el espaciamiento

Una fuente quieta emite frentes separados por $\lambda=v/f_s$. Si se mueve hacia el observador, al emitir el siguiente ciclo ya avanzó hacia él. Durante un período $T_s=1/f_s$, el frente delantero avanza $vT_s$ y la fuente avanza $v_sT_s$. La separación delante queda:

$$
\lambda_{\mathrm{delante}}=(v-v_s)T_s
=\frac{v-v_s}{f_s}.
$$

Detrás de la fuente, el movimiento agrega separación:

$$
\lambda_{\mathrm{detrás}}=\frac{v+v_s}{f_s}.
$$

La rapidez de la onda sigue siendo la que determina el aire. Por eso una fuente móvil genera distinta longitud de onda delante y detrás. Un observador quieto recibe $f=v/\lambda$: frecuencia mayor delante de la fuente que se acerca y menor detrás de la fuente que se aleja.

### Un observador en movimiento cambia el ritmo de encuentro

Si la fuente está quieta, la longitud de onda ya está fijada en el aire. Un observador que se mueve hacia la fuente encuentra más frentes por segundo; uno que se aleja se encuentra con menos. La longitud de onda no cambia por mover al observador.

### Fórmula general y convención de signos

Combinando ambos efectos:

$$
f_{\mathrm{obs}}=f_s\frac{v+v_o}{v-v_s}.
$$

En esta guía:

- $v_o>0$ cuando el observador se mueve hacia la fuente y $v_o<0$ cuando se aleja.
- $v_s>0$ cuando la fuente se mueve hacia el observador y $v_s<0$ cuando se aleja.
- Las dos velocidades se miden respecto del aire.

Así, acercarse aumenta la frecuencia por dos mecanismos posibles: el observador intercepta los frentes más rápido (sube el numerador) y la fuente los comprime (baja el denominador). Alejarse produce el efecto opuesto.

![[imagenes/doppler-casos.svg]]

### Eco de una pared: aplicar Doppler en dos etapas

En un eco con pared quieta, primero la pared recibe el sonido de la fuente móvil. Esa frecuencia depende del movimiento de la fuente. La pared refleja el sonido sin cambiar su frecuencia en su propio marco. Luego la fuente móvil recibe la onda reflejada como observadora en movimiento. Son dos cambios Doppler sucesivos, no una sola aplicación con una velocidad combinada.

Si fuente y pared se aproximan con rapidez relativa $v_s$ y el medio está quieto, la frecuencia que oye la fuente es:

$$
f_{\mathrm{eco}}=f_s\frac{v+v_s}{v-v_s}.
$$

El resultado debe ser mayor que $f_s$ si la fuente se acerca a la pared. En el ejercicio del parcial, dibujar las dos etapas evita confundir quién actúa como fuente y quién como observador en cada tramo.

## 10. Cómo elegir el modelo en un ejercicio

| Si el enunciado pide… | Identifica primero… | Relación inicial |
|---|---|---|
| Desplazamiento desde presión | Amplitud de presión, $B$, $f$ y $v$ del mismo medio | $k=2\pi f/v$; $\Delta p_{\max}=Bk s_{\max}$ |
| Rapidez del sonido en fluido, gas o varilla | Qué propiedades del medio están dadas | $v=\sqrt{B/\rho}$; $v=\sqrt{\gamma RT/M}$; $v\approx\sqrt{Y/\rho}$ |
| Longitud de onda en un medio | Rapidez de propagación y frecuencia | $\lambda=v/f$ |
| Intensidad desde presión | Si el dato es amplitud máxima o valor eficaz | $I=p_{\max}^2/(2\rho v)$ o $I=p_{\mathrm{rms}}^2/(\rho v)$ |
| Potencia de una fuente o cambio con distancia | Si la fuente emite isotrópicamente | $I=P_{\mathrm{ac}}/(4\pi r^2)$ |
| Nivel sonoro desde intensidad, o viceversa | Referencia $I_0$ y razón dentro del logaritmo | $\beta=10\log_{10}(I/I_0)$ |
| Dos parlantes o reflexión en pared | Diferencia de caminos y fase relativa | $\Delta r=m\lambda$ o $\Delta r=(m+\tfrac12)\lambda$ |
| Sirena en movimiento | Velocidades de fuente y observador respecto del aire | Doppler; si se mueve la fuente, primero cambia $\lambda$ |
| Eco que vuelve a una fuente móvil | Qué objeto recibe cada tramo | Aplicar Doppler a la ida y a la vuelta |

## 11. Ruta de razonamiento

1. Dibuja el medio, la fuente, el receptor y el sentido de propagación.
2. Separa rapidez de la onda $v$ y movimiento local de las partículas $u$.
3. Anota si la presión es una variación acústica máxima, un valor eficaz u otra cantidad.
4. Escribe qué material determina la rapidez, o usa el valor que ya entrega el problema.
5. Para varias fuentes, decide si son incoherentes (sumar intensidades) o coherentes (sumar ondas y usar fases).
6. En Doppler, define las velocidades respecto del aire y luego asigna signos.
7. Despeja con símbolos antes de introducir números y revisa unidades.
8. Comprueba la tendencia física: más presión-amplitud significa más intensidad; acercamiento debe elevar la frecuencia recibida.

## Fuentes consultadas

- [Texto sobre tipos de ondas mecánicas, sección 15.1](zotero://select/library/items/RHTMK6UM): propagación, período, frecuencia, longitud de onda y separación entre el movimiento de la onda y el de las partículas, PDF pp. 4–6.
- [Presentación de ondas y sonido](zotero://select/library/items/WFMW87CP): definición y sonido longitudinal, PDF p. 12; rapidez en medios y gas ideal, pp. 13–14; intensidad, p. 15; nivel sonoro, pp. 16–17; Doppler y variables, pp. 18–22.
- [Práctica de sonido, Física Aplicada 2021](zotero://select/library/items/ZFCVVKE5): presión y desplazamiento, ejercicios 1–2; sonar y longitud de onda, 3; rapidez en sólidos y gases, 4–5; intensidad, potencia y decibeles, 6–10; reflexión e interferencia, 11–12; longitudes de onda móviles, Doppler y eco, 13–17.
- Los modelos de parcial priorizan presión-desplazamiento, nivel sonoro y Doppler. El recorrido ampliado incorpora las familias de la práctica que no aparecen en los modelos consultados.

## Autoevaluación conceptual

Contesta con tus palabras y despliega después la explicación para comprobar el razonamiento.

**1. En una onda sonora, ¿qué llega desde la fuente hasta el oído: las mismas moléculas de aire o una perturbación?**

> [!success]- Mostrar explicación
> Avanza la perturbación y transporta energía. Las moléculas de aire cercanas al oído oscilan alrededor de sus posiciones; no viajan desde la fuente hasta el oído junto con el patrón.

**2. ¿Qué diferencia hay entre la rapidez del sonido $v$ y la rapidez local de una partícula $u$?**

> [!success]- Mostrar explicación
> $v$ es la rapidez con que avanza la fase de la onda por el medio; $u$ es la velocidad instantánea de oscilación de una partícula. La relación $v=\lambda f$ describe la primera.

**3. ¿Por qué una compresión aumenta la presión?**

> [!success]- Mostrar explicación
> La compresión reduce el volumen local. El módulo volumétrico mide la resistencia a ese cambio, y una deformación negativa genera una variación positiva de presión. Matemáticamente, $\Delta p\approx-B\,\partial s/\partial x$.

**4. Si la onda entra del aire a otro fluido, ¿qué pasa con frecuencia y longitud de onda?**

> [!success]- Mostrar explicación
> La frecuencia sigue marcada por la fuente y se conserva al cruzar la frontera. La rapidez cambia según las propiedades del nuevo medio; por $\lambda=v/f$, cambia la longitud de onda.

**5. ¿Por qué presión acústica y desplazamiento no son máximos a la vez y lugar?**

> [!success]- Mostrar explicación
> La presión depende de cuánto cambia el desplazamiento entre partículas vecinas, es decir, del gradiente espacial. Al derivar una sinusoide aparece un desfase de un cuarto de ciclo: el desplazamiento máximo coincide con presión acústica cero, mientras que una compresión máxima coincide con presión máxima.

**6. ¿Qué distingue la presión acústica de la presión atmosférica?**

> [!success]- Mostrar explicación
> La presión acústica es la variación local alrededor de la presión de equilibrio. Si el enunciado da una amplitud de presión, no se le suma la presión atmosférica.

**7. Dos fuentes incoherentes e iguales duplican la intensidad. ¿Cuánto cambia el nivel?**

> [!success]- Mostrar explicación
> Sube aproximadamente $3.01\,\mathrm{dB}$, porque $10\log_{10}(2I/I_0)-10\log_{10}(I/I_0)=10\log_{10}2$. Se suman intensidades, no niveles.

**8. Dos parlantes coherentes llegan al punto $P$ con diferencia de camino $\lambda/2$. ¿Qué ocurre si emitían en fase?**

> [!success]- Mostrar explicación
> La diferencia de camino equivale a media longitud de onda, es decir, a medio ciclo de desfase. Una cresta coincide con un valle y la interferencia es destructiva ideal.

**9. ¿Qué cambia en el aire cuando se acerca una fuente sonora: la rapidez del sonido o el espaciamiento de frentes delante de la fuente?**

> [!success]- Mostrar explicación
> Cambia el espaciamiento delante de la fuente: se acorta porque la fuente avanza entre emisiones. La rapidez del sonido la fija el aire y no cambia por el movimiento de la fuente.

**10. ¿Por qué calcular el eco de una pared fija para una fuente móvil requiere dos pasos Doppler?**

> [!success]- Mostrar explicación
> La fuente móvil primero produce una frecuencia distinta en la pared. La pared refleja esa frecuencia; luego la fuente móvil recibe el reflejo como observadora en movimiento. Cada tramo tiene su propio emisor y receptor.

**11. Si una onda avanza $2.4\,\mathrm m$ durante $0.60\,\mathrm s$, ¿qué representa el cociente y qué rapidez obtienes?**

> [!success]- Mostrar explicación
> El cociente es la rapidez del patrón: $v=\Delta x/\Delta t=2.4/0.60=4.0\,\mathrm{m/s}$. No informa cuánto se desplazó una partícula del medio.

**12. Una onda tiene frecuencia $5\,\mathrm{Hz}$. ¿Qué significa ese dato y cuánto dura un ciclo?**

> [!success]- Mostrar explicación
> Significa que un punto del medio completa cinco oscilaciones por segundo. El período es el tiempo por oscilación: $T=1/f=0.20\,\mathrm s$.

**13. La frecuencia de una onda se duplica mientras sigue viajando en el mismo medio. Si la rapidez del medio no cambia, ¿qué pasa con $\lambda$?**

> [!success]- Mostrar explicación
> Como $v=\lambda f$ y $v$ permanece constante, al duplicarse $f$ la longitud de onda debe reducirse a la mitad: $\lambda=v/f$.
