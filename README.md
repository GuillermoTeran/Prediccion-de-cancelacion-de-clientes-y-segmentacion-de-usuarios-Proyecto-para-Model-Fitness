# Predicción de cancelación de clientes y segmentación de usuarios — Proyecto para Model Fitness
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

