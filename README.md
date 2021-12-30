# MSE-CompVis-Assignment2

## Introduction
In this exercise, you should design and train a convolutional neural network to classify the pixels of an image into the different classes of the cityscape data set that is used for training autonomous driving.
Data Preparation
The whole data set is quite large, so a smaller portion of the data set (using just one city, Zurich, for the training, and another, Frankfurt, for the valiation ) has already been prepared and divided into smaller image patches of 256x256 patches. The test set will provided a bit later, when you got the training running already. 

## ConvNet Approaches
The task is to implement two different fully convolutional neural networks and train and validate them on the data:
For the first network, a relatively simple FCN should be used that only uses convolutional layers of stride 1, but no downsampling of the data. This is for testing the overall approach and that the training procedure has not errors. 
The second network should use a some form of downsampling and upsampling. Try to tune the network to get the best results and try different network architectures.
Conv nets approaches benefit a lot from gpus. If you don't have a gpu available, use more simple networks to get first results and also keep the networks for the second task smaller.

Use the train and validation data sets to tune your hyper parameters. This includes changing the number of layers or the sizes of the convolutional filters in the network.
Finally run the networks on the test data set to compare the performance

## Datasets
The data sets are available from https://drive.switch.ch/index.php/s/PfgmHsurnnsU36t

Please only use the dataset for the course. If you are interested in the complete data set, please register at https://www.cityscapes-dataset.com/
