# Análisis de Riesgo Crediticio: Predicción de Default Bancario

Este repositorio contiene un proyecto integral de **Ciencia de Datos y Finanzas Cuantitativas** enfocado en la detección temprana de eventos de incumplimiento (*default*) de clientes bancarios. El objetivo primordial es mitigar el riesgo de cartera vencida mediante modelos de aprendizaje supervisado.

## 🚀 Metodología del Proyecto

El flujo de trabajo se divide en las siguientes etapas para garantizar la robustez del modelo:

* **Curación de Datos:** Limpieza avanzada, traducción técnica de variables e imputación de valores faltantes basada en perfiles demográficos y límites de crédito.
* **Análisis Exploratorio (EDA):** Identificación de patrones de comportamiento, sesgos en la distribución de ingresos y segmentación por tipo de tarjeta.
* **Tratamiento de Desbalance:** Aplicación de técnicas de **Random Undersampling** para estabilizar la distribución de la variable objetivo (*default*) y eliminar el sesgo hacia la clase mayoritaria.
* **Modelado y Validación:** Entrenamiento comparativo de Regresión Logística, Árboles de Decisión y **Random Forest** utilizando validación cruzada de 5 particiones ($k=5$).

## 📊 Resultados Principales

Tras la evaluación de métricas de desempeño alineadas con el negocio bancario, el modelo **Random Forest** demostró ser el más eficaz:

* **Recall (Sensibilidad):** **98%** en la detección de incumplimientos (Clase 1), minimizando los falsos negativos.
* **AUC-ROC:** **0.99**, indicando una capacidad de discriminación casi perfecta entre perfiles solventes y de riesgo.

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python 3.x
* **Librerías:** * **Procesamiento:** Pandas, NumPy
    * **Visualización:** Matplotlib, Seaborn
    * **Machine Learning:** Scikit-learn

## ✒️ Autor
**Rugerio Ordoñez Sahira Azenet** - Estudiante de la Facultad de Ciencias Físico Matemáticas, BUAP.
