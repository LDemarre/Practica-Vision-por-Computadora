# Unidad 1 - Ejercicio 5

## **Enunciado**
Genere un video en un patio o en un hall de edificio donde en un principio se vea vacío y luego aparezca una persona. Mediante los métodos de motion detection (sin usar deep learning) logre una detección de la persona cuando entra al cuadro suponiendo la utilidad para una cámara de seguridad. Luego sobre el mismo video aplique los algoritmos de flujo denso y disperso que se mostraron en clase. Escriba una reflexión sobre los resultados en el formato md dentro del Jupyter Notebook.

## **Recursos**
### 'videos/'
Esta carpeta contiene los videos que se utilizaran para la detección de movimiento utilizando distintos algoritmos. Cada video de cada algoritmo se guarda a su vez en otra carpeta dentro de la esta misma llamada **'videos_motion_detection'**.  El video base utilizado esta sacado de una camara de seguridad del Buffet que le pertenece a mis padres, por lo que es material propio. Dicho video lo use porque justamente proviene de una camara de seguridad lo cual es un objetivo dentro del enunciado, que el *video sea utilizado suponiendo la utilidad para una cámara de seguridad*. 

### 'videos/videos_motion_detection/'
* 'security_camera_fdfull.mp4': **Frame Difference**
* 'security_camera_bs.mp4:' **Background Subtraction**
* 'security_camera_fdfull': **Optical Sparse flow**
* 'security_camera_pdoflow': **Optical Dense Flow**

### 'Ejercicio 5.ipynb'
Colab donde se utilizan los distintos algoritmos para detectar movimiento en un video sobre el video base para ver su funcionamiento. 
Algoritmos utilizados: 
* Frame Difference
* Background Subtraction
* Optical Sparse Flow
* Optical Dense Flow