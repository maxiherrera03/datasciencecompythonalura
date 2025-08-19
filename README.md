# Análisis de Datos de Tiendas

Este notebook realiza un análisis exploratorio de los datos de ventas de cuatro tiendas diferentes para identificar métricas clave de rendimiento.

## Objetivos del Análisis

El objetivo de este análisis es comprender el rendimiento de cada tienda en términos de:

*   **Análisis de Facturación:** Calcular y comparar el ingreso total de cada tienda.
*   **Ventas por Categoría:** Identificar las categorías de productos más y menos vendidas en cada tienda.
*   **Calificación Promedio:** Determinar la satisfacción general del cliente para cada tienda.
*   **Productos más y menos vendidos:** Identificar los productos individuales con mayor y menor volumen de ventas.
*   **Costo de Envío Promedio:** Calcular el costo promedio asociado al envío de productos por tienda.

## Datos

Los datos utilizados en este análisis provienen de cuatro archivos CSV, uno para cada tienda, disponibles en el siguiente repositorio de GitHub:

*   `tienda_1.csv`
*   `tienda_2.csv`
*   `tienda_3.csv`
*   `tienda_4.csv`

## Análisis Realizado

Se realizaron los siguientes pasos de análisis en el notebook:

1.  **Importación de Datos:** Carga de los datos de cada tienda en dataframes de pandas.
2.  **Análisis de Facturación:** Cálculo del ingreso total para cada tienda sumando la columna 'Precio'.
3.  **Ventas por Categoría:** Conteo de la cantidad de productos vendidos por cada categoría en cada tienda.
4.  **Calificación Promedio de la Tienda:** Cálculo de la calificación promedio para cada tienda utilizando la columna 'Calificación'.
5.  **Productos más y menos vendidos:** Identificación de los productos con mayor y menor cantidad de ventas en cada tienda.
6.  **Envío Promedio por Tienda:** Cálculo del costo de envío promedio para cada tienda.

## Visualizaciones

Se generaron visualizaciones para ayudar a interpretar los resultados del análisis:

*   **Gráfico de Barras de Facturación:** Un gráfico de barras que compara el ingreso total de las cuatro tiendas.

## Conclusiones Preliminares

Según el análisis de facturación, la **Tienda 4** registró el menor ingreso total, lo que podría sugerir una menor rentabilidad en comparación con las otras tiendas, aunque se necesitaría un análisis de costos más completo para confirmarlo. Se pueden derivar más conclusiones al examinar las ventas por categoría, las calificaciones y los productos más y menos vendidos para cada tienda.

## Uso del Notebook

Para ejecutar este análisis, simplemente abre el notebook en un entorno como Google Colab y ejecuta las celdas en secuencia. Asegúrate de tener las librerías necesarias (pandas, matplotlib) instaladas.
