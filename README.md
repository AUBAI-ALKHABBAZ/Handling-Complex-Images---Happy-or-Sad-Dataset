# Handling-Complex-Images-Happy-or-Sad-Dataset
Coursera-Introduction to TensorFlow for Artificial Intelligence Machine Learning and Deep Learning - week4
In this assignment you will be using the happy or sad dataset, which contains 80 images of emoji-like
faces, 40 happy and 40 sad.
Create a convolutional neural network that trains to 99.9% accuracy on these images, which cancels
training upon hitting this training accuracy threshold.
Some helpful tips in case you are stuck:
- A good first layer would be a Conv2D layer with an input shape that
matches
that of every image in the training set (including the color dimension)
- The model will work best with 3 convolutional layers
- There should be a Flatten layer in between convolutional and dense layers
- The final layer should be a Dense layer with the number of units and
activation function that supports binary classification.
