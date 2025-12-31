# Retail Sales Data Analysis & Optimization

## Executive Summary
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre más de 420,000 registros de ventas retail con el objetivo de optimizar inventarios y estrategias comerciales. Se aplicaron técnicas de limpieza de datos, transformación de fechas y análisis estadístico para detectar ineficiencias y patrones de consumo.

**Impacto destacado:** El análisis de Pareto reveló que solo **28 de 81 departamentos (34%)** generan el **80% de las ventas totales**, lo que sugiere la necesidad de una reestructuración de inventarios priorizando los departamentos de alto rendimiento ("Vital Few").

## Tech Stack
* **Lenguaje:** Python 3.10
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn
* **Datos:** [Walmart Retail Dataset (Kaggle)](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)

## Key Insights & Visualizations

### 1. Principio de Pareto (80/20) en Departamentos
Se detectó una concentración crítica de ingresos. Los departamentos clave deben ser priorizados en gestión de stock y marketing, mientras que los de bajo rendimiento requieren revisión de viabilidad.

### 2. Estacionalidad Marcada
El análisis de series temporales reveló picos masivos de ventas en las semanas 46-52 (festividades de fin de año). Se observó una ligera caída interanual entre 2010 y 2012 que requiere atención estratégica para frenar el descenso.

### 3. Impacto de Promociones
Se evaluó la correlación entre el `TotalMarkdown` y el volumen de ventas. Las semanas con promociones agresivas mostraron una mediana de ventas menor en ciertos segmentos, sugiriendo una posible canibalización de márgenes que debe ser optimizada.

## How to Run
1.  Clonar el repositorio.
2.  Instalar dependencias: `pip install pandas numpy matplotlib seaborn`
3.  Ejecutar el notebook `PROYECTO_RETAIL_DATA.ipynb`.
