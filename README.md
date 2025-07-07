# Demanda-Taxis

## Predicción de Demanda de Taxis por Hora – Sweet Lift Taxi

Sweet Lift Taxi, una compañía de transporte en aeropuertos, necesita anticipar la cantidad de pedidos de taxis por hora para atraer a más conductores durante las horas pico. Para ello, se debe construir un modelo de machine learning que prediga el número de pedidos para la hora siguiente, con una métrica de error RMSE ≤ 48 en el conjunto de prueba.

 Objetivo
Construir y evaluar modelos de regresión que permitan predecir con precisión el número de pedidos de taxis por hora, utilizando datos históricos, y seleccionando el modelo más preciso y eficiente.
Librerías de Python

•	Pandas: para la manipulación y análisis de datos tabulares
•	NumPy: operaciones numéricas eficientes
•	Matplotlib & Seaborn: visualización de datos (gráficas de líneas y dispersión)
•	Scikit-learn:



XGBoost fue el modelo más eficaz, con un RMSE de 26.07, muy por debajo del límite exigido (48).
•	La incorporación de características temporales (hour, day_of_week, lags) mejoró significativamente la calidad predictiva.
•	El Árbol de Decisión fue más rápido pero menos preciso.
•	La visualización final evidenció que XGBoost se ajusta mejor a los valores reales, sin sobreajuste ni alta varianza.

