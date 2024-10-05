# MNIST and CIFAR-10 Image Classification

This repository contains deep learning models for image classification tasks using the MNIST and CIFAR-10 datasets. These models are built using PyTorch and implement Convolutional Neural Networks (CNNs) to classify images with high accuracy.

## Overview

- **MNIST**: A dataset of handwritten digits (0-9) with 60,000 training samples and 10,000 test samples. The task is to classify the digits.
- **CIFAR-10**: A dataset of 60,000 32x32 color images across 10 classes, including airplanes, cars, birds, cats, and more.

This project explores different deep learning techniques and optimizations for accurate image classification on both datasets.

## Key Features

- **Deep CNN Architecture**: Multiple convolutional layers are used to extract hierarchical features from images.
- **Data Augmentation**: Random cropping, horizontal flipping, and normalization are applied to improve generalization.
- **Regularization**: Techniques like dropout and weight decay are used to reduce overfitting.
- **Learning Rate Scheduling**: The learning rate decreases over time to fine-tune the model performance.
- **Adam Optimizer**: Utilized for efficient training and convergence.

## Dataset Information

- **MNIST**: 10 classes of grayscale handwritten digit images of size 28x28.
- **CIFAR-10**: 10 classes of 32x32 color images across various objects (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).

## Requirements

Before running the code, make sure you have the necessary dependencies installed:

```bash
pip install -r requirements.txt
