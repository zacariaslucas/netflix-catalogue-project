# PROYECTO DE ANÁLISIS DE DATOS SOBRE EL CONTENIDO DEL CATÁLOGO DE NETFLIX

### OBJETIVO
La empresa Netflix necesita un análisis histórico de su contenido que permita detectar oportunidades de mejora de la plataforma y tomar decisiones estratégicas para futuras incorporaciones al catálogo.

### BASE DE DATOS UTILIZADA
El dataset proviene de Kaggle y contiene 8.807 registros con la siguiente información acerca del contenido de Netflix:
- **ID**: Identificador del contenido.
- **Tipo**: Identificador que indica si se trata de una película o serie.
- **Título**: Nombre del contenido.
- **Director**: Nombre del director.
- **Reparto**: Lista de actores que aparecen.
- **País**: Lugar donde fue producida.
- **Fecha de adición**: Cuándo fue añadida al catálogo de Netflix.
- **Fecha de estreno**: Cuándo se estrenó.
- **Clasificación**: Código que indica el público para el cual es apto el contenido.
- **Duración**: Tiempo en minutos para el caso de las películas y en temporadas para las series.
- **Categorías**: Listado de géneros en los que se clasifica.
- **Descripción**: Sinopsis de la trama.


### METODOLOGÍA
1.	Se selecciona la base de datos y se limpia con SQL al detectar varios problemas en ella: registros duplicados, campos valores múltiples, datos inconsistentes...
2.	Se analiza la nueva base de datos mediante SQL para obtener los primeros insights.
3.	Se utiliza Tableau para construir un dashboard interactivo que permite visualizar los patrones detectados y analizar los factores asociados a los retrasos.

### DASHBOARD
[<img width="1619" height="1079" alt="Dashboard 1" src="https://github.com/user-attachments/assets/6ed0601b-57c7-4497-adf8-51dd12093103" />
](https://public.tableau.com/views/Netflix_17743679369640/Dashboard1?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### CONCLUSIONES
Tras el análisis de los datos de origen y la comprensión de los resultados obtenidos, se obtienen las siguientes conclusiones:
-	Las películas tienen mucho más protagonismo que las series, representando un 70% del contenido.
-	El tiempo medio que transcurre entre el estreno del contenido y su incorporación al catálogo de Netflix es de 4,7 años.
-	El año que mayor crecimiento tuvo el catálogo con respecto al año anterior fue 2016, mientras que el año que más incorporaciones hubo fue en 2019.
-	Los géneros que más abundan son las películas internacionales, los dramas y las comedias.
-	El país que más contenido genera es, con diferencia, Estados Unidos.
-	Las categorías dominantes son TV-MA, TV-14 y TV-PG, indicando un enfoque a una audiencia madura.
