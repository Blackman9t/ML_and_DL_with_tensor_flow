# ML_and_DL_with_tensor_flow
Using The popular tensor_flow library for Machine Learning and Deep Learning Projects

The first thing we need to know is that Deep Learning is about Neural Networks
The structure of a NN is like any network. But a NN is a highly structured network, made up of an input layer, one or more hidden layers and an output layer.
A Neural Network can be viewed as the result of spinning classifiers together in a layered web.
This is because each node in the hidden and output layer has it's own classifier.

Forward Propagation:
This refers to the series of events as the input layer feeds the first hidden layer, which feeds the next, up to the output layer.
Forward prop is the NN way of classifying a set of inputs

A Little History
The first Neural Nets were born out of the need to address the inaccuracy of an earlier classifier, the Perceptron.
It was shown that by using a layered web of Perceptrons, the accuracy of predictions could be improved.
As a result, this new breed of neural nets was called a Multi-Layer Perceptron or MLP. Since then, the nodes inside neural nets have replaced perceptrons with more powerful classifiers, but the name MLP has stuck.
Each edge has a unique weight, and each node has a unique bias.
This means that the combination used for each activation is also unique, which explains why the nodes fire differently.
You may have guessed that the prediction accuracy of a neural net depends on its weights and biases. We want that accuracy to be high, meaning we want the neural net to predict a value that is as close to the actual output as possible, every single time.
The process of improving a neural net’s accuracy is called training, just like with other machine learning methods.
Here's that forward prop again - to train the net, the output from forward prop is compared to the output that is known to be correct, and the cost is the difference of the two.
The point of training is to make that cost as small as possible, across millions of training examples. To do this, the net tweaks the weights and biases step by step until the prediction closely matches the correct output.
Once trained well, a neural net has the potential to make accurate predictions each time.
