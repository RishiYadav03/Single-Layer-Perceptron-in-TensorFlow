# Single-Layer-Perceptron-in-TensorFlow

 Neural Networks work in the same way that our biological neuron works.
 
![Biological-Neuron-and-similarity-with-neural-network](https://github.com/user-attachments/assets/db767c7b-31a1-430b-8bb5-3414f033f8f4)

Biological neuron has three basic functionality 

->Receive signal from outside.

->Process the signal and enhance whether we need to send information or not.

->Communicate the signal to the target cell which can be another neuron or gland.

In the same way, neural networks also work.

![nodeNeural (1)](https://github.com/user-attachments/assets/2ea6193c-bd9d-4d8c-86bd-b842f45837fe)

What is Single Layer Perceptron?

It is one of the oldest and first introduced neural networks. It was proposed by Frank Rosenblatt in 1958. Perceptron is also known as an artificial neural network. Perceptron is mainly used to compute the logical gate like AND, OR, and NOR which has binary input and binary output.

The main functionality of the perceptron is:-

->Takes input from the input layer

->Weight them up and sum it up.

->Pass the sum to the nonlinear function to produce the output.

![Single-Layer-Perceptron](https://github.com/user-attachments/assets/9b73dc79-3440-48b9-a5ac-d639385be10c)

Here activation functions can be anything like sigmoid, tanh, relu Based on the requirement we will be choosing the most appropriate nonlinear activation function to produce the better result. Now let us implement a single-layer perceptron.

# IMPLEMENTATION OF SINGLE-LAYER PERCEPTRON

Let us now implement a single-layer perceptron using the “MNIST” dataset using the TensorFlow library.

Step1: Import necessary libraries

o Numpy – Numpy arrays are very fast and can perform large computations in a very short time.

o Matplotlib – This library is used to draw visualizations.

o TensorFlow – This is an open-source library that is used for Machine Learning and Artificial intelligence and provides a range of functions to achieve complex functionalities with single lines of code.

Step 2: Now load the dataset using “Keras” from the imported version of tensor flow.

Step 3: Now display the shape and image of the single image in the dataset. The image size contains a 28*28 matrix and length of the training set is 60,000 and the testing 
        set is 10,000.

Step 4: Now normalize the dataset in order to compute the calculations in a fast and accurate manner.

Step 5: Building a neural network with single-layer perception. Here we can observe as the model is a single-layer perceptron that only contains one input layer and one 
        output layer there is no presence of the hidden layers.  

Step 6: Output the accuracy of the model on the testing data.
