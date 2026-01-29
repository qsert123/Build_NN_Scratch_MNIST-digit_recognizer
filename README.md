# Build_NN_Scratch_MNIST-digit_recognizer
Neural Network built from scratch using NumPy to classify Sign Language MNIST images with manual forward and backward propagation.

# Overview

This project implements a fully connected neural network from scratch using pure Python and NumPy to classify hand sign images from the Sign Language MNIST dataset.
No deep learning frameworks (TensorFlow / PyTorch / Keras) are used — all core neural network operations are manually implemented.

The project demonstrates a complete end-to-end pipeline including forward propagation, backpropagation, softmax classification, gradient descent training, and prediction visualization.

# Objective

To understand and implement the internal mechanics of neural networks at a mathematical and vectorized level using only NumPy.

# Model Architecture
Input Layer:   784 neurons 
Hidden Layer:  Dense layer + ReLU activation
Output Layer:  Softmax classifier (multi-class hand sign labels)

# Implemented Components

Parameter initialization
        |
Forward propagation
        |
ReLU activation function
        |
Numerically stable Softmax
        |
One-hot encoding with class gap handling
        |
Backpropagation (manual gradients)
        |
Vectorized gradient computation
        |
Gradient descent optimization
        |
Accuracy tracking during training
        |
Image prediction visualization

# Dataset : https://www.kaggle.com/competitions/digit-recognizer/data

# 📊 Training Output

During training, the model prints:

iteration number : 500
training accuracy : 0.89
