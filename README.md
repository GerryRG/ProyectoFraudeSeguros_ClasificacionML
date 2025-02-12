# Análisis de Datos e Implementación de Modelos de Clasificación en un conjunto de fraudes en seguros de autos

## Descripción
Este proyecto tiene como objetivo analizar un conjunto de datos de reclamaciones de seguros de automóviles e implementar modelos de clasificación para predecir casos de fraude. Se presenta un enfoque completo que incluye, análisis exploratorio, limpieza de datos, preproceamiento de datos y la aplicación de modelos de aprendizaje automático (regresión logística, random forest y maquinas de soporte vectorial).

## Contexto: Detección de Fraudes en Seguros
El fraude de seguros implica actividades engañosas como la fabricación de incidentes falsos, la manipulación de hechos y la exageración de daños con el fin de obtener beneficios económicos indebidos. En el caso de las aseguradoras de automóviles, este problema genera pérdidas significativas. La detección manual de fraudes no es viable debido a los altos costos en tiempo y dinero, por lo que el uso de modelos de aprendizaje automático se convierte en una estrategia clave.

## Objetivo del Proyecto

El objetivo principal es implementar modelos de aprendizaje automático que permita identificar reclamaciones fraudulentas en seguros de automóviles, optimizando así la detección de fraudes y reduciendo las pérdidas para las aseguradoras.

## Conjunto de datos
El conjunto de datos utilizado en este proyecto fue extraído de la plataforma Kaggle y está disponible en el [siguiente enlace](https://www.kaggle.com/datasets/mykeysid10/insurance-claims-fraud-detection)

## Contenido del [noteboook](Seguros_DeteccionFraudes/InsuranceClaims_FraudDetection.ipynb)
1. Introducción
    - Explicación del problema del fraude en seguros de autos.
    - Importancia de la detección automatizada de fraudes.
    - Conjunto de datos y diccionario
2.	Análisis Exploratorio de Datos (EDA)
    - Distribución de las variables.
    - Análisis numérico (medidas de tendencia central y dispersion)
    - Análisis Grafico (Barras, bloxplot)
    - Análisis de correlaciones para variables numericas
3. Preprocesamiento y Limpieza de Datos
    - Manejo de valores nulos y duplicados.
    - Codificación de variables ordinales y nominales.
    - Normalización y escalado de datos.
    - Manejo del desbalanceo de clases
3.	Selección de Características
    - Análisis estadístico con pruebas de Chi-cuadrado (Chi2) y ANOVA.
    - Uso de Logit y Random Forest para la selección de características.
4.	Implementación de Modelos de Clasificación
    - Modelos utilizados: Regresión Logística, Árboles de Decisión y Maquinas de Soporte Vcetorial.
    - Comparación de desempeño de los modelos.
    - Métricas de evaluación (precisión, recall, F1-score, matriz de confusión).
5.	Conclusiones
    - Análisis de los resultados obtenidos.
    - Reflexiones sobre la efectividad de los modelos.

### Autor: Ramos García Luis Gerardo
### Última Actualización: 23 de enero de 2025
