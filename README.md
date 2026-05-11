# CIFAR-10-Image-Classification-with-CNN
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset. The model is designed to recognize 10 different classes of objects in 32 X 32 RGB images.

Model Architecture
The model is a Sequential CNN built with the following layers:

Convolutional Layers: Multiple Conv2D layers for feature extraction.

Pooling Layers: MaxPooling2D layers to reduce spatial dimensions.

Flattening: A Flatten layer to transition from convolutional layers to dense layers.

Dense Layers: Fully connected layers for classification, including a final layer with 10 units and a softmax activation function.
