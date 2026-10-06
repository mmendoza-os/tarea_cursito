---
name: bigquery-optimizado
description: Crear y optimizar consultas BigQuery seguras, coste-eficientes y reproducibles.
---
# BigQuery optimizado

## Cuándo usarla
Actívala al diseñar, revisar u optimizar SQL para BigQuery, especialmente si hay tablas grandes, particionamiento, costes o datos sensibles.

## Entradas necesarias
- Objetivo analítico, periodo, unidad de análisis y resultado esperado.
- Proyecto, dataset, tablas, esquema, claves, partición, clustering, frescura y permisos disponibles.
- Restricciones de coste, latencia, retención, zona horaria y protección de datos.

## Procedimiento
1. Confirma el esquema, la granularidad y las relaciones antes de consultar.
2. Escribe SQL parametrizado, legible y con CTEs justificados; evita `SELECT *` y joins ambiguos.
3. Filtra la columna de partición, revisa bytes procesados y estima el coste antes de ejecutar.
4. Controla duplicados, cardinalidad, zonas horarias y multiplicación de filas con conteos y sumas de control.
5. Considera clustering, tablas intermedias o materialización solo con una justificación de coste y frescura.
6. No incrustes credenciales ni expongas PII; usa el mínimo privilegio y resultados agregados.

## Salida y criterios de calidad
Entrega la consulta, parámetros, fuente, versión del esquema, controles ejecutados, coste o bytes revisados, limitaciones y pasos de reproducción. No declares que una consulta es correcta o eficiente sin evidencia de validación; señala lo que no pudo verificarse.
