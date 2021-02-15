# ML-ESVAL
Proyecto de diseño de modelos de machine learning para empresa ESVAL S.A.

******************************************************
AUTOR:                                              
Joaquin Farias Muñoz                                
practicante                                         
Ingenieria civil electronica                        
Pontificia universidad catolica de Valparaiso       
******************************************************

## Indice


## Algunas indicaciones
#### Dentro de cada carpeta hay un archivo README.txt para una descripcion mas detallada.

Descripcion de los carpetas:

---> Carpeta Train: dentro tiene los archivos para entrenar los modelos.

---> Carpeta uso_diaro: dentro tiene los archivos para ocupar los modelos en los datos del dia.

---> Carpeta varios: dentro tiene los archivos con la exploracion de los datos que incluye tambien el codigo para separar
     los datos en chuncks (la funcion de carga de datos esta hecha con 3), ademas con las codificaciones si se quisieran 
     cambiar.


Para ocupar todos estos archivos se recomienda tener la base de datos en la carpeta especifica de train o uso diario, 
  segun corresponda.

Para el caso de los datos no-analista los archivos deberian llamarse:
   -> Para entrenamiento: "data-analista2016-2018v3.csv"

   -> Para test (uso diario): "data_analista.csv"

 Para el caso de los datos no-analista los archivos deberian llamarse:
   -> Para entrenamiento: "chunk1_2016-2018v3.csv", "chunk2_2016-2018v3.csv", "chunk3_2016-2018v3.csv"

   -> Para test (uso diario): "data_no-analista.csv"

 lo anterior puede modificarse si se cambia el parametro "archivo" de los codigos.
