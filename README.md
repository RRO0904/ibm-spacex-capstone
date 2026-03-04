# Winning Space Race with Data Science (SpaceX Falcon 9)

**Predictive Analytics & Interactive Dashboards para la viabilidad espacial**

## El Problema de Negocio
Este proyecto se centra en el análisis de los costos y la viabilidad operativa de la reutilización de los cohetes Falcon 9. Dado que SpaceX ha reducido drásticamente los costos de lanzamiento (de $165M a $62M) al lograr recuperar la primera etapa del cohete, **el objetivo de este proyecto es predecir si esta etapa aterrizará con éxito.** El modelo y los cuadros de mando desarrollados sirven como herramienta visual y algorítmica para la toma de decisiones estratégicas de una empresa aeroespacial competidora (la ficticia *Space Y*).

## Stack Tecnológico
* **Lenguajes:** Python, SQL
* **Extracción de Datos:** API REST, Web Scraping (BeautifulSoup)
* **Análisis y Manipulación:** Pandas, NumPy
* **Visualización:** Plotly Dash (Dashboards interactivos), Folium (Mapas geoespaciales), Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Logistic Regression, SVM, Decision Trees, KNN)

## Fases del Proyecto
1. **Recopilación de Datos:** Extracción de registros históricos de lanzamientos consumiendo la API pública de SpaceX y aplicando Web Scraping a tablas de Wikipedia.
2. **Data Wrangling & EDA:** Limpieza exhaustiva de datos y Análisis Exploratorio utilizando consultas **SQL** puras y Pandas.
3. **Analítica Visual:** Desarrollo de mapas interactivos con Folium para analizar el éxito según la ubicación del despegue, y creación de un **Dashboard interactivo con Plotly Dash** para filtrar cargas útiles y tasas de éxito en tiempo real.
4. **Modelado Predictivo:** Entrenamiento y evaluación de múltiples modelos de clasificación para predecir el aterrizaje. Se utilizó `GridSearchCV` para la optimización de hiperparámetros.

## Resultados Clave
Tras evaluar distintos algoritmos de Machine Learning, el modelo de **Árbol de Decisión (Decision Tree)** demostró ser el más efectivo para este problema de negocio, alcanzando una **precisión predictiva del 88%**.

---
*Este proyecto es el Trabajo Final (Capstone) del Certificado Profesional de Data Science de IBM.*
