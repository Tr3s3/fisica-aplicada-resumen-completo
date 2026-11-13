---
tags: [fisica-aplicada, teoria, conceptos, unidad-05, termodinamica]
---

# Conceptos de termodinámica

La termodinámica permite seguir la energía: **qué sistema cambia, cómo entra o sale energía y qué efecto produce**. Una misma energía transferida puede elevar la temperatura, cambiar una fase o permitir que un gas empuje un pistón. Por eso el primer paso consiste en interpretar la situación; la fórmula viene después.

Esta es la explicación extensa del módulo. Combina desarrollos didácticos con figuras originales de los capítulos 17, 19 y 20 y de las diapositivas de la materia. Los ejemplos identifican si conservan datos del libro o si son añadidos para explicar; no son nuevos enunciados de examen. **Ruta de lectura corta:** [[Unidades/05 - Termodinámica/Teoría/05 - Guía breve de termodinámica]] · **Consulta durante la práctica:** [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica]].

## Cómo recorrer esta explicación

Lee una etapa, reexplícala sin mirar y escribe qué supuesto te permite elegir la ecuación. Después intenta el ejercicio indicado. Las respuestas de autoevaluación están plegadas en su propia nota: no hace falta terminar este archivo para empezar a practicar.

| Etapa | Lectura y objetivo | Primer intento después de leer |
|---|---|---|
| 1 | [[#1. Sistema, entorno y estado térmico\|Sistema, temperatura y calor]]: distinguir una propiedad de una transferencia | T1, en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación\|temperatura y dilatación]] |
| 2 | [[#2. Temperatura, escalas y expansión térmica\|Escalas y dilatación]]: elegir la referencia y reconocer qué se expande | T2–T3; después T4–T6, en la misma familia |
| 3 | [[#3. Calor, calor específico y calorimetría\|Mezclas y fases]]: repartir energía y decidir los tramos antes de calcular | T7 → T33 → T29, en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase\|calorimetría]]; completa T8–T11 y T34 |
| 4 | [[#4. Transferencia de calor: conducción, convección y radiación\|Transferencia]]: distinguir energía de energía por segundo | T12 → T13 → T14; después T15/T35, en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor\|transferencia de calor]] |
| 5 | [[#5. Gas ideal y variables de estado\|Estado del gas]] y [[#6. Primera ley: el balance de energía\|primera ley]]: conectar estados, trabajo y energía interna | T27 y el comienzo de T28, en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley\|gases y primera ley]] |
| 6 | [[#7. Procesos termodinámicos y ciclos\|Procesos y ciclos]]: justificar cada tramo y cerrar el balance | T28 → T16 → T17/T18, en la misma familia |
| 7 | [[#8. Motores y refrigeradores: objetivos y rendimientos\|Máquinas]]: identificar el resultado útil y el límite físico | T19 → T20/T32 → T30/T31; después T21–T24, en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas\|máquinas térmicas]] |
| 8 | [[#9. Segunda ley y entropía\|Entropía]]: sumar los cambios del cuerpo y del entorno | T25–T26, en la misma familia |

T9 se aborda después de aprender a separar calentamiento y cambio de fase. El orden de esta tabla sigue los prerrequisitos conceptuales; para distribuir el repaso de un examen usa la [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Ruta prioritaria según los modelos|ruta prioritaria de los modelos]]. Las etiquetas M/R/C se mantienen en los enunciados.

> [!note] Notación que conviene fijar
> $T$ es temperatura; $\Delta T=T_f-T_i$ es su cambio. $Q$, $W$ y $U$ se expresan en joules (J). $Q$ es calor transferido, $W$ es trabajo y $U$ es energía interna. El símbolo $\mathrm W$ junto a una unidad significa **watt**, es decir, $1\,\mathrm W=1\,\mathrm{J/s}$; no es el trabajo $W$. En esta nota $p$ es presión y $P$ es potencia.

> [!info] Cómo leer los desarrollos matemáticos
> Un símbolo como $dV$ representa un cambio muy pequeño y una integral $\int$ suma esos aportes a lo largo de un proceso. Las deducciones muestran por qué aparece cada relación; para los ejercicios seleccionados puedes aplicar sus expresiones finales y concentrarte en justificar las condiciones, despejar y comprobar unidades. Al final de cada etapa se indica dónde ponerlas en práctica.

## Apoyos visuales de las fuentes

Las figuras se leen junto con su explicación: identifica primero **qué sistema aparece, qué cambia y qué representa cada flecha o eje**. Cada pie permite abrir la página original en Zotero. Puedes abrir la imagen en Obsidian para ampliarla.

| Si cuesta entender… | Mira y lee… | Qué llevar a la práctica |
|---|---|---|
| Cómo un termómetro compara dos cuerpos | [[#Leer la ley cero en la figura del libro\|Equilibrio entre A, B y C]] | Igual temperatura no implica igual energía interna |
| Por qué la longitud inicial importa | [[#Leer la expansión lineal en el libro\|Varillas de distintas longitudes]] | Distinguir longitud final de alargamiento |
| Qué ocurre con el agujero de una placa | [[#Leer la arandela de las diapositivas\|Dilatación del radio interior]] | Elegir el coeficiente lineal para un diámetro |
| Cuándo usar $mc\Delta T$ o $mL$ | [[#Leer la curva del agua en el libro\|Calentamiento y mesetas]] | Separar las etapas antes de sumar energías |
| Cómo influyen área y espesor en la conducción | [[#Leer la conducción en la figura del libro\|Tres varillas comparadas]] | Reconocer el área atravesada y la longitud recorrida |
| Qué distingue convección de conducción | [[#Leer la fotografía de convección del libro\|Circulación del agua calentada]] | Identificar el movimiento del fluido |
| Cómo el pistón conecta presión, volumen y temperatura | [[#Leer el gas bajo un pistón en las diapositivas\|Cilindro y condiciones del proceso]] | Decidir qué permanece constante |
| De dónde sale $p\,dV$ y por qué importa el camino | [[#Leer el pistón del libro\|Trabajo mecánico]] y [[#Leer las trayectorias del libro\|Áreas diferentes entre los mismos estados]] | Fijar signos y calcular trabajo por tramo |
| Cómo reconocer un proceso en $p$–$V$ | [[#Leer los cuatro procesos del libro\|Salidas distintas desde el mismo estado]] | Separar isobárico, isocórico, isotérmico y adiabático |
| Qué entra y sale de un motor o una heladera | [[#Leer el flujo de energía del motor en el libro\|Motor]] y [[#Leer el refrigerador del libro\|Refrigerador]] | Diferenciar calor transportado de trabajo consumido |
| Qué significa el límite reversible | [[#Leer el ciclo de Carnot del libro\|Cuatro etapas]] y [[#Ejemplo del libro: trabajo y calor de una máquina de Carnot\|Cálculo guiado]] | Usar Carnot como igualdad solo en su modelo |
| Cómo calcular entropía de un proceso irreversible | [[#Leer la expansión libre del libro: el camino de cálculo\|Proceso real y camino imaginado]] | No confundir $Q_{\mathrm{real}}$ con $Q_{\mathrm{rev}}$ |

Los dibujos de partículas, pistones y varillas exageran distancias para hacer visibles los cambios: no se miden sus píxeles para obtener un dato. En los gráficos, las posiciones solo permiten calcular cuando hay valores o relaciones indicadas en los ejes. Los esquemas SVG del vault se conservan para relacionar estas figuras con los TP y modelos.

## 1. Sistema, entorno y estado térmico

### Elegir qué se estudia cambia el balance

Un **sistema** es la materia que elegimos analizar. La **frontera** lo separa del **entorno**, que es todo lo demás. La frontera puede ser una pared real o una separación imaginaria que dibujamos.

Si estudias solo el té, la energía que pasa del té al vaso sale del sistema. Si estudias **té más vaso**, ese intercambio ocurre entre partes del sistema y no cruza su frontera exterior. Al resolver una mezcla, suele convenir incluir todos los cuerpos que intercambian energía: así sus pérdidas y ganancias se compensan dentro del conjunto.

| Expresión del enunciado                      | Qué permite suponer                                                      | Qué todavía puede ocurrir                              |
| -------------------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------ |
| Sistema cerrado                              | No entra ni sale materia                                                 | Puede intercambiar calor y trabajo                     |
| Sistema aislado                              | No intercambia materia ni energía con el entorno                         | Sus partes pueden intercambiar energía entre sí        |
| Pared adiabática o proceso adiabático        | El calor que cruza esa frontera es despreciable: $Q=0$                   | Puede haber trabajo y cambio de temperatura            |
| Recipiente rígido                            | Su volumen no cambia                                                     | Puede intercambiar calor; no hace trabajo de expansión |
| Recipiente de capacidad térmica despreciable | Se omite la energía necesaria para cambiar la temperatura del recipiente | Su contenido sí puede absorber o ceder energía         |

**Aislado y adiabático no son sinónimos.** Un gas bajo un pistón aislante puede empujarlo: no recibe calor, pero entrega trabajo. Tampoco “rígido” significa “aislado”: una olla rígida puede calentarse.

### Temperatura y equilibrio

La **temperatura** caracteriza el estado térmico de un cuerpo y permite predecir el sentido del intercambio espontáneo de calor. Entre dos cuerpos en contacto térmico a distinta temperatura, la transferencia neta va del de mayor temperatura al de menor temperatura, mientras no intervenga un dispositivo que fuerce el proceso opuesto.

Hay **equilibrio térmico** cuando las temperaturas se igualan y deja de haber intercambio neto debido a esa diferencia. No significa que las partículas se detengan. La **ley cero** expresa que, si A y B están cada uno en equilibrio térmico con C, están en equilibrio térmico entre sí; esto permite comparar temperaturas usando un mismo termómetro.

Un **estado** describe cómo está el sistema: por ejemplo, su temperatura, volumen, presión y fase. Para atribuir una sola temperatura a todo un cuerpo suponemos que su interior ya se equilibró lo suficiente. Una pieza recién calentada por un extremo puede tener temperaturas distintas en distintas zonas; no se reemplaza automáticamente por un cuerpo uniforme.

### Leer la ley cero en la figura del libro

![[imagenes/termodinamica-libro-equilibrio-ley-cero.png|680]]

*Fuente: cap. 17, figura 17.2; [PDF p. 3, página impresa 572](zotero://open-pdf/library/items/4NVQU8DQ?page=3). Los bloques verdes representan aislantes y las piezas grises, conductores.*

1. **Panel a:** A y B no intercambian calor directamente entre sí; ambos pueden hacerlo con C. Se espera a que cada uno alcance equilibrio con C: $T_A=T_C$ y $T_B=T_C$.
2. **Panel b:** se aísla C y se permite el contacto térmico entre A y B. Como $T_A=T_B$, no aparece una transferencia neta por diferencia de temperatura entre ellos.
3. **Conclusión útil:** C puede servir como termómetro para comparar temperaturas. La igualdad corresponde a $T$, no a masas, capacidades térmicas ni energías internas iguales.

Un termómetro real alcanza su propia temperatura de equilibrio al medir. Para que esa lectura represente aproximadamente la temperatura que el cuerpo tenía antes de introducirlo, su capacidad térmica debe ser pequeña frente a la del cuerpo. Si modifica apreciablemente la mezcla, se incluye en el balance, como en T33.

### Calor y energía interna

La **energía interna** $U$ reúne las energías microscópicas de las partículas: su movimiento y sus interacciones. No incluye el movimiento ni la altura del objeto completo. La **temperatura** no mide toda esa energía: también importan la cantidad de materia, la sustancia y la fase.

El **calor** $Q$ es energía que se transfiere por una diferencia de temperatura. Un cuerpo almacena energía interna; “calor absorbido” describe cómo recibió energía. Dos recipientes de agua a la misma temperatura pueden tener distinta energía interna si contienen distintas masas, aunque al ponerlos en contacto no haya flujo neto de calor entre ellos.

### Cómo leer un supuesto

Un supuesto simplifica el modelo y debe corresponder a una condición del problema. “Sin pérdidas” en una mezcla significa que despreciamos el intercambio con la habitación durante el experimento; **sí contamos** la energía que pasa entre los cuerpos de la mezcla. “Calor específico constante” significa que usamos un valor representativo en ese intervalo de temperaturas, no que el material tenga siempre el mismo valor.

Si una condición no está dada y modifica el resultado —por ejemplo, no sabemos si había hielo o agua— no se completa en silencio: se explicita la hipótesis o se reconoce que falta información.

> [!tip] Pausa y aplicación
> Reexplica la diferencia entre cerrado, aislado, adiabático y rígido. Contrasta tu explicación en [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Sistema, supuestos y equilibrio|autoevaluación: sistema y supuestos]] y resuelve T1 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|la primera familia]].

## 2. Temperatura, escalas y expansión térmica

### Temperatura no es cambio de temperatura

Celsius, Fahrenheit y Kelvin asignan valores a una temperatura. Para sus **valores numéricos**:

$$
T_{\mathrm K}=T_{^\circ\mathrm C}+273.15,
\qquad
T_{^\circ\mathrm F}=\frac{9}{5}T_{^\circ\mathrm C}+32.
$$

El cero de Celsius y el de Fahrenheit están desplazados. Por eso convertir una temperatura requiere un desplazamiento además de un factor de escala. Kelvin parte del cero absoluto; un kelvin tiene el mismo tamaño que un grado Celsius.

Un **cambio** compara dos estados: $\Delta T=T_f-T_i$. Al restar las conversiones de las temperaturas final e inicial se cancelan los desplazamientos:

$$
\Delta T_{\mathrm K}=\Delta T_{^\circ\mathrm C},
\qquad
\Delta T_{^\circ\mathrm C}=\frac{5}{9}\Delta T_{^\circ\mathrm F}.
$$

Por ejemplo, pasar de $20$ a $30\,^\circ\mathrm C$ equivale a pasar de $293.15$ a $303.15\,\mathrm K$: el incremento vale $10\,^\circ\mathrm C$ o $10\,\mathrm K$. No se suma $273.15$ a ese incremento.

En una razón como $T_C/T_H$, en $pV=nRT$, en radiación y en entropía se usan **temperaturas absolutas en kelvin**. Una razón de temperaturas Celsius depende de dónde elegimos el cero y no tiene la interpretación física de una razón absoluta.

### De dónde sale la expansión lineal

En muchos sólidos, al aumentar la temperatura aumenta ligeramente la distancia media entre partículas. No basta decir que “vibran más”: la interacción entre partículas no es perfectamente simétrica alrededor de su separación de equilibrio, y una vibración mayor suele desplazar la separación media. La longitud macroscópica cambia con ella.

En el laboratorio se observa que, para cambios pequeños, una varilla más larga se alarga más y un mayor incremento de temperatura produce más alargamiento. El coeficiente **lineal** $\alpha$ relaciona esos cambios:

$$
\alpha\approx\frac{\Delta L}{L_0\Delta T}
\quad\Longrightarrow\quad
\Delta L\approx\alpha L_0\Delta T.
$$

Aquí $L_0$ es la longitud a la temperatura de referencia $T_i$; $\Delta L=L_f-L_0$ y $\Delta T=T_f-T_i$. Al sumar el cambio a la longitud inicial:

$$
L_f\approx L_0(1+\alpha\Delta T).
$$

$\alpha$ tiene unidades $\mathrm{K^{-1}}$ o $^\circ\mathrm C^{-1}$: $\alpha\Delta T$ es una fracción sin unidad. Si $\alpha=1.2\times10^{-5}\,\mathrm{K^{-1}}$, cada kelvin produce aproximadamente un cambio de $0.0012\%$ de la longitud de referencia.

**Supuestos:** el objeto puede expandirse libremente, su temperatura es aproximadamente uniforme, $\alpha$ se toma constante y $|\alpha\Delta T|\ll1$. Si se impide la expansión aparecen tensiones; esa situación requiere un análisis adicional. Algunos materiales e intervalos presentan comportamientos anómalos, por lo que se usa el coeficiente correspondiente al problema.

**Aplicación:** si $\alpha>0$, al enfriar $\Delta T<0$ y $\Delta L<0$. En T3 se impone que el diámetro final del remache iguale el del agujero para encontrar la temperatura límite. En T4, cada regla tiene su propia temperatura de calibración: sus dos $\Delta T$ son diferentes aunque terminen a la misma temperatura.

### Leer la expansión lineal en el libro

![[imagenes/termodinamica-libro-expansion-lineal.png|430]]

*Fuente: cap. 17, figura 17.8; [PDF p. 7, página impresa 576](zotero://open-pdf/library/items/4NVQU8DQ?page=7). El libro llama $T_0$ a la temperatura inicial; aquí usamos también $T_i$.*

En **a**, la longitud inicial es la misma: al duplicar el aumento de temperatura se duplica el alargamiento. En **b**, el aumento de temperatura es el mismo: una varilla inicialmente dos veces más larga se alarga el doble. Son las dos proporcionalidades reunidas en $\Delta L=\alpha L_0\Delta T$.

La franja azul marca **el incremento**, no toda la longitud final. Por ejemplo, con datos añadidos para practicar la lectura, $L_0=1.00\,\mathrm m$, $\alpha=1.2\times10^{-5}\,\mathrm{K^{-1}}$ y $\Delta T=50\,\mathrm K$ dan $\Delta L=0.00060\,\mathrm m=0.60\,\mathrm{mm}$. La longitud final es $1.00060\,\mathrm m$. Confundir ambas magnitudes produciría un error mucho mayor que cualquier redondeo.

### Volumen y agujeros

Un sólido **isotrópico** tiene la misma expansión lineal en todas las direcciones. Si cada una de sus tres dimensiones se multiplica por $1+\alpha\Delta T$, el volumen se multiplica por su cubo:

$$
V_f\approx V_0(1+\alpha\Delta T)^3
\approx V_0(1+3\alpha\Delta T).
$$

En el segundo paso se descartan los términos cuadrático y cúbico porque el cambio fraccionario es pequeño. Al comparar con $\Delta V=\beta V_0\Delta T$ se obtiene $\beta\approx3\alpha$. Los líquidos se describen directamente con el coeficiente **volumétrico** $\beta$; no se les asigna una longitud propia como a una varilla.

Un agujero aumenta con una placa que se calienta libre y uniformemente. Imagina rellenarlo con el mismo material: la pieza imaginaria se dilataría junto con la placa. Al retirarla, el borde conserva esa separación mayor. Para un diámetro se usa $\alpha$; para la capacidad de un recipiente isotrópico se usa $\beta\approx3\alpha$.

### Leer la arandela de las diapositivas

![[imagenes/termodinamica-clase-arandela-dilatacion.png|250]]

*Fuente: Clase 1 de Termodinámica, 11-08-2025; [diapositiva/PDF p. 24](zotero://open-pdf/library/items/57T7VR7L?page=24). Se recortó la ilustración de la arandela; $a$ es el radio interior y $b$, el exterior.*

La arandela de abajo está más caliente. Para expansión libre y uniforme con $\alpha>0$, **ambos radios aumentan**: $\Delta a=\alpha a\Delta T$ y $\Delta b=\alpha b\Delta T$. No se añade material hacia el centro del agujero: las distancias entre todos los puntos de la pieza aumentan en la misma proporción. Por eso también crece su diámetro interior $2a$.

La llama identifica el calentamiento, pero el modelo supone que la temperatura de la pieza ya se uniformó; una pieza calentada solo en una zona puede deformarse de otra manera. En T3, separa además qué cuerpo se enfría: cambiar el diámetro de un remache no cambia automáticamente el agujero de una placa que conserva su temperatura.

### Por qué puede derramarse un líquido

Si al principio el recipiente está lleno hasta el borde, el líquido y la capacidad del recipiente parten del mismo volumen $V_0$. Tras el mismo cambio de temperatura:

$$
V_{\ell,f}=V_0(1+\beta_\ell\Delta T),
\qquad
V_{r,f}=V_0(1+\beta_r\Delta T).
$$

El volumen excedente es la diferencia:

$$
V_{\mathrm{derramado}}\approx
V_{\ell,f}-V_{r,f}
=V_0(\beta_\ell-\beta_r)\Delta T,
\quad\text{si la diferencia es positiva}.
$$

Una diferencia negativa significa que queda espacio libre, no que existe un “derrame negativo”. Se supone que ambos alcanzan la misma temperatura, que no hay evaporación apreciable y que los coeficientes representan ese intervalo. Si el recipiente no estaba lleno, primero se compara el volumen final del líquido con la capacidad final disponible.

> [!tip] Pausa y aplicación
> Revisa [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Temperatura, calor y fases|los conceptos de temperatura y dilatación]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la pregunta 1 de fórmulas]]. Intenta T2–T3 antes de continuar con T4–T6 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Temperatura y dilatación|temperatura y dilatación]].

## 3. Calor, calor específico y calorimetría

### Cambiar temperatura: qué significa cada factor

Para aumentar la temperatura de una sustancia sin cambiar su fase, hace falta una energía que depende de cuánta materia hay y de cuánto queremos cambiar su temperatura. El **calor específico** $c$ indica la energía necesaria por kilogramo y por grado, bajo las condiciones del proceso:

$$
Q=mc\Delta T=mc(T_f-T_i).
$$

- $m$ es la masa, en kg.
- $c$ se expresa en $\mathrm{J/(kg\,K)}$ y corresponde al material y a su fase.
- $mc$ es la **capacidad térmica del cuerpo**, en $\mathrm{J/K}$: energía por cada grado para esa masa completa.
- $\Delta T$ es un intervalo en K o en $^\circ\mathrm C$; el producto tiene unidad J.

Por ejemplo, $c_{\mathrm{agua}}\approx4186\,\mathrm{J/(kg\,K)}$ significa que $1\,\mathrm{kg}$ de agua necesita aproximadamente $4186\,\mathrm J$ por cada grado de aumento. El doble de masa necesita el doble de energía para el mismo cambio. Un $c$ grande significa que la temperatura cambia menos ante un mismo aporte por kilogramo.

Si te dan volumen en vez de masa, usa la **densidad** $\rho=m/V$ y despeja $m=\rho V$. Por ejemplo, el té de T7 se modela con $\rho=1.00\,\mathrm{g/cm^3}$: $200\,\mathrm{cm^3}$ corresponden a $200\,\mathrm g=0.200\,\mathrm{kg}$. El volumen no se sustituye directamente en el lugar de $m$.

Mantén compatibles la masa y el calor específico: si $c$ está en $\mathrm{J/(g\,K)}$, puedes usar gramos; si está en $\mathrm{J/(kg\,K)}$, usa kilogramos. $1\,\mathrm{J/(g\,K)}=1000\,\mathrm{J/(kg\,K)}$. Cambiar la unidad de masa sin ajustar $c$ cambia erróneamente la energía por un factor 1000.

La relación surge de medir esa proporcionalidad. Para un pequeño intervalo, $c\approx Q/(m\Delta T)$; si varía poco podemos usar un valor constante en todo el tramo. Para variaciones importantes se necesita su dependencia con la temperatura y se suman aportes pequeños.

**Condiciones de uso:** masa constante, una sola fase en el tramo, temperaturas inicial y final bien definidas y un calor específico apropiado. En los problemas de sólidos y líquidos se desprecia el trabajo de expansión y otras transferencias relevantes. En un gas el calentamiento puede incluir trabajo importante; se distingue la capacidad a presión constante de la de volumen constante, como se desarrolla en la sección 6.

Con la convención $Q>0$ para energía que entra, el signo sale de $T_f-T_i$: un cuerpo que se enfría tiene $Q<0$. No se sustituye automáticamente la diferencia por su valor absoluto.

### Cambiar de fase: por qué la temperatura puede no aumentar

Fundir un sólido o vaporizar un líquido cambia la organización y separación de sus partículas. La energía puede destinarse a ese cambio sin aumentar la temperatura. Para una sustancia pura que cambia de fase en equilibrio a presión fija, las dos fases coexisten a una temperatura característica.

El **calor latente** $L$ es la energía necesaria por kilogramo para ese cambio de fase, en $\mathrm{J/kg}$. Si cambian de fase $m_{\mathrm{transformada}}$ kilogramos:

$$
|Q_{\mathrm{fase}}|=m_{\mathrm{transformada}}L.
$$

Se escribe $Q=+mL_f$ al fundir, $Q=-mL_f$ al solidificar, $Q=+mL_v$ al vaporizar y $Q=-mL_v$ al condensar. $L_f$ y $L_v$ son valores positivos diferentes; el signo corresponde al sentido del proceso. **La masa de esta fórmula es la que efectivamente se transforma**, que puede ser menor que la masa total.

Para hielo/agua cerca de presión atmosférica se usa fusión a $0\,^\circ\mathrm C$. Esa temperatura depende de la presión y de la composición; el modelo del ejercicio supone agua pura y esas condiciones. El agua puede recibir energía a $0\,^\circ\mathrm C$ mientras queda hielo, aunque $mc\Delta T$ dé cero para ese tramo: hace falta contar $mL_f$.

### Balance de una mezcla: el origen de la suma de calores

Elige como sistema todos los cuerpos relevantes. Si el conjunto no intercambia energía con la habitación y no hay trabajo exterior apreciable, su energía total se conserva. La energía perdida por una parte es la ganada por las otras:

$$
\sum_i Q_i=0.
$$

Aquí cada $Q_i$ corresponde al **intercambio de una parte**, no a un aporte desde afuera al conjunto. Para sólidos y líquidos con trabajo despreciable, ese intercambio se traduce en su cambio de energía interna. Por eso es compatible que el conjunto esté aislado y, a la vez, que $Q_1$ o $Q_2$ no sean cero.

Para dos cuerpos sin cambio de fase:

$$
m_1c_1(T_f-T_{1,i})+m_2c_2(T_f-T_{2,i})=0.
$$

Para despejar, se agrupan los términos con $T_f$ a un lado:

$$
(m_1c_1+m_2c_2)T_f
=m_1c_1T_{1,i}+m_2c_2T_{2,i}.
$$

Así,

$$
T_f=\frac{m_1c_1T_{1,i}+m_2c_2T_{2,i}}
{m_1c_1+m_2c_2}.
$$

Es un promedio **ponderado por capacidades térmicas** $mc$. El cuerpo con mayor capacidad cambia menos su temperatura e influye más en la temperatura de equilibrio. El promedio simple solo sirve si las capacidades térmicas son iguales. Esta expresión no sustituye un balance con fusión, evaporación o una fuente adicional.

**Supuestos y controles:** todos llegan al equilibrio a una misma $T_f$; no hay pérdidas ni reacción química y se usan $c$ aproximadamente constantes. Si no hay cambios de fase ni otras fuentes, $T_f$ debe quedar entre las temperaturas iniciales. Si el recipiente tiene capacidad apreciable, agrega $m_rc_r(T_f-T_{r,i})$: omitirlo dejaría energía sin contabilizar.

### Medir modifica la mezcla: temperaturas iniciales desconocidas

Un termómetro inicialmente frío absorbe energía del agua y hace que el agua disminuya su temperatura hasta alcanzar el equilibrio. Si se da un calor específico **efectivo** del termómetro, se representa todo el instrumento por una sola capacidad $m_tc_t$, agrupando sus componentes sin estudiar cada uno por separado. La lectura final describe el equilibrio **agua más termómetro**; la temperatura inicial del agua era mayor. La ley no cambia si la incógnita es inicial:

$$
m_ac_a(T_f-T_{a,i})+m_tc_t(T_f-T_{t,i})=0
$$

$$
\Longrightarrow\quad
T_{a,i}=T_f+\frac{m_tc_t}{m_ac_a}(T_f-T_{t,i}).
$$

Si $T_f>T_{t,i}$, la corrección es positiva, como se espera. Si un metal caliente se introduce en agua y recipiente inicialmente fríos, ambos absorben energía: se suman sus dos capacidades antes de despejar la temperatura inicial del metal. Practica las dos situaciones en T33. Para hallar un calor latente desconocido, como en T34, primero se separa la energía de calentamiento de la de fusión; el resto se divide por la masa fundida.

### Recuperar una propiedad desconocida con el mismo balance

En T8, una aleación caliente cede energía a agua y recipiente inicialmente a la misma temperatura $T_c$. Si la incógnita es $c_x$ de la aleación, la energía que gana el conjunto frío es $(m_ac_a+m_rc_r)(T_f-T_c)$ y la que pierde la aleación, en magnitud, es $m_xc_x(T_{x,i}-T_f)$. Igualarlas y dividir da

$$
c_x=\frac{(m_ac_a+m_rc_r)(T_f-T_c)}{m_x(T_{x,i}-T_f)}.
$$

El numerador es una energía positiva; el denominador es masa por intervalo positivo, de modo que se obtiene un calor específico positivo en $\mathrm{J/(kg\,K)}$. No cambió el principio: solo cambió qué factor del balance se despeja.

En T34, el mercurio empieza sólido en su temperatura de fusión $T_m$ y termina líquido a $T_f>T_m$. Primero se obtiene la energía positiva cedida por agua y calorímetro. El mercurio la reparte entre fusión y calentamiento del líquido:

$$
E_{\mathrm{cedida}}=m_{\mathrm{Hg}}L_f
+m_{\mathrm{Hg}}c_{\mathrm{Hg,l}}(T_f-T_m).
$$

Por eso

$$
L_f=\frac{E_{\mathrm{cedida}}-m_{\mathrm{Hg}}c_{\mathrm{Hg,l}}(T_f-T_m)}{m_{\mathrm{Hg}}}.
$$

Se resta la energía del calentamiento **antes** de dividir por la masa. Asignar toda la energía recibida a la fusión sobreestimaría $L_f$; obtener un valor negativo indicaría un planteo o unos datos incompatibles con la secuencia supuesta.

### Decidir si se funde todo antes de calcular la temperatura

Considera un cuerpo caliente y hielo inicialmente a $0\,^\circ\mathrm C$, en un conjunto aislado, con trabajo y capacidad del recipiente despreciables. Se supone que no se llega a ebullición ni a otros cambios de fase. **Primero se decide qué fases pueden quedar; después se calcula la temperatura.**

La energía máxima que el cuerpo caliente cedería hasta llegar a cero es una cantidad positiva:

$$
E_{\mathrm{disp}}=m_hc_h(T_{h,i}-0).
$$

Se compara con $E_{\mathrm{fusión}}=m_iL_f$. $E_{\mathrm{disp}}$ es una disponibilidad para comparar; el calor con signo del cuerpo caliente, si llega a cero, sería $-E_{\mathrm{disp}}$.

1. **Si $E_{\mathrm{disp}}<m_iL_f$:** queda hielo y agua a $0\,^\circ\mathrm C$. Se funde $m_{\mathrm{fundida}}=E_{\mathrm{disp}}/L_f$; el resto permanece sólido.
2. **Si $E_{\mathrm{disp}}=m_iL_f$:** se funde el último hielo y toda el agua queda a $0\,^\circ\mathrm C$.
3. **Si $E_{\mathrm{disp}}>m_iL_f$:** se funde todo y, en este modelo, $T_f>0$. El balance correcto incluye la fusión y el calentamiento del agua resultante:

$$
m_hc_h(T_f-T_{h,i})+m_iL_f+m_ic_a(T_f-0)=0.
$$

Al agrupar y despejar:

$$
T_f=\frac{m_hc_hT_{h,i}-m_iL_f}{m_hc_h+m_ic_a}.
$$

En esta última ecuación los valores de temperatura están en Celsius con referencia a $0\,^\circ\mathrm C$; los cambios en grados Celsius tienen el mismo tamaño que en kelvin. El numerador positivo expresa que hay energía después de la fusión; el denominador reúne las capacidades que deben calentarse hasta el equilibrio. **No se calcula el calentamiento del agua con todo $E_{\mathrm{disp}}-m_iL_f$ ignorando al metal:** este también termina a $T_f$, no a cero.

Si el hielo empieza bajo cero, hay que calentarlo primero con $m_ic_{\mathrm{hielo}}(0-T_{i,i})$. Se comprueba si hay energía para llegar a la fusión antes de aplicar las tres ramas anteriores. Si el recipiente intercambia energía, se añade su término. Estos casos requieren volver al balance, no aplicar sin cambios la fórmula de este ejemplo. T10 y T29 muestran esas decisiones.

### Leer una curva de calentamiento

![[imagenes/termodinamica-curva-calentamiento.svg]]

*Esquema del vault basado en la lectura de curvas de calentamiento del TP1, ejercicio 14. Mira el eje horizontal: es tiempo, no energía.*

El calentador aporta una potencia $P$ en J/s. Si es constante y toda esa energía llega a la muestra, durante un tramo de duración $\Delta t$:

$$
Q=P\Delta t.
$$

En un tramo inclinado no cambia la fase. Al igualar $P\Delta t=mc\Delta T$ se obtiene

$$
c=\frac{P\Delta t}{m\Delta T},
\qquad
\frac{\Delta T}{\Delta t}=\frac{P}{mc}.
$$

Por eso, a igual masa y potencia, una pendiente más pronunciada significa menor calor específico. En una meseta, $\Delta T=0$ pero el calentador sigue aportando energía; $P\Delta t=mL$, de donde $L=P\Delta t/m$. Se usa la **duración de ese tramo**, no el tiempo total desde el comienzo. Si hay pérdidas, la potencia absorbida por la muestra es menor que la suministrada; la igualdad anterior exige despreciarlas o conocerlas.

### Leer la curva del agua en el libro

![[imagenes/termodinamica-libro-curva-agua-fases.png|720]]

*Fuente: cap. 17, figura 17.21; [PDF p. 19, página impresa 588](zotero://open-pdf/library/items/4NVQU8DQ?page=19). Muestra agua pura a presión aproximadamente atmosférica, con aporte de calor a tasa constante.*

Recorre la línea roja de izquierda a derecha:

- **a→b:** se calienta hielo bajo cero; $Q=mc_{\mathrm{hielo}}(0-T_i)$.
- **b→c:** coexisten hielo y agua a $0\,^\circ\mathrm C$; la energía funde hielo, $Q=mL_f$ si termina de fundirse toda la muestra.
- **c→d:** el agua líquida aumenta de temperatura; $Q=mc_{\mathrm{agua}}(100-0)$ para completar ese tramo.
- **d→e:** coexisten agua líquida y vapor a $100\,^\circ\mathrm C$; $Q=mL_v$ si se vaporiza toda la muestra.
- **Después de e:** ya se calienta vapor; corresponde su calor específico, bajo las condiciones del proceso.

En una meseta la muestra **no está toda en una única fase** hasta llegar a su extremo final. El tiempo transcurrido dentro de ella permite determinar cuánta masa se transformó: $m_{\mathrm{transformada}}=P\Delta t/L$. La figura no trae una escala numérica de tiempo, por lo que no se puede obtener un valor de $L$ midiendo el ancho del dibujo. El gráfico de T9 sí proporciona datos para calcular.

> [!tip] Pausa y aplicación
> Reexplica por qué primero se determina la fase y después $T_f$. Comprueba [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Temperatura, calor y fases|calor, fases y mezclas]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Decisiones que aparecen en la práctica ampliada|las decisiones de fase]]. Intenta T7 y T33, continúa con T29/T10 y usa T9 para leer una curva en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Calorimetría y cambios de fase|calorimetría y cambios de fase]].

## 4. Transferencia de calor: conducción, convección y radiación

![[imagenes/termodinamica-transferencia-calor.svg]]

*Esquema didáctico del vault. Compara qué transporta la energía: interacciones locales, movimiento de fluido u ondas electromagnéticas.*

### Energía transferida y rapidez de transferencia

$Q$ indica cuánta energía pasó, en J. La **potencia térmica** indica cuánta pasa por segundo, en W. Para una tasa constante de magnitud $H$, $|Q|=H\Delta t$. No es lo mismo perder $1000\,\mathrm J$ en un segundo que en una hora: la energía es igual y la rapidez de pérdida cambia.

Aquí usamos $H\ge0$ para la magnitud de la potencia por conducción. La densidad de flujo sería $H/A$, en $\mathrm{W/m^2}$: no se confunde con la potencia total $H$.

### Conducción a través de una pared

La conducción transfiere energía mediante interacciones microscópicas sin transporte macroscópico del material. En un metal también contribuyen sus electrones móviles. Para una pared plana:

$$
H=kA\frac{T_h-T_c}{L},\qquad T_h>T_c.
$$

$k$ es la conductividad, en $\mathrm{W/(m\,K)}$; $A$ es el área perpendicular al paso del calor, en $\mathrm{m^2}$, y $L$ es el espesor recorrido, en m. Una mayor diferencia térmica impulsa más transferencia; más área ofrece más caminos simultáneos y más espesor dificulta atravesar el material.

La relación es el caso de pared uniforme de la **ley de Fourier**, $\dot Q_x=-kA\,dT/dx$: el signo menos indica transferencia hacia temperaturas menores. Si el perfil es lineal, su pendiente en valor absoluto es $(T_h-T_c)/L$ y se obtiene la expresión anterior.

**Supuestos:** régimen estacionario, conducción en una dirección, $k$ constante, caras a temperaturas fijas, sin generación interna ni pérdidas laterales apreciables. *Estacionario* significa que la temperatura de cada lugar ya no cambia con el tiempo; no significa que toda la pared esté a la misma temperatura. Entra y sale la misma energía por segundo, por lo que no se acumula energía en ella.

Las temperaturas de la fórmula son las de las **caras de la pared**. Si el TP da las del aire y las usa directamente, está despreciando las diferencias aire–superficie y sus resistencias de convección. T12 y T35 usan este modelo simplificado.

### Leer la conducción en la figura del libro

![[imagenes/termodinamica-libro-conduccion-area-espesor.png|400]]

*Fuente: cap. 17, figura 17.23; [PDF p. 23, página impresa 592](zotero://open-pdf/library/items/4NVQU8DQ?page=23). Las tres situaciones mantienen el material y las temperaturas de los extremos.*

En **a** se fija la referencia: el calor atraviesa una sección $A$ y recorre una longitud $L$ desde $T_H$ hasta $T_C$. Las flechas representan transferencia de energía; la varilla no viaja hacia el extremo frío.

En **b** se duplica el área perpendicular al flujo y la potencia se duplica: hay más material conduciendo en paralelo. En **c** se duplica la distancia recorrida y la potencia se reduce a la mitad. Esta comparación da sentido a $H\propto A/L$. Para una pared, $L$ es su espesor y $A$ la superficie de su cara; no se intercambian aunque ambos aparezcan como dimensiones en el dibujo.

Si área y espesor se duplican **a la vez**, los factores se compensan y $H$ queda igual, siempre que se mantengan $k$ y las temperaturas. Puedes comprobar esa lectura en [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Lectura de figuras de las fuentes|la autoevaluación visual]] antes de intentar T12/T35.

### Comparar aislantes sin confundir espesor y conductividad

Si dos paredes tienen igual área, espesor y diferencia de temperatura, $H$ es proporcional a $k$: $H_2/H_1=k_2/k_1$. La reducción respecto de la primera se calcula como $(H_1-H_2)/H_1$; se multiplica por 100 para expresarla en porcentaje. El denominador fija con qué situación se compara.

Para que dos materiales de distinto $k$ dejen pasar la misma potencia con iguales área y diferencia térmica, deben tener igual resistencia: $L_1/k_1=L_2/k_2$. Despejar da $L_2=L_1k_2/k_1$: el material más conductor necesita mayor espesor. Es la comparación que se practica en T35.

### Capas en serie y temperatura de unión

Varias placas están **en serie** cuando el calor debe atravesar primero una, después la siguiente y así hasta la cara fría. Consideramos placas planas de la misma área $A$, en régimen estacionario, con contacto térmico ideal, sin generación interna ni pérdidas por los costados. Sus espesores $L_i$ y conductividades $k_i$ pueden ser distintos; el subíndice $i$ identifica la placa.

![[imagenes/termodinamica-placas-en-serie.svg|750]]

*Esquema didáctico del vault: tres placas consecutivas. Cada una tiene su propia caída de temperatura, pero todas conducen la misma energía por segundo. Los anchos del dibujo no representan espesores a escala.*

#### 1. Por qué hay un único valor de H

Llamamos $H_1$, $H_2$ y $H_3$ a las potencias que atraviesan las placas. Si a una unión le llegara más energía por segundo de la que sale, se calentaría y su temperatura cambiaría. Como el régimen es estacionario, no hay acumulación:

$$
H_1-H_2=0,\qquad H_2-H_3=0
\quad\Longrightarrow\quad
\boxed{H_1=H_2=H_3=H}.
$$

**Lo que cambia entre placas es la caída de temperatura necesaria para conducir ese mismo $H$.** Una placa más resistente necesita una caída mayor. El calor atraviesa las placas sucesivamente: las potencias no se suman para obtener la que atraviesa el conjunto.

#### 2. Despejar la caída de temperatura de cada placa

Empecemos con **dos placas**. Sus caras exteriores están a $T_h$ y $T_c$, con $T_h>T_c$, y la unión está a una temperatura desconocida $T_x$. Para la primera placa, la diferencia es $T_h-T_x$; para la segunda, $T_x-T_c$:

$$
H=k_1A\frac{T_h-T_x}{L_1},
\qquad
H=k_2A\frac{T_x-T_c}{L_2}.
$$

Para despejar $H$ sin conocer todavía $T_x$, primero dejamos sola **la diferencia de temperaturas** en cada ecuación. En la placa 1, multiplicamos ambos lados por $L_1$ y después dividimos ambos lados por $k_1A$:

$$
\begin{aligned}
HL_1&=k_1A(T_h-T_x),\\
\frac{HL_1}{k_1A}&=T_h-T_x,\\
T_h-T_x&=H\frac{L_1}{k_1A}.
\end{aligned}
$$

El factor $L_1/(k_1A)$ se llama **resistencia térmica** $R_1$. Repetir el mismo despeje en la placa 2 da:

$$
R_1=\frac{L_1}{k_1A},\qquad R_2=\frac{L_2}{k_2A},
\qquad
T_h-T_x=HR_1,\qquad T_x-T_c=HR_2.
$$

Cada $R_i$ se mide en K/W; por eso $HR_i$ es una diferencia de temperatura en K, equivalente numéricamente a una diferencia en °C. Esta resistencia no es la constante de los gases $R$.

#### 3. Sumar las caídas y despejar H

Sumamos las dos ecuaciones completas. La temperatura de unión aparece una vez restando y otra sumando, por lo que se cancela:

$$
\begin{aligned}
(T_h-T_x)+(T_x-T_c)&=HR_1+HR_2,\\
T_h-T_c&=H(R_1+R_2).
\end{aligned}
$$

En el segundo paso sacamos **factor común $H$** a la derecha. Para dejarlo solo, dividimos ambos lados por $R_1+R_2$:

$$
\frac{T_h-T_c}{R_1+R_2}=H,
\qquad
\boxed{H=\frac{T_h-T_c}{R_1+R_2}}.
$$

Si reemplazamos las resistencias por sus definiciones, queda la misma fórmula escrita directamente con los datos de las placas:

$$
H=\frac{T_h-T_c}{\dfrac{L_1}{k_1A}+\dfrac{L_2}{k_2A}}
=\frac{A(T_h-T_c)}{\dfrac{L_1}{k_1}+\dfrac{L_2}{k_2}}.
$$

La última igualdad usa que **el área es la misma en ambas placas**: se extrae $1/A$ como factor común del denominador y dividir por $1/A$ equivale a multiplicar por $A$.

**Con tres placas se repite exactamente el procedimiento.** Ahora hay dos temperaturas de unión, $T_1$ y $T_2$:

$$
\begin{aligned}
T_h-T_1&=HR_1,\\
T_1-T_2&=HR_2,\\
T_2-T_c&=HR_3.
\end{aligned}
$$

Sumando miembro a miembro, se cancelan $-T_1+T_1$ y $-T_2+T_2$:

$$
\begin{aligned}
(T_h-T_1)+(T_1-T_2)+(T_2-T_c)&=HR_1+HR_2+HR_3,\\
T_h-T_c&=H(R_1+R_2+R_3),\\
\boxed{H}&=\boxed{\frac{T_h-T_c}{R_1+R_2+R_3}}.
\end{aligned}
$$

Para **$n$ placas consecutivas**:

$$
\boxed{H=\frac{T_h-T_c}{R_1+R_2+\cdots+R_n}}
=\frac{A(T_h-T_c)}{\dfrac{L_1}{k_1}+\dfrac{L_2}{k_2}+\cdots+\dfrac{L_n}{k_n}}.
$$

El símbolo $\sum_iR_i$ es una forma abreviada de escribir $R_1+R_2+\cdots+R_n$: **se suman las resistencias**, cada una calculada con el espesor y la conductividad de su placa.

#### 4. Recuperar las temperaturas de unión

Una vez conocido $H$, calculamos la caída de cada placa con $\Delta T_i=HR_i$. Empezando por la cara caliente, restamos una caída después de otra:

$$
T_1=T_h-HR_1,\qquad
T_2=T_1-HR_2=T_h-H(R_1+R_2),\qquad
T_c=T_2-HR_3.
$$

Para dos placas, basta $T_x=T_h-HR_1$; también se puede partir desde la cara fría y sumar: $T_x=T_c+HR_2$. Ambos caminos deben dar la misma temperatura.

#### 5. Ejemplo didáctico con tres placas

Estos valores se eligen para mostrar el cálculo; no corresponden a un enunciado del TP. Las tres placas tienen área $A=0.50\,\mathrm{m^2}$ y las caras exteriores se mantienen a $T_h=100\,^\circ\mathrm C$ y $T_c=20\,^\circ\mathrm C$.

| Placa, desde la cara caliente | Espesor $L_i$ | Conductividad $k_i$ | Resistencia $R_i=L_i/(k_iA)$ |
|---|---|---|---|
| 1 | $0.020\,\mathrm m$ | $0.40\,\mathrm{W/(m\,K)}$ | $0.020/(0.40\cdot0.50)=0.10\,\mathrm{K/W}$ |
| 2 | $0.040\,\mathrm m$ | $0.16\,\mathrm{W/(m\,K)}$ | $0.040/(0.16\cdot0.50)=0.50\,\mathrm{K/W}$ |
| 3 | $0.020\,\mathrm m$ | $0.20\,\mathrm{W/(m\,K)}$ | $0.020/(0.20\cdot0.50)=0.20\,\mathrm{K/W}$ |

Primero obtenemos la potencia común usando la diferencia **total** y la resistencia **total**:

$$
H=\frac{100-20}{0.10+0.50+0.20}
=\frac{80\,\mathrm K}{0.80\,\mathrm{K/W}}
=\boxed{100\,\mathrm W}.
$$

Después repartimos los $80\,^\circ\mathrm C$ de caída entre las placas:

$$
\Delta T_1=(100)(0.10)=10\,\mathrm K,\qquad
\Delta T_2=(100)(0.50)=50\,\mathrm K,\qquad
\Delta T_3=(100)(0.20)=20\,\mathrm K.
$$

Las temperaturas se recorren en este orden:

$$
100\,^\circ\mathrm C
\xrightarrow{\text{placa 1: baja }10\,\mathrm K}90\,^\circ\mathrm C
\xrightarrow{\text{placa 2: baja }50\,\mathrm K}40\,^\circ\mathrm C
\xrightarrow{\text{placa 3: baja }20\,\mathrm K}20\,^\circ\mathrm C.
$$

**Comprobación:** al aplicar la ley de una placa con su propia diferencia térmica, recuperamos el mismo valor en las tres:

$$
H_1=\frac{(0.40)(0.50)(100-90)}{0.020}=100\,\mathrm W,\qquad
H_2=\frac{(0.16)(0.50)(90-40)}{0.040}=100\,\mathrm W,
$$
$$
H_3=\frac{(0.20)(0.50)(40-20)}{0.020}=100\,\mathrm W.
$$

La placa 2 tiene la mayor resistencia y la mayor caída de temperatura. Las caídas suman $10+50+20=80\,\mathrm K$ y se llega a la temperatura fría indicada.

> [!warning] Qué diferencia de temperatura usar
> Para todo el conjunto, usa $T_h-T_c$ y $R_1+R_2+\cdots+R_n$. Para una sola placa, usa las temperaturas de **sus propias caras** y su $R_i$. En el ejemplo, poner $100-20$ en cada placa daría potencias incompatibles con el régimen estacionario. La potencia del conjunto es $100\,\mathrm W$: no se suman $H_1+H_2+H_3$, porque es la misma energía atravesando tres etapas.

**Pasa a práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#T13. Dos placas y temperatura de contacto — R · antecedente 2025 aportado por el estudiante · prioridad de estudio alta|T13: aplicar el procedimiento a dos placas del TP]].

### Convección

En líquidos y gases, la energía también se transporta con el movimiento del fluido. En **convección natural**, diferencias de densidad y gravedad generan circulación: en condiciones comunes, aire calentado menos denso asciende. En **convección forzada**, un ventilador o una bomba impulsan el fluido. Puede coexistir con conducción y radiación; los cálculos de los TP se concentran en los otros dos mecanismos.

### Leer la fotografía de convección del libro

![[imagenes/termodinamica-libro-conveccion-agua.png|300]]

*Fuente: cap. 17, figura 17.28; [PDF p. 26, página impresa 595](zotero://open-pdf/library/items/4NVQU8DQ?page=26). Un elemento en la punta del tubo calienta el agua que lo rodea.*

La región agitada que asciende muestra que **el propio fluido se desplaza**. El agua próxima al calentador recibe energía, normalmente se vuelve menos densa y asciende; otra agua ocupa su lugar y se establece circulación. La energía no queda transportada únicamente por interacciones entre partículas que permanecen en la misma región, como en el modelo de conducción en una pared fija.

La fotografía ayuda a reconocer el mecanismo, pero no da una potencia térmica por sí sola. No se aplica la fórmula de pared plana al dibujo de esa corriente; para un cálculo de convección harían falta otros datos y un modelo apropiado.

### Radiación: emitir y perder energía neta

Toda superficie a temperatura superior a cero absoluto emite radiación electromagnética. No necesita un medio material ni contacto. La ley de **Stefan–Boltzmann** describe la potencia emitida:

$$
P_{\mathrm{emitida}}=\varepsilon\sigma A T_{\mathrm{sup}}^4.
$$

$\sigma=5.67\times10^{-8}\,\mathrm{W/(m^2\,K^4)}$; $\varepsilon$ es la **emisividad**, adimensional entre 0 y 1, que compara la emisión con la de un emisor ideal. Se usa el área que efectivamente radia. Al convertir áreas se eleva al cuadrado el factor de longitud: $1\,\mathrm{mm^2}=(10^{-3}\,\mathrm m)^2=10^{-6}\,\mathrm{m^2}$. Esta ley es una relación física de partida, no una consecuencia de $Q=mc\Delta T$.

El cuerpo también absorbe radiación del ambiente. Para una superficie gris —aproximada con la misma emisividad y absorptividad relevantes— rodeada por un entorno grande, uniforme e isotérmico:

$$
P_{\mathrm{neta,saliente}}=
\varepsilon\sigma A(T_{\mathrm{sup}}^4-T_{\mathrm{amb}}^4).
$$

Ambas temperaturas van en K y se elevan por separado a la cuarta potencia: **$T_{\mathrm{sup}}^4-T_{\mathrm{amb}}^4$ no es $(T_{\mathrm{sup}}-T_{\mathrm{amb}})^4$**. Si el cuerpo está más caliente, esta potencia saliente es positiva; su calor recibido por radiación es negativo. A igual temperatura sigue emitiendo y absorbiendo, pero la transferencia neta es cero.

T14 pide el intercambio neto. T15 adopta explícitamente el modelo de potencia eléctrica igual a potencia emitida: se desprecia la absorción ambiental y las pérdidas por otros mecanismos, y la temperatura del filamento se mantiene estable. Si la absorción ambiental fuera relevante, el balance de potencia usaría la emisión **neta**.

> [!tip] Pausa y aplicación
> Distingue J de W, emisión de intercambio neto y estacionario de temperatura uniforme. Comprueba [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Transferencia: condiciones del modelo|las condiciones de transferencia]] y las preguntas 4/8 de [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|fórmulas]]. Intenta T12 → T13 → T14 antes de T15/T35 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Transferencia de calor|transferencia de calor]].

## 5. Gas ideal y variables de estado

### Qué representan los datos de un gas

Un gas puede ocupar el volumen disponible y ejercer presión sobre sus paredes. Para describir un estado de equilibrio usamos:

- $p$: **presión absoluta**, fuerza normal por unidad de área, en Pa. Si se da presión manométrica, se suma la atmosférica para obtener la absoluta.
- $V$: volumen ocupado, en $\mathrm{m^3}$. $1\,\mathrm L=10^{-3}\,\mathrm{m^3}$ y $1\,\mathrm{cm^3}=10^{-6}\,\mathrm{m^3}$.
- $T$: temperatura absoluta, en K.
- $n$: cantidad de sustancia, en mol. Un mol contiene un número fijo de partículas. Si se conocen la masa $m$ y la masa molar $M$, $n=m/M$, usando unidades de masa compatibles.

En un gas ideal las partículas tienen tamaño despreciable frente al espacio disponible y sus interacciones se desprecian salvo en los choques. La presión surge de los choques con las paredes. La temperatura se relaciona con la energía cinética media de traslación de las partículas; no con la rapidez de una partícula concreta.

El modelo funciona mejor para gases diluidos lejos de la condensación. **Ideal** describe cómo modelamos la materia; no significa que el proceso sea reversible o adiabático.

### Ecuación de estado: qué conecta y qué no

Las leyes experimentales muestran que, para una cantidad fija, $pV$ es proporcional a la temperatura absoluta. Se reúnen en

$$
pV=nRT,\qquad R=8.314\,\mathrm{J/(mol\,K)}.
$$

Es una **ecuación de estado**: relaciona las propiedades en un estado de equilibrio. No determina por sí sola el calor ni el trabajo transferidos para llegar a ese estado. Para $n$ fijo:

$$
\frac{p_iV_i}{T_i}=nR=\frac{p_fV_f}{T_f},
\qquad
\frac{T_f}{T_i}=\frac{p_fV_f}{p_iV_i}.
$$

Esto permite comparar temperaturas en un gráfico sin conocer los moles: mayor $pV$ significa mayor $T$ para el mismo gas. Que dos extremos tengan el mismo producto solo prueba igual temperatura **en esos extremos**; no demuestra una trayectoria isotérmica entre ellos.

Como $\mathrm{Pa\,m^3}=\mathrm{N\,m}=\mathrm J$, los productos $pV$ tienen unidad de energía. Esto no significa que $pV$ sea siempre el trabajo: el trabajo también depende de cómo cambió el volumen.

### Leer el gas bajo un pistón en las diapositivas

![[imagenes/termodinamica-clase-gas-piston.png|220]]

*Fuente: Clase 1 de Termodinámica, 11-08-2025; [diapositiva/PDF p. 30](zotero://open-pdf/library/items/57T7VR7L?page=30). La flecha doble indica que el pistón puede moverse; no representa una oscilación obligatoria.*

Elige como sistema **el gas debajo del pistón**. La posición de la cara móvil determina su volumen; los choques de las partículas contra esa cara originan la presión. Si no hay fugas, la cantidad $n$ es la misma en los estados inicial y final.

La imagen por sí sola no fija el proceso. Hay que leer la condición que acompaña al movimiento:

- **Temperatura constante:** $p_iV_i=p_fV_f$; al duplicar $V$, la presión se reduce a la mitad. Es la ley de Boyle para cantidad fija.
- **Presión constante:** $V_f/V_i=T_f/T_i$; al duplicar la temperatura **en kelvin**, se duplica el volumen. Es la proporcionalidad descrita en la diapositiva.
- **Pistón inmovilizado:** $V$ permanece constante y $p_f/p_i=T_f/T_i$.

Estas relaciones se obtienen de $pV=nRT$ eliminando los factores constantes. Para saber cuánto calor entró o qué trabajo hubo se necesita además la primera ley y la trayectoria. Un pistón móvil no implica automáticamente temperatura constante ni ausencia de calor.

> [!tip] Pausa y aplicación
> Revisa [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Gases, procesos y lectura de gráficos|estado y trayectoria de un gas]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|las fórmulas de gases]]. Identifica los estados y compara temperaturas de T28 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|la práctica de gases]]. Continúa con la primera ley para calcular sus intercambios de energía.

## 6. Primera ley: el balance de energía

### Separar calor, trabajo y energía interna

La **primera ley** expresa conservación de energía. Para un sistema cerrado, si no cambian apreciablemente su energía cinética ni su energía potencial como cuerpo completo, se escribe

$$
\Delta U=Q-W.
$$

Usamos la convención del módulo: $Q>0$ si entra calor al sistema y $W>0$ si el sistema realiza trabajo sobre el entorno. $Q$ y $W$ corresponden al mismo proceso; $\Delta U=U_f-U_i$ compara sus estados. Si hubiera cambios del movimiento o de la altura del conjunto, también entrarían en el balance total. Si entrara o saliera materia haría falta contabilizar la energía transportada con ella.

![[imagenes/termodinamica-sistema-balance.svg]]

*Esquema creado para el vault. Sigue las flechas respecto de la frontera: el calor que entra suma energía y el trabajo que sale la resta. Una frontera que impide calor todavía puede permitir trabajo.*

La ecuación puede leerse también como $Q=\Delta U+W$: el calor neto recibido se reparte entre cambio de energía interna y trabajo neto entregado. **No exige que ambos términos sean positivos.** Una compresión tiene $W<0$; entonces $-W>0$ representa energía que entra como trabajo.

Por ejemplo, si un gas recibe $1000\,\mathrm J$ y entrega $400\,\mathrm J$ de trabajo, $\Delta U=1000-400=600\,\mathrm J$. Si está térmicamente aislado y el entorno realiza $400\,\mathrm J$ sobre él, $Q=0$, $W=-400\,\mathrm J$ y $\Delta U=+400\,\mathrm J$. Puede aumentar su temperatura sin recibir calor.

> [!note] Dos convenciones compatibles
> Una fuente que use $W_{\mathrm{sobre}}$ para el trabajo recibido escribirá $\Delta U=Q+W_{\mathrm{sobre}}$. Como $W_{\mathrm{sobre}}=-W$, expresa el mismo balance. Mantén una sola convención en cada resolución.

### De fuerza y desplazamiento al trabajo de un gas

Un gas en un cilindro empuja un pistón de área $A$. En el modelo de movimiento lento, presión bien definida y rozamiento despreciable, la fuerza es $F=pA$. Un pequeño desplazamiento $dx$ cambia el volumen en $dV=A\,dx$. Por la definición mecánica de trabajo:

$$
\delta W=F\,dx=pA\,dx=p\,dV.
$$

### Leer el pistón del libro

![[imagenes/termodinamica-libro-piston-trabajo.png|550]]

*Fuente: cap. 19, figura 19.5; [PDF p. 3, página impresa 648](zotero://open-pdf/library/items/HJSBDNDF?page=3). El área $A$ corresponde a la cara circular del pistón.*

La flecha roja es la fuerza $pA$ **del gas sobre el pistón**. La marca $dx$ compara dos posiciones muy próximas de esa cara. El volumen añadido es un cilindro delgado: área de base por espesor, $dV=A\,dx$. Por eso el trabajo mecánico $F\,dx$ se convierte en $p\,dV$.

En la expansión, fuerza y desplazamiento apuntan hacia afuera: el gas entrega trabajo positivo. Al comprimirlo, el desplazamiento cambia de sentido y el trabajo del gas es negativo. No se confunde esta fuerza con la que el entorno ejerce sobre el gas.

Los símbolos $dx$ y $dV$ representan cambios muy pequeños; sumar todos los aportes da la integral

$$
W=\int_{V_i}^{V_f}p(V)\,dV.
$$

La presión puede cambiar mientras se mueve el pistón. Si permanece constante, sale de la suma y $W=p(V_f-V_i)$. En expansión $dV>0$ y $W>0$; en compresión $dV<0$ y $W<0$.

Para usar la presión del **gas** en toda la trayectoria se requiere evolución mecánica aproximadamente en equilibrio. Si el gas se expande bruscamente no suele tener una presión uniforme que pueda dibujarse como una curva de estados. En el modelo de trabajo contra una presión exterior conocida se analiza $\int p_{\mathrm{ext}}\,dV$; no se introduce sin justificación la presión inicial del gas. La expansión libre contra el vacío ilustra el límite: el volumen aumenta, pero no se empuja una carga exterior y el trabajo de expansión es cero.

### Por qué el camino importa

En el gráfico $p$–$V$, el trabajo de una trayectoria cuasiestática es el área bajo la curva **con el signo del cambio de volumen**. Dos caminos entre los mismos estados pueden tener áreas distintas y trabajos distintos. Como el cambio $\Delta U$ es el mismo, sus calores también pueden ser diferentes.

$U$ es una **función de estado**; $Q$ y $W$ dependen del proceso. Por eso tiene sentido escribir $U_f-U_i$, pero no una cantidad de “calor almacenado final menos inicial”.

### Leer las trayectorias del libro

![[imagenes/termodinamica-libro-trayectorias-trabajo.png|780]]

*Fuente: cap. 19, figura 19.7; [PDF p. 5, página impresa 650](zotero://open-pdf/library/items/HJSBDNDF?page=5). Se reorganizaron sus cuatro paneles en dos filas para facilitar la lectura; se conservan sus letras, ejes y trayectorias.*

Los tres recorridos unen **el mismo estado 1 con el mismo estado 2**. En el dibujo $p_1>p_2$ y $V_2>V_1$. Sigue las flechas, no solo los puntos de llegada:

1. **Panel b, 1→3→2:** primero se expande a la presión alta $p_1$; luego baja la presión sin cambiar volumen. Solo el tramo horizontal aporta trabajo: $W_b=p_1(V_2-V_1)$.
2. **Panel c, 1→4→2:** primero baja la presión a volumen fijo; después se expande a la presión baja $p_2$. Ahora $W_c=p_2(V_2-V_1)$.
3. **Panel d:** la presión disminuye mientras aumenta el volumen. El área y el trabajo quedan entre los dos anteriores. La curva dibujada no aporta una ecuación suficiente para calcular un valor exacto ni para llamarla isotérmica.

Restar los dos trabajos rectangulares da $W_b-W_c=(p_1-p_2)(V_2-V_1)>0$. **Mismos extremos no significan mismo trabajo.** Para el mismo sistema, $\Delta U$ sí coincide; como $Q=\Delta U+W$, la diferencia entre sus calores es también $Q_b-Q_c=W_b-W_c$. Esta es la razón física para resolver T28 por tramos antes de cerrar el balance.

### Energía interna del gas ideal

Al despreciar la energía de interacción entre partículas, la energía interna del gas ideal depende solo de $T$ para una cantidad fija. La capacidad calorífica **molar a volumen constante** $C_V$ se define midiendo el calor por mol y por grado cuando no cambia el volumen. Como allí $W=0$, ese calor cambia únicamente la energía interna:

$$
\Delta U=nC_V(T_f-T_i),\qquad C_V\text{ constante}.
$$

Aunque $C_V$ se mida a volumen constante, **esta expresión para $\Delta U$ vale en cualquier trayectoria del gas ideal** entre esas temperaturas. Lo que no vale para cualquier trayectoria es identificar $Q$ con $nC_V\Delta T$: puede haber trabajo.

En el modelo clásico, cada forma independiente de movimiento que almacena energía aporta a $C_V$. Un gas monoatómico tiene tres componentes de traslación y $C_V=3R/2$. Un diatómico a temperaturas ordinarias suele tener además dos modos de rotación activos: $C_V\approx5R/2$. A otras temperaturas cambian los modos activos; en los ejercicios se usa el modelo o el $\gamma$ indicado.

### Por qué $C_P$ es mayor que $C_V$

$C_P$ mide el calor por mol y por grado a **presión constante**. Al calentarse a presión constante, el gas también se expande y realiza trabajo. De $pV=nRT$ con $p$ constante se obtiene $p\Delta V=nR\Delta T$. Entonces:

$$
Q=\Delta U+W=nC_V\Delta T+nR\Delta T
=n(C_V+R)\Delta T.
$$

Como en ese proceso $Q=nC_P\Delta T$, resulta

$$
C_P=C_V+R.
$$

No aparece una energía extra sin origen: el mayor aporte cubre el trabajo que el gas entrega. $C_V$ y $C_P$ se miden en $\mathrm{J/(mol\,K)}$; el $c$ de calorimetría se refiere a masa, en $\mathrm{J/(kg\,K)}$. No son intercambiables sin convertir la cantidad de sustancia.

El cociente $\gamma=C_P/C_V$ es adimensional. Usando $C_P=C_V+R$:

$$
\gamma=1+\frac{R}{C_V}
\quad\Longrightarrow\quad
C_V=\frac{R}{\gamma-1}.
$$

Para monoatómico $C_P=5R/2$ y $\gamma=5/3$; para diatómico ordinario $C_P\approx7R/2$ y $\gamma\approx1.40$. Si el enunciado da $\gamma$, esta relación evita tener que adivinar $C_V$.

> [!tip] Pausa y aplicación
> Reexplica cómo puede cambiar $U$ con $Q=0$ y por qué $\Delta U=nC_V\Delta T$ no obliga a volumen constante. Comprueba [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Gases, procesos y lectura de gráficos|gases y procesos]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|los signos de la primera ley]]. Intenta T27 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|la práctica de gases]] y continúa con las condiciones de cada proceso.

## 7. Procesos termodinámicos y ciclos

### Reconocer la condición antes de simplificar

Un **proceso** conecta dos estados. Su nombre indica una condición de la trayectoria, no qué ecuación resulta más cómoda. Para el gas ideal del módulo, con cantidad fija y solo trabajo de expansión:

| Proceso | Qué permanece fijo o se anula | Qué simplifica en el balance |
|---|---|---|
| Isocórico o isovolumétrico | $V$ constante | $W=0$ y $Q=\Delta U$ |
| Isobárico | $p$ constante | $W=p\Delta V=nR\Delta T$ |
| Isotérmico | $T$ constante | $\Delta U=0$ y $Q=W$, para gas ideal |
| Adiabático | No se intercambia calor: $Q=0$ | $\Delta U=-W$ |

Un proceso **cuasiestático** avanza suficientemente despacio respecto del tiempo de ajuste interno del sistema como para aproximarlo por estados de equilibrio sucesivos. Así pueden asignarse $p$ y $T$ al gas en cada punto. Un proceso **reversible** permite invertirlo mediante cambios infinitesimales y devolver sistema y entorno a sus estados iniciales, sin efectos netos restantes. Requiere además evitar fricción y transferencia de calor a través de diferencias finitas de temperatura, entre otras irreversibilidades.

**Cuasiestático no garantiza reversible.** Un pistón que se mueve lentamente con rozamiento puede disipar energía. En las adiabáticas ideales de los ejercicios se usan ambas condiciones y se desprecia el rozamiento.

### Leer los cuatro procesos del libro

![[imagenes/termodinamica-libro-cuatro-procesos.png|470]]

*Fuente: cap. 19, figura 19.16; [PDF p. 13, página impresa 658](zotero://open-pdf/library/items/HJSBDNDF?page=13). Todos parten de $a$, pero terminan en estados distintos. Las curvas azules finas son isotermas de referencia.*

Para cantidad fija de gas ideal, compara $pV$ con su valor inicial $p_aV_a$:

| Recorrido mostrado | Cómo leerlo | Temperatura final y balance |
|---|---|---|
| a→2, isocórico | Baja $p$ sin cambiar $V$ | Baja $T$; $W=0$ y el gas cede calor |
| a→3, isobárico | Aumenta $V$ con $p$ fija | Sube $T$; el calor recibido aumenta $U$ y permite hacer trabajo |
| a→4, isotérmico | $p$ disminuye de modo que $pV$ permanece constante | $T_4=T_a$; para gas ideal $\Delta U=0$ y $Q=W>0$ |
| a→1, adiabático reversible | Se expande sin recibir calor; su presión cae más que en una isoterma al comparar el mismo volumen | Baja $T$; $Q=0$ y el trabajo positivo sale de $U$ |

La vertical de esta figura representa **enfriamiento**, pero un proceso isocórico también podría subir por la misma línea al calentarse. Los nombres indican la condición mantenida, no un sentido único. Usa siempre las flechas. Las expresiones específicas y sus supuestos se desarrollan a continuación.

### Isocórico: puede entrar calor sin haber trabajo

Un recipiente rígido impide $\Delta V$, de modo que no hay trabajo de expansión. La primera ley da

$$
Q=\Delta U=nC_V\Delta T.
$$

Si aumenta $T$, también aumenta $p$ porque $p=nRT/V$ y el volumen no cambia. En un diagrama $p$–$V$ aparece como línea vertical, con área de trabajo nula. Esto supone que no hay otro trabajo, como una paleta que agite el gas: volumen fijo elimina el trabajo de expansión, no cualquier mecanismo de trabajo.

### Isobárico: parte del calor se convierte en trabajo

Si la presión permanece constante en una trayectoria de equilibrio:

$$
W=p(V_f-V_i),\qquad
\Delta U=nC_V\Delta T,\qquad
Q=\Delta U+W=nC_P\Delta T.
$$

Durante una expansión isobárica del gas ideal aumentan $V$ y $T$, el gas realiza trabajo y su energía interna aumenta. $Q$ supera a $W$ porque también cubre ese aumento de $U$. Si el problema da $Q$, $p$ y los dos volúmenes, primero calcula $W$ y después $\Delta U=Q-W$; no necesita dar $n$ para ese balance. Es el procedimiento de T27.

### Isotérmico: temperatura constante no significa calor nulo

En un gas ideal, $T$ constante implica $\Delta U=0$. Si se expande realizando trabajo, necesita absorber la misma energía como calor para que su energía interna no disminuya:

$$
Q=W.
$$

Para calcular ese trabajo en una expansión isotérmica reversible, se sustituye $p=nRT/V$ en el área bajo la curva:

$$
W=nRT\int_{V_i}^{V_f}\frac{dV}{V}
=nRT\ln\!\left(\frac{V_f}{V_i}\right).
$$

El logaritmo natural $\ln$ aparece al sumar cambios proporcionales a $dV/V$. Su argumento $V_f/V_i$ no tiene unidad. Es positivo en expansión, negativo en compresión y cero si los volúmenes coinciden. No se usa una única presión en $p\Delta V$ porque aquí la presión cambia. En un gas real, temperatura constante no garantiza energía interna constante; esa conclusión usa el modelo ideal.

### Adiabático: la temperatura cambia por trabajo

$Q=0$ puede aproximarse con una pared bien aislante o cuando el proceso dura tan poco que el intercambio de calor es despreciable. Si el gas entrega trabajo, esa energía sale de $U$:

$$
\Delta U=-W.
$$

Para un gas ideal que se expande contra el entorno realizando $W>0$, $\Delta U<0$ y $T_f<T_i$. Una compresión con trabajo recibido hace lo contrario. El calificativo adiabático **no exige temperatura constante**. Tampoco basta que aumente el volumen para asegurar que se enfríe: en expansión libre de gas ideal aislado, $W=0$, por lo que $\Delta U=0$.

Las relaciones de potencias añaden condiciones: gas ideal, cantidad fija, proceso adiabático reversible y capacidades caloríficas aproximadamente constantes. Con esas condiciones:

$$
p_iV_i^\gamma=p_fV_f^\gamma,
\qquad
T_iV_i^{\gamma-1}=T_fV_f^{\gamma-1}.
$$

Que un proceso sea rápido puede justificar $Q\approx0$, pero **no demuestra que sea reversible ni que cumpla esas potencias**. Una pared aislante permite realizar el modelo adiabático lentamente sin recibir calor: “adiabático” y “lento” son compatibles.

### De dónde salen las potencias de la adiabática

La primera ley para un pequeño cambio adiabático reversible combina energía interna y trabajo:

$$
nC_V\,dT=-p\,dV.
$$

Sustituir $p=nRT/V$ y dividir por $nC_VT$ da

$$
\frac{dT}{T}=-\frac{R}{C_V}\frac{dV}{V}
=-(\gamma-1)\frac{dV}{V}.
$$

Al sumar esos cambios entre estados, con $C_V$ constante, se obtienen logaritmos:

$$
\ln\!\left(\frac{T_f}{T_i}\right)
=-(\gamma-1)\ln\!\left(\frac{V_f}{V_i}\right).
$$

El mismo resultado, escrito sin logaritmos, es

$$
\frac{T_f}{T_i}=\left(\frac{V_i}{V_f}\right)^{\gamma-1}.
$$

Al sustituir $T=pV/(nR)$ se obtiene $p_iV_i^\gamma=p_fV_f^\gamma$. La relación no es una nueva ley independiente: surge de **primera ley más gas ideal más condiciones del proceso**.

Para resolver T16, despeja antes de sustituir:

$$
p_f=p_i\left(\frac{V_i}{V_f}\right)^\gamma,
\qquad
T_f=T_i\left(\frac{V_i}{V_f}\right)^{\gamma-1}.
$$

Las razones de volúmenes son adimensionales; pueden usar L o $\mathrm{m^3}$ si numerador y denominador tienen la misma unidad. Si $V_f>V_i$ y $\gamma>1$, ambas razones finales son menores que 1: presión y temperatura disminuyen.

El trabajo se obtiene sin integrar otra vez:

$$
W=-\Delta U=nC_V(T_i-T_f)
=\frac{nR(T_i-T_f)}{\gamma-1}
=\frac{p_iV_i-p_fV_f}{\gamma-1}.
$$

El último paso usa $nRT=pV$ en cada estado. **Aquí sí convierte a Pa y $\mathrm{m^3}$ para obtener joules.** Si solo se sabe que el proceso es adiabático, el balance $W=-\Delta U$ sigue siendo válido; las potencias para hallar $p_f$ y $T_f$ necesitan las condiciones adicionales explicadas arriba.

### Interpretar una recta inclinada en un diagrama p–V

Una línea horizontal es isobárica y una vertical, isocórica. Una recta inclinada significa que la presión cambia linealmente con el volumen. No es una isoterma de gas ideal: una isoterma cumple $pV=\mathrm{constante}$ y tiene forma de hipérbola.

Para el tramo recto, el área del trapecio usa presión media y cambio de volumen:

$$
W=\frac{p_i+p_f}{2}(V_f-V_i).
$$

La fórmula conserva el signo de expansión o compresión. Para comparar temperaturas se usa $T\propto pV$ en los estados, pero si se necesita la máxima temperatura dentro de un tramo inclinado también se comprueba cómo varía $p(V)V$ en el interior: no siempre alcanza con mirar los extremos.

En T28, lee primero las unidades de los ejes y las flechas. Recuerda $1\,\mathrm{kPa\,m^3}=1000\,\mathrm J$, $1\,\mathrm{kPa\,L}=1\,\mathrm J$ y $1\,\mathrm{m^3}=1000\,\mathrm L$. Una variación es $V_f-V_i$; no es el volumen de uno de los estados.

### Cerrar un ciclo: qué vuelve a cero

Un **ciclo** devuelve el sistema a su estado inicial. Todas sus funciones de estado recuperan su valor inicial, por lo que $\Delta U_{\mathrm{ciclo}}=0$. Eso no obliga a que el calor y el trabajo de cada tramo sean cero:

$$
Q_{\mathrm{neto}}=\sum_jQ_j
=\sum_jW_j=W_{\mathrm{neto}}.
$$

En el diagrama, el área encerrada con signo representa $W_{\mathrm{neto}}$. En sentido horario, el gas se expande a presiones mayores que aquellas a las que se comprime y entrega trabajo neto; en sentido antihorario recibe trabajo neto. Para un triángulo se usa base por altura dividido por dos; para un rectángulo, base por altura. La geometría da $W_{\mathrm{neto}}$, **no todo el calor absorbido**.

![[imagenes/termodinamica-diagramas-pv.svg]]

*Esquemas del vault basados en los ciclos del TP2, ejercicios 12–13. Sigue las flechas y compara el área de expansión con la de compresión.*

Para calcular la eficiencia de un ciclo, construye una fila por tramo con estados, $\Delta U$, $W$ y $Q=\Delta U+W$. Después suma por separado:

$$
Q_H=\sum_{Q_j>0}Q_j,
\qquad
|Q_C|=-\sum_{Q_j<0}Q_j,
\qquad
Q_{\mathrm{neto}}=Q_H-|Q_C|.
$$

$Q_H$ cuenta el calor que entra; $Q_{\mathrm{neto}}$ ya resta el calor que sale. Reemplazar $Q_H$ por $Q_{\mathrm{neto}}$ al calcular $W_{\mathrm{neto}}/Q_H$ daría falsamente eficiencia 1 para cualquier motor. Si el signo de $Q$ cambia dentro de un tramo, se divide también allí antes de sumar entradas y salidas.

> [!tip] Pausa y aplicación
> Contrasta tu explicación de adiabático, reversible y ciclo en [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Gases, procesos y lectura de gráficos|gases y gráficos]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Decisiones que aparecen en la práctica ampliada|las decisiones de los modelos]]. Resuelve T28 → T16; luego T17/T18 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|gases y primera ley]].

## 8. Motores y refrigeradores: objetivos y rendimientos

### Focos térmicos y sustancia de trabajo

Una **fuente o foco térmico** es un cuerpo suficientemente grande para intercambiar energía sin variar apreciablemente su temperatura. No es que no cambie su energía: su capacidad térmica es tan grande frente al intercambio considerado que se trata $T$ como constante.

La **sustancia de trabajo**, por ejemplo un gas, recorre un ciclo y vuelve a su estado inicial. Los focos y la carga mecánica sí reciben cambios netos: el ciclo describe la sustancia, no el regreso de todo el universo al comienzo.

### Motor térmico: balance y eficiencia

El motor absorbe $Q_H>0$ del foco caliente, entrega trabajo neto $W_{\mathrm{salida}}>0$ y cede calor al foco frío. Con signos respecto del motor, ese último calor es $Q_C<0$. Es cómodo escribir su magnitud positiva $|Q_C|$:

$$
0=\Delta U_{\mathrm{ciclo}}
=Q_H-|Q_C|-W_{\mathrm{salida}}.
$$

Al despejar:

$$
Q_H=W_{\mathrm{salida}}+|Q_C|.
$$

La **eficiencia** compara el trabajo útil con el calor suministrado al motor:

$$
e=\frac{W_{\mathrm{salida}}}{Q_H}
=1-\frac{|Q_C|}{Q_H}.
$$

Es una razón sin unidad. $e=0.28$ significa que el $28\%$ del calor de entrada se obtiene como trabajo neto y el resto se rechaza. Para calcular, $28\%=0.28$, no 28. En los ejercicios, el $W$ del motor se entiende como **trabajo neto por ciclo**, salvo que se indique otro intervalo.

El balance usa primera ley. La exigencia de que un motor cíclico entre dos focos rechace parte del calor es una restricción adicional de la segunda ley; no se deduce solo de conservar energía.

### Leer el flujo de energía del motor en el libro

![[imagenes/termodinamica-libro-flujo-motor.png|340]]

*Fuente: cap. 20, figura 20.3; [PDF p. 4, página impresa 676](zotero://open-pdf/library/items/S254CFZT?page=4). $H$ alude al foco caliente y $C$, al frío; no indican capacidad calorífica.*

Sigue el flujo desde arriba: entra $Q_H$, una parte sale hacia la carga como trabajo $W$ y otra llega al foco frío como $|Q_C|$. El círculo representa que la sustancia de trabajo recorre un ciclo, no que acumule el calor que entra. El dibujo usa la anchura de los conductos para sugerir cuánto se reparte; para calcular se usan los datos del enunciado.

La expresión $W=Q_H+Q_C$ de la imagen es compatible con $W=Q_H-|Q_C|$: en la primera, $Q_C$ es negativo porque sale del motor; en la segunda, las barras lo convierten en una magnitud positiva que se resta. Si el problema da energía por ciclo, todas las flechas se contabilizan en J por ese ciclo; si da tasas, todas se expresan en J/s. Así se evita mezclar calor por ciclo con potencia en T20/T32.

### Potencia y duración de un ciclo

La potencia media es energía por unidad de tiempo:

$$
P_{\mathrm{salida}}=\frac{W_{\mathrm{ciclo}}}{\tau},
\qquad
\tau=\frac{W_{\mathrm{ciclo}}}{P_{\mathrm{salida}}}.
$$

$\tau$ es la duración del ciclo, en s. $\mathrm{J/(J/s)}=\mathrm s$. Usamos $\tau$ para no confundir tiempo con la temperatura $T$. Si se conocen $P$ y $e$ pero no una energía por ciclo, no puede deducirse la duración de cada ciclo: sí pueden hallarse las tasas de calor.

Dividir **todo el balance por el mismo intervalo** da

$$
\dot Q_H=P_{\mathrm{salida}}+|\dot Q_C|,
\qquad
e=\frac{P_{\mathrm{salida}}}{\dot Q_H}.
$$

El punto indica transferencia por unidad de tiempo, o su promedio durante la operación periódica. Despejando:

$$
\dot Q_H=\frac{P_{\mathrm{salida}}}{e},
\qquad
|\dot Q_C|=\dot Q_H-P_{\mathrm{salida}}.
$$

Las tres magnitudes se expresan en W o kW, aunque una sea potencia mecánica y las otras térmicas. Para tasas constantes, $Q_H=\dot Q_H\Delta t$ y $W=P\Delta t$. Una tasa en kW multiplicada por segundos da kJ. T20 practica el tiempo por ciclo y T32 las tasas y energías de un intervalo.

### Consumo de combustible: distinguir energía liberada y trabajo útil

El **poder calorífico** $q_{\mathrm{comb}}$ indica energía liberada por kilogramo de combustible, en J/kg. No es calor por segundo ni eficiencia. Bajo el supuesto del modelo de que toda la energía liberada llega al motor como calor:

$$
Q_H=m_{\mathrm{comb}}q_{\mathrm{comb}}.
$$

Como $W=eQ_H$, el despeje se hace en dos pasos:

$$
Q_H=\frac{W}{e},
\qquad
m_{\mathrm{comb}}=\frac{Q_H}{q_{\mathrm{comb}}}
=\frac{W}{e\,q_{\mathrm{comb}}}.
$$

Dividir solo $W/q_{\mathrm{comb}}$ supondría conversión completa a trabajo y omitiría el calor rechazado. Si solo llega al motor una fracción $\eta_{\mathrm{aporte}}$ de la energía liberada, $Q_H=\eta_{\mathrm{aporte}}m q_{\mathrm{comb}}$; esa fracción es distinta de la eficiencia térmica $e$. T30 usa explícitamente aporte completo. El combustible calculado por ciclo no se transforma en consumo por segundo sin conocer el tiempo o la cantidad de ciclos por segundo.

### Refrigerador y bomba de calor: por qué cambia el cociente

Un refrigerador extrae calor de un foco frío y lo entrega a uno más caliente gracias a trabajo de entrada. Escribimos las tres **magnitudes positivas**:

$$
|Q_H|=|Q_C|+W_{\mathrm{entrada}}.
$$

Esto respeta $\Delta U=Q-W$: para la sustancia del refrigerador, $Q=|Q_C|-|Q_H|$ y el trabajo realizado por ella es $W=-W_{\mathrm{entrada}}$. No se cambió la primera ley; se nombró positivamente el trabajo que consume el dispositivo.

El **coeficiente de desempeño** compara el resultado buscado con el trabajo pagado:

$$
COP_R=\frac{|Q_C|}{W_{\mathrm{entrada}}}
\quad\text{(refrigerador)},
\qquad
COP_{BC}=\frac{|Q_H|}{W_{\mathrm{entrada}}}
\quad\text{(bomba de calor)}.
$$

El refrigerador busca enfriar; la bomba busca calentar. Del balance resulta $COP_{BC}=COP_R+1$. Un $COP_R=3$ significa extraer $3\,\mathrm J$ del foco frío por cada joule de trabajo consumido, entregando $4\,\mathrm J$ al caliente. Puede ser mayor que 1 porque el equipo **transporta** calor además de recibir trabajo; no genera energía.

![[imagenes/termodinamica-maquina-y-refrigerador.svg]]

*Esquema del vault. En el motor sale trabajo; en el refrigerador entra. Los calores indicados con barras son magnitudes positivas.*

### Leer el refrigerador del libro

![[imagenes/termodinamica-libro-refrigerador-componentes.png|780]]

*Fuente: cap. 20, figura 20.9; [PDF p. 9, página impresa 681](zotero://open-pdf/library/items/S254CFZT?page=9). El panel a muestra el circuito y el b ubica sus componentes. Es un refrigerador por compresión de vapor, no el ciclo ideal de Carnot.*

La **sustancia de trabajo** es el refrigerante que circula por las tuberías. No se confunde con los alimentos o el aire interior que se quieren enfriar. Recorre el circuito siguiendo las flechas:

1. **Evaporador, dentro:** el refrigerante absorbe energía del recinto frío mientras se evapora. Ese es el calor útil extraído, $|Q_C|$.
2. **Compresor:** recibe trabajo del motor eléctrico y eleva la presión del refrigerante. En el balance del equipo se cuenta $W_{\mathrm{entrada}}$.
3. **Condensador, fuera:** el refrigerante cede energía al ambiente mientras se condensa. Sale $|Q_H|=|Q_C|+W_{\mathrm{entrada}}$, una cantidad mayor que la extraída del interior.
4. **Válvula de expansión:** reduce la presión y permite volver a las condiciones de entrada del evaporador. Después se repite la circulación.

Los cambios de fase permiten transportar energía sin exigir una gran variación de temperatura durante cada intercambio. Para los ejercicios de COP no hace falta calcular cada estado del refrigerante: basta identificar qué calor es el resultado útil y qué trabajo se paga. El esquema real tampoco autoriza a aplicar automáticamente la fórmula del COP de Carnot.

En T23 primero se calcula la energía que hay que extraer para enfriar agua, congelarla y enfriar el hielo. Esos tres aportes forman $|Q_C|$. Después se divide por el tiempo para hallar $|\dot Q_C|$ y por $COP_R$ para hallar la potencia de entrada. No se confunde potencia de enfriamiento con consumo mecánico. Comprueba esta lectura en [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Lectura de figuras de las fuentes|la pregunta sobre el calor que recibe la cocina]].

### Carnot: qué idealiza y qué permite concluir

La máquina de **Carnot** es un modelo reversible que opera entre dos focos a temperaturas constantes $T_H>T_C$. Su ciclo tiene dos intercambios isotérmicos de calor, uno con cada foco, unidos por dos procesos adiabáticos reversibles. Así se evita transferir calor a través de diferencias finitas de temperatura y se obtiene la eficiencia máxima entre esos focos.

Para ese ciclo reversible se cumple la relación de calores y temperaturas

$$
\frac{|Q_C|}{Q_H}=\frac{T_C}{T_H}.
$$

Al sustituirla en $e=1-|Q_C|/Q_H$ se obtiene

$$
e_C=1-\frac{T_C}{T_H}.
$$

La relación de calores puede deducirse usando las isotermas y las adiabáticas del ciclo; en la sección 9 también se obtiene mediante el balance de entropía. No es válido imponerla a cualquier máquina real solo por conocer sus dos focos.

Para un motor cíclico que solo intercambia calor con esos dos focos:

$$
e\le e_C,
\qquad
W\le W_{\max}=e_CQ_H.
$$

La igualdad corresponde al límite reversible; las irreversibilidades reducen el rendimiento. En estos cocientes se usan K. Una diferencia Celsius equivale numéricamente a una diferencia kelvin, pero **el denominador $T_H$ sigue siendo una temperatura absoluta**.

Si se conocen $W$ y $Q_H$, primero se obtiene la eficiencia real $e=W/Q_H$; las temperaturas sirven para calcular el límite con el que se la compara. Una propuesta puede conservar energía y tener $e<1$, pero ser imposible porque supera $e_C$. T31 requiere ambas comprobaciones. T30 sí dice Carnot: allí se puede usar $e=e_C$ para calcular sus energías y el combustible.

En T17/T18 se compara la eficiencia del ciclo con Carnot entre $T_{\min}$ y $T_{\max}$. Es una referencia superior ideal para ese intervalo térmico; **no convierte el ciclo dado en un ciclo de Carnot** ni sustituye la suma de sus calores por tramo.

### Leer el ciclo de Carnot del libro

![[imagenes/termodinamica-libro-ciclo-carnot.png|800]]

*Fuente: cap. 20, figura 20.13; [PDF p. 13, página impresa 685](zotero://open-pdf/library/items/S254CFZT?page=13). El gráfico central sigue los mismos estados que los cuatro pistones de alrededor.*

El eje horizontal es volumen, no tiempo: hacia la derecha hay expansión y hacia la izquierda, compresión. Sigue $a\to b\to c\to d\to a$:

- **a→b, isoterma caliente:** entra $Q_H>0$ mientras el gas hace trabajo. Para gas ideal, $\Delta U=0$ porque no cambia $T$.
- **b→c, adiabática reversible:** no entra calor; el gas sigue expandiéndose y su temperatura baja de $T_H$ a $T_C$ al entregar energía como trabajo.
- **c→d, isoterma fría:** el entorno comprime el gas y este rechaza calor. $W<0$, $Q_C<0$ y $\Delta U=0$.
- **d→a, adiabática reversible:** el trabajo recibido eleva su temperatura de $T_C$ a $T_H$ sin intercambio de calor.

Las ramas rojas son los tramos isotérmicos del ciclo; las azules gruesas son sus adiabáticas. Las otras curvas azules finas solo ayudan a comparar temperaturas. El área rosa **encerrada** da el trabajo neto del ciclo. No representa por sí sola todo $Q_H$: el motor también realiza y recibe trabajo durante los otros tramos.

### Ejemplo del libro: trabajo y calor de una máquina de Carnot

El ejemplo 20.2 del [cap. 20, PDF pp. 14–15](zotero://open-pdf/library/items/S254CFZT?page=14) da $Q_H=2000\,\mathrm J$, $T_H=500\,\mathrm K$ y $T_C=350\,\mathrm K$. La siguiente resolución conserva esos datos y explicita el procedimiento.

1. **Elegir el modelo:** dice Carnot; por eso se puede igualar la eficiencia a su límite reversible. Las temperaturas ya están en kelvin:

$$
e_C=1-\frac{T_C}{T_H}
=1-\frac{350}{500}=0.30=30\%.
$$

2. **Obtener el trabajo:** de $e=W/Q_H$, multiplica por $Q_H$:

$$
W=e_CQ_H=0.30(2000\,\mathrm J)=600\,\mathrm J.
$$

3. **Cerrar el balance:** de $Q_H=W+|Q_C|$, resta el trabajo:

$$
|Q_C|=Q_H-W=2000\,\mathrm J-600\,\mathrm J=1400\,\mathrm J.
$$

4. **Interpretar y controlar:** por ciclo entran 2000 J, salen 600 J de trabajo y se entregan 1400 J al foco frío. Con signo respecto del motor, $Q_C=-1400\,\mathrm J$; $\Delta U=2000-1400-600=0$. Si solo dijera “motor real entre esos focos”, los 600 J serían un **máximo**, no necesariamente su trabajo efectivo. Aplica esta distinción a T30/T31.

### Refrigerador reversible entre dos focos

El ciclo reversible invertido obedece la misma razón de calores. Como $W_{\mathrm{entrada}}=|Q_H|-|Q_C|$:

$$
COP_{R,C}=\frac{|Q_C|}{|Q_H|-|Q_C|}
=\frac{T_C}{T_H-T_C}.
$$

Es el desempeño máximo de refrigeración entre esos focos, en K. Al aumentar la separación térmica, aumenta el esfuerzo necesario por unidad de calor extraído y disminuye el COP ideal. El COP real puede darse como dato sin que el equipo sea reversible.

### Ciclo Otto: modelo, razón de compresión y origen de su eficiencia

El **Otto ideal** aproxima un motor de encendido por chispa. En el modelo de aire estándar, una cantidad fija de gas ideal se comprime adiabática y reversiblemente (1→2), recibe calor a volumen constante (2→3), se expande adiabática y reversiblemente (3→4) y rechaza calor a volumen constante (4→1). La combustión y el escape reales se reemplazan por esos intercambios de calor; se usan capacidades constantes y se omiten pérdidas.

La razón de compresión es

$$
r=\frac{V_{\max}}{V_{\min}}>1.
$$

No es la razón de presiones. Durante los dos intercambios isocóricos:

$$
Q_H=nC_V(T_3-T_2),
\qquad
|Q_C|=nC_V(T_4-T_1).
$$

Las adiabáticas dan $T_2/T_1=T_3/T_4=r^{\gamma-1}$. Por lo tanto, $T_3-T_2=r^{\gamma-1}(T_4-T_1)$, y al dividir los dos calores se obtiene

$$
e_{\mathrm{Otto}}=1-\frac{|Q_C|}{Q_H}
=1-\frac{1}{r^{\gamma-1}}.
$$

La fórmula procede de **ese ciclo particular**. No corresponde a cualquier motor, ni a Carnot ni a un diésel solo por ser motor térmico. En T19, el balance se resuelve con las energías suministradas; en T21, el enunciado sí especifica Otto ideal y permite usar esta relación.

> [!tip] Pausa y aplicación
> Reexplica qué va en el numerador de eficiencia/COP y cuándo Carnot es una igualdad o un límite. Contrasta [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Máquinas, límites y entropía|máquinas y límites]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|las preguntas de potencia, combustible y Carnot]]. Resuelve T19 → T20/T32 → T30/T31; después completa T21–T24 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|máquinas térmicas]].

## 9. Segunda ley y entropía

### Conservar energía no determina la dirección

La primera ley admite un balance donde un cuerpo frío cede energía a uno caliente, pero ese intercambio no sucede por sí solo. La **segunda ley** añade una dirección a los procesos: el calor no pasa espontáneamente del frío al caliente sin otros efectos, y un motor cíclico no puede tener como único resultado convertir en trabajo todo el calor tomado de un solo foco.

Un refrigerador puede enviar calor del frío al caliente porque consume trabajo y produce efectos en el entorno. Un gas puede convertir calor enteramente en trabajo durante una expansión isotérmica ideal, pero ese proceso aislado **no es un ciclo**: el gas termina en otro volumen. Para devolverlo al comienzo hay que contar el resto del recorrido.

### Qué es la entropía y qué mide su cambio

La **entropía** $S$ es una función de estado, medida en J/K. Sirve para contabilizar la transferencia de energía por calor en relación con la temperatura y para distinguir cambios reversibles e irreversibles. La asociación microscópica con la cantidad de configuraciones posibles da intuición; llamarla simplemente “desorden” no alcanza para calcularla ni decidir su signo.

Para un pequeño intercambio en un camino reversible:

$$
dS=\frac{\delta Q_{\mathrm{rev}}}{T},
\qquad
\Delta S=\int_i^f\frac{\delta Q_{\mathrm{rev}}}{T}.
$$

$T$ es la temperatura absoluta a la que se intercambia ese calor en el camino reversible. El símbolo $\delta Q$ recuerda que es energía transferida durante el proceso, mientras que $dS$ corresponde al cambio de una propiedad de estado.

**El camino de cálculo puede ser imaginario.** Aunque el proceso real sea irreversible, se elige una sucesión reversible entre los mismos estados inicial y final. Como $S$ depende del estado, el resultado para $\Delta S$ es el mismo. No se reemplaza sin más el numerador por el calor real dividido por una temperatura arbitraria.

### Fusión a temperatura constante

Si una masa $m$ se funde a la temperatura de equilibrio $T_m$, el camino reversible recibe $Q_{\mathrm{rev}}=mL_f$ a esa temperatura constante:

$$
\Delta S_{\mathrm{sustancia}}=\frac{mL_f}{T_m}>0.
$$

Al solidificar entre los mismos estados, cambia el signo. Si el calor proviene de un foco grande a $T_{\mathrm{foco}}>T_m$, el foco entrega esa misma energía y su cambio es

$$
\Delta S_{\mathrm{foco}}=-\frac{mL_f}{T_{\mathrm{foco}}}.
$$

Al sumar:

$$
\Delta S_{\mathrm{total}}=mL_f
\left(\frac{1}{T_m}-\frac{1}{T_{\mathrm{foco}}}\right)>0.
$$

La transferencia real tiene una diferencia finita de temperaturas y es irreversible. Para la sustancia se usa su temperatura de fusión; para el foco se usa la del foco. T25 termina cuando se funde el hielo: no se añade un calentamiento posterior del agua que el enunciado no pide.

### Calentamiento o enfriamiento sin cambio de fase

Para una masa con $c$ constante, imaginamos aportes reversibles pequeños $\delta Q_{\mathrm{rev}}=mc\,dT$. Entonces:

$$
\Delta S=mc\int_{T_i}^{T_f}\frac{dT}{T}
=mc\ln\!\left(\frac{T_f}{T_i}\right).
$$

El logaritmo se debe a que la misma energía por grado se intercambia a temperaturas que van cambiando. No puede sacarse una única $T$ del denominador. Si el cuerpo se calienta, $T_f/T_i>1$ y $\Delta S>0$; si se enfría, el logaritmo y el cambio son negativos. Las temperaturas deben ir en K y la razón no tiene unidad.

Para el gas ideal, esta forma usa la capacidad correspondiente al camino reversible elegido: en uno isocórico sería $nC_V\ln(T_f/T_i)$. No se adopta el $c$ de agua para cualquier sustancia ni se omiten efectos de volumen en un cambio general de gas. Los ejercicios T25/T26 se centran en fases y en sólidos/líquidos con trabajo despreciable.

### El entorno puede conservar su temperatura y cambiar su entropía

En T26 el agua pierde energía y baja su temperatura: se usa el logaritmo para su $\Delta S$. El aire de la cocina se modela como un **foco** que permanece a $T_{\mathrm{aire}}$ y recibe toda esa energía:

$$
Q_{\mathrm{aire}}=-Q_{\mathrm{agua}}>0,
\qquad
\Delta S_{\mathrm{aire}}=\frac{Q_{\mathrm{aire}}}{T_{\mathrm{aire}}}.
$$

No se usa el logaritmo con las temperaturas inicial y final del agua para el aire: son dos sistemas con comportamientos distintos. Que el foco no varíe apreciablemente su temperatura no implica que no reciba energía ni entropía.

### Qué exige la segunda ley al sumar

Si incluimos el sistema y todas las partes del entorno que intercambian energía con él, el conjunto se trata como aislado:

$$
\Delta S_{\mathrm{total}}=
\Delta S_{\mathrm{sistema}}+\Delta S_{\mathrm{entorno}}\ge0.
$$

En el límite reversible el total es cero; en un proceso irreversible es positivo. **Una parte sí puede perder entropía.** Enfriar agua disminuye su entropía, pero el entorno aumenta la suya en una cantidad suficiente. No se aplica la desigualdad a una parte dejando fuera los intercambios que ocurren a través de su frontera.

Un proceso adiabático reversible tiene $\Delta S=0$. Uno adiabático irreversible puede generar entropía aunque $Q=0$; por ejemplo, la expansión libre de un gas ideal aislado. “Sin calor” y “sin cambio de entropía” solo coinciden al añadir reversibilidad.

### Leer la expansión libre del libro: el camino de cálculo

![[imagenes/termodinamica-libro-expansion-libre-entropia.png|690]]

*Fuente: cap. 20, figura 20.19 y ejemplo 20.8; [PDF pp. 21–22, páginas impresas 693–694](zotero://open-pdf/library/items/S254CFZT?page=21). Los paneles a y b muestran el cambio real; el c presenta un camino reversible de cálculo.*

En **a**, un gas ideal ocupa $V$ y el otro compartimiento está vacío. Al romper la membrana ocupa **b**, con volumen $2V$. Las paredes externas son rígidas y aislantes: no entra calor y el gas no mueve una carga exterior. Así, $Q_{\mathrm{real}}=0$, $W_{\mathrm{real}}=0$ y $\Delta U=0$. Para ese gas ideal, también $T_f=T_i$; al duplicar el volumen, la presión de equilibrio final es la mitad.

La expansión es brusca y no recorre estados de equilibrio intermedios. Por eso **la curva de c no describe su trabajo real**. Se imagina otro experimento: el mismo gas se expande lentamente, contra un pistón, en contacto con un foco que mantiene $T$ constante. Ese camino reversible une los mismos estados, pero sí recibe calor y entrega trabajo:

$$
Q_{\mathrm{rev}}=W_{\mathrm{rev}}=nRT\ln\!\left(\frac{2V}{V}\right)
=nRT\ln2.
$$

Como la entropía depende solo de los estados, el camino imaginado permite hallar también el cambio del proceso real:

$$
\Delta S=\frac{Q_{\mathrm{rev}}}{T}=nR\ln2>0.
$$

Para $n=1.00\,\mathrm{mol}$, como calcula el libro, $\Delta S=(1.00)(8.314)\ln2=5.76\,\mathrm{J/K}$. No se ha creado energía: el cambio de energía interna sigue siendo cero. Se produjo un cambio irreversible con aumento de entropía. La cantidad de calor del camino auxiliar no se incorpora al balance del experimento real.

> [!note] Alcance de este ejemplo visual
> Aclara por qué “adiabático” no basta para afirmar $\Delta S=0$. Los ejercicios T25/T26 se concentran en fases y cambios de temperatura; no necesitan esta fórmula de expansión libre. Contrasta la diferencia entre ambos caminos en [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Lectura de figuras de las fuentes|la autoevaluación visual]] y vuelve a su fórmula específica al practicar.

### El vínculo con el límite de Carnot

Para un motor cíclico entre dos focos, la sustancia de trabajo regresa al mismo estado y su cambio de entropía es cero. El foco caliente pierde $Q_H$ y el frío recibe $|Q_C|$:

$$
\Delta S_{\mathrm{total}}
=-\frac{Q_H}{T_H}+\frac{|Q_C|}{T_C}\ge0.
$$

Despejando, $|Q_C|/Q_H\ge T_C/T_H$. Al restar de 1:

$$
e=1-\frac{|Q_C|}{Q_H}\le1-\frac{T_C}{T_H}=e_C.
$$

La igualdad corresponde a entropía total nula, es decir, al modelo reversible. Así se conectan las dos comprobaciones de T31: conservar energía y respetar la dirección y los límites que impone la segunda ley.

> [!tip] Pausa y aplicación
> Contrasta [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Máquinas, límites y entropía|entropía del cuerpo y del entorno]] y [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Fórmulas|la elección de la fórmula de entropía]]. Resuelve T25 → T26 en [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Segunda ley y máquinas térmicas|máquinas y entropía]]. Termina con [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Repaso del módulo|el repaso del módulo]] y vuelve al bloque que explique cualquier decisión que aún no puedas justificar.

## Cómo redactar el planteo al pasar a la práctica

Antes de sustituir valores, escribe unas líneas que hagan visible la decisión física:

1. **Sistema:** qué cuerpos o qué gas incluyes.
2. **Condiciones:** si hay aislamiento, recipiente rígido, gas ideal, cambio de fase o proceso reversible, y qué consecuencia concreta tiene cada dato.
3. **Principio:** conservación de energía, ecuación de estado o segunda ley; después la relación particular que corresponde.
4. **Cálculo:** signos, conversiones, despeje simbólico y sustitución con unidades.
5. **Control:** compatibilidad de temperatura y fase, sentido del trabajo, cierre del ciclo o límite de Carnot.

Por ejemplo: “Tomo como sistema agua y vaso. Supongo intercambio con la habitación y trabajo despreciables. Por conservación de energía, $Q_{\mathrm{agua}}+Q_{\mathrm{vaso}}=0$. Como ninguno cambia de fase, expreso cada término como $mc(T_f-T_i)$”. Ese planteo explica **por qué** corresponde la cuenta; después se despeja y calcula. Las [[Unidades/05 - Termodinámica/Resoluciones/05 - Resoluciones de termodinámica|resoluciones del módulo]] desarrollan el procedimiento para cada ejercicio.

## Fuentes consultadas

- [[Recursos de estudio/Fuentes y cobertura/Fuentes Zotero y probabilidad#Termodinámica: fuentes consultadas para el módulo|Registro de fuentes, modelos y alcance]]. Las ampliaciones explicativas se redactaron para el vault. Los ejemplos 20.2 y 20.8 conservan datos y resultados del libro con resolución reexplicada; el cálculo de alargamiento que acompaña a la figura 17.8 usa datos didácticos añadidos.
- [Capítulo 17: Temperatura y calor](zotero://select/library/items/4NVQU8DQ): equilibrio y escalas (PDF pp. 1–6), expansión (pp. 7–9), calor específico y fases (pp. 14–20), conducción (pp. 23–26), radiación (pp. 27–28).
- [Capítulo 18: Propiedades térmicas de la materia](zotero://select/library/items/D9BACN8A): ecuación de estado y modelo de gas ideal, en particular PDF p. 2. Las ecuaciones de estado se distinguen de las condiciones de la trayectoria.
- [Capítulo 19: La primera ley](zotero://select/library/items/HJSBDNDF): sistema, trabajo y energía interna (PDF pp. 1–9), procesos y capacidades del gas (pp. 11–16), adiabática y su deducción (pp. 17–18).
- [Capítulo 20: La segunda ley](zotero://select/library/items/S254CFZT): motores, refrigeradores y Otto (PDF pp. 3–10), segunda ley y Carnot (pp. 11–18), entropía (pp. 19–24).
- [Clase 1 de Termodinámica, 11-08-2025](zotero://select/library/items/57T7VR7L): ilustraciones de arandela (PDF p. 24) y gas con pistón (p. 30). Se recortaron las figuras, sin reproducir las diapositivas completas.
- [TP1: Temperatura y calor](zotero://select/library/items/PX9XMSD9) y [TP2: Máquinas térmicas](zotero://select/library/items/C6CQ6LHB): selección de las situaciones que se interpretan y practican. Los números T1–T35 identifican los ejercicios del vault; sus enunciados citan la procedencia concreta.

Los **14 recortes PNG** —12 del libro y 2 de las diapositivas— complementan los SVG propios. Sus pies indican figura, página PDF y, para el libro, página impresa. Los paneles de la figura 19.7 se reorganizaron conservando su contenido. Las preguntas sobre estas lecturas están en [[Unidades/05 - Termodinámica/Autoevaluación/05 - Termodinámica#Lectura de figuras de las fuentes|autoevaluación de figuras]].
