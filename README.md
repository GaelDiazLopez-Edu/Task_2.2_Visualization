# Task_2.2_Visualization

Proyecto de Visualización: Evolución y Tendencias
Este proyecto consiste en un ejercicio práctico de análisis de datos utilizando Python. El objetivo principal es aprender a representar datos que cambian con el tiempo (series temporales) y saber interpretar conceptos clave como tendencias, estacionalidad y ruido.

## Herramientas utilizadas
- Python

- Pandas: Para la carga y manipulación de los datasets (CSV).

- Matplotlib & Seaborn: Para la creación de los gráficos y personalización visual.

## Contenido del Ejercicio
El notebook se divide en tres secciones principales:

1. Tendencias Globales (Life Expectancy / GDP)

En esta sección analizamos cómo evolucionan datos macroeconómicos a largo plazo.

Filtramos datos por países (España, Francia y China).

Aprendimos que al comparar países con escalas muy diferentes (como China frente a los europeos), es necesario usar escalas logarítmicas o gráficos separados para no perder el detalle.

2. Éxitos de Spotify

Trabajamos con datos de reproducciones de canciones para practicar:

Multiplots: Dibujar cada canción en un cuadro separado para ver su comportamiento individual.

Gráficos combinados: Poner todas las líneas juntas para ver quién lidera el mercado en cada momento.

3. Estacionalidad (Pasajeros de Avión)

Estudiamos patrones que se repiten cíclicamente.

Analizamos el dataset histórico de aerolíneas para identificar picos de viajes en meses de vacaciones.

Diferenciamos entre la tendencia (el sector crece cada año) y la estacionalidad (cada verano hay un pico de ventas).

## Conclusiones
A través de estas visualizaciones, he aprendido a:

Identificar si una variable sube o baja de forma constante (Trend).

Detectar patrones repetitivos (Seasonality).

Elegir el tipo de gráfico adecuado según si quiero comparar magnitudes o ver detalles individuales.