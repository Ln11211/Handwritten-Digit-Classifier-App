# Handwritten-Digit-Classifier-App
This Kotlin app's primary purpose is to recognize the handwritten digits. The digits are drawn on a blackboard provided in the app.

![8](https://user-images.githubusercontent.com/91385411/222761335-26b95adb-78c7-4b0e-8eef-267887c85b5e.gif)

A Convolution Neural Netwrok is used to make inferences. The CNN is trained on the MNIST dataset and the model can predict only single digit.

This app is an experiment to optimize the TensorFlow model using the TennsorFlow optimizer and to realize the optimized model using the Kotlin libray.


https://user-images.githubusercontent.com/91385411/222759860-80e41218-90af-408d-a6bd-4529fd0eb589.mp4


The un-optimized CNN model has about 307K parameters.
The model architecture is simple.

It has 4 Conv2D layers with three 128 filters and two 64 filters.
There are intermediate maxpooling,dropout and batchNormalization layer among the Conv2D layers.

It also has 4 Dense layers.

The activation function for all layers is the "ReLU" function and the loss used is the Sparse Categorical Cross Entropy fuinction.
