# Proyecto 1 Responsible AI

# Predicción de Churn con datos de Telcom

## Descripción General

Este proyecto tiene como objetivo predecir la probabilidad de que un cliente abandone un servicio utilizando técnicas de aprendizaje automático.
Se emplea un conjunto de datos históricos de Telcom proveniente de Kaggle[https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data] para entrenar dos modelos de clasificación y seleccionar el que mejor rendimiento ofrece.

## Propósito

El propósito de este proyecto es proporcionar una herramienta que permita a las empresas identificar a los clientes con mayor riesgo de churn y tomar medidas proactivas para retenerlos. Esto puede ayudar a reducir la tasa de abandono y mejorar la satisfacción del cliente.

## Estructura del Proyecto

- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Contiene el conjunto de datos utilizado para el entrenamiento y la prueba.
- `project.ipynb`: Incluye el notebook de Jupyter con el análisis exploratorio de datos y la construcción de modelos.
- `models/`: Almacena los modelos entrenados.
- `README.md`: Este archivo, que proporciona una visión general del proyecto e instrucciones.

## Dependencias

Para ejecutar este proyecto, necesitarás instalar las siguientes dependencias:

- Python 3.10 o superior
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- shap
- joblib

Puede instalar todas las dependencias utilizando el siguiente comando:

```bash
pip install -r requirements.txt
```
