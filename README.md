# PRAC 1. Web scraping

## Descripción

Esta práctica se ha realizado bajo el contexto de la asignatura _Tipología y ciclo de vida de los datos_, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. En ella, se aplican técnicas de _web scraping_ mediante el lenguaje de programación Python para extraer así datos de la web _PlaneCrashInfo_ y generar un _dataset_.


## Miembros del equipo

La actividad ha sido realizada por **Luis Alberto Bayo** y **Miguel Ángel Bermejo Águeda**.


## Ficheros del código fuente

* **src/main.py**: punto de entrada al programa. Inicia el proceso de scraping.
* **src/scraper.py**: código que genera el conjunto de datos **LaLiga123_17-18_stats** a partir de la base de datos online [LaLiga123](https://www.laliga.es/estadisticas-historicas/plantillas/segunda/2017-18/).
* **src/reason_classifier.py**: contiene la implementación de la clase que se encarga de asignar una causa a un resumen de accidente dado. Para ello, utiliza la librería *TextBlob*.


## Recursos

- Lawson, R. (2015). _Web Scraping with Python_. Packt Publishing Ltd. Chapter 2. Scraping the Data.
- Simon Munzert, Christian Rubba, Peter Meißner, Dominic Nyhuis. (2015). _Automated Data Collection with R: A Practical Guide to Web Scraping and Text Mining_. John Wiley & Sons.
