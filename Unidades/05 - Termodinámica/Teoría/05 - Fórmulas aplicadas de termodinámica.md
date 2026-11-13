---
tags: [fisica-aplicada, teoria, formulas, unidad-05, termodinamica]
---

# Fórmulas aplicadas de termodinámica

Usa esta nota como apoyo al resolver: primero identifica el sistema, el proceso y la incógnita. El origen conceptual y las condiciones de cada relación se explican en [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica]]. Para practicar, usa [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|Temperatura y dilatación]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase|Calorimetría y cambios de fase]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor|Transferencia de calor]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|Gases ideales y primera ley]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|Segunda ley y máquinas térmicas]].

## 1. Temperatura y escalas

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#2. Temperatura, escalas y expansión térmica|leer el desarrollo conceptual]].

$$T_{\mathrm K}=T_{^\circ\mathrm C}+273.15$$

$$T_{^\circ\mathrm F}=\frac{9}{5}T_{^\circ\mathrm C}+32,\qquad
\Delta T_{^\circ\mathrm C}=\frac{5}{9}\Delta T_{^\circ\mathrm F}.$$

- **Elige la relación:** para valores de temperatura convierte con el desplazamiento; para intervalos usa solo la razón entre tamaños de grado.
- **Unidades:** diferencias en °C y K tienen el mismo valor numérico. Convierte temperaturas a K en cocientes termodinámicos, radiación y entropía.
- **Comprueba:** una diferencia de temperatura no depende del desplazamiento arbitrario del cero de escala.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 2. Dilatación

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#2. Temperatura, escalas y expansión térmica|leer el desarrollo conceptual]].

$$\Delta L=\alpha L_0\Delta T,\qquad L_f=L_0(1+\alpha\Delta T).$$

$$\Delta V=\beta V_0\Delta T,\qquad
\beta_{\mathrm{sólido}}\approx3\alpha\ \text{(isotrópico)}.$$

Para el volumen que rebalsa un recipiente lleno:

$$V_{\mathrm{derramado}}\approx
V_0(\beta_{\mathrm{líquido}}-\beta_{\mathrm{recipiente}})\Delta T
\quad\text{si el exceso es positivo}.$$

- **Elige la relación:** $\alpha$ para una longitud o diámetro; $\beta$ para el volumen total de un sólido o líquido; diferencia de coeficientes para el desborde.
- **Supuestos:** expansión libre y pequeña, temperatura uniforme y coeficientes aproximadamente constantes. Para desborde, recipiente inicialmente lleno y ambos materiales con el mismo $\Delta T$; si el exceso es negativo queda espacio libre.
- **Signo y unidades:** $\Delta T=T_f-T_i$; $\alpha$ y $\beta$ tienen unidades $\mathrm{K^{-1}}$ o $^\circ\mathrm C^{-1}$. El resultado de $\Delta L$ debe tener unidad de longitud.
- **Comprueba:** un agujero en una placa se dilata junto con la placa; no se contrae al calentar.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 3. Calor sensible, cambio de fase y mezcla

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#3. Calor, calor específico y calorimetría|leer el desarrollo conceptual]].

$$Q=mc\Delta T\quad\text{(sin cambio de fase)},\qquad
|Q|=mL\quad\text{(masa transformada a T constante)}.$$

$$\sum_i Q_i=0\quad\text{(sistema aislado).}$$

- **Elige la relación:** revisa primero si cambia la temperatura, la fase o ambas; divide en etapas y suma sus energías.
- **Símbolos:** $m$ masa, $c$ calor específico, $L$ calor latente, $\Delta T=T_f-T_i$.
- **Unidades SI:** $Q$ en J, $m$ en kg, $c$ en $\mathrm{J/(kg\,K)}$, $L$ en J/kg. Las tablas también pueden dar $c$ por gramo: mantén unidades compatibles.
- **Signos:** $Q>0$ al absorber y $Q<0$ al ceder. En cambios de fase, $Q=+mL$ para fundir/vaporizar y $Q=-mL$ para solidificar/condensar. Incluye recipiente y calorímetro si su capacidad térmica es apreciable.
- **Condiciones:** $mc\Delta T$ corresponde a una sola fase y $c$ constante apropiado al proceso. El balance de mezcla supone aislamiento del conjunto y trabajo despreciable; cada parte sí intercambia calor con las otras.
- **Curva con potencia absorbida constante y pérdidas despreciables:** $Q=P\Delta t$. En las zonas inclinadas $Q=mc\Delta T$; en las mesetas $Q=mL$.
- **Decisión de fase:** con hielo inicialmente a $0\,^\circ\mathrm C$, compara primero la energía disponible positiva $E_{\mathrm{disp}}$ que cedería el cuerpo caliente al llegar a $0\,^\circ\mathrm C$ con $m_iL_f$. Si no alcanza, $T_f=0\,^\circ\mathrm C$ y $m_{\mathrm{fundida}}=E_{\mathrm{disp}}/L_f$. Si sobra, suma fusión y calentamiento del agua en el balance. Véase [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T29. ¿Se funde todo el hielo? Dos resultados posibles — R · reconstrucción de la clave 2026 · prioridad de estudio alta|T29]].
- **Despeje inverso:** si se conoce $T_f$, se puede despejar una temperatura inicial, $c$ o $L_f$ del mismo balance; no hace falta una ley nueva. Véanse [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T33. Recuperar la temperatura inicial de una mezcla — R · prioridad de examen alta|T33]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T34. Calor latente obtenido de una mezcla — R · prioridad de examen media|T34]].
- **Comprueba:** sin fuentes adicionales ni trabajo apreciable, el equilibrio queda entre las temperaturas iniciales y debe ser compatible con las fases que permanecen.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 4. Transferencia de calor

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#4. Transferencia de calor: conducción, convección y radiación|leer el desarrollo conceptual]].

### Conducción estacionaria

$$H=\left|\frac{dQ}{dt}\right|=kA\frac{T_h-T_c}{L},\qquad
R_{\mathrm{térmica}}=\frac{L}{kA},\qquad
H=\frac{T_h-T_c}{\sum_i R_i}.$$

- **Elige la relación:** pared plana, conducción en una dirección, propiedades uniformes, temperaturas de superficie estables, sin generación ni pérdidas laterales. $H$ es una magnitud positiva de potencia en W. En serie suma $R_i$ con contacto ideal; la misma potencia atraviesa cada capa.
- **Unión de dos capas:** $T_x=T_h-HR_1=T_c+HR_2$. Estacionario significa sin acumulación de energía, no temperatura uniforme. Las temperaturas del aire solo sustituyen a las de las caras si se desprecia la resistencia aire–pared.
- **Unidades:** $H$ en W, $k$ en $\mathrm{W/(m\,K)}$, $A$ en $\mathrm{m^2}$, $L$ en m y $T_h-T_c$ en K o °C.
- **Interpretación:** menor $k$ o mayor espesor reducen la transferencia; no confundas flujo por área con potencia total.

#### Despeje para varias placas consecutivas

En serie, $H_1=H_2=\cdots=H$; cada placa cumple $\Delta T_i=HR_i$. Para dos placas con unión a $T_x$:

$$
(T_h-T_x)+(T_x-T_c)=HR_1+HR_2
\ \Longrightarrow\ T_h-T_c=H(R_1+R_2)
\ \Longrightarrow\ H=\frac{T_h-T_c}{R_1+R_2}.
$$

Para tres placas de **igual área $A$**, reemplaza cada resistencia antes de calcular:

$$
H=\frac{T_h-T_c}{\dfrac{L_1}{k_1A}+\dfrac{L_2}{k_2A}+\dfrac{L_3}{k_3A}}
=\frac{A(T_h-T_c)}{\dfrac{L_1}{k_1}+\dfrac{L_2}{k_2}+\dfrac{L_3}{k_3}}.
$$

- **Orden de cálculo:** convierte áreas y espesores; calcula cada $R_i=L_i/(k_iA)$; suma las resistencias; divide la diferencia total por esa suma. El resultado es la potencia de cada placa y del conjunto.
- **Temperaturas de unión:** calcula $\Delta T_i=HR_i$ y resta las caídas desde la cara caliente: $T_1=T_h-HR_1$, $T_2=T_h-H(R_1+R_2)$, etc.
- **Control:** las caídas deben sumar $T_h-T_c$; al calcular $H_i=k_iA\Delta T_i/L_i$, todas deben dar el mismo $H$. No uses la diferencia total en cada placa ni sumes sus potencias. Si todas tienen el mismo $k$, se recupera $H=kA(T_h-T_c)/(L_1+L_2+\cdots+L_n)$.

**Desarrollo y ejemplo de tres placas:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Capas en serie y temperatura de unión|ver cada paso del despeje]].

### Radiación

$$P_{\mathrm{emitida}}=\varepsilon\sigma AT^4,\qquad
P_{\mathrm{neta}}=\varepsilon\sigma A
(T_{\mathrm{sup}}^4-T_{\mathrm{amb}}^4).$$

$\varepsilon$ es adimensional entre 0 y 1 y $\sigma=5.67\times10^{-8}\,\mathrm{W/(m^2\,K^4)}$. La expresión neta supone una superficie gris frente a un entorno amplio y aproximadamente uniforme.

- **Elige la forma neta** para pérdida o ganancia por radiación hacia el ambiente. Usa emisión si se pide esa magnitud o se desprecia la absorción ambiental, como en T15. $P_{\mathrm{neta}}$ se toma positiva hacia afuera; su signo es opuesto al calor recibido por el cuerpo.
- **Unidades:** todas las temperaturas en K. Convierte el área a $\mathrm{m^2}$.
- **Comprueba:** si ambas temperaturas son iguales, la potencia neta es cero; si $T_{\mathrm{sup}}>T_{\mathrm{amb}}$, el cuerpo pierde energía.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 5. Estado de un gas ideal

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#5. Gas ideal y variables de estado|leer el desarrollo conceptual]].

$$pV=nRT,\qquad n=\frac{m}{M}.$$

- **Elige la relación:** gas diluido, en equilibrio y con cantidad fija para conectar sus estados. Si $n$ no cambia, también puedes usar $p_1V_1/T_1=p_2V_2/T_2$.
- **Unidades SI:** presión absoluta $p$ en Pa, $V$ en $\mathrm{m^3}$, $n$ en mol, $T$ en K y $R=8.314\,\mathrm{J/(mol\,K)}$. $M$ es masa molar, con unidad de masa compatible con $m$; $1\,\mathrm L=10^{-3}\,\mathrm{m^3}$.
- **Alcance:** conecta estados de equilibrio; no fija por sí sola el trabajo ni el calor del camino.
- **Comprueba:** $pV$ tiene unidad de energía y debe ser positivo para un estado físico.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 6. Trabajo y primera ley

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#6. Primera ley: el balance de energía|leer el desarrollo conceptual]].

$$W_{\mathrm{por\ el\ sistema}}=\int_{V_i}^{V_f}p\,dV,\qquad
\Delta U=Q-W.$$

Para un gas ideal:

$$\Delta U=nC_V\Delta T,\qquad
C_P-C_V=R,\qquad\gamma=\frac{C_P}{C_V}.$$

- **Condiciones:** $\Delta U=Q-W$ se aplica aquí a un sistema cerrado sin cambios apreciables de energía cinética ni potencial del conjunto. En la integral, usar $p$ del gas requiere evolución mecánica cuasiestática sin disipación; en una expansión brusca no se sustituye arbitrariamente la presión inicial.
- **Convención de esta unidad:** $Q>0$ entra al sistema; $W>0$ lo realiza el sistema. Si una fuente usa trabajo hecho *sobre* el sistema, su signo es el opuesto.
- **Trabajo a presión constante:** $W=p(V_f-V_i)$; el área bajo la trayectoria en el plano $p$–$V$ da el trabajo.
- **Tramo recto inclinado:** $W=\frac{p_i+p_f}{2}(V_f-V_i)$; es el área de un trapecio y requiere que $p(V)$ sea lineal. Una recta inclinada no es una isoterma. Practica [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T28. Interpretar el ciclo triangular de los modelos — M · prioridad de examen alta|T28]].
- **Conversiones del gráfico:** $1\,\mathrm{kPa\,m^3}=1000\,\mathrm J$; $1\,\mathrm{m^3}=1000\,\mathrm L$; $1\,\mathrm{kPa\,L}=1\,\mathrm J$.
- **Capacidad calorífica:** $C_V$ y $C_P$ son molares, en $\mathrm{J/(mol\,K)}$; $c$ es específica por masa, en $\mathrm{J/(kg\,K)}$. Para gas ideal de cantidad fija y $C_V$ constante, $\Delta U=nC_V\Delta T$ vale en cualquier trayectoria; identificar además $Q=nC_V\Delta T$ exige volumen constante y solo trabajo de expansión. De $\gamma=C_P/C_V$ se despeja $C_V=R/(\gamma-1)$.
- **Comprueba:** la ecuación debe cerrar con $\Delta U=Q-W$ y con el signo físico de expansión o compresión.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 7. Procesos de un gas ideal

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#7. Procesos termodinámicos y ciclos|leer el desarrollo conceptual]].

| Proceso | Relaciones útiles | Condición del modelo |
|---|---|---|
| Isocórico | $W=0$; $Q=\Delta U=nC_V\Delta T$ | Volumen constante. |
| Isobárico | $W=p\Delta V=nR\Delta T$; $Q=nC_P\Delta T$ | Presión constante. |
| Isotérmico | $\Delta U=0$; $W=Q=nRT\ln(V_f/V_i)$ | Gas ideal, temperatura constante, proceso cuasiestático para calcular $W$. |
| Adiabático | $Q=0$; $p_iV_i^\gamma=p_fV_f^\gamma$; $T_iV_i^{\gamma-1}=T_fV_f^{\gamma-1}$ | Gas ideal, cantidad fija, adiabática reversible y capacidades constantes para las relaciones de potencias. |

Para trabajo adiabático del gas:

$$W=\frac{p_iV_i-p_fV_f}{\gamma-1}.$$

- **Elección:** identifica qué se mantiene constante a partir del proceso descrito, no del dato que sea más fácil usar.
- **Unidades:** en $pV$, usa Pa y $\mathrm{m^3}$ para obtener J. En el logaritmo de un proceso isotérmico la razón de volúmenes no tiene unidades.
- **Comprueba:** en una expansión adiabática que hace trabajo contra una carga, $W>0$, $\Delta U<0$ y la temperatura del gas ideal disminuye. En expansión libre aislada, $W=0$ aunque aumente el volumen: no se aplican las potencias de la adiabática reversible.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 8. Ciclos y máquinas térmicas

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#8. Motores y refrigeradores: objetivos y rendimientos|leer el desarrollo conceptual]].

En un ciclo, $\Delta U_{\mathrm{ciclo}}=0$ y $W_{\mathrm{neto}}=Q_{\mathrm{neto}}$. Para eficiencia, $Q_H$ suma solo los calores positivos; no es el calor neto, que ya resta los rechazados.

### Motor

$$Q_H=W+|Q_C|,\qquad
e=\frac{W}{Q_H}=1-\frac{|Q_C|}{Q_H},\qquad
P=\frac{W}{\Delta t}.$$

### Tasas de calor y combustible

$$\dot Q_H=\frac{P_{\mathrm{salida}}}{e},\qquad
|\dot Q_C|=\dot Q_H-P_{\mathrm{salida}},\qquad Q=\dot Q\Delta t\ \text{si la tasa es constante}.$$

- **Cuándo:** el dato «por segundo» pide una tasa en J/s o W, no J por ciclo. El punto sobre $Q$ indica derivada temporal o tasa media en operación periódica. Véase [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T32. Calor suministrado y desechado por segundo — M · prioridad de examen alta|T32]].

$$m_{\mathrm{comb}}=\frac{Q_H}{q_{\mathrm{comb}}}
=\frac{W}{e\,q_{\mathrm{comb}}}.$$

- **Cuándo:** consumo de combustible con transferencia completa de su energía liberada al calor que recibe el motor.
- **Símbolos y unidades:** $q_{\mathrm{comb}}$ es poder calorífico en J/kg; $Q_H$ y $W$ deben referirse al mismo intervalo o ciclo. Dividir J entre J/kg da kg. Si se conoce una eficiencia adicional de aporte $\eta_{\mathrm{aporte}}$, usa $m=Q_H/(\eta_{\mathrm{aporte}}q_{\mathrm{comb}})$.
- **Comprueba:** el calor del combustible debe cubrir $Q_H$, que supera el trabajo útil. Véase [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T30. Carnot y consumo de combustible por ciclo — M · prioridad de examen alta|T30]].

### Refrigerador y bomba de calor

En estas relaciones $W$ es la **magnitud positiva del trabajo de entrada**. Respecto de la sustancia de trabajo, $W_{\mathrm{por\ el\ sistema}}=-W_{\mathrm{entrada}}$; se mantiene la primera ley.

$$|Q_H|=|Q_C|+W,\qquad
COP_R=\frac{|Q_C|}{W},\qquad
COP_{BC}=\frac{|Q_H|}{W}=COP_R+1.$$

### Límites ideales

$$e_{\mathrm{Carnot}}=1-\frac{T_C}{T_H},\qquad
COP_{R,\mathrm{Carnot}}=\frac{T_C}{T_H-T_C}.$$

$$e_{\mathrm{Otto}}=1-\frac{1}{r^{\gamma-1}},\qquad
r=\frac{V_{\max}}{V_{\min}}.$$

- **Elección:** en un motor el resultado útil es $W$; en un refrigerador es $|Q_C|$. No intercambies esos numeradores.
- **Supuestos específicos:** Carnot usa dos focos de temperatura constante y reversibilidad para la igualdad; una máquina real puede quedar por debajo. Otto requiere su ciclo ideal de dos adiabáticas reversibles y dos isocóricas con $\gamma$ constante.
- **Unidades:** eficiencia y COP son razones sin unidad. Las temperaturas de Carnot van en kelvin; la eficiencia se expresa como fracción o porcentaje.
- **Comprobación:** para un motor cíclico entre los mismos dos focos, $0\le e\le e_{\mathrm{Carnot}}$. La igualdad corresponde al reversible ideal; el irreversible queda por debajo. El COP de refrigeración no es una eficiencia porcentual.
- **Propuesta y trabajo máximo:** calcula primero $e_{\mathrm{propuesta}}=W_{\mathrm{propuesta}}/Q_H$ y compárala con $e_C$. Equivalentemente, $W_{\mathrm{propuesta}}\le W_{\max}=e_CQ_H$. El balance de energía por sí solo no asegura viabilidad; practica [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T31. Máquina real y propuesta imposible — M · prioridad de examen alta|T31]].

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

## 9. Cambios de entropía

**Origen y supuestos explicados:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#9. Segunda ley y entropía|leer el desarrollo conceptual]].

$$\Delta S=\int_i^f\frac{\delta Q_{\mathrm{rev}}}{T}.$$

Casos de uso directo:

$$\Delta S=\frac{Q_{\mathrm{rev}}}{T}
\quad\text{(proceso isotérmico reversible)},$$

$$\Delta S=\frac{mL}{T_{\mathrm{fase}}}
\quad\text{(fusión o vaporización; signo opuesto al invertir)},$$

$$\Delta S=mc\ln\left(\frac{T_f}{T_i}\right)
\quad\text{(sin cambio de fase)}.$$

- **Elige la relación:** la forma $mc\ln(T_f/T_i)$ se usa aquí para sólidos/líquidos con $c$ constante y trabajo despreciable. El cambio de entropía es entre dos estados. Si el proceso real es irreversible, imagina una trayectoria reversible equivalente para calcularlo.
- **Entorno:** si un foco a $T_{\mathrm{foco}}$ recibe calor $Q_{\mathrm{foco}}$, $\Delta S_{\mathrm{foco}}=Q_{\mathrm{foco}}/T_{\mathrm{foco}}$ con signo positivo si el foco absorbe calor.
- **Unidades:** J/K; todas las temperaturas en K y el argumento del logaritmo es una razón sin unidad.
- **Comprueba:** incluye todo el entorno relevante para aplicar $\Delta S_{\mathrm{total}}\ge0$. Solo la adiabática reversible garantiza $\Delta S=0$; $Q=0$ no basta si hay irreversibilidades. Comprueba también el signo según fusión o solidificación.

> [!tip] Comprueba lo aprendido
> Al terminar este bloque, ve a [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la autoevaluación de fórmulas]]. Intenta responder antes de abrir la explicación y vuelve aquí si necesitas revisar el razonamiento.

**Sigue:** [[Unidades/05 - Termodinámica/Teoría/05 - Guía breve de termodinámica|lectura breve]] · [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Repaso del módulo|repaso completo]].
