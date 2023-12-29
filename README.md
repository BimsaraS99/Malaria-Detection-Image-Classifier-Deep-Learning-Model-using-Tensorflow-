# Malaria-Detection-Image-Classifier-Deep-Learning-Model-using-Tensorflow-
Malaria Detection Model (TensorFlow) Detect malaria parasites in blood smear images using a CNN. 
Model architecture: Input ➔ Conv2D ➔ MaxPool ➔ BatchNorm ➔ Flatten ➔ Dense (ReLU) ➔ BatchNorm ➔ Dense (Sigmoid). Load the model and predict external images with the provided code snippet. (300/300)


Malaria Detection Model using TensorFlow
Overview
This repository contains a Malaria Detection Model built using TensorFlow. The model is designed to classify whether a given blood smear image contains malaria parasites or is uninfected. The architecture of the model is a Convolutional Neural Network (CNN) implemented with TensorFlow's Keras API.

Model Architecture
The CNN architecture consists of the following layers:

Input Layer: Accepts images of size (IM_SIZE, IM_SIZE, 3).
Convolutional Layer 1: 6 filters with a kernel size of 3x3, valid padding, and ReLU activation.
Max Pooling Layer: Pooling with a 2x2 window and strides of 2.
Batch Normalization: Normalizes the activations of the previous layer.
Convolutional Layer 2: 16 filters with a kernel size of 3x3, valid padding, and ReLU activation.
Batch Normalization: Normalizes the activations of the previous layer.
Max Pooling Layer: Pooling with a 2x2 window and strides of 2.
Flatten Layer: Flattens the output for input to the fully connected layers.
Dense Layer 1: 100 neurons with ReLU activation.
Batch Normalization: Normalizes the activations of the previous layer.
Dense Layer 2: 10 neurons with ReLU activation.
Batch Normalization: Normalizes the activations of the previous layer.
Output Layer: 1 neuron with a sigmoid activation for binary classification.
