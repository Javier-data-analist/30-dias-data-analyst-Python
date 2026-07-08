# Proyecto Final: Análisis de Correlación Tesla y GameStop

*Certificado Profesional de IBM Data Science - Coursera*

### Objetivo del Proyecto
Analizar la relación entre el precio de las acciones de Tesla (TSLA) y GameStop (GME) y sus ingresos trimestrales reportados. La pregunta central: ¿Los movimientos en bolsa responden a los resultados financieros fundamentales?

### Metodología y Proceso
1. *Extracción de datos*: Se obtuvieron datos históricos de precios de TSLA y GME de los últimos 5 años mediante la librería yfinance.
2. *Web Scraping*: Los ingresos trimestrales se extrajeron de Yahoo Finance utilizando pandas.read_html y BeautifulSoup para el parseo de HTML.
3. *Procesamiento de datos*: Se realizó limpieza de datos, incluyendo la alineación de fechas entre series temporales diarias y trimestrales, manejo de valores nulos y conversión de tipos de datos.
4. *Visualización*: Se crearon gráficas comparativas con matplotlib para superponer la evolución del precio de la acción con los ingresos reportados por trimestre.

### Principales Hallazgos
El análisis mostró que Tesla presenta mayor correlación entre reportes de ingresos y movimientos posteriores en el precio de la acción. En contraste, GameStop mostró periodos de alta volatilidad no directamente relacionados con sus resultados financieros fundamentales.

### Stack Tecnológico
Python Pandas NumPy yfinance Requests BeautifulSoup Matplotlib Jupyter Notebook

### Resultados Visuales
![Grafica Tesla vs Ingresos](url-de-tu-imagen-aqui)

### Cómo Replicar el Proyecto
1. Clonar el repositorio: git clone https://github.com/Javier-data-analist/30-dias-data-analyst-Python.git
2. Abrir Proyecto_final_Tesla_GameSTOP.ipynb en Jupyter Notebook o Google Colab
3. Ejecutar todas las celdas para reproducir el análisis completo

### Conclusión
Este proyecto demuestra el ciclo completo de un análisis de datos: desde la definición de una hipótesis de negocio, la extracción y limpieza de datos de múltiples fuentes, hasta la visualización y comunicación de insights.

---
*Autor*: Javier Rangel Zuñiga
