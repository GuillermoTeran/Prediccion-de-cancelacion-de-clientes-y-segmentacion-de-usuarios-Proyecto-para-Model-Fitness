# Predicción de cancelación de clientes y segmentación de usuarios — Proyecto para Model Fitness

## ES Español

Descripción del proyecto:

Como parte del equipo de análisis de datos en Model Fitness, una cadena de gimnasios en proceso de transformación digital, desarrollé un modelo predictivo para identificar clientes con alto riesgo de cancelación y una segmentación de usuarios para diseñar estrategias personalizadas de retención. Este proyecto tuvo como objetivo principal reducir la tasa de rotación de clientes mediante un enfoque analítico.

## Objetivos del proyecto:

Predecir la probabilidad de cancelación de los clientes para el mes siguiente.

Identificar segmentos de usuarios según sus hábitos y características.

Detectar los factores clave que influyen en la pérdida de clientes.

Formular recomendaciones estratégicas para la retención basadas en análisis de datos.

## Análisis exploratorio de datos (EDA)
Se trabajó con datos de clientes, historial de visitas, servicios adicionales, tipo de contrato y datos sociodemográficos.

### Principales tareas:

Análisis descriptivo de características como edad, frecuencia de asistencia, duración del contrato y uso de servicios adicionales.

Comparación de métricas clave entre clientes que permanecieron y los que se dieron de baja.

Visualización de distribuciones y creación de una matriz de correlación para identificar relaciones entre variables.

## Modelado predictivo: clasificación de cancelación
Se desarrollaron y compararon dos modelos de clasificación:

Regresión logística

Bosque aleatorio (Random Forest)

### Resultados:

Ambos modelos fueron evaluados por precisión, recall y exactitud.

El modelo de bosque aleatorio ofreció mejores métricas de desempeño, siendo más robusto frente a variabilidad de datos.

## Segmentación de usuarios (Clustering)
Se llevó a cabo una segmentación de clientes mediante K-means (k=5), previa estandarización de las variables:

Análisis jerárquico con dendrogramas para estimar el número óptimo de clústeres.

Evaluación de diferencias entre grupos en características clave como frecuencia de visitas, uso de servicios, edad, tipo de contrato.

Cálculo de tasas de cancelación por clúster, identificando perfiles de alto y bajo riesgo.

## Hallazgos clave:
Los clientes con contratos más largos, participación en clases grupales y mayor gasto en servicios adicionales presentaron menores tasas de cancelación.

Aquellos con contratos mensuales, baja frecuencia de visitas y sin vínculos promocionales o cercanía geográfica fueron los más propensos a abandonar.

La variable “Lifetime” (meses como cliente) tuvo alta correlación negativa con la cancelación: a mayor antigüedad, mayor lealtad.

## Recomendaciones estratégicas:
Segmentación activa de clientes para campañas personalizadas según riesgo de cancelación.

Promoción de contratos de largo plazo con beneficios adicionales.

Fomento de clases grupales como herramienta de fidelización.

Ofertas personalizadas para clientes nuevos o inactivos, como descuentos en servicios adicionales o invitaciones a eventos.

## Herramientas utilizadas:

Python (pandas, numpy, matplotlib, seaborn, scikit-learn, scipy)

Jupyter Notebook

Algoritmos de machine learning supervisado y no supervisado


# Customer churn prediction and user segmentation — Project for Model Fitness

## US English

Project description:

As part of the data analysis team at Model Fitness, a chain of gyms undergoing digital transformation, I developed a predictive model to identify customers at high risk of cancellation and user segmentation to design personalized retention strategies. The main objective of this project was to reduce customer turnover through an analytical approach.

## Project objectives:

Predict the likelihood of customer churn for the following month.

Identify user segments based on their habits and characteristics.

Detect the key factors that influence customer loss.

Formulate strategic recommendations for retention based on data analysis.

## Exploratory data analysis (EDA)
We worked with customer data, visit history, additional services, contract type, and sociodemographic data.

### Main tasks:

Descriptive analysis of characteristics such as age, frequency of attendance, contract duration, and use of additional services.

Comparison of key metrics between customers who remained and those who canceled their service.

Visualization of distributions and creation of a correlation matrix to identify relationships between variables.

## Predictive modeling: cancellation classification
Two classification models were developed and compared:

Logistic regression

Random Forest

### Results:

Both models were evaluated for precision, recall, and accuracy.

The random forest model offered better performance metrics, being more robust against data variability.

## User segmentation (clustering)
Customer segmentation was carried out using K-means (k=5), after standardizing the variables:

Hierarchical analysis with dendrograms to estimate the optimal number of clusters.

Evaluation of differences between groups in key characteristics such as frequency of visits, use of services, age, and type of contract.

Calculation of cancellation rates by cluster, identifying high- and low-risk profiles.

## Key findings:
Customers with longer contracts, participation in group classes, and higher spending on additional services had lower cancellation rates.

Those with monthly contracts, low visit frequency, and no promotional ties or geographical proximity were the most likely to leave.

The “Lifetime” variable (months as a customer) had a high negative correlation with cancellation: the longer the tenure, the greater the loyalty.

## Strategic recommendations:
Active customer segmentation for personalized campaigns based on cancellation risk.

Promotion of long-term contracts with additional benefits.

Promotion of group classes as a loyalty tool.

Personalized offers for new or inactive customers, such as discounts on additional services or invitations to events.

## Tools used:

Python (pandas, numpy, matplotlib, seaborn, scikit-learn, scipy)

Jupyter Notebook

Supervised and unsupervised machine learning algorithms













