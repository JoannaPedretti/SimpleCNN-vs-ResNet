# SimpleCNN-vs-ResNet

## Description
A school project for my deep learning class where a simple CNN is compared to a ResNet50 model, using the CIFAR-10 dataset. The goal is to evaluate the performance of each model on the same image classification task, and observe how ResNet50 is utilized to have more efficient training due to pre-training the weights. ResNet architectures can also be used to solve issues such as the vanishing gradient problem that occur in deep convolutional neural networks.

## Features
- Two .ipynb files, one for each model, originally written in Google Colab. 
- Train and evaluate a simple CNN and a ResNet50 model.
- Compute accuracy, loss, precision, recall, and F-1 score for each model and compare.
- Results are plotted in the respective notebook for each model. 

## Dataset
- [CIFAR-10 dataset on Kaggle](https://www.cs.toronto.edu/~kriz/cifar.html)
- 60,000 32x32 color images in 10 classes, with 6000 images per class.

## Results after training for 10 epochs
- Simple CNN Test Accuracy: 69.7%
- ResNet50 Test Accuracy: 95.5%
- ResNet clearly has an advantage by utilizing pre-trained weights and transfer learning. 

## Instructions to run the Notebooks
- Upload .ipynb files to Google Drive, open in Google Colab
- No setup required, just run the cells!
- Or try using Jupyter
