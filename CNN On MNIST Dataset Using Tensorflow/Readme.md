# CNN On MNIST Dataset Using Tensorflow #

1. The images are of the size 28*28. (i.e. 784 pixels)
2. Number of channels in the input layer were 1 because we wanted to consider each image separately.
3. Number of units in the first convolution layer were 32. The stride size was 1 and the window size was 5*5.
4. Number of units in the second convolution layer were 16. The stride size was 1 and the window size was 5*5.
5. The pooling window size in both pooling layers was 5*5.
6. The number of units in the hidden layer was 1024.
7. Because the output classes was 10. So number of unis in the output layer was 10.
8. Initialised random weights and biases using a normal distribution with mean = 0 and variance = 1.
9. Wrote functions for convulation and pooling layer.
10. Wrote the main cnn function using convulation and pooling functions.
11. Wrote a cost function which computes cross entropy after applying softmax function.
12. Used Adam Optimizer with a learning rate = 0.01.
13. Applied batch gradient descent with a batch_size of 100.Looped this 25 times to get to optimal weights.
14. Evaluated results

## Dataset Characteristics ##

The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems. The MNIST database contains 60,000 training images and 10,000 testing images. Half of the training set and half of the test set were taken from NIST's training dataset, while the other half of the training set and the other half of the test set were taken from NIST's testing dataset.

### The accuracy achieved was 98.68%. ###
