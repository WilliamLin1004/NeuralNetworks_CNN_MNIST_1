# NeuralNetworks_CNN_MNIST_1
Applied CNN on MNIST digit recognition dataset.

## CNN
The basics of Convolutional Neural Networks were introduced during class. A Convolutional Neural Network consists of three main component, Convolution, Pooling, and a fully-connected neural network.

## Convolution
Given several kernels(filters), we're able to derive several feature maps. Feature map should come in squares with odd number of blocks per side, since the significance of the feature should be represented at the center of that frame.

## Pooling
Used for reduction of blocks per side. One of the most frequently used pooling is MaxPooling.

## Fully-Connected Network
After flattening the feature maps derived from convolutions and pooling, the array should be processed with a fully connected neural network. The number of nodes in the output layer is decided by the number of classes there is. A softmax function is usually applied to get a probability-like number.

## Keywords
* CNN
* Convolution
* Pooling
* Fully-Connected Network
