# 🛍️ RetailBoost – Predicción del Gasto Mensual de Clientes

> Proyecto de Machine Learning para estimar el gasto mensual de clientes de un e-commerce mediante modelos de regresión y apoyar estrategias comerciales basadas en datos.

---

# 📌 Descripción del proyecto

RetailBoost es una empresa ficticia de comercio electrónico que busca comprender qué factores influyen en el gasto mensual de sus clientes.

Este proyecto desarrolla un pipeline de análisis y modelado predictivo para estimar el valor de **`monthly_spent`**, combinando análisis exploratorio de datos con modelos de regresión lineal.

El objetivo no consiste únicamente en obtener buenas predicciones, sino también en interpretar cómo las variables demográficas y de comportamiento impactan sobre el gasto de los clientes.

---

# 🎯 Objetivos

- Comprender la estructura y calidad del conjunto de datos.
- Explorar las relaciones entre las variables predictoras y el gasto mensual.
- Implementar modelos de regresión lineal simple y múltiple.
- Comparar el desempeño de los modelos.
- Interpretar los resultados para apoyar decisiones comerciales.

---

# 🏗️ Pipeline del proyecto

```text
Carga de datos
       │
       ▼
Análisis Exploratorio (EDA)
       │
       ▼
Preprocesamiento
       │
       ▼
Regresión Lineal Simple
       │
       ▼
Regresión Lineal Múltiple
       │
       ▼
Evaluación
       │
       ▼
Insights de negocio
```

---

# 📁 Estructura del repositorio

```text
retailboost-sales-prediction
│
├── data
│   └── retailboost_customers_regression.csv
│
├── notebooks
│   └── RetailBoost_Regression.ipynb
│
├── images
│
├── README.md
└── requirements.txt
```

---

# 📊 Contexto de negocio

Comprender el comportamiento de compra permite:

- identificar clientes de alto valor;
- optimizar campañas de marketing;
- personalizar promociones;
- mejorar estrategias de fidelización;
- apoyar decisiones comerciales basadas en datos.

---

# 🔍 Análisis Exploratorio de Datos

Durante el EDA se realizaron las siguientes tareas:

- inspección de la estructura del dataset;
- identificación de valores faltantes;
- análisis descriptivo de variables numéricas;
- estudio de la distribución de la variable objetivo;
- análisis de correlaciones entre variables.

Esta etapa permitió detectar patrones relevantes antes del modelado.

---

# 🤖 Modelado predictivo

Se implementaron dos enfoques de regresión.

## Regresión Lineal Simple

Modelo utilizado para estudiar la relación entre una única variable predictora y el gasto mensual.

## Regresión Lineal Múltiple

Modelo que incorpora múltiples variables explicativas para mejorar la capacidad predictiva y comprender el efecto conjunto de distintos factores.

---

# 📈 Métricas de evaluación

Los modelos fueron comparados mediante:

- R²
- MAE
- RMSE

Estas métricas permitieron evaluar tanto la capacidad explicativa como el error de predicción.

---

# 💡 Principales resultados

- La Regresión Lineal Múltiple presentó un mejor desempeño que la Regresión Lineal Simple.
- Las variables demográficas y de comportamiento mostraron diferente grado de influencia sobre el gasto mensual.
- El modelo logró un equilibrio adecuado entre interpretabilidad y capacidad predictiva.

---

# ⭐ Conclusiones

El proyecto demuestra cómo un enfoque de regresión puede utilizarse para estimar el comportamiento económico de los clientes y transformar datos históricos en información útil para la toma de decisiones.

Asimismo, evidencia la importancia del análisis exploratorio y de la correcta selección de variables para mejorar el desempeño de los modelos predictivos.

---

# 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 💼 Competencias demostradas

- Análisis Exploratorio de Datos (EDA)
- Regresión Lineal
- Regresión Lineal Múltiple
- Evaluación de modelos de regresión
- Interpretación de coeficientes
- Storytelling con datos
- Machine Learning aplicado a negocio

---

## 👩‍💻 Autora

**Vanina Cavallin**

Doctora en Ciencias Biológicas | Jr. Data Scientist
