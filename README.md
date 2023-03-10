# Proyecto Integrador de Data Science馃彔馃搳
## Descripci贸n del proyecto 馃攳

Este proyecto tiene como objetivo desarrollar una soluci贸n de Data Science completa para la p谩gina web de fincaraiz.com.co, utilizando t茅cnicas de web scraping, data engineering, an谩lisis de datos, machine learning y visualizaci贸n. Los pasos clave del proyecto son:

1) Realizar un web scraping de todos los departamentos publicados en fincaraiz.com.co utilizando Selenium, BS4 o Scrapy para recolectar informaci贸n sobre precios, caracter铆sticas, ubicaci贸n, entre otros. 馃暩

2) Pasar la informaci贸n recolectada a un dataframe y luego a un CSV o DB. 馃捑

3) Realizar un an谩lisis exploratorio de los datos (EDA) para entender las caracter铆sticas y tendencias de los departamentos. 馃攳

4) Realizar un proceso de limpieza, transformaci贸n y carga de los datos (ETL) para prepararlos para el modelado. 馃泚

5) Realizar un modelo de bases de datos para el DataWarehouse. 

6) Crear una API con FastAPI para facilitar el acceso a la informaci贸n de los departamentos almacenada en la base de datos. 馃捇

7) Crear una dashboard interactiva con PowerBI, Google DataStudio o Tableau para visualizar la informaci贸n recolectada y las predicciones realizadas. 馃搳

8) Desarrollar un modelo de machine learning para realizar predicciones sobre los precios de los departamentos. 馃

9) Containizar la API y el modelo de machine learning para su despliegue en un servidor de hosting a eleccion (un ejemplo es mogenius)


## Herramientas y tecnolog铆as utilizadas 馃洜
* Python
* Pandas, Numpy y Scikit-learn para el an谩lisis y modelado de los datos
* FastAPI para desarrollar la API
* PowerBI, Google DataStudio o Tableau para crear la dashboard interactiva
* SQL o MongoDB para almacenar los datos
* Selenium, BS4 o Scrapy para realizar el web scraping
* virtualenv para crear un entorno virtual
* Docker para contenerizar la API y subirlo a un servidor de hosting de su elecci贸n (como mogenius)

## C贸mo ejecutar el proyecto 馃殌
* Clonar este repositorio en su m谩quina local
* Crear un entorno virtual con virtualenv
* Instalar las dependencias necesarias utilizando pip o conda
* Ejecutar el script de web scraping con Selenium, BS4 o Scrapy para recolectar los datos
* Ejecutar el script de ETL para limpiar y preparar los datos
* Ejecutar el script de modelado para entrenar y evaluar el modelo de machine learning
* Iniciar el servidor de la API con FastAPI
* Utilizar la dashboard interactiva para visualizar la informaci贸n