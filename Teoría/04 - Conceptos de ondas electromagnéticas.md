---
tags: [fisica-aplicada, teoria, conceptos, ondas-em]
---

# Conceptos de ondas electromagnéticas

[[Teoría/04 - Ondas electromagnéticas|← Índice del módulo]] · [[Teoría/04 - Fórmulas aplicadas de ondas electromagnéticas|Formulario aplicado]] · [[Ejercicios/04 - Ondas electromagnéticas|Práctica]]

> [!summary] La idea central
> Una onda electromagnética es un patrón de campos eléctrico y magnético que cambia y avanza por el espacio. Transporta energía, pero no necesita que la materia viaje desde la fuente hasta el receptor. En el vacío avanza a la rapidez de la luz, $c$.

## Ruta sugerida para aprender el tema

1. Empieza con las secciones 1–4 y el esquema: identifica qué cambia, qué representa cada parámetro y cómo se orientan los campos.
2. Lee la sección 5 para aprender a construir las ecuaciones de la onda y verificar su sentido.
3. Practica los ejercicios 20 y 21. Después usa la tabla de la sección 6 para elegir el modelo en los ejercicios complementarios.
4. Vuelve a la sección 7 si quieres entender por qué esas relaciones se desprenden de Maxwell. Las derivaciones vectoriales se pueden abrir cuando ya tengas clara la imagen física.

## 1. Qué viaja y qué oscila

En una onda sonora, oscilan partículas del aire y sus empujes transmiten la perturbación. Por eso el sonido necesita un medio. En una onda electromagnética no tienen que oscilar partículas materiales: lo que cambia son el **campo eléctrico** $\vec E$ y el **campo magnético** $\vec B$.

Un campo describe una propiedad física en cada punto del espacio. Si la fuente cambia esos campos, sus variaciones se enlazan y la perturbación se propaga. Una vez emitida, puede recorrer el vacío. La luz visible, las ondas de radio, las microondas y los rayos X son ondas electromagnéticas; se distinguen principalmente por su frecuencia y longitud de onda.

**La onda avanza; los campos oscilan.** En una onda plana sinusoidal, cada componente del campo sube, baja y vuelve a repetirse mientras el patrón se mueve. La energía puede llegar a otra región aunque no haya un flujo de materia que acompañe a la onda.

## 2. Leer los parámetros en los gráficos

![[imagenes/componentes-onda-electromagnetica.svg]]

El dibujo tiene dos lecturas complementarias:

- **Perfil espacial:** imaginamos una fotografía de toda la onda en un mismo instante. La distancia entre dos repeticiones equivalentes es la longitud de onda $\lambda$.
- **Oscilación temporal:** fijamos la atención en un punto y observamos cómo cambia el campo allí. El tiempo entre repeticiones es el período $T$.

Las curvas de $E_y$ y $B_z$ se dibujan separadas en el primer gráfico para mostrar sus componentes sobre ejes distintos. En el segundo están superpuestas y normalizadas solo para mostrar que, en la onda plana sinusoidal en el vacío, oscilan **en fase**: sus máximos y cruces por cero ocurren a la vez. Sus unidades y valores numéricos no son iguales.

| Símbolo | Qué significa | Cómo lo reconoces o calculas |
|---|---|---|
| $E_{max}$ | Amplitud del campo eléctrico: máximo valor de $E$ respecto de cero. | Se mide en $\mathrm{V/m}$. Si dan $B_{max}$, en el vacío $E_{max}=cB_{max}$. |
| $B_{max}$ | Amplitud del campo magnético. | Se mide en teslas. En el vacío $B_{max}=E_{max}/c$. |
| $\lambda$ | Distancia espacial de un ciclo completo de la onda. | Cresta a cresta de un mismo campo, en metros. |
| $T$ | Tiempo de un ciclo en un punto fijo. | Se mide en segundos. |
| $f$ | Número de ciclos por segundo. | $f=1/T$, en hertz. La fija la fuente. |
| $c$ | Rapidez de propagación en el vacío. | $3.00\times10^8\,\mathrm{m/s}$. No es la rapidez de oscilación de una partícula. |
| $v$ | Rapidez de propagación en un material. | La determina el material; se usa $v=\lambda f$. |
| $k$ | Cambio de fase por distancia. | $k=2\pi/\lambda$, en $\mathrm{rad/m}$. |
| $\omega$ | Cambio de fase por tiempo. | $\omega=2\pi f=2\pi/T$, en $\mathrm{rad/s}$. |
| $\phi_0$ | Fase inicial: estado de la oscilación en el origen elegido. | Aparece como constante en el argumento del seno o coseno. |

> [!important] No son la misma clase de amplitud
> En una onda de cuerda, la amplitud suele ser un desplazamiento en metros. En una onda electromagnética, las amplitudes son valores de campo: $E_{max}$ se mide en voltios por metro y $B_{max}$ en teslas. Ninguno representa cuánto se desplaza una partícula del espacio.

## 3. De dónde sale $v=\lambda f$

La rapidez de propagación se define como distancia recorrida por el patrón dividida por el tiempo. Si en un punto transcurre un período $T$, pasa un ciclo completo; durante ese tiempo la onda avanza una longitud de onda $\lambda$. Entonces

$$
v=\frac{\text{distancia}}{\text{tiempo}}=\frac{\lambda}{T}.
$$

Como la frecuencia cuenta ciclos por segundo y $f=1/T$,

$$
\boxed{v=\frac{\lambda}{T}=\lambda f}.
$$

En el vacío $v=c$, así que

$$
\boxed{c=\lambda f},\qquad
\boxed{f=\frac{c}{\lambda}},\qquad
\boxed{\lambda=\frac{c}{f}}.
$$

Esto da una regla de interpretación: si la frecuencia aumenta en el vacío, la longitud de onda disminuye para que el producto siga siendo $c$. La frecuencia la fija la fuente; $\lambda$ indica cuánto espacio ocupa cada ciclo. Si la onda entra en un material, conserva la frecuencia pero cambia su rapidez y, por eso, cambia su longitud de onda. Allí se usa $\lambda=v/f$, no $c/f$.

## 4. Orientación de $\vec E$, $\vec B$ y el avance

En una onda plana, los tres sentidos son perpendiculares entre sí:

$$
\vec E\perp\vec B,\qquad
\vec E\perp\hat n,\qquad
\vec B\perp\hat n,
$$

donde $\hat n$ es el vector unitario que señala el avance. Por eso la onda electromagnética es transversal. **La onda no avanza en la dirección de $\vec E$ ni de $\vec B$**: avanza perpendicular a ambos.

![[imagenes/onda-electromagnetica.svg]]

Para encontrar el sentido que falta, usa la regla de la mano derecha:

$$
\vec B_{max}=\frac{1}{c}\,\hat n\times\vec E_{max},
\qquad
\vec E_{max}\times\vec B_{max}\text{ apunta como }\hat n.
$$

Por ejemplo, si la onda avanza en $+x$ y $\vec E$ apunta en $+y$, entonces $\vec B$ apunta en $+z$, porque $\hat x\times\hat y=\hat z$. Comprueba el resultado al revés: $\hat y\times\hat z=\hat x$. El orden importa; invertir los factores invierte el sentido.

En el vacío, las magnitudes máximas se relacionan así:

$$
\boxed{E_{max}=cB_{max}},\qquad
\boxed{B_{max}=\frac{E_{max}}{c}}.
$$

Esta relación se aplica a una onda plana en el vacío. Los campos tienen unidades distintas; el factor $c$ hace la conversión entre ellas. No significa que sus valores numéricos sean iguales. El formulario aplicado muestra cómo se obtiene esta relación a partir de la ley de Faraday.

## 5. Cómo escribir la onda y reconocer hacia dónde viaja

En una onda sinusoidal que avanza por el eje $x$, la fase puede escribirse

$$
\Phi(x,t)=kx\mp\omega t+\phi_0.
$$

La fase identifica en qué punto del ciclo está el campo. Un ciclo espacial hace que cambie $2\pi$ radianes a lo largo de $\lambda$, y un ciclo temporal cambia $2\pi$ en un período. De ahí salen $k=2\pi/\lambda$ y $\omega=2\pi f$.

Para una onda hacia $+x$:

$$
\vec E(x,t)=\vec E_{max}\cos(kx-\omega t+\phi_0),\qquad
\vec B(x,t)=\vec B_{max}\cos(kx-\omega t+\phi_0).
$$

Para una onda hacia $-x$, se usa $kx+\omega t+\phi_0$. ¿Por qué cambia el signo? Sigue una cresta, manteniendo constante su fase:

- $kx-\omega t=C$ implica $dx/dt=+\omega/k$: avanza hacia $+x$.
- $kx+\omega t=C$ implica $dx/dt=-\omega/k$: avanza hacia $-x$.

![[imagenes/sentido-fase-onda.svg]]

Un coseno y un seno pueden describir la misma onda con una fase inicial distinta. Lo importante es que $\vec E$ y $\vec B$ compartan la fase y que el signo indique el sentido correcto.

### Receta para construir las funciones de campo

1. Dibuja los ejes y anota hacia dónde avanza la onda.
2. Escribe los datos en unidades SI: por ejemplo, nm a m y mT a T.
3. Calcula $f$ o $\lambda$ con $c=\lambda f$.
4. Calcula el otro campo con $E_{max}=cB_{max}$ o $B_{max}=E_{max}/c$.
5. Usa el producto vectorial para fijar la dirección de $\vec B$ y confirma que $\vec E\times\vec B$ apunte como el avance.
6. Obtén $k=2\pi/\lambda$ y $\omega=2\pi f$; elige la fase según el sentido.
7. Sustituye todo en las dos funciones y comprueba unidades, direcciones y $\omega=ck$.

Esta receta corresponde sobre todo a los ejercicios 20 y 21. El 21 invierte el sentido de propagación y sirve para comprobar que el signo no se decide de memoria ni a ojo.

## 6. Elegir el modelo según lo que pide el ejercicio

| Qué describe el enunciado | Idea que debes aplicar | Ejercicios |
|---|---|---|
| Una onda sinusoidal en el vacío y sus ecuaciones vectoriales | $c=\lambda f$, amplitudes, producto vectorial y fase | 20–21 |
| Luz o radio que pasa a un material | Primero calcula $v$; la frecuencia se conserva y $\lambda=v/f$ | 22–23 |
| Campos instantáneos y energía por volumen | Suma energía eléctrica y magnética; usa valores instantáneos | 24 |
| Potencia repartida alrededor de una antena | Intensidad = potencia/área; luego relaciona intensidad y amplitudes | 25 |
| Fuerza de la luz sobre una superficie | La radiación transporta momento; distingue absorción de reflexión | 26 |
| Dos ondas que se superponen en sentidos opuestos | Forma estacionaria; promedia el flujo durante un período | 27 |
| Ondas entre paredes conductoras | Impón nodos de $E$ en las paredes y cuenta medias longitudes de onda | 28 |

Los desarrollos numéricos y las condiciones precisas para cada fórmula están en [[Teoría/04 - Fórmulas aplicadas de ondas electromagnéticas]]. Aquí el objetivo es reconocer qué fenómeno representa cada ejercicio antes de sustituir números.

## 7. Qué explican las leyes de Maxwell

La idea física puede resumirse sin calcular integrales: un campo magnético que cambia en el tiempo está asociado con un campo eléctrico que circula; un campo eléctrico que cambia está asociado con un campo magnético que circula. La ley de Faraday y la ley de Ampère-Maxwell describen ese acoplamiento. El aporte de Maxwell permite que exista campo magnético variable incluso en una región sin corriente material.

Al combinar ambas leyes en el vacío se obtiene una ecuación de onda para cada campo. Su rapidez resulta

$$
c=\frac{1}{\sqrt{\mu_0\epsilon_0}}\approx3.00\times10^8\,\mathrm{m/s},
$$

donde $\epsilon_0$ es la permitividad eléctrica y $\mu_0$ la permeabilidad magnética del vacío. Maxwell mostró así que la luz es una onda electromagnética: su rapidez coincide con la rapidez que predicen las ecuaciones del electromagnetismo.

> [!example]- Ver las cuatro leyes de Maxwell en forma integral
> La presentación del curso las muestra de esta forma. $S$ es una superficie cerrada y $C$ su contorno; el flujo mide cuánto campo atraviesa la superficie y la circulación suma la componente del campo a lo largo del contorno.
>
> ![[imagenes/maxwell-ecuaciones-presentacion.png]]
>
> $$
> \begin{aligned}
> \int_S \vec E\cdot d\vec A&=\frac{Q_{enc}}{\epsilon_0} &&\text{(Gauss eléctrica)},\\
> \int_S \vec B\cdot d\vec A&=0 &&\text{(Gauss magnética)},\\
> \oint_C \vec E\cdot d\vec\ell&=-\frac{d\Phi_B}{dt} &&\text{(Faraday)},\\
> \oint_C \vec B\cdot d\vec\ell&=\mu_0\left(I_{enc}+\epsilon_0\frac{d\Phi_E}{dt}\right) &&\text{(Ampère-Maxwell)}.
> \end{aligned}
> $$
>
> La ley de Gauss eléctrica vincula el flujo de $\vec E$ con la carga encerrada; la ley de Gauss magnética expresa que el flujo magnético neto cerrado es cero. Faraday vincula el cambio de flujo magnético con circulación eléctrica. Ampère-Maxwell vincula la circulación magnética con la corriente y con el cambio de flujo eléctrico.

> [!example]- Ver el paso matemático que produce la ecuación de onda
> En el vacío, sin cargas ni corrientes de conducción, las formas locales relevantes son $\nabla\times\vec E=-\partial\vec B/\partial t$ y $\nabla\times\vec B=\mu_0\epsilon_0\,\partial\vec E/\partial t$, junto con $\nabla\cdot\vec E=0$. Aplicar el rotacional a la ley de Faraday y sustituir Ampère-Maxwell da
>
> $$
> \nabla\times(\nabla\times\vec E)
> =-\frac{\partial}{\partial t}(\nabla\times\vec B)
> =-\mu_0\epsilon_0\frac{\partial^2\vec E}{\partial t^2}.
> $$
>
> La identidad $\nabla\times(\nabla\times\vec E)=\nabla(\nabla\cdot\vec E)-\nabla^2\vec E$ y $\nabla\cdot\vec E=0$ producen $\nabla^2\vec E-\mu_0\epsilon_0\,\partial^2\vec E/\partial t^2=0$. Al compararla con $\nabla^2\psi-(1/v^2)\partial^2\psi/\partial t^2=0$, se obtiene $v=1/\sqrt{\mu_0\epsilon_0}=c$. Para $\vec B$ se llega a la misma ecuación.
>
> Los símbolos $\nabla\cdot$ y $\nabla\times$ representan divergencia y rotacional. No es necesario calcularlos en los ejercicios de este módulo; esta derivación explica de dónde viene la rapidez $c$.

## 8. Energía que transporta la onda

Los campos guardan energía en el espacio. En el vacío, la energía por unidad de volumen es

$$
u=\frac12\epsilon_0E^2+\frac{B^2}{2\mu_0}.
$$

Cada término es una parte: energía eléctrica y magnética. En una onda plana en el vacío, $E=cB$ hace que ambas contribuciones sean iguales, por lo que $u=\epsilon_0E^2=B^2/\mu_0$.

El vector de Poynting describe el flujo de energía: indica la dirección y cuánta energía cruza por unidad de área y tiempo,

$$
\vec S=\frac{1}{\mu_0}\vec E\times\vec B.
$$

Su unidad es $\mathrm{W/m^2}$. El producto cruzado hace que el flujo apunte en el sentido de propagación. En una onda progresiva en el vacío, $S=cu$.

**Instantáneo y promedio no son lo mismo.** Para un pulso con campos constantes detrás del frente, se usan los valores instantáneos: $S=EB/\mu_0$. Para una onda sinusoidal, se suele pedir la intensidad media durante un ciclo:

$$
I=\langle S\rangle
=\frac{E_{max}B_{max}}{2\mu_0}
=\frac12\epsilon_0cE_{max}^2.
$$

El factor $1/2$ aparece al promediar el producto sinusoidal, pues el promedio de $\cos^2$ en un ciclo es $1/2$. Por eso el pulso del ejercicio 24 y la antena sinusoidal del ejercicio 25 no usan exactamente la misma forma de cálculo.

### Potencia repartida por una antena

Si una antena distribuye uniformemente la potencia media $P$ sobre una esfera de radio $r$, el área es $4\pi r^2$. Si la distribuye sobre el hemisferio superior, el área es $2\pi r^2$. En ambos casos,

$$
I=\frac{P}{\text{área atravesada}}.
$$

Luego se obtiene $E_{max}$ con la fórmula de intensidad media y $B_{max}=E_{max}/c$. Primero decide qué superficie corresponde a la descripción; no uses automáticamente el área de una esfera completa.

### Presión de radiación

La radiación transporta momento además de energía, por eso puede ejercer una fuerza. Para incidencia perpendicular:

- superficie que absorbe: $p_{rad}=I/c$;
- superficie que refleja perfectamente: $p_{rad}=2I/c$.

El reflejo duplica el cambio de momento porque invierte su sentido. Con la presión calculada, la fuerza sobre un área $A$ es $F=p_{rad}A$.

## 9. Cuando la onda entra en un material

El material responde a los campos y modifica la rapidez de propagación. Para un material uniforme, lineal y sin pérdidas, con permitividad $\epsilon=K\epsilon_0$ y permeabilidad $\mu=K_m\mu_0$,

$$
v=\frac{1}{\sqrt{\epsilon\mu}}=\frac{c}{\sqrt{KK_m}}.
$$

La frecuencia sigue fijada por la fuente y se conserva al cruzar una frontera estacionaria. Si la rapidez disminuye, también disminuye la longitud de onda:

$$
\lambda_{material}=\frac{v}{f}.
$$

Calcula primero la rapidez del material y después la longitud de onda. La expresión $c/f$ corresponde al vacío. Esta secuencia resuelve los ejercicios 22 y 23.

## 10. Ondas estacionarias y cavidades

Dos ondas de igual frecuencia y amplitud que viajan en sentidos opuestos pueden superponerse y formar un patrón con nodos fijos. Un nodo es un punto donde la amplitud de esa componente siempre es cero; un vientre o antinodo es donde alcanza su máximo.

Una onda estacionaria no implica que los campos sean siempre nulos. La energía puede fluir momentáneamente en uno u otro sentido; en el patrón ideal el flujo neto medio durante un período es cero.

Entre paredes conductoras, el campo eléctrico paralelo a la pared debe anularse en la superficie. Por eso las paredes son nodos de $E$. Para que haya un patrón permitido, entre ellas debe caber un número entero de medias longitudes de onda:

$$
L=m\frac{\lambda}{2},\qquad m=1,2,3,\ldots
$$

En el modo fundamental, $m=1$: $\lambda_1=2L$. El campo eléctrico tiene un máximo en el centro; el patrón espacial del campo magnético es complementario, con máximos junto a las paredes y un nodo central. Esto orienta los ejercicios 27 y 28.

## Errores que conviene evitar

- Tratar $E_{max}$ como un desplazamiento en metros: es amplitud de campo eléctrico, en $\mathrm{V/m}$.
- Confundir la rapidez de propagación con el ritmo de oscilación: $c$ o $v$ se miden en $\mathrm{m/s}$; $f$ en ciclos por segundo.
- Confundir frecuencia $f$ con frecuencia angular $\omega=2\pi f$.
- Usar $c/f$ para la longitud de onda dentro de un material.
- Creer que $\vec E$ o $\vec B$ apuntan en la dirección de avance.
- Elegir $\vec B$ sin revisar que $\vec E\times\vec B$ apunte con la onda.
- Olvidar convertir nm, μm, mT o MV/m a unidades SI.
- Usar el factor $1/2$ de intensidad media para un campo instantáneo constante, o quitarlo de una onda sinusoidal promediada.
- Aplicar $E_{max}=cB_{max}$ en un medio material sin que el modelo lo permita.

## Fuentes de esta nota

- [Presentación de Ondas Electromagnéticas](zotero://select/library/items/FQBGWVB4), PDF pp. 2–5: qué es una onda electromagnética, diferencia con ondas mecánicas, leyes de Faraday y Ampère-Maxwell y formulación de Maxwell. La diapositiva de las leyes se incluye como imagen para poder leer sus símbolos.
- [Práctica de ondas electromagnéticas](zotero://select/library/items/T92A4S8A), PDF pp. 2–9: ecuaciones de campo, propagación en materiales, energía, flujo, presión de radiación, ondas estacionarias y cavidades.
- Los enlaces de origen y los modelos consultados también están listados en [[Fuentes Zotero y probabilidad]].

## Autoevaluación de conceptos

Responde con tus palabras antes de abrir cada explicación. En cada caso identifica la pista del enunciado que te hace elegir esa idea.

**1. En el gráfico espacial, ¿qué mides con $\lambda$? ¿Qué mides con $T$ en el gráfico temporal?**

> [!success]- Mostrar explicación
> $\lambda$ es la distancia de un ciclo completo entre puntos vecinos que repiten el mismo estado, medida en una instantánea. $T$ es el tiempo de un ciclo al seguir un punto fijo. Son dos maneras distintas de observar el mismo patrón periódico.

**2. ¿Qué oscila en una onda electromagnética y qué diferencia principal tiene con el sonido?**

> [!success]- Mostrar explicación
> Oscilan los campos $\vec E$ y $\vec B$. No hace falta que partículas materiales transporten la perturbación. El sonido es mecánico: necesita materia y transmite la onda mediante el movimiento local e interacción de las partículas.

**3. ¿Qué información física contiene $E_{max}$? ¿Es un desplazamiento de una partícula?**

> [!success]- Mostrar explicación
> Es el valor máximo del campo eléctrico y se mide en $\mathrm{V/m}$. No es un desplazamiento. En este tipo de onda la amplitud describe el tamaño del campo, no una distancia recorrida por materia.

**4. Si se conoce $T$, ¿cómo hallas la frecuencia? ¿Qué significa ese resultado?**

> [!success]- Mostrar explicación
> $f=1/T$. El resultado indica cuántos ciclos pasan por un punto en un segundo. Si $T=0.20\,\mathrm{s}$, por ejemplo, $f=5\,\mathrm{Hz}$.

**5. Una onda avanza hacia $+x$ y $\vec E$ apunta hacia $+y$. ¿En qué sentido apunta $\vec B$?**

> [!success]- Mostrar explicación
> $\vec B$ apunta hacia $+z$, porque $\hat x\times\hat y=\hat z$. Compruébalo con $\vec E\times\vec B$: $\hat y\times\hat z=\hat x$, el sentido de avance.

**6. ¿Por qué en el vacío una frecuencia mayor implica una longitud de onda menor?**

> [!success]- Mostrar explicación
> En el vacío $c=\lambda f$ y $c$ es constante. Para que el producto no cambie, cuando $f$ aumenta $\lambda$ debe disminuir. La fuente fija $f$ y la rapidez determina la longitud de onda.

**7. ¿Qué significa la fase $kx-\omega t$ y hacia dónde viaja?**

> [!success]- Mostrar explicación
> La fase señala el estado del ciclo en cada posición y tiempo. Si la mantenemos constante, $kx-\omega t=C$ da $dx/dt=+\omega/k$; la forma de onda viaja hacia $+x$.

**8. ¿De dónde aparece la rapidez $c$ en las ondas electromagnéticas?**

> [!success]- Mostrar explicación
> Maxwell relaciona las variaciones de los campos. Al combinar sus leyes se obtiene una ecuación de onda con rapidez $1/\sqrt{\mu_0\epsilon_0}$, igual a la rapidez de la luz en el vacío.

**9. La luz entra en un material donde viaja más despacio. Si la fuente no cambia, ¿qué ocurre con $f$ y con $\lambda$?**

> [!success]- Mostrar explicación
> La frecuencia se conserva porque la fuente sigue oscilando con el mismo ritmo. Como $v=\lambda f$, al bajar $v$ también baja $\lambda$.

**10. ¿Por qué la intensidad media de una onda sinusoidal lleva un factor $1/2$?**

> [!success]- Mostrar explicación
> El flujo instantáneo depende del producto de los campos y, para la sinusoide, contiene un factor $\cos^2$. El promedio de $\cos^2$ en un ciclo es $1/2$. Un pulso de campos constantes usa valores instantáneos y no ese promedio.

**11. ¿Por qué una superficie perfectamente reflectante recibe el doble de presión que una que absorbe la misma intensidad?**

> [!success]- Mostrar explicación
> Al absorber, la radiación entrega su momento incidente. Al reflejar, el momento cambia al sentido contrario, por lo que la variación de momento transferida es el doble. De ahí $2I/c$ frente a $I/c$.

**12. En la cavidad fundamental, ¿por qué hay nodos de $E$ en las paredes?**

> [!success]- Mostrar explicación
> Las paredes conductoras exigen que el campo eléctrico tangencial se anule en su superficie. Son nodos consecutivos separados por media longitud de onda; por eso $L=\lambda/2$ en el modo fundamental. El campo magnético tiene el patrón espacial complementario.
