# Práctica 8: Pronóstico (Forecasting - Series de Tiempo)

Este proyecto aplica un modelo de **Regresión Lineal** sobre una serie de tiempo para predecir la evolución del xG (Expected Goals) en la Premier League.

## Contenido
- `forecasting.ipynb`: Cuaderno con el análisis de la serie de tiempo, el entrenamiento del modelo y el pronóstico a futuro.
- `cleaned_epl_shots.csv`: Dataset con los datos de tiros y fechas de los partidos.

## Metodología
1. **Agregación de Datos**: Se transformaron los datos de tiros individuales en una serie temporal diaria sumando el xG generado por fecha.
2. **Variable Independiente (X)**: Días transcurridos desde el inicio de la temporada.
3. **Variable Dependiente (Y)**: Total de xG diario.
4. **Modelo**: Regresión Lineal de scikit-learn.
5. **Pronóstico**: Se proyectó la tendencia de la peligrosidad de los tiros para los próximos 30 días.

## Requisitos
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
