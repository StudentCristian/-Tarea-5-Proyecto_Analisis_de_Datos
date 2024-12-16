# Proyecto de Análisis Exploratorio de Datos - Titanic

Este repositorio contiene un proyecto de análisis exploratorio de datos (EDA) basado en el conjunto de datos del Titanic. El objetivo principal es explorar las variables del dataset, identificar patrones relevantes y entrenar un modelo predictivo para predecir la supervivencia de los pasajeros.

## Descripción del Proyecto

El proyecto incluye las siguientes etapas principales:

1. **Clasificación de Variables**: Las variables del conjunto de datos se clasifican en `categóricas` y `numéricas`, con una subclasificación adicional en `nominales`, `ordinales`, `discretas` y `continuas`.

2. **Análisis Descriptivo**: Se analizan las cantidades totales y las estadísticas de cada variable para entender su comportamiento individual.

3. **Visualizaciones**: Uso de bibliotecas como `Matplotlib` y `Seaborn` para crear gráficos que muestran distribuciones y relaciones entre las variables.

4. **Preparación del Modelo Predictivo**: Con base en los hallazgos del EDA, se entrena un modelo de Regresión Logística para predecir la supervivencia de los pasajeros, evaluando su rendimiento con métricas como Precisión, Recall y F1-Score.

## Estructura del Repositorio

- `EDA.ipynb`: Notebook principal que contiene el código y el análisis realizado.
- `datasets/Titanic-Dataset.csv`: Conjunto de datos utilizado en el proyecto.

## Requisitos

Para ejecutar el notebook, asegúrate de tener instalado lo siguiente:

- Python 3.8 o superior
- Bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Puedes instalar las dependencias con:

```bash
pip install -r requirements.txt
```

## Ejecución

1. Clona el repositorio:

```bash
git clone https://github.com/StudentCristian/-Tarea-5-Proyecto_Analisis_de_Datos.git
```

2. Navega al directorio del proyecto:

```bash
cd -Tarea-5-Proyecto_Analisis_de_Datos
```

3. Ejecuta el notebook:

```bash
jupyter notebook EDA.ipynb
```

## Resultados

El modelo de Regresión Logística desarrollado alcanzó una precisión del 78%, con mejor desempeño al identificar a los pasajeros que no sobrevivieron (recall del 83%). Los resultados sugieren que el modelo es funcional, pero podría mejorarse mediante técnicas de balanceo de clases y optimización de hiperparámetros.

## Enlace al Repositorio

[Repositorio en GitHub](https://github.com/StudentCristian/-Tarea-5-Proyecto_Analisis_de_Datos)

---
