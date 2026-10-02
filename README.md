# Electiva Profesional I

Este repositorio contiene un notebook de práctica para aprender a importar, inspeccionar y manipular datos con Python y `pandas`.

## ¿De qué trata el proyecto?

El proyecto está orientado a la introducción del manejo de datos en distintos formatos, principalmente:

- CSV (texto plano)
- Excel (.xlsx)
- JSON (datos semiestructurados)

Se usa un conjunto de datos de productos de una librería para mostrar cómo:

- leer archivos con `pd.read_csv()` y `pd.read_excel()`
- visualizar tablas con `DataFrame`
- inspeccionar columnas, tipos de datos y contenido
- trabajar con datos semiestructurados en formato JSON
- comenzar con análisis inicial y limpieza básica de datos

## Contenido

- `Importación_y_manejo_de_datos_Electiva_pro_II.ipynb`: notebook principal con ejemplos prácticos y explicaciones.

## Herramientas utilizadas

- Python
- Pandas
- Jupyter Notebook / Google Colab

## Objetivo del curso

El objetivo es que el estudiante comprenda cómo importar datos desde fuentes reales y prepararlos para análisis posteriores, aprendiendo las bases de la ciencia de datos con Python.

## Cómo abrir el proyecto

Puedes abrir el notebook directamente en GitHub o ejecutarlo en Google Colab con el enlace incluido en el archivo `.ipynb`.

## Ejemplo de uso

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/.../productos.csv", sep=";")
print(df.head())
```

Esta práctica sirve como base para futuros análisis de datos, limpieza, transformación y visualización.
