# Painters Identification project
The theme of the project was to train the neural network for recognizing paintings artist. The goal was to achieve recognition accuracy of more than 50 percent<p/>
A convolutional neural network, which is effectively used for the problem of recognizing objects in images, was chosen to solve the problem.

## First try 
A trial attempt was made with a simple convolutional network consisting of two convolutional, two pooling and one fully connected layers.<p/>
__Maximum accuracy obtained in this way - 34%__

## Second try
A second attempt was made with a network Resnet50 - convolutional neural network consisting of 50 layers with preloaded ImageNet weights.
__Maximum accuracy obtained in this way - 64%__

## Technologies used:
* Python 3.6.9
* TensorFlow 2.2.0
* Keras 2.4.3
* NumPy 1.18
