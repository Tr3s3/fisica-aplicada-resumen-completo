---
tags: [fisica-aplicada, teoria, lectura-activa, gravitacion]
aliases: [Teoría breve de gravitación y órbitas, Lectura activa de gravitación y órbitas]
---

# Guía breve — Gravitación y órbitas

> [!info] Cómo trabajar esta nota
> Lee un bloque por vez (5–10 minutos). Al terminar, cierra la nota y explica con tus palabras qué situación describe y por qué corresponde esa relación. Contesta la pregunta de comprobación sin desplegar su explicación y pasa enseguida al ejercicio enlazado. Intenta plantearlo antes de mirar la pista o la resolución.

**Profundizar:** [[Unidades/01 - Gravitación y órbitas/Teoría/01 - Conceptos de gravitación y órbitas|contexto y deducciones]] · [[Unidades/01 - Gravitación y órbitas/Teoría/01 - Fórmulas aplicadas de gravitación y órbitas|fórmulas aplicadas]] · [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicios]] · [[Unidades/01 - Gravitación y órbitas/Resoluciones/01 - Gravitación y órbitas|resoluciones paso a paso]]

## Orientación rápida: ¿qué bloque leer?

| Si el enunciado pregunta por… | Lee |
|---|---|
| Fuerza entre masas, campo en un punto o varias fuentes | [[#G1. De las masas al campo y la fuerza]] |
| Peso o gravedad en la superficie y a cierta altura | [[#G2. Peso y distancia al centro]] |
| Rapidez, período o aceleración de un satélite en órbita | [[#G3. Movimiento circular y órbitas]] |
| Lectura de una balanza en el ecuador de un planeta que rota | [[#G4. Qué registra la balanza en el ecuador]] |
| Energía, caída o rapidez de escape | [[#G5. Energía gravitatoria y escape]] |
| Comparación entre períodos y radios orbitales | [[#G6. Comparar órbitas con Kepler]] |

## G1. De las masas al campo y la fuerza

### La idea física

Dos masas se atraen a lo largo de la línea que las une. La fuerza sobre cada una tiene el mismo módulo y sentido opuesto, como exige la tercera ley de Newton. La ley se llama **universal** porque describe la interacción entre cualquier par de masas, en cualquier lugar dentro del modelo newtoniano. La constante $G$ también es universal: fija la intensidad de esa interacción y tiene el mismo valor para todos esos pares.

![[imagenes/ley-gravitacion-dos-masas-libro.png]]

### De la interacción al campo

Conviene separar dos preguntas:

1. **¿Qué produce la masa fuente $M$ en este punto?** Su campo gravitatorio.
2. **¿Qué fuerza siente un objeto de masa $m$ colocado allí?** El campo multiplicado por esa masa.

Para dos masas separadas por una distancia $r$ entre sus centros, el módulo de la fuerza es

$$
F_g=G\frac{Mm}{r^2}.
$$

Si el vector unitario $\hat r$ apunta desde la fuente hacia el punto donde está el objeto, la gravedad apunta al revés, hacia la fuente. Por eso

$$
\vec g=-G\frac{M}{r^2}\hat r,
\qquad
\vec F_g=m\vec g.
$$

El campo $\vec g$ describe la fuente y el punto, no una masa de prueba particular: al calcularlo, la masa de prueba se divide y se cancela. La fuerza sí depende de la masa del objeto porque $F_g=mg$. Por eso, dos objetos de distinta masa colocados por separado en el mismo campo tienen fuerzas distintas, pero la misma aceleración gravitatoria si la gravedad es la única fuerza relevante. En cambio, cuando se estudia el par de cuerpos que se atraen mutuamente, sus fuerzas son iguales y opuestas y sus aceleraciones pueden ser distintas: cada aceleración es $a=F/m$.

![[imagenes/campo-gravitatorio.svg]]

Si hay varias fuentes, calcula el campo que aporta cada una y suma las flechas: $\vec g_{\text{total}}=\sum_i\vec g_i$. Después, si piden la fuerza sobre un objeto concreto, usa $\vec F=m\vec g_{\text{total}}$. Considerar solo un par de cuerpos es una aproximación del problema: se omiten las demás fuentes cuando su efecto puede despreciarse para la pregunta planteada.

**Para reconocer el método:** si piden una fuerza, incluye la masa del objeto afectado; si piden campo o aceleración gravitatoria, calcula por unidad de masa. Dibuja las direcciones antes de sumar. Para una esfera simétrica observada desde fuera, mide $r$ desde su centro y usa su masa total.

**Comprueba:** ¿por qué dos masas de prueba reciben fuerzas diferentes en el mismo punto, pero tienen la misma aceleración gravitatoria?

> [!success]- Explicación después de intentar
> El campo en el punto es el mismo para ambas. Como $F=mg$, la masa mayor recibe más fuerza; pero al calcular $a=F/m$, esa misma masa se cancela y queda $a=g$ (si actúa solo la gravedad).

**Pasa a práctica:** [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicios 1–2 y 8; complementarios C1–C3]].

## G2. Peso y distancia al centro

El **peso** es la fuerza gravitatoria sobre el objeto: $W=mg$. La masa del objeto no cambia al trasladarlo, pero el campo $g$ sí cambia con la distancia al centro del planeta. Para una fuente esférica vista desde fuera,

$$
g(r)=\frac{GM}{r^2},
\qquad
W(r)=m\frac{GM}{r^2}.
$$

El radio $r$ se mide desde el **centro** del planeta. Si el objeto está a una altura $h$ sobre la superficie de radio $R$, entonces $r=R+h$; la altura por sí sola no es la distancia que va en la fórmula.

Para comparar el campo en superficie ($r=R$) con el de una altura $h$, dividimos las expresiones. Se cancelan $G$ y $M$:

$$
\frac{g(h)}{g(0)}
=\frac{GM/(R+h)^2}{GM/R^2}
=\left(\frac{R}{R+h}\right)^2.
$$

La razón compara el valor de arriba con el de abajo. Como $R+h$ es mayor que $R$, resulta menor que uno: el campo disminuye al alejarse. Si se duplica la distancia al centro, el campo queda en la cuarta parte. Para el mismo objeto, los pesos guardan esa misma razón porque la masa $m$ se cancela.

![[imagenes/orbita-satelite.svg]]

**Para reconocer el método:** identifica si el dato es una altura o un radio desde el centro. Si comparas dos pesos del mismo objeto, usa la razón para evitar calcular la masa; convierte las longitudes a unidades compatibles.

**Comprueba:** un satélite pasa de la superficie, a distancia $R$ del centro, a una órbita de radio $2R$. ¿Su peso queda en la mitad o en la cuarta parte?

> [!success]- Explicación después de intentar
> En la cuarta parte. El peso es proporcional a $g$, y $g\propto1/r^2$: al reemplazar $r$ por $2r$, el denominador se multiplica por cuatro.

**Pasa a práctica:** [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicios 3–4 y complementarios C4–C5]].

## G3. Movimiento circular y órbitas

### Por qué hay aceleración aunque la rapidez sea constante

La **rapidez** indica cuánto recorre un objeto por unidad de tiempo; no dice hacia dónde se mueve. La **velocidad** sí incluye dirección. En una circunferencia, la velocidad instantánea es tangente al camino. Aunque su módulo —la rapidez $v_t$— permanezca constante, su dirección cambia continuamente; cambiar la velocidad significa tener aceleración.

En un intervalo pequeño, la dirección de la velocidad gira un ángulo $\Delta\theta$. Los triángulos formados por las dos velocidades y por su cambio son semejantes, así que $\Delta v\approx v_t\Delta\theta$. El arco recorrido cumple $\Delta s\approx r\Delta\theta$ (con el ángulo en radianes). Al dividir por $\Delta t$ y hacer el intervalo cada vez más pequeño, $\Delta s/\Delta t$ tiende a $v_t$:

$$
a_c=\lim_{\Delta t\to0}\frac{\Delta v}{\Delta t}
=\frac{v_t}{r}\lim_{\Delta t\to0}\frac{\Delta s}{\Delta t}
=\frac{v_t^2}{r}.
$$

Esta aceleración apunta al centro y cambia la **dirección** de la velocidad. No es una fuerza nueva: la segunda ley dice que la fuerza neta hacia el centro debe ser $F_{\text{radial}}=ma_c$.

![[imagenes/v-vt-ac-movimiento-circular.svg]]

### Aplicación a una órbita circular

En una órbita circular ideal, la gravedad es la fuerza radial que mantiene al satélite en su trayectoria. Igualamos la fuerza gravitatoria con la fuerza neta requerida para curvar el movimiento:

$$
G\frac{Mm}{r^2}=m\frac{v_t^2}{r}
\quad\Longrightarrow\quad
v_{\text{orb}}=v_t=\sqrt{\frac{GM}{r}}.
$$

La masa del satélite se cancela porque tanto la fuerza gravitatoria como la respuesta del movimiento son proporcionales a $m$. Una vuelta recorre una circunferencia $2\pi r$; por eso el período —tiempo de una vuelta— es $T=2\pi r/v_t$.

**Para reconocer el método:** si piden rapidez orbital, usa que la gravedad proporciona la aceleración centrípeta; si piden período, relaciona una vuelta ($2\pi r$) con la rapidez. Usa el radio medido desde el centro, no la altura sobre la superficie.

**Comprueba:** ¿cómo puede haber aceleración si la rapidez no cambia, y hacia dónde apunta?

> [!success]- Explicación después de intentar
> La velocidad cambia de dirección aunque conserve su módulo. Su cambio apunta hacia el centro; por eso la aceleración centrípeta también apunta allí.

**Pasa a práctica:** [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicio 5: rapidez y período; luego sus partes de energía y escape; y complementario C6]].

## G4. Qué registra la balanza en el ecuador

En el ecuador de un planeta que rota, una persona quieta respecto del suelo también se mueve en una circunferencia alrededor del eje del planeta. Vista desde un marco que no gira con el planeta, necesita aceleración hacia el centro: $a_c=\omega^2R$, donde $\omega=2\pi/T$.

Sobre la persona actúan dos fuerzas radiales: el peso $mg$ hacia el centro y la fuerza normal $N$ de la balanza hacia afuera. Tomamos hacia el centro como positivo. La segunda ley radial queda

$$
mg-N=m\omega^2R
\quad\Longrightarrow\quad
\frac{N}{m}=g-\omega^2R.
$$

La gravedad $g=GM/R^2$ es el campo gravitatorio local. La balanza no mide ese campo ni la atracción gravitatoria por separado: mide la fuerza normal $N$ que ejerce sobre la persona. Por eso $N/m$ es la **gravedad efectiva** o peso aparente por unidad de masa en este caso. Al aumentar la rapidez de rotación, aumenta la aceleración centrípeta requerida y disminuye la lectura de la balanza en el ecuador.

![[imagenes/gravedad-rotacion-jupiter.svg]]

**Para reconocer el método:** dibuja las fuerzas y elige un sentido positivo antes de aplicar Newton. No agregues una “fuerza centrípeta” aparte; $ma_c$ es el resultado neto de las fuerzas radiales.

**Comprueba:** si el planeta rotara más rápido, ¿aumentaría o disminuiría la normal que ejerce la balanza?

> [!success]- Explicación después de intentar
> Disminuiría: $N/m=g-\omega^2R$. La gravedad sigue apuntando hacia dentro y la balanza aporta la fuerza hacia fuera; su diferencia produce la aceleración hacia el centro.

**Pasa a práctica:** [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicio 9]].

## G5. Energía gravitatoria y escape

La energía mecánica es la suma de la energía cinética, $K=\frac12mv^2$, asociada al movimiento, y la potencial $U$, asociada a la posición dentro de una interacción: $E=K+U$. Si solo actúa la gravedad, la suma se conserva. Al elegir $U=0$ en el infinito, la energía potencial gravitatoria a distancia $r$ del centro queda

$$
U(r)=-\frac{GMm}{r}.
$$

El signo negativo indica que la energía potencial está por debajo del cero elegido en el infinito. Si la **energía mecánica total** también es negativa, el objeto está ligado: hace falta aportarle energía para que escape. La **rapidez de escape mínima** es la rapidez inicial que alcanza justo el límite de escape, llegando al infinito con rapidez final tendiendo a cero. En ese caso límite, tanto la energía cinética final como la potencial final son cero. Por conservación, la energía inicial también debe sumar cero:

$$
\underbrace{\frac12m v_{\text{esc}}^2}_{\text{energía cinética inicial}}+
\underbrace{\left(-\frac{GMm}{r}\right)}_{\text{energía potencial inicial}}
=0
\quad\Longrightarrow\quad
\frac12m v_{\text{esc}}^2=\frac{GMm}{r}.
$$

La masa $m$ aparece en ambos lados y se cancela. Multiplicando por $2$ y tomando la raíz positiva (la rapidez no puede ser negativa), queda $v_{\text{esc}}=\sqrt{2GM/r}$.

La energía cinética que el cuerpo ya tiene cuenta dentro de ese balance: la rapidez de escape es el umbral que debe tener inicialmente en $r$, no una cantidad que siempre se suma a la rapidez que ya lleva. Si el objeto ya se mueve, usa su rapidez inicial en $K_i+U_i=K_f+U_f$. “Rapidez” es el módulo de la velocidad y no incluye dirección.

**Para reconocer el método:** para una caída o un lanzamiento entre grandes distancias usa $U=-GMm/r$ y escribe la energía del estado inicial igual a la del final. Cerca de la superficie, si $h$ es un pequeño cambio de altura y $g$ casi no varía, puede usarse $\Delta U\approx mgh$.

**Comprueba:** en el escape mínimo, ¿con qué rapidez llega el objeto al infinito y por qué eso fija la energía final?

> [!success]- Explicación después de intentar
> Llega con rapidez que tiende a cero. Allí $K_f\to0$ y, por la elección de referencia, $U_f=0$. Por tanto, la energía final límite es cero; por conservación, la energía inicial debe ser cero también.

**Pasa a práctica:** [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicio 5: energía y escape; ejercicio 10 y complementarios C7–C8]].

## G6. Comparar órbitas con Kepler

Para una órbita circular, la rapidez tangencial $v_t$ viene de igualar gravedad y aceleración centrípeta; el período es el tiempo que se tarda en recorrer la vuelta: $T=2\pi r/v_t$. Al combinar esas dos relaciones se obtiene

$$
T^2=\frac{4\pi^2}{GM}r^3,
\qquad
\frac{T^2}{r^3}=\frac{4\pi^2}{GM}.
$$

La relación muestra que, cuanto mayor es la órbita, más largo es su período. Para **comparar dos cuerpos que orbitan la misma masa central**, el lado derecho es común y se cancela:

$$
\frac{T_1^2}{T_2^2}=\frac{r_1^3}{r_2^3}.
$$

En estos ejercicios, $r$ es el radio de una órbita circular o el radio medio usado en la aproximación. En una órbita elíptica, la forma general usa el semieje mayor $a$ en lugar de $r$. Si piden la masa central y se conocen el radio y el período, despeja $M=4\pi^2r^3/(GT^2)$.

**Para reconocer el método:** usa razones si comparas órbitas alrededor del mismo astro; si las masas centrales no son iguales, no canceles $M$. Mantén las unidades de período y distancia consistentes.

**Comprueba:** ¿qué condición permite cancelar el lado derecho al comparar dos órbitas?

> [!success]- Explicación después de intentar
> Deben orbitar la misma masa central $M$. Así $4\pi^2/(GM)$ tiene el mismo valor para ambas órbitas y se cancela en la razón.

**Pasa a práctica:** [[Unidades/01 - Gravitación y órbitas/Ejercicios/01 - Gravitación y órbitas|ejercicios 6–7 y complementario C6]].

---

## Si todavía queda una duda

Vuelve al concepto o a la fórmula señalados en [[Recursos de estudio/Teoría general/00 - Teoría esencial para practicar|la ruta general]]. Registra la duda en [[Recursos de estudio/Práctica/00 - Método y registro]] y vuelve a intentar el ejercicio sin la pista.
