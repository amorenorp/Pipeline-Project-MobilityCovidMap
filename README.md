## *Mobility Covid Map*

![MobilityCovidMap](https://github.com/yamadajc/Pipeline-Project-MobilityCovidMap/blob/main/images/applecovid.jpg).



### Introducion:
El 13 de enero del 2020 Apple empezo a proporcionar de manera gratuita los datos referidos a las tendencias de movilidad de los usuarios de sus dsispositivos. 

Estos datos se generan contando la cantidad de solicitudes realizadas a Mapas de Apple para obtener indicaciones en países, regiones, subregiones y ciudades concretas. Los datos que se envían desde los dispositivos de los usuarios al servicio de Mapas están asociados con identificadores rotativos aleatorios para que Apple no tenga un perfil de los movimientos y búsquedas a nivel individual. La disponibilidad de datos de un país, región, subregión o ciudad en particular se basa en una serie de factores, incluidos los umbrales mínimos para las solicitudes de indicaciones al día.

### Objetivos: 
>En este proyecto se manipulara un conjunto de datos, previamente depurado con el fin de enriquecerlos a traves de tecnicas de Web scraping con el fin de aportar valor formativo e informativo.

### Datos:
>El analisis de la tendencia de la movilidad se realizara sobre los datos extraidos directamente del sitio oficial de apple. Los informes se publican diariamente y reflejan las solicitudes de indicaciones en Mapas de Apple. En el siguiente enlace podremos descargar los datos al completo https://covid19.apple.com/mobility con los cambios diarios en las solicitudes de indicaciones por tipo de transporte para todos los países, regiones, subregiones y ciudades disponibles.

>Los datos presentes en esp_pop.csv han sido extraidos de la enciclopedia Wikipedia mediante la tecnica de Web scraping.

> En el archivo report.ipynb podras accceder a los ditintios procesos necesarios para trabajar con un data frame generando series temporales y sus visualizaciones. 



