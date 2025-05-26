# Predicción del precio de viviendas con redes neuronales

## Objetivo
Desarrollar un modelo de red neuronal capaz de predecir el precio de viviendas a partir de características como número de habitaciones, ubicación, ingresos de la zona, entre otros, utilizando el dataset `housing.csv`.

## Metodología
- Limpieza y preprocesamiento de datos (eliminación de columnas categóricas, imputación de NaNs).
- Estandarización con `StandardScaler`.
- Entrenamiento de una red neuronal con `Keras` y `TensorFlow`.
- Evaluación del modelo con `MAE` (Mean Absolute Error).

## Resultados
- **MAE final**: 36,519.64 dólares
- Se generaron gráficos comparativos entre valores reales y predichos, así como métricas de evaluación.

## Conclusiones
- El modelo presenta un error moderado, lo que indica que aprendió patrones útiles.
- Se podrían aplicar mejoras mediante el uso de más datos, otras variables categóricas y técnicas avanzadas.
