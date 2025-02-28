### Handwritten digit trascriber in images
This is the result of my master's thesis project, which falls within the field of computer vision.

In this project, the goal was to work on the recognition of handwritten digits that form a code and a date, and to store them in digital format for use in other applications, such as their insertion into a database.

To achieve the project's objective, it was necessary to use various computer vision techniques.

The techniques I am referring to are the following:

- **Semantic segmentation** to select the portion of the original image where the digits to be recognized are located.
- **Object detection**, which made it possible to detect, within the segmented image, the pixels belonging to each digit in order to isolate them.
- **Classification** of the areas where the digits were detected to identify the actual digits that make up the code and the target date.
- 
For the implementation of these techniques, specific algorithms have been used:

- **U-NET** for segmentation, implemented using Python and TensorFlow.
- **YOLO**, a pre-trained object detection model, used to detect the different digits present in the segmented image.
- **Classifier**, implemented with a convolutional neural network (CNN) using Python and TensorFlow.
  
Different types of training were required for these algorithms:

- raining with a custom dataset, such as for U-Net.
- Fine-tuning YOLO with a custom dataset.
- Training with a standard dataset, such as MNIST, to train the classifier.
- 
As can be seen, this project aims to showcase the widest range of techniques, algorithms, training methods, and strategies to demonstrate the immense potential and versatility of artificial intelligence when tackling problem-solving.

