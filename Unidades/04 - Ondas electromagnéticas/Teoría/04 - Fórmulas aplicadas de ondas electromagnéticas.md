---
tags: [fisica-aplicada, teoria, formulas, ondas-em]
---

# Fórmulas aplicadas — ondas electromagnéticas

[[Unidades/04 - Ondas electromagnéticas/Teoría/04 - Ondas electromagnéticas|← Índice del módulo]] · [[Unidades/04 - Ondas electromagnéticas/Teoría/04 - Conceptos de ondas electromagnéticas|Conceptos]]

## Magnitudes y unidades

| Símbolo | Significado | Unidad SI |
|---|---|---|
| $\lambda$ | Longitud de onda | $\mathrm m$ |
| $f$ | Frecuencia | $\mathrm{Hz}=\mathrm{s^{-1}}$ |
| $T$ | Período | $\mathrm s$ |
| $c$ | Rapidez de propagación en el vacío | $\mathrm{m/s}$ |
| $v$ | Rapidez de propagación en un medio material | $\mathrm{m/s}$ |
| $k$ | Número de onda | $\mathrm{rad/m}$ |
| $\omega$ | Frecuencia angular | $\mathrm{rad/s}$ |
| $\epsilon_0$ | Permitividad eléctrica del vacío | $\mathrm{F/m}$ |
| $\mu_0$ | Permeabilidad magnética del vacío | $\mathrm{H/m}$ |
| $E_{max}$ | Amplitud del campo eléctrico | $\mathrm{V/m}$ |
| $B_{max}$ | Amplitud del campo magnético | $\mathrm T$ |
| $K$ | Permitividad relativa del medio (constante dieléctrica) | adimensional |
| $K_m$ | Permeabilidad relativa del medio | adimensional |
| $n$ | Índice de refracción | adimensional |
| $m$ | Número de modo de una cavidad | entero positivo |
| $u$ | Densidad de energía electromagnética | $\mathrm{J/m^3}$ |
| $\vec S$ | Flujo de energía (vector de Poynting) | $\mathrm{W/m^2}$ |
| $I$ | Intensidad media de una onda | $\mathrm{W/m^2}$ |
| $p_{rad}$ | Presión de radiación | $\mathrm{Pa}$ |
| $A$ | Área que recibe el flujo | $\mathrm{m^2}$ |
| $L$ | Separación entre paredes de una cavidad | $\mathrm m$ |

Convierte primero: $1\,\mathrm{nm}=10^{-9}\,\mathrm m$, $1\,\mathrm{\mu m}=10^{-6}\,\mathrm m$, $1\,\mathrm{mT}=10^{-3}\,\mathrm T$ y $1\,\mathrm{MV/m}=10^6\,\mathrm{V/m}$.

Para los cálculos en el vacío, usa $\epsilon_0=8.85\times10^{-12}\,\mathrm{F/m}$, $\mu_0=4\pi\times10^{-7}\,\mathrm{H/m}$ y $c=3.00\times10^8\,\mathrm{m/s}$.

> [!info] Supuestos del formulario
> Las secciones 1–5 describen una onda plana sinusoidal en el vacío, como la del modelo de parcial; allí $E_{max}$ y $B_{max}$ son amplitudes. Las secciones 6–10 amplían el modelo a materiales uniformes, pulsos, potencia irradiada, presión de radiación y cavidades conductoras ideales. Cada sección indica las condiciones de uso. Para el contexto físico, consulta [[Unidades/04 - Ondas electromagnéticas/Teoría/04 - Conceptos de ondas electromagnéticas]].

## 1. Rapidez, frecuencia y longitud de onda

$$
c=\lambda f,\qquad
f=\frac{c}{\lambda},\qquad
\lambda=\frac{c}{f}.
$$

**De dónde sale:** la rapidez de una onda es distancia recorrida dividida por tiempo. En un período $T$, el patrón avanza exactamente una longitud de onda $\lambda$; entonces $v=\lambda/T$. Como $f=1/T$, queda $v=\lambda f$. En el vacío, Maxwell predice que esa rapidez es $c$, y de ahí salen las tres formas despejadas arriba.

**Cuándo usarla:** cuando el enunciado da $\lambda$ o $f$ de una onda en el vacío. En este módulo $v=c=3.00\times10^8\,\mathrm{m/s}$. Comprueba que la respuesta tenga unidades: $(\mathrm m)(\mathrm{s^{-1}})=\mathrm{m/s}$.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 2. Número de onda y frecuencia angular

La fase cuenta el avance de una oscilación en radianes. Un ciclo completo ocupa $\lambda$ metros y hace avanzar la fase $2\pi$ radianes; la fase temporal completa $2\pi$ radianes en un período $T$. Así, el cambio de fase por metro y por segundo es

$$
k=\frac{2\pi}{\lambda},\qquad
\omega=2\pi f,\qquad
\omega=ck.
$$

Usa $k$ en la fase espacial y $\omega$ en la fase temporal. Los radianes son adimensionales, pero se conservan en las unidades para recordar qué cantidad mide cada razón. La igualdad $\omega=ck$ se obtiene al reemplazar $k=2\pi/\lambda$ y $\omega=2\pi f$ en $c=\lambda f$; sirve como control independiente.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 3. Relación entre amplitudes

Para una onda plana sinusoidal en el vacío, las ecuaciones de Maxwell relacionan los máximos de ambos campos:

$$
E_{max}=cB_{max},\qquad
B_{max}=\frac{E_{max}}{c}.
$$

Elige la forma que despeja directamente la incógnita. La comprobación dimensional es útil: $(\mathrm{m/s})(\mathrm T)=\mathrm{V/m}$.

**De dónde sale:** tomemos el caso del dibujo: la onda avanza en $+x$, $\vec E$ está en $+y$ y $\vec B$ en $+z$:

$$
\vec E=\hat y E_{max}\cos\Phi,\qquad
\vec B=\hat z B_{max}\cos\Phi,\qquad
\Phi=kx-\omega t.
$$

En esta orientación, la ley de Faraday $\nabla\times\vec E=-\partial\vec B/\partial t$ compara la variación espacial del campo eléctrico con la variación temporal del magnético. Al derivar cada coseno:

$$
\nabla\times\vec E
=-\hat z\,kE_{max}\sin\Phi,
\qquad
-\frac{\partial\vec B}{\partial t}
=-\hat z\,\omega B_{max}\sin\Phi.
$$

Como la igualdad debe cumplirse en todo punto y tiempo, los factores comunes se cancelan y queda

$$
kE_{max}=\omega B_{max}
\quad\Longrightarrow\quad
\frac{E_{max}}{B_{max}}=\frac{\omega}{k}.
$$

Pero $\omega/k$ es la rapidez con que avanza una fase constante. En el vacío esa rapidez es $c$, por eso $E_{max}=cB_{max}$. En forma vectorial, la misma sustitución en la ley de Faraday da $\vec k\times\vec E_{max}=\omega\vec B_{max}$: explica tanto la razón de amplitudes como la orientación perpendicular de los campos. No hace falta derivar las funciones para usar la relación en los ejercicios.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 4. Dirección de los campos

Sea $\hat n$ el vector unitario de propagación. La orientación del campo magnético queda determinada por

$$
\vec B=\frac{1}{c}\,\hat n\times\vec E,
\qquad
\vec E\times\vec B\ \text{apunta en la dirección de}\ \hat n.
$$

La fórmula se obtiene de $\vec k\times\vec E_{max}=\omega\vec B_{max}$, usando $\vec k=k\hat n$ y $\omega=ck$. Sirve solo si los campos son perpendiculares y la onda está en el vacío. Para decidir el sentido, trabaja con unitarios cartesianos: $\hat x\times\hat y=\hat z$, $\hat y\times\hat z=\hat x$ y $\hat z\times\hat x=\hat y$. Invertir el orden invierte el signo. La comprobación final es que $\vec E\times\vec B$ apunte como $\hat n$.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 5. Ecuaciones de campo y sentido de viaje

En el eje $x$, las formas sinusoidales usuales son

$$
\vec E(x,t)=\vec E_{max}\cos(kx-\omega t+\phi_0),
\qquad
\vec B(x,t)=\vec B_{max}\cos(kx-\omega t+\phi_0)
$$

para propagación en $+x$. Para propagación en $-x$, cambia la fase a $kx+\omega t+\phi_0$. El signo sale de seguir un punto de fase constante: $kx-\omega t=C$ implica $dx/dt=+\omega/k$; $kx+\omega t=C$ implica $dx/dt=-\omega/k$. Los vectores amplitud $\vec E_{max}$ y $\vec B_{max}$ contienen tanto la magnitud como la dirección; deben respetar la regla del producto vectorial. Ambos campos comparten la misma fase.

Una forma que sirve para cualquier dirección es

$$
\vec E(\vec r,t)=\vec E_{max}\cos(\vec k\cdot\vec r-\omega t+\phi_0),
$$

con $\vec k=k\hat n$. El parcial puede resolverse en una dimensión usando $x$ y el signo de la fase.

> [!note] Una solución completa debe ser coherente
> No alcanza con calcular $f$, $k$ y las amplitudes: las direcciones de los vectores, la fase y el sentido de viaje describen una sola onda. Al sustituir los datos, verifica a la vez $\omega=ck$, $E_{max}=cB_{max}$ y que $\vec E\times\vec B$ señale la propagación.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 6. Rapidez y longitud de onda dentro de un material

En un medio uniforme, la respuesta eléctrica y magnética del material cambia la rapidez con que se propaga la onda. Para un medio lineal, isotrópico y sin pérdidas, con permitividad $\epsilon=K\epsilon_0$ y permeabilidad $\mu=K_m\mu_0$,

$$
v=\frac{1}{\sqrt{\epsilon\mu}}
=\frac{c}{\sqrt{KK_m}},
\qquad
n=\frac{c}{v}=\sqrt{KK_m}.
$$

La frecuencia la fija la fuente y se mantiene al cruzar una frontera estacionaria. Al cambiar $v$, cambia la separación espacial entre crestas:

$$
\lambda_{medio}=\frac{v}{f}=\frac{\lambda_0}{n}.
$$

**Cuándo usarlo:** cuando el enunciado da $K$, $K_m$ o el índice del material. Calcula primero $v$; luego usa $\lambda=v/f$. No uses $c/f$ para la longitud de onda dentro del material. La relación supone un medio homogéneo; no incluye absorción ni dispersión dependiente de la frecuencia.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 7. Densidad de energía y vector de Poynting

Los campos eléctrico y magnético almacenan energía por volumen. En el vacío, la suma de ambas contribuciones es

$$
u=u_E+u_B
=\frac12\epsilon_0E^2+\frac{B^2}{2\mu_0}.
$$

Para una onda plana en el vacío, $E=cB$ y las dos contribuciones son iguales; por eso se puede simplificar a

$$
u=\epsilon_0E^2=\frac{B^2}{\mu_0}.
$$

El vector de Poynting describe hacia dónde fluye la energía y a qué ritmo cruza cada unidad de área:

$$
\vec S=\frac{1}{\mu_0}\vec E\times\vec B.
$$

En una onda plana progresiva en el vacío, su magnitud instantánea satisface $S=cu$. Una superficie de área $A$ recibe potencia $P=SA$ si el flujo es uniforme y perpendicular a ella.

Para una onda sinusoidal, las amplitudes son máximos y $E$ y $B$ varían como cosenos. El promedio de $\cos^2$ sobre un período es $1/2$, de donde

$$
I=\langle S\rangle
=\frac{E_{max}B_{max}}{2\mu_0}
=\frac12\epsilon_0cE_{max}^2
=\frac{E_{max}^2}{2\mu_0c}.
$$

**No mezcles los dos casos:** para un pulso con campos constantes detrás del frente usa valores instantáneos y no agregues el factor $1/2$ de promedio sinusoidal. Para amplitudes de onda sinusoidal, sí se promedia y aparece ese factor.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 8. Reparto de potencia y amplitudes a distancia

Si una antena irradia uniformemente hacia el espacio completo, la potencia cruza un área esférica $4\pi r^2$. Si el suelo bloquea la mitad inferior y la potencia se reparte solo hacia arriba, el área es hemisférica:

$$
I=\frac{P}{A},
\qquad A_{esfera}=4\pi r^2,
\qquad A_{hemisferio}=2\pi r^2.
$$

Una vez obtenida $I$ para una onda sinusoidal, despeja $E_{max}=\sqrt{2I/(\epsilon_0c)}$ y luego $B_{max}=E_{max}/c$. Escoge el área según las direcciones en que realmente se reparte la potencia; usar $4\pi r^2$ cuando la antena emite solo sobre el terreno produce una intensidad dos veces menor.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 9. Presión de radiación en una superficie

La radiación transporta momento además de energía. Para incidencia perpendicular,

$$
p_{rad}=\frac{I}{c}\quad\text{(superficie absorbente)},
\qquad
p_{rad}=\frac{2I}{c}\quad\text{(reflexión perfecta)},
\qquad
F=p_{rad}A.
$$

La superficie absorbente recibe el momento que trae la radiación; una reflexión perfecta invierte el momento de los fotones y por eso transfiere el doble. Usa $I/c$ en paneles que absorben por completo. Las expresiones suponen incidencia normal y una intensidad media uniforme.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 10. Modos estacionarios en una cavidad

Dos ondas de igual frecuencia y amplitud que viajan en sentidos opuestos pueden formar una onda estacionaria. Los nodos se mantienen fijos. Entre dos paredes conductoras ideales, la componente tangencial de $\vec E$ debe anularse en ambas superficies; la distancia $L$ debe contener un número entero de semilongitudes de onda:

$$
L=m\frac{\lambda_m}{2},
\qquad
\lambda_m=\frac{2L}{m},
\qquad
f_m=\frac{mc}{2L},
\qquad m=1,2,3,\ldots
$$

El modo fundamental es $m=1$: tiene la mayor longitud de onda y la menor frecuencia distintas de cero. En ese modo $E$ tiene nodos en las paredes y un máximo a mitad de camino; la amplitud espacial de $B$ tiene máximos en las paredes y un nodo en el centro. Aunque los campos oscilan, el flujo de energía promediado en el tiempo no tiene dirección neta en una onda estacionaria ideal.


> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/04 - Ondas electromagnéticas/Autoevaluación/04 - Ondas electromagnéticas#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## Receta de resolución

1. Dibuja los ejes y escribe la dirección de propagación.
2. Convierte todos los datos a SI.
3. Calcula $f=c/\lambda$ o $\lambda=c/f$.
4. Calcula la amplitud que falta con $E_{max}=cB_{max}$.
5. Calcula $k=2\pi/\lambda$ y $\omega=2\pi f$.
6. Elige el signo de la fase a partir del sentido de viaje.
7. Obtén la dirección del otro campo con $\hat n\times\vec E$.
8. Escribe las dos ecuaciones y comprueba $\vec E\times\vec B$.

## Controles rápidos

- $E_{max}/B_{max}$ debe dar $3.00\times10^8\,\mathrm{m/s}$.
- Si la onda avanza en $-x$, la fase unidimensional debe tener $+\omega t$.
- Los tres sentidos deben ser mutuamente perpendiculares.
- Si usas amplitudes positivas junto con unitarios, el signo va en el unitario, no escondido en la fase.
- Un valor en $\mathrm{mT}$ o $\mathrm{nm}$ debe convertirse antes de calcular.
