**Copa Mundial de Series Temporales: Grupo 3**

**Descripción del Proyecto**
Este repositorio contiene el miniproyecto final para la unidad de "Series Temporales y Pronóstico". 
El objetivo principal es predecir la temperatura media diaria utilizando registros climáticos históricos. 

Se desarrollaron, entrenaron y evaluaron modelos de forecasting supervisado (univariantes y multivariantes) mediante la librería `skforecast` para generar predicciones a un horizonte temporal estricto de 7 días en el futuro.

**Dataset:**
Trabajamos exclusivamente con el dataset "Daily Climate Delhi" (versión adaptada por el docente), el cual consta de registros continuos.
* Variable Temporal: `fecha` (Frecuencia diaria explícita).
* Variable Objetivo: `temperatura_media` (a predecir).
* Variables Exógenas: `humedad`, `velocidad_viento` y `presion_media`.

**Instrucciones de Ejecución:**
Para reproducir este proyecto y ejecutar el código fuente:
1. Clona este repositorio en tu máquina local:
   git clone https://git.utec.edu.uy/usuario/proyecto_series_temporales-grupo_3.git
   
2. Abre el archivo `notebooks/Proyecto_Clima.ipynb` utilizando Jupyter Notebook, JupyterLab, o súbelo a Google Colab.
3. El notebook está diseñado para ser completamente reproducible. Ejecuta todas las celdas en orden.