# Pipeline de Análisis y Modelado de Costos Médicos

## Descripción
Este proyecto desarrolla un pipeline completo de ciencia de datos para el análisis y predicción
del **costo médico anual** de asegurados, utilizando un dataset realista de seguros médicos
obtenido desde Kaggle.

El flujo de trabajo incluye:
- Exploración y limpieza de datos con Pandas
- Análisis Exploratorio de Datos (EDA)
- Feature Engineering usando programación funcional
- Encapsulación del proceso mediante Programación Orientada a Objetos (POO)
- Entrenamiento y evaluación de un modelo de Machine Learning
- Pruebas unitarias y buenas prácticas de reproducibilidad

El proyecto fue desarrollado íntegramente dentro de un **Jupyter Notebook** como parte del curso
*Paradigmas de Programación para IA y Análisis de Datos*.



## Objetivo del Proyecto
Construir un modelo de **regresión** capaz de predecir el **costo médico anual**
(`annual_medical_cost`) de un individuo, a partir de variables demográficas,
económicas, clínicas y del plan de seguro.



## Dataset
- **Nombre:** Medical Insurance Cost Prediction  
- **Fuente:** Kaggle  
- **Enlace:**  
  https://www.kaggle.com/datasets/mohankrishnathalla/medical-insurance-cost-prediction  

El dataset contiene más de **100,000 registros** con variables numéricas y categóricas,
incluyendo información médica, hábitos de salud y características del seguro.



## Estructura del Proyecto

├── ProyectoFinal_Apellido_Nombre.ipynb
├── mi_pipeline_utils.py
├── test_mi_pipeline.py
├── requirements.txt
└── README.md



## Tecnologías Utilizadas
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pytest



## Modelo Implementado
- **Modelo:** RandomForestRegressor  
- **Métricas de Evaluación:**
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² (Coeficiente de determinación)

El modelo obtuvo un desempeño sobresaliente, con un **R² cercano a 0.99**,
indicando una alta capacidad predictiva.



## Cómo Ejecutar el Proyecto

1. Clona este repositorio:   
   git clone https://github.com/edwinpuco/paradigmasprogramacion
   
2. Instala las dependencias:
 pip install -r requirements.txt

3. Abre el notebook:
jupyter notebook ProyectoFinal_Puco_Edwin.ipynb

4. Ejecuta todas las celdas en orden para reproducir el análisis completo.
El proyecto incluye pruebas unitarias básicas utilizando pytest
para validar funciones auxiliares del preprocesamiento.

Para ejecutar las pruebas:

pytest
