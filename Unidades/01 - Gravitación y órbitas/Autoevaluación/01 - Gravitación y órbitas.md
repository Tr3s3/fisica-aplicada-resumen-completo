---
tags: [fisica-aplicada, autoevaluacion, unidad-01]
---

# Autoevaluación — Gravitación y órbitas

[[Recursos de estudio/Autoevaluación/Inicio|← Índice]] · [[Unidades/01 - Gravitación y órbitas/Teoría/01 - Guía breve de gravitación y órbitas|Guía breve]] · [[Unidades/01 - Gravitación y órbitas/Teoría/01 - Conceptos de gravitación y órbitas|Conceptos]] · [[Unidades/01 - Gravitación y órbitas/Teoría/01 - Fórmulas aplicadas de gravitación y órbitas|Fórmulas]] · [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|Ejercicios]]

> [!info] Secuencia recomendada
> Responde la sección asociada al bloque que acabas de leer. Escribe una justificación, no solo el resultado; abre cada respuesta para comparar el procedimiento y detectar qué decisión física debes reforzar.

## Conceptos

Preguntas de comprensión, interpretación y elección del modelo.

### Autoevaluación conceptual

Responde con tus palabras y escribe la relación física que respalda cada respuesta. Abre la explicación plegable solo después de intentarlo.

**1. Si la distancia entre dos masas se duplica, ¿por qué la fuerza queda en la cuarta parte? ¿Desde dónde se mide esa distancia?**

> [!success]- Mostrar explicación
> La ley universal dice $F_g\propto1/r^2$. Al reemplazar $r$ por $2r$, queda $F'_g/F_g=r^2/(2r)^2=1/4$. En planetas y otros cuerpos esféricamente simétricos vistos desde fuera, $r$ se mide entre los centros, no desde la superficie.

**2. ¿Por qué el campo de una fuente no depende del objeto de prueba y cómo se relaciona con su aceleración?**

> [!success]- Mostrar explicación
> Se define $\vec g=\vec F_g/m$. Al sustituir $\vec F_g=-GMm\,\hat{\mathbf r}/r^2$, la masa de prueba se cancela y queda $\vec g=-GM\,\hat{\mathbf r}/r^2$. Si no actúan otras fuerzas, $\vec a=\vec F_g/m=\vec g$. Las fuerzas sobre dos masas de prueba pueden ser distintas porque $F_g=mg$, aunque su aceleración gravitatoria sea la misma.

**3. Un objeto está a una altura igual al radio del planeta. ¿Qué distancia al centro usas y qué fracción del campo superficial tiene?**

> [!success]- Mostrar explicación
> Se usa $r=R+h=2R$. Como $g=GM/r^2$, su razón respecto del campo superficial es $g/g_0=(R/2R)^2=1/4$. La altura es la distancia sobre la superficie; la ley requiere la distancia desde el centro.

**4. ¿Qué dos ideas se combinan para obtener la rapidez orbital circular?**

> [!success]- Mostrar explicación
> La segunda ley de Newton requiere una fuerza neta radial $ma_c=mv^2/r$. En una órbita circular ideal, la gravedad es esa fuerza: $GMm/r^2=mv^2/r$. Al cancelar $m$ queda $v=\sqrt{GM/r}$. La dirección de la velocidad es tangente, mientras la aceleración apunta hacia el centro.

**5. ¿Por qué la energía potencial es negativa y en qué situación se recupera $mgh$?**

> [!success]- Mostrar explicación
> Se elige $U=0$ en el infinito. Al acercar dos masas, la gravedad realiza trabajo positivo y la energía potencial disminuye, por eso $U=-GMm/r<0$. Cerca de la superficie, si $h\ll R$, el cambio exacto $GMm(1/R-1/(R+h))$ se aproxima por $GMmh/R^2=mgh$, usando $g=GM/R^2$.

**6. ¿Cómo cambia el cálculo de energía de escape si el satélite ya está en una órbita circular?**

> [!success]- Mostrar explicación
> El umbral es la energía total final $E_f=0$. En una órbita circular el satélite ya tiene energía cinética y $E_i=-GMm/(2r)$, así que el aporte es la diferencia $\Delta E=E_f-E_i=GMm/(2r)$. No se agrega otra vez toda la energía cinética asociada a $v_{\text{esc}}$: esa rapidez es la rapidez total límite en el radio $r$. Primero identifica la energía que el satélite ya trae y luego calcula cuánto falta.

**7. ¿Cuándo se puede cancelar la constante de la tercera ley al comparar dos órbitas?**

> [!success]- Mostrar explicación
> Cuando ambos cuerpos orbitan la misma masa central y se mantiene el mismo modelo para las órbitas. En ese caso $4\pi^2/(GM)$ es común, de modo que $T_1^2/r_1^3=T_2^2/r_2^3$ (o se usan los semiejes mayores para órbitas elípticas). Si las masas centrales son distintas, el factor no es común.

**8. ¿Por qué la velocidad en una circunferencia es tangente, cómo se obtiene $v_t=2\pi r/T$ y de dónde sale $a_c=v_t^2/r$?**

> [!success]- Mostrar explicación
> En un intervalo muy corto, el desplazamiento entre dos posiciones se aproxima a la tangente; por eso la velocidad instantánea es tangente y perpendicular al radio. Una vuelta recorre $2\pi r$ durante un período $T$, así que $v_t=2\pi r/T$ (para movimiento uniforme). Entre dos instantes cercanos, las velocidades tienen módulo $v_t$ y difieren en un ángulo $\Delta\theta$: $|\Delta\vec v|\approx v_t\Delta\theta$. Para la circunferencia, el arco cumple exactamente $\Delta s=r|\Delta\theta|$; es la cuerda recta entre las posiciones la que se aproxima al arco cuando el intervalo es pequeño. Con $v_t=\lim_{\Delta t\to0}\Delta s/\Delta t$, entonces $a_c=\lim_{\Delta t\to0}|\Delta\vec v|/\Delta t=v_t^2/r$, dirigida hacia el centro.

## Fórmulas

Preguntas para elegir relaciones, reconocer supuestos, despejar y comprobar resultados.

### Aplicación de fórmulas

Intenta justificar la elección o el despeje antes de abrir la explicación.

**1. Si una masa está a altura $h=R$ sobre la superficie, ¿qué fracción del campo superficial experimenta y qué distancia debes usar en la razón?**

> [!success]- Mostrar explicación
> La distancia al centro es $r=R+h=2R$, no $R$. Como $g=GM/r^2$, la razón es $g/g_{sup}=R^2/(2R)^2=1/4$. Duplicar la distancia al centro reduce el campo a la cuarta parte.

**2. ¿Cómo se obtiene la rapidez de una órbita circular y por qué la masa del satélite se cancela?**

> [!success]- Mostrar explicación
> Se iguala la fuerza gravitatoria con la fuerza radial neta necesaria para el movimiento circular: $GMm/r^2=mv^2/r$. La masa del satélite $m$ aparece en ambos lados y se cancela, de donde $v=\sqrt{GM/r}$. La cancelación expresa que, en este modelo, la aceleración gravitatoria no depende de la masa del satélite.

**3. ¿Qué condición de energía define la rapidez de escape y cómo se diferencia del cálculo de rapidez orbital?**

> [!success]- Mostrar explicación
> Para escapar justo, el objeto llega al infinito con rapidez final cero y energía potencial cero. Se impone $\frac12mv_{esc}^2-GMm/r=0$, lo que da $v_{esc}=\sqrt{2GM/r}$. En una órbita circular se igualan fuerza gravitatoria y requerimiento centrípeto, y se obtiene $v_{orb}=\sqrt{GM/r}$; son condiciones físicas distintas.

**4. ¿Qué cantidades comparas para hallar el radio de una órbita a partir de períodos alrededor de la misma masa central?**

> [!success]- Mostrar explicación
> Usas $T^2/r^3=4\pi^2/(GM)$ para cada órbita. Como $M$ es común, $T_1^2/r_1^3=T_2^2/r_2^3$, así que $r_2=r_1(T_2/T_1)^{2/3}$. Verifica que ambos períodos correspondan al mismo cuerpo central.

## Repaso del módulo

Preguntas de síntesis sobre las decisiones que conviene dominar antes de resolver la práctica completa.

### Comprensión global

Intenta responder antes de desplegar cada explicación. Si dudas, vuelve a la nota de conceptos o de fórmulas enlazada en la ruta del módulo.

**1. ¿Qué información se pierde si, al calcular el campo de dos masas, sumas sus módulos sin dibujar sus direcciones?**

> [!success]- Mostrar explicación
> Se pierde la orientación de cada contribución. Los campos se suman como vectores: se proyectan sobre ejes, se suman las componentes con signo y luego se obtiene el módulo y la dirección del campo total. La masa de prueba no cambia ese campo porque se cancela al dividir la fuerza por dicha masa.

**2. Un satélite está a altura $h$ sobre un planeta. ¿Por qué se usa $R+h$ en las ecuaciones y qué papel cumple la gravedad en una órbita circular?**

> [!success]- Mostrar explicación
> La ley gravitatoria usa la distancia entre centros; por eso el radio orbital es $r=R+h$. En una órbita circular ideal, la gravedad es la fuerza radial neta que proporciona la aceleración centrípeta. No se agrega una fuerza centrípeta aparte.

**3. ¿Por qué la rapidez de escape desde un radio dado es mayor que la rapidez orbital circular en ese mismo radio?**

> [!success]- Mostrar explicación
> La órbita circular requiere $v_{orb}=\sqrt{GM/r}$ y deja energía total negativa, $E=-GMm/(2r)$. Escapar exige llegar al infinito con rapidez final nula, donde se toma $U=0$; al igualar la energía inicial a cero resulta $v_{esc}=\sqrt{2GM/r}=\sqrt2\,v_{orb}$.

**4. ¿Cuándo puedes usar una razón de la tercera ley de Kepler para comparar dos órbitas?**

> [!success]- Mostrar explicación
> Cuando ambos cuerpos orbitan la misma masa central y se puede despreciar la masa de cada satélite frente a ella. La constante $4\pi^2/(GM)$ es entonces común y se cancela: $T^2\propto r^3$ para órbitas circulares, o $T^2\propto a^3$ usando el semieje mayor en órbitas elípticas.

**Comprobación práctica:** marca el avance cuando puedas responder las cuatro preguntas sin abrir sus explicaciones, resolver los diez ejercicios numerados y completar los cuatro complementarios de prioridad alta (C2, C4, C6 y C7) sin abrir primero las pistas.

- [ ] Completé la autoevaluación sin ayuda.
- [ ] Resolví los diez ejercicios numerados sin abrir primero las pistas.
- [ ] Resolví los complementarios de prioridad alta C2, C4, C6 y C7.

**Procedencia y límites:** [[Recursos de estudio/Fuentes y cobertura/Fuentes Zotero y probabilidad]] · Las páginas de consulta de gravitación se detallan en las notas de conceptos, fórmulas y resoluciones.
