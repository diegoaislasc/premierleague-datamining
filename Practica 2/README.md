# Práctica 2: Descriptive Statistics

## Descripción
En esta práctica se realiza un análisis estadístico descriptivo del dataset limpio de la EPL 2024-2025. El objetivo es comprender la distribución de los datos, identificar las entidades principales (Jugadores, Partidos) y sus relaciones, y obtener métricas agrupadas.

## Contenido
- **Dataset:** `cleaned_epl_shots.csv` (Copia del dataset limpio de la Práctica 1).
- **Notebook:** `descriptive_statistics.ipynb`

## Análisis Realizados
1.  **Estadísticas Descriptivas:**
    - Cálculo de media, mediana, desviación estándar para variables numéricas (`xg`, `xgot`, `time`).
    - Análisis de frecuencia para variables categóricas (`shotType`, `situation`, `player_position`).
2.  **Identificación de Entidades y Relaciones:**
    - Se identificaron las entidades **Player**, **Match** y **Shot**.
    - Se diagramó la relación entre ellas (Un Jugador realiza muchos Tiros; Un Partido contiene muchos Tiros).
3.  **Agrupación de Datos:**
    - **Por Jugador:** Total de tiros, xG acumulado y promedio por jugador.
    - **Por Partido:** Intensidad ofensiva (tiros por partido) y xG total del encuentro.
    - **Por Situación:** Calidad promedio de tiros según el tipo de jugada (balón parado, jugada abierta, etc.).

## Instrucciones de Ejecución
1.  Asegúrate de tener instaladas las dependencias:
    ```bash
    pip install -r ../requirements.txt
    ```
2.  Abre y ejecuta el notebook `descriptive_statistics.ipynb`.
