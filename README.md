# 🦟 Dengue EDA — Caquetá, Colombia (2018–2023)

![Python](https://img.shields.io/badge/Python-3.14-blue)
![pandas](https://img.shields.io/badge/pandas-2.0-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview
Exploratory Data Analysis (EDA) of dengue fever cases reported 
in the department of Caquetá, Colombia, covering the period 
from 2018 to 2023.

**Descripción:** Análisis exploratorio de casos de dengue en 
Caquetá, Colombia. Se identificaron patrones estacionales, 
tendencias anuales y distribución geográfica por municipio 
usando Python y visualizaciones interactivas.

## Objectives
- Identify temporal patterns in dengue cases
- Analyze geographic distribution across 17 municipalities
- Visualize trends over a 6-year period

## Key Findings
- **2020 and 2023** recorded the highest number of cases
- **February** is the peak month, linked to rainy season patterns
- **Florencia** (capital city) concentrates the most cases
- All 17 municipalities show active reporting

## Tech Stack
| Tool | Purpose |
|------|---------|
| Python 3.14 | Main language |
| pandas | Data cleaning & analysis |
| matplotlib | Data visualization |
| seaborn | Statistical plots |
| Jupyter Notebook | Interactive analysis |

## Project Structure
```
dengue-eda-colombia/
├── data/
│   ├── data_dengue.csv          ← raw dataset
│   └── data_dengue_limpio.csv   ← cleaned dataset
├── notebooks/
│   └── analisis.ipynb           ← main analysis
├── outputs/
│   ├── casos_por_anio.png
│   ├── casos_por_mes.png
│   ├── casos_por_municipio.png
│   └── tendencia_mensual.png
└── README.md
```

## Visualizations
- Cases by year
- Cases by month
- Cases by municipality
- Monthly trend 2018–2023

## Data Source
[datos.gov.co](https://www.datos.gov.co) — 
Instituto Nacional de Salud (INS)  
**Dataset:** 6,808 records | 16 variables | 17 municipalities

## 👩‍💻 Author
**Kelly Valentina**  
