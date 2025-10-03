# Analisis de Video Juegos - Data Analytics

***Presentación complementaria:*** [https://docs.google.com/presentation/d/1hrJARXbqQ7l0aFm9SpMTlGeAVqljTVA15dsK4f1gUtU/edit?usp=sharing](https://docs.google.com/presentation/d/11eyALUV3vJ1mSAG1XcjFWwhp9KflZ1gKbq1r2YLahL0/edit?usp=drive_link)

Este proyecto realiza un análisis estadístico de datos de ventas de videojuegos utilizando el lenguaje de programación R. Incluye visualizaciones, pruebas estadísticas y análisis de tendencias para explorar patrones en diferentes regiones, géneros y plataformas.


El archivo .ipynb contiene un análisis estadístico de datos de videojuegos utilizando R. A continuación, se describen los diferentes apartados:

# Introducción y Preparación de Datos

Se descargan las librerías necesarias (readr, kaggler) y se autentica con Kaggle para descargar el dataset de ventas de videojuegos.
Se descomprime el archivo y se carga el dataset en una variable llamada videogames.

# Exploración del Dataset

Se describe el contenido del dataset, incluyendo los campos como Rank, Name, Platform, Year, Genre, Publisher, y las ventas por región (NA_Sales, EU_Sales, JP_Sales, etc.).

# Pregunta 1: Relación entre Publisher y Éxito Regional

Se analiza si ciertos editores tienen más éxito en regiones específicas (Norteamérica, Europa, Japón).
Se generan tablas y gráficos para mostrar las ventas promedio por región y se realizan agrupaciones por editor.
Se crean gráficos de barras para comparar las ventas promedio por región.

# Pregunta 2: Evolución Temporal de Ventas por Región y Plataforma

Se analizan las ventas de videojuegos a lo largo del tiempo en diferentes regiones (Europa, América, Japón).
Se generan gráficos de líneas para mostrar la evolución temporal de las ventas por editor y región.

# Pregunta 3: Análisis Temporal de Lanzamientos Exitosos

Se analiza si hay periodos específicos en los que se lanzaron más videojuegos exitosos.
Se calcula la correlación entre el año y las ventas globales, y se visualiza con un diagrama de dispersión.
Se analiza el éxito de los años en función del ranking promedio de los videojuegos lanzados.

# Pregunta 4: Análisis de Palabras Comunes en Títulos por Género

Se identifican las palabras más comunes en los títulos de videojuegos, excluyendo stopwords y números.
Se generan nubes de palabras para cada género (e.g., Sports, Racing, Action, etc.).

# Pregunta 5: Análisis de Lanzamientos por Plataforma y Año

Se cuenta el número de videojuegos lanzados por plataforma y año.
Se generan gráficos de líneas para mostrar las tendencias de lanzamientos en diferentes plataformas a lo largo del tiempo.

# Conclusiones

Se destacan las tendencias observadas en las ventas, lanzamientos y popularidad de videojuegos según región, plataforma y género.
Cada apartado incluye visualizaciones y análisis detallados para responder preguntas específicas relacionadas con los datos de videojuegos.
