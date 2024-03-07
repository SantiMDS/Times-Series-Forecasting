# Exploración de Métodos de Forecasting de Ventas

## Objetivo del Proyecto
Nuestro objetivo es explorar diferentes métodos para realizar forecasting de ventas. Analizamos enfoques tradicionales como ARIMA y SARIMA, así como métodos de machine learning como XGBoost, CatBoost y KNN aplicados al forecasting. Dividimos el proyecto en varias etapas que incluyen limpieza y preprocesamiento de datos, análisis exploratorio de datos (EDA), aplicación de métodos de predicción clásicos y modernos, y finalmente, la interpretación de resultados utilizando herramientas como SHAP.

## Etapas del Proyecto

### 1. Limpieza y Preprocesamiento de Datos
En esta fase, realizamos la limpieza de datos eliminando gastos y albaranes de venta cancelados. Analizamos los productos más vendidos, principales clientes, productos más vendidos por clientes y la distribución geográfica de las ventas.

### 2. Análisis Exploratorio de Datos (EDA)
Analizamos las ventas a nivel mensual, semanal y diario para identificar patrones y tendencias en la serie temporal anual. Aplicamos la descomposición temporal para examinar la tendencia y estacionalidad, realizamos el test Dickey-Fuller y analizamos los gráficos de autocorrelación y autocorrelación parcial para verificar la estacionariedad de la serie. Utilizamos modelos SARIMAX para encontrar el mejor ajuste.

### 3. Modelos de Machine Learning
Construimos modelos de machine learning utilizando un workflow típico de ML. Desarrollamos tres modelos baseline y realizamos mediciones para evaluar su desempeño. Utilizamos transformadores para mejorar las mediciones y seleccionamos el mejor modelo para ajustar hiperparámetros y mejorar su rendimiento.

### 4. Interpretación de Resultados
Utilizamos SHAP para identificar las características más influyentes en el modelo final. Presentamos conclusiones y discutimos las limitaciones del estudio, así como posibles mejoras para futuras investigaciones.

## Resultados Esperados
Esperamos obtener modelos de forecasting de ventas que sean capaces de predecir con precisión las ventas futuras. Además, esperamos identificar qué características tienen mayor impacto en el modelo de machine learning, lo que proporcionará información valiosa para la toma de decisiones empresariales.

## Conclusiones
Este proyecto proporciona una comprensión profunda de los métodos de forecasting de ventas, desde enfoques tradicionales hasta técnicas más avanzadas de machine learning. Los resultados y conclusiones obtenidos sirven como base para futuras investigaciones y mejoras en la predicción de ventas.
