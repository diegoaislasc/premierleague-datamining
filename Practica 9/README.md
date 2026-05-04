# Práctica 9: Análisis de Texto (Word Cloud)

Este proyecto genera representaciones visuales de los datos textuales del dataset de la Premier League 2024-2025 utilizando nubes de palabras (**Word Clouds**).

## Contenido
- `text_analysis.ipynb`: Cuaderno con el procesamiento de texto y la generación de nubes de palabras.
- `cleaned_epl_shots.csv`: Dataset con los datos de tiros.

## Metodología
1. **Extracción de Texto**: Se seleccionaron las columnas `player_name`, `situation` y `bodyPart`.
2. **Preprocesamiento**: Limpieza de nombres y concatenación de términos para formar un corpus.
3. **Generación de Nube de Palabras**: Uso de la librería `wordcloud` para visualizar la frecuencia de los términos.
4. **Análisis**: Identificación de los jugadores y situaciones más recurrentes en los datos de disparos.

## Requisitos
```bash
pip install pandas matplotlib wordcloud
```
