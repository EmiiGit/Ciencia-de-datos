# Análisis y clasificación de semillas de trigo

Este proyecto consiste en un análisis exploratorio y la construcción de modelos de clasificación supervisada para identificar variedades de trigo a partir de características morfológicas de las semillas.

El dataset utilizado (Seeds Dataset - UCI) contiene mediciones físicas de semillas pertenecientes a tres variedades: Kama, Rosa y Canadian.

El objetivo principal es evaluar si las variables morfológicas permiten distinguir correctamente entre las variedades y comparar el desempeño de distintos modelos predictivos.

## Metodología

Se realiza un análisis completo en R que incluye:

- Análisis exploratorio de datos (distribuciones, outliers y correlaciones)
- Visualización de relaciones entre variables
- Modelos de clasificación:
  - Árbol de decisión (CART)
  - Validación cruzada (5-Fold)
  - Random Forest
  - Gradient Boosting Machine (GBM)

## Objetivo
- Clasificar variedades de trigo usando variables físicas de las semillas
- Comparar el rendimiento de distintos modelos de machine learning
- Identificar las variables más importantes en la clasificación

## Resultados

Los modelos de ensamble (Random Forest y Boosting) alcanzan los mejores resultados de precisión, superando al árbol de decisión simple. Las variables más relevantes para la clasificación son las relacionadas con el tamaño del grano, como `area`, `perimeter` y `groove_length`.

## Conclusión

Las características morfológicas de las semillas permiten una clasificación altamente precisa de las variedades de trigo. Los métodos basados en árboles muestran un buen equilibrio entre interpretabilidad y poder predictivo.
