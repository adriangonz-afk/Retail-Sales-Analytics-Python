# Retail Sales Data Analysis & Executive Dashboard

## Executive Summary
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre más de 420,000 registros de ventas retail con el objetivo de optimizar inventarios y estrategias comerciales. Se aplicaron técnicas de limpieza de datos, transformación de fechas y análisis estadístico en Python para detectar ineficiencias, y se desarrolló un Dashboard en Power BI para el monitoreo interactivo de KPIs comerciales y desviaciones de ventas.

**Impacto destacado:** El análisis de Pareto reveló que solo 28 de 81 departamentos (34%) generan el 80% de las ventas totales, lo que sugiere la necesidad de una reestructuración de inventarios priorizando los departamentos de alto rendimiento ("Vital Few").

## Power BI Executive Dashboard
*Herramienta interactiva para la detección de desviaciones diarias y análisis de cross-selling.*

<div align="center">
  <video src="./dashboard/dashboard.mp4" width="100%" controls autoplay loop></video>
</div>

*(Si el video no se reproduce automáticamente, [haz clic aquí para verlo](./dashboard/dashboard.mp4))*

## Tech Stack
* **Business Intelligence:** Power BI (DAX, Power Query, Data Modeling)
* **Lenguaje:** Python 3.10
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn
* **Datos:** [Walmart Retail Dataset (Kaggle)](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)

##  Key Insights & Visualizations

### 1. Principio de Pareto (80/20) en Departamentos
Se detectó una concentración crítica de ingresos. Los departamentos clave deben ser priorizados en gestión de stock y marketing, mientras que los de bajo rendimiento requieren revisión de viabilidad.

### 2. Estacionalidad Marcada
El análisis de series temporales reveló picos masivos de ventas en las semanas 46-52 (festividades de fin de año). Se observó una ligera caída interanual entre 2010 y 2012 que requiere atención estratégica para frenar el descenso.

### 3. Impacto de Promociones
Se evaluó la correlación entre el `TotalMarkdown` y el volumen de ventas. Las semanas con promociones agresivas mostraron una mediana de ventas menor en ciertos segmentos, sugiriendo una posible canibalización de márgenes que debe ser optimizada.

##  How to Run
1. Clonar el repositorio.
2. **Para el Análisis en Python:** Instalar dependencias (`pip install pandas numpy matplotlib seaborn`) y ejecutar el notebook `PROYECTO_RETAIL_DATA.ipynb`.
3. **Para el Dashboard:** Abrir el archivo `.pbix` (ubicado en la carpeta del repositorio) utilizando Power BI Desktop.
