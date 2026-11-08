---
tags: [fisica-aplicada, teoria, lectura-activa, ondas-acustica]
aliases: [Teoría breve de ondas y acústica, Lectura activa de ondas y acústica]
---

# Guía breve — Ondas y acústica

> [!info] Cómo trabajar esta nota
> Lee un bloque por vez (5–10 minutos). Cierra la nota y explica con tus palabras qué fenómeno describe, qué significa la relación central y cuándo se puede usar. Contesta la pregunta de comprobación sin desplegar su explicación; intenta inmediatamente el ejercicio enlazado, sin pistas. Abre la explicación solo después de intentar recordar o resolver.

**Profundizar:** [[Unidades/03 - Ondas y acústica/Teoría/03 - Conceptos de ondas y acústica|contexto y deducciones]] · [[Unidades/03 - Ondas y acústica/Teoría/03 - Fórmulas aplicadas de ondas y acústica|fórmulas aplicadas]] · [[Unidades/03 - Ondas y acústica/Ejercicios/03 - Ondas y acústica|ejercicios]] · [[Unidades/03 - Ondas y acústica/Resoluciones/03 - Ondas y acústica|resoluciones paso a paso]]


## O1. Qué oscila y qué avanza

Una onda mecánica es una perturbación que se propaga por un medio. Las partículas del medio oscilan alrededor de su equilibrio; la perturbación y la energía avanzan. En una onda periódica, la amplitud $A$ es el máximo desplazamiento, la longitud de onda $\lambda$ es la separación entre puntos en la misma fase y el período $T$ es el tiempo de una oscilación. La frecuencia es $f=1/T$.

En un período, un patrón avanza una longitud de onda. Por ello, su rapidez satisface

$$
v=\frac{\lambda}{T}=\lambda f.
$$

Para una sinusoide $y=A\cos(kx-\omega t+\phi)$, $k=2\pi/\lambda$ mide el cambio de fase por distancia y $\omega=2\pi f$ mide el cambio de fase por tiempo. No son velocidades; la rapidez de fase es $\omega/k=\lambda f$.

![[imagenes/parametros-onda-mecanica.svg]]

**Decisión:** determina si te piden el estado de una partícula, la distancia entre ciclos o el avance del patrón. Conserva unidades: $k$ en rad/m, $\omega$ en rad/s.

**Comprueba:** si conoces $f$ y $v$ en el medio, ¿cómo obtienes la distancia entre dos crestas consecutivas?

> [!success]- Explicación después de intentar
> La distancia entre crestas es $\lambda$. De $v=\lambda f$ se despeja $\lambda=v/f$.

**Pasa a práctica:** [[Unidades/03 - Ondas y acústica/Ejercicios/03 - Ondas y acústica|ejercicio 20 y la parte de parámetros de C21]]. Después relaciona el esquema con [[Unidades/03 - Ondas y acústica/Teoría/03 - Conceptos de ondas y acústica]].

## O2. Sonido: desplazamiento y presión

El sonido en el aire es longitudinal: las partículas se desplazan en la misma dirección en que avanza la perturbación y forman compresiones y rarefacciones. La presión acústica $\Delta p$ es la pequeña variación respecto de la presión de equilibrio, no la presión atmosférica completa.

El módulo volumétrico $B$ mide cuánto se resiste el medio a comprimirse. Una deformación relativa produce un cambio de presión; para una onda sinusoidal, la variación espacial del desplazamiento aporta el factor $k$. De ahí que las amplitudes cumplan $\Delta p_{\max}=Bk s_{\max}$, donde $s_{\max}$ es la amplitud del desplazamiento local. Si una superficie recibe esa presión sobre un área $A$, la fuerza es $F=\Delta p A$; por eso, en el modelo simplificado del oído, conservar la fuerza mientras disminuye el área aumenta la presión transmitida.

La rapidez depende de las propiedades elásticas e inerciales del medio: por ejemplo, en un fluido $v=\sqrt{B/\rho}$ y en una varilla delgada $v\approx\sqrt{Y/\rho}$. Al cambiar de medio suele cambiar $v$ y, como $f$ la fija la fuente, cambia $\lambda=v/f$. Al reemplazar $B=\rho v^2$ y $k=2\pi f/v$ en la relación de amplitudes, queda $\Delta p_{\max}=\rho v(2\pi f)s_{\max}$; esta forma permite hallar el desplazamiento en el fluido del ejercicio del oído.

**Decisión:** identifica el medio, usa su modelo de rapidez y diferencia amplitud de presión de amplitud de desplazamiento. Para la relación de amplitudes, despeja $s_{\max}=\Delta p_{\max}/(Bk)$.

**Comprueba:** si el sonido entra a otro medio, ¿qué magnitud conserva la fuente y cuál debe ajustarse para que se cumpla $v=\lambda f$?

> [!success]- Explicación después de intentar
> La frecuencia $f$ se conserva en una frontera fija porque la fuente sigue oscilando al mismo ritmo. La rapidez cambia según el medio y la longitud de onda se ajusta a $\lambda=v/f$.

**Pasa a práctica:** [[Unidades/03 - Ondas y acústica/Ejercicios/03 - Ondas y acústica|ejercicio 14 y ejercicios 20–22]].

## O3. Intensidad y decibeles

La intensidad $I$ es la potencia transportada por unidad de área. En el sonido, la presión empuja las partículas y realiza trabajo sobre el medio; al promediar ese flujo de energía durante un ciclo sinusoidal se obtiene, para amplitud máxima de presión $\Delta p_{\max}$:

$$
I=\frac{(\Delta p_{\max})^2}{2\rho v}.
$$

El nivel sonoro expresa en una escala logarítmica la razón entre la intensidad y una intensidad de referencia $I_0$. El logaritmo permite representar en una escala manejable intensidades que abarcan muchos órdenes de magnitud:

$$
\beta=10\log_{10}\left(\frac{I}{I_0}\right)\ \mathrm{dB}.
$$

Si llegan fuentes independientes, primero se suman sus intensidades lineales; después se calcula el nivel con el logaritmo. Duplicar intensidad no duplica decibeles: agrega $10\log_{10}2\approx3.0\,\mathrm{dB}$. Si la fuente reparte potencia en todas direcciones, la misma potencia atraviesa áreas esféricas mayores y $I=P/(4\pi r^2)$.

**Decisión:** convierte cualquier dato a intensidad lineal antes de sumar. No sumes directamente niveles en dB salvo que el problema provea una situación especial que lo justifique.

**Comprueba:** si se duplica $I$, ¿qué operación haces con el nivel: duplicarlo o volver a aplicar el logaritmo?

> [!success]- Explicación después de intentar
> Vuelves a aplicar el logaritmo a la intensidad total: el nivel sube $10\log_{10}2\approx3.0\,\mathrm{dB}$; no se duplica.

**Pasa a práctica:** [[Unidades/03 - Ondas y acústica/Ejercicios/03 - Ondas y acústica|ejercicios 15–16 y 21, 23]].

## O4. Efecto Doppler: separar fuente y observador

La rapidez del sonido se mide respecto del aire. Una fuente móvil cambia el espaciamiento de los frentes y, por tanto, la longitud de onda que deja en el medio. Un observador móvil cambia cuántos frentes encuentra por segundo. Al acercarse, la frecuencia recibida aumenta; al alejarse, disminuye.

Con el signo positivo asignado al movimiento **hacia el otro participante**, una forma útil es

$$
f_{\mathrm{obs}}=f_s\frac{v+v_o}{v-v_s},
$$

donde $v$ es la rapidez del sonido en el medio, $v_o$ la rapidez del observador y $v_s$ la de la fuente. Para ambos acercándose, la fuente deja frentes separados por $\lambda'=(v-v_s)/f_s$ y el observador los encuentra a rapidez $v+v_o$; por eso $f_{\mathrm{obs}}=(v+v_o)/\lambda'$. Esta convención supone movimiento rectilíneo sobre la línea fuente–observador; anota aparte si cada uno se acerca o aleja antes de sustituir.

**Decisión:** si se mueve la fuente, piensa primero en la longitud de onda que genera; si se mueve el observador, piensa en la rapidez con que encuentra frentes. El resultado debe ser mayor que $f_s$ cuando ambos se acercan.

**Comprueba:** ¿qué actor cambia el espaciamiento de los frentes en el aire y cuál cambia el ritmo con que los recibe?

> [!success]- Explicación después de intentar
> La fuente móvil cambia el espaciamiento o longitud de onda que deja en el aire. El observador móvil cambia la rapidez con que encuentra esos frentes y, por tanto, el número recibido por segundo.

**Pasa a práctica:** [[Unidades/03 - Ondas y acústica/Ejercicios/03 - Ondas y acústica|ejercicios 17–19 y 26–27]].

## O5. Interferencia y ondas estacionarias

Cuando dos ondas coherentes se superponen, sus desplazamientos y presiones se suman punto a punto. La diferencia de camino genera una diferencia de fase $\Delta\phi=2\pi\Delta r/\lambda$. Si las fuentes están en fase, $\Delta r=n\lambda$ produce interferencia constructiva (las oscilaciones llegan alineadas); $\Delta r=(n+\tfrac12)\lambda$ produce interferencia destructiva (llegan en oposición). La reflexión puede cambiar la fase y, por eso, también debe considerarse qué ocurre en el límite.

**Decisión:** dibuja las trayectorias, calcula la diferencia de caminos y compárala con $\lambda$. No uses la regla de fuentes independientes para sumar intensidades cuando la fase relativa determina el resultado.

**Comprueba:** ¿qué diferencia de camino entre dos fuentes en fase permite un mínimo de interferencia?

> [!success]- Explicación después de intentar
> Una diferencia $\Delta r=(n+\tfrac12)\lambda$, con $n$ entero, produce una diferencia de fase impar de $\pi$ y llegada en oposición.

**Pasa a práctica:** [[Unidades/03 - Ondas y acústica/Ejercicios/03 - Ondas y acústica|ejercicios 24–25]]. Mira ![[imagenes/interferencia-altavoces-tp-2021.png|500]].

---

## Si todavía queda una duda

Vuelve al concepto o a la fórmula señalados en [[Recursos de estudio/Teoría general/00 - Teoría esencial para practicar|la ruta general]]. Registra la duda en [[Recursos de estudio/Práctica/00 - Método y registro]] y vuelve a intentar el ejercicio sin la pista.
