# Taller 1 — Machine Learning Applied
## Pipelines, entrenamiento, comparación de modelos y validación cruzada — Regresión y Clasificación

**Autores:** Laura Marín, Andrés Felipe Berrío

## Descripción

Este repositorio contiene la solución al Taller 1 del curso Machine Learning Applied, aplicando el ciclo
completo de un proyecto de ML supervisado sobre dos problemas:

- **Regresión** — predicción de precios de viajes de Uber/taxi en Nueva York (`TalleRegresion.ipynb`)
- **Clasificación** — diagnóstico de enfermedad tiroidea (`TallerClasificacion_thyroid.ipynb`)

## Contenido

Cada notebook incluye: EDA y limpieza de datos, construcción de pipelines con `ColumnTransformer`,
entrenamiento y comparación de modelos (KNN, y regresión lineal/logística con regularización L1 y L2),
evaluación en train/validation/test, y optimización de hiperparámetros con `RandomizedSearchCV` y
validación cruzada K-Fold.

## Datasets

- Uber Ride Price Prediction: https://www.kaggle.com/datasets/kushsheth/uber-ride-price-prediction
- Thyroid Disease Data: https://www.kaggle.com/datasets/jainaru/thyroid-disease-data

## Cómo ejecutar

1. Clonar el repositorio.
2. Instalar dependencias: `pip install pandas numpy matplotlib seaborn scikit-learn openpyxl`
3. Descargar los datasets y ubicarlos en la misma carpeta que los notebooks.
4. Abrir y ejecutar `taller1_regresion_uber.ipynb` y `taller1_clasificacion_thyroid.ipynb` en Jupyter/Colab.
