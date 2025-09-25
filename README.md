# ERER Bolivia: Estimación del Tipo de Cambio Real con Machine Learning

Este repositorio contiene el código Python para estimar el Tipo de Cambio Real de Equilibrio (ERER) en Bolivia usando modelos de machine learning (Random Forest, XGBoost, LightGBM, CatBoost) con análisis de interpretabilidad mediante SHAP y LIME, como se describe en el artículo de investigación.

## Contenido
- `ModeloFinaltipo25_09_25.ipynb`: Script Python que implementa los modelos, evaluación de métricas y análisis de SHAP/LIME.
- `nueva_base_con_rezagosfinal.xlsx` (no incluido): Dataset usado para entrenamiento y prueba (contactar al autor para acceso).
- `resultados_modelos.xlsx` (salida): Resultados con métricas, predicciones e interpretabilidad.

## Instrucciones de uso
1. Instala las dependencias: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `lightgbm`, `catboost`, `shap`, `lime`.
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm catboost shap lime

Coloca el dataset (nueva_base_con_rezagosfinal.xlsx) en la misma carpeta.
## Además
VECM con train-test split, pronósticos y métricas
 ECM (Regresión Lineal) con Train-Test, Pronósticos y Métricas
 ## Contenido
- `baseVECMfinal.xlsx` (no incluido): Dataset usado para entrenamiento y prueba (contactar al autor para acceso).
