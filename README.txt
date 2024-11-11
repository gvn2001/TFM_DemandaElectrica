# Predicción de Demanda de Energía Eléctrica con Modelos de Machine Learning

## Descripción
En este archivo txt únicamente se va a mencionar la estructura del proyecto: carpetas, archivos y programas. El grueso de las explicaciones se encuentra redactado en la memoria del trabajo.

## Tecnologías usadas

- Python: Lenguaje de programación para el desarrollo.
- Principales librerías utilizadas:
  - pandas: para manipulación de datos.
  - numpy: para operaciones matemáticas.
  - scikit-learn: para el desarrollo y evaluación de modelos de Machine Learning.
  - matplotlib: para la visualización de datos.
  - skforecast: para facilitar el entrenamiento de modelos para series temporales.
  - keras: Para el desarrollo de redes neuronales.
  - pyesios: librería para la extracción de datos de demanda eléctrica en el API de la REE.

## Estructura de carpetas y archivos

- latex: carpeta que contiene todos los archivos de la memoria redactada a partir de latex.

- preprocessing: contiene todos los programas y archivos necesarios para la extracción, preprocesamiento y EDA de los datos.
    - extracción_temperatura_humedad.ipynb: notebook para la extracción de datos meteorológicos.
    - datos_climáticos_diarios.csv: archivo de texto que contiene los datos meteorológicos extraídos y preprocesados.
    - extracción_demanda_eléctrica.ipynb: notebook para la extracción de datos de demanda eléctrica.
    - datos_demanda_media_diaria.csv: archivo de texto que contiene los datos de demanda eléctrica extraídos y preprocesados.
    - preprocesamiento.ipynb: notebook donde se realiza el preprocesamiento de los datos.
    - datos_preprocesados: archivo de texto que contiene los datos limpios.
    - EDA.ipynb: notebook donde se realiza el EDA.
    - resto de archivos: archivos necesarios para el correcto funcionamiento de la librería de pyesios.

- models: scripts y archivos orientados al entrenamiento de los modelos.
    - ARIMAX.ipynb: notebook donde se aplica y optimiza el modelo ARIMAX.
    - generic_model.ipynb: notebook donde se aplican y optimizan los modelos de Decision Tree, Random Forest y XGBoost.
    - LSTM.ipynb: notebook donde se aplica y optimiza el modelo LSTM.
    - results.xlsx: excel donde se recogen los resultados de todos los modelos.

- data: copia de seguridad para todos los archivos planos que contienen datos.
