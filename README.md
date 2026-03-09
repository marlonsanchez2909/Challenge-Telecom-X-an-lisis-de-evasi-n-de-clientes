Challenge Telecom X
Análisis de evasión de clientes (Churn)
Introducción

Este proyecto corresponde a un Challenge del programa ONE de Alura Latam, en el cual se plantea un caso de análisis de datos enfocado en la evasión de clientes (Churn) dentro de una empresa ficticia de telecomunicaciones llamada Telecom X.

En este escenario, la compañía enfrenta un alto índice de cancelación de servicios por parte de sus clientes, sin haber identificado aún las causas principales de este problema. Por esta razón, se requiere el apoyo de un analista de datos que pueda examinar la información disponible, realizar procesos de limpieza y transformación de datos, y posteriormente desarrollar un análisis exploratorio que permita identificar patrones relevantes.

El objetivo del análisis es preparar y estructurar los datos para que posteriormente el equipo de ciencia de datos pueda utilizarlos en la construcción de modelos predictivos capaces de anticipar el abandono de clientes y proponer estrategias de retención.

Descripción del proyecto

Este repositorio contiene un análisis exploratorio de datos (EDA) aplicado a un conjunto de información de clientes de una empresa de telecomunicaciones. El trabajo abarca todo el proceso de análisis, desde la extracción de los datos desde una API en formato JSON, hasta su limpieza, transformación y visualización.

El propósito principal es transformar datos sin procesar en información útil para la toma de decisiones, permitiendo identificar los factores que influyen en la cancelación del servicio por parte de los clientes.

Como resultado del análisis se generan insights basados en datos, los cuales pueden ser utilizados por la gerencia para desarrollar estrategias orientadas a reducir la tasa de abandono y mejorar la fidelización de los clientes.

Objetivo del análisis

El proyecto busca responder tres preguntas clave desde una perspectiva empresarial:

¿Quiénes son los clientes que abandonan la empresa?
Identificar las características principales del perfil de clientes con mayor probabilidad de cancelación.

¿Cuáles son los factores que influyen en la evasión de clientes?
Analizar variables relacionadas con contratos, servicios, costos y comportamiento del usuario.

¿Qué acciones pueden implementarse para reducir la tasa de cancelación?
Proponer recomendaciones estratégicas basadas en los resultados del análisis.

El objetivo final es proporcionar información clara y basada en datos que sirva como apoyo para la toma de decisiones dentro de la empresa.

Tecnologías utilizadas

El análisis se realizó en un entorno de Python dentro de Google Colab, utilizando herramientas ampliamente utilizadas en ciencia de datos.

Principales librerías utilizadas:

Python – Lenguaje principal para el análisis de datos.

Pandas – Manipulación, limpieza y transformación de datos.

NumPy – Operaciones numéricas y manejo de valores nulos.

Matplotlib / Plotly – Visualización de datos y generación de gráficos.

Requests – Extracción de datos desde una API en formato JSON.

Google Colab – Entorno de desarrollo en la nube para la ejecución del proyecto.

Metodología de análisis

El proyecto sigue una estructura basada en las etapas principales del análisis de datos.

1. Extracción de datos

Los datos utilizados en el proyecto fueron obtenidos a partir de una API que proporciona la información en formato JSON. Esta información fue cargada directamente en el entorno de Google Colab para su procesamiento.

2. Limpieza y transformación de datos (ETL)

Durante esta etapa se realizaron diferentes procesos de preparación de los datos:

Normalización de la estructura JSON para convertirla en un DataFrame tabular.

Conversión de variables a sus tipos de datos correctos.

Identificación y tratamiento de valores nulos o inconsistentes.

Estandarización de variables categóricas.

Este proceso permitió obtener un conjunto de datos limpio y preparado para el análisis exploratorio.

3. Análisis exploratorio de datos (EDA)

En esta etapa se analizaron diferentes variables del conjunto de datos con el fin de identificar patrones relacionados con la cancelación de clientes.

El análisis incluyó:

Análisis univariado
Estudio de la distribución de variables individuales.

Análisis bivariado
Comparación de la variable Churn con otras variables del dataset.

Análisis multivariado
Exploración de la interacción entre múltiples variables para identificar relaciones más complejas.

4. Visualización de datos

Se desarrollaron diferentes gráficos y visualizaciones con el objetivo de facilitar la interpretación de los resultados y comunicar los hallazgos de manera clara.

Las visualizaciones permiten identificar tendencias y patrones relevantes dentro de los datos analizados.

Principales hallazgos del análisis

A partir del análisis exploratorio se identificaron varios factores que influyen significativamente en la evasión de clientes.

Tipo de contrato

Los clientes con contratos mes a mes (Month-to-month) presentan una tasa de cancelación considerablemente mayor en comparación con los contratos anuales o de largo plazo.

Tipo de servicio de internet

Los clientes que utilizan fibra óptica presentan una mayor tasa de cancelación en comparación con los clientes que utilizan DSL.

Servicios adicionales

La ausencia de servicios complementarios como soporte técnico o seguridad online está asociada con una mayor probabilidad de cancelación.

Antigüedad del cliente

Los clientes con poco tiempo en la empresa presentan mayor probabilidad de abandonar el servicio, especialmente cuando los costos mensuales son elevados.

Nivel de compromiso con la empresa

Los clientes que contratan más servicios adicionales tienden a mostrar una mayor permanencia en la compañía, lo que sugiere que un mayor nivel de integración con los servicios de la empresa incrementa la fidelidad del cliente.

Informe ejecutivo y recomendaciones
Perfil del cliente con mayor riesgo de cancelación

El cliente con mayor probabilidad de abandonar el servicio suele presentar las siguientes características:

Contrato de mes a mes.

Baja antigüedad en la empresa.

Uso de cheque electrónico como método de pago.

Servicio de fibra óptica sin soporte técnico adicional.

Estrategias recomendadas

A partir de los resultados obtenidos se sugieren las siguientes acciones estratégicas:

1. Mejorar la propuesta de valor del servicio de fibra óptica

Incluir servicios como soporte técnico y seguridad online dentro de los paquetes iniciales para mejorar la experiencia del cliente.

2. Incentivar contratos de mayor duración

Desarrollar campañas que motiven a los clientes con contratos mensuales a migrar hacia planes anuales, ofreciendo beneficios adicionales.

3. Programa de acompañamiento para nuevos clientes

Implementar un programa de onboarding durante los primeros 90 días, especialmente para clientes de fibra óptica, con el fin de garantizar una buena experiencia inicial.

Cómo ejecutar el proyecto en Google Colab

Para ejecutar este análisis puedes seguir los siguientes pasos:

Accede a Google Colab
https://colab.research.google.com/

Carga el archivo del proyecto
Puedes subir el archivo .ipynb directamente desde el menú Archivo → Subir notebook.

Ejecuta las celdas del notebook
Ejecuta cada celda de código de forma secuencial para reproducir el análisis completo.

Explora las visualizaciones
Algunos gráficos son interactivos y permiten explorar los datos con mayor detalle.
