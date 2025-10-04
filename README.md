# Análisis Exploratorio de Datos - Ventas de Videojuegos

**Autor:** Samuel Angel Cardona

## Introducción
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre el mercado global de videojuegos, buscando patrones en preferencias de consumo, evolución histórica de la industria y estrategias comerciales exitosas. Se analizan características como ventas por región (NA_Sales, EU_Sales, JP_Sales, Other_Sales), plataformas de lanzamiento (Platform), géneros (Genre), distribuidores (Publisher), desarrolladores (Developer) y años de publicación (Year_of_Release), entre otros factores relevantes para comprender la dinámica del negocio de los videojuegos.

## Videojuegos (Dataset)
**Fuente:** Kaggle - https://www.kaggle.com/datasets/ibriiee/video-games-sales-dataset-2022-updated-extra-feat

El conjunto de datos contiene registros históricos de videojuegos con información sobre sus ventas en millones de unidades desglosadas por región (Norteamérica, Europa, Japón y otros mercados), la plataforma en la que fueron lanzados, el género al que pertenecen, el publisher y desarrollador responsables, y el año de publicación. Los datos abarcan desde los inicios de la industria hasta 2016, permitiendo analizar la evolución del mercado a lo largo de décadas.

## Descripción del Análisis Exploratorio de Datos

Se realizó una limpieza del conjunto de datos identificando y tratando valores nulos en columnas críticas como Year_of_Release, Publisher y Developer. Los registros sin año de lanzamiento fueron filtrados por imposibilitar el análisis de tendencias temporales. Se normalizaron los nombres de las columnas y se verificaron los tipos de datos numéricos para las variables de ventas. Durante este proceso se llevaron a cabo diversos análisis exploratorios que permitieron identificar los siguientes hallazgos:

## Hallazgos Principales
- Poder de las Franquicias: Las marcas consolidadas como Super Mario, Call of Duty y Pokémon dominan las ventas a largo plazo, demostrando la importancia de la lealtad del consumidor.
- Ecosistema de Nintendo: Nintendo lidera como publisher y fabricante de hardware, creando un ecosistema cerrado y muy rentable con consolas como la Wii y la DS.
- Preferencias Regionales: Se observan claras diferencias culturales: los juegos de Rol (RPG) son dominantes en Japón, mientras que en Norteamérica y Europa prefieren Acción, Deportes y Disparos (Shooter).
- La "Era Dorada" (2008-2009): El pico de ventas coincide con el auge de la PS2, Wii y DS.
- Estrategias de Desarrollador: Se evidencia cómo Rockstar North basa su éxito en una sola mega-franquicia (Grand Theft Auto), mientras que Treyarch logra ventas similares a través de contribuciones constantes a una franquicia anual (Call of Duty). 
         (hallazgos completos en el archivo)                                         
## Librerías utilizadas

Para llevar a cabo este análisis exploratorio de datos (EDA), fue necesario utilizar las siguientes librerías:

- pandas
- numpy
- matplotlib.pyplot


