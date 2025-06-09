# 📊 Análisis Estadístico y Preprocesamiento de Datos
*Un cuaderno de Jupyter para la aplicación práctica de técnicas fundamentales en Ciencia de Datos.*

---

## 📝 Resumen del Proyecto
Este repositorio presenta un cuaderno de Jupyter (`Analisis Estadistico Avanzado.ipynb`) donde se ponen en práctica diversas técnicas de análisis y preparación de datos. El objetivo es aplicar conceptos estadísticos en un entorno práctico, utilizando múltiples datasets (Finanzas, Cáncer y Titanic) para demostrar la versatilidad de cada método.

---

## 🛠️ Técnicas Aplicadas
El análisis se estructura en cuatro áreas clave del flujo de trabajo de un Científico de Datos.

### 1. Análisis Exploratorio y Limpieza de Datos
Se sientan las bases para cualquier análisis posterior, asegurando la calidad y comprensión del dato.
- **Manejo de Datos Faltantes:** Imputación de valores `NaN`.
- **Estadística Descriptiva:** Cálculo de medidas de tendencia central y dispersión.

### 2. Evaluación de Distribuciones
Análisis para verificar el supuesto de normalidad, un requisito común para diversos modelos estadísticos.
- **Análisis Visual:** Uso de Histogramas, Gráficos Q-Q y Boxplots.
- **Pruebas Estadísticas:** Aplicación de tests de **Shapiro-Wilk**, **Kolmogorov-Smirnov** y **D'Agostino's K²**.

### 3. Análisis de Correlación
Exploración de las relaciones entre diferentes tipos de variables para la selección de características (*feature selection*).
- **Numérica - Numérica:** Coeficiente de **Pearson** y visualización con **Mapas de Calor**.
- **Categórica - Categórica:** Tablas de contingencia y prueba **Chi-cuadrado (χ²)**.
- **Numérica - Categórica:** **ANOVA** (para +2 grupos) y **Test t de Student** (para 2 grupos) con pruebas **Post-Hoc de Tukey** para identificar diferencias significativas.

### 4. Preprocesamiento y Transformación de Datos
Técnicas de ingeniería de características para optimizar los datos antes de introducirlos en un modelo.
- **Manejo de Outliers:** Detección con Rango Intercuartílico (IQR) y tratamiento con **Winsorización**.
- **Escalado y Normalización:** Aplicación de **Escalado Min-Max** y **Transformación de Box-Cox**.
- **Discretización (Binning):** Conversión de variables numéricas a categóricas (ej. "Edad" a "Joven", "Adulto").

---

## 💻 Tecnologías Utilizadas
- **Python**
- **Pandas** y **NumPy**
- **Matplotlib** y **Seaborn**
- **SciPy** y **Statsmodels**

---
## 👨‍💻 Autor
Gustavo Castellon
Estudiante de Licenciatura en Ciencia de Datos.

LinkedIn: https://linkedin.com/in/ichbinzeed
