# Image-classification-Using-Neural-Network

## The Purpose
- Make a model to predict the numbers from 1 to 9 from the hands moving.
- Compare between:- different models - CNN and regular NN in Image Classification

## The Dataset 
'Turkey Ankara Ayranci Anadolu High School's Sign Language Digits' 

## Data Source 
https://github.com/ardamavi/Sign-Language-Digits-Dataset

## What I Did

### Split your data into 2 parts: 
- Training (80%).
- testing(20%).

### Train using normalized gray images
#### Do preprocessing steps (Normalization):
- Convert each image to gray
- Divide each image by 255
#### Build 2 different Neural Network architectures that can detect the digit of a given image (change number of hidden layer, number of neurons in each hidden layer).
#### Apply cross-validation during training.

### Train using normalized RGB image
#### Do preprocessing steps (Normalization):
- calculate the average for all images,
- subtract this averages from each image.
- Divide each image by 255
#### Build a convolutional neural network model that can detect the digit of a given image (change number of conv layer , pooling layers).
