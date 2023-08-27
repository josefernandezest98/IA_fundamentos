# Entregable 2 de la asignatura Inteligencia Artificial, Curso 20/21

En este entregable vamos a crear un modelo de clasificación de imágenes utilizando técnicas de deep learning. En el notebook instrucciones.ipynb puedes ver los pasos que debes seguir para crear un modelo de clasificación de imágenes. 

Requisitos mínimos (5 puntos):
La tarea de este entregable consiste en elegir un problema de clasificación de imágenes (puedes elegir el tema que quieras, la única restricción es que el problema de clasificación debe contener al menos tres categorías) y crear un modelo de clasificación siguiendo los pasos explicados en el notebook de las instrucciones. Deberás crear un notebook con los pasos que des para crear el modelo. Para construir tu dataset puedes construir tu propio dataset siguiendo los pasos explicados en el blog de [Adrian Rosebrock](https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/) o usar un dataset que ya exista como los proporcionados en [kaggle](https://www.kaggle.com/datasets?search=image+classification).

Ampliaciones (5 puntos):
- En las instrucciones se explica cómo crear un modelo usando la arquitectura ResNet 34, una ampliación consiste en construir modelos con otras [arquitecturas](https://pytorch.org/docs/stable/torchvision/models.html) y comparar los resultados obtenidos con las mismas (la comparativa puede incluir información como tiempos de entrenamiento, rendimiento de las redes, etc).
- Limpiar el dataset. 
- Intentar entrenar un modelo usando CPUs y comparar los tiempos con los obtenidos usando GPUs.
- Aplicar la técnica explicada en el blog de [Sylvain Gugger](https://sgugger.github.io/how-do-you-find-a-good-learning-rate.html#how-do-you-find-a-good-learning-rate) para seleccionar un learning rate correcto. 
- A partir del modelo construido, crear una aplicación para usarlo directamente.
- Cualquier otra ampliación que incluyas será valorada positivamente. 
