---
inclusion: fileMatch
fileMatchPattern: "**/*.{sql,bq}"
---
# BigQuery

- Escribir SQL legible, con nombres explícitos, CTEs justificados, parámetros y filtros de fecha; evitar `SELECT *` en producción.
- Aprovechar particionado y clustering filtrando la columna de partición; revisar bytes procesados, costes, plan y necesidad de materialización.
- Validar tipos, zona horaria, duplicados, joins many-to-many, granularidad y riesgo de multiplicar filas; conservar controles de conteo y sumas.
- No incrustar credenciales ni datos sensibles. Documentar proyecto, dataset, tablas, permisos, frescura, retención, dependencias y versión del esquema.
- Comparar resultados con totales de control y comunicar límites de frescura, cobertura y coste antes de publicar.
