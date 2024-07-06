# Drowsy Driver Detection using CNN and HAAR Cascade Classifier

This project implements a Drowsy Driver Detection system using shallow and deep learning techniques. 
First, a CNN classifier model is created, which classifies images into open or closed eyes. The hyperparameters
of the model are tuned using Keras-Tuner in order to find the configuration with the greatest accuracy.
Later, the HAAR Cascade Classifier is used to identify the region of interest in the images (face and both eyes).
Then the CNN model is used on the region where each eye is present and a prediction is made as to whether the
eye is open or not. Using this data, the driver is classified as drowsy or non-drowsy.

## Features
* Convolutional Neural Network
* Keras Tuner
* HAAR Cascade Classifier

## Requirements
* Numpy
* Pandas
* Matplotlib
* PIL
* cv2
* Glob
* Sklearn
* Tensorflow

## Dataset 
This project is developed using the Drowsiness Detection Dataset available on:
https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset
