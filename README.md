# Handwritten Digits Recognition
Implemented a Neural Network from scratch to recognize handwritten digits of the MNIST dataset.

In this project I used MNIST dataset to recognize the handwriten digits using neural networks and stochastic gradient descent algorithm by python from scratch. 
First I made weight and biases randomly, then using SGD computed their gradients in different batches and continued the algorithm for every epoch. At the end I Ploted the cost function for each epoch. Costs are obviously descending and accuracy of model on the train and test sets are almost 90%. After that I shifted the test set four pixels and computed the accuracy again, in this case accuracy is less than 30%. 
I tried this with different activation functions and different types of gradient descent, almost for every situation the accuracy is about 90%.
