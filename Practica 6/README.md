# Práctica 6: Clasificación de Datos (K-NN)

Este proyecto aplica el algoritmo de **K-Nearest Neighbors (K-NN)** para clasificar los tiros de la Premier League (temporada 2024-2025) en dos categorías: **Gol** o **No Gol**.

## Contenido
- `data_classification.ipynb`: Cuaderno con el preprocesamiento, entrenamiento y evaluación del modelo.
- `cleaned_epl_shots.csv`: Dataset utilizado para el análisis.

## Metodología
1. **Definición del Target**: Se transformó la variable `shotType` en una variable binaria (`is_goal`).
2. **Selección de Características**: Se utilizaron coordenadas del tiro (`shot_x`, `shot_y`), situación de juego, parte del cuerpo y el xG (Expected Goals).
3. **Preprocesamiento**:
   - Codificación de variables categóricas.
   - Escalado de variables numéricas (StandardScaler) para optimizar el cálculo de distancias en K-NN.
4. **Optimización**: Se evaluó el modelo con diferentes valores de $K$ (de 1 a 25) para encontrar el punto con menor tasa de error.

## Requisitos
Para ejecutar este cuaderno, necesitas las siguientes librerías:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
