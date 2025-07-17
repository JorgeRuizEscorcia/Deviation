# Deviation
# 📊 Análisis de Desviación en Resultados Saber Pro (2021–2022)

Este proyecto analiza estadísticamente la evolución de los puntajes del examen Saber Pro entre los años 2021 y 2022, aplicando técnicas de inferencia, visualización y detección de outliers.

---

## 🎯 Objetivo

Evaluar si existen diferencias significativas entre los resultados de los estudiantes en distintas cohortes y periodos académicos del examen Saber Pro, identificando patrones, anomalías y tendencias relevantes.

---

## 📁 Datos

- Archivo utilizado: `2021-20221-20222 Saber Pro-2.xlsx`
- Columnas clave:
  - `saber2021`
  - `saber20221`
  - `saber20222`
  - `saber2022G`

---

## 🧪 Metodología

### 1. Preprocesamiento
- Carga del archivo desde Google Drive.
- Eliminación de filas con valores nulos.
- Cálculo de estadísticas básicas.

### 2. Pruebas de hipótesis
- Se aplicaron **pruebas t para muestras independientes** para comparar los puntajes entre diferentes periodos:
  - `saber2021` vs. `saber20221`
  - `saber20221` vs. `saber20222`
  - `saber20222` vs. `saber2022G`
- Se reportan estadísticos t y valores p para cada comparación.

### 3. Visualización de la distribución
- Histogramas con curvas de distribución normal ajustada.
- Estimaciones de media y desviación estándar para cada cohorte.
- Comparación entre distribuciones.

### 4. Análisis gráfico combinado
- Comparación visual entre cohortes usando histogramas superpuestos.
- Inclusión de curvas normales estimadas y marcas de mediana.
- Boxplots con indicadores de media, mediana, cuartiles e identificación de outliers.

### 5. Limpieza de datos
- Identificación y eliminación de valores atípicos usando el rango intercuartílico (IQR).
- Análisis posterior de la muestra limpia.

---

## 🧰 Tecnologías y librerías

- **Python** (Google Colab)
- **Pandas**, **NumPy** – Manipulación y análisis de datos.
- **SciPy**, **Statsmodels** – Pruebas estadísticas.
- **Seaborn**, **Matplotlib** – Visualizaciones.

---

## 📈 Ejemplos de salidas gráficas

- Histogramas con distribución normal ajustada.
- Boxplots multivariables con datos sin outliers.
- Gráficos comparativos entre cohortes.

---

## 📚 Referencias

- Instituto Colombiano para la Evaluación de la Educación (ICFES) – Saber Pro.
- Técnicas de análisis estadístico comparativo.
- Prueba t de Student para muestras independientes.

---

## 👨‍💻 Autor

**Jorge Ruiz Escorcia**  
📧 jorgeruizescorcia@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/jorge-ruiz-escorcia/)  
🔗 [GitHub](https://github.com/JorgeRuizEscorcia)

---

## 📜 Licencia

Este análisis se comparte con fines educativos y de investigación.
