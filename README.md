# <div align="center">Driver Phone Detection Using Convolutional Neural Networks (CNN)</div>

## Project Overview

This project employs Convolutional Neural Networks (CNNs) to identify whether a driver is using their phone while driving based on images captured from a camera. The goal is to develop a model capable of distinguishing between drivers who are using their phones and those who are not.

## Dataset

The dataset is too large to include in this repository. You can download it from [Google Drive](https://drive.google.com/file/d/1FLtZKu_L1a5-f8fM6587q6BwBIC7aRl2/view?usp=sharing)


The dataset used for this project consists of 6,000 images, categorized into two classes:

- Phone Use: 3,000 images where the driver is using their phone (labeled as 1).
- No Phone Use: 3,000 images where the driver is not using their phone (labeled as 0).

The dataset is balanced, providing equal representation of both classes to train a robust and unbiased model.


## Model Architecture

The CNN model architecture used in this project is designed to effectively capture features from the images and classify them into the two categories (phone use or no phone use). The architecture includes several convolutional layers, pooling layers, and fully connected layers, which are optimized through training.

## Model Performance

The Convolutional Neural Network (CNN) was evaluated on training, validation, and test datasets. Here are the key performance metrics:

### Training Results
  - Training Accuracy: 99.53%
  - Training Loss: 0.0127

### Validation Results
  - Validation Accuracy: 97.71%
  - Validation Loss: 0.0755
  
### Test Results
  - Test Accuracy: 98.00%
