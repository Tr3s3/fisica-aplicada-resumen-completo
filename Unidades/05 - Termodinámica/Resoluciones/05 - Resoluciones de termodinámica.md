---
tags: [fisica-aplicada, resoluciones, unidad-05, termodinamica]
---

# Resoluciones de termodinámica

Esta nota reúne las resoluciones de toda la unidad, con las mismas familias e identificadores que el archivo de ejercicios. Intenta primero el enunciado y compara después el principio elegido, el despeje, las unidades y el control final.

**Ejercicios:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica|ejercicios de termodinámica]] · **Recorrido:** [[Unidades/05 - Termodinámica/Teoría/05 - Termodinámica|mapa de la unidad]].

**Etiquetas:** M reproduce un planteo de modelo; R practica una variante de una familia examinada; C cubre contenidos complementarios. Cada ejercicio conserva su fuente y su prioridad de examen o didáctica.

## Índice de familias

| Familia, en orden de práctica | Ejercicios, en orden | Consulta |
|---|---|---|
| [[#Segunda ley y máquinas térmicas\|Segunda ley y máquinas térmicas]] | T31, T30, T32, T20, T19, T24 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas\|Enunciados]] |
| [[#Gases ideales y primera ley\|Gases ideales y primera ley]] | T16, T27, T28, T18, T17 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley\|Enunciados]] |
| [[#Calorimetría y cambios de fase\|Calorimetría y cambios de fase]] | T29, T7, T8, T11, T33, T10, T34 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase\|Enunciados]] |
| [[#Transferencia de calor\|Transferencia de calor]] | T13, T12 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor\|Enunciados]] |
| [[#Temperatura y dilatación\|Temperatura y dilatación]] | T1, T2, T3, T4, T5, T6 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación\|Enunciados]] |
| [[#Curvas de calentamiento\|Curvas de calentamiento]] | T9 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Curvas de calentamiento\|Enunciados]] |
| [[#Radiación y elección de materiales\|Radiación y elección de materiales]] | T14, T15, T35 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Radiación y elección de materiales\|Enunciados]] |
| [[#Otto, refrigeración y entropía\|Otto, refrigeración y entropía]] | T21, T22, T23, T25, T26 | [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Otto, refrigeración y entropía\|Enunciados]] |

## Segunda ley y máquinas térmicas

**Práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|Segunda ley y máquinas térmicas]] · **Conceptos:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#8. Motores y refrigeradores: objetivos y rendimientos]] · [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#9. Segunda ley y entropía|entropía]].

En un motor se busca trabajo de salida; en un refrigerador se busca extraer calor de la fuente fría. Las convenciones de magnitudes positivas se indican en cada balance.

### T31. Máquina real y propuesta imposible

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T31. Máquina real y propuesta imposible — M · prioridad de examen alta|volver a T31]].

#### 1. Balance de energía del funcionamiento real

El sistema es la máquina durante un ciclo completo. Como vuelve al mismo estado, $\Delta U=0$ y el calor de entrada se reparte entre trabajo y calor rechazado:

$$Q_H=W+|Q_C|\quad\Rightarrow\quad
|Q_C|=2500-850=1650\,\mathrm J.$$

La eficiencia real proviene de las energías medidas:

$$e_{\mathrm{real}}=\frac{W}{Q_H}
=\frac{850}{2500}=0.340=34.0\%.$$

#### 2. Límite de la segunda ley

Convertimos temperaturas antes de formar la razón:

$$T_H=873.15\,\mathrm K,\qquad T_C=298.15\,\mathrm K.$$

$$e_C=1-\frac{T_C}{T_H}
=1-\frac{298.15}{873.15}=0.65854=65.9\%.$$

El funcionamiento real, $34.0\%$, queda por debajo de ese máximo. La igualdad correspondería a un motor reversible ideal.

#### 3. Evaluar la propuesta con las dos leyes

La propuesta exigiría:

$$e_{\mathrm{propuesta}}=\frac{1900}{2500}=0.760=76.0\%.$$

La primera ley permitiría un rechazo de $2500-1900=600\,\mathrm J$; el balance de energía cerraría. Sin embargo:

$$76.0\%>65.9\%.$$

Por eso la propuesta es **imposible entre esos mismos focos**: supera el límite de Carnot y viola la segunda ley. Tener eficiencia menor que $100\%$ no basta para asegurar que sea posible.

#### 4. Trabajo máximo compatible con los datos

De $e=W/Q_H$ y $e\le e_C$:

$$W_{\max}=e_CQ_H=(0.65854)(2500\,\mathrm J)
=1646.34\,\mathrm J.$$

**Resultados:** $|Q_C|=1650\,\mathrm{J/ciclo}$, $e_{\mathrm{real}}=34.0\%$, $e_C\approx65.9\%$ y $W_{\max}\approx1.65\,\mathrm{kJ/ciclo}$. Los $1900\,\mathrm J$ propuestos superan el máximo.

**Control:** $850<1646<1900\,\mathrm J$. No se usó la igualdad $e_{\mathrm{real}}=e_C$: Carnot fija el techo, no la eficiencia medida.

**Contraste de fuente:** resultados y pasos cotejados con la [clave de corrección 2026](zotero://select/library/items/TZPNLWDL) (E3, p. 1). Presenta ecuaciones, unidades y explicación física, además del número final.

### T30. Carnot y consumo de combustible por ciclo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T30. Carnot y consumo de combustible por ciclo — M · prioridad de examen alta|volver a T30]].

#### 1. Identificar el modelo y convertir temperaturas

Se declara un motor ideal de Carnot: su eficiencia **alcanza** el límite reversible entre los dos focos. No se aplica esta igualdad a una máquina real sin esa condición.

$$T_H=460+273.15=733.15\,\mathrm K,\qquad
T_C=15+273.15=288.15\,\mathrm K.$$

$$e_C=1-\frac{288.15}{733.15}=0.60697=60.7\%.$$

#### 2. Despejar el calor absorbido y el cedido

Partimos de la definición de eficiencia; multiplicamos por $Q_H$ y dividimos por $e_C$:

$$e_C=\frac{W}{Q_H}
\quad\Rightarrow\quad e_CQ_H=W
\quad\Rightarrow\quad Q_H=\frac{W}{e_C}.$$

$$Q_H=\frac{1500\,\mathrm J}{0.60697}=2471.29\,\mathrm J.$$

El motor vuelve al mismo estado tras cada ciclo, por lo que $\Delta U=0$ y la primera ley exige $Q_H=W+|Q_C|$:

$$|Q_C|=Q_H-W=2471.29-1500=971.29\,\mathrm J.$$

#### 3. Pasar de energía a masa de combustible

El poder calorífico indica cuántos joules libera cada kg:

$$q_{\mathrm{comb}}=4100\,\mathrm{kJ/kg}
=4.10\times10^6\,\mathrm{J/kg}.$$

Con transferencia completa de esa energía al motor:

$$Q_H=m_{\mathrm{comb}}q_{\mathrm{comb}}
\quad\Rightarrow\quad
m_{\mathrm{comb}}=\frac{Q_H}{q_{\mathrm{comb}}}
=\frac{2471.29\,\mathrm J}{4.10\times10^6\,\mathrm{J/kg}}
=6.03\times10^{-4}\,\mathrm{kg}.$$

$$m_{\mathrm{comb}}=0.603\,\mathrm g\text{ por ciclo}.$$

Se usa $Q_H$ porque el combustible suministra toda la energía de entrada; solo una fracción $e_C$ se convierte en trabajo. Dividir directamente $W/q_{\mathrm{comb}}$ supondría convertir toda la energía en trabajo, contradiciendo el calor que se cede al foco frío.

**Resultados:** $e_C\approx60.7\%$, $Q_H\approx2.47\,\mathrm{kJ}$, $|Q_C|\approx0.971\,\mathrm{kJ}$ y $m_{\mathrm{comb}}\approx0.603\,\mathrm{g/ciclo}$.

**Control:** $2471.29=1500+971.29\,\mathrm J$; la masa multiplicada por el poder calorífico recupera $Q_H$. Si solo una fracción $\eta_{\mathrm{aporte}}$ del calor del combustible llegara al motor, se usaría $m=Q_H/(\eta_{\mathrm{aporte}}q_{\mathrm{comb}})$ y el consumo sería mayor.

### T32. Calor suministrado y desechado por segundo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T32. Calor suministrado y desechado por segundo — M · prioridad de examen alta|volver a T32]].

#### 1. Elegir el balance y distinguir tasa de energía

El sistema es el motor. En un ciclo vuelve al mismo estado, por lo que su cambio neto de energía interna es cero. Con $Q_H>0$ como energía absorbida y $|Q_C|>0$ como magnitud del calor rechazado:

$$Q_H=W+|Q_C|.$$

Dividimos los tres términos por la misma duración; en operación cíclica estable obtenemos tasas medias:

$$\dot Q_H=P_{\mathrm{salida}}+|\dot Q_C|.$$

La eficiencia también se puede expresar con tasas:

$$e=\frac{W}{Q_H}
=\frac{W/\Delta t}{Q_H/\Delta t}
=\frac{P_{\mathrm{salida}}}{\dot Q_H}.$$

El dato «$23000\,\mathrm J$ por segundo» es una potencia de $23000\,\mathrm{J/s}=23\,\mathrm{kW}$, no una energía por ciclo. La eficiencia $20\%$ se sustituye como $0.20$.

#### 2. Caso A — tasas de calor del modelo global

Despejamos primero la tasa de entrada:

$$e\dot Q_H=P_{\mathrm{salida}}
\quad\Rightarrow\quad
\dot Q_H=\frac{P_{\mathrm{salida}}}{e}.$$

$$\dot Q_H=\frac{23000\,\mathrm{J/s}}{0.20}
=115000\,\mathrm{J/s}=115\,\mathrm{kW}.$$

Después usamos el balance para el calor rechazado por segundo:

$$|\dot Q_C|=\dot Q_H-P_{\mathrm{salida}}
=115000-23000=92000\,\mathrm{J/s}=92\,\mathrm{kW}.$$

**Resultados del modelo:** entran $115\,\mathrm{kJ}$ de calor por cada segundo de operación; $23\,\mathrm{kJ}$ se convierten en trabajo y se rechazan $92\,\mathrm{kJ}$.

**Control:** $115\,\mathrm{kW}=23\,\mathrm{kW}+92\,\mathrm{kW}$ y $23/115=0.20$. La entrada térmica supera la potencia útil. Sin duración del ciclo no podemos expresar estas respuestas en J/ciclo.

#### 3. Caso B — variante del TP con los mismos despejes

Usamos ahora $P_{\mathrm{salida}}=180\,\mathrm{kW}=180000\,\mathrm{J/s}$ y $e=0.28$:

$$\dot Q_H=\frac{180000\,\mathrm{J/s}}{0.28}
=642857\,\mathrm{J/s}\approx642.9\,\mathrm{kW},$$

$$|\dot Q_C|=642857-180000
=462857\,\mathrm{J/s}\approx462.9\,\mathrm{kW}.$$

Estas tasas resuelven los dos incisos originales del TP.

#### 4. Ampliación del caso B — energías de un minuto

Como las tasas son constantes, cada energía es su tasa multiplicada por $\Delta t=60.0\,\mathrm s$:

$$W_{1\mathrm{min}}=(180000\,\mathrm{J/s})(60.0\,\mathrm s)
=10.80\,\mathrm{MJ},$$

$$Q_{H,1\mathrm{min}}=(642857\,\mathrm{J/s})(60.0\,\mathrm s)
\approx38.57\,\mathrm{MJ},$$

$$|Q_{C,1\mathrm{min}}|=(462857\,\mathrm{J/s})(60.0\,\mathrm s)
\approx27.77\,\mathrm{MJ}.$$

**Control:** $38.57\approx10.80+27.77\,\mathrm{MJ}$. Las tasas se expresan en W; al multiplicarlas por segundos se obtienen J. El dato de un minuto pertenece a la ampliación del TP, no al enunciado del global.


---

**Cierre:** [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Repaso del módulo|autoevaluación final]] · [[Unidades/05 - Termodinámica/Teoría/05 - Termodinámica|volver al módulo]].

### T20. Potencia y duración del ciclo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T20. Potencia de salida y duración de cada ciclo — M · prioridad de examen alta|volver a T20]].

La eficiencia relaciona el calor rechazado con el absorbido:

$$0.25=1-\frac{8000}{Q_H}
\quad\Longrightarrow\quad
Q_H=\frac{8000}{1-0.25}=10666.7\,\mathrm J.$$

El trabajo por ciclo es

$$W=Q_H-|Q_C|=10666.7-8000=2666.7\,\mathrm J.$$

La potencia es trabajo por unidad de tiempo:

$$\Delta t=\frac{W}{P}
=\frac{2666.7\,\mathrm J}{5000\,\mathrm{J/s}}
=0.533\,\mathrm s.$$

**Resultados:** $\boxed{Q_H=10.67\,\mathrm{kJ}}$, $\boxed{W=2.67\,\mathrm{kJ/ciclo}}$ y $\boxed{\Delta t\approx0.533\,\mathrm s/ciclo}$.

### T19. Motor diésel

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T19. Motor diésel: energía y eficiencia — M · prioridad de examen alta|volver a T19]].

Por ciclo el motor recibe $Q_H$, entrega $W$ y expulsa $|Q_C|$. Como vuelve al mismo estado, $\Delta U_{\mathrm{ciclo}}=0$:

$$Q_H=W+|Q_C|=2200+4300=6500\,\mathrm J.$$

La eficiencia es el trabajo útil dividido por el calor recibido:

$$e=\frac{W}{Q_H}=\frac{2200}{6500}=0.3385=33.85\%.$$

**Resultados:** $\boxed{Q_H=6500\,\mathrm J}$ y $\boxed{e=33.9\%}$.

### T24. Máquinas de Carnot

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T24. Dos despejes de Carnot — R · prioridad de examen alta|volver a T24]].

#### a. Calores conocidos

El balance de energía da

$$W=Q_H-|Q_C|=550-335=215\,\mathrm J.$$

En Carnot, $|Q_C|/Q_H=T_C/T_H$:

$$T_C=620\left(\frac{335}{550}\right)=377.64\,\mathrm K.$$

La eficiencia es

$$e=\frac{W}{Q_H}=\frac{215}{550}=0.3909=39.09\%.$$

**Resultados a:** $\boxed{W=215\,\mathrm J}$, $\boxed{T_C\approx378\,\mathrm K}$ y $\boxed{e\approx39.1\%}$.

#### b. Eficiencia y trabajo conocidos

Despejamos el calor absorbido:

$$Q_H=\frac{W}{e}
=\frac{2.5\times10^4}{0.59}
=4.237\times10^4\,\mathrm J.$$

Convertimos la temperatura de la fuente fría:

$$T_C=20+273.15=293.15\,\mathrm K.$$

De $e=1-T_C/T_H$:

$$T_H=\frac{T_C}{1-e}
=\frac{293.15}{0.41}
=715.0\,\mathrm K
=441.9\,^\circ\mathrm C.$$

**Resultados b:** $\boxed{Q_H\approx42.4\,\mathrm{kJ}}$ y $\boxed{T_H\approx715\,\mathrm K}$.

**Control:** en ambos casos se usaron temperaturas absolutas. Carnot permite despejar la razón de temperaturas de los focos.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|enunciados de esta familia]] · [[#Gases ideales y primera ley|siguiente familia: gases ideales y primera ley]].

---

## Gases ideales y primera ley

Convención en estas soluciones: $Q>0$ hacia el gas y $W>0$ realizado por el gas, así que $\Delta U=Q-W$.

**Práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|Gases ideales y primera ley]] · **Conceptos:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#6. Primera ley: el balance de energía]] · **Fórmulas:** [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica#6. Trabajo y primera ley]].

### T16. Expansión adiabática

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T16. Expansión adiabática en un cilindro — M · prioridad de examen media|volver a T16]].

#### 1. Caso A — interpretar y ordenar los datos del modelo

El sistema es el gas dentro del cilindro: no intercambia calor ($Q=0$), pero realiza trabajo al mover el pistón. Se supone gas ideal con $\gamma=1.40$ constante, expansión reversible y solo trabajo de presión–volumen. Usamos $\Delta U=Q-W$.

Convertimos los volúmenes antes de multiplicarlos por presiones:

$$V_i=2.00\,\mathrm L=2.00\times10^{-3}\,\mathrm{m^3},\qquad
V_f=6.00\times10^{-3}\,\mathrm{m^3}.$$

El cociente $V_i/V_f=1/3$ no tiene unidades. La presión inicial es $5.00\times10^5\,\mathrm{Pa}$; $T_i=600\,\mathrm K$ se necesita para el último inciso.

#### 2. Presión final

La relación $pV^\gamma=\mathrm{constante}$ corresponde a esta **adiabática reversible de gas ideal**; no basta que un proceso cualquiera tenga $Q=0$ para poder usarla. Despejamos:

$$p_iV_i^\gamma=p_fV_f^\gamma
\quad\Rightarrow\quad
p_f=p_i\left(\frac{V_i}{V_f}\right)^\gamma.$$

$$p_f=(5.00\times10^5\,\mathrm{Pa})\left(\frac{2.00}{6.00}\right)^{1.40}
=1.07399\times10^5\,\mathrm{Pa}.$$

#### 3. Trabajo y energía interna: por qué elegimos esta fórmula

La presión cambia durante la expansión, por lo que no corresponde usar una sola presión multiplicada por $\Delta V$. Para un gas ideal con $C_V$ constante,

$$\Delta U=nC_V(T_f-T_i),\qquad C_V=\frac{R}{\gamma-1}.$$

Al reemplazar $nRT$ por $pV$, queda:

$$\Delta U=\frac{p_fV_f-p_iV_i}{\gamma-1}.$$

Como $Q=0$, la primera ley da $W=-\Delta U$. Por eso usamos:

$$W=\frac{p_iV_i-p_fV_f}{\gamma-1}.$$

Los productos $pV$ son energías: $\mathrm{Pa\,m^3}=\mathrm J$.

$$p_iV_i=(5.00\times10^5)(2.00\times10^{-3})=1000\,\mathrm J,$$

$$p_fV_f=(1.07399\times10^5)(6.00\times10^{-3})
\approx644.394\,\mathrm J.$$

Conservamos cifras intermedias hasta terminar:

$$W=\frac{1000-644.394}{1.40-1}=+889.015\,\mathrm J,$$

$$\Delta U=0-W=-889.015\,\mathrm J.$$

El gas entrega trabajo tomando energía de su propia energía interna: adiabático no significa que la energía interna permanezca constante.

#### 4. Temperatura final

La relación adiabática de temperaturas da:

$$T_iV_i^{\gamma-1}=T_fV_f^{\gamma-1}
\quad\Rightarrow\quad
T_f=T_i\left(\frac{V_i}{V_f}\right)^{\gamma-1}.$$

$$T_f=(600\,\mathrm K)\left(\frac{2.00}{6.00}\right)^{0.40}
=386.64\,\mathrm K.$$

**Resultados del modelo:** $p_f\approx1.074\times10^5\,\mathrm{Pa}$, $W\approx+889\,\mathrm J$, $\Delta U\approx-889\,\mathrm J$ y $T_f\approx386.6\,\mathrm K$.

**Control:** $V_f>V_i$, $W>0$, $\Delta U<0$, $T_f<T_i$ y $p_f<p_i$. Además, para la misma cantidad de gas, $T_f/T_i=p_fV_f/(p_iV_i)\approx0.6444$: coincide con $386.64/600$.

#### 5. Caso B — transferir el método a los datos del TP

Aquí cambian los datos: $V_i=50.0\times10^{-6}\,\mathrm{m^3}$, $V_f=300\times10^{-6}\,\mathrm{m^3}$ y $p_i=3.0\times10^6\,\mathrm{Pa}$. Por eso ahora $V_i/V_f=1/6$, no $1/3$.

$$p_f=(3.0\times10^6)\left(\frac{1}{6}\right)^{1.40}
\approx2.44\times10^5\,\mathrm{Pa}.$$

$$p_iV_i=150\,\mathrm J,\qquad p_fV_f\approx73.25\,\mathrm J,$$

$$W=\frac{150-73.25}{0.40}\approx+191.9\,\mathrm J.$$

Estas son las dos respuestas pedidas en el TP. Para la ampliación de práctica:

$$\Delta U=-W\approx-191.9\,\mathrm J,$$

$$T_f=(600\,\mathrm K)\left(\frac{1}{6}\right)^{0.40}
\approx293.0\,\mathrm K.$$

**Control del caso B:** también hay expansión, trabajo positivo y enfriamiento. No se mezclan estos resultados con los del modelo: las razones de expansión y los productos $pV$ iniciales son distintos.

**Contraste de fuente:** resultados y pasos cotejados con la [clave de corrección 2026](zotero://select/library/items/TZPNLWDL) (E2, p. 1). Presenta ecuaciones, unidades y explicación física, además del número final.

### T27. Expansión isobárica y primera ley

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T27. Expansión isobárica y primera ley — M · prioridad de examen media|volver a T27]].

#### 1. Definir el proceso y el signo del trabajo

El sistema es el gas. El pistón es liviano, sin fricción y se mueve lentamente; por eso la presión del gas se mantiene aproximadamente igual a la atmosférica durante toda la expansión:

$$
P=1.013\times10^5\,\mathrm{Pa}.
$$

El volumen aumenta, así que el gas empuja el pistón y realiza trabajo sobre el entorno. Con la convención indicada, $W$ será positivo.

#### 2. Calcular el trabajo a presión constante

En un diagrama $pV$, el trabajo es el área bajo la trayectoria. Como $P$ es constante, el área es un rectángulo:

$$
W=P\Delta V=P(V_f-V_i).
$$

El cambio de volumen es:

$$
\Delta V=18.2-12.0=6.2\,\mathrm{m^3}.
$$

Entonces:

$$
W=(1.013\times10^5\,\mathrm{Pa})(6.2\,\mathrm{m^3})
=6.2806\times10^5\,\mathrm J.
$$

La unidad coincide porque $1\,\mathrm{Pa\,m^3}=1\,\mathrm J$. Redondeando a tres cifras significativas, $W\approx6.28\times10^5\,\mathrm J$.

#### 3. Convertir el calor recibido

La primera ley requiere que $Q$ y $W$ estén en la misma unidad. Convertimos kilocalorías a joules:

$$
Q=(1400\,\mathrm{kcal})\left(4184\,\frac{\mathrm J}{\mathrm{kcal}}\right)
=5.8576\times10^6\,\mathrm J.
$$

El signo es positivo porque el calor entra al gas.

#### 4. Aplicar la primera ley

Con $W$ positivo cuando lo realiza el gas, la primera ley se escribe:

$$
\Delta U=Q-W.
$$

Sustituimos los valores:

$$
\Delta U=5.8576\times10^6-6.2806\times10^5
=5.22954\times10^6\,\mathrm J.
$$

#### Resultado e interpretación

$$
\boxed{W\approx6.28\times10^5\,\mathrm J},\qquad
\boxed{\Delta U\approx5.23\times10^6\,\mathrm J}.
$$

El gas recibe más energía como calor de la que entrega mediante trabajo; la diferencia aumenta su energía interna. Este tipo aparece una vez en los modelos revisados, por eso su prioridad de examen es media.

### T28. Interpretar el ciclo triangular de los modelos

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T28. Interpretar el ciclo triangular de los modelos — M · prioridad de examen alta|volver a T28]].

#### 1. Leer los estados y reconocer los procesos

El sistema es el gas. Se recorre $A\to B\to C\to A$ en sentido horario. En $A\to B$ no cambia el volumen: es un calentamiento isocórico. En $B\to C$ el volumen aumenta y la presión disminuye linealmente. En $C\to A$ la presión se mantiene en $1.0\,\mathrm{kPa}$ y el volumen baja de $5.0$ a $2.0\,\mathrm{m^3}$: es una compresión isobárica.

**1: verdadera; 3: verdadera; 7: falsa**, porque en $C\to A$ el volumen cambia.

#### 2. Comparar temperaturas sin conocer los moles

Para cantidad fija de gas ideal, $T=pV/(nR)$. Por tanto:

$$p_AV_A=2.0\,\mathrm{kJ},\quad p_BV_B=6.0\,\mathrm{kJ},\quad p_CV_C=5.0\,\mathrm{kJ}.$$

Al dividir se cancelan $nR$ y las unidades de $pV$:

$$\frac{T_B}{T_A}=\frac{6.0}{2.0}=3,\qquad
\frac{T_C}{T_B}=\frac{5.0}{6.0}\ne1.$$

**2: falsa:** $B\to C$ no es isotérmico, pues ni siquiera sus extremos tienen la misma temperatura. Una isoterma ideal cumple $pV=\text{constante}$ y es una hipérbola. **6: falsa:** $T_B=3T_A$, con temperaturas absolutas.

#### 3. Trabajo de cada tramo y del ciclo

Usamos $W=\int p\,dV$. En el tramo vertical $W_{AB}=0$. En el tramo recto inclinado, el área bajo la curva es un trapecio: presión media por cambio de volumen.

$$W_{BC}=\frac{p_B+p_C}{2}(V_C-V_B)
=\frac{3.0+1.0}{2}(5.0-2.0)\,\mathrm{kPa\,m^3}
=+6.0\,\mathrm{kJ}.$$

En el regreso isobárico:

$$W_{CA}=p_A(V_A-V_C)
=(1.0)(2.0-5.0)\,\mathrm{kPa\,m^3}
=-3.0\,\mathrm{kJ}.$$

$$W_{\mathrm{neto}}=0+6.0-3.0=+3.0\,\mathrm{kJ}.$$

También se obtiene con el área del triángulo:

$$W_{\mathrm{neto}}=\frac{(5.0-2.0)(3.0-1.0)}{2}=+3.0\,\mathrm{kJ}.$$

**4: verdadera.** El signo es positivo porque el gas se expande a presiones mayores que las de compresión.

#### 4. Volumen y calor neto

$$\Delta V_{BC}=5.0-2.0=+3.0\,\mathrm{m^3}=+3000\,\mathrm L.$$

**5: falsa:** son $3000\,\mathrm L$. En $C\to A$, $\Delta V=-3.0\,\mathrm{m^3}=-3000\,\mathrm L$; **9: falsa**, es una compresión de $3000\,\mathrm L$.

Como al cerrar el ciclo vuelve al mismo estado, $\Delta U_{\mathrm{ciclo}}=0$. Por la primera ley:

$$0=Q_{\mathrm{neto}}-W_{\mathrm{neto}}
\quad\Rightarrow\quad
Q_{\mathrm{neto}}=+3000\,\mathrm J.$$

**8: falsa:** el gas recibe un calor neto de $3000\,\mathrm J$. Este calor neto es la suma con signos de todos los intercambios; no es el calor total absorbido $Q_H$.

**Clave:** V, F, V, V, F, F, F, F, F. **Control:** coinciden el área, la suma de trabajos y el balance del ciclo; la conversión de volumen lleva un factor $1000$.

### T18. Ciclo rectangular monoatómico

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T18. Ciclo rectangular de un gas monoatómico — R · prioridad de examen alta|volver a T18]].

El trabajo neto es el área encerrada:

$$W_{\mathrm{neto}}=(3p_0-p_0)(2V_0-V_0)=2p_0V_0.$$

Para hallar el calor de entrada, usamos $C_V=3R/2$.

**Tramo b→c, isocórico:** el producto $pV$ aumenta de $p_0V_0$ a $3p_0V_0$:

$$W_{bc}=0,\qquad
\Delta U_{bc}=\frac32(2p_0V_0)=3p_0V_0,$$

$$Q_{bc}=3p_0V_0.$$

**Tramo c→d, isobárico:** $W_{cd}=3p_0V_0$ y $\Delta U_{cd}=(3/2)(3p_0V_0)=4.5p_0V_0$:

$$Q_{cd}=\Delta U_{cd}+W_{cd}=7.5p_0V_0.$$

Los otros dos tramos ceden calor. Por tanto:

$$Q_H=Q_{bc}+Q_{cd}=10.5p_0V_0,$$

$$e=\frac{W_{\mathrm{neto}}}{Q_H}
=\frac{2}{10.5}=\frac{4}{21}=19.05\%.$$

Las temperaturas son proporcionales a $pV$ para la misma cantidad de gas. La temperatura máxima ocurre en d ($6p_0V_0$) y la mínima en b ($p_0V_0$):

$$e_{\mathrm{Carnot}}=1-\frac{T_L}{T_H}
=1-\frac{1}{6}=\frac56=83.33\%.$$

La razón es

$$\frac{e}{e_{\mathrm{Carnot}}}
=\frac{4/21}{5/6}=\frac{8}{35}=22.86\%.$$

**Control:** el área del ciclo es positiva porque el recorrido es horario; su eficiencia queda por debajo de Carnot.

### T17. Ciclo con tramo adiabático

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T17. Ciclo con un tramo adiabático — R · prioridad de examen alta|volver a T17]].

#### Estados

En el estado 1:

$$V_1=\frac{nRT_1}{p_1}
=\frac{(0.350)(8.314)(300)}{1.013\times10^5}
=8.618\times10^{-3}\,\mathrm{m^3}.$$

Como 1→2 es isocórico y $T_2=600\,\mathrm K$:

$$V_2=V_1,\qquad p_2=p_1\frac{T_2}{T_1}
=2.026\times10^5\,\mathrm{Pa}.$$

El diagrama da $p_3=p_1$ y $T_3=492\,\mathrm K$. Entonces:

$$V_3=\frac{nRT_3}{p_3}
=1.4133\times10^{-2}\,\mathrm{m^3}.$$

#### Energía en cada tramo

Usamos $C_V=5R/2=20.785\,\mathrm{J/(mol\,K)}$ y $\Delta U=nC_V\Delta T$.

**1→2, isocórico:** $W_{12}=0$ porque no cambia el volumen.

$$\Delta U_{12}=(0.350)(20.785)(600-300)=+2182.4\,\mathrm J,$$

$$Q_{12}=\Delta U_{12}+W_{12}=+2182.4\,\mathrm J.$$

**2→3, adiabático:** no entra ni sale calor, así que $Q_{23}=0$.

$$\Delta U_{23}=(0.350)(20.785)(492-600)=-785.7\,\mathrm J,$$

$$W_{23}=Q_{23}-\Delta U_{23}=+785.7\,\mathrm J.$$

**3→1, isobárico:** el gas se comprime; por eso el trabajo del gas es negativo.

$$W_{31}=nR(T_1-T_3)
=(0.350)(8.314)(300-492)=-558.7\,\mathrm J,$$

$$\Delta U_{31}=(0.350)(20.785)(300-492)
=-1396.8\,\mathrm J,$$

$$Q_{31}=\Delta U_{31}+W_{31}=-1955.5\,\mathrm J.$$

#### Balance del ciclo

$$W_{\mathrm{neto}}=0+785.7-558.7=227.0\,\mathrm J,$$

$$Q_{\mathrm{neto}}=2182.4+0-1955.5=226.9\,\mathrm J.$$

La pequeña diferencia es por redondeo de los datos; ambos balances coinciden aproximadamente. El calor entrante es $Q_H=Q_{12}=2182.4\,\mathrm J$:

$$e=\frac{W_{\mathrm{neto}}}{Q_H}
=\frac{227.0}{2182.4}=0.104\approx10.4\%.$$

Entre $T_C=300\,\mathrm K$ y $T_H=600\,\mathrm K$:

$$e_{\mathrm{Carnot}}=1-\frac{300}{600}=0.500=50.0\%.$$

**Control:** la eficiencia del ciclo real del ejercicio es menor que el límite de Carnot; el trabajo neto también coincide, dentro del redondeo, con el calor neto.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|enunciados de esta familia]] · [[#Calorimetría y cambios de fase|siguiente familia: calorimetría y cambios de fase]].

---

## Calorimetría y cambios de fase

**Práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase|Calorimetría y cambios de fase]] · **Conceptos:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#3. Calor, calor específico y calorimetría]] · **Fórmulas:** [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica#3. Calor sensible, cambio de fase y mezcla]].

### T29. ¿Se funde todo el hielo? Dos resultados posibles

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T29. ¿Se funde todo el hielo? Dos resultados posibles — R · reconstrucción de la clave 2026 · prioridad de estudio alta|volver a T29]].

#### Caso principal: reconstrucción de la clave 2026

El sistema es aluminio + agua inicial + hielo, aislado y con trabajo despreciable. Usamos $Q>0$ para una parte que recibe calor; por conservación de energía, la suma de sus calores es cero.

**1. Decidir la fusión antes de despejar la temperatura.** Hasta llegar a $0\,^\circ\mathrm C$, aluminio y agua inicial podrían ceder

$$
E_{\mathrm{disp}}=(0.80)(900)(180)+(0.50)(4186)(20)
=129600+41860=171460\,\mathrm J.
$$

La fusión del hielo requiere $m_iL_f=(0.10)(334000)=33400\,\mathrm J$. Como $171460>33400$, se funde todo y el equilibrio será por encima de cero. Esta comparación es un estado de referencia: no dice que el agua inicial realmente se enfríe hasta cero en el proceso final.

**2. Balance con el agua inicial y el hielo fundido separados.** El aluminio se enfría desde 180 °C; el agua inicial se calienta desde 20 °C; el hielo se funde a cero y después su agua se calienta hasta $T_f$:

$$
m_{\mathrm{Al}}c_{\mathrm{Al}}(180-T_f)
=m_iL_f+m_wc_w(T_f-20)+m_ic_wT_f.
$$

Sustituyendo en J y °C,

$$
720(180-T_f)=33400+2093(T_f-20)+418.6T_f,
$$

$$
129600-720T_f=-8460+2511.6T_f,
\qquad
T_f=\frac{138060}{3231.6}=42.7219\,^\circ\mathrm C.
$$

**3. Calor cedido por el aluminio.** Su magnitud es

$$
|Q_{\mathrm{Al}}|=(0.80)(900)(180-42.7219)
=98840.3\,\mathrm J\approx98.84\,\mathrm{kJ}.
$$

El calor con signo es negativo: el aluminio pierde energía. La masa final es $0.50+0.10=0.60\,\mathrm{kg}$ de agua. No queda hielo.

**Control con la clave:** coinciden fusión total, $T_f\approx42.72\,^\circ\mathrm C$ y $98.84\,\mathrm{kJ}$. El agua inicial recibe calor porque $T_f>20\,^\circ\mathrm C$; su término no puede tratarse como si empezara a cero. Los datos reconstruyen la versión resuelta por la [clave, E1, p. 1](zotero://select/library/items/TZPNLWDL), que difiere de la transcripción anterior. No deben combinarse con los casos siguientes a 160 °C.

**Qué corregir en el intento:** comparación energética (5 puntos), balance y temperatura (5), calor del aluminio (5), principio de conservación (2) y presentación coherente (3), según la clave de E1.

**Variantes anteriores a/b: aluminio a 160 °C sin agua líquida inicial.** Conservan sus planteos y resultados como refuerzo posterior.

#### 1. Elegir el sistema y la decisión inicial

El sistema incluye aluminio y hielo/agua. Está aislado y no hay trabajo apreciable; la conservación de energía se escribe $Q_{\mathrm{Al}}+Q_{\mathrm{hielo/agua}}=0$.

A presión atmosférica, si al final coexisten hielo y agua en equilibrio, $T_f=0\,^\circ\mathrm C$. No sabemos de antemano si quedará hielo. Calculamos primero el calor **disponible hasta llegar a esa temperatura**:

$$Q_{\mathrm{disp}}=m_{\mathrm{Al}}c_{\mathrm{Al}}(160-0)
=(0.80)(900)(160)=115200\,\mathrm J.$$

Esta es una cantidad positiva de energía que puede ceder. El calor con signo del aluminio sería negativo.

#### 2. Caso a: 0.50 kg de hielo

Para fundirlo todo sin subir aún la temperatura del agua se necesitaría:

$$Q_{\mathrm{fusión}}=m_iL_f=(0.50)(334000)=167000\,\mathrm J.$$

Como $115200<167000$, **no se funde todo**. El equilibrio queda a $0\,^\circ\mathrm C$ y toda la energía cedida se emplea en fundir una parte:

$$m_{\mathrm{fundida}}L_f=Q_{\mathrm{disp}}
\quad\Rightarrow\quad
m_{\mathrm{fundida}}=\frac{115200}{334000}=0.34491\,\mathrm{kg}.$$

$$m_{\mathrm{hielo},f}=0.50-0.34491=0.15509\,\mathrm{kg}.$$

**Resultados a:** $T_f=0\,^\circ\mathrm C$, agua $0.345\,\mathrm{kg}$, hielo $0.155\,\mathrm{kg}$ y calor cedido $115.2\,\mathrm{kJ}$ ($Q_{\mathrm{Al}}=-115.2\,\mathrm{kJ}$).

#### 3. Caso b: 0.20 kg de hielo

Ahora $m_iL_f=(0.20)(334000)=66800\,\mathrm J<115200\,\mathrm J$: se funde todo y sobra energía para alcanzar $T_f>0\,^\circ\mathrm C$.

El aluminio cede energía; el hielo primero se funde a $0\,^\circ\mathrm C$ y luego el agua se calienta:

$$m_{\mathrm{Al}}c_{\mathrm{Al}}(160-T_f)
=m_iL_f+m_ic_{\mathrm{agua}}(T_f-0).$$

Desarrollamos y reunimos los términos en $T_f$:

$$115200-720T_f=66800+837.2T_f,$$

$$115200-66800=(720+837.2)T_f,$$

$$T_f=\frac{48400\,\mathrm J}{1557.2\,\mathrm{J/K}}
=31.08\,^\circ\mathrm C.$$

El cociente da un incremento de $31.08\,\mathrm K$ respecto de $0\,^\circ\mathrm C$, por eso la temperatura final es $31.08\,^\circ\mathrm C$.

El calor cedido por el aluminio es:

$$|Q_{\mathrm{Al}}|=(0.80)(900)(160-31.08)
\approx92821\,\mathrm J.$$

**Resultados b:** agua $0.200\,\mathrm{kg}$, sin hielo restante, $T_f\approx31.1\,^\circ\mathrm C$ y calor cedido $92.8\,\mathrm{kJ}$.

**Control:** en a la masa fundida es menor que la inicial; en b $0<T_f<160\,^\circ\mathrm C$ y $66.8\,\mathrm{kJ}$ de fusión más $26.0\,\mathrm{kJ}$ de calentamiento suman los $92.8\,\mathrm{kJ}$ cedidos. Una temperatura negativa obtenida suponiendo fusión total habría indicado que esa suposición era incorrecta.

### T7. Té caliente en un vaso

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T7. Té caliente en un vaso — M · prioridad de examen alta|volver a T7]].

El volumen del té es $200\,\mathrm{cm^3}$. Con $\rho=1.00\,\mathrm{g/cm^3}$, su masa es $200\,\mathrm g=0.200\,\mathrm{kg}$. El té se enfría y el vaso se calienta; el sistema está aislado:

$$m_t c_t(95-T_f)=m_vc_v(T_f-25).$$

Despejando la temperatura:

$$T_f=\frac{m_tc_t(95)+m_vc_v(25)}{m_tc_t+m_vc_v}.$$

$$T_f=
\frac{(0.200)(4186)(95)+(0.150)(840)(25)}
{(0.200)(4186)+(0.150)(840)}
=85.84\,^\circ\mathrm C.$$

**Resultado:** $\boxed{T_f\approx85.8\,^\circ\mathrm C}$.

**Control:** la temperatura final queda entre 25 °C y 95 °C y más cerca de la del té porque su capacidad térmica es mayor.

### T8. Calor específico de la aleación

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T8. Calor específico de una aleación — R · prioridad de examen alta|volver a T8]].

La aleación pierde energía; el agua y el aluminio la ganan. El calorímetro comienza a la misma temperatura que el agua:

$$m_xc_x(540-30.5)
=\left(m_wc_w+m_{\mathrm{Al}}c_{\mathrm{Al}}\right)(30.5-10).$$

Despejamos $c_x$ antes de sustituir:

$$c_x=
\frac{[(0.400)(4186)+(0.200)(900)](20.5)}
{(0.150)(509.5)}
=497.4\,\mathrm{J/(kg\,K)}.$$

**Resultado:** $\boxed{c_x\approx4.97\times10^2\,\mathrm{J/(kg\,K)}}$.

**Control:** la aleación caliente cede energía; incluir el calorímetro aumenta la energía ganada y, por tanto, el valor inferido de $c_x$.

### T11. Tres metales

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T11. Tres metales alcanzan el equilibrio — R · prioridad de examen alta|volver a T11]].

El aluminio se enfría; el hierro y el cobre también se enfrían o se calientan según la temperatura final. Escribimos una sola ecuación de balance con signo:

$$\sum_i m_ic_i(T_f-T_i)=0.$$

Despejando:

$$T_f=
\frac{\sum_i m_ic_iT_i}{\sum_i m_ic_i}
=\frac{(300)(0.897)(80)+(400)(0.449)(50)+(500)(0.386)(30)}
{(300)(0.897)+(400)(0.449)+(500)(0.386)}.$$

$$T_f=\frac{36298}{641.7}=56.56\,^\circ\mathrm C.$$

**Resultado:** $\boxed{T_f\approx56.6\,^\circ\mathrm C}$.

**Control:** $50<T_f<80\,^\circ\mathrm C$: el aluminio cede energía; el hierro y el cobre la absorben. El resultado está entre la temperatura mayor y la menor. No es el promedio simple porque las capacidades térmicas de los bloques son diferentes.

### T33. Recuperar la temperatura inicial de una mezcla

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T33. Recuperar la temperatura inicial de una mezcla — R · prioridad de examen alta|volver a T33]].

#### 1. Caso A — datos y sentido de la transferencia

Convertimos la masa del termómetro: $m_t=0.045\,\mathrm{kg}$. El agua tiene masa $m_a=220\,\mathrm g=0.220\,\mathrm{kg}$. Como el termómetro pasa de $19.0$ a $38.5\,^\circ\mathrm C$, absorbe energía del agua.

#### 2. Balance con la incógnita correcta

El conjunto está aislado; la primera ley da:

$$m_ac_a(T_f-T_{a,i})+m_tc_t(T_f-T_{t,i})=0.$$

Despejamos sin sustituir todavía:

$$m_ac_a(T_{a,i}-T_f)=m_tc_t(T_f-T_{t,i}),$$

$$T_{a,i}=T_f+\frac{m_tc_t(T_f-T_{t,i})}{m_ac_a}.$$

La suma muestra por qué la temperatura inicial del agua debe superar la final.

#### 3. Sustituir y comprobar

El calor ganado por el termómetro es:

$$Q_t=(0.045)(837)(38.5-19.0)=734.47\,\mathrm J.$$

$$T_{a,i}=38.5+\frac{734.47}{(0.220)(4186)}
=38.5+0.7975=39.30\,^\circ\mathrm C.$$

**Resultado:** $T_{a,i}\approx39.3\,^\circ\mathrm C$.

**Control e interpretación:** $19.0<38.5<39.3\,^\circ\mathrm C$. Medir requirió que el termómetro absorbiera calor y redujo unos $0.80\,^\circ\mathrm C$ la temperatura del agua. La lectura describe el equilibrio nuevo, no el estado anterior a medir.

#### 4. Caso B — identificar los tres cuerpos que intercambian calor

El sistema aislado es herradura + agua + recipiente. La herradura pierde energía; el agua y el recipiente ganan energía al pasar de $20$ a $25\,^\circ\mathrm C$. El hierro del recipiente no puede ignorarse: su temperatura también cambia.

Definimos $T_{h,i}$ como temperatura inicial de la herradura. Usamos todas las masas en kg y ambos calores específicos en J/(kg K), tal como se dan en el caso B.

#### 5. Balance y despeje de la temperatura inicial

Sin cambio de fase ni pérdidas, la conservación de energía da:

$$Q_h+Q_a+Q_r=0,$$

$$m_hc_{\mathrm{Fe}}(T_f-T_{h,i})
+m_ac_a(T_f-T_0)+m_rc_{\mathrm{Fe}}(T_f-T_0)=0.$$

Agrupamos los dos cuerpos que se calientan desde $T_0=20\,^\circ\mathrm C$ y pasamos el término de la herradura al otro lado:

$$m_hc_{\mathrm{Fe}}(T_{h,i}-T_f)
=(m_ac_a+m_rc_{\mathrm{Fe}})(T_f-T_0).$$

Dividimos por $m_hc_{\mathrm{Fe}}$ y sumamos $T_f$:

$$T_{h,i}=T_f+
\frac{(m_ac_a+m_rc_{\mathrm{Fe}})(T_f-T_0)}{m_hc_{\mathrm{Fe}}}.$$

#### 6. Sustituir y explicar el resultado

Las capacidades térmicas de agua y recipiente suman:

$$m_ac_a+m_rc_{\mathrm{Fe}}
=(1.35)(4186)+(0.300)(450)
=5786.1\,\mathrm{J/K}.$$

El calor total que reciben es:

$$Q_{\mathrm{ganado}}=(5786.1\,\mathrm{J/K})(5.0\,\mathrm K)
=28930.5\,\mathrm J.$$

La herradura tiene capacidad térmica $(0.400)(450)=180\,\mathrm{J/K}$. Entonces:

$$T_{h,i}=25.0\,^\circ\mathrm C+
\frac{28930.5\,\mathrm J}{180\,\mathrm{J/K}}
=25.0\,^\circ\mathrm C+160.725\,\mathrm K
\approx185.7\,^\circ\mathrm C.$$

El cociente es una **diferencia** de temperatura: un cambio de $160.725\,\mathrm K$ equivale a $160.725\,^\circ\mathrm C$; no hay que restarle $273.15$.

**Control:** el agua gana $28255.5\,\mathrm J$, el recipiente gana $675.0\,\mathrm J$ y la herradura pierde $28930.5\,\mathrm J$. La suma es cero y $20<25<185.7\,^\circ\mathrm C$. El agua tiene mucha más capacidad térmica que la herradura: que el equilibrio quede cerca de la temperatura inicial del agua es coherente.

### T10. Fundir solo la mitad del hielo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T10. Fundir solo la mitad del hielo — R · prioridad de examen media|volver a T10]].

El hielo primero sube de $-4$ °C a 0 °C. Después se funden $0.050\,\mathrm{kg}$, la mitad de la masa:

$$Q_{\mathrm{hielo}}
=(0.100)(2100)(4)+(0.050)(334000)
=840+16700=17540\,\mathrm J.$$

El agua caliente se enfría de 80 °C a 0 °C. Igualamos su calor cedido con el que absorbe el hielo:

$$m_wc_{\mathrm{agua}}(80)=17540,$$

$$m_w=\frac{17540}{(4186)(80)}
=0.05238\,\mathrm{kg}=52.4\,\mathrm g.$$

**Resultado:** se necesitan $\boxed{52.4\,\mathrm g}$ de agua a 80 °C.

**Control:** queda hielo sin fundir, de modo que el equilibrio a 0 °C es coherente con el enunciado.

### T34. Calor latente obtenido de una mezcla

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T34. Calor latente obtenido de una mezcla — R · prioridad de examen media|volver a T34]].

#### 1. Interpretar los estados antes de calcular

El mercurio empieza sólido a su temperatura de fusión. Como termina a $5.06\,^\circ\mathrm C>-39.0\,^\circ\mathrm C$, al final está completamente líquido. Su energía ganada tiene dos partes:

$$Q_{\mathrm{Hg}}=m_{\mathrm{Hg}}L_f
+m_{\mathrm{Hg}}c_{\mathrm{Hg,líquido}}(T_f-T_m).$$

No hay tramo de calentamiento del sólido: ya empieza en el punto de fusión. Agua y calorímetro se enfrían y ceden energía.

#### 2. Escribir y despejar el balance

Por conservación de energía en el conjunto aislado:

$$(m_ac_a+m_{\mathrm{cal}}c_{\mathrm{Al}})(T_i-T_f)
=m_{\mathrm{Hg}}L_f+m_{\mathrm{Hg}}c_{\mathrm{Hg,líquido}}(T_f-T_m).$$

Restamos el calor que calienta al mercurio líquido y dividimos por su masa:

$$L_f=\frac{(m_ac_a+m_{\mathrm{cal}}c_{\mathrm{Al}})(T_i-T_f)
-m_{\mathrm{Hg}}c_{\mathrm{Hg,líquido}}(T_f-T_m)}{m_{\mathrm{Hg}}}.$$

#### 3. Sustituir las energías por separado

$$Q_{\mathrm{cedido}}=[(0.400)(4186)+(0.620)(900)](12.8-5.06)
=17278.78\,\mathrm J.$$

$$Q_{\mathrm{líquido}}=(1.00)(138)[5.06-(-39.0)]
=(1.00)(138)(44.06)=6080.28\,\mathrm J.$$

Por tanto:

$$L_f=\frac{17278.78-6080.28}{1.00}
=11198.5\,\mathrm{J/kg}\approx11.2\,\mathrm{kJ/kg}.$$

**Resultado:** $L_f\approx1.12\times10^4\,\mathrm{J/kg}$.

**Control:** $11.20\,\mathrm{kJ}$ de fusión más $6.08\,\mathrm{kJ}$ de calentamiento suman los $17.28\,\mathrm{kJ}$ cedidos. Asignar toda esa energía a la fusión daría un valor demasiado grande.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase|enunciados de esta familia]] · [[#Transferencia de calor|siguiente familia: transferencia de calor]].

---

## Transferencia de calor

**Práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor|Transferencia de calor]] · **Conceptos:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#4. Transferencia de calor: conducción, convección y radiación]] · **Fórmulas:** [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica#4. Transferencia de calor]].

**Prioridad:** T13 entrena la familia de conducción entre placas recordada por el estudiante para 2025; T12 es el puente de una sola capa. Los datos de ambos ejercicios son del TP.

### T13. Dos placas en serie

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T13. Dos placas y temperatura de contacto — R · antecedente 2025 aportado por el estudiante · prioridad de estudio alta|volver a T13]].

#### 1. Justificar el flujo común y deducir el caso general

En estado estacionario la unión no acumula energía, por lo que la potencia que le llega es la misma que sale. Tomamos $H>0$ de la cara caliente hacia la fría y definimos $R_1=L_1/(k_1A)$ y $R_2=L_2/(k_2A)$. Las caídas de temperatura son:

$$T_h-T_x=HR_1,\qquad T_x-T_c=HR_2.$$

Al sumarlas desaparece $T_x$:

$$T_h-T_c=H(R_1+R_2)
\quad\Rightarrow\quad
H=\frac{T_h-T_c}{R_1+R_2}.$$

Para hallar la temperatura de contacto, sustituimos en $T_x=T_h-HR_1$:

$$T_x=\frac{R_2T_h+R_1T_c}{R_1+R_2}.$$

Esta deducción cubre el ejercicio 17 del TP1 con espesores y conductividades generales. El ejercicio 18 usa exactamente el mismo balance.

#### 2. Aplicar los datos de las placas

El área es $80\,\mathrm{cm^2}=0.0080\,\mathrm{m^2}$ y cada espesor es $0.0030\,\mathrm m$. En serie, las resistencias térmicas se suman:

$$R_1=\frac{L}{k_1A}
=\frac{0.0030}{(48.1)(0.0080)}
=0.007796\,\mathrm{K/W},$$

$$R_2=\frac{0.0030}{(68.2)(0.0080)}
=0.005498\,\mathrm{K/W}.$$

La potencia que atraviesa ambas placas es la misma:

$$H=\frac{100-0}{R_1+R_2}
=\frac{100}{0.013294}
=7.52\times10^3\,\mathrm W.$$

La caída de temperatura en la placa 1 es $HR_1$. Por tanto, su cara de contacto queda a

$$T_{\mathrm{unión}}=100-HR_1
=100-(7521.7)(0.007796)
=41.4\,^\circ\mathrm C.$$

**Resultados:** $\boxed{H\approx7.52\,\mathrm{kW}}$ y $\boxed{T_{\mathrm{unión}}\approx41.4\,^\circ\mathrm C}$.

**Control:** el contacto queda entre 0 °C y 100 °C. La placa de menor conductividad tiene mayor resistencia y mayor caída de temperatura.

### T12. Pérdida por una pared aislante

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T12. Pérdida de calor por una pared aislante — R · refuerzo de conducción · prioridad didáctica alta|volver a T12]].

En estado estacionario, la potencia conducida por una pared plana es

$$H=kA\frac{T_h-T_c}{L}.$$

Convertimos $L=4.0\,\mathrm{cm}=0.040\,\mathrm m$ y reemplazamos:

$$H=(0.040)(1.40)\frac{175-35}{0.040}
=196\,\mathrm W.$$

**Resultado:** $\boxed{H=196\,\mathrm W}$.

**Control:** el calor fluye de la cara caliente a la fría. La respuesta está en W porque es energía por unidad de tiempo.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor|enunciados de esta familia]] · [[#Temperatura y dilatación|siguiente familia: temperatura y dilatación]].

---

## Ejercicios complementarios de los TP

Estos C se estudian después del núcleo de examen. Su prioridad didáctica no indica aparición en los modelos.

## Temperatura y dilatación

**Práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|Temperatura y dilatación]] · **Conceptos:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#2. Temperatura, escalas y expansión térmica]] · **Fórmulas:** [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica#1. Temperatura y escalas]].

### T1. ¿Temperatura, calor o equilibrio?

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T1. ¿Temperatura, calor o equilibrio? — C · sin evidencia de examen · prioridad didáctica alta|volver a T1]].

1. **Falsa.** Los cuerpos tienen energía interna. El calor es energía en tránsito por una diferencia de temperatura, no algo que cada objeto “contiene”.
2. **Falsa al inicio.** $T_A\ne T_B$, por lo que en contacto habrá transferencia neta de energía desde A hacia B.
3. **Falsa en el lenguaje físico.** A transfiere energía como calor; la temperatura es una propiedad del estado y no una sustancia que viaja.
4. **Falsa en general.** La temperatura final depende de la capacidad térmica de cada objeto ($mc$), no solo del promedio aritmético de sus temperaturas. Ese promedio se obtiene únicamente si tienen capacidades térmicas iguales y el conjunto está aislado.

**Control conceptual:** “caliente” describe una temperatura mayor; “ceder calor” describe una transferencia.

### T2. Cambios entre Fahrenheit y Celsius

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T2. Cambios entre Fahrenheit y Celsius — C · sin evidencia de examen · prioridad didáctica media|volver a T2]].

#### 1. De 24 °F a 45 °F

El dato es una diferencia:

$$\Delta T_F=45-24=21\,^\circ\mathrm F.$$

Para diferencias de temperatura no se suma ni se resta 32:

$$\Delta T_C=\frac{5}{9}(21)=11.67\,^\circ\mathrm C.$$

**Resultado:** la temperatura subió $11.7\,^\circ\mathrm C$.

#### 2. De 44 °F a −56 °C

Ahora se mezclan temperaturas expresadas en escalas distintas. Convertimos el estado inicial:

$$T_{i,C}=\frac{5}{9}(44-32)=6.67\,^\circ\mathrm C.$$

Restamos final menos inicial:

$$\Delta T_C=T_f-T_i=-56-6.67=-62.67\,^\circ\mathrm C.$$

**Resultado:** la temperatura disminuyó $62.7\,^\circ\mathrm C$.

**Control:** el signo negativo refleja enfriamiento. No se usa la fórmula de intervalos con $44\,^\circ\mathrm F$ porque 44 es una temperatura, no una diferencia.

### T3. Enfriar el remache

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T3. Enfriar un remache para que entre — C · sin evidencia de examen · prioridad didáctica alta|volver a T3]].

#### Datos y modelo

$$D_i=1.871\,\mathrm{cm},\quad D_f=1.868\,\mathrm{cm},\quad
T_i=20\,^\circ\mathrm C,\quad
\alpha=1.2\times10^{-5}\,^\circ\mathrm C^{-1}.$$

El diámetro es una dimensión lineal. Aplicamos $\Delta D=\alpha D_i\Delta T$ y despejamos:

$$\Delta T=\frac{D_f-D_i}{\alpha D_i}
=\frac{1.868-1.871}{(1.2\times10^{-5})(1.871)}
=-133.62\,^\circ\mathrm C.$$

La temperatura final resulta

$$T_f=T_i+\Delta T=20-133.62=-113.62\,^\circ\mathrm C.$$

**Resultado:** debe enfriarse hasta aproximadamente $\boxed{-114\,^\circ\mathrm C}$ o menos.

**Control:** $\Delta T<0$ y el remache se contrae; la escala de la temperatura final es físicamente consistente con una fuerte refrigeración.

### T4. Dos reglas calibradas a distinta temperatura

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T4. Dos reglas calibradas a temperaturas diferentes — C · sin evidencia de examen · prioridad didáctica media|volver a T4]].

La regla A tiene $L_0=1.000\,\mathrm m$ a $10\,^\circ\mathrm C$. A $15\,^\circ\mathrm C$:

$$L_A=L_0[1+\alpha(15-10)]
=1.000[1+(1.2\times10^{-5})(5)]
=1.000060\,\mathrm m.$$

La regla B tiene $L_0=1.000\,\mathrm m$ a $25\,^\circ\mathrm C$. A $15\,^\circ\mathrm C$:

$$L_B=1.000[1+(1.2\times10^{-5})(15-25)]
=0.999880\,\mathrm m.$$

Por tanto,

$$|L_A-L_B|=0.000180\,\mathrm m=0.180\,\mathrm{mm}.$$

**Resultado:** la diferencia es $\boxed{0.18\,\mathrm{mm}}$. La regla A se expande respecto de su referencia y la B se contrae.

### T5. Coeficiente de expansión de una varilla

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T5. Medir el coeficiente de expansión — C · sin evidencia de examen · prioridad didáctica media|volver a T5]].

$$\Delta L=40.148-40.125=0.023\,\mathrm{cm},\qquad
\Delta T=45-20=25\,^\circ\mathrm C.$$

Despejamos de $\Delta L=\alpha L_0\Delta T$ usando la longitud inicial:

$$\alpha=\frac{0.023}{(40.125)(25)}
=2.293\times10^{-5}\,^\circ\mathrm C^{-1}.$$

**Resultado:** $\boxed{\alpha\approx2.29\times10^{-5}\,^\circ\mathrm C^{-1}}$.

**Control:** cm se cancela con cm; queda inversa de temperatura, como debe tener $\alpha$.

### T6. Agua que rebalsa

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T6. Agua que rebalsa al calentarse — C · sin evidencia de examen · prioridad didáctica media|volver a T6]].

El agua y el vaso parten de $V_0=245\,\mathrm{mL}$ y aumentan su temperatura en $40\,^\circ\mathrm C$. El agua rebalsada es el aumento del líquido menos el aumento de capacidad del vaso:

$$\Delta V_{\mathrm{rebalse}}
=V_0(\beta_{\mathrm{agua}}-\beta_{\mathrm{vidrio}})\Delta T.$$

$$\Delta V_{\mathrm{rebalse}}
=245(210-27)\times10^{-6}(40)\,\mathrm{mL}
=1.7934\,\mathrm{mL}.$$

**Resultado:** se derraman aproximadamente $\boxed{1.79\,\mathrm{mL}}$.

**Control:** $\beta_{\mathrm{agua}}>\beta_{\mathrm{vidrio}}$, así que el exceso debe ser positivo.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|enunciados de esta familia]] · [[#Curvas de calentamiento|siguiente familia: curvas de calentamiento]].

---

## Curvas de calentamiento

**Complementario C:** contenido del TP sin aparición directa identificada en los modelos revisados. [[Unidades/05 - Termodinámica/Teoría/05 - Guía breve de termodinámica|Guía breve]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Curvas de calentamiento|Enunciados]].

### T9. Curva de calentamiento

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T9. Leer una curva de calentamiento — C · sin evidencia de examen · prioridad didáctica media|volver a T9]].

La muestra tiene $m=0.500\,\mathrm{kg}$ y recibe energía con potencia constante $P=40\,\mathrm{kJ/min}$.

![[imagenes/termodinamica-curva-calentamiento.svg]]

#### Calor latente

La meseta dura de $1.0$ a $2.5\,\mathrm{min}$, es decir, $1.5\,\mathrm{min}$. Esa energía cambia de fase:

$$Q_f=P\Delta t=(40)(1.5)=60\,\mathrm{kJ},\qquad
L_f=\frac{Q_f}{m}=\frac{60}{0.500}=120\,\mathrm{kJ/kg}.$$

#### Calor específico del sólido

El primer tramo dura $1.0\,\mathrm{min}$ y la temperatura sube de 0 °C a 10 °C:

$$c_s=\frac{P\Delta t}{m\Delta T}
=\frac{40\,\mathrm{kJ}}{(0.500\,\mathrm{kg})(10\,\mathrm K)}
=8.0\,\mathrm{kJ/(kg\,K)}.$$

#### Calor específico del líquido

El último tramo dura $4.0-2.5=1.5\,\mathrm{min}$ y la temperatura aumenta de 10 °C a 40 °C:

$$c_l=\frac{(40\,\mathrm{kJ/min})(1.5\,\mathrm{min})}
{(0.500\,\mathrm{kg})(30\,\mathrm K)}
=4.0\,\mathrm{kJ/(kg\,K)}.$$

**Resultados:** $\boxed{L_f=120\,\mathrm{kJ/kg}}$, $\boxed{c_s=8.0\,\mathrm{kJ/(kg\,K)}}$ y $\boxed{c_l=4.0\,\mathrm{kJ/(kg\,K)}}$.

> [!warning] Diferencia con el resumen resuelto del TP
> El resumen archivado asigna $4.0\,\mathrm{kJ/(kg\,K)}$ también al sólido. En el gráfico original de la p. 2, el primer tramo parte de 0 °C y termina en 10 °C; con esos datos, el cálculo da $8.0\,\mathrm{kJ/(kg\,K)}$. La resolución de esta guía sigue los puntos visibles del gráfico original.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Curvas de calentamiento|enunciados de esta familia]] · [[#Radiación y elección de materiales|siguiente familia: radiación y elección de materiales]].

---

## Radiación y elección de materiales

Estos C amplían radiación y comparación de materiales. Se estudian después del bloque de conducción entre placas. [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Radiación y elección de materiales|Enunciados]].

### T14. Radiación neta de una persona

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T14. Radiación neta de una persona — C · sin evidencia de examen · prioridad didáctica alta|volver a T14]].

Convertimos las temperaturas:

$$T_{\mathrm{piel}}=37+273.15=310.15\,\mathrm K,\qquad
T_{\mathrm{amb}}=20+273.15=293.15\,\mathrm K.$$

La potencia neta es

$$P_{\mathrm{net}}
=\varepsilon\sigma A(T_{\mathrm{piel}}^4-T_{\mathrm{amb}}^4)
=(0.85)(5.67\times10^{-8})(1.40)
(310.15^4-293.15^4)
=126.0\,\mathrm W.$$

En un minuto:

$$E=P\Delta t=(126.0\,\mathrm{J/s})(60\,\mathrm s)
=7.56\times10^3\,\mathrm J.$$

**Resultados:** pierde $\boxed{126\,\mathrm W}$ o $\boxed{7.56\,\mathrm{kJ}}$ por minuto.

**Control:** la piel está más caliente que la habitación, así que el intercambio neto es hacia fuera.

### T15. Potencia radiada por un filamento

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T15. Potencia radiada por un filamento — C · sin evidencia de examen · prioridad didáctica media|volver a T15]].

Convertimos el área y la temperatura:

$$A=50\,\mathrm{mm^2}=50\times10^{-6}\,\mathrm{m^2},\qquad
T=2127+273.15\approx2400\,\mathrm K.$$

Con el supuesto de que toda la potencia suministrada se emite:

$$P=\varepsilon\sigma AT^4
=(0.83)(5.67\times10^{-8})(50\times10^{-6})(2400)^4
=78.1\,\mathrm W.$$

**Resultado:** se necesitan aproximadamente $\boxed{78\,\mathrm W}$.

**Control:** la conversión de mm² a m² es crucial; el área es muy pequeña aunque la temperatura sea elevada.

### T35. Elegir un material para reducir las pérdidas

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T35. Elegir un material para reducir las pérdidas — C · sin evidencia de examen · prioridad didáctica media|volver a T35]].

#### 1. Elegir la relación y comparar

Para una pared plana en conducción estacionaria:

$$H=kA\frac{\Delta T}{L}.$$

$H$ es energía transferida por segundo, en W. Con área, espesor y temperaturas iguales, menor conductividad implica menor pérdida: elegimos **adobe**.

Convertimos $L=0.200\,\mathrm m$ y calculamos $\Delta T=26-1=25\,\mathrm K$.

#### 2. Potencias y reducción porcentual

$$H_{\mathrm{ladrillón}}=(0.97)(1.40)\frac{25}{0.200}
=169.75\,\mathrm W,$$

$$H_{\mathrm{adobe}}=(0.40)(1.40)\frac{25}{0.200}
=70.0\,\mathrm W.$$

La razón muestra qué fracción de la pérdida original permanece:

$$\frac{H_{\mathrm{adobe}}}{H_{\mathrm{ladrillón}}}
=\frac{0.40}{0.97}=0.4124.$$

El adobe deja pasar el $41.24\%$ de la potencia del ladrillón. La reducción es el resto:

$$\mathrm{reducción}=\frac{169.75-70.0}{169.75}\times100\%
=58.8\%.$$

#### 3. Espesor equivalente de ladrillón

Para el mismo $A$ y $\Delta T$, igualamos las dos potencias:

$$\frac{k_{\mathrm{ladrillón}}}{L_{\mathrm{ladrillón}}}
=\frac{k_{\mathrm{adobe}}}{L_{\mathrm{adobe}}}.$$

Multiplicando en cruz y despejando:

$$L_{\mathrm{ladrillón}}
=\frac{k_{\mathrm{ladrillón}}}{k_{\mathrm{adobe}}}L_{\mathrm{adobe}}
=\frac{0.97}{0.40}(0.200\,\mathrm m)
=0.485\,\mathrm m=48.5\,\mathrm{cm}.$$

**Control:** el material más conductor necesita más espesor para igualar el aislamiento: $48.5\,\mathrm{cm}>20.0\,\mathrm{cm}$. Tanto las potencias como el espesor responden a $k/L$.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Radiación y elección de materiales|enunciados de esta familia]] · [[#Otto, refrigeración y entropía|siguiente familia: otto, refrigeración y entropía]].

---

## Otto, refrigeración y entropía

**Complementario C:** contenido del TP sin aparición directa identificada en los modelos revisados. [[Unidades/05 - Termodinámica/Teoría/05 - Guía breve de termodinámica|Guía breve]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Otto, refrigeración y entropía|Enunciados]].

### T21. Ciclo Otto ideal

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T21. Eficiencia ideal de un ciclo Otto — C · sin evidencia de examen · prioridad didáctica media|volver a T21]].

La relación de compresión y $\gamma$ determinan la eficiencia del modelo Otto:

$$e=1-\frac{1}{r^{\gamma-1}}
=1-\frac{1}{9.50^{0.40}}
=0.59364=59.36\%.$$

El resto del calor recibido se rechaza:

$$|Q_C|=Q_H(1-e)
=(10000)(1-0.59364)
=4063.6\,\mathrm J.$$

**Resultados:** $\boxed{e\approx59.4\%}$ y $\boxed{|Q_C|\approx4.06\,\mathrm{kJ}}$.

**Control:** la eficiencia es menor que 100 %; el resultado corresponde a un ciclo ideal, no al rendimiento medido de un motor real.

### T22. Refrigerador por ciclo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T22. Trabajo requerido por un refrigerador — C · sin evidencia de examen · prioridad didáctica alta|volver a T22]].

El coeficiente del refrigerador compara el calor que se extrae con el trabajo que se consume:

$$COP_R=\frac{|Q_C|}{W}
\quad\Longrightarrow\quad
W=\frac{34000}{2.10}=16190.5\,\mathrm J.$$

El balance de energía es

$$|Q_H|=|Q_C|+W=34000+16190.5=50190.5\,\mathrm J.$$

**Resultados:** $\boxed{W\approx16.2\,\mathrm{kJ}}$ y $\boxed{|Q_H|\approx50.2\,\mathrm{kJ}}$ por ciclo.

**Control:** el refrigerador expulsa más calor al ambiente del que extrae del compartimiento porque también recibe trabajo.

### T23. Potencia para fabricar hielo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T23. Potencia para fabricar hielo — C · sin evidencia de examen · prioridad didáctica media|volver a T23]].

Primero calculamos el calor que se extrae en cada etapa para $m=0.030\,\mathrm{kg}$.

1. Enfriar el agua de 22 °C a 0 °C:

$$Q_1=mc_w\Delta T
=(0.030)(4190)(22)=2765.4\,\mathrm J.$$

2. Congelarla a 0 °C:

$$Q_2=mL_f=(0.030)(334000)=10020\,\mathrm J.$$

3. Enfriar el hielo de 0 °C a −20 °C:

$$Q_3=mc_i\Delta T
=(0.030)(2100)(20)=1260\,\mathrm J.$$

Por minuto, el refrigerador extrae

$$|Q_C|=Q_1+Q_2+Q_3=14045.4\,\mathrm J.$$

La potencia de enfriamiento es $|Q_C|/60=234.09\,\mathrm W$. Como $COP_R=|Q_C|/W_{\mathrm{entrada}}$:

$$P_{\mathrm{entrada}}=\frac{234.09}{3.00}=78.03\,\mathrm W.$$

**Resultado:** necesita aproximadamente $\boxed{78.0\,\mathrm W}$ de potencia mecánica.

### T25. Entropía al fundir hielo

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T25. Entropía al fundir hielo — C · sin evidencia de examen · prioridad didáctica alta|volver a T25]].

La cantidad de energía necesaria para fundir el hielo es

$$Q=mL_f=(0.350)(334000)=116900\,\mathrm J.$$

El hielo se funde reversiblemente a $273.15\,\mathrm K$ para calcular el cambio de entropía del agua:

$$\Delta S_{\mathrm{agua}}=\frac{Q}{T_{\mathrm{fusión}}}
=\frac{116900}{273.15}
=+427.97\,\mathrm{J/K}.$$

La fuente a $25\,^\circ\mathrm C$ pierde esa energía a $298.15\,\mathrm K$:

$$\Delta S_{\mathrm{fuente}}=\frac{-Q}{T_{\mathrm{fuente}}}
=\frac{-116900}{298.15}
=-392.08\,\mathrm{J/K}.$$

Sumamos sistema y entorno:

$$\Delta S_{\mathrm{total}}=427.97-392.08
=+35.89\,\mathrm{J/K}.$$

**Resultados:** agua $\boxed{+428\,\mathrm{J/K}}$, fuente $\boxed{-392\,\mathrm{J/K}}$, total $\boxed{+35.9\,\mathrm{J/K}}$.

**Interpretación:** la entropía de la fuente disminuye, pero la del conjunto aumenta; esto concuerda con un proceso espontáneo e irreversible.

### T26. Entropía del té y del aire

**Enunciado:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T26. Entropía de té que se enfría — C · sin evidencia de examen · prioridad didáctica alta|volver a T26]].

Convertimos las temperaturas del agua:

$$T_i=358.15\,\mathrm K,\qquad T_f=293.15\,\mathrm K.$$

El cambio de entropía del agua se calcula como si el cambio se realizara reversiblemente:

$$\Delta S_{\mathrm{agua}}
=mc\ln\left(\frac{T_f}{T_i}\right)
=(0.250)(4190)\ln\left(\frac{293.15}{358.15}\right)
=-209.78\,\mathrm{J/K}.$$

El calor que pierde el agua y gana el aire es

$$Q_{\mathrm{aire}}=mc(T_i-T_f)
=(0.250)(4190)(65)=68087.5\,\mathrm J.$$

El aire se modela como un foco que permanece a $293.15\,\mathrm K$:

$$\Delta S_{\mathrm{aire}}=\frac{Q_{\mathrm{aire}}}{T_{\mathrm{aire}}}
=\frac{68087.5}{293.15}
=+232.26\,\mathrm{J/K}.$$

Por tanto,

$$\Delta S_{\mathrm{total}}=-209.78+232.26
=+22.48\,\mathrm{J/K}.$$

**Resultados:** agua $\boxed{-210\,\mathrm{J/K}}$, aire $\boxed{+232\,\mathrm{J/K}}$ y conjunto $\boxed{+22.5\,\mathrm{J/K}}$.

**Control:** el agua se enfría y su entropía disminuye; el aumento del aire es mayor, así que el cambio total permanece positivo.

**Navegación:** [[#Índice de familias|índice de familias]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Otto, refrigeración y entropía|enunciados de esta familia]].

---
