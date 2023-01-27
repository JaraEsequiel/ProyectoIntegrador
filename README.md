# Proyecto Integrador de Data Science🏠📊
## Descripción del proyecto 🔍

Este proyecto tiene como objetivo desarrollar una solución de Data Science completa para la página web de fincaraiz.com.co, utilizando técnicas de web scraping, data engineering, análisis de datos, machine learning y visualización. Los pasos clave del proyecto son:

1) Realizar un web scraping de todos los departamentos publicados en fincaraiz.com.co utilizando Selenium, BS4 o Scrapy para recolectar información sobre precios, características, ubicación, entre otros. 🕸

2) Pasar la información recolectada a un dataframe y luego a un CSV o DB. 💾

3) Realizar un análisis exploratorio de los datos (EDA) para entender las características y tendencias de los departamentos. 🔍

4) Realizar un proceso de limpieza, transformación y carga de los datos (ETL) para prepararlos para el modelado. 🛁

5) Realizar un modelo de bases de datos para el DataWarehouse. 

6) Crear una API con FastAPI para facilitar el acceso a la información de los departamentos almacenada en la base de datos. 💻

7) Crear una dashboard interactiva con PowerBI, Google DataStudio o Tableau para visualizar la información recolectada y las predicciones realizadas. 📊

8) Desarrollar un modelo de machine learning para realizar predicciones sobre los precios de los departamentos. 🤖

9) Containizar la API y el modelo de machine learning para su despliegue en un servidor de hosting a eleccion (un ejemplo es mogenius)


## Herramientas y tecnologías utilizadas 🛠
* Python
* Pandas, Numpy y Scikit-learn para el análisis y modelado de los datos
* FastAPI para desarrollar la API
* PowerBI, Google DataStudio o Tableau para crear la dashboard interactiva
* SQL o MongoDB para almacenar los datos
* Selenium, BS4 o Scrapy para realizar el web scraping
* virtualenv para crear un entorno virtual
* Docker para contenerizar la API y subirlo a un servidor de hosting de su elección (como mogenius)

## Cómo ejecutar el proyecto 🚀
* Clonar este repositorio en su máquina local
* Crear un entorno virtual con virtualenv
* Instalar las dependencias necesarias utilizando pip o conda
* Ejecutar el script de web scraping con Selenium, BS4 o Scrapy para recolectar los datos
* Ejecutar el script de ETL para limpiar y preparar los datos
* Ejecutar el script de modelado para entrenar y evaluar el modelo de machine learning
* Iniciar el servidor de la API con FastAPI
* Utilizar la dashboard interactiva para visualizar la información