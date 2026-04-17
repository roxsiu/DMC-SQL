# DMC-SQL: Análisis de Horas Extras

Este proyecto presenta una solución integral para el control y análisis de horas extras, resolviendo la fragmentación de datos mediante un flujo ETL robusto y visualización estratégica.

## Tecnologías
* **SQL Server:** Modelado dimensional (esquemas STG/ODS), limpieza de datos y creación de vistas analíticas.
* **Power BI:** Creación de dashboards interactivos con medidas DAX para seguimiento de KPIs.
* **Análisis de Negocio:** Centralización de fuentes (Planillas y Maestros) para la toma de decisiones.

## Alcance Técnico
* **Procesamiento ETL:** Transformación de archivos Excel dispersos hacia una base de datos relacional.
* **Arquitectura:** Diseño de esquema estrella con tablas de dimensiones (Personal, Sede, Reclutamiento) y tablas de hechos (Horas Extras y Metas).
* **Insights:** Identificación de sobrecostos y cumplimiento de metas mensuales.

## Contenido del Repositorio
* **[Presentación Ejecutiva (PDF)](./DMC-HorasExtras.pdf):** Metodología y hallazgos clave.
* **[Scripts SQL](./Analisis_Horas_Extras.sql):** Lógica completa de creación de tablas, esquemas y transformaciones.
* **[Dashboard Power BI](./screenshot_pbi.png):** Visualización de los indicadores clave.

---
*Proyecto desarrollado como parte de la formación SQL Server for Analytics de DMC.*
