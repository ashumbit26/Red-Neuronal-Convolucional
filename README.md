# Red Neuronal Convolucional 
Este proyecto consiste en el desarrollo de una Red Neuronal Convolucional (CNN) para la clasificación de imágenes de animales. El modelo fue entrenado con cinco clases definidas, con el objetivo de identificar si una imagen pertenece a alguna de ellas o si se encuentra fuera de las categorías establecidas.


## Objetivo
Desarrollar una Red Neuronal Convolucional capaz de clasificar imágenes dentro de cinco categorías de animales previamente definidas, incorporando una estrategia para identificar imágenes que no correspondan a ninguna de las clases entrenadas.


## Características Principales
- Implementación de la CNN desde cero en Python.
- Uso de capas convolucionales para la extracción de características visuales.
- Implementación de una capa de pooling para reducción dimensional.
- Uso de capas totalmente conectadas para la clasificación final.
- Implementación manual del forward pass.
- Implementación explícita del algoritmo de backpropagation.
- Cálculo de gradientes para el ajuste de pesos.
- Actualización de pesos mediante descenso de gradiente.
- Implementación de función de activación no lineal y su derivada.
- Estrategia de umbral de confianza para detectar imágenes fuera de las clases entrenadas.


## Tecnologías Utilizadas
- Python
- NumPy
- OpenCV / PIL
- Matplotlib


## Nota sobre el conjunto de datos
El conjunto de imágenes utilizado para el entrenamiento no se incluye en este repositorio por motivos de tamaño y organización. El notebook está preparado para ejecutarse en Google Colab utilizando una ruta de Google Drive.
