# Caso Harvard: Hollywood Rules  

Este repositorio contiene el desarrollo y la resolución del caso de Harvard **“Hollywood Rules”**, realizado en el marco del curso **Analítica de los Negocios**.  

Datos y archivos de réplica para el análisis del caso por:  

**David Santiago Aguirre Polanco**  
**María Juanita Rojas Chacón**  
**Andrés Felipe Romero Rodríguez**  

--------------------------------------------------  

# **Resumen**  

El caso *Hollywood Rules* analiza la industria cinematográfica desde una perspectiva financiera y analítica, con el objetivo de identificar los factores que influyen en el éxito comercial de las películas. En particular, se estudia cómo distintos elementos relacionados con la producción, el lanzamiento y la recepción del público impactan los ingresos en taquilla.  

A partir de un conjunto de datos que incluye las 150 películas más taquilleras de 2006, se realiza un análisis cuantitativo para evaluar variables clave y apoyar la toma de decisiones de inversión en portafolios de películas (slates). Este análisis busca determinar qué características pueden aumentar la probabilidad de éxito de una película y, por ende, mejorar el rendimiento esperado para inversionistas.  

El análisis incluye el estudio de variables como:  

- Opening Gross (Ingresos del primer fin de semana)  
- Total U.S. Gross  
- Total Non-U.S. Gross  
- Budget  
- Opening Theatres  
- Genre  
- MPAA Rating  
- Sequel y Known Story  
- Critics’ Opinion  
- Oscars (Nominaciones y premios)  

A través de estadísticas descriptivas, pruebas de hipótesis y modelos de regresión, se busca comprender los determinantes del desempeño en taquilla y evaluar la relación entre el rendimiento inicial y el éxito total de una película.  

--------------------------------------------------  

# **Estructura del repositorio**  

El repositorio está organizado en las siguientes carpetas:  

--------------------------------------------------  

# **Carpeta Document**  

Esta carpeta contiene los documentos finales relacionados con el análisis del caso.  

**Archivos incluidos:**  

- **Caso Harvard Hollywood Rules.pdf**  

Documento principal donde se presenta el desarrollo completo del análisis del caso. Este documento incluye la exploración de los datos, el análisis estadístico realizado, la construcción de modelos de regresión, la interpretación de los resultados y las conclusiones sobre los factores que influyen en el éxito de las películas.  

- **Resumen Ejecutivo. Caso Harvard Hollywood Rules.pdf**  

Documento que presenta una síntesis de los hallazgos más relevantes del análisis. En este resumen se destacan las conclusiones clave relacionadas con los determinantes del éxito en taquilla y las implicaciones para la toma de decisiones de inversión en la industria cinematográfica.  

--------------------------------------------------  

# **Carpeta Stores**  

Esta carpeta contiene las bases de datos utilizadas para el análisis.  

**Archivos incluidos:**  

- **Hollywood.xls**  

Este archivo contiene la información utilizada en el caso, incluyendo datos sobre:  

- Ingresos del primer fin de semana (Opening Gross)  
- Ingresos totales en EE. UU.  
- Ingresos internacionales  
- Presupuesto de producción  
- Número de salas de estreno  
- Género de la película  
- Clasificación MPAA  
- Secuelas y adaptaciones  
- Opinión de críticos  
- Premios Oscar  

Estos datos constituyen la base para el análisis estadístico y la construcción de los resultados obtenidos.

--------------------------------------------------  

# **Carpeta Scripts**  

Esta carpeta contiene el código utilizado para desarrollar el análisis de datos.  

El análisis fue realizado utilizando el software **R**.  

**Archivo incluido:**  

- **Caso Harvard Hollywood Rules.R**  

Este script incluye:  

- Preparación y limpieza de los datos  
- Cálculo de estadísticas descriptivas  
- Realización de pruebas de hipótesis  
- Construcción de modelos de regresión  
- Generación de gráficos y tablas  
- Análisis de relaciones entre variables  

--------------------------------------------------  

# **Carpeta Views**  

Esta carpeta contiene todas las **figuras, tablas y gráficos generados durante el análisis**.  

Entre las visualizaciones incluidas se encuentran:  

- Gráficos de distribución de variables clave  
- Diagramas de dispersión entre variables  
- Gráficos comparativos por género y clasificación  
- Resultados visuales de modelos de regresión  
- Tablas de estadísticas descriptivas  

Estas ilustraciones permiten interpretar y comunicar de manera clara los resultados obtenidos en el análisis.  

--------------------------------------------------  

# **Notas**  

Para ejecutar correctamente el análisis se recomienda utilizar **R o RStudio**.  

Antes de ejecutar los scripts es recomendable:  

1. Configurar el directorio de trabajo en la carpeta **Scripts** del repositorio.  
2. Verificar que todos los paquetes necesarios estén previamente instalados.  
3. Ejecutar los scripts siguiendo el orden indicado en el código.  

La velocidad de ejecución puede variar dependiendo de las características del equipo en el que se ejecuten los scripts.  
