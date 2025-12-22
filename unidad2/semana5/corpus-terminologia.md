---
layout: default
title: Corpus y Terminología
parent: Semana 5
grand_parent: Unidad 2
nav_order: 2
---

# Corpus y Terminología en Traducción Técnica

## Introducción

Los corpus especializados y la gestión terminológica son herramientas fundamentales para profesionales de la traducción. En el contexto de textos técnicos sobre IAG, estas herramientas nos permiten identificar patrones lingüísticos, extraer terminología consistente y garantizar la calidad de nuestras traducciones.

## ¿Qué es un Corpus?

Un **corpus** (plural en inglés: **corpora**) es una colección de textos organizados y digitalizados que representan el uso real de una lengua en un dominio específico. En traducción técnica, utilizamos principalmente **corpus especializados** que contienen textos de un campo particular, como inteligencia artificial generativa.

### Tipos de Corpora Relevantes para Traducción

| **Tipo** | **Descripción** | **Uso en Traducción** |
|----------|-----------------|----------------------|
| **Corpus monolingüe especializado** | Textos en una lengua sobre un tema específico | Investigación terminológica y patrones lingüísticos |
| **Corpus bilingüe/paralelo** | Textos originales y sus traducciones | Identificación de equivalencias y patrones de traducción |
| **Corpus comparable** | Textos similares en dos lenguas (no traducciones) | Análisis contrastivo y validación terminológica |

## Gestión de Corpus para Traducción

### Criterios de Calidad para Corpus Especializados

Para crear un corpus útil para traducción técnica, considera:

**Tamaño mínimo**: 100,000 palabras para obtener resultados significativos

**Criterios de inclusión**:
- Tipo de texto (artículos académicos, documentación técnica, manuales)
- Dominio específico (ej: IAG, aprendizaje automático)
- Autoría experta (profesionales del campo, no traducciones)
- Audiencia especializada
- Fecha de publicación (preferiblemente reciente para campos en evolución)
- Idioma original (evitar traducciones para reducir interferencias)

### Sistema de Calificación de Confiabilidad

| **Estrellas** | **Autor confiable** | **Publicación confiable** |
|----------|-----------------|----------------------|
| Sin estrellas | Autor no validado | Publicación no validada  |
| ★ | Experto en la materia, pero no hablante nativo del idioma del corpus | Publicación aprobada con procesos de revisión no verificables |
| ★★ | Experto en la materia Y hablante nativo del idioma del corpus | Publicación aprobada con procesos de revisión verificables |

## Extracción Automática de Terminología

### Cómo Funciona la Extracción Automática

La extracción automática combina dos tipos de información:

**1. Información lingüística**: Patrones de formación de términos típicos en cada idioma
- Inglés: noun, adjective + noun, noun + of + noun
- Español: sustantivo, adjetivo + sustantivo, sustantivo + de + sustantivo

**2. Información estadística**: Frecuencia de palabras individuales y compuestas que siguen estos patrones

### Problemas Comunes en Extracción Automática

**Ruido** (sobre-generación):
- Palabras que aparecen juntas frecuentemente pero no son términos
- Ejemplo: "they are", "when you", "the first"

**Silencio** (sub-generación):
- Términos reales que no aparecen en la lista por baja frecuencia
- Ejemplo: "heart and lung disease" donde "heart disease" no se detecta como término individual

**Otros problemas**:
- Variaciones ortográficas y de capitalización
- Límites de términos imprecisos
- Números y abreviaciones

### Mejorando la Extracción con Listas de Exclusión

Las **listas de exclusión (stop lists)** contienen palabras muy comunes que se excluyen de los resultados:
- Preposiciones, artículos, conjunciones
- Ventaja: Lista más manejable de candidatos a términos
- Desventaja: Puede excluir términos válidos (ej: "internet of things")

## Validación Humana de Términos

### Estrategias de Validación

**1. Extracción de definiciones**
Busca patrones como:
- "[término] es..." / "[term] is..."
- "[término] se compone de..." / "[term] consists of..."
- "[término] se define como..." / "[term] is defined as..."

**2. Análisis de frecuencia relativa**
Compara la frecuencia del término en:
- Corpus especializado vs. corpus general
- Si es más frecuente en el corpus especializado = probable término

**3. Validación por frecuencia**
- Los términos deben ser usados por múltiples expertos
- Variaciones ortográficas: la más frecuente se considera principal
- Términos con uso inconsistente pueden ser neologismos o estar obsoletos

## Práctica con Sketch Engine

### Actividad: Extracción Terminológica Práctica

**Corpus de práctica proporcionado** (disponible en Teams)
- 12 documentos en inglés sobre IAG
- 12 documentos en español sobre IAG
- Aproximadamente 20,000 palabras total

**Pasos a seguir**

1. **Acceso a [Sketch Engine](https://www.sketchengine.eu)**
   - Regístrate para obtener una cuenta gratuita (30 días)
   - Descarga el corpus bilingüe proporcionado

2. **Creación de corpus**
   - Crear un corpus para el español y un corpus para el inglés
   - Sube los documentos a Sketch Engine
   - Configura como corpus especializado de IAG

4. **Extracción de términos**
   - Utiliza la función "Keywords" para extracción automática
   - Aplica listas de exclusión apropiadas
   - Examina tanto términos simples como compuestos

5. **Análisis y validación**
   - Identifica candidatos a términos relevantes
   - Verifica contextos de uso
   - Compara frecuencias entre lenguas

**Guía de trabajo**: Consulta [Automatic Terminology Extraction with Sketch Engine](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad2/semana5/referencias/AutoTermExtractionWithSketchEngine.pdf) para instrucciones detalladas.

## Aplicación Práctica para Estudiantes

### Desarrollando tu Proceso de Investigación Terminológica

**Para proyectos de traducción técnica**:

1. **Antes de traducir**:
   - Identifica el dominio específico del texto
   - Busca corpus especializados existentes
   - Crea un glosario preliminar de términos clave

2. **Durante la traducción**:
   - Consulta tu glosario para mantener consistencia
   - Documenta términos nuevos que encuentres
   - Verifica equivalencias en corpus comparables

3. **Después de traducir**:
   - Revisa consistencia terminológica
   - Actualiza tu glosario personal
   - Guarda recursos útiles para futuros proyectos

### Construyendo Recursos Personales

**Glosarios especializados**:
- Organiza por campo temático (IAG, medicina, legal, etc.)
- Incluye contextos de uso y fuentes
- Actualiza regularmente con nuevos términos

**Corpus personales**:
- Recopila textos de calidad en tus áreas de especialización
- Organiza por tipo de documento y audiencia
- Mantén criterios de calidad consistentes

## Reflexión y Desarrollo Profesional

### Preguntas para Considerar

1. **Investigación eficiente**: ¿Cómo puedes desarrollar un proceso sistemático para investigar terminología antes de cada proyecto?

2. **Gestión de recursos**: ¿Qué estrategias puedes implementar para organizar y mantener tus recursos terminológicos actualizados?

3. **Calidad vs. cantidad**: ¿Cómo equilibras la exhaustividad en la investigación terminológica con los plazos de entrega?

4. **Colaboración profesional**: ¿Cómo puedes aprovechar redes profesionales para validar terminología especializada?

5. **Tecnología emergente**: ¿Qué desafíos específicos presenta la traducción de campos en rápida evolución como la IAG?

---

## 📥 Descarga este Contenido

Encuentra este archivo [en nuestro repositorio](https://github.com/alainamb/uic_tr18-trad-inversa-es-en/blob/main/unidad2/semana5/corpus-terminologia.md) y descárgalo.

### 🤖 Prompts de Estudio con IAG
Copia el contenido descargado y prueba estos prompts:
- "Ayúdame a crear un proceso sistemático para investigar terminología especializada usando corpus"
- "¿Cuáles son los mejores criterios para evaluar la calidad de un corpus especializado en [tu área de interés]?"
- "Crea una plantilla para documentar y organizar terminología extraída de corpus especializados"
- "¿Cómo puedo mantener actualizada mi investigación terminológica en campos que evolucionan rápidamente?"
- "Explica las ventajas y limitaciones de la extracción automática vs. manual de terminología"

---

**Siguiente:** [Proyecto Texto 4](./proyecto-texto4.md)
