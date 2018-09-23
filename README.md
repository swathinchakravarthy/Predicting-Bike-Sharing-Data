# Predicting-Bike-Sharing-Data-NeuralNets

This project focussed on building a neural network to predict bike sharing rides. This project was a part of the Udacity Nanodegree program. 

# Description

A neural network was built from scratch using numpy library. Forward pass, back propagation and gradient descent implementations were the main focus. 

# Results

The goal of the project was to meet the following specifications:
* The sigmoid activation function is implemented correctly
* The forward pass is correctly implemented for the network's training.
* The run method correctly produces the desired regression output for the neural network.
* The network correctly implements the backward pass for each batch, correctly updating the weight change.
* Updates to both the input-to-hidden and hidden-to-output weights are implemented correctly.
* The number of epochs is chosen such the network is trained well enough to accurately make predictions but is not overfitting          to the training data.
* The number of hidden units is chosen such that the network is able to accurately predict the number of bike riders, is able to generalize, and is not overfitting.
* The learning rate is chosen such that the network successfully converges, but is still time efficient.
* The number of output nodes is properly selected to solve the desired problem.
* The training loss is below 0.09 and the validation loss is below 0.18.

# Additional Remarks

The model predicts data quite accurately. The bias however stems from the insufficient availability of data during the holiday week of the month.
