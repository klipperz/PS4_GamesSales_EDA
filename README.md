# Análisis Exploratorio de Datos (EDA) de Ventas de Videojuegos
## Introducción
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un conjunto de datos de ventas de videojuegos, utilizando el archivo Video_Games.csv. El objetivo es descubrir patrones, tendencias y relaciones clave en la industria de los videojuegos, desde las franquicias más exitosas hasta las preferencias de mercado por región.

El análisis está estructurado en un notebook de Jupyter (videojuegos EDA.ipynb) que guía al usuario a través de la limpieza de datos, la visualización y la interpretación de los hallazgos.

### Objetivos del Análisis
- Identificar los juegos y franquicias con mayores ventas globales, consolidando datos de múltiples plataformas.

- Analizar las preferencias de género por mercado, enfocándose en las regiones de Norteamérica, Europa y Japón.

- Determinar qué plataformas (consolas) y distribuidoras (publishers) dominan el mercado en términos de ventas.

- Observar la evolución de las ventas globales a lo largo de los años para identificar tendencias históricas.

- Comparar las estrategias de ventas de desarrolladores específicos, como Rockstar North y Treyarch.

## Contenido del Análisis
- El notebook está organizado en las siguientes secciones principales:

1. Carga y Limpieza de Datos:

- Importación de las librerías necesarias (pandas, numpy, matplotlib).

- Lectura del archivo Video_Games.csv.

- Limpieza de nombres de columnas.

- Conversión de tipos de datos para las columnas de ventas y puntuaciones.

- Manejo de valores nulos en columnas críticas.

2. Análisis Descriptivo General:

- Estadísticas básicas de las ventas globales y regionales.

- Distribución de la cantidad de juegos por género y plataforma.

3. Visualizaciones y Hallazgos Clave:

- Top 10 de Juegos por Ventas Consolidadas: Gráfico de barras que muestra los juegos más vendidos sumando todas sus versiones.

- Top 10 de Franquicias por Ventas Globales: Análisis que agrupa juegos en franquicias (ej. "Super Mario", "Call of Duty") para medir el poder de la marca a largo plazo.

- Plataformas con Mayores Ventas: Gráfico de barras que identifica las consolas que han generado más ventas de software.

- Distribución de Géneros por Región: Gráficos de pastel que comparan las preferencias de género en Norteamérica, Europa y Japón.

- Cuota de Mercado de Publishers: Gráfico de pastel que muestra la participación de las principales distribuidoras en las ventas globales.

- Evolución de Ventas Anuales: Gráfico de líneas que ilustra el comportamiento del mercado desde los inicios hasta 2016.

- Comparativa de Desarrolladores: Un análisis específico que compara el total de ventas y los juegos más vendidos de Rockstar North frente a Treyarch.

## Hallazgos Principales
- Poder de las Franquicias: Las marcas consolidadas como Super Mario, Call of Duty y Pokémon dominan las ventas a largo plazo, demostrando la importancia de la lealtad del consumidor.
- Ecosistema de Nintendo: Nintendo lidera como publisher y fabricante de hardware, creando un ecosistema cerrado y muy rentable con consolas como la Wii y la DS.
- Preferencias Regionales: Se observan claras diferencias culturales: los juegos de Rol (RPG) son dominantes en Japón, mientras que en Norteamérica y Europa prefieren Acción, Deportes y Disparos (Shooter).
- La "Era Dorada" (2008-2009): El pico de ventas coincide con el auge de la PS2, Wii y DS.
- Estrategias de Desarrollador: Se evidencia cómo Rockstar North basa su éxito en una sola mega-franquicia (Grand Theft Auto), mientras que Treyarch logra ventas similares a través de contribuciones constantes a una franquicia anual (Call of Duty).
