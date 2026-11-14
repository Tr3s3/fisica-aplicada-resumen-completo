---
tags: [fisica-aplicada, unidad-05, termodinamica, maquinas-termicas, resumen-practico]
aliases: [Cómo resolver ejercicios de máquinas térmicas]
---

# Máquinas térmicas: cómo resolver los ejercicios

**Objetivo:** reconocer qué entrega y qué recibe un motor, elegir el balance y resolver calor, trabajo, rendimiento, potencia, combustible y límite de Carnot. Los ejemplos usan los ejercicios del módulo; puedes consultar este resumen por apartados mientras practicas.

**Volver:** [[Unidades/05 - Termodinámica/Teoría/05 - Termodinámica|Termodinámica]] · **Profundizar:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#8. Motores y refrigeradores: objetivos y rendimientos|conceptos y origen de las fórmulas]].

## 1. El esquema que debes reconocer

Un **motor térmico** toma calor de una fuente caliente, convierte una parte en trabajo neto y entrega el resto a una fuente fría. Su sustancia de trabajo recorre un **ciclo**: vuelve al mismo estado al terminar.

![[imagenes/termodinamica-libro-flujo-motor.png|340]]

*Figura 20.3 del libro, cap. 20, página impresa 676; [PDF p. 4](zotero://open-pdf/library/items/S254CFZT?page=4). Sigue las tres flechas: calor recibido, trabajo entregado y calor rechazado.*

| Símbolo | Qué representa | Cómo usarlo aquí |
|---|---|---|
| $Q_H$ | Calor absorbido del foco caliente | Positivo, en J o kJ |
| $Q_C$ | Calor cedido al foco frío, con signo respecto del motor | Negativo; su magnitud $\lvert Q_C\rvert$ es positiva |
| $W$ | Trabajo **neto** entregado en el ciclo | Positivo para un motor |
| $e$ | Eficiencia o rendimiento térmico | Sin unidad; $25\%=0.25$ |
| $P$ | Potencia mecánica de salida | W o kW; $1\,\mathrm W=1\,\mathrm{J/s}$ |
| $T_H$, $T_C$ | Temperaturas de los focos caliente y frío | En K al usar Carnot; $H$: caliente, $C$: frío |

La primera ley, con trabajo positivo cuando lo realiza el sistema, es:

$$\Delta U=Q-W.$$

La energía interna $U$ depende del estado. Como al cerrar el ciclo se recupera el estado inicial, $\Delta U_{\mathrm{ciclo}}=0$. El calor neto es $Q_H-|Q_C|$, por lo que:

$$0=Q_H-|Q_C|-W
\quad\Longrightarrow\quad
\boxed{Q_H=W+|Q_C|}.$$

**Interpretación:** toda la energía recibida se reparte entre trabajo útil y calor rechazado. Si entran $100\,\mathrm J$ y se entregan $30\,\mathrm J$ de trabajo, salen $70\,\mathrm J$ hacia el foco frío.

> [!important] Dos decisiones antes de calcular
> En $Q_H=W+|Q_C|$, usa la **magnitud positiva** del calor rechazado. Además, $\Delta U=0$ corresponde al **ciclo completo**: en cada etapa puede haber un cambio de energía interna distinto de cero. Este balance describe funcionamiento cíclico sin acumulación neta de energía ni otras entradas o salidas consideradas en el modelo.

## 2. Elegir la fórmula y despejar

El rendimiento compara el trabajo obtenido con el calor recibido:

$$\boxed{e=\frac{W}{Q_H}
=1-\frac{|Q_C|}{Q_H}}.$$

La segunda forma sale de sustituir $W=Q_H-|Q_C|$ en la primera. Un rendimiento de $0.25$ significa que el 25% del calor recibido se convierte en trabajo y el 75% se rechaza.

| Datos del problema | Primer planteo | Después |
|---|---|---|
| Trabajo y calor rechazado | $Q_H=W+\lvert Q_C\rvert$ | $e=W/Q_H$ |
| Calor recibido y trabajo | $\lvert Q_C\rvert=Q_H-W$ | $e=W/Q_H$ |
| Rendimiento y calor recibido | $W=eQ_H$ | $\lvert Q_C\rvert=(1-e)Q_H$ |
| Rendimiento y trabajo | $Q_H=W/e$ | $\lvert Q_C\rvert=Q_H-W$ |
| Rendimiento y calor rechazado | $Q_H=\lvert Q_C\rvert/(1-e)$ | $W=eQ_H$ |
| Dos temperaturas y máquina de Carnot | $e_C=1-T_C/T_H$, con T en K | Usa ese rendimiento en el balance |
| Dos temperaturas y máquina real | Calcula el **máximo** $e_C$ | El rendimiento real requiere datos adicionales |

**El despeje que más suele costar:** si te dan el calor rechazado y el rendimiento,

$$e=1-\frac{|Q_C|}{Q_H}
\quad\Rightarrow\quad
(1-e)Q_H=|Q_C|
\quad\Rightarrow\quad
\boxed{Q_H=\frac{|Q_C|}{1-e}}.$$

**Método de resolución:**

1. Dibuja las tres flechas y anota qué energía representa cada dato.
2. Identifica si los datos son **por ciclo**, por un intervalo o **por segundo**.
3. Convierte porcentajes a fracción y unifica unidades.
4. Elige el planteo de la tabla y despeja antes de sustituir.
5. Calcula las magnitudes restantes con el balance.
6. Revisa $Q_H=W+|Q_C|$ y, si conoces los focos, compara con Carnot.

### Ejemplo básico — T19

Un motor entrega $W=2200\,\mathrm J$ y rechaza $|Q_C|=4300\,\mathrm J$ en cada ciclo. Se piden el calor recibido y el rendimiento.

$$Q_H=2200+4300=6500\,\mathrm J.$$

$$e=\frac{2200}{6500}=0.3385\approx33.9\%.$$

**Resultado:** recibe $6.50\,\mathrm{kJ/ciclo}$ y convierte aproximadamente un tercio en trabajo. El nombre «motor diésel» del enunciado no obliga a reconstruir un ciclo diésel: estos datos se resuelven con el balance general.

## 3. Carnot: rendimiento máximo y propuestas imposibles

La segunda ley establece un límite para un motor cíclico que intercambia calor únicamente con **dos focos de temperaturas constantes**, $T_H>T_C>0$:

$$\boxed{e_C=1-\frac{T_C}{T_H}},\qquad
\boxed{e_{\mathrm{real}}\le e_C},\qquad
\boxed{W_{\max}=e_CQ_H}.$$

Convierte primero: **$T(\mathrm K)=T({}^\circ\mathrm C)+273.15$**. Una razón de temperaturas exige valores absolutos; usar Celsius cambia el cociente.

**Por qué aparece esa razón:** en el ciclo reversible, el balance de entropía da $Q_H/T_H=|Q_C|/T_C$. Entonces $|Q_C|/Q_H=T_C/T_H$; al sustituir en la definición de rendimiento se obtiene $e_C$. La igualdad corresponde al reversible ideal; un motor irreversible entre esos focos queda por debajo.

> [!important] Distingue qué pide el enunciado
> **«Rendimiento real» con energías medidas:** $e=W/Q_H$.
>
> **«Rendimiento máximo» entre dos focos:** $e_C=1-T_C/T_H$.
>
> **«Motor de Carnot» o «motor reversible entre esos dos focos»:** puedes usar $e=e_C$ para calcular sus intercambios. La palabra «ideal» por sí sola también puede referirse a otro ciclo, como Otto: identifica cuál se especifica.

Si piden una temperatura **en Carnot**, despeja:

$$1-e_C=\frac{T_C}{T_H}
\quad\Rightarrow\quad
\boxed{T_C=(1-e_C)T_H},\qquad
\boxed{T_H=\frac{T_C}{1-e_C}}.$$

El resultado sale en K. Resta $273.15$ al final si lo piden en °C. Con una eficiencia real inferior a Carnot, estas igualdades no permiten determinar los focos.

### Ejemplo: máquina real y propuesta — T31

**Datos:** foco caliente a $600\,^\circ\mathrm C$, frío a $25\,^\circ\mathrm C$, entrada $Q_H=2500\,\mathrm J$ y trabajo real $W=850\,\mathrm J$ por ciclo. Se propone aumentar el trabajo a $1900\,\mathrm J$ manteniendo entrada y focos.

Primero se caracteriza la máquina real:

$$|Q_C|=2500-850=1650\,\mathrm J,\qquad
e_{\mathrm{real}}=\frac{850}{2500}=0.340=34.0\%.$$

Después se calcula el límite con las temperaturas en K:

$$T_H=873.15\,\mathrm K,\qquad T_C=298.15\,\mathrm K,$$

$$e_C=1-\frac{298.15}{873.15}=0.65854\approx65.9\%.$$

La propuesta exigiría:

$$e_{\mathrm{propuesta}}=\frac{1900}{2500}=0.760=76.0\%>e_C.$$

**Conclusión física:** la propuesta es imposible entre esos focos. Su balance de energía cerraría con $600\,\mathrm J$ rechazados, pero viola la segunda ley. También se ve al calcular:

$$W_{\max}=(0.65854)(2500\,\mathrm J)\approx1646\,\mathrm J<1900\,\mathrm J.$$

Una propuesta por debajo de Carnot es compatible con este límite; eso no demuestra que una máquina concreta pueda alcanzar ese rendimiento.

### Si preguntan por las etapas del ciclo de Carnot

Para una sustancia de trabajo modelada como gas ideal:

| Etapa, en orden | Qué ocurre | Signos y balance |
|---|---|---|
| Expansión isotérmica a $T_H$ | Absorbe calor del foco caliente | $Q>0$, $W>0$, $\Delta U=0$ |
| Expansión adiabática reversible | Baja de $T_H$ a $T_C$ | $Q=0$, $W>0$, $\Delta U<0$ |
| Compresión isotérmica a $T_C$ | Rechaza calor al foco frío | $Q<0$, $W<0$, $\Delta U=0$ |
| Compresión adiabática reversible | Sube de $T_C$ a $T_H$ | $Q=0$, $W<0$, $\Delta U>0$ |

En una adiabática puede cambiar la temperatura: **adiabático significa $Q=0$**. Consulta el [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer el ciclo de Carnot del libro|diagrama de Carnot y su lectura]] si necesitas seguir los cuatro estados.

## 4. Potencia, tiempo de ciclo y calor por segundo

La **energía** indica cuánto se transfiere; la **potencia** indica a qué ritmo. Para ciclos iguales de duración $\tau$, las tasas medias son:

$$\boxed{P=\frac{W_{\mathrm{ciclo}}}{\tau}},\qquad
\boxed{\tau=\frac{W_{\mathrm{ciclo}}}{P}}.$$

Si te dan frecuencia $f$ en ciclos por segundo: $f=1/\tau$ y $P=fW_{\mathrm{ciclo}}$. $\tau$ se mide en s y $f$ en $\mathrm{s^{-1}}$.

Dividiendo el balance y la definición de rendimiento por el mismo tiempo:

$$\dot Q_H=P+|\dot Q_C|,\qquad e=\frac{P}{\dot Q_H}.$$

Por tanto:

$$\boxed{\dot Q_H=\frac{P}{e}},\qquad
\boxed{|\dot Q_C|=\dot Q_H-P}.$$

El punto sobre $Q$ indica calor por unidad de tiempo. Las tasas se expresan en **J/s = W**, también cuando se trata de calor. Si son constantes, en un tiempo $t$ se transfieren $Q_H=\dot Q_Ht$ y $W=Pt$.

### Ejemplo: duración del ciclo — T20

**Datos:** $P=5.0\,\mathrm{kW}$, $e=0.25$ y $|Q_C|=8000\,\mathrm{J/ciclo}$. Primero hacen falta las energías por ciclo:

$$Q_H=\frac{8000}{1-0.25}=10666.7\,\mathrm{J/ciclo},$$

$$W=10666.7-8000=2666.7\,\mathrm{J/ciclo}.$$

Ahora se usa la potencia, convertida a $5000\,\mathrm{J/s}$:

$$\tau=\frac{2666.7\,\mathrm J}{5000\,\mathrm{J/s}}
\approx0.533\,\mathrm s\text{ por ciclo}.$$

**Control:** $2666.7/0.533\approx5000\,\mathrm W$. Dividir $Q_H$ por la potencia mecánica no daría el tiempo correcto: esa potencia corresponde a $W$.

**Variante por segundo — T32 A:** si $P=23\,\mathrm{kW}$ y $e=0.20$, entonces $\dot Q_H=23/0.20=115\,\mathrm{kW}$ y $|\dot Q_C|=115-23=92\,\mathrm{kW}$. Sin una energía por ciclo o su frecuencia, estos datos permiten hallar tasas, pero no la duración del ciclo.

## 5. Combustible: convertir el calor de entrada en masa

El **poder calorífico** $q_{\mathrm{comb}}$ expresa energía liberada por unidad de masa, en J/kg o kJ/kg. Si toda esa energía llega al motor como calor:

$$Q_H=m_{\mathrm{comb}}q_{\mathrm{comb}}
\quad\Rightarrow\quad
\boxed{m_{\mathrm{comb}}=\frac{Q_H}{q_{\mathrm{comb}}}
=\frac{W}{e\,q_{\mathrm{comb}}}}.$$

Usa energías referidas al mismo ciclo o intervalo. Para consumo por segundo, $\dot m_{\mathrm{comb}}=P/(e\,q_{\mathrm{comb}})$, en kg/s si trabajas con W y J/kg.

### Ejemplo: Carnot con combustible — T30

**Datos:** motor de Carnot, $W=1500\,\mathrm{J/ciclo}$, focos a $460\,^\circ\mathrm C$ y $15\,^\circ\mathrm C$, poder calorífico $4100\,\mathrm{kJ/kg}$. Se supone transferencia completa del calor del combustible al motor.

$$e_C=1-\frac{288.15}{733.15}=0.60697.$$

$$Q_H=\frac{1500}{0.60697}=2471.29\,\mathrm{J/ciclo},\qquad
|Q_C|=2471.29-1500=971.29\,\mathrm{J/ciclo}.$$

Convierte $4100\,\mathrm{kJ/kg}=4.10\times10^6\,\mathrm{J/kg}$:

$$m_{\mathrm{comb}}=\frac{2471.29\,\mathrm J}{4.10\times10^6\,\mathrm{J/kg}}
=6.03\times10^{-4}\,\mathrm{kg/ciclo}
=\boxed{0.603\,\mathrm{g/ciclo}}.$$

**Por qué se divide $Q_H$:** el combustible debe aportar tanto el trabajo como el calor que luego se rechaza. Dividir directamente $W/q_{\mathrm{comb}}$ subestima el consumo.

Si el enunciado añade una eficiencia de transferencia $\eta_{\mathrm{aporte}}$ entre combustible y motor, usa $Q_H=\eta_{\mathrm{aporte}}m_{\mathrm{comb}}q_{\mathrm{comb}}$. Es un factor adicional al rendimiento térmico $e=W/Q_H$; no lo añadas sin que el problema lo requiera.

## 6. Si dan un ciclo en un gráfico p–V

Aquí hay que obtener trabajo y calor a partir de las **etapas**. Para un gas ideal de cantidad fija, con capacidades caloríficas constantes y solo trabajo de expansión o compresión:

$$pV=nRT,\qquad \Delta U=nC_V(T_f-T_i),\qquad
\boxed{Q=\Delta U+W}.$$

$n$ es cantidad de gas en mol, $R$ la constante de los gases y $C_V$ la capacidad calorífica molar a volumen constante. Para un gas ideal monoatómico, $C_V=3R/2$ y puede usarse $\Delta U=\tfrac32(p_fV_f-p_iV_i)$.

| Etapa | Trabajo del gas | Cómo hallar el calor |
|---|---|---|
| Isocórica: $V$ constante | $W=0$ | $Q=\Delta U$ |
| Isobárica: $p$ constante | $W=p(V_f-V_i)$ | $Q=\Delta U+W$ |
| Isotérmica de gas ideal | $W=nRT\ln(V_f/V_i)$ en proceso reversible | $\Delta U=0$, luego $Q=W$ |
| Adiabática | $W=-\Delta U$ | $Q=0$ |
| Recta inclinada en $p$–$V$ | $W=\tfrac{p_i+p_f}{2}(V_f-V_i)$ | $Q=\Delta U+W$ |

La lectura del área como trabajo del gas supone una trayectoria mecánica cuasiestática sin disipación. Una recta inclinada no es una isoterma: para el gas ideal la isoterma cumple $pV=\text{constante}$.

**Procedimiento:** calcula $W$, $\Delta U$ y $Q$ por etapa. Suma los trabajos con su signo y separa los aportes de calor que entran de los que salen:

$$W_{\mathrm{neto}}=\sum_iW_i,\qquad
Q_H=\sum_{Q_i>0}Q_i,\qquad
|Q_C|=-\sum_{Q_i<0}Q_i.$$

$$\boxed{e=\frac{W_{\mathrm{neto}}}{Q_H}}.$$

Estas sumas suponen etapas en las que el flujo de calor mantiene su sentido; si cambia dentro de una etapa, hay que dividirla. En los tramos del ejemplo siguiente no cambia.

> [!warning] El calor neto no es el calor absorbido
> En el ciclo $Q_{\mathrm{neto}}=Q_H-|Q_C|=W_{\mathrm{neto}}$. Usar $W_{\mathrm{neto}}/Q_{\mathrm{neto}}$ daría siempre 1: ese cociente no es el rendimiento.

### Ejemplo: ciclo rectangular monoatómico — T18

El recorrido es $b\to c\to d\to a\to b$, con estados escritos como $(V,p)$: $b=(V_0,p_0)$, $c=(V_0,3p_0)$, $d=(2V_0,3p_0)$ y $a=(2V_0,p_0)$.

| Etapa | $W/(p_0V_0)$ | $\Delta U/(p_0V_0)$ | $Q/(p_0V_0)$ |
|---|---|---|---|
| $b\to c$: calienta a volumen constante | $0$ | $3$ | $3$ |
| $c\to d$: expansión a presión constante | $3$ | $4.5$ | $7.5$ |
| $d\to a$: enfría a volumen constante | $0$ | $-6$ | $-6$ |
| $a\to b$: compresión a presión constante | $-1$ | $-1.5$ | $-2.5$ |
| **Ciclo completo** | **$2$** | **$0$** | **$2$** |

Las cifras de la tabla multiplican a $p_0V_0$, que tiene unidades de energía. Entran calores en los dos primeros tramos:

$$Q_H=(3+7.5)p_0V_0=10.5p_0V_0,\qquad
|Q_C|=(6+2.5)p_0V_0=8.5p_0V_0.$$

$$e=\frac{2p_0V_0}{10.5p_0V_0}=\frac4{21}\approx19.05\%.$$

**Control geométrico:** el área del rectángulo es $(3p_0-p_0)(2V_0-V_0)=2p_0V_0$, igual al trabajo neto. El recorrido horario produce trabajo positivo. El área encerrada permite hallar $W_{\mathrm{neto}}$; para el rendimiento también necesitas $Q_H$.

**Unidades del gráfico:** $1\,\mathrm{Pa\,m^3}=1\,\mathrm J$; $1\,\mathrm{kPa\,m^3}=1\,\mathrm{kJ}$; $1\,\mathrm{kPa\,L}=1\,\mathrm J$.

## 7. Otros modelos que conviene distinguir

**Otto ideal:** si el problema especifica dos adiabáticas reversibles y dos isocóricas, con $\gamma=C_P/C_V$ constante, usa:

$$e_{\mathrm{Otto}}=1-\frac{1}{r^{\gamma-1}},\qquad
r=\frac{V_{\max}}{V_{\min}}.$$

$r$ es la relación de compresión, sin unidad. Una vez hallado $e$, sigue valiendo el balance general del motor. La [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Ciclo Otto: modelo, razón de compresión y origen de su eficiencia|explicación de Otto]] desarrolla el origen y los supuestos.

**Refrigerador:** consume trabajo para extraer calor del foco frío. Usa magnitudes positivas y distingue el objetivo:

$$|Q_H|=|Q_C|+W_{\mathrm{entrada}},\qquad
COP_R=\frac{|Q_C|}{W_{\mathrm{entrada}}}.$$

El COP puede superar 1 porque mide calor transportado por trabajo consumido. Para este caso, continúa en [[Unidades/05 - Termodinámica/Teoría/05 - Guía breve de termodinámica#Refrigeración y Otto: qué resultado es útil|refrigeración y elección del resultado útil]].

## 8. Control final y práctica dirigida

- ¿Todas las energías corresponden al mismo ciclo o intervalo? ¿Separé J de J/s?
- ¿Usé $e$ como fracción y $|Q_C|$ como magnitud positiva?
- ¿Cierra $Q_H=W+|Q_C|$ y es $0<e<1$ para un motor que produce trabajo entre focos a temperatura positiva?
- ¿Convertí a K antes de usar Carnot y distinguí rendimiento real de máximo?
- ¿Dividí el trabajo por la potencia **mecánica** al hallar el tiempo?
- ¿Calculé combustible a partir del calor recibido?
- Si hay gráfico, ¿sumé solo los calores de entrada para obtener $Q_H$?

**Para practicar por dificultad del método:** T19 → T20 → T32 A → T31 → T24 → T30. T19 fija el balance; T20/T32 separan energía de potencia; T31 distingue las dos leyes; T24 entrena despejes y T30 añade combustible. Es una secuencia didáctica para este resumen; la prioridad de examen del módulo se consulta en su ruta general.

**Enunciados y corrección:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|ejercicios de máquinas térmicas]] · [[Unidades/05 - Termodinámica/Resoluciones/05 - Resoluciones de termodinámica#Segunda ley y máquinas térmicas|resoluciones explicadas]]. Para gráficos, sigue T28 → T18 → T17 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|gases ideales y primera ley]].

**Base del resumen:** síntesis de la teoría y las resoluciones locales de T19, T20, T24, T30, T31, T32 y T18. Los enunciados conservan allí sus referencias a los TP y modelos de parcial. Las tablas de decisión y la secuencia de consulta son una organización didáctica añadida; el desarrollo general está en [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica#8. Ciclos y máquinas térmicas|fórmulas de ciclos y máquinas térmicas]].
