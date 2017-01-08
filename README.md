# Learning to Recognise Multiple Digits in Real-World Images with Convolutional Neural Networks

This project explores how Convolutional Neural Networks (ConvNets) can be used to identify series of digits in natural images taken from The Street View House Numbers (SVHN) dataset

## Programming language and packages

All the code in this project has been written using Python 2.7 and the ConvNets have been implemented using TensorFlow.

## What is contained in this repository?

1. ```01-svhn-single-preprocessing.ipynb```: contains code for pre-processing the SVHN 32-by-32 images
2. ```02-svhn-single-model.ipynb``: contains code for implementing a simple ConvNet for recognising single digits in the SVHN 32-by-32 images using TensorFlow
3. ```03-mnist-synthetic-dataset.ipynb```: contains code for creating a simplistic synthetic dataset of images with multiple digits created from the MNIST dataset
4. ```04-mnist-synthetic-model.ipynb```: contains code for implementing a ConvNet for recognising multiple digits in the synthetic MNIST dataset using TensorFlow
5. ```05-svhn-multi-preprocessing.ipynb```: contains code for pre-processing the original SVHN images
6. ```06-svhn-multi-model.ipynb```: contains code for implementing a ConvNet for recognising multiple digits from the original SVHN dataset using TensorFlow and TensorBoard.

## Resources

* [The Street View House Numbers (SVHN) Dataset](http://ufldl.stanford.edu/housenumbers/)
* [Multi-digit Number Recognition from Street View Imagery using Deep Convolutional Neural Networks](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/42241.pdf)
