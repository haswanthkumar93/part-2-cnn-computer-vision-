# part-2-cnn-computer-vision-
CNN Computer Vision Project
Project Overview
This project develops a Convolutional Neural Network (CNN) for classifying manufacturing defects.

The model categorizes images into four classes:

normal

scratch

dent

stain

Problem Classification
This is an Image Classification task since each image belongs to a single class.

Dataset Details
The dataset includes manufacturing surface images divided into:

normal

scratch

dent

stain

All images are standardized to 128x128 pixels prior to training.

Data Preprocessing
Preprocessing techniques applied:

Image resizing

Pixel value normalization

Data augmentation

Training/validation split

Augmentation methods:

rotation

zoom

horizontal flipping

Model Architecture
The CNN consists of:

Convolutional layers

ReLU activation functions

MaxPooling layers

Flatten layer

Dense layers

Softmax output layer

Performance Evaluation
Model assessment used:

Accuracy metrics

Validation accuracy

Confusion matrix

Classification report

Prediction examples

Core CNN Concepts
Convolution Purpose
Convolution operations detect image features like edges and textures.

Role of Pooling
Pooling downsamples images and reduces overfitting risk.

Benefits of ReLU
ReLU enables faster training and better performance.

CNN Advantage for Images
CNNs learn spatial features automatically while maintaining image structure.

Industry Application
This solution supports automated defect detection in manufacturing for quality control.

The system identifies:

scratches

dents

stains

normal products

Technology Stack
Python

TensorFlow

Keras

NumPy

Matplotlib

Seaborn

Scikit-learn