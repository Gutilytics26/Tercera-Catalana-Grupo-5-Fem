Gutilytics Intelligence Scouting
Dashboard de Análisis y Scouting — Tercera Federación Femenina · Grupo 5 (Catalunya)

¿Qué resuelve este proyecto?
El scouting deportivo tradicional depende de observación manual y criterio subjetivo. Este dashboard transforma datos reales de rendimiento de jugadoras de la Tercera Federación Femenina de Catalunya (Grupo 5) 
en inteligencia deportiva accionable permitiendo comparar jugadoras, identificar talento eficiente y analizar el comportamiento de equipos a partir de métricas objetivas.

Origen de los datos
Los datos fueron obtenidos mediante Web Scraping desarrollado en Python, extrayendo estadísticas individuales y colectivas desde fuentes públicas de la competición. El pipeline completo incluyó:

- Extracción automatizada con BeautifulSoup / Selenium
- Limpieza y normalización con Pandas (duplicación, conversión de tipos, estandarización de nombres)
- Construcción de métricas derivadas: goles/90 min, ratio de titularidad, amarillas/90, goles recibidos/90


Funcionalidades del Dashboard
Análisis de Liga

- KPIs generales — jugadoras activas, goles totales, promedios de rendimiento
- Ranking de goleadoras eficientes (top 10 por goles/90 min)
- Volumen de goles por equipo con visualización interactiva
- Distribución por experiencia de las jugadoras

Análisis por Equipo

- Navegación visual por los 12 equipos del grupo con logos
- Plantilla completa con métricas individuales por jugadora
- Filtro dinámico por minutos mínimos jugados

Rendimiento de Porteras

- Análisis específico del puesto con métrica de goles recibidos/90
- Comparativa de ratio de titularidad entre porteras del grupo

Stack Tecnológico: Python, Pandas, Plotly Express, Streamlit,  BeautifulSoup / Selenium.

Métricas clave implementadas

- Goles/90 min — eficiencia goleadora normalizada por tiempo jugado
- Ratio de titularidad — regularidad de la jugadora en el equipo
- Amarillas/90 min — índice de conflictividad
- Goles recibidos/90 — rendimiento defensivo de porteras
- Proxy de experiencia — categorización por perfil de trayectoria


