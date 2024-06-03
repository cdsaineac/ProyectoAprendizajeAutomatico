# Proyecto Aprendizaje Automático
## Predicción de Supervivencia en Pacientes con COVID-19 en Colombia: Un Enfoque Basado en Aprendizaje Supervisado y Variables Demográficas
En este repositorio se encuentran los notebooks con los cuales se realizó el proyecto para la clase de aprendizaje automático. A continuación se descrie el funcionamiento de cada uno:

1. PreparacionDatos.ipynb: Contiene el paso a paso de como se preprocesó la información previo a entrar al modelo.
2. Carpetas RandomForest y GradientBoosting: Contiene los notebooks donde se realizó la validación cruzada para cada uno de los modelos (RandomForest y HistGradientBosting). Cada modelo contiene dos notebooks con GridSearchCV, mostrando el proceso de validación cruzada para con rebalanceo OverSampling y otro con realanceo UnderSampling. También se agregan dos notebooks que contienen el entrenamiento y validación para el conjunto de datos completo usando el mejor modelo resultante de la validación cruzada.
3. ComparaciónModelos.ipynb: Contiene la comparación entre los modelos seleccionados con los diferentes hiper parametros.
