# Entregable 3 de la asignatura Inteligencia Artificial, Curso 20/21

En este entregable vamos a crear un modelo de clasificación de texto utilizando técnicas de deep learning. En el notebook instrucciones.ipynb puedes ver los pasos que debes seguir para crear un modelo de clasificación de imágenes. 

Requisitos mínimos (7 puntos):

La tarea de este entregable consiste en elegir un dataset de clasificación de texto y crear un modelo de clasificación siguiendo los pasos explicados en el notebook de las instrucciones. Deberás crear un notebook detallando los pasos que des para crear el modelo. 

En primer lugar debes buscar un dataset para clasificación de texto. A continuación tienes un par de enlaces donde aparecen unos cuantos datasets para la clasificación de texto. 
- [Kaggle](https://www.kaggle.com/datasets?search=text+classification)
- [Variedad de datasets](https://lionbridge.ai/datasets/14-best-text-classification-datasets-for-machine-learning/)

Una vez que hayas descargado el dataset deberás organizarlo en carpetas siguiendo la estructura de fastai. Es decir, una carpeta dataset que contenga una carpeta train y otra carpeta test. Dentro de cada una de esas carpetas tiene que haber tantas subcarpetas como clases tiene el dataset. Por último cada carpeta de clase contendrá los ficheros de esa clase. En caso de que estés trabajando con un fichero csv también puedes cargarlo directamente como se explica en la [documentación de FastAI](https://docs.fast.ai/text.data.html#TextBlock.from_df)


Ampliaciones (3 puntos):
- En las instrucciones se explica cómo crear un modelo usando la arquitectura ULMFit, una ampliación consiste en construir modelos con la librería [blurr](https://github.com/ohmeow/blurr) y comparar los resultados obtenidos con las mismas (la comparativa puede incluir información como tiempos de entrenamiento, rendimiento de las redes, etc).
- Aplicar la técnica explicada en el blog de [Sylvain Gugger](https://sgugger.github.io/how-do-you-find-a-good-learning-rate.html#how-do-you-find-a-good-learning-rate) para seleccionar un learning rate correcto. 
- A partir del modelo construido, crear una aplicación para usarlo directamente.
- Compara los resultados que se obtienen entrenando el modelo de clasificación usando el modelo de lenguaje de Wikipedia. Tienes una explicación de cómo llevar a cabo ese proceso con el dataset IMDb en el [libro de fastai](https://github.com/fastai/fastbook/blob/master/01_intro.ipynb).
- Utilizar técnicas de ensemble (ver final de este [notebook](https://github.com/fastai/course-nlp/blob/master/nn-english.ipynb)) para mejorar los resultados del modelo. 
- Cualquier otra ampliación que incluyas será valorada positivamente. 
