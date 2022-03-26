# CB_Bioinspired_Computing__Python

*It's a Jupyter Notebook project, so the code was write and the file for its execution its from there. I also leave a raw txt file with the code.*


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
