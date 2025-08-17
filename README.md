# MNIST Neural Network (NumPy)

Implementation of a feedforward neural network trained on the MNIST dataset using only NumPy.

## Architecture
- [784 → 25 → 15 → 10]
- ReLU activations (hidden layers), Softmax (output)

## Features
- Inverted Dropout
- L2 Regularization
- Mini-batch Gradient Descent
- Adam Optimizer
- Batch-Norm
- Gradient Checking

## Performance
- Training Accuracy: **98.56166666666667%**
- Test Accuracy: **97.46000000000001%**

## Dataset
MNIST (28×28 grayscale digits)