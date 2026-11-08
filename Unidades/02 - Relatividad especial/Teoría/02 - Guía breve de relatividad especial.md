---
tags: [fisica-aplicada, teoria, lectura-activa, relatividad]
aliases: [Teoría breve de relatividad especial, Lectura activa de relatividad especial]
---

# Guía breve — Relatividad especial

> [!info] Cómo trabajar esta nota
> Lee un bloque por vez (5–10 minutos). Cierra la nota y explica con tus palabras qué fenómeno describe, qué significa la relación central y cuándo se puede usar. Contesta la pregunta de comprobación sin desplegar su explicación; intenta inmediatamente el ejercicio enlazado, sin pistas. Abre la explicación solo después de intentar recordar o resolver.

**Profundizar:** [[Unidades/02 - Relatividad especial/Teoría/02 - Conceptos de relatividad especial|contexto y deducciones]] · [[Unidades/02 - Relatividad especial/Teoría/02 - Fórmulas aplicadas de relatividad especial|fórmulas aplicadas]] · [[Unidades/02 - Relatividad especial/Ejercicios/02 - Relatividad especial|ejercicios]] · [[Unidades/02 - Relatividad especial/Resoluciones/02 - Relatividad especial|resoluciones paso a paso]]


## R1. Factor de Lorentz y tiempo propio

La relatividad especial compara mediciones hechas en marcos inerciales y conserva la misma rapidez de la luz para todos ellos. Por eso no basta con restar velocidades como en la mecánica cotidiana. Al traducir mediciones entre marcos sin cambiar el valor de $c$, las transformaciones de espacio y tiempo introducen el factor de Lorentz $\gamma$:

$$
\gamma=\frac{1}{\sqrt{1-v^2/c^2}}.
$$

Si $v$ es mucho menor que $c$, entonces $\gamma\approx1$ y las diferencias relativistas son pequeñas; al acercarse $v$ a $c$, $\gamma$ crece.

El **tiempo propio** $\Delta\tau$ es el que marca un reloj que está presente en ambos eventos; en el marco de ese reloj, los eventos ocurren en el mismo lugar. Otro marco ve ese reloj en movimiento y mide un intervalo mayor: $\Delta t=\gamma\Delta\tau$. Primero se identifican los eventos y los marcos; después se decide cuál intervalo es propio. No se elige la fórmula mirando solamente qué tiempo es conocido.

![[imagenes/reloj-luz-dilatacion.svg]]

**Decisión:** busca el reloj que puede estar junto a los dos eventos. Su medida es propia. Verifica que $\gamma\ge1$ y que el intervalo no propio sea mayor.

**Comprueba:** en el ejemplo de una nave, ¿qué detalle del enunciado te permite identificar el tiempo propio?

> [!success]- Explicación después de intentar
> El tiempo propio lo mide el reloj que acompaña a los dos eventos. En el marco de la nave, ambos ocurren en el mismo lugar; por eso el reloj de la tripulación marca $\Delta\tau$.

**Pasa a práctica:** [[Unidades/02 - Relatividad especial/Ejercicios/02 - Relatividad especial|ejercicios 8–10 y complementarios C1, C6–C7]].

## R2. Simultaneidad y longitud propia

La **longitud propia** $L_0$ se mide en el marco donde el objeto está en reposo. Si el objeto se mueve respecto del observador, la longitud en la dirección del movimiento es $L=L_0/\gamma$. Esta relación sale de transformar las posiciones de los extremos y medirlas simultáneamente en el marco observador. Las dimensiones perpendiculares al movimiento no se contraen en este modelo.

Medir una longitud requiere registrar los dos extremos **al mismo tiempo en el marco que mide**. La simultaneidad entre marcos no es universal: dos observadores pueden no coincidir en qué mediciones de extremos son simultáneas. Esta condición explica por qué la contracción no se aplica comparando lecturas de extremos tomadas en momentos distintos.

**Decisión:** identifica dónde el objeto está en reposo para saber cuál es $L_0$, y confirma que la longitud pedida es paralela al movimiento. Una longitud contraída debe ser menor que $L_0$.

**Comprueba:** ¿en qué marco hay que medir simultáneamente los extremos para obtener la longitud que ve ese observador?

> [!success]- Explicación después de intentar
> En el marco del observador que mide esa longitud. Sus posiciones de ambos extremos deben registrarse simultáneamente según sus relojes.

**Pasa a práctica:** [[Unidades/02 - Relatividad especial/Ejercicios/02 - Relatividad especial|ejercicio 11 y complementarios C2–C4]]. Consulta [[Unidades/02 - Relatividad especial/Teoría/02 - Conceptos de relatividad especial]] si necesitas repasar la simultaneidad.

## R3. Sumar velocidades de marcos distintos

Si un objeto tiene velocidad $u'$ en un marco que se mueve a velocidad $v$ respecto del laboratorio, y ambas velocidades se miden sobre el mismo eje, el laboratorio mide:

$$
u=\frac{u'+v}{1+u'v/c^2}.
$$

La relación se obtiene al transformar las velocidades entre marcos usando las transformaciones relativistas de espacio y tiempo. El denominador corrige la suma clásica para que el resultado no supere $c$; cuando ambas velocidades son pequeñas frente a $c$, el término $u'v/c^2$ se vuelve despreciable y se recupera aproximadamente la suma clásica. La fórmula usa velocidades **con signo**: antes de reemplazar, define un eje y asigna signo según cada movimiento. Si las velocidades apuntan en sentidos opuestos, una entra negativa. Una vez obtenido $u$ en el marco solicitado, recién entonces se calcula allí el tiempo de viaje, por ejemplo $t=D/u$ si la distancia y la rapidez están medidas en ese mismo marco.

**Decisión:** escribe quién se mueve respecto de quién, fija el eje y verifica que el resultado tenga el sentido esperado y $|u|<c$.

**Comprueba:** ¿por qué no puedes combinar una distancia de la Tierra con una rapidez medida desde la nave para calcular directamente el tiempo terrestre?

> [!success]- Explicación después de intentar
> Porque $t=D/u$ relaciona distancia y rapidez medidas en el mismo marco. Si mezclas marcos, esos valores no describen un único recorrido y tiempo; primero transforma la velocidad al marco terrestre.

**Pasa a práctica:** [[Unidades/02 - Relatividad especial/Ejercicios/02 - Relatividad especial|ejercicios 12–13]].

---

## Si todavía queda una duda

Vuelve al concepto o a la fórmula señalados en [[Recursos de estudio/Teoría general/00 - Teoría esencial para practicar|la ruta general]]. Registra la duda en [[Recursos de estudio/Práctica/00 - Método y registro]] y vuelve a intentar el ejercicio sin la pista.
