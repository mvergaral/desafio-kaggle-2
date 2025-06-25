# desafio-kaggle-2

Este repositorio contiene un ejemplo de predicción de precios de casas utilizando imágenes y datos numéricos. El notebook `cnn_solution.ipynb` aplica varios pasos de preprocesamiento y emplea una red convolucional preentrenada para mejorar las predicciones.

Para ejecutarlo:

1. Instalar dependencias con `pip install -r requirements.txt`.
2. Ejecutar todas las celdas de `cnn_solution.ipynb` para entrenar el modelo y generar `submission.csv`.

Los datos deben estar en la carpeta `data` y las imágenes en `imgs` tal como se proveen en este repositorio.

El flujo de trabajo realiza una limpieza de las columnas de fecha, completa valores faltantes con la media del conjunto de entrenamiento y estandariza las variables numéricas. Para las imágenes se utiliza un modelo ResNet preentrenado como extractor de características y se combinan dichas representaciones con los atributos numéricos.
