---
tags: [fisica-aplicada, primer-parcial, modelo-2026, termodinamica, optica, resoluciones]
aliases: [Primer parcial 2026 resuelto paso a paso]
---

# Primer parcial 2026: resoluciones para aprender

Esta nota desarrolla los cinco ejercicios de la **clave de corrección de Física Aplicada 2026**. Explica cómo reconocer el modelo, plantear las ecuaciones, despejar, sustituir y comprobar cada resultado.

**Para intentar primero:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido|enunciados reconstruidos]]. Los encabezados E1–E5 tienen el mismo orden en ambos archivos.

## Índice

1. [[#E1. Calorimetría y cambio de fase|E1: decidir la fusión y hacer el balance]].
2. [[#E2. Expansión adiabática y primera ley|E2: presión, trabajo, energía y temperatura]].
3. [[#E3. Máquina térmica y límite de Carnot|E3: eficiencia medida y máximo permitido]].
4. [[#E4. Refracción y reflexión interna total|E4: crítico y condición de confinamiento]].
5. [[#E5. Sistema de dos lentes convergentes|E5: dos imágenes y dos aumentos]].
6. [[#Resultados para autocorregir|Resultados para autocorregir]].
7. [[#Cómo se reconstruyeron los enunciados|Fuentes, inferencias y diferencias con la transcripción]].

## E1. Calorimetría y cambio de fase

**Enunciado:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido#E1. Calorimetría y cambio de fase|volver a E1]].

### Reconocer el problema y ordenar los datos

El sistema incluye **aluminio + agua inicial + hielo**. El recipiente no intercambia calor con el ambiente y se desprecia su capacidad térmica y el trabajo. La energía que unas partes pierden la reciben las otras.

$$
m_{\mathrm{Al}}=0.80\,\mathrm{kg},\quad T_{\mathrm{Al},i}=180\,^\circ\mathrm C,
\qquad m_w=0.50\,\mathrm{kg},\quad T_{w,i}=20\,^\circ\mathrm C,
$$

$$
m_i=0.10\,\mathrm{kg},\quad T_{i,i}=0\,^\circ\mathrm C.
$$

Usaremos $c_{\mathrm{Al}}=900\,\mathrm{J/(kg\,K)}$, $c_w=4186\,\mathrm{J/(kg\,K)}$ y $L_f=334000\,\mathrm{J/kg}$.

Dos relaciones cumplen funciones diferentes: **$Q=mc\Delta T$** cuando cambia la temperatura sin cambiar de fase, y **$Q=mL_f$** cuando el hielo se funde a cero. Durante la fusión no aumenta la temperatura.

Las diferencias de temperatura tienen el mismo valor numérico en °C y en K. Aquí puedes usar $180-T_f$ o $T_f-20$ en °C junto con esas capacidades térmicas.

### a. Decidir si se funde todo el hielo

Antes de despejar una temperatura, hay que decidir si quedará hielo. Si coexistieran hielo y agua en equilibrio, la temperatura sería cero. Tomamos ese estado como referencia y preguntamos cuánta energía podrían entregar los cuerpos inicialmente calientes al llegar a él.

El aluminio podría ceder:

$$E_{\mathrm{Al},0}=m_{\mathrm{Al}}c_{\mathrm{Al}}(180-0)=(0.80)(900)(180)=129600\,\mathrm J.$$

El agua inicial podría ceder:

$$E_{w,0}=m_wc_w(20-0)=(0.50)(4186)(20)=41860\,\mathrm J.$$

En total:

$$E_{\mathrm{disp}}=129600+41860=171460\,\mathrm J=171.46\,\mathrm{kJ}.$$

Fundir el hielo requiere:

$$E_{\mathrm{fusión}}=m_iL_f=(0.10)(334000)=33400\,\mathrm J=33.4\,\mathrm{kJ}.$$

Como **$171.46>33.4\,\mathrm{kJ}$**, alcanza para fundirlo por completo y sobra energía: el equilibrio final estará por encima de cero.

> [!important] El enfriamiento hasta cero es una comparación hipotética
> Sirve para decidir si alcanza la energía. No afirma que el agua inicial efectivamente se enfríe hasta cero durante el proceso. La temperatura final decidirá si esa agua gana o pierde calor en el balance real.

### b. Plantear el balance y hallar la temperatura final

Ya sabemos que todo el hielo se transforma en agua. Separamos tres historias térmicas:

| Parte | Proceso hasta el equilibrio | Calor con signo |
|---|---|---|
| Aluminio | Se enfría desde $180\,^\circ\mathrm C$ | $m_{\mathrm{Al}}c_{\mathrm{Al}}(T_f-180)$ |
| Agua inicial | Cambia desde $20\,^\circ\mathrm C$ | $m_wc_w(T_f-20)$ |
| Hielo | Se funde a cero y su agua llega a $T_f$ | $m_iL_f+m_ic_wT_f$ |

Con $Q>0$ para una parte que recibe calor, la conservación de energía exige:

$$Q_{\mathrm{Al}}+Q_w+Q_i=0.$$

Pasando la pérdida del aluminio al otro miembro:

$$m_{\mathrm{Al}}c_{\mathrm{Al}}(180-T_f)=m_iL_f+m_wc_w(T_f-20)+m_ic_wT_f.$$

**No juntes las dos masas de agua como si empezaran a la misma temperatura:** una parte ya era líquida a 20 °C y la otra aparece al fundirse el hielo a cero.

Sustituyendo los productos $mc$, en $\mathrm{J/K}$:

$$720(180-T_f)=33400+2093(T_f-20)+418.6T_f.$$

Distribuye y reúne los términos:

$$129600-720T_f=33400+2093T_f-41860+418.6T_f,$$

$$129600-720T_f=-8460+2511.6T_f,$$

$$138060=3231.6T_f.$$

Por tanto:

$$\boxed{T_f=\frac{138060}{3231.6}=42.7219\,^\circ\mathrm C\approx42.72\,^\circ\mathrm C}.$$

La solución confirma la hipótesis de fusión total. Además, $T_f>20\,^\circ\mathrm C$: el agua inicial **recibe** calor en el estado final.

### c. Calor cedido por el aluminio

Para el aluminio, la temperatura final es menor que la inicial:

$$Q_{\mathrm{Al}}=m_{\mathrm{Al}}c_{\mathrm{Al}}(T_f-180).$$

$$Q_{\mathrm{Al}}=(0.80)(900)(42.7219-180)=-98840.3\,\mathrm J.$$

Así, **el aluminio cede $98.84\,\mathrm{kJ}$**. Si expresas el calor intercambiado con signo, escribe **$Q_{\mathrm{Al}}=-98.84\,\mathrm{kJ}$**.

### d. Principio físico y comprobación

Se aplica la **conservación de la energía**: en el conjunto aislado, sin trabajo apreciable, la suma algebraica de los calores internos es cero. Que el conjunto no reciba calor exterior no impide que sus partes intercambien calor entre sí.

Podemos comprobar el resultado con las energías recibidas:

$$Q_w=2093(42.7219-20)\approx47.56\,\mathrm{kJ},$$

$$Q_i=33.4+\frac{418.6(42.7219)}{1000}\approx51.28\,\mathrm{kJ}.$$

Su suma, $47.56+51.28=98.84\,\mathrm{kJ}$, coincide con la pérdida del aluminio. Al final hay **$0.60\,\mathrm{kg}$ de agua y no queda hielo**.

**Qué aprender de este ejercicio:** primero decide la fase final; después escribe el balance siguiendo la historia de cada sustancia. Si obtienes una temperatura negativa al suponer fusión total, revisa esa hipótesis.

**Qué valora la clave:** comparación de energías (5), balance y temperatura (5), calor cedido (5), conservación (2) y presentación con unidades, signos y conclusión (3).

## E2. Expansión adiabática y primera ley

**Enunciado:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido#E2. Expansión adiabática y primera ley|volver a E2]].

### Reconocer el proceso y preparar las unidades

El sistema es el **gas**. “Adiabática” significa $Q=0$. El gas puede realizar trabajo moviendo el pistón, por lo que su energía interna y su temperatura pueden cambiar.

Además, es gas ideal, la expansión es reversible y $\gamma=1.40$ es constante. Estas condiciones permiten usar **$pV^\gamma=\mathrm{constante}$**; $Q=0$ por sí solo no basta para esa relación.

$$p_1=5.00\times10^5\,\mathrm{Pa},\qquad V_1=2.00\times10^{-3}\,\mathrm{m^3},\qquad V_2=6.00\times10^{-3}\,\mathrm{m^3}.$$

El cociente $V_1/V_2=1/3$ puede obtenerse usando ambos volúmenes en litros. Para productos $pV$ usa metros cúbicos: **$\mathrm{Pa\,m^3}=\mathrm J$**.

La convención elegida es $\Delta U=Q-W$, con $W>0$ cuando el gas realiza trabajo.

### a. Presión final

Relaciona los dos estados mediante la adiabática reversible:

$$p_1V_1^\gamma=p_2V_2^\gamma.$$

Divide por $V_2^\gamma$:

$$p_2=p_1\left(\frac{V_1}{V_2}\right)^\gamma.$$

Sustituye:

$$p_2=(5.00\times10^5\,\mathrm{Pa})\left(\frac{2.00}{6.00}\right)^{1.40}.$$

$$\boxed{p_2=1.07399\times10^5\,\mathrm{Pa}\approx1.074\times10^5\,\mathrm{Pa}}.$$

Es menor que la inicial: el gas se expandió y también se enfrió.

### b. Trabajo realizado por el gas

La presión cambia durante la expansión, así que no corresponde multiplicar $p_1$ por $V_2-V_1$. El trabajo es el área bajo la curva $p(V)$:

$$W=\int_{V_1}^{V_2}p(V)\,dV.$$

Como $pV^\gamma=K$, con $K$ constante, sustituye $p=KV^{-\gamma}$:

$$W=\frac{K}{1-\gamma}\left(V_2^{1-\gamma}-V_1^{1-\gamma}\right).$$

En cada extremo, $KV^{1-\gamma}=pV$. Reordenando:

$$\boxed{W=\frac{p_1V_1-p_2V_2}{\gamma-1}}.$$

Ahora calcula los productos sin redondear demasiado $p_2$:

$$p_1V_1=(5.00\times10^5)(2.00\times10^{-3})=1000\,\mathrm J,$$

$$p_2V_2=(1.07399\times10^5)(6.00\times10^{-3})\approx644.394\,\mathrm J.$$

Entonces:

$$\boxed{W=\frac{1000-644.394}{1.40-1}=+889.015\,\mathrm J\approx+889\,\mathrm J}.$$

El signo es positivo porque el gas empuja el pistón y entrega energía mecánica al exterior.

### c. Cambio de energía interna

Usa la primera ley con la convención fijada:

$$\Delta U=Q-W.$$

Como no entra calor:

$$\boxed{\Delta U=0-889=-889\,\mathrm J}.$$

El trabajo se hace a costa de la energía interna del gas. El signo negativo describe una disminución, no una energía interna absoluta negativa.

### d. Temperatura final

La relación de temperaturas se obtiene combinando $pV^\gamma=\mathrm{constante}$ con $pV=nRT$ para una cantidad fija de gas:

$$pV^\gamma=(nRT)V^{\gamma-1}=\mathrm{constante}
\quad\Longrightarrow\quad TV^{\gamma-1}=\mathrm{constante}.$$

Por tanto:

$$T_2=T_1\left(\frac{V_1}{V_2}\right)^{\gamma-1}.$$

$$\boxed{T_2=(600\,\mathrm K)\left(\frac{2.00}{6.00}\right)^{0.40}=386.64\,\mathrm K\approx386.6\,\mathrm K}.$$

**Control físico:** $V_2>V_1$, $W>0$, $\Delta U<0$, $T_2<T_1$ y $p_2<p_1$. Todas las conclusiones son coherentes.

**Control numérico independiente:** por gas ideal, $T_2/T_1=p_2V_2/(p_1V_1)=644.394/1000\approx0.6444$, igual que $386.64/600$.

**Qué aprender:** adiabático fija el calor; la primera ley conecta trabajo y energía interna. Las relaciones adiabáticas aportan la conexión entre los estados.

**Qué valora la clave:** presión, trabajo, energía interna y temperatura, 5 puntos cada uno.

## E3. Máquina térmica y límite de Carnot

**Enunciado:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido#E3. Máquina térmica y límite de Carnot|volver a E3]].

### Separar el funcionamiento real del máximo posible

El sistema es la máquina durante **un ciclo completo**. Vuelve al mismo estado, de modo que $\Delta U_{\mathrm{ciclo}}=0$. Usa $Q_H>0$ para el calor que absorbe, $Q_L>0$ para la magnitud que cede y $W>0$ para el trabajo que entrega.

El reparto de energía es:

$$\text{foco caliente}\xrightarrow{Q_H}\text{máquina}\xrightarrow{W}\text{exterior},\qquad \text{máquina}\xrightarrow{Q_L}\text{foco frío}.$$

El calor absorbido es $2500\,\mathrm J$ y el trabajo real es $850\,\mathrm J$ por ciclo. Estas energías describen lo que la máquina hace. Las temperaturas fijan un techo que ninguna máquina entre esos focos puede superar.

### a. Calor cedido al foco frío

La primera ley para el ciclo da:

$$0=Q_H-Q_L-W.$$

Despeja:

$$\boxed{Q_L=Q_H-W=2500-850=1650\,\mathrm{J/ciclo}}.$$

El valor es la magnitud del calor cedido. Si se usara calor con signo respecto de la máquina, ese intercambio sería $-1650\,\mathrm J$.

### b. Eficiencia térmica real

La eficiencia es la fracción del calor recibido que termina como trabajo útil:

$$\eta_{\mathrm{real}}=\frac{W}{Q_H}.$$

$$\boxed{\eta_{\mathrm{real}}=\frac{850}{2500}=0.340=34.0\%}.$$

De cada 100 J absorbidos, 34 J salen como trabajo y 66 J se ceden al foco frío. No calcules esta eficiencia con las temperaturas: la máquina real no se ha declarado reversible.

### c. Eficiencia máxima entre esos focos

La segunda ley fija el máximo de Carnot, alcanzable por un motor reversible ideal:

$$\eta_C=1-\frac{T_L}{T_H}.$$

La razón exige **temperaturas absolutas**:

$$T_H=600+273.15=873.15\,\mathrm K,\qquad T_L=25+273.15=298.15\,\mathrm K.$$

$$\boxed{\eta_C=1-\frac{298.15}{873.15}=0.65854\approx65.9\%}.$$

La eficiencia real, $34.0\%$, está por debajo del máximo; pasa este control de la segunda ley.

### d. Evaluar la propuesta de 1900 J por ciclo

Si absorbiera los mismos $2500\,\mathrm J$ y entregara $1900\,\mathrm J$, necesitaría:

$$\eta_{\mathrm{propuesta}}=\frac{1900}{2500}=0.760=76.0\%.$$

Compara con el máximo de los mismos focos:

$$76.0\%>65.9\%.$$

**La propuesta es imposible entre esas temperaturas: viola la segunda ley.**

La primera ley, por sí sola, no la descarta: quedaría un rechazo positivo de $2500-1900=600\,\mathrm J$. Pero conservar energía no garantiza que una transformación respete el límite de Carnot.

Como comprobación añadida, el mayor trabajo permitido para ese calor de entrada es:

$$W_{\max}=\eta_CQ_H=(0.65854)(2500)\approx1646\,\mathrm{J/ciclo}.$$

Los $1900\,\mathrm J$ propuestos lo superan. Este cálculo es un control didáctico adicional; no se añade como otro inciso del examen reconstruido.

**Qué aprender:** la primera ley comprueba el balance de energía; la segunda fija una restricción adicional sobre cuánto calor puede convertirse en trabajo.

**Puntaje de la fuente:** declara 20 puntos, pero enumera cuatro apartados de 5 y agrega 2 de presentación, sumando 22. Además, rotula el último apartado como “e”. Aquí se normaliza a **d**, sin inventar una redistribución del puntaje.

## E4. Refracción y reflexión interna total

**Enunciado:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido#E4. Refracción y reflexión interna total|volver a E4]].

### Dibujar la interfaz y reconocer el sentido del rayo

El rayo viene del **vidrio**, de índice $n_v=1.52$, hacia el medio exterior. La incidencia de $55^\circ$ ya está medida desde la normal, así que no hay que tomar su complementario.

El agua tiene $n_a=1.33$ y el aire $n_{\mathrm{aire}}=1.00$. En ambos casos pasa de un índice mayor a otro menor: puede existir reflexión interna total, pero aún hay que comprobar el ángulo.

### Relación que permite resolver a y b

Snell conecta incidencia y transmisión:

$$n_v\sin\theta_i=n_{\mathrm{ext}}\sin\theta_t.$$

El ángulo crítico corresponde al límite $\theta_t=90^\circ$, es decir, transmisión rasante:

$$n_v\sin\theta_c=n_{\mathrm{ext}}\sin90^\circ
\quad\Longrightarrow\quad
\boxed{\theta_c=\arcsin\!\left(\frac{n_{\mathrm{ext}}}{n_v}\right)}.$$

La reflexión total requiere **$n_v>n_{\mathrm{ext}}$ y $\theta_i>\theta_c$**. En la igualdad estás en el umbral.

### a. ¿El rayo sale al agua?

Calculamos primero el crítico para poder comparar:

$$\theta_{c,\mathrm{agua}}=\arcsin\!\left(\frac{1.33}{1.52}\right)\approx61.04^\circ.$$

Como **$55^\circ<61.04^\circ$**, el rayo **emerge al agua**. No hay reflexión interna total.

Esto no obliga a que desaparezca la reflexión parcial: significa que existe un rayo transmitido. Como control opcional, Snell daría $\theta_t\approx69.42^\circ$, mayor que la incidencia, como corresponde al pasar a un índice menor.

### b. Ángulo crítico vidrio–agua

Es el valor ya usado para decidir el inciso anterior:

$$\boxed{\theta_{c,\mathrm{agua}}\approx61.04^\circ\text{ desde la normal}}.$$

Aunque a y b se preguntan en ese orden, puedes calcular el crítico una sola vez y usarlo para justificar ambas respuestas.

### c. Ángulo crítico vidrio–aire

Ahora cambia solamente el índice exterior:

$$\boxed{\theta_{c,\mathrm{aire}}=\arcsin\!\left(\frac{1.00}{1.52}\right)\approx41.14^\circ}.$$

Para la misma incidencia de $55^\circ$, ahora **$55^\circ>41.14^\circ$**: habría reflexión interna total. El rayo reflejado forma $55^\circ$ con la normal.

### d. Dónde es más fácil confinar la luz

Para que la luz permanezca dentro por reflexión total, su incidencia debe superar el crítico. Los intervalos son:

- Vidrio rodeado de agua: $61.04^\circ<\theta_i<90^\circ$.
- Vidrio rodeado de aire: $41.14^\circ<\theta_i<90^\circ$.

**Es más fácil confinarla con aire alrededor**, porque un intervalo angular mayor cumple la condición. El índice del vidrio sigue siendo el mismo; el cambio de exterior reduce el crítico.

**Control de todo el ejercicio:** $41.14^\circ<55^\circ<61.04^\circ$. La misma incidencia supera un crítico y queda por debajo del otro.

**Qué aprender:** identifica de dónde viene la luz y compara el ángulo con el crítico de esa interfaz. Un índice de salida menor es necesario, pero no suficiente.

**Qué valora la clave:** decisión de salida, crítico en agua, crítico en aire y justificación del confinamiento, 5 puntos cada uno.

**Si te cuesta reconocer los ángulos:** [[Unidades/06 - Óptica/Teoría/06 - Resumen práctico de Snell y ángulo crítico|resumen práctico de Snell y ángulo crítico]].

## E5. Sistema de dos lentes convergentes

**Enunciado:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido#E5. Sistema de dos lentes convergentes|volver a E5]].

### Preparar el eje y la convención de signos

La luz viaja de izquierda a derecha. Tomamos L1 en $x=0$, L2 en $x=50.0\,\mathrm{cm}$ y el objeto original en $x=-30.0\,\mathrm{cm}$, con altura $h_0=+4.00\,\mathrm{cm}$.

Para **cada lente**:

- $s>0$: objeto real del lado de llegada de la luz, aquí a la izquierda.
- $s'>0$: imagen real del lado de salida, aquí a la derecha; $s'<0$ indicaría imagen virtual a la izquierda.
- $f>0$: lente convergente.
- $m<0$: imagen invertida respecto de su propio objeto; $m>0$: derecha.

Las relaciones para lentes delgadas son:

$$\frac1f=\frac1s+\frac1{s'},\qquad m=-\frac{s'}s,\qquad h'=mh.$$

El despeje que usaremos dos veces es:

$$\frac1{s'}=\frac1f-\frac1s=\frac{s-f}{fs}
\quad\Longrightarrow\quad
\boxed{s'=\frac{fs}{s-f}}.$$

Todas las distancias pueden quedarse en cm. Los aumentos no tienen unidades.

### a. Imagen producida por L1

Para la primera lente, $s_1=+30.0\,\mathrm{cm}$ y $f_1=+10.0\,\mathrm{cm}$:

$$s'_1=\frac{f_1s_1}{s_1-f_1}=\frac{(10.0)(30.0)}{30.0-10.0}\,\mathrm{cm}.$$

$$\boxed{s'_1=+15.0\,\mathrm{cm}}.$$

Es una imagen **real**, a 15.0 cm a la derecha de L1. Su coordenada global es $x_{I_1}=+15.0\,\mathrm{cm}$; queda entre las lentes.

### b. Aumento y altura de la imagen intermedia

$$\boxed{m_1=-\frac{s'_1}{s_1}=-\frac{15.0}{30.0}=-0.500}.$$

$$\boxed{h_1=m_1h_0=(-0.500)(4.00\,\mathrm{cm})=-2.00\,\mathrm{cm}}.$$

El signo negativo indica que está invertida. Su tamaño es $2.00\,\mathrm{cm}$, la mitad del objeto original.

### c. Imagen final: volver a medir desde L2

La imagen de L1 es ahora el **objeto de L2**. No hay que sustituir de nuevo el objeto original: L2 recibe el haz que viene de la imagen intermedia.

Como L2 está en 50 cm y esa imagen en 15 cm:

$$\boxed{s_2=D-s'_1=50.0-15.0=+35.0\,\mathrm{cm}}.$$

El signo positivo indica que es un objeto real para L2: está a su izquierda y los rayos llegan a L2 divergiendo desde él.

> [!important] Distancia local y coordenada global
> $15\,\mathrm{cm}$ es la posición de la imagen medida desde L1. La distancia que entra en la ecuación de L2 es **$35\,\mathrm{cm}$**, medida desde L2. La misma posición física tiene referencias distintas en cada etapa.

Con $f_2=+15.0\,\mathrm{cm}$:

$$s'_2=\frac{f_2s_2}{s_2-f_2}=\frac{(15.0)(35.0)}{35.0-15.0}\,\mathrm{cm}.$$

$$\boxed{s'_2=+26.25\,\mathrm{cm}}.$$

La imagen final es real y queda a **26.25 cm a la derecha de L2**. Si se pide ubicarla respecto de L1:

$$\boxed{x_{I_f}=50.0+26.25=76.25\,\mathrm{cm}}.$$

Ahora calcula el aumento de la segunda etapa:

$$m_2=-\frac{s'_2}{s_2}=-\frac{26.25}{35.0}=-0.750.$$

La altura final se puede calcular desde la intermedia, $h_f=m_2h_1$. Para compararla con el objeto original, combina las dos etapas:

$$h_f=m_2(m_1h_0)=(m_1m_2)h_0.$$

Por eso los aumentos se **multiplican**:

$$\boxed{m_{\mathrm{total}}=m_1m_2=(-0.500)(-0.750)=+0.375}.$$

$$\boxed{h_f=(0.375)(4.00\,\mathrm{cm})=+1.50\,\mathrm{cm}}.$$

La imagen final es **real, derecha y reducida respecto del objeto original**. Es derecha porque hay dos inversiones: L1 invierte el objeto y L2 invierte la imagen intermedia. Respecto de esa imagen intermedia, la final sí está invertida.

### d. Construir el dibujo de rayos

Marca primero las posiciones obtenidas y los focos. Para L1: $F_1$ en $x=-10\,\mathrm{cm}$ y $F'_1$ en $x=+10\,\mathrm{cm}$. Para L2: $F_2$ en $x=35\,\mathrm{cm}$ y $F'_2$ en $x=65\,\mathrm{cm}$.

**Primera construcción:** desde la punta del objeto original, traza un rayo paralelo al eje que, al atravesar L1, pasa por su foco derecho. Traza otro por el centro óptico de L1, sin desviación. Su cruce está en $x=15\,\mathrm{cm}$ y altura $-2\,\mathrm{cm}$.

**Segunda construcción:** desde la punta de esa imagen intermedia, traza un rayo paralelo al eje hasta L2 y hazlo salir por el foco derecho de L2. Traza otro por el centro óptico de L2, sin desviación. Se cruzan 26.25 cm a su derecha, a altura $+1.50\,\mathrm{cm}$.

![[imagenes/primer-parcial-2026-dos-lentes.svg|850]]

*Construcción en dos paneles para este ejercicio. Cada panel muestra los dos rayos que permiten ubicar la imagen de una lente. El punto $I_1$ del primero se usa como objeto en el segundo. Las escalas horizontal y vertical son distintas; usa las cotas, no medidas sobre la figura.*

En un dibujo conjunto, recuerda que un rayo vuelve a refractarse cuando alcanza L2. El rayo que pasa por el centro de L1 no tiene por qué pasar por el centro de L2.

**Controles:** en L1, $s_1>2f_1$ y la imagen queda entre $f_1$ y $2f_1$. En L2, $s_2>2f_2$ y vuelve a quedar entre $f_2$ y $2f_2$. Cada etapa reduce e invierte; el producto de dos aumentos negativos es positivo y menor que uno.

**Qué aprender:** resuelve una lente por vez, vuelve a medir desde la siguiente y multiplica los aumentos. Una altura intermedia negativa sigue siendo un objeto real para L2: orientación y carácter real/virtual son propiedades diferentes.

**Qué valora la clave:** imagen de L1 (5), aumento y altura intermedios (5), resultado final (5) y rayos (5). La fuente rotula el último apartado como “f”; aquí corresponde al **d** de los enunciados.

## Resultados para autocorregir

| Ejercicio | Resultados centrales |
|---|---|
| E1 | Se funde todo; $T_f=42.72\,^\circ\mathrm C$; aluminio cede $98.84\,\mathrm{kJ}$; $Q_{\mathrm{Al}}<0$ |
| E2 | $p_2=1.074\times10^5\,\mathrm{Pa}$; $W=+889\,\mathrm J$; $\Delta U=-889\,\mathrm J$; $T_2=386.6\,\mathrm K$ |
| E3 | $Q_L=1650\,\mathrm J$; $\eta_{\mathrm{real}}=34.0\%$; $\eta_C=65.9\%$; propuesta de $76.0\%$ imposible |
| E4 | Agua: $\theta_c=61.04^\circ$, emerge; aire: $\theta_c=41.14^\circ$; confinamiento más fácil en aire |
| E5 | $s'_1=15.0\,\mathrm{cm}$; $m_1=-0.500$; $h_1=-2.00\,\mathrm{cm}$; $s_2=35.0\,\mathrm{cm}$; $s'_2=26.25\,\mathrm{cm}$; $m_{\mathrm{total}}=+0.375$; $h_f=+1.50\,\mathrm{cm}$ |

Para aprender de la corrección, identifica **el primer paso que no pudiste justificar**: elección de modelo, geometría, signos, despeje, unidades o cálculo. Vuelve a resolver desde ese paso con las respuestas tapadas y registra el error en [[Recursos de estudio/Práctica/00 - Método y registro]].

## Cómo se reconstruyeron los enunciados

Se leyeron las dos páginas de la [clave original](zotero://select/library/items/TZPNLWDL) y se contrastaron con la [transcripción de enunciados de 2026](zotero://select/library/items/BA354CLU). Las cifras de las soluciones anteriores coinciden con la clave dentro del redondeo.

**E1 necesita una reconstrucción propia.** La clave permite leer $180\,^\circ\mathrm C$ para el aluminio, $20\,^\circ\mathrm C$ para el agua, $0.10\,\mathrm{kg}$ de hielo y las energías hasta cero. Con las constantes de la transcripción:

$$m_{\mathrm{Al}}=\frac{129600}{900\cdot180}=0.80\,\mathrm{kg},$$

$$m_w\approx\frac{41900}{4186\cdot20}\approx0.50\,\mathrm{kg}.$$

Los 41.9 kJ están redondeados: una masa de 0.50 kg da 41.86 kJ. El balance de la clave incluye fusión y calentamiento del hielo fundido desde cero, por lo que se reconstruye **hielo inicialmente a cero**, recipiente despreciable y sin intercambio exterior. Es una versión consistente con la corrección, no una recuperación literal e inequívoca del enunciado perdido.

La transcripción anterior de E1 da aluminio a **160 °C**, menciona agua y después pregunta por hielo sin fijar el estado inicial. Esos datos no se mezclan con la versión de la clave a **180 °C**. Las variantes de aquella transcripción siguen en el banco de la unidad.

**E2–E5** conservan los datos y preguntas de la transcripción, comprobados con los resultados y procedimientos de la clave. Se hicieron explícitos los supuestos de gas ideal, lentes delgadas y convenciones necesarios para estudiar con claridad. Los controles numéricos adicionales y las explicaciones físicas son desarrollo didáctico de esta nota.

**Correspondencia con la práctica del vault:** E1 → T29 principal; E2 → T16 A; E3 → T31; E4 → O23; E5 → O24. Este archivo los reúne en el orden del parcial para practicarlo completo.

**Volver a practicar:** [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido|los cinco enunciados sin respuestas]].
