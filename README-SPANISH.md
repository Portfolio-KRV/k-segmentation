# K-segmentation
Desarrollado en el curso de Reconocimiento de Patrones en Minería de Datos por: Kevin Reyes. 
## Objetivos
- Segmentar imágenes utilizando algoritmo K-Means.

## Descripción
Segmentación de imágenes con algoritmo K-Means.

## Conclusiones
- Se nota un aumento en la calidad de la imagen segmentada al aumentar el número de clusters, se puede captar mayor detalle de la imaen a través de más clusters, sin embargo esto último rara vez es el objetivo de segmentar imágenes.
- Para obtener un resultado óptimo, por ejemplo para que un vehículo autónomo logre detectar los objetos importantes en un recorrido, se debería considerar un número de cluster que como mínimo permita detectar los elementos esenciales, tales como: señales de tránsito, personas, soleras, paisaje y otros vehículos.
- El algoritmo puede presentar fallas cuando algunos objetos de la imagen tienen colores similares, ya que las segmenta en un mismo cluster cuando deberían ser distintos. Es decir, el algoritmo solo está considerando información de color para detectar los objetos, no utiliza información espacial o de forma.

## Stack de tecnologías
- Cv2.
- Numpy.
- Matplotlib.