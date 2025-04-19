# multiclass-classification-using-MNIST-dataset

This project implements a multiclass classification model using an Artificial Neural Network (ANN) to recognize handwritten digits (0–9) from the MNIST dataset. The ANN is trained from scratch using supervised learning techniques to classify 28x28 grayscale images into one of ten classes.

Model Architecture
Input layer: 784 neurons (28x28 pixels flattened)

Hidden layers: 1 or more fully connected layers with ReLU activation

Output layer: 10 neurons (Softmax for class probabilities)

Loss Function: Categorical Cross-Entropy (but here i have used sparse categorical cross entropy instead of simple categorical crossentropy because in sparse we dont need to do one hot encoding for our labels)

Optimizer: i have used adam optimizer(SGD, Adam — specify which one you used)

Project Overview

Dataset: MNIST

Task: Multiclass classification (10 classes)

Approach: ANN
