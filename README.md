### Handwritten digit trascriber in images
This is the result of my master's thesis project, which falls within the field of computer vision.

In this project, the goal was to work on the recognition of handwritten digits that form a code and a date, and to store them in digital format for use in other applications, such as their insertion into a database.

To achieve the project's objective, it was necessary to use various computer vision techniques.

The techniques I am referring to are the following:

- **Semantic segmentation** to select the portion of the original image where the digits to be recognized are located.
- **Object detection**, which made it possible to detect, within the segmented image, the pixels belonging to each digit in order to isolate them.
- **Classification** of the areas where the digits were detected to identify the actual digits that make up the code and the target date.
  
For the implementation of these techniques, specific algorithms have been used:

- **U-NET** for segmentation, implemented using Python and TensorFlow.
- **YOLO**, a pre-trained object detection model, used to detect the different digits present in the segmented image.
- **Classifier**, implemented with a convolutional neural network (CNN) using Python and TensorFlow.
  
Different types of training were required for these algorithms:

- Training with a **custom dataset**, such as for U-Net.
- **Fine-tuning** YOLO with a custom dataset.
- Training with a standard dataset, such as **MNIST**, to train the classifier.
  
As can be seen, this project aims to showcase the widest range of techniques, algorithms, training methods, and strategies to demonstrate the immense potential and versatility of artificial intelligence when tackling problem-solving.


**Note: The names of companies or business activities referenced in the report are fictitious.**
--------------------------------------------------------------------------------------------------------------

### Transcriptor de dígitos escritos a mano en imagenes.

Este es el resultado de mi proyecto fin de master, que se enmarca dentro del campo de la visión artificial. 

En este proyecto la idea era trabajar el reconocimiento de dígitos escritos a mano que forman un código y una fecha, y almacenarlos en formato digital para su uso en otras aplicaciones, como por ejemplo su inserción en una base de datos. 

Para conseguir el objetivo marcado en este proyecto ha sido necesario utilizar diferentes técnicas de visión artificial.

Las técnicas a las que me refiero son las siguientes:
- **Segmentación semántica** para seleccionar el trozo de imagen original donde se encuentran los dígitos que se deben reconocer
- **Detección de objetos**, con la que ha sido posible detectar dentro de la imagen segmentada los pixeles que pertenecián a cada digito, para poder seleccionarlos.
- **Clasificación** de las zonas donde se habian detectado los digitos y conocer así los digitos que realmente componen el codigo y la fecha buscada.

Para la implementación de estas tecnicas ha sido necesario utilizar determinados algoritmos:
- **U-NET** en la segmentacion, el cual se ha implementado mediante codigo python y TensorFlow. 
- **YOLO**  modelo preentrenado en deteccion de objetos, para la detección de los diferentes digitos que aparecen en la imagen segmentada. 
- **Clasificador**, implementado con una red neuronal convolucional con python y  TensorFlow.

Sobre estos algoritmos se han tenido que realizar diferentes tipos de entrenamientos:
- Entrenamiento con un **dataset personalizado**, como por ejemplo en U-Net
- **Fine-tuning** sobre YOLO, con un dataset personalizado.
- Entrenamiento un dataset standart como es **MNist**, para entrenar el clasificador.

Como se puede apreciar, en este proyecto se ha intentado mostrar el mayor numero de técnicas, algoritmos, entrenamientos y estrategias, para mostrar el grandísimo potencial y la versatilidad que tiene la inteligencia artificial a al hora de enfrentarse a la solución de un problema.


**Nota: los nombres de empresas o actividades empresariales a los que se hacen referencia en la memoria son ficticios.**
