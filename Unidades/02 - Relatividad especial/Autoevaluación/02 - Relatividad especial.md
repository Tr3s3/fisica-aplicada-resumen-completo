---
tags: [fisica-aplicada, autoevaluacion, unidad-02]
---

# Autoevaluación — Relatividad especial

[[Recursos de estudio/Autoevaluación/Inicio|← Índice]] · [[Unidades/02 - Relatividad especial/Teoría/02 - Guía breve de relatividad especial|Guía breve]] · [[Unidades/02 - Relatividad especial/Teoría/02 - Conceptos de relatividad especial|Conceptos]] · [[Unidades/02 - Relatividad especial/Teoría/02 - Fórmulas aplicadas de relatividad especial|Fórmulas]] · [[Unidades/02 - Relatividad especial/Ejercicios/02 - Relatividad especial|Ejercicios]]

> [!info] Secuencia recomendada
> Responde la sección asociada al bloque que acabas de leer. Escribe una justificación, no solo el resultado; abre cada respuesta para comparar el procedimiento y detectar qué decisión física debes reforzar.

## Conceptos

Preguntas de comprensión, interpretación y elección del modelo.

### Autoevaluación conceptual

Responde cada pregunta por tu cuenta y despliega después su explicación razonada.

**1. ¿Qué afirma el segundo postulado de la relatividad especial y qué límite impone a la suma de velocidades?**

> [!success]- Mostrar explicación
> La rapidez de la luz en el vacío es la misma para todo observador inercial, independientemente del movimiento de la fuente. Si se conservara el tiempo universal de la transformación clásica, la suma de velocidades daría $c+v$ o $c-v$ para un rayo, en contradicción con ese postulado. La transformación de Lorentz cambia cómo se relacionan espacio y tiempo entre marcos y mantiene $c$ invariante. Para velocidades mucho menores que $c$, se recupera aproximadamente la mecánica clásica.

**2. ¿Qué hace que un intervalo sea tiempo propio y por qué otro marco mide un intervalo mayor?**

> [!success]- Mostrar explicación
> Los dos eventos deben ocurrir en el mismo lugar del marco que mide $\Delta t_0$. En otro marco el reloj se mueve y los eventos ocurren en posiciones distintas. Al comparar las mediciones, $\Delta t=\gamma\Delta t_0$ con $\gamma>1$ si hay movimiento relativo; la diferencia surge de la geometría espacio-temporal, no de un defecto del reloj.

**3. ¿Por qué una medición de longitud requiere que los extremos se registren simultáneamente en el marco que mide?**

> [!success]- Mostrar explicación
> La longitud es la separación entre los extremos en un mismo instante del marco que mide. La relación $\Delta t'=\gamma(\Delta t-v\Delta x/c^2)$ muestra que dos registros simultáneos en la Tierra ($\Delta t=0$) no suelen ser simultáneos en la nave ($\Delta t'\ne0$). La longitud propia se mide en el marco de reposo del objeto; al medir simultáneamente los extremos desde un marco donde se mueve, se obtiene $L=L_0/\gamma$ en la dirección del movimiento.

**4. Una nave avanza hacia $+x$ y lanza un proyectil hacia atrás. ¿Qué signo tiene la velocidad del proyectil en el marco de la nave y para qué sirve ese signo?**

> [!success]- Mostrar explicación
> Si se define $+x$ como la dirección de avance de la nave, el proyectil tiene $u'<0$ en el marco de ella. El signo permite aplicar la suma relativista con la orientación correcta y decidir si, desde la Tierra, el proyectil todavía avanza hacia $+x$ o termina moviéndose hacia $-x$.

**5. ¿Qué energía gana un electrón que parte del reposo al atravesar una diferencia de potencial, y cómo se convierte esa energía en rapidez?**

> [!success]- Mostrar explicación
> El trabajo eléctrico aporta $K=e|\Delta V|$. Se relaciona con la energía relativista mediante $K=(\gamma-1)m_ec^2$; se despeja $\gamma$ y luego $v/c=\sqrt{1-1/\gamma^2}$. Este contenido es una ampliación del TP, posterior a los tipos que aparecen en los modelos.

## Fórmulas

Preguntas para elegir relaciones, reconocer supuestos, despejar y comprobar resultados.

### Aplicación de fórmulas

Antes de abrir cada explicación, escribe qué representa cada dato y en qué marco se mide.

**1. Un reloj viaja con una nave y mide el intervalo entre dos eventos que ocurren en el mismo lugar de la nave. ¿Qué relación usas para hallar el intervalo terrestre?**

> [!success]- Mostrar explicación
> El intervalo del reloj de la nave es propio: $\Delta t_0$. Primero calculas $\gamma=1/\sqrt{1-v^2/c^2}$ y luego usas $\Delta t=\gamma\Delta t_0$. El resultado terrestre debe ser igual o mayor que el propio. La elección se justifica por dónde ocurren los eventos, no por cuál valor es dado.

**2. Una nave mide 100 m en reposo y pasa paralela a su eje largo. ¿Qué longitud mide un observador que la ve moverse y qué sincronización requiere?**

> [!success]- Mostrar explicación
> Se usa $L=L_0/\gamma$. El observador registra las posiciones de ambos extremos al mismo tiempo en su propio marco; no puede tomar una lectura simultánea en el marco de la nave y reutilizarla. La contracción afecta solo la dirección paralela al movimiento.

**3. En $S'$, un proyectil viaja hacia $-x$ y el marco $S'$ se mueve hacia $+x$ respecto de $S$. ¿Cómo asignas los signos en $u=(u'+v)/(1+u'v/c^2)$?**

> [!success]- Mostrar explicación
> Escribes $u'<0$ porque el proyectil viaja hacia $-x$ en $S'$, y $v>0$ porque $S'$ se mueve hacia $+x$ respecto de $S$. Sustituyes esos signos en numerador y denominador; el signo de $u$ determina el sentido medido en $S$. El denominador aparece porque el tiempo también se transforma entre marcos, y el módulo de la velocidad resultante debe ser menor que $c$.

**4. ¿Puedes dividir una distancia medida desde la Tierra por una rapidez medida desde la nave para calcular el tiempo terrestre de llegada?**

> [!success]- Mostrar explicación
> No. La distancia y la rapidez deben corresponder al mismo marco para que $t=D/u$ describa el intervalo de ese observador. Primero transforma la velocidad al marco terrestre, convierte las unidades y entonces calcula el tiempo terrestre.

**5. Un electrón parte del reposo y gana energía cinética $K$ en una diferencia de potencial. ¿Cómo obtienes su rapidez sin usar $K=\frac12mv^2$?**

> [!success]- Mostrar explicación
> Primero usas $E_0=m_ec^2$ y $K=(\gamma-1)m_ec^2$, por lo que $\gamma=1+K/E_0$. Luego despejas $v/c=\sqrt{1-1/\gamma^2}$. La fórmula clásica de energía cinética no describe correctamente una partícula que se acerca a $c$.

## Repaso del módulo

Preguntas de síntesis sobre las decisiones que conviene dominar antes de resolver la práctica completa.

### Comprensión global

Contesta sin consultar las notas de conceptos ni fórmulas; luego despliega la explicación para corregirte.

**1. ¿Cómo reconoces cuál intervalo temporal es el propio?**

> [!success]- Mostrar explicación
> Identifica los dos eventos que delimitan el proceso y busca el marco donde ocurren en el mismo lugar. El reloj en reposo en ese marco mide el tiempo propio $\Delta t_0$. Para otro marco, $\Delta t=\gamma\Delta t_0$, con $\gamma\ge1$.

**2. ¿Qué condiciones deben cumplirse al comparar la longitud propia de una nave con su longitud medida desde la Tierra?**

> [!success]- Mostrar explicación
> La longitud propia $L_0$ se mide en el marco donde la nave está en reposo. La Tierra mide las posiciones de ambos extremos simultáneamente en su propio marco. Si la dimensión es paralela al movimiento, obtiene $L=L_0/\gamma$; una dimensión transversal no se contrae en este modelo.

**3. ¿Qué debes fijar antes de sumar velocidades relativistas y qué control físico haces al final?**

> [!success]- Mostrar explicación
> Dibuja un eje, identifica qué marco se mueve respecto de cuál y asigna signo a cada velocidad según su sentido. Sustituye en la transformación correspondiente, no en la suma clásica. La rapidez final de un objeto material debe quedar menor que $c$; además, para velocidades pequeñas frente a $c$ la expresión debe aproximarse a la suma clásica.
