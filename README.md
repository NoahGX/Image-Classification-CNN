# Image Classification: Convolutional Neural Networks

## Overview
The purpose of this Jupyter notebook is to implement a Convolutional Neural Network (ConvNet) model using PyTorch, specifically tailored for image classification tasks. It is designed to work with the FashionMNIST dataset.

## Features
- **Model Design:** The notebook includes a detailed definition and implementation of a ConvNet model comprising multiple convolutional, ReLU activation, batch normalization, max pooling, and fully connected layers.
- **Data Handling:** Code snippets for loading and examining the FashionMNIST dataset.
- **Training and Evaluation:** Instructions and code for training the model and evaluating its performance.

## Usage
Run each cell sequentially to load the dataset, define the model, and train the model on the dataset.

## Prerequisites 
- Python 3.x
- Libraries such as `pytorch`, `torchvision` (latest versions)

## Input
The input to the model is the FashionMNIST dataset, which includes images of various clothing items, formatted as 28x28 grayscale images.

## Output
The output of the notebook is a trained ConvNet model capable of classifying images into one of the ten classes of the FashionMNIST dataset. The expected accuracy should be above 80% on the test set.

## Notes
- Adjust batch sizes and the number of epochs depending on the computational resources available.
- Ensure the `download` parameter in the data loader is properly in order to fetch the dataset.