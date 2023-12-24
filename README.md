# Fashion-MNIST CNN Classifier

##  Overview
This repository contains the implementation of a Convolutional Neural Network (CNN) for classifying images from the Fashion-MNIST dataset. The model is built using TensorFlow and Keras, utilizing the Adam optimizer with softmax activation for multiclass classification.

##  Dataset
Fashion-MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image belonging to one of 10 classes.

## Model Architecture
The CNN model architecture includes convolutional layers, max-pooling layers, and dense layers. The model is trained to recognize and classify various fashion items such as T-shirts, trousers, and more.

## Training
The model is trained using the Adam optimizer and employs early stopping to prevent overfitting. Training stops at the 23rd epoch, achieving a training accuracy of 99.38%.

## Evaluation
After training, the model is evaluated on a separate test set, achieving a test accuracy of 91.6%. This indicates the model's ability to generalize well to unseen data.

## Usage
You can use this model to classify Fashion-MNIST images by following the instructions in the provided Jupyter Notebook. Ensure that you have the required dependencies installed.

# Dependencies
TensorFlow, 
Keras,
Other dependencies
