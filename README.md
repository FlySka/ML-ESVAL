# ML-ESVAL
Proyecto de diseño de modelos de machine learning para empresa ESVAL S.A.

******************************************************
AUTOR:                                              
Joaquin Farias Muñoz                                
practicante                                         
Ingenieria civil electronica                        
Pontificia universidad catolica de Valparaiso       
******************************************************

## Descripción del proyecto

En este proyecto se diseñaron modelos de machine learning para la empresa ESVAL S.A. que ayudaran a solucionar el problema de refacturas de clientes. A grandes rasgos las estas refacturas ocurren cuando hay un mal cobro a un cliente y este reclama; estos conlleva un costo para la empresa.
LA base de datos es desbalanceada por lo que tuvieron que ocuparse metodos especiales para este tipo de bases de datos; esta no puede ser compartida por confidencialidad, así como tampoco los modelos guardados. Tambien, se crearon metricas especiales para el problema.

Se hizo una exploración de los datos y se probaron distintos modelos y preprocesamiento de los datos.

Se crearon modelos con los algoritmo:
* Redes neuronales
* árbol de decisión
* Regresión logistica
* XGBoost

## Contenido

* Exploracion de datos [[Jupyter Notebook]](https://github.com/FlySka/ML-ESVAL/blob/main/varios/Exploraci%C3%B3n%20de%20datos_V2.ipynb)

* Codigos para entrenamiento de modelos [[Jupyter Notebook]](https://github.com/FlySka/ML-ESVAL/tree/main/Train)

* Codigos para ejecucion de modelos [[Jupyter Notebook]](https://github.com/FlySka/ML-ESVAL/tree/main/Ejecucion)

* Informe del proyecto  [[PDF]](https://github.com/FlySka/ML-ESVAL/blob/main/Entregables/Informe%20ML%20ESVAL_Joaquin%20Farias_V3.pdf) [[PDF (Formato doble columna)]](https://github.com/FlySka/ML-ESVAL/blob/main/Entregables/Informe%20ejecutivo%20ML_Joaquin%20Farias_V3.pdf)

* Presentacion del proyecto [[PDF]](https://github.com/FlySka/ML-ESVAL/blob/main/Entregables/Presentacion%20proyecto%20ML%20ESVAL_Joaquin%20Farias_V3.pdf)

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
