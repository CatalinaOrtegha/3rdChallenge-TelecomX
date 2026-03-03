📊 Predicción de Cancelación de Clientes
📖 Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning capaces de predecir la cancelación de clientes y analizar los factores más influyentes en la decisión de abandono.

La finalidad es transformar datos históricos en estrategias de retención accionables que permitan reducir la pérdida de clientes y optimizar los recursos comerciales.

🎯 Objetivos

Predecir qué clientes tienen alta probabilidad de cancelar.

Comparar distintos modelos de clasificación.

Analizar la importancia de las variables.

Proponer estrategias de retención basadas en datos.

🗂 Dataset

El dataset contiene información demográfica, contractual y de facturación de los clientes, incluyendo:

Tipo de contrato

Antigüedad 

Cargos mensuales

Servicios contratados

Método de pago

Variable objetivo: rotacion_cliente (True/False)

El problema presenta desbalance de clases, por lo que se aplicó SMOTE para balancear la clase minoritaria.

🧠 Modelos Implementados

Se entrenaron y evaluaron tres modelos de clasificación:

Regresión Logística

K-Nearest Neighbors (KNN)

Random Forest

Todos los modelos fueron implementados utilizando:

Pipeline

ColumnTransformer

Normalización (cuando aplica)

RandomizedSearchCV para optimización

Validación cruzada

🏆 Modelo Seleccionado: Random Forest

Se seleccionó Random Forest por:

Mejor ROC AUC

Mejor equilibrio entre recall y precision

Mayor estabilidad

Robustez ante alta dimensionalidad

🔍 Variables Más Importantes

El análisis de coeficientes (Regresión Logística) y la importancia de variables (Random Forest) permitió identificar los factores clave del churn:

🔴 Factores que aumentan cancelación

Contratos mensuales 
Baja antigüedad 
Cargos mensuales elevados
Algunos métodos de pago electrónicos

🟢 Factores que reducen cancelación

Contratos a largo plazo (1–2 años)

Alta antigüedad

Paquetes integrales de servicios

💡 Estrategias de Retención Propuestas

Programa de fidelización temprana para nuevos clientes

Incentivos para contratos de largo plazo

Optimización de planes con cargos elevados

Activación de campañas predictivas basadas en el score del modelo

🛠 Tecnologías Utilizadas

Python

Pandas

NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

Matplotlib

Seaborn

🚀 Cómo Ejecutar el Proyecto

Clonar el repositorio:

git clone https://github.com/tu_usuario/tu_repositorio.git

Instalar dependencias:

pip install -r requirements.txt

Ejecutar el notebook:

jupyter notebook Proyecto_final.ipynb
📈 Impacto del Proyecto

Este modelo permite:

Detectar clientes en riesgo de cancelación.

Optimizar recursos en campañas de retención.

Tomar decisiones estratégicas basadas en datos.

Reducir potencialmente la tasa de churn.

👩‍💻 Autora

Ingrid Catalina Parada Ortega
Profesional en Comercio Internacional | En transición a Data Science
Interesada en análisis de datos, visualización y modelos predictivos.


Dashboard interactivo para monitoreo del churn.

Explicabilidad avanzada con SHAP.
