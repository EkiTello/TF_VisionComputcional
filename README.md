
Trabajo Final de Visión Computacional del Diplomado en IA de AI PUCP.
====================================

Este repositorio presenta los resultados obtenidos en el Trabajo Final de Visión Computacional integrado por:
- Erika Tello
- Diego De Lama

Problemática
------------------------------------
Una empresa agroindustrial dedicada a la selección de semillas de inducción, presenta un problema en la clasificación de semillas en haploides y diploides. Considerando que una población de 3 kilogramos puede tener cerca de 10,000 granos. De los cuales solo se desea seleccionar los granos haploides, ya que serán útiles para los próximos pasos del proceso. 

Los diploides son considerados descartes y están presentes en un 80%-88% del total de una población. Este porcentaje ocasiona que en próximas etapas se siembre semilla que debe ser descartada, e incrementa de costos y desperdicios. 

Debido a que las diferencias entre haploides y diploides son visuales → Se puede proponer un modelo de visión computacional. 

Dataset: https://www.rovile.org/datasets/haploid-and-diploid-maize-seeds-dataset/
![Test Image 4](https://github.com/EkiTello/TF_VisionComputcional/blob/main/img1.png)

Propuesta de solución
------------------------------------
- Aplicar modelos de red convolucional preentrenados freezeando las capas y adaptando la ultima capa para identificar las clases haploide y diploide.
![Test Image 4](https://github.com/EkiTello/TF_VisionComputcional/blob/main/img2_.png)
- Aplicar el paquete de Detecto que utiliza la red convulocional Faster RCC Resnet 50 FPN para detectar las clases haploides y diploides en una muestra de granos.
![Test Image 4](https://github.com/EkiTello/TF_VisionComputcional/blob/main/img3_.png) 
