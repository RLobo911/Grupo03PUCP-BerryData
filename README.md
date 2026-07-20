# Data Visualization with Power BI + Cloud — Proyecto Final

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI" width="50"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

## 📝 Descripción del Proyecto
Este repositorio contiene el desarrollo del proyecto final para el curso **Data Visualization with Power BI + Cloud (2026)**. En esta etapa, el proyecto ha evolucionado hacia una solución integral de Inteligencia de Negocios implementada en **Microsoft Power BI**, enfocada en la toma de decisiones estratégicas basadas en datos.

El proyecto abarca desde la concepción del caso de negocio hasta la resolución de 10 preguntas clave de asesoría mediante visualizaciones dinámicas y narración de datos.

---

## 🎯 Objetivo del Proyecto
Analizar y optimizar el porcentaje de kilogramos exportables por campaña en una empresa agroexportadora de arándanos. A través del análisis de datos, la selección de indicadores clave (KPIs) y el diseño de dashboards interactivos, se busca **incrementar en un 10% el KPI de exportabilidad** y mejorar la rentabilidad del negocio, segmentando el comportamiento por regiones y variedades.

### 💼 Caso de Negocio (Business Case)

*   **El Problema:** Al cierre de la campaña anual 25-26 (01 de mayo de 2026), el valor del *Indicador Anual de Arándanos Exportables por Campaña* de la empresa **BerryData** se situó en un **75%**, ubicándose en un nivel de eficiencia bajo (semáforo rojo). Esto representa una pérdida notable de fruta que podría colocarse en mercados internacionales de mayor valor.
*   **La Meta:** Incrementar este indicador al **85%** al cierre de la campaña 26-27 (01 de mayo de 2027), alcanzando el nivel óptimo de eficiencia (semáforo verde) y maximizando el volumen de exportación.
*   **La Estrategia:** Implementar un plan de mejora enfocado en el proceso de postcosecha que incluye:
    *   Capacitación al personal en selección y clasificación de fruta.
    *   Estandarización de criterios de calidad exportable.
    *   Optimización del manejo, cadena de frío y conservación del arándano.
    *   Seguimiento operativo constante mediante indicadores de calidad.
*   **Costo / Beneficio:** 
    *   *Costo único total de implementación:* S/ 20,000 (Soles por campaña anual).
    *   *Facturación adicional estimada:* S/ 70,000 (Soles por campaña anual al cumplir el objetivo).
    *   *Retorno Neto Estimado (ROI):* S/ 50,000 (Soles de beneficio directo).

---

## 📊 Estructura del Reporte en Power BI
El informe está estructurado en pestañas estratégicas para guiar al usuario a través del dato:

*   **Caso de Negocio:** Contexto, problemática y justificación financiera del proyecto.
*   **Indicadores:** Definición de las métricas clave y KPIs de rendimiento.
*   **Dashboard:** Panel principal interactivo con la situación macro de la operación.
*   **Reporte Detallado:** 
    *   *Detalle Región:* Análisis geoespacial y rendimiento por zona productiva.
    *   *Detalle Variedad:* Comportamiento y calidad según el tipo de arándano.
*   **Sección de Asesoría (Preguntas 1 a 10):** Respuestas analíticas a los 10 requerimientos críticos planteados en la asesoría del negocio.

---

## 🗄️ Modelo de Datos (Data Model)
El proyecto cuenta con un modelo relacional diseñado para analizar el rendimiento de la fruta desde las etapas de cultivo hasta su clasificación final en las líneas de empaque. 

### 📐 Arquitectura del Modelo
El diseño combina tablas de hechos centrales asociadas a dimensiones de negocio organizadas para optimizar las consultas analíticas:

*   **Núcleo de Operaciones y Calidad:** La tabla `G3 LOTE` funciona como nexo principal, conectando el origen agrícola (`G3 PRODUCCION`) con los resultados de inspección (`G3 METRICA_KILOGRAMO`).
*   **Gestión de Producción y Variedades:** Vincula el lote con las tablas `G3 CAMPANA` y `G3 VARIEDAD` para evaluar el rendimiento genético e histórico por temporada.
*   **Dimensión Temporal y Geográfica:** Mapeo continuo a través de `G3 CALENDARIO` y segmentación espacial mediante `G3 REGION` para identificar oportunidades geográficas.
*   **Control de Planta y Personal:** Relación detallada entre `G3 LINEA_EMPAQUE`, `G3 PLANTA` y la asignación operativa de supervisores y operarios a través de `G3 TRABAJADOR_LINEA` y `G3 TRABAJADOR`.

> [!NOTE]
> *Todas las relaciones mantienen una dirección de filtrado óptima, asegurando la integridad analítica al cruzar variables climáticas, operativas y de calidad.*

---

## 🛠️ Herramientas Utilizadas
*   **Microsoft Power BI:** Modelado de datos (DAX), ETL (Power Query) y diseño de la interfaz interactiva.
*   **Microsoft Excel:** Procesamiento inicial y almacenamiento de las bases de datos origen.
*   **GitHub Pages:** Despliegue estático y presentación del portafolio del proyecto.

---

## 👥 Integrantes (Grupo 3)
*   Jairo Corimanya Seminario
*   Aarón Luque Cherres
*   Fabiola Vallejos
*   Rodrigo Lovera

---

## 🚀 ¿Cómo visualizar el proyecto?
> [!TIP]
> Puedes interactuar directamente con la presentación y los resultados de este proyecto visitando nuestra **[Página de GitHub Pages](AQUÍ_VA_EL_LINK_DE_TU_PÁGINA)**.
