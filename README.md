# 📊 Predicción de Demanda de Energía Eléctrica mediante modelos de Machine Learning

## 📌 Descripción  
La demanda eléctrica es un pilar fundamental de la economía, con grandes desafíos debido a su difícil almacenamiento y variabilidad. Con el auge del **Big Data** y 
la **inteligencia artificial**, se han desarrollado modelos avanzados para predecir el consumo y evitar pérdidas económicas. Este proyecto compara técnicas de **Machine Learning** 
y modelos tradicionales para evaluar su eficacia en la predicción de la demanda eléctrica.

---

## 🛠️ Tecnologías Utilizadas  

## 🛠️ Tecnologías Utilizadas  

### 📌 Lenguaje de Programación  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
- **Python** → Desarrollo y análisis de datos.  

### 📌 Librerías Principales  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
- `pandas` → Manipulación y limpieza de datos.  

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)  
- `numpy` → Cálculos matemáticos y operaciones numéricas.  

![Scikit-Learn](https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)  
- `scikit-learn` → Modelos de Machine Learning.  

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)  
- `matplotlib` → Visualización de datos.  

![Skforecast](https://img.shields.io/badge/Skforecast-FF6F00?style=for-the-badge&logo=python&logoColor=white)  
- `skforecast` → Modelado de series temporales.  

![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)  
- `keras` → Redes neuronales profundas (Deep Learning).  

![Pyesios](https://img.shields.io/badge/Pyesios-003B57?style=for-the-badge&logo=python&logoColor=white)  
- `pyesios` → Extracción de datos de la API de REE.  

---

## 📂 Estructura del Proyecto  

📁 **latex/** → Contiene los archivos de la memoria redactada en LaTeX.  

📁 **preprocessing/** → Extracción, preprocesamiento y análisis exploratorio de los datos.  
  - 📄 `extracción_temperatura_humedad.ipynb` → Obtención de datos meteorológicos.  
  - 📄 `datos_climáticos_diarios.csv` → Datos meteorológicos procesados.  
  - 📄 `extracción_demanda_eléctrica.ipynb` → Obtención de datos de demanda eléctrica.  
  - 📄 `datos_demanda_media_diaria.csv` → Datos de consumo eléctrico.  
  - 📄 `preprocesamiento.ipynb` → Limpieza y transformación de datos.  
  - 📄 `datos_preprocesados.csv` → Datos finales listos para modelado.  
  - 📄 `EDA.ipynb` → Análisis exploratorio de datos.  

📁 **models/** → Implementación y evaluación de modelos de predicción.  
  - 📄 `ARIMAX.ipynb` → Modelo ARIMAX optimizado.  
  - 📄 `generic_model.ipynb` → Modelos **Decision Tree, Random Forest y XGBoost**.  
  - 📄 `LSTM.ipynb` → Modelo de **Red Neuronal LSTM** para series temporales.  
  - 📄 `results.xlsx` → Comparación de resultados entre modelos.  

📁 **data/** → Copia de seguridad de los archivos con los datos.  

---

## 🚀 Modelos Implementados  
✔ **ARIMAX** → Modelo estadístico para series temporales.  
✔ **Decision Tree, Random Forest, XGBoost** → Modelos de aprendizaje supervisado.  
✔ **LSTM (Long Short-Term Memory)** → Red neuronal para modelado de series temporales.  

---

## 📈 Resultados y Conclusiones  
Este proyecto ha permitido analizar y comparar distintos modelos de Machine Learning para la predicción de la demanda eléctrica, destacando XGBoost como el más eficiente en términos de precisión y coste computacional. Aunque el modelo LSTM mostró potencial, su rendimiento se vio limitado por los tiempos de procesamiento y la granularidad de los datos. Las variables exógenas, como la temperatura y los días festivos, tuvieron un impacto clave en la predicción, mientras que otras, como la humedad, introdujeron cierto ruido. En general, la planificación y ejecución del proyecto han sido exitosas, aunque futuras mejoras podrían centrarse en un mayor nivel de detalle en los datos y la optimización avanzada de hiperparámetros. 

---


