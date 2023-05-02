# Predicción de Ataques Cerebrales

## Autores
1. Kevin Andrade
2. Nicolás Boada
3. Emilio Clavón

## Descripción
Este proyecto consiste en un caso práctico de análisis de datos de una base de datos púbica de un hospital, de la cual se pretende predecir la presencia o no de ataques cerebrales en pacientes con diferentes condiciones, mediante la implementación de varios modelos de clasificación de Machine Learning.
Para ello se hace un correcto análisis exploratorio de los datos (EDA), en el cual se comprende la base de datos y se procede a realizar el respectivo preprocesamiento de datos para tener una base de datos limpia y lista para entrenar varios modelos. Se aplicaron técnicas de imputación de valores atípicos y nulos, específicamente con KNN Imputer.
Además se implementó la mejor técnica de balanceo de clases (SMOTETomek) para garantizar buenos resultados.
Finalmente, se probaron 4 algoritmos de clasificación: Regresión Logística, KNN, Random Forest y Gradient Boosting. De los cuales, se analizó la métrica de recall_score para seleccionar el mejor modelo, y se obtubo que la Regresión Lógistica es el mejor aunque se trate de un modelo simple. Además se aplicó un Random Forest para identificar las variables más importantes en el modelo.

## Archivo
En el archivo Prediccion_Ataques_cerebrales.ipynb se encuentra el código completo creado para este proyecto
