#########################################################
Proyecto de machine learning para empresa ESVAL S.A    ##
#########################################################


******************************************************
AUTOR:                                              **
Joaquin Farias Muñoz                                **
practicante                                         **
Ingenieria civil electronica                        **
Pontificia universidad catolica de Valparaiso       **
******************************************************

# Dentro de esta carpeta se encuetran los archivos para entrenar y guardar los modelos junto con su
  validacion con los datos de diciembre de 2018.
# Existen dos tipos de modelos:
## con datos de analista (DA)
## con datos de no-analista (DNA)

# Modelos con datos analista

### archivos con modelos sin divisiones en los datos
---> train_NN_DA_sindiv.ipynb: notebook con codigo para entrenar modelo de redes neuronales artificiales.
---> train_XGB_DA_sindiv.ipynb: notebook con codigo para entrenar modelo con algoritmo XGBoost.
---> train_LR_DA_sindiv.ipynb: notebook con codigo para entrenar modelo con algoritmo de regresion logistica.
---> train_DT_DA_sindiv.ipynb: notebook con codigo para entrenar modelo con algoritmo de arbol de decision.

### Archivos con modelos con division por temporada
---> train_NN_DA_temporada.ipynb: notebook con codigo para entrenar modelo de redes neuronales artificiales.
---> train_XGB_DA_temporada.ipynb: notebook con codigo para entrenar modelo con algoritmo XGBoost.

### Archivos con modelos con division por codigo de diametro
---> train_NN_DA_diametro.ipynb: notebook con codigo para entrenar modelo de redes neuronales artificiales.
---> train_XGB_DA_diametro.ipynb: notebook con codigo para entrenar modelo con algoritmo XGBoost.

## Modelos con datos no-analista

### archivos con modelos sin divisiones en los datos
---> train_NN_DNA_sindiv.ipynb: notebook con codigo para entrenar modelo de redes neuronales artificiales.
---> train_XGBN_DNA_sindiv.ipynb: notebook con codigo para entrenar modelo con algoritmo XGBoost.
---> train_LR_DNA_sindiv.ipynb: notebook con codigo para entrenar modelo con algoritmo de regresion logistica.
---> train_DT_DNA_sindiv.ipynb: notebook con codigo para entrenar modelo con algoritmo de arbol de decision.

### Archivos con modelos con division por temporada
---> train_NN_DNA_temporada.ipynb: notebook con codigo para entrenar modelo de redes neuronales artificiales.
---> train_CGB_DNA_temporada.ipynb: notebook con codigo para entrenar modelo con algoritmo XGBoost.

### Archivos con modelos con division por codigo de diametro
---> train_NN_DNA_diametro.ipynb: notebook con codigo para entrenar modelo de redes neuronales artificiales.
---> train_XGB_DNA_diametro.ipynb: notebook con codigo para entrenar modelo con algoritmo XGBoost.