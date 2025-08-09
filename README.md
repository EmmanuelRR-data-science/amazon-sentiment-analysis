# 📊 Análisis de Reseñas de Productos en Amazon con Python y Tableau

Este proyecto combina **procesamiento de lenguaje natural (NLP)** y **visualización de datos** para analizar miles de reseñas de productos en Amazon, identificando patrones de sentimiento y palabras más frecuentes, y presentando los resultados en un **dashboard interactivo**.

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a9/Amazon_logo.svg/905px-Amazon_logo.svg.png" alt="Logo de Amazon" width="800">
</p>

---

## 📌 Contexto
Las reseñas de usuarios contienen información valiosa para empresas y consumidores. Sin embargo, su volumen y complejidad hacen que analizarlas manualmente sea poco práctico.  
Este proyecto utiliza un dataset de reseñas de Amazon, procesado con Python, para extraer métricas clave y visualizarlas de manera clara en Tableau.

---

## 🎯 Objetivo del Análisis
- Determinar la **distribución de sentimientos** (positivo, negativo, neutral) en las reseñas.
- Identificar las **palabras más frecuentes** en cada categoría de sentimiento.
- Presentar los resultados en un **dashboard interactivo** para facilitar la exploración.

---

## 🔄 Flujo de Trabajo

1. **Preprocesamiento en Python**
   - Limpieza de datos (eliminación de valores nulos).
   - Análisis de sentimientos con técnicas de NLP.
   - Generación de nubes de palabras.
   - Creación de archivos CSV con las palabras más frecuentes por sentimiento.

2. **Visualización en Tableau**
   - Gráficas de distribución de sentimientos.
   - Promedio de calificaciones por sentimiento.
   - Tablas y gráficos de palabras más frecuentes.
   - Integración de todo en un dashboard.

3. **Publicación**
   - Dashboard publicado en **Tableau Public** para acceso libre.

---

## 📊 Principales Resultados
- El **89%** de las reseñas analizadas fueron positivas.
- Palabras más comunes en reseñas positivas: *great*, *love*, *easy*.
- Palabras más comunes en reseñas negativas: *bad*, *waste*, *poor*.
- El puntaje promedio de las reseñas positivas es de **4.6/5**, mientras que en las negativas es de **1.8/5**.

---

## 🌐 Dashboard Interactivo
🔗 **🔗 **[Ver Dashboard en Tableau Public](https://public.tableau.com/views/Amazon_SA/Dashboard1?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**
**

---

## 🛠️ Tecnologías Utilizadas
- **Python** (pandas, matplotlib, seaborn, wordcloud, nltk)
- **Tableau Desktop**
- **Tableau Public**

---

## 📂 Cómo Reproducir el Proyecto
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/EmmanuelRR-data-science/amazon-sentiment-analysis.git

2. Instalar dependencias en Python
   ```bash
   pip install -r requirements.txt
3. Ejecutar el Jupyter Notebook principal para generar los CSV de análisis.

4. Abrir Tableau y conectar los CSV generados en el notebook.

5. Recrear el dashboard o explorar el publicado en Tableau Public.

---

## 👤 Autor
📧 [emmanuel.mec@gmail.com]
🔗 [linkedin.com/in/emmanuel-data-science]
