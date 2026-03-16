## ?? Business Value

Este dashboard fue desarrollado utilizando **Excel como herramienta de Business Intelligence**, con el objetivo de transformar datos transaccionales en **reportes interactivos para análisis de desempeño del negocio**.

El dashboard permite:

- ?? **Analizar tendencias de ventas, utilidad y margen**
- ?? **Identificar regiones, productos y segmentos más rentables**
- ?? **Monitorear crecimiento interanual (YoY)** para evaluar desempeño
- ?? **Explorar datos mediante filtros interactivos y segmentaciones**
- ?? **Comparar métricas actuales vs. años anteriores** para identificar variaciones de negocio

El objetivo es facilitar **análisis descriptivo y monitoreo de KPIs clave**, utilizando **Excel como plataforma de reporting interactivo**.

---

## ?? Data Preparation (Power Query)

Se implementó un proceso de **ETL utilizando Power Query** para preparar los datos antes del análisis.

Este proceso incluyó:

- **Limpieza y estandarización de datos**
- **Corrección de formatos numéricos y monetarios**
- **Eliminación de duplicados**
- **Transformaciones de columnas**
- **Merges entre tablas**
- **Creación de claves auxiliares** para soportar el modelo analítico

Adicionalmente, se creó una **tabla calendario (`DimCalendar`)** para permitir **análisis temporal y cálculos de crecimiento interanual**.

Este proceso permitió estructurar los datos de forma adecuada para **análisis analítico mediante tablas dinámicas y el modelo de datos de Excel**.

---

## ?? Advanced Excel Analysis

El análisis fue desarrollado utilizando **funcionalidades avanzadas de Excel orientadas a reporting y análisis multidimensional de datos**.

Entre las principales técnicas utilizadas:

- **Pivot Tables (Tablas Dinámicas)** para análisis multidimensional  
- **Pivot Charts** para visualización de tendencias  
- **Slicers** para filtrado interactivo de los reportes  
- **Excel Data Model** para gestionar relaciones entre múltiples tablas  
- **Creación de KPIs dinámicos** mediante campos calculados y medidas  

Se desarrollaron **indicadores tipo KPI cards** avanzados, incluyendo:

- **indicadores de desempeño**
- **flechas dinámicas de tendencia**
- **formato condicional visual (verde / rojo)**

Estas tarjetas se construyeron mediante:

- **columnas auxiliares**
- **cuadros de texto dinámicos**
- **símbolos tipográficos** para representar tendencias

Esto permite crear **indicadores visuales interactivos similares a dashboards de BI**.

También se implementaron **técnicas avanzadas de visualización**, incluyendo:

- **formateo avanzado de gráficos**
- **control de ordenamiento dinámico de categorías**
- **adaptación de gráficos para cumplir con diseños específicos de dashboard**

---

### ?? Métricas analizadas

Las métricas analizadas incluyen **indicadores clave de desempeño**:

- **Total Sales**
- **Total Profit**
- **Orders**
- **Gross Margin**
- **Year-over-Year Growth**

Para el análisis interanual se implementaron **cálculos de comparación contra el año anterior**, manejando escenarios donde **no existen datos históricos**, mediante validaciones que evitan errores en las métricas.

---

## ?? Data Model

Se implementó un **modelo dimensional tipo Star Schema** dentro del **Excel Data Model**, permitiendo realizar análisis desde múltiples dimensiones del negocio.

### Estructura del modelo

- **FactSales** – métricas transaccionales  
- **DimCustomer**
- **DimProduct**
- **DimGeography**
- **DimShipMode**
- **DimCalendar**

Este modelo permite:

- **analizar métricas desde diferentes dimensiones**
- **optimizar cálculos analíticos**
- **soportar análisis temporal y comparaciones interanuales**

Durante el desarrollo se comprendió también el funcionamiento del **Pivot Cache**, lo cual es clave para entender cómo **múltiples tablas dinámicas pueden compartir el mismo origen y afectar la interacción entre reportes**.

---

## ?? Skills Demonstrated

- **Advanced Excel for Data Analysis**
- **Pivot Tables & Pivot Charts**
- **Interactive Dashboards in Excel**
- **Slicers for Dynamic Filtering**
- **Excel Data Model**
- **Power Query (ETL & Data Transformation)**
- **Dimensional Data Modeling (Star Schema)**
- **KPI Design & Performance Indicators**
- **Advanced Chart Formatting**
- **Data Cleaning & Data Preparation**
- **Business Intelligence Reporting**
- **Analytical Problem Solving**
