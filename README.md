# Minería de Datos - Premier League 2024/2025 ⚽️📊

Este repositorio documenta el ciclo completo de un proyecto de Minería de Datos, aplicado al análisis de la **English Premier League (EPL)** durante la temporada 2024-2025. El objetivo principal es transformar datos crudos de eventos de partidos en conocimiento accionable y modelos predictivos.

## 🚀 Descripción del Proyecto

El análisis utiliza un dataset detallado de tiros a gol y eventos de la liga inglesa, explorando desde la limpieza inicial hasta técnicas avanzadas de aprendizaje automático. El proyecto culmina con un Producto Integrador de Aprendizaje (PIA) que sintetiza todos los hallazgos semestrales.

## 📁 Estructura del Repositorio

El trabajo se divide en etapas incrementales de complejidad, cada una contenida en su respectiva carpeta:

1.  **Práctica 1: Limpieza de Datos** (`data_cleaning.ipynb`): Tratamiento de valores nulos, normalización de variables y preparación del dataset maestro.
2.  **Práctica 2: Estadística Descriptiva** (`descriptive_statistics.ipynb`): Análisis de tendencias centrales, dispersión y caracterización de las entidades principales (equipos, jugadores).
3.  **Práctica 3: Visualización de Datos** (`data_visualization.ipynb`): Exploración visual mediante histogramas, diagramas de caja y mapas de calor para identificar patrones y *outliers*.
4.  **Práctica 4: Pruebas Estadísticas** (`statistic_tests.ipynb`): Aplicación de ANOVA, Kruskal-Wallis y otras pruebas para validar diferencias significativas entre grupos de datos.
5.  **Práctica 5: Modelos Lineales** (`linear_models.ipynb`): Análisis de correlación y regresión lineal para entender la relación entre variables predictoras y resultados.
6.  **Práctica 6: Clasificación** (`data_classification.ipynb`): Implementación de algoritmos de clasificación (como KNN) para categorizar eventos o resultados del juego.
7.  **Práctica 7: Agrupamiento (Clustering)** (`data_clustering.ipynb`): Segmentación de datos mediante K-Means para encontrar perfiles de equipos o jugadores con comportamientos similares.
8.  **Práctica 8: Pronóstico (Forecasting)** (`forecasting.ipynb`): Modelado de series de tiempo y proyecciones basadas en tendencias históricas de la temporada actual.
9.  **Práctica 9: Análisis de Texto** (`text_analysis.ipynb`): Procesamiento de lenguaje natural y generación de nubes de palabras basadas en los comentarios y metadatos de los encuentros.
10. **Práctica 10: Producto Integrador de Aprendizaje (PIA)**: Reporte final de Inteligencia de Negocios que integra los hallazgos más relevantes de todo el semestre.

## 📝 Notas Especiales sobre el PIA (Práctica 10)

Debido a limitaciones técnicas persistentes con la grabación de pantalla en mi equipo personal, la elaboración del video de presentación requirió un enfoque alternativo:

*   **Video (`video-mineria-epl.mp4`)**: Generado utilizando **NotebookLM**. Debido a que mi laptop presentaba errores críticos al intentar grabar la pantalla, recurrí a esta herramienta de IA para la locución y ensamble del video. 
*   **Autoría del Contenido**: Es importante destacar que **yo realicé personalmente las diapositivas (`pia_slides.html`)** y proporcioné las **instrucciones y guiones precisos** a la herramienta para asegurar que el video reflejara fielmente mi análisis y conclusiones.

## 🛠️ Requisitos e Instalación

Para replicar este análisis, se recomienda el uso de un entorno virtual de Python.

1.  **Clonar el repositorio**:
    ```bash
    git clone https://github.com/diegoaislasc/premierleague-datamining.git
    cd premierleague-datamining
    ```

2.  **Configurar el entorno**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3.  **Ejecutar Jupyter**:
    ```bash
    jupyter lab
    ```

---
**Autor:** Diego Andre  
**Curso:** Minería de Datos - Semestre 7  
**Dataset Principal:** `epl_2024_2025_match_shots.csv`
