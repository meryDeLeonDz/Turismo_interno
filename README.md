# 🧳 Turismo interno

Proyecto de análisis y visualización de datos sobre las **viviendas vacacionales registradas en Canarias**.

🎓 Este proyecto se desarrolla como parte de la **PEC2 de la asignatura Visualización de Datos del Máster Universitario en Ciencia de Datos de la UOC**.

---

## 🎯 Objetivo

Analizar la distribución de las **viviendas vacacionales en Canarias**, explorando su presencia en las distintas islas y municipios
y su relación con variables como el número de plazas disponibles y la población residente.

El proyecto permite además experimentar con distintas técnicas y herramientas de visualización de datos,
comparando sus posibilidades para representar un mismo conjunto de datos.

---

## 📊 Fuentes de datos

### 👥 Datos de población

**Fuente:** Instituto Canario de Estadística (ISTAC)

🔗 https://www3.gobiernodecanarias.org/istac/statistical-visualizer/visualizer/data.html?resourceId=6daf4220-c08f-431c-8383-a0a7daa87da7&indicatorSystem=C00067A&resourceType=indicatorInstance#visualization/table

---

### 🏡 Viviendas vacacionales

**Fuente:** Portal de Datos Abiertos del Gobierno de Canarias

**Dataset:** *Establecimientos extrahoteleros de tipología vivienda vacacional inscritos en el Registro General Turístico de Canarias.*

📁 Formato original: CSV

🔗 https://datos.canarias.es/catalogos/general/dataset/9f4355a2-d086-4384-ba72-d8c99aa2d544/resource/8ff8cc43-c00b-4513-8f42-a5b961c579e1/download/establecimientos-extrahoteleros-de-tipologia-vivienda-vacacional-inscritos-en-el-registro-genera.csv

El conjunto de datos contiene el listado de establecimientos extrahoteleros de tipología **vivienda vacacional** inscritos en el Registro General Turístico de Canarias.

> ℹ️ **Nota:** el código `_U` indica que se trata de un dato desconocido o que no consta.

---

## 🛠️ Preparación de los datos

Los datos originales han sido procesados para seleccionar y preparar las variables necesarias para las distintas visualizaciones.

Entre las variables utilizadas se encuentran:

- 🏝️ Isla
- 🏘️ Municipio
- 🛏️ Número de plazas
- 🏠 Características de los establecimientos
- 👥 Población residente

---

# 📈 Gráficos publicados

## 🔵 Tableau

Dashboard interactivo para analizar la distribución de las viviendas vacacionales en Canarias.

Permite explorar los datos territorialmente y consultar la información mediante diferentes elementos interactivos.

🔗 https://public.tableau.com/app/profile/mar.a.jos.de.le.n.d.az/viz/ViviendasvacacionalesCanarias/Dashboard1?publish=yes

---

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

