# telecom-analysis
🚀 Análisis de Comportamiento de Clientes: ConnectaTel 2024
Este proyecto se enfoca en el rol de un Analista de Datos encargado de evaluar y optimizar el rendimiento de ConnectaTel, una empresa de telecomunicaciones líder en Latinoamérica. El análisis utiliza datos operativos registrados hasta el año 2024 para extraer inteligencia de negocio, identificar perfiles de consumo y detectar oportunidades estratégicas.

📋 Descripción del Proyecto
El objetivo principal es transformar datos crudos en conclusiones accionables. A través de un proceso de limpieza, exploración estadística y segmentación avanzada, el proyecto busca:

Construir un perfil estadístico detallado de los clientes.

Detectar comportamientos atípicos (outliers) que impactan la rentabilidad.

Diseñar estrategias de retención basadas en patrones de churn.

Optimizar la oferta comercial de los planes actuales.

📊 Datasets Utilizados
El repositorio incluye tres fuentes de datos principales que permiten una visión 360° del negocio:

plans.csv: Diccionario de los planes comerciales (precios base, cuotas de minutos/GB y costos por excedentes).

users.csv: Datos demográficos y contractuales (edad, ubicación, fecha de registro y estado de permanencia).

usage.csv: Registro transaccional del uso real de servicios (volumen de llamadas y mensajería).

🛠️ Metodología de Análisis
El desarrollo sigue un enfoque programático y estructurado:

ETL & Data Cleaning: Tratamiento de valores nulos, corrección de tipos de datos y unificación de fuentes.

EDA (Exploratory Data Analysis): Análisis de medidas de tendencia central, varianza y distribución de frecuencias.

Gestión de Outliers: Aplicación del método IQR (Interquartile Range) para validar si los consumos extremos son errores técnicos o Power Users altamente rentables.

Segmentación de Clientes: Clasificación basada en lógica de negocio por nivel de uso y rangos etarios.

Pruebas de Hipótesis: Validación estadística para comparar la rentabilidad entre planes.

💡 Competencias Aplicadas
Python: Pandas, NumPy.

Visualización de Datos: Matplotlib, Seaborn.

Estadística: Análisis descriptivo e inferencial.

Business Intelligence: Segmentación y toma de decisiones basada en datos.

🚀 ¿Cómo empezar?
Clona el repositorio.

Asegúrate de tener instaladas las dependencias necesarias (pip install pandas matplotlib seaborn).

Ejecuta el notebook principal para ver el flujo de análisis completo.

Cambiar la ubicación de los repositorios .csv para poder ejecutarlos, estos son de ejemplo ya que por porteccion de datos no se pueden entrar los .csv originales
