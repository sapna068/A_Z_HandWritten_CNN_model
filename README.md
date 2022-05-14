# A_Z_HandWritten_CNN_model
Building a CNN model for A_Z_Handwritten_Data

Problem Statement: Building a CNN model for A_Z_Handwritten_Data and analyse model performance

Dataset: A_Z_Hadwritten_Data.csv

This project aims to develop a  module for predicting alphabets. 
The csv file consists of the pixels for alphabets. While analysing the dataset it was found that the csv 0th column consists of the labels(0-25) representing letters from A-Z . A cnn model has been build to train the dataset as there were multiclass classification of images is there and evaluate model accuracy and performance using confusion matrix. 

About CNN model: Convolution Neural Network
Convolution layer: a filter passes over input image, scanning the pixels ans create a feature map
pooling layer: resduces no of pixelsa using max pooling so that we can retain the strongest pixels while ignoring weaker one
flattening:output from previous layer are flattened to single vector to paas to nect input level:
Activation Function (ReLU and Softmax)
After each convolutional and max pooling operation, we can apply Rectified Linear Unit (ReLU). Softmax assigns decimal probabilities to each class in a multi-class problem. Those decimal probabilities must add up to 1

Steps  to run the notebook:
 a)cmd-->jupyter notebook, new-->pyhton3
 a)all the required libraries and versions are attached to requirements.txt , install all those with pip install
 b)load the data set to jupyter notebook with name A_Z_Hadwritten_Data.csv
 c)after data split , the train  test data and label will be there in jupyternotebook only
 d)All the preprocessing and building cnn model has been done in A_Z_Hadwritten_CNN ipynb file

 
