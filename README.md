# Repositorio para calcular Tabulados de la ENSU
![Estatus](https://img.shields.io/badge/Estatus-desarrollo-yellow)

## Introducción

En este repositorio encuentras código en R para realizar el cálculo de algunos tabulados básicos de la encuesta ENSU.


## Acerca de este proyecto

La Encuesta Nacional de Seguridad Pública Urbana (ENSU) 2024 es un proyecto estadístico destinado para enriquecer la oferta de información de interés nacional vinculada al Subsistema Nacional de Información de Gobierno, Seguridad Pública e Impartición de Justicia.

La encuesta se llevó a cabo con la finalidad de obtener información que permita realizar estimaciones sobre la percepción de la población acerca de la seguridad pública en su ciudad, tanto a nivel nacional como en cada una de las áreas urbanas (ciudades) de interés.

Para mayor información y descarga de datos, cuestionarios, etcétera visite el enlace: [ENSU](h#ttps://www.inegi.org.mx/programas/ensu/)



## Requerimientos
- [R (> 4.0)](https://www.r-project.org/)
- [Quarto](https://quarto.org/)  

Se recomienda instalar el IDE [Rstudio](https://www.rstudio.com/categories/rstudio-ide/), sin embargo es posible correr este proyecto con cualquier otro IDE donde la persona usuaria pueda utilizar `R`.

## Instrucciones de uso

Para ejecutar el código en este repositorio es necesario tener instalado el lenguaje de programación estadística `R`. El repositorio está ordenado de tal forma que todos los códigos se encuentran en la carpeta `procesamiento` y los datos se almacenan en la carpeta `datos`.

El primer paso es descargar los datos de la ENSU [Datos](https://www.inegi.org.mx/programas/ensu/#microdatos) del portal del INEGI, descomprime y pega las tablas csv en la carpeta `datos-originales`. Renderiza el archivo `tabulados.qmd` para obtener un `Html con la explicación de uso`