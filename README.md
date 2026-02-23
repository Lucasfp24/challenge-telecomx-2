# 📊 Telecom X – Predicción de Cancelación de Clientes
## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) en Telecom X y desarrollar modelos predictivos capaces de anticipar qué clientes tienen mayor probabilidad de cancelar el servicio.

A través de análisis exploratorio, modelado predictivo y evaluación comparativa, se identificaron las variables más relevantes y se propusieron estrategias de retención basadas en datos.


## 🎯 Objetivos

Analizar variables que influyen en la cancelación.

Preparar los datos para modelado predictivo.

Implementar y comparar distintos modelos de Machine Learning.

Evaluar desempeño mediante métricas estándar.

Identificar factores clave de churn.

Proponer estrategias de retención basadas en resultados.

## 🛠️ Tecnologías Utilizadas

Python.

Pandas.

NumPy.

Matplotlib.

Scikit-learn.

Google Colab.


## 🔧 Metodología
## 1️⃣ Preparación de Datos

Carga del dataset previamente limpiado.

Eliminación de columnas irrelevantes (ej. ID del cliente).

Transformación de variables categóricas mediante One-Hot Encoding.

Separación en variables predictoras (X) y variable objetivo (Cancelación).

División en conjunto de entrenamiento (80%) y prueba (20%).

Normalización con StandardScaler para modelos sensibles a escala.


## 2️⃣ Análisis Exploratorio

Se realizó:

Matriz de correlación.

Análisis de correlación con la variable objetivo.

Boxplots para:

Antigüedad × Cancelación.

Cargos Totales × Cancelación.

Hallazgos principales:

La antigüedad es el factor más determinante (correlación negativa fuerte).

Mayores cargos mensuales aumentan la probabilidad de cancelación.

Clientes con contratos mensuales presentan mayor riesgo.

Servicios adicionales reducen significativamente el churn.


## 🤖 Modelos Implementados
🔹 Regresión Logística (con normalización)

Accuracy Train: 0.807

Accuracy Test: 0.801

Buen equilibrio entre precisión y recall.

No presenta overfitting.

Buena capacidad de generalización.

🔹 Random Forest (sin normalización)

Accuracy Train: 0.998

Accuracy Test: 0.785

Presenta overfitting.

Alta complejidad del modelo.


## 📊 Evaluación de Modelos

Se utilizaron las siguientes métricas:

Accuracy.

Precision.

Recall.

F1-score.

Matriz de Confusión.

Regresión Logística.

Random Forest.


## 🔎 Variables Más Relevantes

Tanto la Regresión Logística como Random Forest coinciden en que las variables más influyentes son:

Antigüedad del cliente.

Cargos mensuales.

Tipo de contrato.

Servicios adicionales (soporte técnico, seguridad).

Facturación electrónica.


## 💡 Estrategias de Retención Propuestas

Programas de fidelización para nuevos clientes.

Incentivar contratos de largo plazo.

Ofrecer paquetes promocionales de servicios adicionales.

Revisar estructura de precios en planes de alto costo.

Implementar sistema de alerta temprana basado en modelo predictivo.


## 📈 Conclusiones

El churn no es aleatorio. Está fuertemente influenciado por:

Tiempo de permanencia.

Nivel de gasto.

Tipo de contrato.

Nivel de vinculación con la empresa.


## ✒️ Autor
### Lucas Pruya

Proyecto desarrollado como parte del Challenge Telecom X 2 Latam
📅 Año: 2025
