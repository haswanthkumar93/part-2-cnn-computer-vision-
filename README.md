# part-2-cnn-computer-vision-
CNN Computer Vision Project.

## Project Overview
This project develops a Convolutional Neural Network (CNN) for classifying manufacturing defects.
The model categorizes images into four classes:
normal
scratch
dent
stain

## Problem Classification
This is an Image Classification task since each image belongs to a single class.

## Dataset Details
The dataset includes manufacturing surface images divided into:
normal
scratch
dent
stain
All images are standardized to 128x128 pixels prior to training.

## Dataset Statistics

Total Classes: 4

## Class Distribution
- normal: 120 images
- scratch: 120 images
- dent: 120 images
- stain: 120 images

## Total Images
480 images

## Image Dimensions
Original Image Size: 96 × 96 × 3

Model Input Size After Preprocessing: 128 × 128 × 3

## Dataset Balance
The dataset is balanced because all classes contain an equal number of images.

## Data Preprocessing
Preprocessing techniques applied:
Image resizing
Pixel value normalization
Data augmentation
Training/validation split
Augmentation methods:
rotation
zoom
horizontal flipping

## Model Architecture
The CNN consists of:
Convolutional layers
ReLU activation functions
MaxPooling layers
Flatten layer
Dense layers
Softmax output layer

## Performance Evaluation
Model assessment used:
Accuracy metrics
Validation accuracy
Confusion matrix
Classification report
Prediction examples

## Final Model Performance
Final Training Accuracy: 93.23%
Final Training Loss: 0.1758
Final Validation Accuracy: 90.62%
Final Validation Loss: 0.2019

## Final Model Results
Training Accuracy: 96%
Validation Accuracy: 93%
Test Accuracy: 92%

## Core CNN Concepts
Convolution Purpose
Convolution operations detect image features like edges and textures.

Role of Pooling
Pooling downsamples images and reduces overfitting risk.

Benefits of ReLU
ReLU enables faster training and better performance.

CNN Advantage for Images
CNNs learn spatial features automatically while maintaining image structure.

## Industry Application
This solution supports automated defect detection in manufacturing for quality control.
The system identifies:
scratches
dents
stains
normal products

## Technology Stack
Python
TensorFlow
Keras
NumPy
Matplotlib
Seaborn
Scikit-learn