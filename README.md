# Análisis de Emisiones Globales de CO2 y Modelo de Regresión Lineal

Proyecto final de análisis de datos enfocado en la exploración, limpieza, visualización y modelado predictivo de las emisiones anuales de dióxido de carbono ($CO_2$) a nivel mundial, tomando como caso de estudio principal la tendencia histórica de Colombia.

## Fuente de Datos
Los datos fueron obtenidos de la plataforma **Our World in Data**:
* **Referencia:** Hannah Ritchie and Max Roser (2020) - *"CO₂ emissions"*. Publicado en línea en [OurWorldInData.org](https://ourworldindata.org/co2-emissions).
* **Dataset:** `annual-co2-emissions-per-country.csv` (emisiones anuales de $CO_2$ por país medidas en toneladas).

## Estructura del Repositorio
* `analisis_co2.ipynb`: Jupyter Notebook con el desarrollo completo del proyecto (exploración, limpieza de entidades no nacionales y filtrado desde 1950, análisis visual y modelo de regresión lineal).
* `annual-co2-emissions-per-country.csv`: Conjunto de datos original utilizado para el análisis.
* `README.md`: Documentación general del proyecto.

## Metodología y Resultados Principales
1. **Limpieza y Preparación:** Se filtraron únicamente los registros correspondientes a países reales (código ISO de 3 letras) y se acotó la serie temporal desde 1950 hasta 2025 para garantizar consistencia estadística sin valores nulos.
2. **Análisis Exploratorio:** Se identificó una fuerte concentración global encabezada por China, Estados Unidos e India, evidenciando las brechas históricas y actuales frente a países de Latinoamérica como Brasil y Colombia.
3. **Modelo de Regresión Lineal (Colombia 1960–2025):** Se entrenó un modelo con `scikit-learn` que alcanzó un coeficiente de determinación **$R^2 = 0.9621$**, demostrando una tendencia lineal ascendente con un incremento promedio de **1,25 millones de toneladas de $CO_2$ por año**.

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.13
* **Entorno:** Jupyter Notebook
* **Librerías:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Integrantes del Grupo
* *[Nombre Completo Integrante 1]*
* *[Nombre Completo Integrante 2]*
* *[Nombre Completo Integrante 3]*
* *[Nombre Completo Integrante 4]*
