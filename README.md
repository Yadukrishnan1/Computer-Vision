# Fashion MNIST using TensorFlow Keras

Using the 'Fashion' dataset available from MNIST, a deep neural network is employed to classify 'previously unseen' images of a clothing artifact to its correct category, for example T-shirt, shorts, shoes, etc. A deep NN with 128, 256, 512, and 1024 input layers are employed first, the accuracy of the test is plotted as a function of the layer numbers.

Later, convolutional network is used with pooling to compress the images to improve performance. Playing around with the number of input layers/convolutional layers give us a general idea about how a (C)NN works, and how the loss and accuracy of the classification process gets affected. 

*The 'callback' function shown is adopted from L. Maroney's Coursera course, and credited.
