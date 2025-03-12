# Análisis de Comportamiento de Usuario en Páginas Web

## Tecnologías Utilizadas

- **Python**: Lenguaje principal para el análisis de datos.
- **Jupyter Notebook**: Entorno interactivo para desarrollar y documentar el análisis.
- **Librerías de Python**:
  - `pandas`: Para manipulación y análisis de datos.
  - `numpy`: Para operaciones numéricas.
  - `matplotlib` y `seaborn`: Para visualización de datos.
  - `scipy`: Para análisis estadístico.

## Resumen del Análisis

El objetivo de este proyecto es analizar el comportamiento de los usuarios en una página web para comprender su interacción y mejorar la experiencia del usuario. Se llevaron a cabo las siguientes etapas:

1. **Carga y Exploración de Datos**: Se importaron los datos de registros de usuarios y se realizó una exploración inicial para comprender su estructura y contenido.
2. **Limpieza de Datos**: Se manejaron valores nulos, duplicados y se corrigieron inconsistencias en los datos para garantizar su calidad.
3. **Análisis Exploratorio de Datos (EDA)**: Se generaron estadísticas descriptivas y visualizaciones para identificar patrones de comportamiento y posibles áreas de mejora en la página web.
4. **Análisis del Embudo de Conversión**: Se evaluaron las etapas del embudo de ventas para identificar en qué puntos los usuarios abandonan el proceso de compra.
5. **Pruebas A/A/B**: Se realizaron pruebas para comparar diferentes versiones de la página y determinar cuál proporciona una mejor experiencia al usuario.

## Conclusiones del Análisis

El análisis reveló que ciertos pasos en el proceso de compra presentan una alta tasa de abandono, sugiriendo la necesidad de optimizar estas etapas. Las pruebas A/A/B indicaron que la versión B de la página mejora la tasa de conversión en un 15% en comparación con la versión A, recomendando su implementación.

## Contenido del Directorio `Análisis de Comportamiento de Usuario en Páginas Web`

- **`Proyecto_11_revizado.ipynb`**: Notebook principal que documenta todo el proceso de análisis, desde la carga y limpieza de datos hasta las conclusiones y recomendaciones.
- **`datos/`**: Directorio que contiene los conjuntos de datos utilizados en el análisis.
  - `logs.csv`: Archivo con los registros de actividad de los usuarios en la página web.
  - `clean_logs.csv`: Archivo con los registros depurados y listos para el análisis.
- **`visualizaciones/`**: Carpeta que almacena las gráficas y visualizaciones generadas durante el análisis.
  - `embudo_conversion.png`: Gráfico que muestra las etapas del embudo de conversión y las tasas de abandono en cada una.
  - `pruebas_aa_b.png`: Visualización de los resultados de las pruebas A/A/B realizadas.

Este README proporciona una visión general del análisis realizado y detalla el contenido del directorio `Análisis de Comportamiento de Usuario en Páginas Web`. Para más información, se recomienda revisar el notebook principal y los archivos asociados.
