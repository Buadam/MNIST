# MNIST digit recognition
## Description
This repository contains my solutions to the MNIST digit recognition task via Kaggle. I start from a basic Linear Regression model, advancing towards a simple CNN through a Deep fully connected NN as a middle step. 

## Files
MNIST digit recognition CNN.ipynb : this notebook contains my final submission using a simple CNN architecture, built in Keras. Data augmentation is applied using keras.preprocessing.image.ImageDataGenerator

MNIST digit recognition.ipynb: this notebook contains the previous models (Linear Regression, Deep FC NN), tracing the improvement of the accuracy as the model gets more and more complicated. 

Test CNNs trained on MNIST.ipynb: this code displays the activations of the neurons in each layer for a given input image. The code is based on Gabriel Pierobon's tutorial: https://github.com/gabrielpierobon/cnnshapes.

## Scoring:
Cross-validation accuracy (without any image augmentation and hyperparameter tuning):

LR model: 91.9%
NN with 2 hidden layers: 95.6%
CNN: 99.2%

Cross-validation accuracy (with image augmentation and hyperparameter tuning):

CNN: 99.25%

Public score (Test accuracy): CNN with image augmentation: 99.4%

Ranking: 649.
