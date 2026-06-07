# Convolutional Neural Network
# CIFAR-10 Image Classification using CNN

## 📌 Project Overview
This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using TensorFlow (Keras).

The model is trained to classify 32x32 RGB images into 10 different categories.

## 📂 Dataset
CIFAR-10 dataset:
- 60,000 color images
- 10 classes
- 50,000 training images
- 10,000 test images
- Image size: 32x32x3

Dataset is loaded using:
```python
from tensorflow.keras.datasets import cifar10
