# Predicción del Gasto Mensual de Clientes – RetailBoost
## Descripción del proyecto

Este proyecto aborda un problema de regresión aplicado a analítica de clientes para una empresa ficticia de comercio electrónico llamada *RetailBoost*.

El *objetivo principal* es predecir el gasto mensual de los clientes (monthly_spent) a partir de variables demográficas y de comportamiento, tales como edad, ingresos, historial de visitas y otros factores relevantes.

El trabajo combina **Análisis Exploratorio de Datos (EDA)** con **modelado predictivo**, priorizando tanto la interpretabilidad de los modelos como su evaluación mediante métricas estadísticas estándar.

#### Objetivos

1. Realizar un análisis exploratorio para comprender la estructura y características del dataset.

2. Analizar la distribución de la variable objetivo (monthly_spent) y de las principales variables predictoras.

3. Ajustar y comparar distintos modelos de regresión.

4. Evaluar el rendimiento de los modelos utilizando métricas de error.

5. Interpretar los resultados para identificar qué variables influyen con mayor peso en el gasto mensual.


#### Contexto del negocio

Comprender el comportamiento de gasto de los clientes es fundamental para empresas de e-commerce, ya que permite:

- Mejorar la segmentación de clientes.

- Optimizar estrategias de marketing y fidelización.

- Identificar clientes de alto valor.

- Apoyar la toma de decisiones basada en datos.

Este proyecto simula un escenario real donde el análisis predictivo aporta insights accionables para el negocio.


#### *Análisis Exploratorio de Datos (EDA)*

El EDA incluye:

- Inspección inicial del dataset (dimensiones, tipos de datos y valores faltantes).

- Estadísticos descriptivos de las variables numéricas.

- Visualización de la distribución de la variable objetivo (monthly_spent).

- Análisis de las principales variables predictoras mediante gráficos y correlaciones.

Esta etapa permite evaluar la *calidad de los datos* y *detectar patrones* relevantes antes del modelado.


#### *Modelado*

Se implementaron los siguientes modelos de regresión:

**Regresión lineal simple**
Utilizada para *analizar la relación entre una única variable predictora y el gasto mensual*.

**Regresión lineal múltiple**
Permite evaluar el *efecto conjunto de varias variables explicativas sobre el gasto mensual de los clientes*.

Para garantizar una evaluación objetiva, el dataset se dividió en conjuntos de entrenamiento y prueba.


#### *Métricas de evaluación*

El desempeño de los modelos se evaluó utilizando:

**R² (coeficiente de determinación):** Mide la proporción de la variabilidad del gasto mensual explicada por el modelo.

**MAE (Mean Absolute Error):** Indica el error promedio absoluto de las predicciones.

**RMSE (Root Mean Squared Error):** Penaliza con mayor peso los errores grandes, proporcionando una medida de robustez del modelo.

Estas métricas permiten comparar de forma clara la calidad de los modelos ajustados.


#### *Resultados principales*

- El modelo de regresión lineal múltiple presenta un mejor ajuste que el modelo simple, explicando una mayor proporción de la variabilidad del gasto mensual.

- Algunas variables demográficas y de comportamiento muestran una influencia más significativa sobre el gasto de los clientes.

- Los errores de predicción obtenidos son razonables en relación con la escala de la variable objetivo, lo que indica un desempeño adecuado del modelo.


#### *Conclusiones*

- El Análisis Exploratorio de Datos resulta clave para comprender el comportamiento de las variables y orientar el proceso de modelado.

- Los modelos de regresión múltiple ofrecen un mejor desempeño predictivo que los modelos simples cuando el comportamiento del cliente depende de múltiples factores.

- Las métricas obtenidas indican un buen equilibrio entre capacidad explicativa y error de predicción, manteniendo la interpretabilidad del modelo.

- La metodología empleada puede ampliarse incorporando técnicas más avanzadas, como regularización o modelos no lineales, para mejorar aún más el rendimiento.

En conjunto, este análisis evidencia el valor del enfoque analítico para generar conocimiento útil y apoyar decisiones estratégicas basadas en datos.


#### *Tecnologías utilizadas*

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn


### **👩‍💻 Autora**

Dra. Vanina Cavallin
Junior Data Scientist