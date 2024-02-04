# Taller de Machine Learning: Boston House Prices Dataset

Este proyecto tiene como objetivo explorar diversas estrategias de ingeniería de características en el contexto de un problema de regresión lineal utilizando el conjunto de datos de precios de casas de Boston. Se utilizará un modelo de regresión lineal estándar y se evaluará su desempeño en diferentes escenarios de preprocesamiento de datos.

## Estrategias de Ingeniería de Características

1. **Características Originales:**
   - Entrenamiento del modelo con las características originales proporcionadas por `sklearn.datasets.load_boston`.

2. **Características Escaladas:**
   - Entrenamiento del modelo con características escaladas utilizando diversos métodos disponibles en `sklearn.preprocessing`.

3. **Características Proyectadas con PCA:**
   - Utilización de PCA para proyectar el conjunto de datos sobre los dos primeros componentes principales.

4. **Binning y Características de Interacción:**
   - Aplicación de binning y generación de características de interacción. Se realizará binning en características continuas.

5. **Características Polinómicas:**
   - Generación de características polinómicas con diferentes grados. Elección del grado que proporciona el mejor desempeño.

## Propósito del Taller

- **Exploración de Estrategias de Preprocesamiento:**
  - Comprender cómo diferentes técnicas de ingeniería de características pueden afectar el rendimiento de un modelo de regresión lineal.

- **Evaluación del Impacto en el Modelo:**
  - Comparar y analizar cómo cada estrategia impacta la capacidad del modelo para realizar predicciones precisas.

- **Toma de Decisiones Informada:**
  - Proporcionar información sobre qué estrategias de ingeniería de características pueden ser más beneficiosas en el contexto de un problema de regresión lineal.

- **Práctica con Herramientas de Machine Learning:**
  - Familiarizarse con el uso de funciones y herramientas de la biblioteca scikit-learn para implementar diferentes estrategias de preprocesamiento.

## Instrucciones para el Desarrollo

El proyecto se ha desarrollado en un archivo Jupyter Notebook (NombreArchivo.ipynb) y se encuentra disponible en el siguiente repositorio de GitHub:

[Enlace al Repositorio](https://github.com/gustavo198saavedra/Taller2)

El objetivo es analizar y comprender cómo las distintas estrategias de ingeniería de características afectan el rendimiento del modelo de regresión lineal en un problema práctico de predicción de precios de casas en Boston. Cada estrategia se implementa y se evalúa exhaustivamente para tomar decisiones informadas sobre su impacto.

Este ejercicio proporciona una valiosa práctica en el uso de técnicas de preprocesamiento de datos, una habilidad esencial en la construcción de modelos de machine learning efectivos. ¡Disfruta del aprendizaje!
