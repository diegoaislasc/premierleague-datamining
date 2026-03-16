# Práctica 5: Linear Models + Correlation

## Descripción
En esta práctica se explora la relación lineal entre variables numéricas del dataset de la EPL 2024-2025 mediante análisis de correlación y regresión lineal simple.

## Objetivo
Generar un modelo lineal para predecir la calidad de ejecución de un tiro (`xgot`) basándose en la calidad de la oportunidad (`xg`), y evaluar su desempeño.

## Contenido
- **Dataset:** `cleaned_epl_shots.csv` (Copia del dataset limpio).
- **Notebook:** `linear_models.ipynb`

## Análisis Realizados

1.  **Matriz de Correlación (Pearson):**
    - Se calculó la correlación entre `xg`, `xgot`, `time` y coordenadas de tiro.
    - Se visualizó mediante un mapa de calor (heatmap).

2.  **Modelo de Regresión Lineal Simple:**
    - **Variable Independiente (X):** `xg` (Expected Goals).
    - **Variable Dependiente (y):** `xgot` (Expected Goals on Target).
    - **Filtro:** Se utilizaron solo tiros a puerta (`xgot > 0`) para analizar la calidad de ejecución pura.

3.  **Evaluación del Modelo:**
    - **Coeficiente de Determinación ($R^2$):** Indica qué proporción de la varianza en la calidad del tiro es explicada por la calidad de la oportunidad.
    - **Error Cuadrático Medio (MSE):** Mide el promedio de los errores al cuadrado.

4.  **Visualización:**
    - Gráfico de dispersión con la línea de regresión ajustada para visualizar el ajuste del modelo a los datos reales.

## Instrucciones de Ejecución
1.  Asegúrate de tener instaladas las dependencias (`scikit-learn` es clave aquí):
    ```bash
    pip install -r ../requirements.txt
    ```
2.  Abre y ejecuta el notebook `linear_models.ipynb`.
