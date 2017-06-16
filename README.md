# FirstNeuralNetwork
In this project, I built a neural network from scratch to carry out a prediction problem on a real dataset! 
By building a neural network from the ground up, now I have a much better understanding of gradient descent, 
backpropagation and other concepts of NN.

The data comes from the UCI Machine Learning Database.

============================================================================================================================================================  
Problem Statement : Neural Network for predicting Bike Sharing Rides. Here NN will predict how many bikes 
a company needs because if they have too few they are losing money from potential riders 
and if they have too many they are wasting money on bikes that are just sitting around. 
So NN will predict from the hisitorical data how many bikes they will need in the near future.

#Network Description# 
The network has two layers, a hidden layer and an output layer. The hidden layer 
uses the sigmoid function for activations. The output layer has only one node and is used for the regression, 
the output of the node is the same as the input of the node. That is, the activation function is f(x)=xf(x)=x . 
A function that takes the input signal and generates an output signal, but takes into account the threshold, i
s called an activation function. We work through each layer of our network calculating the outputs for each neuron. 
All of the outputs from one layer become inputs to the neurons on the next layer. This process is called forward propagation. 
We use the weights to propagate signals forward from the input to the output layers in a neural network. 
We use the weights to also propagate error backwards from the output back into the network to update our weights. 
This is called backpropagation.
============================================================================================================================================================  
