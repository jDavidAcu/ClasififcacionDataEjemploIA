# Clasificación de Clientes con IA - Proyecto Final

Este proyecto fue desarrollado como parte de la materia de **Inteligencia Artificial**, con el objetivo de aplicar técnicas de **clustering** y **clasificación** para la **gestión de ofertas y descuentos en clientes** de una tienda de comestibles.

Autores:  
- **José Acuña**  
- **Alejandro Curay**

## Descripción del Proyecto

A partir de un conjunto de datos reales de clientes (ver archivo `Customer_Data.csv`), se busca agrupar a los clientes según su comportamiento y características. Luego, se entrenan modelos de clasificación para etiquetar a nuevos clientes en base a los clusters obtenidos.

### Objetivo

El objetivo es facilitar la **administración de promociones y descuentos personalizados** mediante una categorización inteligente de los clientes.

---

## Estructura del Análisis

### Parte 1: Pre-procesamiento de los Datos

- Limpieza y tratamiento de valores vacíos.
- Conversión de variables categóricas a numéricas.
- Normalización de las variables numéricas.
- Selección y justificación de las variables utilizadas.

### Parte 2: Análisis Exploratorio

- Visualización de variables con **boxplots**.
- Detección y eliminación de outliers utilizando el **rango intercuartílico (IQR)**.
- Nuevos boxplots para verificar la limpieza de datos.

### Parte 3: Clustering

- Reducción de dimensionalidad para visualización con PCA.
- Aplicación de **K-Means** y evaluación visual/cuantiativa.
- Aplicación de **DBSCAN** y evaluación.
- Comparación entre los métodos y selección del más adecuado.
- Interpretación de los clusters mediante estadísticas descriptivas.

### Parte 4: Clasificación

- Generación de tres modelos clasificadores con algoritmos diferentes.
- Evaluación de cada modelo con métricas como **precisión**, **recall** y **f1-score**.
- Selección del mejor modelo y prueba con un cliente nuevo simulado.

---

## Archivos del Proyecto

- 📒 `Proyecto Final - Jose Acuña - Alejandro Curay.ipynb`: Notebook con todo el análisis, visualizaciones, modelos y pruebas.
- 📄 `Customer_Data.csv`: Archivo de datos original utilizado para el análisis.
  
---

## Requisitos

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

Para instalar dependencias necesarias:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
