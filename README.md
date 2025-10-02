# Proyecto TB1 — Comprensión de Datos  

## Tema elegido  
**Predicción del éxito comercial de videojuegos** usando el dataset de *Video Game Sales (Kaggle)*, que contiene información histórica de títulos, plataforma, género, editor, año de lanzamiento, rating y ventas regionales/globales.  

## Problema a resolver  
Identificar qué características (género, plataforma, año, etc.) están más asociadas al **éxito en ventas** y construir un **target binario** que clasifique un videojuego como **ventas altas o bajas** (definidas por estar en el 25% superior de `Global_Sales`).  
Este análisis busca explorar los factores que influyen en el desempeño comercial y sentar la base para un modelo predictivo.  

## Roles asignados  
*(Trabajo individual: una sola persona asume todos los roles, pero se definen para claridad de responsabilidades)*  

- **Project Lead**  
  - Planificación del proyecto, integración de entregables y redacción del informe final.  

- **Data Engineer**  
  - Adquisición del dataset (Kaggle), validación del esquema, carga inicial de datos, detección y limpieza de valores faltantes, duplicados y tipos de datos.  

- **Data Analyst**  
  - Exploratory Data Analysis (EDA): estadísticas descriptivas, detección de outliers, generación de visualizaciones, interpretación de hallazgos.  

- **Data Scientist**  
  - Definición de la variable objetivo (ventas altas vs bajas), preparación de un baseline de clasificación, y propuesta de métricas para evaluar el modelo en etapas posteriores.  

---

## Dataset  
- **Fuente:** [Kaggle — Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)  
- **Archivo esperado:** `data/vgsales.csv`  
- **Variables clave:** `Platform`, `Genre`, `Publisher`, `Year_of_Release`, `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`, `Rating`.  

## Estructura de carpetas propuesta  

