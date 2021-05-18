# Face_Mask_Detection

## Problem Statement
To detect whether or not a person is wearing a face-mask by using Convolution Neural Networks and OpenCV

## Dataset
This dataset contains a data folder which contains 2 subdirectories namely

without_mask - which contains 686 images without mask.
with mask- which contains 690 images with masks.
The original dataset is prepared by Prajna Bhandary and available at Github

## Image Preprocessing
All the images are not of the same size and neural networks often expect images that are standardized a fixed size. Therefore, the following preprocessing steps are performed:

Gray scaling
Normalize
Resize
Reshape

## Model Building and Training :
Here a basic model is built using CNN and Keras library.
Model is first trained on both with and without masks images.
Then model is tested on sample test data. Whichever model is giving the good accuracy that model is saved for further use.

## Model Prediction
The following steps are performed here:

Loading the previously saved model(best model) from training phase.
Using webcam to generate test images and prediction is made.


