# Summary

- DL is considered as a subfield of machine learning, most of the time It is used for image recognition.
- Most of neural networks are fully connected (meaning, each node of the layer n is connected to all the nodes of the layer n+1).
- We can divide the layers into three important parts, the input layer, the hidden layers (where the magic happens) and the output layer.
- Each neuron is represented by a number, and each connection has a weight, which is also just a number.
- When building a neural network, we can distibguish two phases:
  1.  Learning (forward phase).
  2.  Feedback (backward phase) - where the weights will get updated.
- Loss function (expected - predicted)^2.
- Our goal is to minimize this loss function as much as possible, and get the most optimal weights.
- Obviously the loss function is "à plusieurs variables w1, w2, w3 etc"
- Each time we do a Learning phase, we do also a Feedback phase.
- There's something called "Overfitting", basically, It happens when a model learns the detail in the training data to the extent that it negatively impacts the performance of the model on new data.

All credits go to Mohamed Nassim Aliousalah
