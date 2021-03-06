![Python 3.6](https://img.shields.io/badge/Python-3.6-blue.svg)

# Model Zoo

A collection of standalone TensorFlow models in Jupyter Notebooks

## Classifiers

- Perceptron [[TensorFlow](tensorflow_ipynb/perceptron.ipynb)] [[PyTorch](pytorch_ipynb/perceptron.ipynb)]
- Logistic Regression [[TensorFlow](tensorflow_ipynb/logistic-regression.ipynb)] [[PyTorch](pytorch_ipynb/logistic-regression.ipynb)]
- Softmax Regression (Multinomial Logistic Regression) [[TensorFlow](tensorflow_ipynb/softmax-regression.ipynb)]
- Multilayer Perceptron [[TensorFlow](tensorflow_ipynb/multilayer-perceptron.ipynb)]
- Multilayer Perceptron with Dropout [[TensorFlow](tensorflow_ipynb/multilayer-perceptron-dropout.ipynb)]
- Multilayer Perceptron with Batch Normalization [[TensorFlow](tensorflow_ipynb/multilayer-perceptron-batchnorm.ipynb)]
- Multilayer Perceptron with Backpropagation from Scratch [[TensorFlow](tensorflow_ipynb/multilayer-perceptron-lowlevel.ipynb)]
- Convolutional Neural Network [[TensorFlow](tensorflow_ipynb/convnet.ipynb)]
- Convolutional Neural Network VGG-16 [[TensorFlow](tensorflow_ipynb/convnet-vgg16.ipynb)]

## Metric Learning

- Siamese Network with Multilayer Perceptrons [[TensorFlow](tensorflow_ipynb/siamese-1.ipynb)]

## Autoencoders

- Autoencoder [[TensorFlow](tensorflow_ipynb/autoencoder.ipynb)]
- Convolutional Autoencoder with Deconvolutions [[TensorFlow](tensorflow_ipynb/autoencoder-deconv.ipynb)]
- Convolutional Autoencoder with Nearest-neighbor Interpolation [[TensorFlow](tensorflow_ipynb/autoencoder-conv.ipynb)]

## General Adversarial Networks

- General Adversarial Networks [[TensorFlow](tensorflow_ipynb/gan.ipynb)]
- Convolutional General Adversarial Networks [[TensorFlow](tensorflow_ipynb/gan-conv.ipynb)]

## PyTorch Workflows

- [Using PyTorch Dataset Loading Utilities for Custom Datasets -- Face Images from CelebA](pytorch_ipynb/custom-data-loader-celeba.ipynb)
- [Getting Gradients of an Intermediate Variable in PyTorch](pytorch_ipynb/manual-gradients.ipynb)

## TensorFlow Workflows

- [Saving and Loading Trained Models -- from TensorFlow Checkpoint Files and NumPy NPZ Archives](tensorflow_ipynb/saving-and-reloading-models.ipynb)
- [Chunking an Image Dataset for Minibatch Training using NumPy NPZ Archives](tensorflow_ipynb/image-data-chunking-npz.ipynb)
- [Storing an Image Dataset for Minibatch Training using HDF5](tensorflow_ipynb/image-data-chunking-hdf5.ipynb)
- [Using Input Pipelines to Read Data from TFRecords Files](tensorflow_ipynb/tfrecords.ipynb)
- [Using Queue Runners to Feed Images Directly from Disk](tensorflow_ipynb/file-queues.ipynb)
- [Using TensorFlow's Dataset API](tensorflow_ipynb/dataset-api.ipynb)