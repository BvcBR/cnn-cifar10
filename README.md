# CIFAR-10 Image Classification with PyTorch

## Project Overview
This project aims to develop a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The goal is to accurately classify these images into one of 10 categories (airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, trucks).

## Objectives
- To implement and train a CNN using PyTorch.
- To understand and apply convolutional layers, batch normalization, pooling layers, and fully connected layers in practice.
- To experiment with different network architectures and hyperparameters to improve classification accuracy.
- To gain experience with handling image data and preparing it for model training.
- Use data Augmentation transformations to provide more data to the model without adding external data.
  
## Tools/Frameworks Used
- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Dataset:** CIFAR-10

## Model Architecture
The CNN model implemented in this project includes the following layers:
- Convolutional layers for feature extraction.
- Batch normalization to stabilize and accelerate the training process.
- ReLU activation functions to introduce non-linearity.
- MaxPooling layers for spatial downsampling.
- Fully connected layers for classification.

## Getting Started
### Prerequisites
Ensure you have Python installed on your system. This project uses Python 3.8. Additionally, you'll need PyTorch and other dependencies, which can be installed using the following command:
```
pip install torch
pip install torchvision
```

