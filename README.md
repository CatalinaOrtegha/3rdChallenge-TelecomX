1️⃣ Objetivo del análisis

El objetivo del proyecto fue desarrollar modelos de machine learning capaces de predecir la cancelación de clientes (rotacion_cliente) e identificar los factores más influyentes en dicha decisión, con el fin de proponer estrategias efectivas de retención.

2️⃣ Modelos Evaluados

Se entrenaron tres modelos de clasificación:

Regresión Logística

K-Nearest Neighbors (KNN)

Random Forest

🔎 Resultados comparativos

La Regresión Logística detecta más clientes en riesgo (mayor recall).

Random Forest presenta mejor equilibrio general y mayor capacidad discriminativa (ROC AUC más alto).

KNN mostró rendimiento similar, pero menor interpretabilidad.

Debido a su mejor balance general, Random Forest fue seleccionado como modelo final.

3️⃣ Variables más influyentes en la cancelación

El análisis de coeficientes (Regresión Logística) y la importancia de variables (Random Forest) permitió identificar los factores más relevantes.

🔴 Factores que AUMENTAN la probabilidad de cancelación

1️⃣ Tipo de contrato mensual 
2️⃣ Cargos mensuales elevados
3️⃣ Servicios adicionales con alto costo
4️⃣ Método de pago electrónico automático
5️⃣ Baja antigüedad

🟢 Factores que REDUCEN la probabilidad de cancelación

1️⃣ Alta antigüedad del cliente 
2️⃣ Contratos a largo plazo
3️⃣ Paquetes integrales de servicios
4️⃣ Pagos automáticos bancarios estables

4️⃣ Interpretación estratégica de los factores
🎯 1. Antigüedad 

Es uno de los factores más importantes.

Clientes nuevos tienen mayor probabilidad de cancelar.

🔎 Interpretación:
Existe una etapa crítica inicial donde el cliente aún no desarrolla lealtad.

🎯 2. Tipo de contrato

Los contratos mensuales presentan mayor cancelación.

🔎 Interpretación:
La falta de compromiso contractual facilita la salida.

🎯 3. Cargos mensuales altos

Clientes con facturación elevada muestran mayor probabilidad de cancelación.

🔎 Interpretación:
Sensibilidad al precio y percepción de bajo valor.

🎯 4. Métodos de pago específicos

Algunos métodos electrónicos se asocian con mayor cancelación.

🔎 Interpretación:
Puede relacionarse con perfiles más digitales y menos fidelizados.

5️⃣ Estrategias de retención propuestas

Basado en los hallazgos del modelo:

🔵 Estrategia 1: Programa de fidelización temprana

Dado que la cancelación es mayor en clientes nuevos:

Contacto proactivo en los primeros 3 meses

Encuestas de satisfacción tempranas

Beneficios exclusivos de bienvenida

Objetivo: Reducir cancelación en etapa crítica inicial.

🟢 Estrategia 2: Incentivar contratos de largo plazo

Dado que contratos mensuales presentan mayor cancelación:

Descuentos por contratos anuales

Beneficios exclusivos por permanencia

Programas de puntos acumulativos

Objetivo: Aumentar compromiso contractual.

🟡 Estrategia 3: Revisión de estructura de precios

Clientes con cargos altos cancelan más.

Ofrecer paquetes personalizados

Descuentos escalonados por permanencia

Alertas de optimización de plan

Objetivo: Reducir percepción de sobrecosto.

🔴 Estrategia 4: Segmentación predictiva

Utilizar el modelo para:

Identificar clientes en riesgo (score > threshold)

Activar campañas específicas de retención

Priorizar recursos en clientes de mayor valor

6️⃣ Conclusiones Generales

1️⃣ La cancelación puede predecirse con buen nivel de precisión (ROC AUC 0.83).
2️⃣ La antigüedad y el tipo de contrato son los factores más determinantes.
3️⃣ Random Forest mostró el mejor equilibrio entre capacidad predictiva y estabilidad.
4️⃣ Las estrategias de retención deben enfocarse especialmente en clientes nuevos y contratos mensuales.

7️⃣ Impacto potencial en negocio

Si el modelo se implementa:

Se puede reducir la tasa de cancelación anticipando clientes en riesgo.

Se optimiza el presupuesto de campañas de retención.

Se mejora la rentabilidad mediante segmentación inteligente.



Este análisis no solo permite predecir la cancelación, sino también comprender los factores estructurales que la impulsan, habilitando decisiones estratégicas basadas en datos.
