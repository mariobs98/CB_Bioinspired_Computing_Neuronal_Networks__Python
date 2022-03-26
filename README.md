# CB_Bioinspired_Computing__Python

*It's a Jupyter Notebook project, so the code was write and the file for its execution its from there.
*We're going to have 3 proyect: 
First one the Multilayer Percepton Proyect. 
Second one ANN with KERAS.
Third one Convolutional Neuronal Network.

PROJECT 1----:
Find 2 simple datasets that have categories as output

1.normalize the input data and the desired output (float and categorical)
2.Make various network topologies suitable to input and output,
3.Train the network a number of epochs and view the results of the loss and precision rating for each model performance.

Remember that it is better to start with a small network and increase its complexity.
The number of epochs and learning rate have a lot to do with training.

In the implementation of MLP, the impulse is not considered as a factor for optimizing the descending gradient.
Modify the learning algorithm so that it uses the momentum parameter.
Using the sklearm library. from sklearn.neural_network import MLPClassifier
Do one of the two examples above.


PROJECT 2----:
As in the previous session, find 2 datasets, one with YES/NO output and the other with categorical output, and implement them in Keras.

Data loading and normalization

Network design (make various network models) from the smallest to the most complex.

Adjustment of each network

Evaluation of the results obtained commenting on how you think it will behave.

You must make several designs for each one. It is not about adjusting it to 99% but about evaluating the data indicating its possible problems.


PROJECT 3----:
It used the CIFAR10 dataset, with which we have 60,000 images, 50,000 training images and 10,000 test images.

More information- https://www.cs.toronto.edu/~kriz/cifar.html

Basically I try to train the convolutional network for recognition and classification
of 10 types of different categories among all the images.

As you can see, he tried several models (including some that he deleted, before doing the data augmentation),
and the best result that has been obtained is in the one that I leave as "model 1", with an Accuracy: 76.58% in test one and
Accuracy: 77.46% in test two. Executing the first one with a learning rate of 0.01 and 10 epochs, and in the second case, 0.001
and 30 times.

As you can see in the code, different types of data augmentation are also used, along with cross-layer dropout.
that is requested in the delivery task.

