# Optimización de Activos Retail: Análisis Geoespacial y Financiero

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Finalizado-success)

## 1. Propósito del Análisis
El objetivo principal del desafío es asistir a la gerencia en la toma de decisiones de inversión. Se busca identificar cuál de las 4 tiendas disponibles presenta el desempeño integral más bajo y, por ende, debería ser vendida para capitalizar una nueva inversión.

La evaluación se realizó bajo un enfoque multidimensional, analizando:
* **Dimensión Financiera:** Facturación total (Ingresos brutos).
* **Dimensión Comercial:** Mezcla de productos (Product Mix) y análisis de Best/Worst Sellers.
* **Dimensión de Calidad:** Satisfacción del cliente mediante calificaciones promedio.
* **Dimensión Logística:** Eficiencia en costos de envío.
* **Dimensión Geoespacial:** Distribución territorial de las ventas (Urbanismo y alcance de mercado).

## 2. Estructura del Repositorio

El proyecto está organizado para facilitar la reproducibilidad del análisis:

📁 retail-analysis-latam/
│
├── 📓 AluraStoreLatam.ipynb   # Notebook principal (ETL + Visualización + Storytelling)
├── 📂 assets/                 # Gráficos exportados y recursos visuales
├── 📄 image_452301.jpg        # Visualización geoespacial de densidad de ventas
└── 📄 README.md               # Documentación del proyecto

## 3. Gráficos e Insights Obtenidos

Se generaron diversas visualizaciones para sustentar la recomendación final. A continuación, se destaca el análisis territorial.

### Distribución Geoespacial de Ventas
Se mapearon las transacciones utilizando coordenadas de latitud y longitud para entender la huella operativa de cada tienda.

![Mapa de Calor de Ventas](image_452301.jpg)
*(Distribución de densidad de ventas en el territorio colombiano)*

**Insight Geoespacial:**
La visualización revela una fuerte polarización de la actividad comercial. Se observa una densa concentración de ventas en los principales clústeres urbanos (Bogotá, Medellín, Cali), lo que favorece a las tiendas posicionadas en estas zonas mediante una logística eficiente.
Por el contrario, la tienda de menor rendimiento muestra una dispersión ineficiente hacia zonas periféricas (como la región amazónica), lo que correlaciona con sus altos costos de envío y menores calificaciones de satisfacción debido a las fricciones logísticas.

### Conclusión del Análisis
Basado en la integración de las variables financieras y espaciales, se recomendó la venta de la tienda con menor facturación y mayor complejidad logística, permitiendo a la gerencia optimizar su cartera de inversión.

## 4. Instrucciones para Ejecutar el Notebook

Este proyecto fue desarrollado para ser ejecutado en **Google Colab**.

1.  Abre el archivo `AluraStoreLatam.ipynb` listado en este repositorio.
2.  Haz clic en el botón "Open in Colab" (o descarga el archivo y súbelo a tu Drive).
3.  El entorno requiere las siguientes librerías (preinstaladas en Colab):
    * `pandas` (Manipulación de datos)
    * `matplotlib` y `seaborn` (Visualización estática)
    * `folium` (Mapas interactivos)
4.  Ejecuta las celdas en orden secuencial ("Run All") para reproducir el análisis y los mapas interactivos.

**Autora:** Izunza Rocío 
*Urbanista & Data Scientist*


El entorno ya incluye las librerías necesarias (pandas, matplotlib, seaborn, folium), por lo que puedes ejecutar todas las celdas secuencialmente.
Autora: Rocío Izunza Urbanista & Data Scientist
