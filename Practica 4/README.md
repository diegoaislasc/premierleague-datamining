# Práctica 4: Statistic Test

## Descripción
En esta práctica se aplican pruebas estadísticas para determinar si existen diferencias significativas entre grupos de datos etiquetados en el dataset de la EPL 2024-2025.

## Objetivo
Demostrar estadísticamente si variables categóricas (como la posición del jugador o la localía) influyen en una variable numérica clave (`xg`).

## Contenido
- **Dataset:** `cleaned_epl_shots.csv` (Copia del dataset limpio).
- **Notebook:** `statistic_tests.ipynb`

## Pruebas Realizadas

1.  **Verificación de Normalidad (Shapiro-Wilk):**
    - Se evaluó la distribución de la variable `xg`.
    - Resultado esperado: Distribución no normal (p < 0.05), lo que justifica el uso de pruebas no paramétricas.

2.  **Prueba 1: Kruskal-Wallis (Comparación Múltiple):**
    - **Grupos:** Posiciones de jugadores (Delanteros vs Mediocampistas vs Defensores).
    - **Variable:** `xg` (Calidad del tiro).
    - **Hipótesis:** ¿Influye la posición en la calidad de la oportunidad de gol?

3.  **Prueba 2: Mann-Whitney U (Comparación de 2 Grupos):**
    - **Grupos:** Local (Home) vs Visitante (Away).
    - **Variable:** `xg`.
    - **Hipótesis:** ¿Tienen los locales mejores oportunidades de gol que los visitantes?

## Instrucciones de Ejecución
1.  Asegúrate de tener instaladas las dependencias (incluyendo `scipy`):
    ```bash
    pip install -r ../requirements.txt
    ```
2.  Abre y ejecuta el notebook `statistic_tests.ipynb`.
