---
tags: [fisica-aplicada, organizacion, convenciones]
aliases: [Reglas del vault, Convenciones de estudio]
---

# Convenciones para mantener y ampliar el vault

Esta nota reúne los criterios editoriales, didácticos y de navegación acordados para que las correcciones y los módulos nuevos mantengan una calidad y una estructura coherentes. Sirve como guía de trabajo; si una decisión cambia, se actualiza aquí y en las notas afectadas.

## Alcance del proyecto

El vault empezó como preparación del segundo parcial y ahora se ampliará progresivamente para cubrir **toda la materia**. Por eso:

- La exclusión de un tema en un parcial —por ejemplo, óptica en el segundo— no significa que quede excluido del curso completo.
- Se distingue lo que evalúa un parcial de lo que forma parte del programa general. La probabilidad basada en modelos sirve para priorizar el repaso de un examen; no determina por sí sola qué temas merece cubrir el vault.
- Los módulos se agregan de acuerdo con el programa, los materiales de clase y los trabajos prácticos disponibles. No se inventan unidades ni se asume que el curso termina en los cuatro temas actuales.
- Las notas de preparación para un examen pueden conservar su alcance y sus planes específicos. Deben presentarse como recursos de ese examen, sin confundirlos con el mapa completo de la materia.

## Estructura por tema

Cada unidad se agrupa bajo `Unidades/NN - [Tema]/`. La nota de recorrido de teoría funciona como entrada al módulo y conecta las subcarpetas de aprendizaje:

| Subcarpeta de la unidad | Archivo | Función |
|---|---|---|
| `Teoría/` | `NN - [Tema].md` | Presenta objetivos, alcance, ruta de estudio, conexiones y enlaces del módulo. |
| `Teoría/` | `NN - Guía breve de [tema].md` | Divide la teoría imprescindible en bloques asociados a familias de ejercicios; cada bloque termina invitando a recuperar la idea y pasar de inmediato a practicar. |
| `Teoría/` | `NN - Conceptos de [tema].md` | Explica el modelo físico, el significado de las magnitudes y de dónde surgen las relaciones. |
| `Teoría/` | `NN - Fórmulas aplicadas de [tema].md` | Organiza fórmulas, criterios de elección, despejes, unidades y controles. |
| `Ejercicios/` o `Práctica/` | Una nota de ejercicios de la unidad | Reúne todos los problemas de la unidad, agrupados por familias mediante títulos, con pistas y claves plegables. |
| `Resoluciones/` | Una nota de resoluciones de la unidad | Desarrolla las soluciones justificadas en las mismas familias y con los mismos identificadores que el archivo de ejercicios. |
| `Autoevaluación/` | `NN - [Tema].md` | Reúne las preguntas conceptuales, de fórmulas y de repaso de esa unidad. |

`Unidades/Inicio.md` es el mapa general. `Recursos de estudio/` agrupa herramientas compartidas entre unidades (índices, autoevaluación general, práctica integradora, fuentes y formularios). `Planes de estudio/` está en la raíz y reúne los cronogramas y su guía común. Las imágenes compartidas se guardan en `imagenes/`; la entrada del vault y las pautas generales permanecen en la raíz.

No hace falta crear una nota vacía para completar el patrón: se crean las notas que aporten contenido real. Los conceptos y las fórmulas pueden tener notas adicionales si un subtema extenso lo requiere; la práctica mantiene el par de archivos indicado. Las unidades 01–04 guardan sus ejercicios en `Ejercicios/` y las unidades 05–06 en `Práctica/`. Todas las unidades guardan sus resoluciones en `Resoluciones/`.

### Familias dentro de una práctica unificada

- Cada unidad tiene **un archivo común de ejercicios y un archivo común de resoluciones**. Los ejercicios se guardan en la carpeta de práctica de la unidad (`Ejercicios/` o `Práctica/`, según su organización existente) y las resoluciones siempre en `Resoluciones/`. La cantidad de familias o de ejercicios se resuelve con encabezados e índices internos; no determina la creación de más archivos.
- Agrupa cada familia bajo un título de nivel 2 (`## Temperatura y dilatación`) y cada ejercicio bajo un título de nivel 3 (`### T1. …`). Dentro de las resoluciones, usa las mismas familias, el mismo orden y los mismos identificadores; los pasos de solución pueden usar títulos de nivel 4.
- Incluye al comienzo de ambos archivos un índice con enlaces a las familias. Cada familia conserva el contexto para empezar, sus referencias teóricas, las etiquetas M/R/C y las prioridades correspondientes.
- Enlaza cada ejercicio con su resolución y cada resolución con el enunciado. Desde la guía breve, los conceptos, las fórmulas y la autoevaluación, apunta al encabezado de la familia o del ejercicio específico, para continuar el estudio sin recorrer todo el archivo.
- La nota de recorrido enlaza los dos archivos comunes y permite entrar por familia. Al unificar archivos existentes, actualiza los enlaces entrantes, retira los archivos reemplazados y conserva el contenido, las pistas, las claves y las referencias de origen. Las familias se identifican por sus títulos; los nombres de archivo usan el número de la unidad sin sufijos A/B/C.
- Separa el **identificador** del ejercicio de su **clasificación M/R/C**. Para módulos nuevos usa identificadores neutrales y estables (por ejemplo, `T1`, `T2` en Termodinámica) y escribe la etiqueta M/R/C al final del título; no uses la misma letra como número y como procedencia.
- Conserva identificadores heredados cuando ya tengan enlaces, aunque empiecen con `C`; la etiqueta en negrita al final del título es la clasificación válida. Al crear ejercicios nuevos, evita esa ambigüedad usando identificadores neutrales.

### Navegación y nombres

- Mantén el prefijo numérico de las unidades y un nombre descriptivo que coincida entre teoría, ejercicios y resoluciones.
- Usa enlaces internos de Obsidian (`[[Unidades/NN - Tema/Subcarpeta/Nombre de nota]]`) para conectar la ruta de estudio y los conceptos relacionados.
- Al sumar una unidad, enlázala desde los mapas e índices que correspondan. Revisa también las notas generales que deban incorporar sus modelos o fórmulas.
- Conserva los identificadores de ejercicios ya publicados: las resoluciones, los planes y los enlaces los usan como referencia. En ejercicios nuevos continúa la numeración de la unidad; si hace falta una clave local, usa un prefijo neutral del tema. La categoría M/R/C se expresa aparte y no debe confundirse con el identificador.
- Usa encabezados concisos y jerárquicos (`#`, `##`, `###`) para que los enlaces a secciones sean estables y fáciles de encontrar.

## Criterios para la teoría

La explicación debe ayudar a entender y elegir un modelo, no funcionar solo como una lista de fórmulas. En cada concepto importante, aclara:

1. **Qué representa** y qué situación física describe.
2. **Cómo se interpreta** cada magnitud, vector, signo y unidad.
3. **De qué principio u observación sale la relación.** Muestra el razonamiento, la deducción breve o las sustituciones que llevan a la fórmula; distingue una ley de partida de una relación derivada para un caso particular.
4. **Qué supuestos requiere** y cuándo se puede aplicar. Señala los casos en que no corresponde usarla.
5. **Cómo orienta un ejercicio:** qué dato reconocer, qué incógnita buscar, qué esquema conviene dibujar y qué control hacer al final.

Introduce primero la situación y la idea física; después define los parámetros, desarrolla la relación matemática y muestra cómo se usa. Cuando una fórmula se obtenga de otra, deja visible el puente entre ambas. Explica las confusiones previsibles —por ejemplo, magnitudes parecidas, marcos de referencia, sentidos o unidades— cerca del concepto involucrado.

### Nota de conceptos y nota de fórmulas

- **Conceptos:** desarrolla el contexto, la intuición, el origen de las expresiones, las condiciones del modelo y sus conexiones. Evita dar por obvio el significado de símbolos o términos técnicos.
- **Fórmulas aplicadas:** facilita la consulta durante la práctica. Para cada relación, indica cuándo elegirla, qué significa cada símbolo, las unidades, cómo despejar y qué resultado o límite permite comprobarla. Enlaza la explicación de origen en conceptos cuando haga falta.
- No dupliques explicaciones extensas si basta con enlazar la nota complementaria; conserva en cada nota el contexto mínimo para que se entienda al abrirla por separado.

### Lectura esencial vinculada a la práctica

- Además de la explicación conceptual completa, ofrece una **ruta breve de lectura activa** por unidad, organizada en bloques que correspondan a un tipo o grupo pequeño de ejercicios similares.
- Cada bloque debe dar el contexto físico mínimo, definir los parámetros relevantes, explicar el origen o el razonamiento central de la relación, indicar cuándo elegirla y advertir una confusión frecuente.
- El bloque concluye con una pregunta breve de recuperación, su explicación justificada en un callout plegable y un enlace directo a los ejercicios para intentar inmediatamente. La secuencia prevista es leer un tramo corto, reexplicarlo sin mirar, responder y practicar; la explicación se despliega después del intento o cuando la respuesta no sale.
- Conserva las deducciones largas, casos especiales, referencias e imágenes de apoyo en las notas conceptuales completas. La ruta breve debe enlazar a ellas cuando una duda requiera profundidad, en vez de duplicar todo el desarrollo.
- No conviertas la ruta breve en un formulario: explica por qué la fórmula corresponde al fenómeno y qué dato del enunciado permite reconocerlo.
- [[Recursos de estudio/Teoría general/00 - Teoría esencial para practicar]] funciona como índice de la lectura activa; el contenido resumido se separa en una guía breve por unidad y se enlaza desde el índice del módulo, la página de inicio y el índice general cuando corresponda. Así cada tema conserva su propio recorrido y no se concentra toda la teoría breve en un archivo extenso.

### Autoevaluación centralizada

- Guarda las preguntas de cada unidad en su subcarpeta `Autoevaluación/`, separadas en **Conceptos**, **Fórmulas** y **Repaso del módulo**. El índice común está en `Recursos de estudio/Autoevaluación/Inicio.md`; conserva una página integradora cuando ayude a comparar temas.
- Las notas extensas de conceptos y fórmulas no repiten las preguntas: al final de cada bloque numerado incluyen un enlace a la categoría correspondiente de autoevaluación.
- Los módulos y los índices señalan el repaso final de la unidad; el índice común de `Recursos de estudio/Autoevaluación/` permite entrar directamente por tema.
- La excepción son las guías breves: conservan una pregunta breve después de cada bloque pequeño, su explicación plegable y el enlace inmediato a la práctica. Esa pregunta forma parte del ciclo lectura–recuperación–ejercicio.
- Las respuestas se ocultan en callouts plegables de Obsidian, por ejemplo:

```markdown
**1. ¿Qué representa esta magnitud y cuándo usarías la relación?**

> [!success]- Mostrar explicación
> Explica el razonamiento, las condiciones y cómo comprobar la respuesta.
```

La explicación debe justificar la respuesta y señalar qué idea conviene revisar si hay un error. Antes de ampliar el número de preguntas, cubre las decisiones conceptuales y de selección de fórmulas que realmente aparecen en la práctica.

## Criterios para ejercicios y resoluciones

### Redacción de los enunciados

Cada ejercicio debe poder abordarse sin tener que adivinar qué significan los datos. Incluye, según corresponda:

- una situación breve que identifique los objetos, el fenómeno y el sistema que se analiza;
- datos con unidades y marco de referencia explícitos;
- convención de ejes, signos o sentidos cuando afecten el planteo;
- una lista separada de datos y de lo que se pide;
- un esquema si aclara la geometría, los vectores, las mediciones o la propagación;
- una pista plegable para orientar el primer paso, sin revelar de inmediato toda la cuenta;
- un enlace a la resolución completa, cuando exista.

No ocultes en la redacción una condición necesaria para elegir la fórmula. Si el dato original es ambiguo o difícil de leer, verifica el documento o la imagen de origen y registra la fuente.

### Etiquetas y prioridad

- **M — modelo:** reproduce un enunciado o planteo de un modelo de examen, aunque se hayan aclarado datos o mejorado la redacción. Cita el año/versión y la pregunta.
- **R — refuerzo/variante:** problema nuevo que transfiere una familia que sí aparece en un modelo a otros datos, incógnitas o condiciones. Cita el modelo relacionado y, si corresponde, el TP del que se adaptó. R no significa “repetido en varios modelos”.
- **C — complementario:** problema tomado o adaptado de un TP u otra fuente de clase cuya habilidad central no aparece en los modelos revisados. Cita fuente y número de ejercicio.
- M/R/C clasifican la relación del ejercicio con las fuentes; **no son por sí solos una escala de probabilidad**. No etiquetes M ni R a una unidad sin respaldo en los modelos consultados.
- Lleva por separado la **evidencia de examen**: alta si la familia aparece en dos o más años/modelos independientes; media si aparece en uno; “sin evidencia en los modelos consultados” si no aparece. Si dos archivos parecen versiones del mismo examen, no los cuentes como dos apariciones independientes sin comprobarlo.
- Lleva por separado la **prioridad didáctica**: alta para prerrequisitos y métodos centrales; media para variantes útiles; ampliación para casos especiales. Puede haber un ejercicio C de prioridad didáctica alta, pero eso no lo convierte en probable para el examen.
- En cada ejercicio o grupo homogéneo, muestra la etiqueta, la referencia de origen y la prioridad que corresponda. Si una unidad no figura en los modelos archivados, decláralo en el índice de la unidad y evita asignar una probabilidad de examen a sus C.

### Resolución guiada

Las resoluciones muestran tanto **por qué se elige el método** como **cómo se hacen los cálculos**. Sigue, adaptando al tema, esta secuencia:

1. Interpretar la situación, definir sistema, eventos o marco, y fijar sentidos.
2. Anotar datos, incógnita y unidades; convertir a un sistema coherente.
3. Elegir y nombrar el principio físico, justificando que sus supuestos se cumplen.
4. Escribir primero la relación simbólica y explicar el despeje antes de reemplazar números.
5. Sustituir valores con unidades y desarrollar los pasos de cálculo necesarios.
6. Expresar el resultado con unidad, dirección o interpretación física.
7. Comprobar orden de magnitud, signo, límites o comportamiento esperado.

No saltes pasos algebraicos que sean justamente la dificultad del ejercicio. Si el enunciado contiene una decisión conceptual escondida, explícalo antes de calcular. La respuesta final debe coincidir con la clave de práctica y mantener la misma notación.

## Imágenes, diagramas y recursos externos

- Añade una imagen si mejora la comprensión de la geometría, el fenómeno, los vectores o la lectura de un gráfico; acompáñala con una explicación de qué debe observarse.
- Para diagramas creados para el vault, prefiere SVG sencillo, legible y editable. Guarda el archivo en `imagenes/` y usa un nombre descriptivo, sin espacios innecesarios.
- Para imágenes extraídas de libros o apuntes, recorta solo la figura necesaria e identifica en el pie su fuente, capítulo o página. No sustituyas la explicación por una imagen ni incorpores páginas completas cuando basta un esquema.
- Inserta los recursos con el formato nativo `![[imagenes/nombre-del-archivo.svg]]`; puedes fijar un ancho, por ejemplo `![[imagenes/nombre.png|500]]`, si así se lee mejor en Obsidian.
- Los videos son apoyo opcional: enlázalos solo si explican una dificultad concreta, indica qué sección o idea conviene mirar y conserva la explicación principal dentro del vault.

## Compatibilidad con Obsidian

- Escribe en Markdown estándar y usa las fórmulas como matemáticas LaTeX: `$...$` en línea y `$$...$$` en bloque.
- Emplea enlaces `[[...]]`, embeds `![[...]]` y callouts nativos. No hagas que el contenido dependa de un plugin comunitario.
- Mantén frontmatter YAML simple, con etiquetas en minúscula y sin valores que necesiten formato complejo.
- Usa tablas para comparaciones cortas. Para deducciones largas, explicaciones y secuencias de cálculo, prefiere texto y ecuaciones en bloques.
- Dentro de una tabla, escapa el separador de texto visible de los enlaces de Obsidian (`[[nota#sección\|texto]]`) para que no se interprete como una columna adicional. Mantén contiguas las filas de la tabla, sin líneas en blanco entre ellas.
- Escribe las unidades junto a los valores y conserva una notación consistente dentro de cada tema. Define cualquier símbolo que pueda tener más de un significado.

## Fuentes y trazabilidad

- Basa las explicaciones y ejercicios en el material de la materia, los modelos de parcial y los trabajos prácticos disponibles. Consulta el original cuando una página, cifra, signo o figura no sea legible.
- Registra autor o título, ubicación útil (capítulo, página, número de problema) y qué parte del vault respalda. Enlaza a la nota de fuentes o a Zotero cuando el enlace esté disponible.
- Separa lo que dice la fuente de una explicación añadida para enseñar. No atribuyas a un modelo una variante que fue creada para practicar.
- Si se usa un recurso externo, comprueba que el enlace corresponda al contenido citado e indica por qué se recomienda.

## Lista de revisión antes de cerrar un módulo

- [ ] El alcance del tema está claro y no se confunde el programa completo con un parcial particular.
- [ ] La teoría define términos, interpreta parámetros y explica el origen, uso y supuestos de las fórmulas importantes.
- [ ] La nota de fórmulas ayuda a elegir una relación, despejarla y revisar unidades y resultados.
- [ ] Los ejercicios tienen enunciados completos, datos explícitos y pistas separadas de la resolución.
- [ ] La unidad reúne sus ejercicios en un archivo y sus resoluciones en otro, con familias bajo títulos, índices internos y enlaces de ida y vuelta.
- [ ] Las etiquetas y prioridades reflejan la fuente y la evidencia disponibles.
- [ ] Las resoluciones justifican el principio y desarrollan los pasos hasta comprobar el resultado.
- [ ] La autoevaluación incluye respuestas explicadas y plegables.
- [ ] Las imágenes aportan algo, tienen enlace y pie de fuente cuando corresponde.
- [ ] Los enlaces internos, nombres de archivo, fórmulas y callouts se visualizan correctamente en Obsidian.
- [ ] Los índices generales y rutas de estudio relevantes apuntan a las notas nuevas.

## Flujo recomendado para trabajar unidad a unidad

1. Inventariar programa, teoría, modelos y trabajos prácticos disponibles para la unidad.
2. Separar conceptos del programa, tipos de pregunta de examen y ejercicios complementarios.
3. Revisar la navegación y los materiales actuales antes de reescribir; preservar correcciones ya incorporadas.
4. Refinar conceptos y fórmulas, explicando el puente entre teoría y resolución.
5. Revisar redacción, variedad y alcance de ejercicios; completar las resoluciones paso a paso.
6. Agregar o ajustar visuales y referencias solo donde ayuden a entender.
7. Aplicar la lista de revisión, actualizar los índices y dejar anotadas las decisiones que afecten a unidades posteriores.

**Entradas:** [[README]] · [[Inicio]] · [[Recursos de estudio/Teoría general/00 - Mapa y formulario general]]

**Planificación de estudio:** [[Pautas para elaborar planes de estudio]].
