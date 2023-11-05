
# Digit Recognition using Convolutional Neural Networks (CNN)

![Digit Recognition](https://github.com/yusufM03/Detect-Digits-using-CNN/assets/119126205/18f326f0-b761-4e22-a8fd-b1327ccce229)

This repository contains a Convolutional Neural Network (CNN) model trained to recognize handwritten digit images. The model is capable of accurately classifying digits from 0 to 9. This project serves as a demonstration of implementing deep learning techniques for image classification tasks.

## Dataset

The model was trained on the popular MNIST dataset, which consists of 28x28 grayscale images of handwritten digits.

## Model Architecture

The CNN model architecture consists of the following layers:
Model Architecture:
-------------------
1. Conv2D layer with 32 filters, 5x5 kernel size, 'Same' padding, and 'relu' activation
2. Conv2D layer with 32 filters, 5x5 kernel size, 'Same' padding, and 'relu' activation
3. MaxPooling2D layer with 2x2 pool size
4. Dropout layer with a dropout rate of 0.25

5. Conv2D layer with 64 filters, 3x3 kernel size, 'Same' padding, and 'relu' activation
6. Conv2D layer with 64 filters, 3x3 kernel size, 'Same' padding, and 'relu' activation
7. MaxPooling2D layer with 2x2 pool size and 2x2 strides
8. Dropout layer with a dropout rate of 0.25

9. Flatten layer
10. Dense layer with 256 units and 'relu' activation
11. Dropout layer with a dropout rate of 0.5
12. Output layer with 10 units (for 10 digits) and 'softmax' activation

## Training

The model was trained using TensorFlow and Keras on a GPU-enabled machine. The training process involved 2 epochs and a batch size of 80. The model achieved an accuracy of [98]% on the validation dataset.
