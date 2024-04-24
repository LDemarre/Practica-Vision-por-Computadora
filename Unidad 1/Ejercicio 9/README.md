# Unidad 1 - Ejercicio 9

## **Enunciado**
Tomar fotografías donde coexistan varios objetos en posiciones solapadas y no, en contextos de diferente complejidad. Luego, aplicar los algoritmos de segmentación propuestos y verificar los resultados de cada uno. Comentar qué diferencias observa. 

## **Recursos**
### 'Algoritmos/'
Esta carpeta contiene carpetas destinadas para guardar los archivos necesarios que necesita cada algoritmo utilizado en el ejercicio.

### 'Escenarios/'
Contiene las dos imágenes que se van a utilizar para la prueba de segmentación de objetos. En cada imagen se encuentran los siguientes tres objetos:
* Un libro
* Un celular
* Un control remoto

Imágenes
* 'escenario_1.jpg': **Los tres objetos sin solapamientos**
* 'escenario_2.jpg:' **Los tres objetos con solapamientos**

### 'Ejercicio 9.ipynb'
Colab donde se utilizan los distintos algoritmos para segmentar los objetos en ambas imágenes. 
Algoritmos utilizados: 
* Mask R-CNN (OpenCV)
* SAM (Segment Anything Model)
* DERT ResNet50 (Transformers)

## **Utilidades**
Es necesario instalar las siguientes librerías para su correcto funcionamiento:
* timm
* pytorch
* torchvision
* transformers