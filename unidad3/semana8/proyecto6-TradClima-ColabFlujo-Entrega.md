---
layout: default
title: Proyecto 6 - Traducción Científica Flujo Colaborativo - Entrega
parent: Semana 8
grand_parent: Unidad 3
nav_order: 4
---

# Proyecto 6 - Traducción Científica Flujo Colaborativo: Entrega Final

**Puntos:** 3

**Modalidad:** Grupos de 2-3 personas (según asignación en clase)

## Descripción completa del proyecto

Este proyecto simula flujos de trabajo profesionales de traducción donde trabajan en equipos especializados utilizando Lilt, una herramienta CAT profesional. Continuarán con sus traducciones de un texto científico sobre cambio climático mientras asumen diferentes roles en el proceso de traducción.

### Texto fuente

Trabajarán traduciendo un texto adaptado del artículo académico "Manglares frente al cambio climático: ¿tropicalización global del Golfo de México?". 

- **Texto completo del artículo:** [ManglaresFrenteElCambioClimático.pdf](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana7/referencias/ManglaresFrenteElCambioClimático.pdf)
- **Texto para traducir:** [manglares-frente-al-cambio-climatico.md](../semana7/manglares-frente-al-cambio-climatico.md)

## Flujo de trabajo en Lilt

### Acceso a Data Sources

Han recibido una actualización en su nivel de acceso a Lilt. Ahora pueden acceder a fuentes de datos (data sources), que son objetos donde se almacenan las entradas de memoria de traducción y base terminológica que guían al modelo de lenguaje en la generación de traducciones ([más información](https://support.lilt.com/developers/guides/manage-content/create-a-datasource)).

**IMPORTANTE:** Tienen acceso de visualización/lectura/escritura a todas las fuentes de datos en nuestro espacio de Lilt. **Tengan mucho cuidado de no editar/eliminar fuentes de datos que no son suyas.**

Cada equipo tiene su propia fuente de datos de Cambio Climático. Las entradas de base terminológica y memoria de traducción que agreguen a su fuente de datos guiarán su propio modelo de lenguaje.

### Roles y responsabilidades

**Flujo de trabajo:** Terminología → Traducción → Edición → Corrección de estilo → Verificación final/Entrega

**Realizado por:** Terminólogo/a → Traductor/a → Editor/a → Corrector/a de estilo → Gerente de proyecto

#### División del trabajo:

| **En equipos de 3** | **En equipos de 2** |
|---------------------|---------------------|
| • **Rol 1:** Terminólogo/a y Corrector/a de estilo<br>• **Rol 2:** Editor/a y Gerente de proyecto <br>• **Rol 3:** Traductor/a | • **Rol 1:** Terminólogo/a y Editor/a<br>• **Rol 2:** Traductor/a y Corrector/a de estilo<br>• *El trabajo de gestión de proyecto se comparte* |

**Tiempo requerido:** Cada integrante debe contribuir un mínimo de dos horas y no más de tres horas al proyecto.

### Descripción detallada de roles

#### Terminología

El/la terminólogo/a recopila y gestiona la terminología especializada del proyecto.

**Tareas:**

1. **Crear base de datos terminológica en Excel** con estos campos:

| **Campo** | **Descripción** | **Requisitos** |
|-----------|-----------------|----------------|
| **ESP Term(s)** | Término principal y sinónimos en español | Separar sinónimos con \| |
| **ESP Definition** | Definición en español | Clara y precisa |
| **ESP Sources** | Fuentes donde obtuvieron el término/definición | URLs, títulos de documentos, etc. |
| **ENG Term(s)** | Término(s) equivalente(s) en inglés | Separar sinónimos con \| |
| **ENG Definition** | Definición en inglés | Clara y precisa |
| **ENG Sources** | Fuentes para el término/definición en inglés | URLs, títulos de documentos, etc. |
| **Notes** | Campo opcional | Cualquier información adicional relevante |

Este archivo debe ser accesible para todo el equipo durante el proyecto.

**Nombre del archivo:** `ApellidosDelMiembro1_ApellidosDelMiembro2_ApellidosDelMiembro3_Glosario-Cambio-Climatico.xlsx`

2. **Agregar términos a la Data Source en Lilt:**

   a. Navegar a su 'Data Source' y hacer clic en editar
   
   b. Hacer clic en `+ New Entry`
   
   ![Agregar entrada en fuente de datos](https://raw.githubusercontent.com/alainamb/uic_tr18-trad-inversa-es-en/main/unidad3/semana8/imagenes/Lilt_AddDataSourceEntry.png)
   
   c. Llenar el cuadro de diálogo con:
      - **Type of entry:** Termbase
      - **Source text [es]:** término fuente
      - **Target text [en]:** término meta
      - **Approval status:** Reviewed
   
   ![Agregar nueva entrada](https://raw.githubusercontent.com/alainamb/uic_tr18-trad-inversa-es-en/main/unidad3/semana8/imagenes/Lilt_AddNewEntry.png)

**Requisito mínimo:** Al menos 5 términos en el glosario.

**Nota:** Tienen acceso a las fuentes de datos de otros equipos. Les advertimos que copien el trabajo de otro equipo bajo su propio riesgo.

#### Traducción

El/la traductor/a realiza la traducción inicial del texto, trabajando con la asistencia del modelo de lenguaje entrenado.

**Tareas:**
- Traducir el texto completo con cuidado de entender el significado fuente y expresarlo en inglés fluido
- Verificar cuidadosamente los resultados generados por el modelo por precisión y estilo
- Confirmar que se ha seguido la base terminológica
- Si encuentran problemas en la base terminológica, actualizar el glosario de Excel y la entrada en Lilt
- Dejar comentarios en Lilt sobre pasajes difíciles o dudas
- Comunicarse con el equipo fuera de Lilt sobre problemas encontrados

> **⚠️ Advertencia profesional:** En entornos de producción, algunos traductores asumen que como su trabajo será verificado después, pueden entregar un borrador de mala calidad. **No hagan esto.** La traducción que entregan necesita ser de calidad pulida.

#### Edición

El/la editor/a verifica la precisión de la traducción mediante comparación cuidadosa del texto meta con el texto fuente.

**Tareas:**
- Hacer una revisión detallada comparando texto fuente y texto meta
- Verificar precisión conceptual y terminológica
- Si encuentran problemas en la base terminológica, actualizar el glosario de Excel y la entrada en Lilt
- Corregir errores de traducción
- Mejorar claridad sin hacer cambios innecesarios

> **⚠️ Advertencia profesional:** En entornos de producción, algunos editores asumen que el/la traductor/a hizo toda la investigación necesaria, así que hacen una revisión descuidada y rápida. **No hagan esto.** El texto editado que entregan idealmente necesita ser de mejor calidad que la traducción, aunque deben tener cuidado de no hacer cambios innecesarios (llamados cambios preferenciales en entornos de producción).

#### Corrección de estilo

El/la corrector/a de estilo hace la verificación final del texto como contenido independiente.

**Tareas:**
- Revisar el texto para asegurar que fluya bien en inglés
- Enfocarse en el estilo fluido más que en la comparación con la fuente
- Verificar que el contenido esté pulido tipográficamente
- Asegurar que se haya seguido la base terminológica
- Corregir cualquier error final de formato o estilo

> **⚠️ Advertencia profesional:** En entornos de producción, algunos correctores de estilo asumen que como están al final del flujo de trabajo, pueden simplemente confirmar todo sin realmente leerlo. **No hagan esto.** La corrección de estilo es un paso importante de gestión de riesgo, especialmente cuando la traducción original tenía múltiples problemas. Mientras más necesitó revisar el/la editor/a, más probable es que pierdan un error en el texto.

#### Gestión de proyecto

El/la gerente de proyecto coordina el trabajo del equipo y prepara los entregables finales.

**Tareas:**
- Coordinar comunicación entre miembros del equipo
- Asegurar que se cumplan los plazos internos
- Preparar el reporte final con tiempos y reflexiones
- Verificar que todos los entregables estén completos y correctamente nombrados
- Hacer la entrega final de archivos

### Fin del proceso en Lilt

Después de cada paso en Lilt, hagan clic en **"Complete"** para entregar el trabajo al siguiente paso. 

**Al final del proceso, no descarguen la traducción para entregarme.** Obtendré su texto finalizado directamente de Lilt.

## Entregables para Semana 8

### 1. Glosario bilingüe especializado (Excel)

- Archivo Excel (.xlsx) con al menos 5 entradas terminológicas
- Todas las columnas completas según la tabla especificada
- **Nombre:** `ApellidosDelMiembro1_ApellidosDelMiembro2_ApellidosDelMiembro3_Glosario-Cambio-Climatico.xlsx`

### 2. Reporte final del proyecto (Word)

El reporte debe incluir:

#### Información del equipo
- Nombres de todas las personas integrantes
- Roles específicos asignados a cada quien

#### Registro detallado de tiempo y tareas

| **Fase** | **Completada por** | **Tiempo dedicado / persona** |
|----------|--------------------|-------------------------------|
| Trabajo terminológico | | |
| Traducción | | |
| Revisión | | |
| Corrección de estilo | | |
| Gestión del proyecto | | |

**Total de horas del Team Member 1:**  
**Total de horas del Team Member 2:**  
**Total de horas del Team Member 3:**  
**Total de horas del proyecto:** [Suma total]

#### Reflexiones sobre la experiencia

Respondan a las siguientes preguntas:

1. **Sobre el flujo de trabajo:** ¿Cómo funcionó la división de roles en su equipo? ¿Qué funcionó bien y qué fue desafiante?

2. **Sobre la colaboración:** ¿Cómo manejaron la comunicación entre roles? ¿Usaron el Query Tracker efectivamente?

3. **Sobre la tecnología:** ¿Cómo les ayudó (o no) el modelo de lenguaje entrenado en Lilt? ¿Qué aprendieron sobre trabajar con IA en traducción?

4. **Sobre el aprendizaje profesional:** ¿Qué competencias profesionales desarrollaron con este proyecto? ¿Cómo se relaciona esto con flujos de trabajo reales de traducción?

**Nombre del archivo:** `ApellidosDelMiembro1_ApellidosDelMiembro2_ApellidosDelMiembro3_Reflexion-Cambio-Climatico.docx`

### 3. Traducción final (vía Lilt)

- La traducción final se obtiene directamente de Lilt
- **No necesitan entregarla por separado**
- Asegúrense de que todos los pasos estén marcados como "Complete" en Lilt

## Verificación final antes de entregar

- [ ] Todos los pasos están marcados como completo en Lilt
- [ ] Los términos del glosario Excel han sido añadidos a su Data Source en Lilt
- [ ] Los términos en Lilt corresponden con los términos en el glosario Excel
- [ ] El glosario Excel está completo con todas las entradas requeridas (mínimo 5)
- [ ] El glosario está nombrado correctamente
- [ ] Los tiempos para cada fase están documentados para todos los miembros del equipo
- [ ] El reporte incluye reflexiones detalladas del equipo sobre el flujo de trabajo
- [ ] El reporte está nombrado correctamente
- [ ] Los archivos tienen presentación profesional sin errores de ortografía

## Entrega

**Una sola persona del equipo** sube los archivos a la plataforma del curso:

1. Glosario Excel
2. Reporte final Word

**Formato de nomenclatura:**
- Usar **primer apellido** de cada integrante, separados por guiones bajos
- **Ejemplo:** `GarcíaMartínez_López_Glosario-Cambio-Climatico.xlsx`

## Criterios de evaluación

### Puntuación total: 3 puntos

| **Componente** | **Criterio** | **Puntuación** |
|----------------|--------------|----------------|
| **Glosario** | Efectivo: Al menos 5 términos, definiciones precisas, fuentes confiables, formato correcto<br>No efectivo: Incompleto, definiciones imprecisas, fuentes inadecuadas | 1 punto<br><br>0 puntos |
| **Traducción** | Efectiva: Terminología consistente, precisión técnica, fluidez en inglés, uso adecuado de Lilt<br>No efectiva: Inconsistencias terminológicas, errores técnicos, problemas de fluidez | 1 punto<br><br>0 puntos |
| **Reporte final** | Efectivo: Documentación completa de tiempos, distribución equitativa del trabajo, reflexiones significativas y detalladas<br>Parcialmente efectivo: Documentación incompleta o reflexiones superficiales<br>No efectivo: Falta información crítica, sin reflexiones sustanciales | 1 punto<br><br>0.5 puntos<br><br>0 puntos |

---

## 📥 Descarga este Contenido
Encuentra este archivo [en nuestro repositorio](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad3/semana8/proyecto6-TradClima-ColabFlujo-Entrega.md) y descárgalo.

### 🤖 Prompts de Estudio con IAG
Copia el contenido descargado y prueba estos prompts:
- "Ayúdame a estructurar reflexiones significativas sobre mi experiencia en un proyecto de traducción colaborativa basado en estos aspectos: [describe tu experiencia]"
- "¿Cómo puedo verificar que mi glosario terminológico cumple con estándares profesionales?"
- "Analiza este registro de tiempo y ayúdame a identificar si la distribución del trabajo fue equitativa: [proporciona datos]"
- "Genera una lista de verificación final para asegurar calidad en una entrega de traducción profesional"
- "¿Qué competencias profesionales clave se desarrollan en flujos de trabajo TEP (Traducción-Edición-Corrección)?"

---

**¡Semana 8 Completa!** La próxima semana exploraremos: [Sistemas de Gestión de Calidad](../semana9/semana9-intro.md)
