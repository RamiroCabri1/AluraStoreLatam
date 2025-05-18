###ATENCION### El trabajo final se encuentra en Copia_de_alurastorelatam.ipynb


# Análisis de Datos de Ventas de Tiendas

Este proyecto realiza un análisis exploratorio de datos sobre las ventas de cuatro tiendas diferentes. El objetivo principal es identificar patrones, tendencias y métricas clave que puedan informar decisiones de negocio.

## 1. Análisis de Facturación

Esta sección se enfoca en comprender el desempeño de ventas de cada tienda individualmente y en conjunto.

- **Primer Contacto con los Datos:** Se realiza una inspección inicial de la estructura y el contenido de los DataFrames utilizando `.info()` y `.describe()`.
- **Búsqueda de Datos Nulos o Incompletos:** Se verifica la presencia de valores faltantes para asegurar la calidad de los datos.
- **Análisis de Facturación Bruta:** Se calcula la suma total de los precios de los productos vendidos por cada tienda para obtener una métrica de facturación bruta (sin considerar costos de envío inicialmente). Se visualiza esta información en un gráfico de dispersión.
- **Exploración de Productos Individuales:** Se identifican los productos únicos vendidos y se cuenta la cantidad de ventas por cada producto en la tienda con mayor facturación.

## 2. Ventas por Categoría

Aquí se analiza el rendimiento de las ventas a nivel de categorías de productos en cada tienda y globalmente.

- **Identificación de Categorías:** Se listan las categorías únicas presentes en los datos.
- **Análisis de Ventas por Categoría (por Tienda):** Se implementa una función para graficar la cantidad de ventas por categoría para cada tienda, permitiendo comparar la distribución de ventas entre ellas.
- **Análisis de Ventas por Categoría (Global):** Se concatena la información de todas las tiendas en un solo DataFrame para analizar las ventas por categoría a nivel global de la empresa. Se visualiza la cantidad de ventas y el monto total facturado por categoría en gráficos de barras y de torta respectivamente.

## 3. Calificación Promedio de la Tienda

Esta sección evalúa la satisfacción del cliente basándose en las calificaciones promedio de cada tienda.

- **Cálculo de Calificación Promedio:** Se calcula la calificación promedio para cada tienda y el promedio global.
- **Visualización de Calificaciones:** Se presenta un gráfico de barras comparando las calificaciones promedio de cada tienda y el promedio global.

## 4. Productos Más y Menos Vendidos

Se identifican los productos con mayor y menor volumen de ventas para entender qué productos son populares y cuáles podrían necesitar atención.

- **Productos Más Vendidos:** Se implementa una función para identificar y graficar el producto más vendido en cada tienda y en el conjunto total de datos.
- **Productos Menos Vendidos:** Se implementa una función para identificar los `n` productos menos vendidos en cada tienda y en el conjunto total de datos, y se visualiza esta información.

## 5. Envío Promedio por Tienda

Se analiza el costo asociado a los envíos en cada tienda y su impacto en la rentabilidad.

- **Costos de Envío Promedio:** Se calcula y se muestra el costo promedio de envío por tienda y el costo promedio global. Se visualiza en un gráfico de barras.
- **Análisis de Rentabilidad:** Se crea una nueva columna en cada DataFrame que representa la "rentabilidad" simple (Precio del Producto - Costo de Envío). Se calcula la suma de esta diferencia por tienda y se visualiza en un gráfico de barras para tener una idea inicial de la rentabilidad por sucursal.
- **Visualización de Lugares de Envío:** Se utiliza la librería `folium` para visualizar en un mapa las ubicaciones de los envíos de una tienda específica, proporcionando una perspectiva geográfica.

## Cómo Ejecutar el Notebook

Para ejecutar este análisis en un entorno como Google Colaboratory o Jupyter Notebooks, sigue los siguientes pasos:

1.  **Abrir el Notebook:** Abre el archivo `.ipynb` en Google Colaboratory o Jupyter Notebooks.
2.  **Ejecutar Celdas:** Ejecuta cada celda de código secuencialmente. Puedes hacerlo haciendo clic en el botón de reproducción en cada celda o utilizando la opción "Run all" en el menú.
3.  **Visualizar Resultados:** Los gráficos y las salidas de texto se mostrarán directamente debajo de cada celda ejecutada.

Asegúrate de tener conexión a internet para descargar los datos desde las URLs proporcionadas.
