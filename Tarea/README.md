#Tarea de replicación Ayudantía 2

En esta ayudantía vamos a replicar el estudio [Dynamics of cross-platform attention to retracted papers](https://www.pnas.org/doi/10.1073/pnas.2119086119).

Los autores pusieron a disposición de la comunidad un [repositorio en github](https://github.com/haoopeng/retraction_attention) con los datos procesados y los algoritmos usados para obtener los resultados de la investigación.


Los autores usan tres fuentes de datos: 

-  Altmetric que se puede acceder por investigadores en https://www.altmetric.com/research-access/ 

-  The Retraction Watch database que está disponible para investigadores del The Center For Scientific Integrity  sujeto a un acuerdo de uso de datos  (detalles en https://retractionwatch.com/retraction-watch-database-user-guide/). 

-  The Microsoft Academic Graph is publicly available at https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/ or https://www.microsoft.com/en-us/research/project/open-academic-graph/. 
  
-  También usan datos de tweets.  Dado resguardo de la privacidad de los usuarios, Twitter no permite compartir directamente el texto de los tweets. Para cumplir con este requerimiento, los autores proveen una identificación de los tweets como critical/uncritical. (https://developer.twitter.com/en/products/twitter-api/academic-research).


Como vemos, varios de estos datos están sujetos a inscripción de los investigadores y no pueden ser publicados directamente. Los autores ponen a nuestra disposición su código de trabajo (en una colección de notebooks), pero no los datos raw sino procesados.

Con estos datos procesados, podemos replicar directamente las tablas de resultado del trabajo.  Para poder hacer el match nosotros, necesitaremos más datos de los que ellos nos han compartido.

Nosotros haremos cuatro cosas:

1. Replicar el match  por nuestra cuenta
2. Estimar los resultados con nuestro match
3. Replicar los resultados con el match de los autores
4. Comparar los resultados de ambas estimaciones

