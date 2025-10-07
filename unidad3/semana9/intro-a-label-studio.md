---
layout: default
title: Introducción a Label Studio
parent: Semana 9
grand_parent: Unidad 3
nav_order: 2
---

# Introducción a Label Studio

Label Studio es un entorno de anotación profesional de código abierto que profesionales utilizan para anotar los datos que se emplean para entrenar modelos de lenguaje grandes (LLMs). Durante la clase, seguirán a la profesora mientras demuestra cómo crear y anotar (evaluar) proyectos en Label Studio.

## Obtener Acceso a Label Studio

Se les ha proporcionado un enlace privado en Teams para acceder a la plataforma Label Studio. Por favor, sigan ese enlace y creen su cuenta en Label Studio.

**Nota importante sobre el acceso:** El enlace de invitación les da acceso a la instancia privada completa de Label Studio de la profesora. Por favor, tengan cuidado de no cambiar ninguna configuración importante ni eliminar ningún proyecto una vez que entren al sistema. Si se elimina un proyecto antes de que todas las personas lo hayan completado, todas y todos tendremos que volver a hacer nuestro trabajo. Además, registren sus contraseñas cuidadosamente. No hay forma de que recuperen su cuenta si pierden su contraseña. Pueden comunicarse con la instructora para restablecer su contraseña, y si ella no está disponible para eso, simplemente tendrán que crear una cuenta nueva.

## Entrenamiento Tecnológico

En el proyecto de entrenamiento tecnológico, el enfoque está en ganar familiaridad con la tecnología Label Studio, no con los aspectos lingüísticos de las evaluaciones de calidad de traducción.

### Proyecto de Práctica: Valor de los Manglares

Para esta sesión de entrenamiento tecnológico, trabajarán con un texto breve sobre la valoración económica de los manglares ante el cambio climático. El objetivo es que se familiaricen con:

- **Panel de control del proyecto**: Dónde se visualizan todos sus proyectos y estadísticas
- **Interfaz de etiquetado**: El espacio principal donde llevan a cabo las evaluaciones
  - Área principal de etiquetado
  - Área de asignación de errores (Dimensiones, Errores, Severidad, Notas)
  - Lista de anotaciones
  - Área de calificación a nivel de documento
- **Navegación**: Cómo moverse entre tareas y guardar su trabajo
- **Controles básicos**: Cómo marcar texto, asignar categorías y agregar comentarios

**Archivo de referencia:** [Valor de los Manglares_ES-MX_2026-1.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/Valor%20de%20los%20Manglares_ES-MX_2026-1.pdf)

**Importante:** Este es un ejercicio de práctica que se completa en clase. No necesitan entregar nada de esta actividad de entrenamiento tecnológico.

## Entrenamiento Lingüístico

En el proyecto de entrenamiento lingüístico, el enfoque está en tomarse el tiempo para familiarizarse con la marcación de errores de traducción según el marco MQM. Pero primero, debemos discutir: ¿Qué es diferente en el entorno de Label Studio en comparación con cómo se lleva a cabo la edición en tecnología de traducción como herramientas TEnT?

### Diferencias Clave: Label Studio vs. Herramientas TEnT

**Herramientas TEnT tradicionales:**
- Presentan el contenido en pares de oraciones fuente-meta descontextualizados
- Enfocadas en la edición oración por oración
- Dificultan la evaluación de coherencia y fluidez del texto completo

**Label Studio:**
- Presenta textos completos con contexto completo
- Permite evaluación holística del documento
- Facilita la identificación de problemas de coherencia y estilo
- Mejor para evaluar efectividad comunicativa general

### Repaso de MQM

Antes de comenzar con el entrenamiento lingüístico, reflexionen sobre sus experiencias previas con MQM:

**Revisen el contenido del curso:**
- [Marco MQM para Evaluación de Traducción](../../unidad2/semana4/marco-mqm.md) - Unidad 2, Semana 4
- La tipología de errores y niveles de gravedad
- Ejemplos de cada tipo de error que estudiaron

**Reflexionen sobre sus evaluaciones:**
- ¿Qué dimensiones de error aparecen más frecuentemente en las evaluaciones de sus traducciones?
- ¿Qué tipos de error todavía les resultan difíciles de distinguir?
- ¿Hay categorías de MQM que aún no comprenden completamente?
- ¿Qué patrones de error han notado en su propio trabajo?

### Preguntas para Consideración

Mientras se preparan para el entrenamiento lingüístico, consideren:

1. **Comprensión de dimensiones**: ¿Entienden claramente la diferencia entre Precisión, Fluidez, Estilo, y Terminología?

2. **Niveles de gravedad**: ¿Pueden distinguir entre errores neutrales, menores, mayores y críticos?

3. **Casos ambiguos**: ¿Qué hacen cuando un error podría clasificarse en más de una categoría?

4. **Contexto vs. oración**: ¿Cómo cambia su evaluación cuando pueden ver el texto completo en lugar de oraciones aisladas?

### Proyectos Disponibles para Entrenamiento

Los resúmenes de artículos académicos se adaptaron de los artículos citados al final de cada uno de los documentos.

| **Nombre del Proyecto** | **Descripción** | **Contenido Fuente** | **Contenido Meta** |
| ----------------------- | --------------- | -------------------- | ------------------ |
| **Carbono en Manglares** | Estudio sobre dinámica del carbono (almacenes y flujos) en manglares mexicanos, evaluando el papel de estos ecosistemas en el ciclo del carbono | [CarbonoEnManglares-Extended_ES-MX.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/CarbonoEnManglares-Extended_ES-MX.pdf) | [CarbonoEnManglares-Extended_EN-US.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/CarbonoEnManglares-Extended_EN-US.pdf) |
| **Manglares: ecosistema centinela** | Investigación sobre manglares como indicadores del cambio climático en el Golfo de México y la tropicalización de la región | [Manglares-EcosistemaCentinela-Extended_ES-MX.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/Manglares-EcosistemaCentinela-Extended_ES-MX.pdf) | [Manglares-EcosistemaCentinela-Extended_EN-US.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/Manglares-EcosistemaCentinela-Extended_EN-US.pdf) |
| **Reserva de carbono** | Análisis de cambios en reservas de carbono en manglares del norte de México durante 35 años, evaluando impactos de presiones antrópicas | [ReservaDeCarbono-Extended_ES-MX.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/ReservaDeCarbono-Extended_ES-MX.pdf) | [ReservaDeCarbono-Extended_EN-US.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/referencias/ReservaDeCarbono-Extended_EN-US.pdf) |

**Selección de proyecto:** Durante el entrenamiento lingüístico en clase, pueden elegir cualquiera de estos tres proyectos para practicar. El objetivo es familiarizarse con el proceso de identificar y categorizar errores usando MQM, no completar todos los proyectos.

**Importante:** Este es un ejercicio de práctica que se completa en clase. No necesitan entregar nada de esta actividad de entrenamiento lingüístico. Su tarea para la semana será completar una evaluación real, que se describirá en la siguiente página del curso.

## Estrategias para Evaluación Efectiva

Mientras practican en Label Studio, consideren estas estrategias:

### Antes de Comenzar a Marcar Errores

1. **Lean el texto completo** en ambos idiomas para comprender el contexto
2. **Identifiquen el tipo de texto** y sus convenciones esperadas
3. **Consideren la audiencia** y el propósito del documento
4. **Noten el tono y registro** apropiados para el texto

### Durante la Marcación de Errores

1. **Marquen con precisión**: Seleccionen exactamente el texto problemático, ni más ni menos
2. **Categoricen cuidadosamente**: Tómense tiempo para elegir la dimensión y tipo de error correctos
3. **Asignen severidad apropiada**: Consideren el impacto real del error en la efectividad del texto
4. **Proporcionen notas útiles**: Expliquen por qué algo es un error y, si es posible, sugieran una corrección

### Después de Marcar Todos los Errores

1. **Evalúen holísticamente**: Consideren el texto completo, no solo los errores individuales
2. **Califiquen correspondencia**: ¿Qué tan bien transmite el significado del fuente?
3. **Califiquen legibilidad**: ¿Qué tan natural fluye como texto independiente en inglés?
4. **Determinen efectividad**: ¿Logra su propósito comunicativo?

## Desafíos Comunes y Cómo Abordarlos

### "No sé cómo categorizar este error"

Si un error parece encajar en múltiples categorías:
- Consideren cuál es el problema **principal**
- Consulten la [tipología MQM](https://themqm.org/the-mqm-typology/) para guía
- Dejen una nota explicando su razonamiento
- Discutan casos ambiguos con la profesora y compañeras/os

### "No estoy seguro/a del nivel de severidad"

Para determinar severidad:
- **Neutral**: Preferencia personal, no afecta significativamente la calidad
- **Menor**: Impacta ligeramente la calidad pero no impide la comprensión
- **Mayor**: Afecta seriamente la comprensión o confiabilidad
- **Crítica**: Hace que el contenido no sea apto para su propósito

### "El error está en el texto fuente, no en la traducción"

Label Studio está diseñado para evaluar la calidad de la traducción, no la calidad del texto fuente. Si identifican un problema en el fuente:
- No lo marquen como error de traducción
- Pueden dejarlo en una nota si es relevante para comprender decisiones de traducción
- Enfóquense en evaluar si la traducción transmite apropiadamente lo que dice el fuente

## Recursos de Apoyo

### Documentación de Label Studio
- [Descripción general de Label Studio](https://labelstud.io/guide/get_started) - Secciones _What is Label Studio_ y _Interface_
- [Guía de etiquetado de Label Studio](https://labelstud.io/guide/labeling)

### Recursos MQM
- [Tipología de errores MQM](https://themqm.org/the-mqm-typology/)
- [Marco MQM del curso](../../unidad2/semana4/marco-mqm.md)

### Archivos de Apoyo
Todos los archivos de apoyo para la Semana 9, incluyendo la configuración de la interfaz de etiquetado y materiales de referencia, están disponibles en Teams: **Week 9 Error Annotation Support Files**

## Preparación para la Evaluación Real

Después de completar el entrenamiento tecnológico y lingüístico en clase, estarán listos/as para realizar su primera evaluación de calidad real de forma independiente. Esta evaluación será su tarea para la semana y se describirá en detalle en la siguiente página del curso.

La experiencia que adquieran durante estos entrenamientos será fundamental para:
- Desarrollar confianza en el uso de Label Studio
- Comprender profundamente la tipología MQM
- Reconocer patrones de error comunes
- Evaluar traducciones de manera consistente y profesional

---

## 📥 Descarga esta Actividad

Encuentra este archivo [en nuestro repositorio](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana9/intro-a-label-studio.md) y descárgalo.

Para prepararte mejor para trabajar con Label Studio y MQM, prueba estos prompts con tu herramienta de IA preferida:

- "Explica las ventajas de evaluar textos completos versus pares de oraciones en evaluación de calidad de traducción"
- "¿Cómo puedo determinar si un error debería categorizarse como 'Precisión' o 'Estilo' en el marco MQM?"
- "Crea una guía paso por paso para evaluar la severidad de errores de traducción"
- "¿Cuáles son las diferencias clave entre errores de 'Terminología' y errores de 'Precisión - Traducción errónea'?"
- "Ayúdame a desarrollar criterios consistentes para asignar calificaciones de correspondencia y legibilidad"
- "¿Qué aspectos debo considerar al evaluar si una traducción científica es 'efectiva'?"

---

**Siguiente:** [Contexto para el Proyecto de Evaluación - Label Studio](./texto6-contexto.md)
