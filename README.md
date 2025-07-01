Análisis y Predicción de Evasión de Clientes en Telecom X
📌 Descripción del Proyecto
Este proyecto tiene como objetivo identificar los factores que influyen en la evasión de clientes (churn) en Telecom X y construir modelos predictivos que permitan anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios.

El proyecto se desarrolla en dos partes:

Parte 1: Análisis exploratorio de datos (EDA) y limpieza de datos.

Parte 2: Modelado predictivo usando algoritmos de clasificación y análisis de variables clave.

📁 Estructura del Proyecto
El proyecto está compuesto por dos notebooks principales:

TelecomX_Churn_Analysis.ipynb: análisis exploratorio y limpieza de datos.

TelecomX_Churn_Modeling.ipynb: entrenamiento y evaluación de modelos predictivos.

Parte 2 – Contenido del Notebook de Modelado
Importación de librerías

Carga del conjunto de datos limpio

Preprocesamiento y codificación de variables

Análisis de balanceo de clases con SMOTE

División en conjuntos de entrenamiento y prueba

Normalización de variables

Entrenamiento de modelos:

Regresión Logística

Random Forest

Evaluación de modelos con métricas:

Precisión, Recall, F1-Score

Matriz de confusión

Análisis de importancia de variables

Conclusiones estratégicas

🧰 Requisitos y Dependencias
Instala las siguientes librerías para ejecutar el proyecto:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
📊 Datos Utilizados
Los datos fueron obtenidos desde una API pública en formato JSON:

URL: https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json

Después del preprocesamiento en la Parte 1, el conjunto final incluye información sobre:

Perfil del cliente

Servicios contratados

Tipo de contrato

Métodos de pago

Cargos y permanencia

Estado de cancelación (Churn)

📈 Resultados y Conclusiones
Modelos Entrenados
Regresión Logística: Requiere normalización. Buen desempeño general.

Random Forest: Sin necesidad de normalización. Mostró mayor robustez y precisión.

Principales Variables Predictoras
Tipo de contrato

Método de pago

Cargos mensuales

Permanencia del cliente

Recomendaciones Estratégicas
Promover contratos de mayor duración para reducir la evasión.

Implementar estrategias de retención durante los primeros meses del cliente.

Ofrecer beneficios por métodos de pago automáticos.

Evaluar la experiencia del cliente con cargos elevados.

Incentivar el uso de servicios de valor agregado como soporte técnico y seguridad.

👤 Autor
Mery Vega M. – Estudiante de Ciencia de Datos

