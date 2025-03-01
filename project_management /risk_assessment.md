# ⚠️ Evaluación de Riesgos
## Descripción
En este documento se identifican los posibles riesgos que podrían afectar el éxito del proyecto.
Debe incluir:
- **Identificación de riesgos**: Problemas técnicos, organizacionales, financieros, etc.
- **Impacto**: Evaluación de cómo afectaría el proyecto cada riesgo.
- **Plan de mitigación**: Acciones preventivas y reactivas ante cada riesgo identificado.


# Identificación de Riesgos

## Tipo de Riesgo
| Tipo de Riesgo           | Descripción |
|--------------------------|-------------|
| Calidad de los datos     | Datos con errores, registros incompletos, problemas de codificación (ej., caracteres especiales como "ñ" y tildes). |
| Problemas técnicos       | Fallos en la infraestructura, errores en la ejecución del pipeline ETL, incompatibilidades con herramientas como Python y Power BI. |
| Disponibilidad del equipo | Carga de trabajo excesiva, falta de recursos humanos o retrasos en la asignación de tareas clave. |
| Cumplimiento normativo   | Posibles incumplimientos con la Ley 1581 de 2012 sobre protección de datos personales en Colombia. |
| Restricciones financieras | Falta de presupuesto para herramientas, almacenamiento en la nube o licencias necesarias. |
| Retrasos en el cronograma | Problemas en la planificación, cambios en los requisitos del cliente o demoras en la entrega de reportes y modelos. |

---

## Impacto de los Riesgos
| Riesgo                   | Probabilidad | Impacto | Descripción del Impacto |
|--------------------------|-------------|---------|--------------------------|
| Calidad de los datos     | Alta        | Alta    | Datos inconsistentes pueden afectar la precisión del modelo de regresión. |
| Problemas técnicos       | Media       | Alta    | Fallos en el pipeline pueden retrasar la disponibilidad de los datos procesados. |
| Disponibilidad del equipo | Media      | Media   | Retrasos en la ejecución de tareas por falta de personal o sobrecarga de trabajo. |
| Cumplimiento normativo   | Baja        | Alta    | Incumplimientos pueden generar sanciones legales y afectar la reputación del proyecto. |
| Restricciones financieras | Baja        | Media   | Falta de recursos podría limitar la capacidad de procesamiento o almacenamiento de datos. |
| Retrasos en el cronograma | Media       | Alta    | Demoras en la entrega de resultados pueden afectar la toma de decisiones gerenciales. |

---

## Plan de Mitigación
| Riesgo                   | Acciones Preventivas | Acciones Reactivas |
|--------------------------|----------------------|---------------------|
| Calidad de los datos     | Implementar reglas de validación y limpieza en la fase de preprocesamiento. | Revisar manualmente los datos críticos y ajustar el pipeline. |
| Problemas técnicos       | Configurar alertas y monitoreo en el pipeline de datos. | Escalar problemas al equipo de infraestructura para solución rápida. |
| Disponibilidad del equipo | Asignación de tareas balanceada y reuniones de seguimiento. | Redistribuir tareas entre el equipo en caso de ausencias. |
| Cumplimiento normativo   | Asegurar la anonimización de datos desde la ingesta. | Implementar auditorías de datos y corregir fallos de seguridad. |
| Restricciones financieras | Optimizar costos en herramientas y almacenamiento. | Buscar alternativas gratuitas o financiamiento adicional. |
| Retrasos en el cronograma | Establecer buffers de tiempo en el cronograma. | Repriorizar tareas críticas y optimizar flujos de trabajo. |
