# tensorflow

In this repository you will find to versions of a simple network to work with the
MNIST database.

The first version (mnist_softmax.py) is the simplest. It can be found on 
https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/mnist/mnist_softmax.py.
In order to understand whats happening follow the guideline https://www.tensorflow.org/get_started/mnist/beginners
The expected accuracy of this version is about 92%. 

The second version (mnist_convolutional.py) is much more complicated, with hidden layer in a convolutional model. 
It has been built following the instructions found in https://www.tensorflow.org/get_started/mnist/pros.
Its accuracy is much higher than previous, about 99.2%.

All you need to run this program is python 3.5 with Tensorflow installed.
You can find the instruction for installing tensorflow in https://www.tensorflow.org/install/

The first version of the program will run in a few second, whereas the second long for about half
an hour, depending on your processor.

Feel free to play with the hyperparameters. For example use 1000 iterations instead of 20000 in the convolutional example
to see how much the accuracy is affected. In machine learning accuracy vs performance is a key aspect ;)

I hope you enjoy. 

All the credits go to the Google Tensorflow guys for their wonderful machine learning platform. I have only followed
their instructions.

You can email me at javier.unix@gmail.com

Greetings from Spain.

Javier.