# Práctica 3: Data Visualization

## Descripción
En esta práctica se generan visualizaciones avanzadas para explorar el dataset de tiros de la EPL 2024-2025. Se utilizan técnicas de visualización estática con `matplotlib` y `seaborn` para revelar patrones, tendencias y distribuciones en los datos.

## Contenido
- **Dataset:** `cleaned_epl_shots.csv` (Copia del dataset limpio).
- **Notebook:** `data_visualization.ipynb`

## Visualizaciones Generadas
Se han creado más de 5 tipos de gráficos utilizando bucles para maximizar la eficiencia y cobertura:

1.  **Histogramas (Distribución):**
    - Análisis de variables numéricas como `xg` (Expected Goals), `xgot` (xG on Target), y coordenadas de tiro.
    - Permite ver la frecuencia y forma de la distribución de los datos.

2.  **Boxplots (Categoría vs Numérico):**
    - Comparación de la calidad del tiro (`xg`) según la situación de juego (juego abierto, balón parado) y tipo de tiro.
    - Identifica valores atípicos (outliers) y medianas.

3.  **Scatter Plots (Relaciones):**
    - **Mapa de Tiros:** Coordenadas X vs Y para visualizar la ubicación espacial de los intentos.
    - **Calidad vs Ejecución:** Relación entre `xg` y `xgot`.

4.  **Pie Charts (Composición):**
    - Proporción de tiros por tipo (pierna derecha, izquierda, cabeza) y situación.

5.  **Line Plots (Tendencias Temporales):**
    - Evolución del `xg` promedio a lo largo de los 90 minutos de partido, revelando momentos de mayor peligro.

## Criterios de Desempeño Aplicados
- **Claridad:** Se usaron títulos descriptivos, etiquetas de ejes y leyendas claras.
- **Diseño:** Paletas de colores (`viridis`, `pastel`, `Set2`) seleccionadas para diferenciar categorías sin fatiga visual.
- **Patrones:** Los gráficos están diseñados para resaltar insights clave, como la baja probabilidad de gol de la mayoría de los tiros (histogramas sesgados a la derecha).

## Instrucciones de Ejecución
1.  Asegúrate de tener instaladas las dependencias:
    ```bash
    pip install -r ../requirements.txt
    ```
2.  Abre y ejecuta el notebook `data_visualization.ipynb`.
