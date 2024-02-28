# MODELO_ML_Genero_MoMA
[English]
This repository contains a set of files related to the development of Machine Learning models regarding gender equality in the MoMA (Museum of Modern Art, NY) archive, carried out within the framework of a Data Science bootcamp.

[Spanish]
Este repositorio contiene un conjunto de archivos relativos a la elaboración de modelos de Machine Learning relativos a igualdad de género en el archivo del MoMA (Museo de arte moderno, NY), realizado en el marco de un bootcamp de Data Science.

__

El repositorio contiene documentos relativos a la elaboración de modelos de Machine Learning relativos a la igualdad de género en el archivo del MoMA (Museo de arte moderno, NY). 
A partir del "data set" The Museum of Modern Art (MoMA) Collection https://github.com/MuseumofModernArt/collection  ![image](https://github.com/a-ndrea-st/MODELO_ML_Genero_MoMA/assets/145352044/a701d208-f1ac-423c-b544-cfc7bb802c63)
, que recoge la colección de uno de los museos de arte moderno y contemporáneo más influyentes del mundo (desde 1929 hasta la actualidad), se ha realizado un análisis del equilibrio de género en las obras. 
En concreto, se ha partido de un EDA centrado en el género para desarrollar tres modelos de machine learning:
1) Clasificación de género de artistas: He usado características como la fecha de nacimiento, la nacionalidad, la fecha de adquisición de la obra para predecir el género del artista (RandomForest, SVM, Regresión logística)
2) Regresión lineal y polinómica. He realizado un modelo para hacer una predicción del año en que el museo alcanzará la igualdad de género en cuanto al número de obras pintadas por mujeres.

Para realizar el análisis de los datos, se han empleado bibliotecas de Python (Documentación oficial) utilizadas para análisis de datos y visualización:

o	NumPy (Documentación oficial) https://numpy.org/doc/stable/ 
o	Pandas (Documentación oficial) https://pandas.pydata.org/pandas-docs/stable/
o	Matplotlib (Documentación oficial) https://matplotlib.org/stable/users/index.html
o	Seaborn (Documentación oficial) https://seaborn.pydata.org/api.html
o	Plotly (Documentación oficial) https://plotly.com/python-api-reference/
o	Scikit-learn (Documentación oficial) https://scikit-learn.org/0.21/documentation.html

__

El archivo Presentación_MODELO es un ppt con la presentación de los resultados.

El archivo Documentación utilizada detalla la documentación, tanto de herramientas y tecnologías, como literatura técnica.

Dentro de la carpeta scr se encuentra el código, siguiendo la estructura:

src/data: todos los archivos de datos utilizados en el analisis.

src/notebooks: contiene el notebook usado para pruebas.

src/utils: contiene todos los modulos y funciones auxiliares creados para el desarrollo del proyecto.

src/main.ipynb: contiene el notebook con todos los pasos de la analítica.
