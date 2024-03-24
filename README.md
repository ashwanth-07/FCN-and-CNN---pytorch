# ResNet-14 CIFAR-10 Classification

## Introduction

This project is an implementation of ResNet-14 for image classification on the CIFAR-10 dataset. ResNet, or Residual Network, is a convolutional neural network (CNN) architecture which allows for the training of much deeper networks by utilizing residual connection to jump over some layers.

## Dataset

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

## Model

The model used in this project is ResNet-14, a variant of the original ResNet model, which has 14 layers. The architecture is designed to solve the problem of vanishing gradients and allows for the training of much deeper networks.

## Requirements

- Python 3.6+
- PyTorch 1.0+
- torchvision
- Numpy
- Matplotlib


## Results

ResNet-14 model achieved a classification accuracy of 83.54% on the CIFAR-10 test set.
