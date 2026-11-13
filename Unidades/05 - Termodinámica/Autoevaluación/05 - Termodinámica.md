---
tags: [fisica-aplicada, autoevaluacion, unidad-05, termodinamica]
---

# Autoevaluación — Termodinámica

[[Recursos de estudio/Autoevaluación/Inicio|← Índice]] · [[Unidades/05 - Termodinámica/Teoría/05 - Guía breve de termodinámica|Guía breve]] · [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica|Conceptos]] · [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica|Fórmulas]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|Práctica]]

Responde primero sin mirar. Para cada respuesta escribe el principio usado y explica qué dato del enunciado te permite elegirlo; después despliega la explicación y compara.

## Conceptos

Avanza por el grupo que corresponde a la lectura. Puedes responder oralmente, pero explica qué supuesto estás usando. Si fallas, vuelve al enlace de teoría de ese grupo y reintenta antes de abrir una resolución.

### Sistema, supuestos y equilibrio

**Volver a la explicación:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#1. Sistema, entorno y estado térmico|sistema y supuestos]].

**1. ¿Un gas cerrado bajo un pistón aislante está necesariamente aislado?**

> [!success]- Mostrar explicación
> No. Cerrado impide intercambio de materia y adiabático impide calor, pero el pistón permite trabajo. El gas puede entregar energía al empujar una carga. Solo sería aislado si no intercambiara energía por ningún mecanismo; no basta con afirmar $Q=0$.

**2. Si el conjunto agua más vaso está aislado, ¿cómo puede el vaso absorber calor?**

> [!success]- Mostrar explicación
> El aislamiento se refiere a la frontera exterior del conjunto. El agua puede ceder energía al vaso dentro de esa frontera. Cada parte tiene un calor distinto de cero y ambos se compensan: $Q_{\mathrm{agua}}+Q_{\mathrm{vaso}}=0$. Elegir solo el agua como sistema cambiaría qué transferencias cruzan la frontera.

**3. ¿“Recipiente rígido” y “recipiente de capacidad térmica despreciable” eliminan el mismo término?**

> [!success]- Mostrar explicación
> No. Rígido elimina el cambio de volumen y el trabajo de expansión de la frontera. Capacidad térmica despreciable permite omitir la energía absorbida por el propio recipiente al cambiar su temperatura. Ninguna frase por sí sola demuestra que no se intercambie calor con la habitación.

### Temperatura, calor y fases

**Volver a la explicación:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#2. Temperatura, escalas y expansión térmica|temperatura y expansión]] · [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#3. Calor, calor específico y calorimetría|calorimetría]].

**1. ¿Un cuerpo “contiene calor”? ¿Qué describe entonces la palabra calor?**

> [!success]- Mostrar explicación
> El cuerpo tiene energía interna. Calor es energía que se transfiere por una diferencia de temperatura, no una propiedad almacenada. La temperatura tampoco indica por sí sola toda la energía interna: importan la masa, el material y la fase.

**2. Si dos objetos se encuentran en equilibrio térmico con el mismo termómetro, ¿qué puede concluirse al ponerlos en contacto entre sí?**

> [!success]- Mostrar explicación
> Tienen la misma temperatura y no habrá transferencia neta debida a una diferencia térmica entre ellos. Es la ley cero. El equilibrio no significa que las partículas dejen de moverse.

**3. Al calentar libre y uniformemente una placa con un agujero, ¿el diámetro aumenta o disminuye?**

> [!success]- Mostrar explicación
> Aumenta si el coeficiente de dilatación es positivo. Imagina una pieza del mismo material rellenando el agujero: se expandiría junto con la placa. Al retirarla, queda el mismo aumento de separación en el borde. El diámetro es una longitud y usa $\alpha$, no $3\alpha$.

**4. ¿Por qué $Q=mc\Delta T$ no calcula la energía de una meseta de fusión?**

> [!success]- Mostrar explicación
> La temperatura no cambia, pero sí hay energía transferida para cambiar la fase. Se usa $Q=+m_{\mathrm{fundida}}L_f$. La masa es la que efectivamente se transforma; si se solidifica, el calor tiene signo negativo. La meseta supone una sustancia pura en equilibrio a presión fija.

**5. En una mezcla aislada, ¿por qué no suele ser correcto promediar las temperaturas sin ponderarlas?**

> [!success]- Mostrar explicación
> Cada parte tiene una capacidad térmica $mc$ que puede ser diferente. Sin cambios de fase y con esas capacidades constantes, el balance da $T_f=\sum_i m_ic_iT_{i,i}/\sum_i m_ic_i$. El promedio simple solo sirve si las capacidades son iguales. Un vaso de capacidad apreciable debe incluirse.

**6. Si dos tramos de una curva de calentamiento tienen pendientes diferentes, ¿cómo reconoces el de mayor calor específico?**

> [!success]- Mostrar explicación
> A igual masa y potencia absorbida constante, $\Delta T/\Delta t=P/(mc)$: el tramo menos inclinado tiene mayor $c$. Una meseta requiere otro análisis: la energía cambia la fase y su duración permite hallar $L=P\Delta t/m$. Sin controlar masa, potencia y pérdidas no se compara $c$ solo por la pendiente.

### Transferencia: condiciones del modelo

**Volver a la explicación:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#4. Transferencia de calor: conducción, convección y radiación|mecanismos y condiciones]].

**1. ¿Qué diferencia conducción, convección y radiación?**

> [!success]- Mostrar explicación
> La conducción transmite energía por interacciones microscópicas sin movimiento macroscópico del material. La convección transporta energía con un fluido en movimiento. La radiación usa ondas electromagnéticas y puede propagarse en el vacío. Pueden actuar simultáneamente.

**2. ¿Una pared en régimen estacionario está a la misma temperatura en todos sus puntos? ¿Por qué dos capas en serie comparten $H$?**

> [!success]- Mostrar explicación
> Estacionario significa que la temperatura de cada punto ya no cambia con el tiempo; puede variar de un punto a otro. Sin generación ni pérdidas laterales, el calor por segundo que entra debe salir: de lo contrario se acumularía energía. Por eso las capas en serie comparten $H$, aunque tengan caídas de temperatura diferentes.

**3. ¿Un cuerpo a la misma temperatura que su ambiente deja de emitir radiación?**

> [!success]- Mostrar explicación
> No. Emite y absorbe radiación con potencias iguales: la transferencia neta es cero. Para la pérdida neta se resta la absorción ambiental; solo en el modelo que la desprecia se identifica potencia emitida con potencia perdida. Las temperaturas de Stefan–Boltzmann van en K.

### Gases, procesos y lectura de gráficos

**Volver a la explicación:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#5. Gas ideal y variables de estado|gas ideal]] · [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#6. Primera ley: el balance de energía|primera ley]] · [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#7. Procesos termodinámicos y ciclos|procesos y ciclos]].

**1. ¿Qué permite calcular $pV=nRT$ y qué información falta para hallar el trabajo?**

> [!success]- Mostrar explicación
> Conecta presión absoluta, volumen, temperatura kelvin y cantidad de gas en un estado de equilibrio. Para hallar trabajo se necesita cómo cambió el volumen frente a la presión durante el proceso; dos caminos entre iguales estados pueden tener trabajos distintos. Que $pV$ tenga unidades de energía no significa que siempre sea el trabajo.

**2. ¿Usar $\Delta U=nC_V\Delta T$ obliga a que el gas permanezca a volumen constante?**

> [!success]- Mostrar explicación
> No. Para un gas ideal de cantidad fija, $U$ depende solo de $T$ y la expresión vale entre estados de cualquier trayectoria, con $C_V$ constante en el intervalo. A volumen constante se mide $C_V$ y además $Q=\Delta U$. En otro proceso, $Q$ puede incluir trabajo y no tiene por qué ser $nC_V\Delta T$.

**3. En una expansión adiabática contra una carga, ¿de dónde sale el trabajo? ¿Y qué ocurre si la expansión es libre contra el vacío?**

> [!success]- Mostrar explicación
> Contra una carga, $Q=0$ y $W>0$ implican $\Delta U=-W<0$; para gas ideal baja $T$. En expansión libre aislada, el volumen también aumenta, pero $W=0$ y $Q=0$, por lo que $\Delta U=0$ y no cambia la temperatura del gas ideal. El cambio de volumen por sí solo no demuestra que se haya hecho trabajo.

**4. ¿Un proceso lento es necesariamente reversible? ¿Un proceso adiabático debe ser rápido?**

> [!success]- Mostrar explicación
> No a ambas preguntas. Un proceso lento con fricción puede ser irreversible. Un aislamiento adecuado permite una adiabática lenta, aproximadamente cuasiestática y reversible si se evitan disipaciones. Que un proceso rápido tenga poco intercambio de calor no autoriza por sí solo a usar $pV^\gamma=\mathrm{constante}$.

**5. ¿Por qué el área encerrada de un ciclo no basta para hallar su eficiencia?**

> [!success]- Mostrar explicación
> El área da $W_{\mathrm{neto}}=Q_{\mathrm{neto}}$. La eficiencia necesita $Q_H$, suma solo de los calores positivos, antes de restar los rechazados. Se calcula $Q$ por tramo con $Q=\Delta U+W$ y se separan entradas de salidas. Usar $Q_{\mathrm{neto}}$ como denominador produciría erróneamente eficiencia 1.

### Máquinas, límites y entropía

**Volver a la explicación:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#8. Motores y refrigeradores: objetivos y rendimientos|máquinas y límites]] · [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#9. Segunda ley y entropía|entropía]].

**1. ¿Por qué eficiencia de motor y COP de refrigerador tienen numeradores distintos? ¿Puede el COP superar 1?**

> [!success]- Mostrar explicación
> El motor busca trabajo útil y usa $e=W_{\mathrm{salida}}/Q_H$. El refrigerador busca extraer calor y usa $COP_R=|Q_C|/W_{\mathrm{entrada}}$. Puede superar 1 porque transporta energía desde el foco frío además de recibir trabajo. Con COP 3 extrae 3 J y consume 1 J, entregando 4 J al foco caliente: la energía se conserva.

**2. ¿Todo motor entre dos temperaturas tiene eficiencia $1-T_C/T_H$? ¿Y todo motor de combustión usa la fórmula de Otto?**

> [!success]- Mostrar explicación
> No. Carnot da una igualdad para el modelo reversible y un límite para los motores entre esos dos focos. La eficiencia real se obtiene de $W/Q_H$. La fórmula de Otto requiere su ciclo ideal específico, con dos adiabáticas reversibles y dos intercambios isocóricos; que el motor use combustible no demuestra esas condiciones.

**3. Si la entropía del agua disminuye, ¿se viola la segunda ley?**

> [!success]- Mostrar explicación
> No necesariamente. La restricción $\Delta S_{\mathrm{total}}\ge0$ se aplica al agua más el entorno que intercambia energía con ella. El agua que se enfría puede perder entropía y el ambiente aumentarla en una cantidad mayor. Hay que sumar ambos cambios.

**4. Un foco conserva su temperatura mientras recibe energía. ¿Su cambio de entropía es cero?**

> [!success]- Mostrar explicación
> No. Se trata como una capacidad muy grande cuya temperatura apenas cambia, no como un sistema que no absorbe energía. Si recibe $Q>0$, $\Delta S_{\mathrm{foco}}=Q/T_{\mathrm{foco}}>0$. Para un cuerpo cuya temperatura sí varía se elige una trayectoria reversible y, con $c$ constante, se integra para obtener $mc\ln(T_f/T_i)$.

**5. ¿$Q=0$ basta para afirmar que $\Delta S=0$?**

> [!success]- Mostrar explicación
> No. Una adiabática reversible tiene $\Delta S=0$, pero una irreversible puede generar entropía. En la expansión libre de gas ideal aislado no entra calor ni cambia $U$, pero aumenta la entropía. Para calcular $\Delta S$ se usa un camino reversible entre los mismos estados, no el calor real nulo dividido por $T$.

### Decisiones que aparecen en la práctica ampliada

**1. Al mezclar un metal caliente con hielo a cero grados, ¿por qué no puedes suponer que el hielo se funde todo?**

> [!success]- Mostrar explicación
> La energía disponible puede no alcanzar. Compara la que cedería el metal al llegar a cero con la necesaria para fundir todo el hielo. Si es menor, quedan hielo y agua a cero; si es mayor, el balance incluye fusión completa y calentamiento del agua resultante. En esa rama el metal también termina a $T_f>0$, no a cero. Compruébalo en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T29. ¿Se funde todo el hielo? Dos resultados posibles — R · reconstrucción de la clave 2026 · prioridad de estudio alta|T29]].

**2. ¿Una recta inclinada en un gráfico $p$–$V$ es isotérmica? ¿Tener igual temperatura en los dos extremos demuestra que lo sea?**

> [!success]- Mostrar explicación
> No. Para gas ideal y cantidad fija, una isoterma cumple $pV=\mathrm{constante}$ en todo el tramo y es una hipérbola. Una recta permite usar presión media por cambio de volumen para el trabajo. Igual $pV$ en los extremos solo demuestra igual temperatura allí, no en el interior. Practica [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T28. Interpretar el ciclo triangular de los modelos — M · prioridad de examen alta|T28]].

**3. ¿Una máquina que conserva energía y tiene eficiencia menor al cien por ciento es siempre posible?**

> [!success]- Mostrar explicación
> Debe respetar además $e\le1-T_C/T_H$ para los mismos dos focos, con temperaturas en K. La igualdad es el límite reversible. En [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T31. Máquina real y propuesta imposible — M · prioridad de examen alta|T31]] la propuesta conserva energía pero supera ese límite. Tener $|Q_C|>0$ no basta para validarla.

### Lectura de figuras de las fuentes

**Volver a la explicación:** [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Apoyos visuales de las fuentes|mapa de figuras originales]]. Mira la figura primero, tapa el texto y justifica la respuesta.

**1. En la figura de conducción, se duplican a la vez el área y la longitud recorrida por el calor. ¿La potencia aumenta, disminuye o queda igual?**

> [!success]- Mostrar explicación
> Queda igual si se mantienen el material y las temperaturas de los extremos: $H_2/H_1=(2A/A)(L/(2L))=1$. La figura muestra cada cambio por separado; al combinarlos se multiplican sus factores. El área es perpendicular al flujo y la longitud es el trayecto que este recorre. Revisa [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la conducción en la figura del libro|los tres casos]].

**2. En las trayectorias del libro, ¿por qué el recorrido 1→3→2 recibe más calor que 1→4→2 si ambos terminan en el mismo estado?**

> [!success]- Mostrar explicación
> Ambos tienen el mismo $\Delta U$, pero el primero se expande a la presión mayor y entrega más trabajo: la diferencia es $(p_1-p_2)(V_2-V_1)>0$. De $Q=\Delta U+W$ resulta que debe recibir esa misma diferencia adicional de calor neto. Los tramos verticales no hacen trabajo de expansión, aunque pueden intercambiar calor. Mira [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer las trayectorias del libro|las áreas de cada recorrido]].

**3. Si una heladera extrae 300 J del interior y recibe 100 J de trabajo por ciclo, ¿cuánto entrega por el condensador? ¿Dónde está el calor útil para calcular su COP?**

> [!success]- Mostrar explicación
> Entrega $|Q_H|=300+100=400\,\mathrm J$ a la cocina. El resultado útil de refrigeración son los 300 J extraídos en el evaporador: $COP_R=300/100=3$. Los 400 J incluyen también el trabajo recibido; usarlos como numerador daría el COP de bomba de calor, cuyo objetivo es calentar. Revisa [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer el refrigerador del libro|el circuito del libro]].

**4. En la figura de expansión libre, el panel c tiene un área de trabajo positiva. ¿Significa que el gas del experimento real hizo ese trabajo?**

> [!success]- Mostrar explicación
> No. Los paneles a y b muestran una expansión hacia el vacío en un recipiente rígido y aislado: $W_{\mathrm{real}}=Q_{\mathrm{real}}=0$. El panel c representa otra trayectoria, reversible e isotérmica, imaginada para calcular el cambio de entropía entre los mismos estados. En ella sí hay trabajo y calor: $Q_{\mathrm{rev}}=W_{\mathrm{rev}}=nRT\ln2$. La propiedad que se traslada al proceso real es $\Delta S=nR\ln2$, no esos intercambios. Revisa [[Unidades/05 - Termodinámica/Teoría/05 - Conceptos de termodinámica#Leer la expansión libre del libro: el camino de cálculo|qué representa cada panel]].

## Fórmulas

**1. ¿Por qué para convertir un cambio Fahrenheit a Celsius se usa $5/9$ sin sumar o restar 32?**

> [!success]- Mostrar explicación
> El 32 desplaza el origen entre las escalas y se cancela al restar dos temperaturas: $\Delta T_C=(5/9)\Delta T_F$. Para una temperatura absoluta de escala sí se usa $T_C=(5/9)(T_F-32)$.

**2. Una sustancia se calienta y luego se funde. ¿Qué relaciones usarías y en qué orden?**

> [!success]- Mostrar explicación
> Para calentarla hasta la fusión usa $Q_1=mc\Delta T$. Mientras se funde usa $Q_2=mL_f$. Si después la fase líquida sigue cambiando de temperatura, agrega otro tramo $mc\Delta T$. No apliques $mc\Delta T$ a la meseta.

**3. ¿Cómo se plantea una mezcla aislada que incluye un vaso inicialmente frío?**

> [!success]- Mostrar explicación
> Escribe $Q_{\mathrm{líquido}}+Q_{\mathrm{vaso}}=0$. El líquido caliente tendrá $Q<0$ y el vaso tendrá $Q>0$. El vaso cuenta como parte del balance porque absorbe energía.

**4. ¿Qué significa sumar resistencias térmicas de dos paredes en serie?**

> [!success]- Mostrar explicación
> El mismo flujo de calor atraviesa ambas capas y cada una produce una caída de temperatura. Para cada capa $R_i=L_i/(k_iA)$; la potencia es $H=(T_h-T_c)/\sum_iR_i$.

**5. ¿Cuándo puedes usar $pV^\gamma=\mathrm{constante}$?**

> [!success]- Mostrar explicación
> Para un gas ideal en una transformación adiabática reversible, con evolución cuasiestática sin disipación y capacidades caloríficas aproximadamente constantes. Que $Q=0$ por sí solo no basta si el proceso no satisface esas condiciones.

**6. Con la convención de este módulo, ¿qué signos tienen $Q$ y $W$ si un gas se comprime y recibe calor?**

> [!success]- Mostrar explicación
> El calor que entra es $Q>0$. El trabajo realizado por el gas durante la compresión es $W<0$, porque el entorno lo comprime. Se colocan en $\Delta U=Q-W$.

**7. ¿Qué temperaturas se usan en una eficiencia de Carnot y por qué?**

> [!success]- Mostrar explicación
> Se usan $T_H$ y $T_C$ en kelvin: $e_C=1-T_C/T_H$. El cociente requiere la escala absoluta cuyo cero es el cero absoluto; los valores en Celsius desplazan arbitrariamente el origen.

**8. ¿Qué dato distingue la fórmula de radiación emitida de la potencia neta intercambiada con el ambiente?**

> [!success]- Mostrar explicación
> La emisión es $P_{\mathrm{emitida}}=\varepsilon\sigma AT^4$. Para saber la pérdida o ganancia neta hay que restar la radiación que absorbe del entorno: $P_{\mathrm{neta}}=\varepsilon\sigma A(T_{\mathrm{sup}}^4-T_{\mathrm{amb}}^4)$.

**9. ¿Cómo se calcula $\Delta S$ de un sistema que cambia de temperatura, y por qué las temperaturas van en kelvin?**

> [!success]- Mostrar explicación
> Para un sólido o líquido sin cambio de fase, con trabajo despreciable y $c$ constante, $\Delta S=mc\ln(T_f/T_i)$. El logaritmo requiere una razón de temperaturas absolutas; en Celsius la razón depende del cero arbitrario de la escala.

**10. Para calcular combustible, ¿divides el trabajo del motor o el calor de entrada por el poder calorífico?**

> [!success]- Mostrar explicación
> Bajo transferencia completa del calor del combustible al motor, $m=Q_H/q_{\mathrm{comb}}$. Como $Q_H=W/e$, también $m=W/(e\,q_{\mathrm{comb}})$. Dividir solo $W/q_{\mathrm{comb}}$ olvidaría la energía que el motor rechaza. Revisa [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T30. Carnot y consumo de combustible por ciclo — M · prioridad de examen alta|T30]].

**11. Si el motor entrega una potencia en kW, ¿cómo calculas cuánto calor necesita por segundo? ¿En qué unidad queda?**

> [!success]- Mostrar explicación
> Usa $\dot Q_H=P/e$. El resultado es una tasa térmica en kW o J/s, no energía por ciclo. Si la tasa es constante, multiplícala por la duración para obtener una energía. Compruébalo en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T32. Calor suministrado y desechado por segundo — M · prioridad de examen alta|T32]].

## Repaso del módulo

**1. ¿Qué pasos seguirías para resolver una mezcla de agua caliente, hielo y recipiente?**

> [!success]- Mostrar explicación
> Define el sistema; identifica las etapas de cada material; asigna signos; calcula cada tramo con $mc\Delta T$ o $mL$; incluye el recipiente si intercambia calor; finalmente escribe $\sum Q_i=0$ y comprueba que la fase y la temperatura final sean compatibles.

**2. Un gas recorre un ciclo en un diagrama $p$–$V$. ¿Qué representa el área encerrada y qué relación debe cumplir el balance al cerrar el ciclo?**

> [!success]- Mostrar explicación
> El área encerrada con signo representa el trabajo neto del gas. Al volver al estado inicial $\Delta U_{\mathrm{ciclo}}=0$, por lo que la primera ley exige $Q_{\mathrm{neto}}=W_{\mathrm{neto}}$.

**3. ¿Cómo comprobarías que los números de un motor térmico son físicamente posibles?**

> [!success]- Mostrar explicación
> Verifica $Q_H=W+|Q_C|$, $e=W/Q_H<1$ y que la eficiencia no exceda la de Carnot para los mismos focos. Un motor cíclico debe rechazar parte del calor.

**4. ¿Qué diferencia hay entre que la entropía del agua baje y que baje la entropía total?**

> [!success]- Mostrar explicación
> El agua puede perder entropía al enfriarse. Para saber si el proceso respeta la segunda ley se suma el cambio del agua al del ambiente; el total de un proceso real no puede ser negativo.

**5. ¿Qué dato del enunciado te ayuda a distinguir entre problema de primera ley y problema de segunda ley?**

> [!success]- Mostrar explicación
> Si se pide relacionar calor, trabajo y energía interna en un proceso, la primera ley organiza el balance. Si pregunta dirección espontánea, rendimiento máximo de un motor, desempeño límite o cambio total de entropía, entra la segunda ley. Muchos problemas necesitan ambas.

---

**Práctica por familia:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|Temperatura y dilatación]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase|Calorimetría y cambios de fase]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor|Transferencia de calor]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|Gases ideales y primera ley]] · [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|Segunda ley y máquinas térmicas]].
