# urban-mobility-economic-analysis
# Mobility Economy Project

## Descripción del proyecto

Este proyecto analiza la relación entre la **movilidad urbana** y la **productividad económica** en distintas ciudades del mundo durante **2024**. El objetivo es identificar patrones entre la congestión vehicular, los tiempos de desplazamiento y el **PIB per cápita**, con el fin de comprender cómo la movilidad puede influir en el desempeño económico y apoyar la toma de decisiones en planificación urbana e infraestructura.

Las principales variables analizadas fueron:

* **jams_delay:** retraso promedio causado por congestión.
* **traffic_index_live:** índice de tráfico en tiempo real.
* **travel_time_live_per_10kms_mins:** tiempo promedio de viaje por cada 10 km.
* **city_gdp_per_capita:** PIB per cápita de cada ciudad.

---

## ¿Qué contiene este repositorio?

Este repositorio incluye los recursos necesarios para reproducir el análisis:

* **Notebook principal (`mobility_economy_project_student.ipynb`)**

  * Limpieza y preparación de datos.
  * Integración de las bases de movilidad y economía.
  * Análisis exploratorio de datos (EDA).
  * Visualizaciones y conclusiones.

* **README.md**

  * Descripción del proyecto.
  * Objetivos.
  * Metodología.
  * Instrucciones de uso.

* **Gráficos**

  * Histogramas.
  * Boxplots.
  * Gráficos comparativos.
  * Visualizaciones utilizadas para identificar tendencias y valores atípicos.

---

## Metodología

El análisis se desarrolló siguiendo las siguientes etapas:

1. Limpieza y estandarización de los datasets.
2. Validación de formatos y nombres de columnas.
3. Selección de variables relevantes.
4. Integración de los datos mediante una **unión INNER** por ciudad y año.
5. Análisis exploratorio utilizando estadísticas descriptivas y visualizaciones.
6. Interpretación de resultados y elaboración de recomendaciones.

---

## Principales hallazgos

Los resultados muestran que las ciudades con mayor actividad económica tienden a presentar niveles elevados de congestión vehicular; sin embargo, la relación no es completamente lineal.

Entre los hallazgos más relevantes se identificó que:

* Grandes centros urbanos presentan mayores retrasos por tráfico.
* Existen ciudades con alto PIB per cápita y niveles moderados de congestión gracias a sistemas de transporte más eficientes.
* Bogotá y Lima aparecen como ciudades que podrían beneficiarse de inversiones adicionales en infraestructura de movilidad.
* Los valores atípicos observados justifican análisis estadísticos complementarios para validar las relaciones encontradas.

---

## Herramientas utilizadas

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**

---

## Conclusiones

Este análisis evidencia que la congestión vehicular puede estar asociada con diferencias en el desempeño económico urbano, aunque dicha relación depende de múltiples factores adicionales, como la infraestructura de transporte, la planificación urbana y el crecimiento demográfico.

Los resultados obtenidos permiten identificar ciudades donde futuras inversiones en movilidad sostenible podrían generar impactos positivos sobre la productividad y la calidad de vida.

---

## Autor

Proyecto desarrollado por **Cesar Palacio** como parte de su formación en **Data Analytics**, posteriormente reorganizado y documentado para su portafolio profesional en GitHub.
