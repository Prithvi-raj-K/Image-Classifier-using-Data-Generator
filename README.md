# Image-Classifer-using-Data-Generator: Project Overview
* Created a image classifer from scratch using Keras Package
* Used Convolutional Neural Network to classify the image
* ImageDataGenerator is used to augument the images
* Used Keras Hyperband to find the best Hyperparameters for the CNN Model

# Requirements
Python Version: 3.8.X
Packages used: os,numpy,pandas,keras,matplotlib

# Model Building
I have tried to create the model in 3 stages.
1. Base Model with only image generators from keras package without data augumentation.
2. Base Model performance when Data Augumentation is used.
3. Improving model performance with hyperparameter tuning.

Further, in the thrird part of my model buiding, I have used Hyperband which is a keras tuner used to automate the hyperparameter tuning. I have used this as it works perferctly with imagedatagenerator.

# Model Performance
* Based Model --- Validation accuracy: 90%
* Model with Data Augumentation-- Accuracy:89%
* Hyperparameter tuned Model --89%

As I worked with a small dataset, there is not much change in the model performance. 
