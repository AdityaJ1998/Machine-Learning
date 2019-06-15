# Tensorflow on MNIST Dataset #

1. Neural network had 2 hidden layers with 256 units each. 
2. Initialised weights & biases using a random distribution with mean = 0 and variance = 1.
3. Wrote forward propogation code for these layers i.e. hidden_layer_1,hidden_layer_2 and output_layer.
4. The activation function used was relu. 
5. Wrote a cost function which computes cross entropy after applying softmax function.
6. Used Adam Optimizer with a learning rate = 0.01.
7. Applied batch gradient descent with a batch_size of 100.Looped this 25 times to get to optimal weights.
8. Evaluated results

## Dataset Characteristics ##
The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems.
The MNIST database contains 60,000 training images and 10,000 testing images. Half of the training set and half of the test set were taken from NIST's training dataset, while the other half of the training set and the other half of the test set were taken from NIST's testing dataset.

## The accuracy achieved was 96.31%. ##


