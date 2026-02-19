# Práctica 1: Data Cleaning

## Descripción
En esta práctica se realizó la limpieza y preprocesamiento del dataset de tiros de la English Premier League (EPL) temporada 2024-2025. El objetivo fue transformar los datos crudos en un formato estructurado y listo para análisis posteriores, cumpliendo con los requisitos de calidad del curso.

## Dataset
- **Archivo Original:** `epl_2024_2025_match_shots.csv`
- **Fuente:** Datos de partidos de la EPL (obtenidos vía BigQuery/Scraping).
- **Dimensiones Iniciales:** ~8,700 filas.

## Procesos de Limpieza Realizados
1.  **Extracción de Datos JSON:**
    - Se desglosó la columna `player` para obtener `player_name`, `player_position` y `player_id`.
    - Se extrajeron las coordenadas `x` e `y` de la columna `playerCoordinates`.
2.  **Conversión de Tipos:**
    - Conversión de la columna `match_date` a formato `datetime`.
3.  **Manejo de Calidad de Datos:**
    - Eliminación de registros con fechas nulas.
    - Verificación y eliminación de registros duplicados.

## Archivos en esta carpeta
- `data_cleaning.ipynb`: Notebook con el código Python paso a paso.
- `epl_2024_2025_match_shots.csv`: Dataset original (Raw).
- `cleaned_epl_shots.csv`: Dataset procesado y limpio (Output).

## Instrucciones de Ejecución
1.  Asegúrate de tener instaladas las dependencias:
    ```bash
    pip install -r ../requirements.txt
    ```
2.  Abre y ejecuta el notebook `data_cleaning.ipynb`.
