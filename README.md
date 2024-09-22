# Análisis de accidentes automovilísticos

Este proyecto forma parte de un trabajo realizado durante la carrera, cuyo objetivo es analizar los accidentes de coches en Canadá. Se enfoca en la clasificación de accidentes mortales y no mortales, empleando técnicas de procesamiento de datos, análisis exploratorio y modelos de clasificación mediante algoritmos de machine learning. El objetivo es emplear modelos y algoritmos de Machine Learning para predecir si dado un accidente este será mortal o no.

## Descripción del proyecto

El proyecto está organizado en varias etapas que incluyen desde la preparación y limpieza de los datos hasta el entrenamiento y evaluación de modelos de clasificación. A lo largo del proyecto, se ha utilizado programación funcional para crear diversas funciones auxiliares que permiten un enfoque modular y escalable del análisis.

### Fases del proyecto:

1. **Análisis preliminar y preprocesamiento de datos:**
   * En esta etapa, se limpian y preparan los datos, eliminando valores nulos, normalizando las variables y preparando los conjuntos de datos para su posterior análisis.
2. **Análisis exploratorio de los datos (EDA):**
   * Visualización de patrones, tendencias y correlaciones relevantes para comprender mejor las características de los accidentes.
3. **Selección de características:**
   * Se realiza un proceso de selección de características para identificar las variables más importantes para el modelo de clasificación.
4. **Modelos de clasificación:**
   * Se implementan diferentes modelos de clasificación (como XGBoost y Random Forest) para predecir si un accidente será mortal o no.
5. **Evaluación y ajuste de los modelos:**
   * Evaluación del rendimiento de los modelos mediante métricas como precisión, recall, y f1-score, seguido de ajustes para mejorar los resultados.

## Estructura del proyecto

El proyecto está dividido en varios scripts de Python, cada uno diseñado para una tarea específica. Se ha hecho un uso extensivo de  **programación funcional** , donde cada script contiene funciones que encapsulan lógica de procesamiento, análisis o modelado.

### Archivos del proyecto:

* **Análisis_clasificacion.py** : Contiene las funciones para la ejecución de los modelos de clasificación y evaluación de su rendimiento.
* **Análisis_preliminar_preprocesing.py** : Incluye funciones para la limpieza y preprocesamiento de los datos.
* **Funciones_exploratorio.py** : Contiene funciones auxiliares para realizar el análisis exploratorio de los datos.
* **main.ipynb** : Archivo Jupyter Notebook donde se presenta la integración de todo el análisis realizado.
* **Modelos_clasificación.py** : Funciones relacionadas con el entrenamiento y evaluación de modelos de machine learning.
* **Seleccion_caracteristicas.py** : Funciones para la selección de las características más relevantes en el análisis.

### Estructura funcional:

Cada archivo de Python está diseñado con un enfoque modular para facilitar la reutilización de código. Las funciones se enfocan en tareas específicas, como la limpieza de datos, visualización y modelado, lo que permite mejorar la legibilidad y escalabilidad del código.

## Principales herramientas utilizadas

* **Python** : Lenguaje principal utilizado en el proyecto.
* **Jupyter Notebook** : Para la creación de informes interactivos.
* **Pandas** : Manejo y procesamiento de datos.
* **Matplotlib/Seaborn** : Visualización de datos.
* **scikit-learn** : Modelos de machine learning.
* **imbalanced-learn** : Manejo de datasets desbalanceados.
* **XGBoost** : Implementación de modelos de clasificación avanzados.

## Conclusiones

Este proyecto muestra cómo se puede abordar un problema de clasificación de accidentes automovilísticos utilizando diversas técnicas de preprocesamiento, análisis de datos y machine learning. Además, el uso de programación funcional ha facilitado la organización y modularización del código, haciéndolo más escalable y fácil de mantener.
