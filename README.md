# Trabajo Fin de Estudio

## Análisis y visualización de factores de riesgo asociados a la diabetes mediante modelos predictivos de aprendizaje automático

### Descripción

Este repositorio contiene el código fuente desarrollado para el Trabajo Fin de Estudio titulado **"Análisis y visualización de factores de riesgo asociados a la diabetes mediante modelos predictivos de aprendizaje automático"**.

El objetivo del proyecto es desarrollar y comparar diferentes modelos de aprendizaje automático para predecir la presencia de diabetes a partir de variables relacionadas con el estado de salud, los hábitos de vida y las características sociodemográficas de los pacientes.

Además del desarrollo de los modelos predictivos, el trabajo incorpora técnicas de interpretabilidad mediante SHAP y un dashboard elaborado en Microsoft Power BI para la visualización de los resultados.

---

## Autora

Leire García Rodríguez

Todos los archivos y commits incluidos en este repositorio han sido desarrollados exclusivamente por la autora.

---

## Dataset empleado

El estudio utiliza el conjunto de datos **Diabetes Health Indicators Dataset**, elaborado a partir de la encuesta **Behavioral Risk Factor Surveillance System (BRFSS) 2015** de los **Centers for Disease Control and Prevention (CDC)**.

Características principales del conjunto de datos:

- Formato: CSV
- Número de registros: 253.680
- Número de variables: 22
- Variable objetivo: **Diabetes_binary**

---

## Contenido del repositorio

Este repositorio incluye:

- El notebook principal con todo el desarrollo del proyecto (`codigo_modelos.ipynb`).
- El conjunto de datos utilizado para el entrenamiento de los modelos (`bbdd_diabetes.xls`).
- El dashboard desarrollado en Microsoft Power BI (`visualizacion1.pbix`).

---

## Metodología

El flujo de trabajo desarrollado sigue las siguientes etapas:

1. Carga del conjunto de datos.
2. Exploración y preprocesamiento de los datos.
3. División del conjunto de datos en entrenamiento y prueba.
4. Aplicación de la técnica SMOTE sobre el conjunto de entrenamiento.
5. Entrenamiento de los modelos de aprendizaje automático.
6. Ajuste de hiperparámetros mediante validación cruzada.
7. Evaluación utilizando Accuracy, Precision, Recall, F1-score y AUC-ROC.
8. Interpretación de los resultados mediante SHAP.
9. Elaboración del dashboard en Microsoft Power BI.

---

## Modelos implementados

En el trabajo se desarrollan y comparan los siguientes algoritmos:

- Regresión Logística
- Árbol de Decisión
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP)
- XGBoost
- LightGBM
- CatBoost

---

## Requisitos

El proyecto ha sido desarrollado en **Python 3** utilizando, entre otras, las siguientes librerías:

- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
- SHAP
- xgboost
- lightgbm
- catboost

Las dependencias empleadas se encuentran recogidas en el archivo `requirements.txt`.

---

## Ejecución

Para reproducir los experimentos basta con:

1. Instalar las dependencias indicadas en `requirements.txt`.
2. Abrir el notebook `codigo_modelos.ipynb`.
3. Ejecutar las celdas de forma secuencial.

El notebook realiza automáticamente todas las etapas del proceso de análisis, entrenamiento, evaluación e interpretación de los modelos.

---

## Reproducibilidad

Con el objetivo de garantizar la reproducibilidad de los experimentos, los procesos que incorporan componentes aleatorios utilizan una semilla fija (`random_state = 42`) cuando corresponde.

---

## Dashboard

El repositorio incluye el archivo `visualizacion1.pbix`, desarrollado en Microsoft Power BI, que permite visualizar los principales resultados obtenidos durante el estudio.

---

## Uso

Este repositorio ha sido desarrollado exclusivamente con fines académicos como parte del Trabajo de Fin de Máster.
