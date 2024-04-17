# <h1 align="center"> Análisis de la validación de hipótesis para la toma de decisiones  </h1>

Una discográfica se enfrenta al emocionante desafío de lanzar a un nuevo artista en la escena musical global. Aunque cuenta con un extenso conjunto de datos (Spotify) que detalla las canciones más escuchadas en 2023, la incertidumbre rodea a los factores que realmente impulsan el éxito de una canción en términos de streams en Spotify.

La discográfica planteó una serie de hipótesis sobre qué hace que una canción sea más escuchada. Estas hipótesis incluyen:

▪️ Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify.

▪️ Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer.

▪️ La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.

▪️ Los artistas con un mayor número de canciones en Spotify tienen más streams totales.

▪️ Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify.


## Objetivo del proyecto

Validar o refutar estas hipótesis mediante un análisis de datos profundo. A través de estos hallazgos, se busca ofrecer recomendaciones estratégicas que permitan a la discográfica y al nuevo artista tomar decisiones informadas, aumentando así sus posibilidades de alcanzar el "éxito" en términos de streams en Spotify.

## Insumos

El conjunto de datos está disponible para descargar en este enlace 'https://bit.ly/3Q4e77g'

## Herramientas que se usaron para el análisis

### Herramientas:

▪️ BigQuery 

▪️ Google Cloud

▪️ Google Colab

▪️ Pitch

▪️ Power BI

### Lenguajes:

▪️ SQL

▪️ Python

## ¿Cuál fue el proceso de trabajo?


| **Procesar y preparar la base de datos**                               | **Análisis exploratorio**                                    | **Técnica de análisis** |
|------------------------------------------------------------------------|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| ▪️ Importación de datos a BigQuery                                      | ▪️ Agrupar datos según variables categóricas                  |  ▪️ Validación de hipótesis a través de la prueba de Mann-Whitney U para muestras no paramétricas|
| ▪️ Identificar Y manejar valores nulos                                  | ▪️ Visualizar las variables categóricas                       | ▪️ Regresión lineal |
| ▪️ Identificar y manejar valores duplicados                             | ▪️ Aplicar medidas de tendencia central y de dispersión      |
| ▪️ Identificar y manejar datos fuera del alcance del análisis           | ▪️ Visualizar distribución - histogramas     |
| ▪️ Identificar y manejar datos discrepantes en variables categóricas    | ▪️ Cálculo de cuartiles |
| ▪️ Identificar y manejar datos discrepantes en variables numéricas      | ▪️ Cálculo de la correlación entre variables |
| ▪️ Comprobar y cambiar tipo de dato                                     | |
| ▪️ Creación de nuevas variables                                         |                                             |
| ▪️ Unión de tablas                                                      |                                            |
| ▪️ Contruir tablas auxiliares                                           |                                                    |


## Chequea mis consultas en SQL

Aquí 'https://bit.ly/3xDSMvh'

## Dashboard en Power BI



