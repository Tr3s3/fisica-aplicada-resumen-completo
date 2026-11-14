---
tags: [fisica-aplicada, primer-parcial, modelo-2026, termodinamica, optica, practica]
aliases: [Primer parcial 2026 para practicar]
---

# Primer parcial 2026: enunciados reconstruidos

Estos cinco problemas reconstruyen los ejercicios resueltos en **Clave_Correccion_Parcial_Fisica_Aplicada-2026**, de la colección `Modelos parcial / 1er parcial` de Zotero. Conservan su orden y sus preguntas, con los datos y supuestos necesarios para poder resolverlos.

**Corrección explicada:** [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado|resoluciones paso a paso]]. Abre ese archivo después del intento; aquí no se incluyen las respuestas.

> [!info] Alcance de la reconstrucción
> **E1** se reconstruye desde el balance y las energías de la clave: las masas de aluminio y agua son compatibles con esos valores, y se toma hielo inicialmente a cero. **E2–E5** se completan con la transcripción del primer parcial 2026, cuyos datos y preguntas coinciden con la clave. La redacción es didáctica; no pretende reproducir literalmente el examen original.

## Cómo practicar

Resuelve en una hoja aparte. En cada ejercicio escribe: **datos y unidades → sistema o esquema → principio físico y condiciones → ecuación y despeje → cálculo → interpretación y control**. Las pistas están plegadas para que puedas intentar primero el planteo.

La clave declara **100 puntos: 20 por ejercicio**. En E3 contiene una inconsistencia de puntaje que se explica en las resoluciones; para practicar se conservan sus cuatro preguntas sin inventar otra distribución.

## Índice

1. [[#E1. Calorimetría y cambio de fase|Aluminio, agua y hielo]].
2. [[#E2. Expansión adiabática y primera ley|Gas ideal en expansión]].
3. [[#E3. Máquina térmica y límite de Carnot|Eficiencia real y propuesta de mejora]].
4. [[#E4. Refracción y reflexión interna total|Vidrio rodeado de agua o aire]].
5. [[#E5. Sistema de dos lentes convergentes|Imagen intermedia y final]].

## E1. Calorimetría y cambio de fase

En un recipiente térmicamente aislado se ponen en contacto una pieza de aluminio caliente, agua líquida y hielo. Se espera hasta alcanzar el equilibrio térmico. Desprecia la capacidad térmica del recipiente, el trabajo y la evaporación; considera la fusión del hielo a $0\,^\circ\mathrm C$.

**Datos**

| Sustancia | Masa | Temperatura inicial |
|---|---|---|
| Aluminio | $m_{\mathrm{Al}}=0.80\,\mathrm{kg}$ | $180\,^\circ\mathrm C$ |
| Agua líquida | $m_w=0.50\,\mathrm{kg}$ | $20\,^\circ\mathrm C$ |
| Hielo | $m_i=0.10\,\mathrm{kg}$ | $0\,^\circ\mathrm C$ |

Usa:

$$c_{\mathrm{Al}}=900\,\mathrm{J/(kg\,K)},\qquad c_w=4186\,\mathrm{J/(kg\,K)},\qquad L_f=3.34\times10^5\,\mathrm{J/kg}.$$

**Se pide**

**a)** Determina si se funde todo el hielo. Justifica comparando la energía que podrían ceder el aluminio y el agua al enfriarse hasta cero con la necesaria para fundir el hielo.

**b)** Calcula la temperatura final de equilibrio.

**c)** Calcula la cantidad de calor cedida por el aluminio e indica el signo de su calor intercambiado.

**d)** Enuncia el principio físico que permite plantear el balance energético.

> [!tip]- Pista para empezar
> Decide primero qué pasa con el hielo. Si se funde por completo, separa el calentamiento del agua inicial del proceso del hielo: fusión a cero y calentamiento del agua que resulta. Las dos porciones de agua no parten de la misma temperatura.

**Después del intento:** [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado#E1. Calorimetría y cambio de fase|explicación de E1]].

## E2. Expansión adiabática y primera ley

Un gas ideal diatómico está encerrado en un cilindro con pistón. Se expande **adiabática y reversiblemente** desde un volumen inicial de $2.00\,\mathrm L$ hasta $6.00\,\mathrm L$. Considera $\gamma$ constante y solo trabajo de presión–volumen.

**Datos**

- $p_1=5.00\times10^5\,\mathrm{Pa}$.
- $V_1=2.00\,\mathrm L$.
- $V_2=6.00\,\mathrm L$.
- $\gamma=C_P/C_V=1.40$.
- Para el inciso d: $T_1=600\,\mathrm K$.

**Convención:** $Q>0$ si el gas recibe calor y $W>0$ si el gas realiza trabajo sobre el exterior.

**Se pide**

**a)** Calcula la presión final $p_2$.

**b)** Calcula el trabajo realizado por el gas durante la expansión y justifica su signo.

**c)** Determina el cambio de energía interna $\Delta U$ y explica su signo.

**d)** Calcula la temperatura final $T_2$.

> [!tip]- Pista para empezar
> “Adiabática” fija el calor intercambiado; “reversible” y “gas ideal con $\gamma$ constante” permiten usar las relaciones adiabáticas entre estados. La presión cambia durante el proceso. Convierte litros a metros cúbicos antes de calcular productos $pV$.

**Después del intento:** [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado#E2. Expansión adiabática y primera ley|explicación de E2]].

## E3. Máquina térmica y límite de Carnot

Una máquina térmica opera cíclicamente entre una fuente caliente a $600\,^\circ\mathrm C$ y el ambiente a $25\,^\circ\mathrm C$. En cada ciclo absorbe $2500\,\mathrm J$ de la fuente caliente y entrega $850\,\mathrm J$ de trabajo mecánico.

**Datos**

- Fuente caliente: $T_H=600\,^\circ\mathrm C$.
- Fuente fría: $T_L=25\,^\circ\mathrm C$.
- Calor absorbido por ciclo: $Q_H=2500\,\mathrm J$.
- Trabajo entregado por ciclo: $W=850\,\mathrm J$.

En este ejercicio, $Q_H$, $Q_L$ y $W$ designan **magnitudes positivas**: calor absorbido, calor cedido y trabajo entregado, respectivamente.

**Se pide**

**a)** Determina el calor $Q_L$ cedido al foco frío en cada ciclo.

**b)** Calcula la eficiencia térmica real de la máquina.

**c)** Calcula la máxima eficiencia teórica posible entre esas mismas temperaturas.

**d)** Un ingeniero propone obtener $1900\,\mathrm J$ de trabajo por ciclo absorbiendo los mismos $2500\,\mathrm J$ y operando entre los mismos focos. Decide si la propuesta es físicamente posible y justifica mediante la segunda ley.

> [!tip]- Pista para empezar
> En un ciclo completo la energía interna vuelve a su valor inicial. La eficiencia real se calcula con las energías medidas; las temperaturas permiten calcular un límite para compararla. Usa kelvin para ese límite.

**Después del intento:** [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado#E3. Máquina térmica y límite de Carnot|explicación de E3]].

## E4. Refracción y reflexión interna total

Un sensor óptico está dentro de un bloque de vidrio rodeado de agua. Un rayo que viaja **dentro del vidrio** llega a la interfaz vidrio–agua formando $55^\circ$ con la normal.

**Datos**

- Índice del vidrio: $n_v=1.52$.
- Índice del agua: $n_a=1.33$.
- Índice del aire, para el inciso c: $n_{\mathrm{aire}}=1.00$.
- Incidencia desde la normal: $\theta_i=55^\circ$.

**Se pide**

**a)** Determina si el rayo emerge al agua o experimenta reflexión interna total.

**b)** Calcula el ángulo crítico para la interfaz vidrio–agua.

**c)** Se retira el bloque del agua y se lo deja rodeado de aire. Calcula el nuevo ángulo crítico.

**d)** Indica en cuál de las dos situaciones es más fácil confinar la luz dentro del vidrio y justifica.

> [!tip]- Pista para empezar
> El rayo parte del vidrio en ambos casos. El ángulo crítico corresponde al límite en que el rayo transmitido forma $90^\circ$ con la normal. Después debes compararlo con la incidencia; tener un índice de salida menor no garantiza por sí solo reflexión total.

**Después del intento:** [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado#E4. Refracción y reflexión interna total|explicación de E4]].

## E5. Sistema de dos lentes convergentes

Un objeto de $4.00\,\mathrm{cm}$ de altura se coloca a $30.0\,\mathrm{cm}$ a la izquierda de una lente convergente L1, de distancia focal $f_1=+10.0\,\mathrm{cm}$. Otra lente convergente L2, de distancia focal $f_2=+15.0\,\mathrm{cm}$, está a $50.0\,\mathrm{cm}$ a la derecha de L1.

La luz avanza de izquierda a derecha. Supón lentes delgadas en aire y rayos paraxiales.

**Datos y referencia**

- Altura inicial: $h_0=+4.00\,\mathrm{cm}$.
- Distancia del objeto a L1: $s_1=+30.0\,\mathrm{cm}$.
- Focales: $f_1=+10.0\,\mathrm{cm}$ y $f_2=+15.0\,\mathrm{cm}$.
- Separación entre lentes: $D=50.0\,\mathrm{cm}$.
- Para ubicar los puntos en un mismo eje: L1 en $x=0$, L2 en $x=50.0\,\mathrm{cm}$ y objeto en $x=-30.0\,\mathrm{cm}$.

Para cada lente, usa distancia de objeto positiva si el objeto es real y está del lado de llegada de la luz; distancia de imagen positiva si la imagen es real y queda del lado de salida. Las alturas son positivas por encima del eje.

**Se pide**

**a)** Determina analíticamente la posición de la imagen producida por L1 e indica si es real o virtual.

**b)** Calcula el aumento de L1 y la altura de la imagen intermedia. Describe su orientación.

**c)** Utiliza esa imagen como objeto para L2 y determina la posición de la imagen final, el aumento total y la altura final. Clasifica la imagen final como real/virtual, derecha/invertida y mayor/menor respecto del objeto original.

**d)** Dibuja la marcha de los rayos principales de ambas lentes. Marca los focos, la imagen intermedia y la imagen final.

> [!tip]- Pista para empezar
> Resuelve L1 antes de analizar L2. La distancia de su imagen está medida desde L1; para usarla como objeto de L2 debes volver a medir desde L2. El aumento total se obtiene multiplicando los aumentos de las dos etapas.

**Después del intento:** [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado#E5. Sistema de dos lentes convergentes|explicación y dibujo de E5]].

## Fuentes y continuación

- [Clave de corrección del parcial de Física Aplicada 2026](zotero://select/library/items/TZPNLWDL), PDF pp. 1–2: base de los cinco problemas y de los resultados que se explican en la nota de resoluciones.
- [Primer parcial 2026, transcripción](zotero://select/library/items/BA354CLU), PDF pp. 1–2: datos y preguntas de E2–E5, y constantes de calorimetría. E1 difiere de la versión resuelta por la clave.
- [[Recursos de estudio/Práctica integradora/Resoluciones/01 - Primer parcial 2026 explicado|Abrir las resoluciones detalladas]].
- [[Recursos de estudio/Práctica/00 - Método y registro|Registrar qué paso necesitas volver a practicar]].
