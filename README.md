# Handwritten Digit Recognition using Neural Networks

This repository contains Python code for building and evaluating neural network models on the MNIST dataset for handwritten digit recognition.

## Description

The code includes the implementation of three neural network models:

1. Neural Network with One Layer:
   - Architecture: Input layer (784 nodes) -> Dense layer with sigmoid activation (10 nodes)
   - Evaluation: Achieved an accuracy of 97.51% on the MNIST test dataset.

2. Neural Network with Two Layers:
   - Architecture: Input layer (784 nodes) -> Dense layer with ReLU activation (100 nodes) -> Dense layer with sigmoid activation (10 nodes)
   - Evaluation: Achieved an accuracy of 97.67% on the MNIST test dataset.

3. Convolutional Neural Network (CNN):
   - Architecture: Conv2D layer with ReLU activation -> MaxPooling2D layer -> Conv2D layer with ReLU activation -> MaxPooling2D layer -> Flatten layer -> Dense layer with ReLU activation (64 nodes) -> Dense layer with softmax activation (10 nodes)
   - Evaluation: Achieved an accuracy of 99.09% on the MNIST test dataset.

## Usage

1. Install the required dependencies by running `pip install tensorflow matplotlib numpy`.

2. Run the code in a Jupyter notebook or Python environment.

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits (0-9). The images are grayscale and have a resolution of 28x28 pixels.

