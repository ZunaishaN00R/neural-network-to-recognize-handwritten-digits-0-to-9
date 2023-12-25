# neural-network-to-recognize-handwritten-digits-0-to-9
Build a neural network to recognize handwritten digits (0 to 9) from the MNIST dataset using a deep learning framework like TensorFlow
# Handwritten Digit REcognition using MNIST Dataset
# Overview
This repository contains a neural network implemented in TensorFlow and Keras to recognize handwritten digits (0 to 9) from the MNIST dataset. The model is designed to achieve high accuracy through experimentation with various architectures and activation functions.

# Mnist Dataset
The MNIST dataset, a collection of 28x28 grayscale images of handwritten digits, is used for training and testing. It is loaded using the TensorFlow Keras API.

# Model Architecture
The neural network comprises a sequence of layers, including a Flatten layer to convert 28x28 images into a flat vector. Experimentation involves adding different architectures, including dense layers with varying neuron counts and activation functions like ReLU. The model is finalized with a Dense layer using the softmax activation function for the output layer.

# Training and Evaulation
The model is trained on the training set for 10 epochs, utilizing the Adam optimizer and sparse categorical crossentropy loss. Training and validation accuracy are monitored during the process. The model is then evaluated on the testing set, yielding a high accuracy of 97.71%.

# Visualization and Predictions
To showcase the model's performance, a visualization of predictions on random test samples is included. The images, along with their corresponding predictions, are displayed to demonstrate the model's ability to accurately classify handwritten digits.

# Conclusion
This project provides a comprehensive example of building and training a neural network for handwritten digit recognition using the MNIST dataset. The achieved accuracy of 97.71% demonstrates the effectiveness of the model. Further experimentation with architectures and hyperparameters may lead to even higher accuracy.
