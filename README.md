# Trabajo final del máster en Data Science

# Descripción 
Este proyecto se basa en el desarrollo del producto para el trabajo final titulado **"Analítica de datos aplicada a la identificación de barrios de la ciudad de Madrid que se encuentren en proceso de gentrificación"** del máster en Data Science. Este trabajo se basa en analizar de forma estadística y geoespacial los datos abiertos referentes a los factores que causan gentrificación en los barrios de Madrid, teniendo en cuenta la edad, nacionalidad, tamaño de los hogares, nivel de estudios y densidad de la población. La captura de los datos, el tratamiento y el análisis estadistico se ha realizado en R, mientras que el análisis geoespacial se ha llevado a cabo en ArcGIS Pro. Por último, se ha publicado un visor interactivo con los factores de gentrificación y un espacio para explorar las capas superpuestas en ArcGIS Online (AGOL)

# Autores
- Autora del TFM: **Paula Andrea Rodriguez Mancipe**

- Directora del TFM: **Anna Muñoz Bollas**

- Profesor responsable de la asignatura: **Albert Solé Ribalta**

# Estructura del Git

En este GitHub se pueden encontrar los siguientes archivos:

- **código/codigo_R_TFM_Gentrificacion_Madrid.Rmd** contiene la implementación en R que carga los datos del estudio y genera las capas en ArcGIS Pro utilizando el conector R-ArcGIS Bridge.

- **código/Datos** directorio que contiene los archivos con la información suministrada por el Ayuntamiento de Madrid. Las cuales son:

  - **código/Datos/Edad_Nacionalidad** directorio que contiene los conjuntos CSV para el estudio de los factores edad y nacionalidad que influyen en el proceso de gentrificación.
  - **código/Datos/Tamaño_hogar** directorio que contiene los conjuntos CSV para el estudio del factor tamaño del hogar que influye en el proceso de gentrificación.
  - **código/Datos/Nivel_de_Estudios** directorio que contiene los conjuntos CSV para el estudio del factor nivel de estudio que influye en el proceso de gentrificación.
  - **código/Datos/Densidad** directorio que contiene el conjunto CSV para analizar la densidad de habitantes por hectarea en cada barrio de Madrid.
  - **código/Datos/Barrios** directorio que contiene el ZIP con los datos de los barrios de Madrid.


- **código/Exports** directorio que contiene las capas exportadas de ArcGIS Pro. Las cuales son:

  - **código/Exports/Edad_Nacionalidad** directorio que contiene los shapefiles de las capas de los factores edad nacionalidad.
  - **código/Exports/Tamaño_hogar** directorio que contiene los shapefiles de las capas del factor tamaño hogar.
  - **código/Exports/Nivel_de_Estudios** directorio que contiene los shapefiles del factor nivel de estudios.
  - **código/Exports/Densidad** directorio que contiene los shapefiles de la densidad de la población.

