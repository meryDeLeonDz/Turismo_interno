# 🧳 Turismo interno

Proyecto de análisis y visualización de datos sobre el turismo interno entre provincias españolas.

🎓 Este proyecto se desarrolla como parte de la **PEC2 de la asignatura Visualización de Datos del Máster Universitario en Ciencia de Datos de la UOC**.

---

## 🎯 Objetivo

Analizar la distribución de las **viviendas vacacionales en Canarias**, explorando su presencia en las distintas islas y municipios
y su relación con variables como el número de plazas disponibles y la población residente.

El proyecto permite además experimentar con distintas técnicas y herramientas de visualización de datos,
comparando sus posibilidades para representar un mismo conjunto de datos.

---

## 📊 Fuentes de datos
SEGITTUR.Sociedad Mercantil Estatal para la Gestión de la Innovación y las Tecnologías Turísticas.

/TURISMO_INTERNO_PROV_CCAA_DL : Procedencia y destino de los turistas residentes que visitan una comunidad
autónoma o provincia distinta a la suya en el territorio español.

**Dataset:** *.*

📁 Formato original: CSV
🔗https://www.dataestur.es/API-SEGITTUR-2/TURISMO_INTERNO_PROV_CCAA_DL?desde%20%28a%C3%B1o%29=2024&desde%20%28mes%29=1&hasta%20%28a%C3%B1o%29=2025&hasta%20%28mes%29=12&CCAA%20origen=Todos&Provincia%20origen=Todos&CCAA%20destino=Todos&Provincia%20destino=Todos


/TURISMO_INTERNO_PROV_CCAA_DL : Procedencia y destino de los turistas residentes que visitan una comunidad
autónoma o provincia distinta a la suya en el territorio español.

---

## 🛠️ Preparación de los datos

Los datos originales han sido procesados para seleccionar y preparar las variables necesarias para las distintas visualizaciones.

Entre las variables utilizadas se encuentran:

- CCAA_Destino: Comunidad Autónoma de destino.
- CCAA_Origen: Comunidad Autónoma de origen.
- PERNOCTACIONES
- PROVINCIA_DESTINO
- PROVINCIA_ORIGEN
- TURISTAS

---

# 📈 Gráficos publicados

## 🟣 Flourish

Visualización de la distribución de las viviendas vacacionales según su número de plazas.

Se utilizó una visualización de tipo jerarquía, ya que la plantilla de barras apiladas de Flourish no permitía representar
la segmentación por número de plazas de la forma requerida para el análisis.

🔗 https://public.flourish.studio/visualisation/30747331/

## 🟢 Datawrapper
Visualización mediante Stacked Bar Chart (gráfico de barras apiladas).

El gráfico muestra la distribución de las viviendas vacacionales por isla, segmentadas según el número de plazas, permitiendo
comparar tanto el volumen total como la composición de las distintas categorías.

🔗  https://www.datawrapper.de/_/ccWt5/

🧰 Herramientas utilizadas

🐍 Python/google Colab — preparación y transformación de los datos inicial

📗 **Microsoft Excel / Power Query** — agregación de datos

📊 Tableau Public — creación de dashboards y visualizaciones interactivas

🌸 Flourish — exploración de alternativas de visualización

🟢 Datawrapper — creación del gráfico de barras apiladas

🐙 GitHub — documentación, organización y seguimiento del proyecto

