## MNIST and CIFAR-10 Image Classification

This repository contains two separate notebooks for image classification tasks using the MNIST and CIFAR-10 datasets. These notebooks leverage PyTorch to implement Convolutional Neural Networks (CNNs) for accurate classification of images.

Project Overview
- MNIST-ImageClassification.ipynb: This notebook focuses on the classification of handwritten digits using the MNIST dataset. It walks through building a CNN model and training it to recognize digits (0-9) from grayscale images of size 28x28.

- CIFAR10-ImageClassification.ipynb: This notebook focuses on classifying images from the CIFAR-10 dataset, which contains 32x32 colored images across 10 classes (airplanes, cars, birds, etc.). A more complex CNN architecture is used due to the complexity and diversity of the images.

# Datasets
1. MNIST Dataset:
- Description: 70,000 images of handwritten digits (0-9), with 60,000 images for training and 10,000 images for testing.
- Image Size: 28x28 pixels, grayscale.
- Number of Classes: 10 (digits 0-9).

3. CIFAR-10 Dataset:
- Description: A dataset containing 60,000 32x32 color images in 10 classes, with 50,000 for training and 10,000 for testing.
- Image Size: 32x32 pixels, RGB color images.
- Number of Classes: 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).

# Key Features
- Deep Learning Framework: Both notebooks use PyTorch to build, train, and evaluate Convolutional Neural Networks (CNNs).
- CNN Architecture: The notebooks demonstrate the use of convolutional layers, pooling layers, and fully connected layers to extract features from images and classify them.
- Data Preprocessing: Images are normalized and transformed to improve model performance.
- Training and Evaluation: Both models are trained using cross-entropy loss and optimized with Adam optimizer.

## Installation
1. Clone the repository:
'''
git clone https://github.com/haikalthrq/MNIST-CIFAR10-Image-Classifier.git
