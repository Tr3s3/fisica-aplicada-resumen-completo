---
tags: [fisica-aplicada, unidad-05, termodinamica, formulas, gases, procesos]
aliases: [Fórmulas de isotérmico isobárico isocórico y adiabático]
---

# Formulario de procesos termodinámicos

**Hoja de consulta sin demostraciones:** condiciones, fórmulas explícitas y signos para resolver procesos **isotérmicos, isobáricos, isocóricos y adiabáticos**.

**Volver:** [[Unidades/05 - Termodinámica/Teoría/05 - Termodinámica|Termodinámica]] · **Práctica:** [[Unidades/05 - Termodinámica/Práctica/05 - Ejercicios de termodinámica#Gases ideales y primera ley|gases y primera ley]].

## 1. Convención, símbolos y unidades

Estas fórmulas corresponden a **un gas ideal, sistema cerrado y cantidad fija de gas**, con capacidades caloríficas constantes y solo trabajo de expansión o compresión. Se desprecian cambios de energía cinética y potencial del conjunto.

| Símbolo | Significado y unidad |
|---|---|
| $i$, $f$ | Estado inicial y final |
| $p$ | Presión **absoluta**, en Pa |
| $V$ | Volumen, en $\mathrm{m^3}$ |
| $T$ | Temperatura **absoluta**, en K |
| $n$ | Cantidad de gas, en mol |
| $Q$ | Calor: **positivo si entra al gas**, negativo si sale; en J |
| $W$ | Trabajo **realizado por el gas**: positivo si entrega trabajo, negativo si recibe trabajo; en J |
| $\Delta U$ | Cambio de energía interna, $U_f-U_i$; en J |
| $C_V$, $C_P$ | Capacidades caloríficas **molares**, en $\mathrm{J/(mol\,K)}$ |
| $\gamma$ | $C_P/C_V$, sin unidades |

$$\boxed{\Delta T=T_f-T_i},\qquad \boxed{\Delta V=V_f-V_i}.$$

**Conversiones:** $T[\mathrm K]=T[{}^\circ\mathrm C]+273.15$; $1\,\mathrm L=10^{-3}\,\mathrm{m^3}$; $1\,\mathrm{kPa}=10^3\,\mathrm{Pa}$; $1\,\mathrm{atm}=101325\,\mathrm{Pa}$.

**Productos de presión y volumen:** $1\,\mathrm{Pa\,m^3}=1\,\mathrm J$; $1\,\mathrm{kPa\,L}=1\,\mathrm J$; $1\,\mathrm{atm\,L}=101.325\,\mathrm J$.

Usa kelvin en la ecuación de estado y en cocientes de temperaturas. Una diferencia $\Delta T$ tiene el mismo valor numérico en K y °C.

> [!important] Signo del trabajo
> Con esta convención, la primera ley es **$\Delta U=Q-W$**. Si te piden el trabajo **sobre el gas**, cambia el signo: $W_{\mathrm{sobre}}=-W$.

## 2. Fórmulas comunes a los cuatro procesos

### Estado del gas

$$\boxed{pV=nRT},\qquad R=8.314\,\mathrm{J/(mol\,K)}.$$

$$\boxed{\frac{p_iV_i}{T_i}=\frac{p_fV_f}{T_f}}.$$

$$p=\frac{nRT}{V},\qquad V=\frac{nRT}{p},\qquad T=\frac{pV}{nR},\qquad n=\frac{pV}{RT}.$$

Si dan masa: $n=m/M$, con masa $m$ y masa molar $M$ en unidades compatibles.

### Primera ley y energía interna

$$\boxed{\Delta U=Q-W},\qquad \boxed{Q=\Delta U+W},\qquad \boxed{W=Q-\Delta U}.$$

$$\boxed{\Delta U=nC_V(T_f-T_i)=\frac{p_fV_f-p_iV_i}{\gamma-1}}.$$

La fórmula de $\Delta U$ corresponde al gas ideal con $C_V$ constante y sirve en **cualquiera de los cuatro procesos**. Para igualar $Q$ a $nC_V\Delta T$ hace falta además $W=0$.

### Capacidades caloríficas

$$\boxed{C_P-C_V=R},\qquad \boxed{\gamma=\frac{C_P}{C_V}}.$$

$$\boxed{C_V=\frac{R}{\gamma-1}},\qquad \boxed{C_P=\frac{\gamma R}{\gamma-1}}.$$

| Gas ideal, si el enunciado adopta este modelo | $C_V$ | $C_P$ | $\gamma$ |
|---|---|---|---|
| Monoatómico | $\frac32R$ | $\frac52R$ | $\frac53\approx1.67$ |
| Diatómico, sin contribución vibracional | $\frac52R$ | $\frac72R$ | $\frac75=1.40$ |

Usa los valores del enunciado cuando estén dados. Si las capacidades son específicas **por masa**, $c_v,c_p$ en $\mathrm{J/(kg\,K)}$, sustituye $nC_V$ por $mc_v$ y $nC_P$ por $mc_p$.

## 3. Tabla para elegir el proceso

| Proceso | Condición principal | Relación entre estados | Trabajo $W$ | Calor $Q$ | Energía interna |
|---|---|---|---|---|---|
| Isotérmico | $T_f=T_i=T$ | $p_iV_i=p_fV_f$ | $nRT\ln(V_f/V_i)$ | $Q=W$ | $\Delta U=0$ |
| Isobárico | $p_f=p_i=p$ | $V_i/T_i=V_f/T_f$ | $p(V_f-V_i)$ | $nC_P(T_f-T_i)$ | $nC_V(T_f-T_i)$ |
| Isocórico | $V_f=V_i=V$ | $p_i/T_i=p_f/T_f$ | $0$ | $Q=\Delta U$ | $nC_V(T_f-T_i)$ |
| Adiabático reversible | $Q=0$ | $p_iV_i^\gamma=p_fV_f^\gamma$ | $(p_iV_i-p_fV_f)/(\gamma-1)$ | $0$ | $\Delta U=-W$ |

**Condiciones de uso:** el trabajo isotérmico de la tabla supone un proceso reversible o mecánicamente cuasiestático sin disipación. El trabajo isobárico supone expansión/compresión cuasiestática a esa presión. Las relaciones de potencias adiabáticas exigen **adiabática reversible**.

## 4. Isotérmico — temperatura constante

**Se mantiene:** $T_f=T_i=T$, por lo que $\Delta T=0$.

**No se mantienen necesariamente:** presión y volumen. Para gas ideal, $\Delta U=0$; el calor puede ser distinto de cero.

### Presión y volumen

$$\boxed{p_iV_i=p_fV_f}.$$

$$\boxed{p_f=p_i\frac{V_i}{V_f}},\qquad \boxed{V_f=V_i\frac{p_i}{p_f}}.$$

### Trabajo y calor — proceso reversible

$$\boxed{W=Q=nRT\ln\!\left(\frac{V_f}{V_i}\right)}.$$

Formas equivalentes útiles según los datos:

$$W=Q=p_iV_i\ln\!\left(\frac{V_f}{V_i}\right)=nRT\ln\!\left(\frac{p_i}{p_f}\right).$$

Si necesitas el volumen final a partir del trabajo:

$$\boxed{V_f=V_i\exp\!\left(\frac{W}{nRT}\right)}.$$

**Signos:** expansión, $V_f>V_i$: $W>0$, $Q>0$, $p_f<p_i$. Compresión: $W<0$, $Q<0$, $p_f>p_i$. En ambos casos $\Delta U=0$ y $T$ constante.

**Dato importante:** $\ln$ es logaritmo natural. En el cociente $V_f/V_i$ puedes usar litros si ambos volúmenes tienen la misma unidad; en el producto $p_iV_i$ debes convertir a unidades que den J.

## 5. Isobárico — presión constante

**Se mantiene:** $p_f=p_i=p$, por lo que $\Delta p=0$.

**Pueden cambiar:** volumen, temperatura, energía interna, calor y trabajo.

### Volumen y temperatura

$$\boxed{\frac{V_i}{T_i}=\frac{V_f}{T_f}}.$$

$$\boxed{T_f=T_i\frac{V_f}{V_i}},\qquad \boxed{V_f=V_i\frac{T_f}{T_i}}.$$

### Trabajo, calor y energía interna

$$\boxed{W=p(V_f-V_i)=nR(T_f-T_i)}.$$

$$\boxed{Q=nC_P(T_f-T_i)},\qquad \boxed{\Delta U=nC_V(T_f-T_i)}.$$

Si dan $\gamma$ y el trabajo, también puedes usar:

$$\boxed{\Delta U=\frac{W}{\gamma-1}},\qquad \boxed{Q=\frac{\gamma}{\gamma-1}W}.$$

Si dan el calor y piden temperatura:

$$\boxed{T_f=T_i+\frac{Q}{nC_P}}.$$

**Signos:** calentamiento: $T_f>T_i$, $V_f>V_i$, $Q>0$, $W>0$, $\Delta U>0$. Enfriamiento: disminuyen $T$ y $V$, y los tres intercambios/cambios son negativos. La presión permanece constante.

## 6. Isocórico o isovolumétrico — volumen constante

**Se mantiene:** $V_f=V_i=V$, por lo que $\Delta V=0$ y **$W=0$** para trabajo de expansión/compresión.

**Pueden cambiar:** presión, temperatura, energía interna y calor.

### Presión y temperatura

$$\boxed{\frac{p_i}{T_i}=\frac{p_f}{T_f}}.$$

$$\boxed{p_f=p_i\frac{T_f}{T_i}},\qquad \boxed{T_f=T_i\frac{p_f}{p_i}}.$$

### Calor y energía interna

$$\boxed{W=0},\qquad \boxed{Q=\Delta U=nC_V(T_f-T_i)}.$$

Si conoces las presiones y el volumen:

$$\boxed{Q=\Delta U=\frac{V(p_f-p_i)}{\gamma-1}}.$$

Si dan el calor y piden temperatura:

$$\boxed{T_f=T_i+\frac{Q}{nC_V}}.$$

**Signos:** calentamiento: $Q>0$, $\Delta U>0$, $T_f>T_i$, $p_f>p_i$. Enfriamiento: $Q<0$, $\Delta U<0$, disminuyen $T$ y $p$. En ambos casos $W=0$ y $V$ constante.

## 7. Adiabático — sin intercambio de calor

**Condición definitoria:** $Q=0$. No exige temperatura constante.

### Energía y trabajo

Para el gas ideal y las condiciones generales de esta hoja:

$$\boxed{\Delta U=-W=nC_V(T_f-T_i)}.$$

$$\boxed{W=nC_V(T_i-T_f)=\frac{nR(T_i-T_f)}{\gamma-1}=\frac{p_iV_i-p_fV_f}{\gamma-1}}.$$

Si conoces el trabajo y piden temperatura:

$$\boxed{T_f=T_i-\frac{W}{nC_V}}.$$

### Relaciones entre estados — solo adiabática reversible

$$\boxed{p_iV_i^\gamma=p_fV_f^\gamma},\qquad \boxed{T_iV_i^{\gamma-1}=T_fV_f^{\gamma-1}}.$$

Para hallar presión o temperatura con los volúmenes:

$$\boxed{p_f=p_i\left(\frac{V_i}{V_f}\right)^\gamma}.$$

$$\boxed{T_f=T_i\left(\frac{V_i}{V_f}\right)^{\gamma-1}}.$$

Para relacionar temperatura y presión:

$$\boxed{T_f=T_i\left(\frac{p_f}{p_i}\right)^{(\gamma-1)/\gamma}}.$$

Para hallar el volumen final:

$$\boxed{V_f=V_i\left(\frac{p_i}{p_f}\right)^{1/\gamma}},\qquad \boxed{V_f=V_i\left(\frac{T_i}{T_f}\right)^{1/(\gamma-1)}}.$$

**Signos en la adiabática reversible:** expansión: $W>0$, $\Delta U<0$, disminuyen $T$ y $p$. Compresión: $W<0$, $\Delta U>0$, aumentan $T$ y $p$. Siempre $Q=0$.

> [!important] Adiabático no significa automáticamente reversible
> Si el enunciado solo dice “sin intercambio de calor”, puedes asegurar $Q=0$ y $\Delta U=-W$. Para usar $pV^\gamma=\mathrm{cte}$ y las otras potencias hace falta reversibilidad. En una **expansión libre al vacío** de gas ideal aislado: $Q=0$, $W=0$, $\Delta U=0$ y $T_f=T_i$; no uses las potencias de la adiabática reversible.

## 8. Qué elegir según lo que te dan

| Lo que necesitas | Fórmula o condición inicial |
|---|---|
| Reconocer el proceso | $T$ constante: isotérmico; $p$ constante: isobárico; $V$ constante: isocórico; $Q=0$: adiabático |
| Hallar una variable de estado | $pV=nRT$ y la relación específica del proceso |
| Hallar $\Delta U$ en cualquier proceso de gas ideal | $nC_V(T_f-T_i)$ o $(p_fV_f-p_iV_i)/(\gamma-1)$ |
| Hallar $Q$ después de calcular $W$ y $\Delta U$ | $Q=\Delta U+W$ |
| Hallar $W$ después de calcular $Q$ y $\Delta U$ | $W=Q-\Delta U$ |
| Elegir entre $C_P$ y $C_V$ | $\Delta U$: siempre $C_V$; calor isobárico: $C_P$; calor isocórico: $C_V$ |
| Resolver un ciclo con varios tramos | Aplica el proceso de cada tramo; suma $Q$ y $W$ con signo; en el ciclo completo $\Delta U_{\mathrm{ciclo}}=0$ y $Q_{\mathrm{neto}}=W_{\mathrm{neto}}$ |

**Referencia del vault:** [[Unidades/05 - Termodinámica/Teoría/05 - Fórmulas aplicadas de termodinámica#7. Procesos de un gas ideal|formulario general de procesos]]. Para practicar una adiabática completa: [[Recursos de estudio/Práctica integradora/Ejercicios/01 - Primer parcial 2026 reconstruido#E2. Expansión adiabática y primera ley|E2 del primer parcial 2026]].
