# Práctica 7: Agrupamiento de Datos (Clustering - K-Means)

Este proyecto utiliza el algoritmo de **K-Means** para agrupar tiros de la Premier League en clústeres basados en su ubicación y peligrosidad.

## Contenido
- `data_clustering.ipynb`: Cuaderno con el proceso de clustering, visualización y análisis de grupos.
- `cleaned_epl_shots.csv`: Dataset utilizado.

## Metodología
1. **Selección de Características**: Se utilizaron las variables `shot_x`, `shot_y`, `xg` y `isHome`.
2. **Escalado**: Los datos fueron normalizados con `StandardScaler` para asegurar que todas las variables contribuyan equitativamente al cálculo de distancias.
3. **Optimización (Método del Codo)**: Se analizó la inercia (WCSS) para elegir un número óptimo de clústeres.
4. **Análisis de Resultados**:
   - Visualización de clústeres en el campo de juego.
   - Cálculo de promedios por clúster para interpretar las características de cada grupo (ej. tiros lejanos de baja probabilidad vs tiros cercanos de alta probabilidad).

## Requisitos
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
