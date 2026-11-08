---
tags: [fisica-aplicada, teoria, guia-breve, unidad-05, termodinamica]
---

# Guía breve de termodinámica

Esta guía te ayuda a **reconocer el problema, elegir el principio y comenzar a resolver**. Lee solo el tramo que necesitas, tapa el texto, reexplica la idea y responde antes de abrir la explicación. Después intenta el ejercicio enlazado. Estima **5–10 minutos de lectura y recuperación por tramo**, sin contar la práctica; los ciclos completos pueden requerir más.

## Elige por dónde entrar

| Si el ejercicio pregunta por… | Lee este tramo | Primera práctica |
|---|---|---|
| Calor, temperatura o conversión de escalas | [[#Temperatura y cambios de escala\|Temperatura]] | T1–T2 (C) |
| Cambios de tamaño o líquido que rebalsa | [[#Dilatación: cambio de tamaño\|Dilatación]] | T3; luego T4–T6 (C) |
| Temperatura de equilibrio o propiedad desconocida | [[#Mezclas sin cambio de fase\|Balance de mezcla]] | T7 (M); T8/T11/T33 (R) |
| Hielo, fusión o curva de calentamiento | [[#Fases: decidir qué cambia antes de calcular\|Cambios de fase]] | T29/T10/T34 (R); T9 (C) |
| Pérdidas a través de paredes o radiación | [[#3. Cómo se transfiere el calor\|Transferencia]] | T12–T15 y T35 (C) |
| Trabajo, temperatura o energía interna de un gas | [[#Estado del gas, trabajo y balance\|Gas y primera ley]] | T27 (M) |
| Expansión sin intercambio de calor | [[#Adiabática: trabajo a costa de energía interna\|Adiabática]] | T16 (M, caso A) |
| Verdadero/falso de un gráfico o un ciclo completo | [[#Leer un ciclo en el plano p–V\|Ciclos]] | T28 (M); T18/T17 (R) |
| Eficiencia, potencia o duración de un ciclo | [[#Motor: calor recibido, trabajo y potencia\|Motor]] | T19/T20/T32 (M) |
| Límite de eficiencia, combustible o propuesta imposible | [[#Carnot: límite, despejes y combustible\|Carnot]] | T24 (R); T30/T31 (M) |
| Refrigerador o motor Otto ideal | [[#Refrigeración y Otto: qué resultado es útil\|Otros dispositivos]] | T22/T23/T21 (C) |
| Entropía del cuerpo y su entorno | [[#Entropía: sumar los cambios del conjunto\|Entropía]] | T25–T26 (C) |

**Para preparar el examen:** trabaja primero motores, lectura de ciclos, mezclas y Carnot; usa la lectura de gases antes de resolver trabajo o ciclos. La [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Ruta prioritaria según los modelos|ruta prioritaria de la práctica]] explica la evidencia. M reproduce un modelo, R refuerza una familia examinada y C completa habilidades de los TP; esas letras no son una probabilidad de aparición.

**Antes de cualquier cuenta:** define el sistema, es decir, qué materia vas a estudiar. Un sistema **cerrado** no intercambia materia; uno **aislado** tampoco intercambia energía. Un recipiente **rígido** no cambia de volumen; una pared **adiabática** impide intercambio de calor. Son condiciones distintas. Para el balance de esta guía se desprecian cambios de energía cinética y potencial del conjunto.

Si una idea no se entiende, consulta la figura correspondiente en el [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Apoyos visuales de las fuentes|mapa visual del apunte largo]] o un despeje en [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica|fórmulas aplicadas]] y vuelve al mismo ejercicio.

## 1. Temperatura, equilibrio y dilatación

### Temperatura y cambios de escala

La **temperatura** indica el estado térmico. Dos cuerpos en equilibrio térmico tienen la misma temperatura; no necesitan la misma masa ni energía interna. El **calor** es energía transferida por una diferencia de temperatura: espontáneamente va del cuerpo más caliente al más frío. Lo que el cuerpo posee es energía interna $U$, asociada a sus partículas, no «calor almacenado».

Para convertir valores de temperatura usa $T_{\mathrm K}=T_{^\circ\mathrm C}+273.15$ y $T_{^\circ\mathrm F}=\tfrac95T_{^\circ\mathrm C}+32$. Para un **cambio** $\Delta T=T_f-T_i$, los desplazamientos de los ceros se cancelan al restar: $\Delta T_{\mathrm K}=\Delta T_{^\circ\mathrm C}$ y $\Delta T_{^\circ\mathrm C}=\tfrac59\Delta T_{^\circ\mathrm F}$.

**Pregunta:** Una temperatura aumenta $10\,^\circ\mathrm C$. ¿Aumentó $283.15\,\mathrm K$? ¿Qué significa que dos cuerpos lleguen al equilibrio?

> [!success]- Mostrar explicación
> El aumento es $10\,\mathrm K$: el desplazamiento $273.15$ se usa para valores de temperatura, no para incrementos. En equilibrio ambos cuerpos tienen la misma temperatura y no hay transferencia neta de calor entre ellos. No se igualan necesariamente sus energías internas.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T1. ¿Temperatura, calor o equilibrio? — C · sin evidencia de examen · prioridad didáctica alta|T1: distinguir conceptos]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T2. Cambios entre Fahrenheit y Celsius — C · sin evidencia de examen · prioridad didáctica media|T2: convertir valores y cambios]]. Separa primero qué datos son temperaturas y cuáles son intervalos.

### Dilatación: cambio de tamaño

En muchos materiales, al calentarse aumenta la separación media entre partículas. Para cambios pequeños, el alargamiento observado es proporcional a la longitud inicial y al cambio térmico:

$$
\Delta L=\alpha L_0\Delta T,\qquad
L_f=L_0+\Delta L=L_0(1+\alpha\Delta T).
$$

$L_0$ es la longitud inicial, $\alpha$ el coeficiente lineal en $\mathrm{K^{-1}}$ y $\Delta L$ el **cambio**, no la longitud final. Vale también para un diámetro. Si buscas $\alpha$, divide: $\alpha=(L_f-L_0)/(L_0\Delta T)$. Si buscas la temperatura límite de un remache, impón primero que su diámetro final iguale el del agujero. Cada objeto usa su propia temperatura de referencia.

Para volumen usa $\Delta V=\beta V_0\Delta T$, con coeficiente volumétrico $\beta$; en sólidos isotrópicos $\beta\approx3\alpha$. En un recipiente inicialmente lleno, **resta el aumento de su capacidad al del líquido**: $V_{\mathrm{exceso}}\approx V_0(\beta_{\mathrm{líquido}}-\beta_{\mathrm{recipiente}})\Delta T$. Solo rebalsa si ese exceso es positivo.

El modelo supone expansión libre, temperatura uniforme y coeficientes aproximadamente constantes. Un agujero se dilata con la placa: imagina la pieza de material que ocuparía ese espacio. En T3 el soporte permanece a temperatura fija: solo cambia el remache.

**Pregunta:** Si una varilla con $\alpha>0$ se enfría, ¿qué signos tienen $\Delta T$ y $\Delta L$? ¿Se vuelve negativa la longitud final?

> [!success]- Mostrar explicación
> Ambos cambios son negativos: $T_f<T_i$ y $\Delta L=\alpha L_0\Delta T<0$. La longitud final es la longitud inicial menos una pequeña contracción y sigue siendo positiva. Si el cálculo predijera una longitud negativa, el modelo estaría fuera de su alcance o habría un error.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T3. Enfriar un remache para que entre — C · sin evidencia de examen · prioridad didáctica alta|T3: remache]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T4. Dos reglas calibradas a temperaturas diferentes — C · sin evidencia de examen · prioridad didáctica media|T4: dos referencias de calibración]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T5. Medir el coeficiente de expansión — C · sin evidencia de examen · prioridad didáctica media|T5: hallar el coeficiente]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T6. Agua que rebalsa al calentarse — C · sin evidencia de examen · prioridad didáctica media|T6: desborde]]. **Apoyo visual:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la expansión lineal en el libro|alargamiento frente a longitud final]] y [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la arandela de las diapositivas|qué ocurre con un agujero]].

## 2. Calorimetría y cambios de fase

### Mezclas sin cambio de fase

**Reconócelo:** varios cuerpos a distintas temperaturas alcanzan una temperatura común. Para una sola fase, con calor específico $c$ aproximadamente constante, $Q=mc(T_f-T_i)$. El producto $mc$ es la energía necesaria por grado de cambio: una mayor masa o mayor $c$ exige más energía para el mismo aumento térmico. Usa $m$ en kg y $c$ en $\mathrm{J/(kg\,K)}$, o ambos expresados por gramo.

Si el conjunto está aislado y el trabajo es despreciable, la energía que unos ceden la reciben los otros: $\sum_i Q_i=0$. **Aislado es el conjunto; cada parte sí intercambia calor.** Incluye vaso, calorímetro o termómetro cuando su capacidad térmica no sea despreciable. Si dan volumen de líquido, primero calcula masa: $m=\rho V$, con densidad $\rho$ y unidades compatibles.

Para dos cuerpos sin cambio de fase:

$$
m_1c_1(T_f-T_1)+m_2c_2(T_f-T_2)=0
\quad\Longrightarrow\quad
T_f=\frac{m_1c_1T_1+m_2c_2T_2}{m_1c_1+m_2c_2}.
$$

El despeje reúne los términos con $T_f$ a un lado y divide por $m_1c_1+m_2c_2$. La temperatura final es un **promedio ponderado por capacidades térmicas**, no necesariamente el promedio aritmético. El cuerpo caliente tiene $T_f-T_i<0$ y cede calor. No añadas otro signo menos a ese cambio.

**Pregunta:** Si ya conoces $T_f$ y te piden un calor específico o una temperatura inicial, ¿necesitas otra ley? ¿Puede el termómetro modificar la temperatura que mide?

> [!success]- Mostrar explicación
> Se usa el mismo balance, despejando la incógnita correspondiente. El termómetro también intercambia energía al alcanzar el equilibrio: su lectura final puede diferir de la temperatura que tenía el agua antes de introducirlo. Para tratarlo como instrumento que no perturba la muestra, su capacidad térmica debe ser despreciable frente a la de esta.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T7. Té caliente en un vaso — M · prioridad de examen alta|T7 (M): té y vaso]]. Después [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T8. Calor específico de una aleación — R · prioridad de examen alta|T8: despejar un calor específico]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T11. Tres metales alcanzan el equilibrio — R · prioridad de examen alta|T11: tres cuerpos]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T33. Recuperar la temperatura inicial de una mezcla — R · prioridad de examen alta|T33: recuperar temperaturas iniciales]]. Escribe un término de calor para cada parte antes de sustituir números.

### Fases: decidir qué cambia antes de calcular

Durante fusión o vaporización a presión fija, una sustancia pura puede absorber energía **sin cambiar de temperatura**: esa energía transforma la fase. Usa $Q=+m_{\mathrm{trans}}L$ al fundir o vaporizar y $Q=-m_{\mathrm{trans}}L$ al solidificar o condensar. $L$ es calor latente en J/kg y $m_{\mathrm{trans}}$ es la masa efectivamente transformada, que puede ser menor que la masa total. Para calentar cada fase usa su propio $c$.

**Con hielo inicialmente a $0\,^\circ\mathrm C$ y presión atmosférica:** compara la energía positiva $E_{\mathrm{disp}}$ que los cuerpos calientes cederían al llegar a cero con $m_hL_f$, la necesaria para fundir todo el hielo:

- Si $E_{\mathrm{disp}}<m_hL_f$, queda hielo y agua a $0\,^\circ\mathrm C$; se funde $m_{\mathrm{fundida}}=E_{\mathrm{disp}}/L_f$.
- Si son iguales, termina de fundirse justo a $0\,^\circ\mathrm C$.
- Si $E_{\mathrm{disp}}>m_hL_f$, funde todo y la energía restante eleva la temperatura del agua y de los demás cuerpos. Plantea el balance con esa nueva etapa.

Si el hielo empieza por debajo de cero, hay que calentarlo hasta cero **antes** de fundirlo, como en T10. Si todo se funde y el líquido termina por encima del punto de fusión, suma $mL_f+mc_{\mathrm{líquido}}(T_f-T_{\mathrm{fusión}})$, como en T34. No asignes todo el calor a un único proceso.

En una curva con potencia absorbida constante y pérdidas despreciables, $Q=P\Delta t$: la potencia es energía por tiempo. Los tramos inclinados dan $c=P\Delta t/(m\Delta T)$; las mesetas dan $L=P\Delta t/m$. Usa **duración del tramo**, no el tiempo contado desde el inicio. Si $P$ está en kJ/min, usa minutos para obtener kJ.

**Pregunta:** ¿Por qué no puedes suponer desde el comienzo que todo el hielo se derrite y calcular una única $T_f$?

> [!success]- Mostrar explicación
> Puede no haber energía suficiente para fundirlo todo. Mientras coexistan agua y hielo en equilibrio a presión atmosférica, la mezcla permanece a cero. Una temperatura negativa obtenida suponiendo toda el agua líquida revela una hipótesis de fase incompatible: hay que volver al balance con fusión parcial.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T29. ¿Se funde todo el hielo? Dos resultados posibles — R · prioridad de examen media|T29: comparar las dos posibilidades]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T10. Fundir solo la mitad del hielo — R · prioridad de examen media|T10: calentamiento y fusión parcial]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T34. Calor latente obtenido de una mezcla — R · prioridad de examen media|T34: despejar un calor latente]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T9. Leer una curva de calentamiento — C · sin evidencia de examen · prioridad didáctica media|T9: leer una curva]]. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la curva del agua en el libro|cómo separar las etapas en una figura del libro]].

## 3. Cómo se transfiere el calor

**Reconócelo:** no preguntan solo cuánta energía cambia, sino **con qué rapidez** atraviesa una pared o sale de una superficie. Una potencia térmica $H$ en W es energía por segundo: $Q=H\Delta t$ si permanece constante. No confundas J con W ni potencia total con potencia por unidad de área.

En **conducción**, la energía se transmite sin transporte macroscópico de materia. Para una pared plana en estado estacionario, mayor área $A$ y diferencia entre caras aumentan la transferencia; mayor espesor $L$ la reduce:

$$
H=kA\frac{T_h-T_c}{L},\qquad
R_i=\frac{L_i}{k_iA_i},\qquad
H=\frac{T_h-T_c}{\sum_iR_i}.
$$

$k$ es conductividad en $\mathrm{W/(m\,K)}$; $T_h$ y $T_c$ son las temperaturas de las caras caliente y fría. $H$ es aquí una magnitud positiva. En capas **en serie**, sin pérdidas laterales y con contacto ideal, pasa la misma potencia por cada una: si se acumulara energía en la unión, no sería estacionario. La resistencia $R_i$ indica cuánto dificulta el paso cada capa. Para dos capas, la unión tiene $T_x=T_h-HR_1=T_c+HR_2$. No confundir esta resistencia con la constante de los gases.

La **convección** transporta energía mediante movimiento de un fluido. La **radiación** usa ondas electromagnéticas y puede atravesar el vacío. En los ejercicios de radiación:

$$
P_{\mathrm{emitida}}=\varepsilon\sigma AT^4,\qquad
P_{\mathrm{neta}}=\varepsilon\sigma A(T^4-T_{\mathrm{amb}}^4).
$$

$\varepsilon$ es emisividad, entre 0 y 1, y $\sigma=5.67\times10^{-8}\,\mathrm{W/(m^2\,K^4)}$. Usa K **antes** de elevar a la cuarta potencia y área en $\mathrm{m^2}$. La forma neta resta la absorción desde un entorno grande y uniforme: es positiva si el cuerpo pierde energía. En T15 se usa emisión según el supuesto del filamento.

**Pregunta:** Si duplicas a la vez el área y el espesor de una pared, manteniendo material y temperaturas, ¿se duplica la pérdida? ¿Un cuerpo a la misma temperatura del entorno deja de emitir?

> [!success]- Mostrar explicación
> La potencia de conducción queda igual porque $2A/(2L)=A/L$. El cuerpo sí emite radiación, pero absorbe la misma potencia: la transferencia neta es cero. Emisión y pérdida neta son magnitudes distintas.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T12. Pérdida de calor por una pared aislante — C · sin evidencia de examen · prioridad didáctica alta|T12: una pared]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T35. Elegir un material para reducir las pérdidas — C · sin evidencia de examen · prioridad didáctica media|T35: comparar materiales]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T13. Dos placas y temperatura de contacto — C · sin evidencia de examen · prioridad didáctica media|T13: capas en serie]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T14. Radiación neta de una persona — C · sin evidencia de examen · prioridad didáctica alta|T14: radiación neta]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T15. Potencia radiada por un filamento — C · sin evidencia de examen · prioridad didáctica media|T15: emisión]]. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la conducción en la figura del libro|área y espesor]] y [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la fotografía de convección del libro|movimiento del fluido]].

## 4. Gas ideal y primera ley

### Estado del gas, trabajo y balance

**Reconócelo:** un gas cambia presión, volumen o temperatura. En equilibrio, el modelo ideal relaciona sus estados mediante $pV=nRT$: $p$ es presión **absoluta** en Pa, $V$ volumen en $\mathrm{m^3}$, $n$ cantidad en mol y $T$ temperatura en K; $R=8.314\,\mathrm{J/(mol\,K)}$. Si la presión dada es manométrica, suma la atmosférica para obtener la absoluta. Para $n$ fijo, $p_iV_i/T_i=p_fV_f/T_f$. La ecuación conecta estados; no indica por sí sola cuánto calor o trabajo se intercambia.

Con $Q>0$ si el gas **recibe calor** y $W>0$ si el gas **realiza trabajo**, conservar energía da:

$$
\Delta U=Q-W\quad\Longleftrightarrow\quad Q=\Delta U+W.
$$

Empujar un pistón requiere fuerza por distancia: como $F=pA$ y $\Delta V=A\Delta x$, a presión constante $W=p\Delta V$. Si cambia la presión, el trabajo es el área con signo bajo la trayectoria: $W=\int_{V_i}^{V_f}p\,dV$. Usar la presión del gas requiere evolución mecánica cuasiestática sin disipación. Expansión: $W>0$; compresión: $W<0$. Volumen fijo: trabajo de expansión cero; aquí no hay otros trabajos.

Para un gas ideal de cantidad fija, $U$ depende solo de $T$: $\Delta U=nC_V\Delta T$ con $C_V$ constante, **aunque el volumen cambie**. $C_V$ es capacidad calorífica molar en $\mathrm{J/(mol\,K)}$, distinta del $c$ por masa. Usa $C_V=3R/2$ para el modelo monoatómico, $5R/2$ para el diatómico de estos ejercicios, o $C_V=R/(\gamma-1)$ si dan $\gamma=C_P/C_V$. $C_P$ es la capacidad calorífica molar a presión constante. Vale $C_P=C_V+R$: a presión constante parte del calor permite expandir el gas.

**Pregunta:** El gas recibe $500\,\mathrm J$ como calor y realiza $200\,\mathrm J$ de trabajo. ¿Cuánto cambia $U$? ¿Conocer solo los estados inicial y final bastaría para fijar ese trabajo?

> [!success]- Mostrar explicación
> $\Delta U=500-200=300\,\mathrm J$: queda en el gas la energía que no entregó como trabajo. Los estados fijan $\Delta U$, pero el trabajo depende del camino seguido; dos trayectorias pueden tener áreas distintas. Sus calores también serán distintos para conservar ese mismo cambio de energía interna.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T27. Expansión isobárica y primera ley — M · prioridad de examen media|T27 (M): expansión a presión constante]]. Calcula primero $W=p(V_f-V_i)$ y después $\Delta U=Q-W$; no necesitas inventar $n$ o $T$. Convierte kcal a J. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer el pistón del libro|fuerza, desplazamiento y volumen]].

### Adiabática: trabajo a costa de energía interna

Adiabático significa $Q=0$, por lo que $\Delta U=-W$. Si el gas se expande haciendo trabajo, disminuye $U$ y se enfría; al comprimirlo con trabajo recibido ocurre lo contrario. **No significa temperatura constante.**

Para un gas ideal con cantidad fija, adiabática **reversible** y capacidades constantes, la primera ley combinada con $pV=nRT$ lleva a $pV^\gamma=\text{constante}$ y $TV^{\gamma-1}=\text{constante}$. Así se despeja:

$$
p_f=p_i\left(\frac{V_i}{V_f}\right)^\gamma,\qquad
T_f=T_i\left(\frac{V_i}{V_f}\right)^{\gamma-1},\qquad
W=\frac{p_iV_i-p_fV_f}{\gamma-1}.
$$

La última relación sale de $W=-\Delta U$, usando $nC_VT=pV/(\gamma-1)$. En las razones de volúmenes puedes usar L si se cancelan; en los productos $pV$ usa Pa y $\mathrm{m^3}$ para obtener J. Recuerda $1\,\mathrm L=10^{-3}\,\mathrm{m^3}$.

**Pregunta:** ¿Basta saber que no entra calor para usar las potencias anteriores? ¿Toda expansión adiabática enfría un gas ideal?

> [!success]- Mostrar explicación
> No: las potencias requieren también reversibilidad y el modelo indicado. En expansión libre aislada contra el vacío no se empuja una carga: $W=0$, luego $\Delta U=0$ y la temperatura ideal no cambia. El enfriamiento anterior se debe al trabajo entregado, no al aumento de volumen por sí solo.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T16. Expansión adiabática en un cilindro — M · prioridad de examen media|T16: caso A del modelo; después caso B de refuerzo]]. Anota antes de calcular por qué deben disminuir $p$ y $T$ en esos casos. **Si falta contexto:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#De dónde salen las potencias de la adiabática|origen de las potencias y sus condiciones]].

### Leer un ciclo en el plano p–V

En el eje horizontal está $V$ y en el vertical $p$. Sigue las flechas, identifica la condición de cada tramo y resuelve **tramo por tramo**:

| Trayectoria | Qué reconocer | Trabajo del gas |
|---|---|---|
| Vertical, isocórica | $V$ constante | $W=0$ |
| Horizontal, isobárica | $p$ constante | $W=p(V_f-V_i)$ |
| Recta inclinada | Presión lineal con el volumen | $W=\tfrac{p_i+p_f}{2}(V_f-V_i)$, área del trapecio con signo |
| Isoterma de gas ideal | $pV$ constante durante todo el tramo | $\Delta U=0$; si es reversible, $W=nRT\ln(V_f/V_i)$ |

Una recta inclinada **no es una isoterma**. Para comparar temperaturas de estados con el mismo $n$, compara $pV$: $T_f/T_i=p_fV_f/(p_iV_i)$. Si precisas $\Delta U$ sin conocer $n$, para $\gamma$ constante sustituye $nRT=pV$: $\Delta U=(p_fV_f-p_iV_i)/(\gamma-1)$. Después $Q=\Delta U+W$.

Al cerrar el ciclo se recupera el estado inicial: $\sum\Delta U=0$ y $Q_{\mathrm{neto}}=W_{\mathrm{neto}}$. El área encerrada da el módulo del trabajo neto: sentido horario positivo, antihorario negativo. **No se anulan necesariamente $Q$ y $W$.** Para calcular eficiencia, $Q_H$ suma solo los calores positivos de los tramos; no es $Q_{\mathrm{neto}}$.

**Pregunta:** Un tramo es vertical y la presión aumenta. ¿Son cero tanto $W$ como $\Delta U$? ¿Podrías usar grados Celsius para comparar sus temperaturas por razón?

> [!success]- Mostrar explicación
> Solo $W$ es cero. Con $V$ y $n$ fijos, $p\propto T$: aumenta la temperatura absoluta, aumenta $U$ y el gas recibe calor. Las razones de temperatura se calculan en K. La condición de volumen fijo no impide intercambiar energía.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T28. Interpretar el ciclo triangular de los modelos — M · prioridad de examen alta|T28 (M): justificar verdadero/falso]]; después [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T18. Ciclo rectangular de un gas monoatómico — R · prioridad de examen alta|T18: ciclo rectangular]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T17. Ciclo con un tramo adiabático — R · prioridad de examen alta|T17: ciclo con adiabática]]. Para los completos arma una fila por tramo con $\Delta U$, $W$ y $Q$. Controla unidades del gráfico: $1\,\mathrm{kPa\,m^3}=1000\,\mathrm J$, pero $1\,\mathrm{kPa\,L}=1\,\mathrm J$. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer los cuatro procesos del libro|comparación visual de procesos]].

## 5. Máquinas térmicas, refrigeración y entropía

### Motor: calor recibido, trabajo y potencia

**Reconócelo:** una máquina repite ciclos, toma calor $Q_H>0$ del foco caliente, entrega trabajo útil $W>0$ y desecha calor $Q_C<0$ al frío. Al volver al estado inicial, $\Delta U_{\mathrm{ciclo}}=0$; por la primera ley:

$$
Q_H=W+|Q_C|,\qquad
e=\frac{W}{Q_H}=1-\frac{|Q_C|}{Q_H}.
$$

$|Q_C|$ es la magnitud positiva del calor desechado; no vuelvas a ponerle signo negativo al usar el balance con módulos. La eficiencia $e$ compara el trabajo útil con **toda la energía recibida**. Usa fracción: $25\%=0.25$.

Para despejar, parte de $eQ_H=W$: si sabes $W$, $Q_H=W/e$; si sabes $|Q_C|$, usa $|Q_C|=(1-e)Q_H$, luego $Q_H=|Q_C|/(1-e)$. Finalmente $W=Q_H-|Q_C|$.

La potencia $P_{\mathrm{salida}}=W/\Delta t$ mide trabajo por tiempo. Si $W$ es por ciclo, su duración es $\Delta t_{\mathrm{ciclo}}=W_{\mathrm{ciclo}}/P_{\mathrm{salida}}$. Si piden calor **por segundo**, usa tasas:

$$
\dot Q_H=\frac{P_{\mathrm{salida}}}{e},\qquad
|\dot Q_C|=\dot Q_H-P_{\mathrm{salida}}.
$$

El punto indica energía por tiempo; las tasas se expresan en W, con $1\,\mathrm{kW}=1000\,\mathrm W$. Para recuperar energía durante un intervalo, multiplica la tasa constante por ese tiempo en segundos. No mezcles J/ciclo con J/s en una suma.

**Pregunta:** Una máquina tiene eficiencia $0.25$ y entrega $100\,\mathrm J$ por ciclo. ¿Recibe $25\,\mathrm J$? Si entrega además una potencia de $50\,\mathrm W$, ¿cuánto dura cada ciclo?

> [!success]- Mostrar explicación
> Recibe $Q_H=W/e=400\,\mathrm J$ y desecha $300\,\mathrm J$. Cada ciclo dura $100\,\mathrm J/(50\,\mathrm{J/s})=2\,\mathrm s$. Multiplicar $W$ por la eficiencia invertiría la definición: la energía recibida debe superar al trabajo útil.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T19. Motor diésel: energía y eficiencia — M · prioridad de examen alta|T19 (M): balance y eficiencia]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T20. Potencia de salida y duración de cada ciclo — M · prioridad de examen alta|T20 (M): duración del ciclo]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T32. Calor suministrado y desechado por segundo — M · prioridad de examen alta|T32 (M, caso A): tasas de calor]]. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer el flujo de energía del motor en el libro|seguir las flechas de energía]].

### Carnot: límite, despejes y combustible

La segunda ley limita cuánto calor puede convertirse en trabajo en un motor cíclico entre **dos focos de temperatura constante**. Carnot es el modelo reversible que alcanza ese máximo:

$$
e_C=1-\frac{T_C}{T_H},\qquad
e_{\mathrm{real}}\le e_C,\qquad W_{\max}=e_CQ_H.
$$

$T_H$ es la temperatura del foco caliente y $T_C$ la del frío, ambas en K; el subíndice C significa frío, no Celsius. En el reversible, el balance de entropía da $|Q_C|/T_C=Q_H/T_H$: al sustituir en la eficiencia se obtiene la razón anterior. En una máquina real, **conocer los focos da el límite, no su eficiencia efectiva**: calcula esta con $W/Q_H$ si esos son los datos.

Para despejar temperaturas en Carnot: $1-e_C=T_C/T_H$, de donde $T_C=(1-e_C)T_H$ o $T_H=T_C/(1-e_C)$. Una propuesta con $W/Q_H>e_C$ es imposible aunque conserve energía.

El combustible aporta el calor de entrada, no solo el trabajo útil. Si toda su energía liberada llega al motor, $Q_H=m_{\mathrm{comb}}q_{\mathrm{comb}}$, luego $m_{\mathrm{comb}}=Q_H/q_{\mathrm{comb}}=W/(e\,q_{\mathrm{comb}})$. $q_{\mathrm{comb}}$ es poder calorífico en J/kg: divide J entre J/kg para obtener kg. Si está en kJ/kg, convierte o trabaja todo en kJ. El balance debe referirse al mismo ciclo o intervalo.

**Pregunta:** Un motor recibe $1000\,\mathrm J$ por ciclo entre $600\,\mathrm K$ y $300\,\mathrm K$. ¿Una propuesta de $600\,\mathrm J$ de trabajo es viable porque desecha los otros $400\,\mathrm J$?

> [!success]- Mostrar explicación
> No. Conserva energía, pero supera $e_C=1-300/600=0.50$. El máximo permitido es $500\,\mathrm J$ por ciclo; la propuesta exigiría eficiencia $0.60$. La primera ley cierra el balance y la segunda restringe qué balances son posibles.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T24. Dos despejes de Carnot — R · prioridad de examen alta|T24: despejes de Carnot]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T30. Carnot y consumo de combustible por ciclo — M · prioridad de examen alta|T30 (M): combustible por ciclo]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T31. Máquina real y propuesta imposible — M · prioridad de examen alta|T31 (M): máquina real y propuesta]]. Para T17/T18, compara su eficiencia calculada con el límite entre las temperaturas extremas; no reemplaces la eficiencia del ciclo por la de Carnot. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Ejemplo del libro: trabajo y calor de una máquina de Carnot|ejemplo resuelto del libro]].

### Refrigeración y Otto: qué resultado es útil

Son dos aplicaciones distintas. Para un **refrigerador**, lo útil es extraer calor de la región fría, no producir trabajo. Aquí usa **magnitudes positivas** $W_{\mathrm{entrada}}$, $|Q_C|$ extraído y $|Q_H|$ entregado al ambiente:

$$
|Q_H|=|Q_C|+W_{\mathrm{entrada}},\qquad
COP_R=\frac{|Q_C|}{W_{\mathrm{entrada}}}.
$$

El COP mide cuánta energía se extrae por cada joule de trabajo; puede superar 1. No cambia la convención de la primera ley: el trabajo realizado por el refrigerante es $W_{\mathrm{por\ el\ sistema}}=-W_{\mathrm{entrada}}$. Una bomba de calor busca calentar el foco caliente, por eso $COP_{BC}=|Q_H|/W_{\mathrm{entrada}}=COP_R+1$.

Para fabricar hielo, suma el calor que hay que retirar en tres etapas: enfriar el agua a cero, congelarla y enfriar el hielo. Divide esa **magnitud total** entre el tiempo para obtener $\dot Q_{\mathrm{extraído}}$; luego $P_{\mathrm{entrada}}=\dot Q_{\mathrm{extraído}}/COP_R$. El límite reversible entre dos focos es $COP_{R,C}=T_C/(T_H-T_C)$ con T en K; no se supone Carnot si solo se da un COP real.

El **motor Otto ideal** produce trabajo mediante dos adiabáticas reversibles y dos procesos a volumen constante. Su eficiencia es $e_{\mathrm{Otto}}=1-1/r^{\gamma-1}$, donde $r=V_{\max}/V_{\min}$ es relación de compresión y $\gamma=C_P/C_V$ se toma constante. La expresión surge del balance del ciclo y de las relaciones adiabáticas; no corresponde aplicarla a cualquier motor real ni al refrigerador.

**Pregunta:** Un refrigerador extrae $300\,\mathrm J$ con $100\,\mathrm J$ de trabajo. ¿Cuál es su COP y cuánto entrega al ambiente? ¿Viola conservación de energía por tener COP mayor que 1?

> [!success]- Mostrar explicación
> $COP_R=300/100=3$ y entrega $400\,\mathrm J$. No crea energía: traslada $300\,\mathrm J$ y recibe otros $100\,\mathrm J$ como trabajo. Para el motor Otto, en cambio, se compara trabajo producido con calor recibido; es otro objetivo y otra razón.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T22. Trabajo requerido por un refrigerador — C · sin evidencia de examen · prioridad didáctica alta|T22: balance de refrigeración]], [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T23. Potencia para fabricar hielo — C · sin evidencia de examen · prioridad didáctica media|T23: enfriar, congelar y calcular potencia]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T21. Eficiencia ideal de un ciclo Otto — C · sin evidencia de examen · prioridad didáctica media|T21: motor Otto ideal]]. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer el refrigerador del libro|componentes y transferencias de una heladera]] y [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Ciclo Otto: modelo, razón de compresión y origen de su eficiencia|origen de la eficiencia de Otto]].

### Entropía: sumar los cambios del conjunto

La **entropía $S$** es una propiedad del estado que permite analizar la dirección de los procesos. No es energía ni temperatura. Su cambio se calcula sumando el calor intercambiado dividido por la temperatura **a lo largo de un camino reversible**: $\Delta S=\int_i^f\delta Q_{\mathrm{rev}}/T$. Si el proceso real es irreversible, se usa un camino reversible imaginado entre los mismos estados, porque $\Delta S$ depende solo de esos estados.

Para los ejercicios de esta unidad, con temperaturas en K y resultado en J/K:

- **Fundir a temperatura fija:** $\Delta S_{\mathrm{cuerpo}}=+mL_f/T_{\mathrm{fusión}}$; para solidificar se invierte el signo.
- **Calentar o enfriar un sólido o líquido sin cambio de fase**, con $c$ constante y trabajo despreciable: $\Delta S_{\mathrm{cuerpo}}=mc\ln(T_f/T_i)$. Al enfriarse, la razón es menor que 1 y el logaritmo es negativo.
- **Foco grande a temperatura constante:** $\Delta S_{\mathrm{foco}}=Q_{\mathrm{foco}}/T_{\mathrm{foco}}$, con calor positivo si el foco lo recibe. Si el cuerpo cede calor, el foco lo gana: $Q_{\mathrm{foco}}=-Q_{\mathrm{cuerpo}}$.

La forma $Q/T$ sale de la integral cuando la temperatura del camino reversible es constante; **no se usa una temperatura promedio arbitraria** para un cuerpo que se enfría. La integral de $mc\,dT/T$ origina el logaritmo.

La segunda ley exige $\Delta S_{\mathrm{total}}=\Delta S_{\mathrm{sistema}}+\Delta S_{\mathrm{entorno}}\ge0$, incluyendo todo el entorno relevante: cero para el reversible y positivo para el irreversible. La entropía de una parte sí puede disminuir. Adiabático significa $Q=0$, pero solo adiabático **reversible** garantiza $\Delta S=0$.

**Pregunta:** Si el té se enfría y su entropía disminuye, ¿se viola la segunda ley? ¿El aire puede aumentar su entropía aunque su temperatura permanezca constante?

> [!success]- Mostrar explicación
> No se decide mirando solo el té. El aire recibe calor y aumenta su entropía: hay que sumar ambos cambios; con diferencia finita de temperaturas, el total es positivo. Un foco grande puede absorber energía sin cambio apreciable de temperatura y aun así tener $\Delta S=Q/T>0$.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T25. Entropía al fundir hielo — C · sin evidencia de examen · prioridad didáctica alta|T25: fusión y fuente caliente]] y [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T26. Entropía de té que se enfría — C · sin evidencia de examen · prioridad didáctica alta|T26: té y ambiente]]. En cada uno calcula por separado el cambio del cuerpo y el del foco antes de sumarlos. **Apoyo:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la expansión libre del libro: el camino de cálculo|por qué el camino reversible de cálculo puede diferir del proceso real]].

## Después de la lectura

Antes de abrir una resolución, escribe: **sistema y datos → condición del proceso → principio elegido → despeje → sustitución con unidades → interpretación**. Justifica la elección con una frase concreta: «El conjunto está aislado y el trabajo es despreciable, por eso sumo los calores de sus partes e igualo a cero».

Si no sale el planteo, abre primero la pista del ejercicio. Consulta después la [[Unidades/05 - Termodinámica/Resoluciones/05 - Resoluciones de termodinámica|resolución paso a paso]] y anota qué decisión faltaba; vuelve a resolver sin mirarla. No avances solo por haber entendido la respuesta al leerla.

Para fijar lo aprendido, usa la [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Repaso del módulo|autoevaluación de la unidad]]. Para ampliar una duda concreta vuelve a [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica|conceptos completos]], [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica|fórmulas aplicadas]] o al [[Unidades/05 - Termodinámica/Teoría/05 - Termodinámica|índice del módulo]].
