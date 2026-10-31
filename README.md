# 🧳 Turismo interno

Proyecto de análisis y visualización de datos sobre el turismo interno entre provincias españolas.

🎓 Este proyecto se desarrolla como parte de la **PEC2 de la asignatura Visualización de Datos del Máster Universitario en Ciencia de Datos de la UOC**.

---

## 🎯 Objetivo




---

## 📊 Fuentes de datos
SEGITTUR.Sociedad Mercantil Estatal para la Gestión de la Innovación y las Tecnologías Turísticas.

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


🔗 https://app.flourish.studio/visualisation/30758261

## 🟢 Observable (D3.js)

La visualización **Force-Directed Graph** se ha desarrollado en Observable con D3.js, tomando como referencia de diseño
e interacción el proyecto: **Monahans — “Final Project: Force Directed Graph of Ingredients”**  
https://old.observablehq.com/@monahans/final-project-force-directed-graph-of-ingredients

A partir de esta referencia se ha adaptado la lógica al análisis del turismo interno entre provincias españolas:

- nodos → provincias
- color → comunidad autónoma
- tamaño del nodo → turistas recibidos
- enlaces → flujos turísticos entre provincias
- grosor del enlace → número de turistas

🧰 Herramientas utilizadas

🐍 Python/google Colab — preparación y transformación de los datos inicial

📗 **Microsoft Excel / Power Query** — agregación de datos

📊 Tableau Public — creación de dashboards y visualizaciones interactivas

🌸 Flourish — exploración de alternativas de visualización

🟢 Datawrapper — creación del gráfico de barras apiladas

🐙 GitHub — documentación, organización y seguimiento del proyecto

