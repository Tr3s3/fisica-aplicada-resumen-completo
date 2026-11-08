---
tags: [fisica-aplicada, teoria, lectura-activa, ondas-em]
aliases: [Teoría breve de ondas electromagnéticas, Lectura activa de ondas electromagnéticas]
---

# Guía breve — Ondas electromagnéticas

> [!info] Cómo trabajar esta nota
> Lee un bloque por vez (5–10 minutos). Cierra la nota y explica con tus palabras qué fenómeno describe, qué significa la relación central y cuándo se puede usar. Contesta la pregunta de comprobación sin desplegar su explicación; intenta inmediatamente el ejercicio enlazado, sin pistas. Abre la explicación solo después de intentar recordar o resolver.

**Profundizar:** [[Unidades/04 - Ondas electromagnéticas/Teoría/04 - Conceptos de ondas electromagnéticas|contexto y deducciones]] · [[Unidades/04 - Ondas electromagnéticas/Teoría/04 - Fórmulas aplicadas de ondas electromagnéticas|fórmulas aplicadas]] · [[Unidades/04 - Ondas electromagnéticas/Ejercicios/04 - Ondas electromagnéticas|ejercicios]] · [[Unidades/04 - Ondas electromagnéticas/Resoluciones/04 - Ondas electromagnéticas|resoluciones paso a paso]]


## E1. Parámetros y ecuación de una onda

Una onda electromagnética es una variación propagante de los campos eléctrico y magnético; no necesita un medio material. Como en una onda periódica, $v=\lambda f$, $k=2\pi/\lambda$ y $\omega=2\pi f$. $k$ indica cuánto cambia la fase por metro (rad/m) y $\omega$ cuánto cambia por segundo (rad/s). En el vacío, $v=c$.

Para avance en $+x$, una componente sinusoidal puede escribirse $E_y=E_{\max}\cos(kx-\omega t+\phi)$. La fase constante se desplaza hacia $+x$; si la fase es $kx+\omega t+\phi$, se desplaza hacia $-x$. Esta comprobación sale de mantener la fase fija y calcular cómo cambia $x$ con el tiempo.

**Decisión:** convierte primero unidades de longitud y campo a SI; obtiene $f$, $k$ y $\omega$; y verifica el sentido de la fase antes de escribir los vectores.

**Comprueba:** si mantienes $kx-\omega t$ constante, ¿hacia qué lado debe moverse $x$ cuando aumenta $t$?

> [!success]- Explicación después de intentar
> De $kx-\omega t=C$ resulta $x=(\omega/k)t+C/k$. Como $\omega/k>0$, la posición aumenta con el tiempo: la onda viaja hacia $+x$.

**Pasa a práctica:** [[Unidades/04 - Ondas electromagnéticas/Ejercicios/04 - Ondas electromagnéticas|ejercicios 20–21]].

## E2. Orientación de los campos

En una onda plana en el vacío, $\vec E$ y $\vec B$ oscilan en fase, son perpendiculares entre sí y ambos son perpendiculares a la dirección de avance $\hat n$. Sus amplitudes cumplen $E_{\max}=cB_{\max}$. Esta igualdad relaciona magnitudes con unidades distintas: el factor $c$ convierte teslas en voltios por metro.

La dirección de transporte de energía es la de $\vec E\times\vec B$. Por eso, conocidos el avance y $\vec E$, la orientación de $\vec B$ se puede hallar con $\vec B=(1/c)\hat n\times\vec E$ y comprobar calculando de vuelta $\vec E\times\vec B$.

**Decisión:** dibuja los tres ejes y usa la regla de la mano derecha. No elijas signos de los vectores solo por memoria: comprueba el producto vectorial.

**Comprueba:** ¿qué operación vectorial permite comprobar que tu elección de $\vec B$ transporta energía en el sentido correcto?

> [!success]- Explicación después de intentar
> Calcula $\vec E\times\vec B$. Su dirección debe coincidir con el sentido de propagación de la onda.

**Pasa a práctica:** [[Unidades/04 - Ondas electromagnéticas/Ejercicios/04 - Ondas electromagnéticas|ejercicios 20–21]].

![[imagenes/onda-electromagnetica.svg|350]]

## E3. La onda al propagarse por un material

En un medio lineal, la permitividad y la permeabilidad determinan la rapidez: $v=1/\sqrt{\mu\epsilon}$. Con propiedades relativas $K$ y $K_m$, se escribe $v=c/\sqrt{KK_m}$. Al cruzar una frontera fija, la frecuencia se conserva porque la oscilación debe coincidir a ambos lados; cambian la rapidez y la longitud de onda, relacionadas por $\lambda=v/f$.

**Decisión:** calcula primero la frecuencia o longitud de onda en el vacío con $c$, después la rapidez en el medio, y finalmente usa la misma frecuencia para hallar la longitud de onda interna.

**Comprueba:** en el diamante, ¿qué razón hace que la longitud de onda sea menor que en el vacío?

> [!success]- Explicación después de intentar
> Como $K>1$ y $K_m\approx1$, $v=c/\sqrt{KK_m}<c$. La frecuencia no cambia al cruzar la frontera fija, así que $\lambda=v/f$ disminuye.

**Pasa a práctica:** [[Unidades/04 - Ondas electromagnéticas/Ejercicios/04 - Ondas electromagnéticas|ejercicios complementarios 22–23]].

## E4. Energía, flujo y presión de radiación

Los campos almacenan energía eléctrica y magnética. La densidad total instantánea es $u=\tfrac12\epsilon_0E^2+B^2/(2\mu_0)$ y el flujo de energía por área y tiempo está descrito por el vector de Poynting $\vec S=(\vec E\times\vec B)/\mu_0$. Para una onda plana en el vacío, $S=cu$ en el caso instantáneo descrito.

En una onda sinusoidal, los campos varían en el tiempo; al promediar el cuadrado de un campo proporcional a $\cos(\omega t)$ se usa $\langle\cos^2(\omega t)\rangle=1/2$. Por eso, al usar amplitudes máximas para la **intensidad media**, aparece $I=\tfrac12\epsilon_0cE_{\max}^2$. No confundas este promedio con un pulso de campos constantes detrás de un frente. La radiación también transfiere momento: a incidencia normal, una superficie absorbente recibe presión $I/c$ y una reflectora ideal $2I/c$.

**Decisión:** reconoce si el dato describe un valor instantáneo, una amplitud o un promedio. Para una antena, distribuye la potencia sobre el área que indica la geometría; luego relaciona intensidad con amplitudes.

**Comprueba:** ¿por qué aparece un factor $1/2$ para la intensidad media sinusoidal, pero no al calcular el flujo de un pulso constante?

> [!success]- Explicación después de intentar
> En una sinusoide, el flujo depende del cuadrado del campo y el promedio de $\cos^2(\omega t)$ durante un período es $1/2$. En la región constante del pulso descrito no se promedia una oscilación temporal.

**Pasa a práctica:** [[Unidades/04 - Ondas electromagnéticas/Ejercicios/04 - Ondas electromagnéticas|ejercicios complementarios 24–26]].

## E5. Modos estacionarios en una cavidad

Una onda estacionaria aparece al superponer ondas de igual frecuencia que viajan en sentidos opuestos. Para el ejercicio de flujo medio, primero se suman los campos $\vec E$ y $\vec B$ punto a punto y después se forma $\vec S$; dos ondas iguales que transportan energía en sentidos opuestos pueden dejar campos no nulos, pero su flujo promedio neto es cero. Entre paredes conductoras ideales, el campo eléctrico tangencial debe anularse en las paredes. Para dos paredes separadas por $L$, el modo fundamental coloca dos nodos consecutivos de $E$ y por eso $L=\lambda/2$. Los modos siguientes acomodan más semilongitudes de onda.

Para el fundamental, $\lambda_1=2L$ y $f_1=c/(2L)$ en el vacío. La condición de contorno fija los nodos del campo eléctrico; los del campo magnético quedan desplazados espacialmente respecto de ellos.

**Decisión:** usa la condición en las paredes para encontrar $\lambda$ antes de calcular la frecuencia; identifica nodos y máximos en el esquema.

**Comprueba:** ¿por qué la distancia entre dos paredes del modo fundamental equivale a media longitud de onda?

> [!success]- Explicación después de intentar
> En cada pared conductora el campo eléctrico tangencial es cero. El modo de menor frecuencia pone dos nodos consecutivos en las paredes; entre ceros consecutivos de una onda estacionaria hay $\lambda/2$.

**Pasa a práctica:** [[Unidades/04 - Ondas electromagnéticas/Ejercicios/04 - Ondas electromagnéticas|ejercicios complementarios 27–28]].

![[imagenes/cavidad-modo-fundamental.svg]]

---

## Si todavía queda una duda

Vuelve al concepto o a la fórmula señalados en [[Recursos de estudio/Teoría general/00 - Teoría esencial para practicar|la ruta general]]. Registra la duda en [[Recursos de estudio/Práctica/00 - Método y registro]] y vuelve a intentar el ejercicio sin la pista.
