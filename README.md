**Análisis Predictivo del PIB Global: Un Enfoque Multidimensional**


**Descripción del Proyecto**

Este proyecto tiene como propósito desarrollar un modelo robusto de clasificación capaz de predecir el nivel de Producto Interno Bruto (PIB) de diversos países. A diferencia de los análisis económicos tradicionales que se centran en una sola métrica, esta investigación integra indicadores sociales, demográficos y económicos provenientes de las bases de datos del Banco Mundial para capturar la complejidad del desarrollo nacional.

El enfoque principal consiste en transformar datos crudos en conocimiento accionable, utilizando técnicas avanzadas de ciencia de datos para identificar los factores subyacentes que mejor explican la variabilidad del bienestar económico global.

Objetivos Estratégicos

Imputación y Calidad de Datos: Implementar protocolos rigurosos de limpieza y tratamiento de datos faltantes para asegurar la integridad del análisis.

Reducción de Complejidad: Aplicar Análisis de Componentes Principales (PCA) para simplificar el vasto conjunto de variables macroeconómicas sin perder la esencia de la información.

Modelado Predictivo: Evaluar y desplegar algoritmos de clasificación que categoricen con precisión el nivel de PIB de un país basándose en sus métricas de desarrollo.

Estructura Metodológica

El desarrollo se divide en tres fases críticas, cada una gestionada en ramas independientes para mantener la trazabilidad del código:

Etapa 1: Análisis Exploratorio y Preprocesamiento: Caracterización del dataset, manejo de outliers y discretización del PIB en categorías (Bajo a Alto).

Etapa 2: Optimización de Dimensionalidad: Estandarización de variables numéricas y selección de componentes principales que expliquen entre el 70% y el 90% de la varianza total.

Etapa 3: Clasificación y Evaluación: Entrenamiento de modelos de aprendizaje supervisado para la predicción final del nivel económico.

Tecnologías Utilizadas

Lenguaje: Python

Bibliotecas: pandas, numpy, wbgapi (extracción de datos), scikit-learn (PCA y modelado).

Control de Versiones: Git y GitHub (siguiendo una estrategia de ramificación por etapas)
