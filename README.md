# Actividad 6 · Predicción de precios de vivienda · Equipo 12

Maestría en Inteligencia Artificial Aplicada · Tecnológico de Monterrey
Inteligencia Artificial y Aprendizaje Automático · Prof. Luis Eduardo Falcón Morales

Entregable: [`PreciosVivienda_Equipo.ipynb`](PreciosVivienda_Equipo.ipynb)

## Equipo 12

| Integrante | Matrícula |
|---|---|
| Edher Iván Díaz Salazar | A01840962 |
| Josué David del Valle Pimentel | A00833285 |
| Víctor Manuel Del Río González | A01840853 |
| Isaí Desales Santiago | A01840669 |

## Datos

Se usa `train.csv` del reto de Kaggle [House Prices – Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data). El archivo no se incluye en el repositorio por las reglas de uso de Kaggle. En Google Colab, la primera celda de código pide subirlo si no está en la sesión.

## Contenido del notebook

- Variables temporales, limpieza, imputación y transformaciones dentro de un `Pipeline`.
- Partición entrenamiento/prueba con validación cruzada y modelo ingenuo.
- Seis modelos de regresión con búsqueda de hiperparámetros, curvas de aprendizaje y tabla comparativa.
- Interpretación del mejor modelo y selección de los tres mejores con RMSE y MAE.
- `VotingRegressor` y `StackingRegressor`.
- Reporte ejecutivo y conclusiones.

El notebook se entrega con las salidas de la ejecución final. Si se vuelve a ejecutar en otro entorno, las cifras pueden variar ligeramente según las versiones de las bibliotecas.
