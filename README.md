# Telecom Analysis - Sprint 7

## 📌 Objetivo del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de ConnectaTel mediante técnicas de análisis exploratorio de datos (EDA), con el fin de identificar patrones de uso, segmentar a los usuarios y generar recomendaciones para mejorar la oferta de planes de telefonía.

---

## 📂 Datasets utilizados

El proyecto utiliza dos conjuntos de datos:

- **users**: información demográfica y del plan de cada usuario.
  - user_id
  - first_name
  - last_name
  - age
  - city
  - reg_date
  - plan
  - churn_date

- **usage**: historial de uso de los clientes.
  - user_id
  - type (call o text)
  - duration

---

## 🔎 Etapas del análisis

Durante el desarrollo del proyecto se realizaron las siguientes etapas:

1. Exploración inicial de los datos.
2. Limpieza y preparación de datos.
3. Identificación y tratamiento de valores nulos.
4. Detección de valores centinela.
5. Conversión de tipos de datos.
6. Creación de variables de uso por usuario.
7. Análisis estadístico descriptivo.
8. Visualización de distribuciones mediante histogramas.
9. Detección de valores atípicos (Outliers) mediante Boxplots e IQR.
10. Segmentación de clientes por edad y nivel de uso.
11. Elaboración de conclusiones y recomendaciones para el negocio.

---

## 🛠 Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ Cómo ejecutar el notebook

### Opción 1. Jupyter Notebook

1. Clonar este repositorio.
2. Instalar las dependencias necesarias.
3. Abrir el archivo `.ipynb` con Jupyter Notebook o JupyterLab.
4. Ejecutar las celdas en orden.

### Opción 2. Google Colab

1. Descargar el notebook.
2. Abrir Google Colab.
3. Seleccionar **Archivo → Subir notebook**.
4. Elegir el archivo `.ipynb`.
5. Ejecutar las celdas de forma secuencial.

---

## 🔁 Guía de reproducción

Para reproducir el análisis:

1. Descargar el notebook del repositorio.
2. Tener disponibles los datasets utilizados.
3. Abrir el notebook en Jupyter Notebook o Google Colab.
4. Ejecutar todas las celdas en el orden en que aparecen.
5. Revisar las visualizaciones, estadísticas y conclusiones generadas.

---

## 👩‍💻 Autora

Catalina Duque Díaz

Proyecto desarrollado como parte del Sprint 7 del programa de Data Analyst de TripleTen.

---

## 🔗 Repositorio público

**Link al repositorio:**

https://github.com/catalinaduquediaz-svg/telecom-analysis
