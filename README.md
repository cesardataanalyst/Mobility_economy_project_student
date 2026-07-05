# mobility_economy_project_student
El objetivo principal de este análisis fue estudiar la relación entre la movilidad urbana y la productividad económica en distintas ciudades del mundo durante 2024. Para ello, se analizaron variables relacionadas con congestión vehicular, tiempos promedio de viaje y PIB per cápita, buscando identificar patrones que permitan comprender cómo el tráfico puede impactar la actividad económica y la calidad de vida urbana.

Las variables clave utilizadas fueron jams_delay, traffic_index_live, travel_time_live_per_10kms_mins y city_gdp_per_capita. Estas métricas permiten evaluar tanto el nivel de congestión urbana como el desempeño económico de cada ciudad, siendo útiles para la toma de decisiones en planeación urbana, infraestructura y movilidad sostenible.
Cobertura de datos:

Especifica los años analizados, número de ciudades y países incluidos. El análisis se desarrolló utilizando información correspondiente al año 2024, integrando datasets de movilidad y economía mediante una unión INNER por ciudad y año. La base final incluyó múltiples ciudades y países, permitiendo comparar comportamientos entre distintas regiones y niveles de desarrollo económico.
Metodología (alto nivel):

Describe los procesos principales: limpieza de datos (formatos, estandarización de columnas).
Explica la agregación por ciudad–año y el uso de una unión INNER para integrar tráfico y economía.
Menciona las validaciones visuales empleadas (distribuciones, outliers, tendencias generales).
Primero se realizó un proceso de limpieza y estandarización de datos, incluyendo validación de formatos, selección de variables relevantes y homogenización de nombres de columnas. Posteriormente, se agregaron métricas por ciudad y año para obtener indicadores comparables entre localidades. Después, se aplicó una unión INNER para conservar únicamente las ciudades presentes en ambos datasets (movilidad y economía). Finalmente, se utilizaron gráficos exploratorios como boxplots, histogramas y gráficos de barras para identificar distribuciones, valores atípicos y posibles tendencias entre congestión vehicular y productividad económica.

Hallazgos iniciales:

Resume los patrones más importantes entre índices de tráfico y PIB per cápita.
Destaca anomalías u outliers que podrían requerir revisión adicional o un análisis más profundo.
Los resultados muestran que algunas ciudades con mayor PIB per cápita también presentan altos niveles de congestión vehicular, especialmente grandes centros urbanos con elevada actividad económica y densidad poblacional. Sin embargo, la relación observada no es completamente lineal, ya que existen ciudades con economías fuertes pero menores niveles de tráfico gracias a mejores sistemas de transporte e infraestructura urbana. Entre los valores atípicos destacó Ciudad de México, que presentó uno de los mayores niveles de congestión del conjunto de datos. También se identificaron diferencias importantes entre ciudades latinoamericanas y ciudades europeas o asiáticas, lo que sugiere la influencia de factores adicionales como planificación urbana, transporte público y crecimiento demográfico.

Recomendaciones
Aterriza los hallazgos en acciones: ciudades prioritarias, necesidad de validar fuentes, requerimiento de análisis adicionales, o propuestas de inversión.

¿Qué ciudad : Bogotá, Lima o Buenos Aires o alguna otra en particular, muestra la mayor correlación significativa entre altos niveles de congestión vehicular y bajos indicadores de productividad económica, sugiriendo ser una ciudad prioritaria para inversión en infraestructura de transporte?
Se recomienda priorizar inversiones en infraestructura de transporte y movilidad inteligente en ciudades con altos niveles de congestión y menor desempeño económico relativo. También es importante complementar este análisis con variables adicionales como calidad del transporte público, emisiones contaminantes y crecimiento poblacional. Con base en los patrones observados, Bogotá y Lima podrían considerarse ciudades prioritarias para futuras inversiones en infraestructura de movilidad, debido a sus altos niveles de congestión y posibles impactos negativos sobre la productividad urbana. No obstante, se recomienda realizar análisis estadísticos más profundos para confirmar la correlación y validar la consistencia de las fuentes de datos.
