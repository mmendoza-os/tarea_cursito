---
name: exploracion-calidad
description: Guiar exploración, perfilado, limpieza y validación reproducible de datos.
---
# Exploración y calidad de datos

## Cuándo usarla
Actívala al iniciar un análisis, investigar discrepancias, preparar una limpieza o evaluar si un conjunto de datos es apto para una métrica o informe.

## Entradas necesarias
- Pregunta de negocio, unidad de análisis, población, periodo y criterio de éxito.
- Fuentes, esquema, granularidad, claves, propietario, fecha de actualización y restricciones de acceso.
- Reglas de negocio conocidas y tolerancias aceptables para la calidad.

## Procedimiento
1. Reformula el objetivo y pide aclaraciones si falta información crítica.
2. Perfila tipos, nulos, duplicados, unicidad, cardinalidad, rangos, distribuciones, outliers, fechas y consistencia entre tablas.
3. Contrasta los resultados con reglas de negocio, totales de control, muestras y relaciones esperadas.
4. Propón cada limpieza o transformación con regla, impacto en el denominador, excepciones y posibilidad de reversión.
5. Revisa sesgo de selección, fuga de información, datos faltantes y cambios de granularidad antes de concluir.

## Salida y criterios de calidad
Entrega un perfil reproducible, hallazgos priorizados, reglas aplicadas o propuestas, controles, decisiones pendientes, limitaciones y pasos de ejecución. Separa hechos observados, cálculos, inferencias e hipótesis; no inventes valores ni declares calidad sin evidencia.
