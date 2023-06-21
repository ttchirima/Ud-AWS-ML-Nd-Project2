# MNIST Digit Classifier Project Introduction

## Introduction to Deep Learning Final Project

## Overview
In this project, you will be given a Jupyter Notebook to do all of your coding and written explanations. You will preprocess a dataset for handwritten digit recognition, build a neural network, then train and tune that neural network using your data.


Before you get started, please see the rubric, and be sure to see the Jupyter Notebook on the Environments to get started.

Images or additional files needed to make your notebook or report complete can be also added.

## Getting Started
Project Instructions
Submission Instructions
Please save your trained model in the workspace or upload a single file for review.

##Instructions Summary

* Step 1
- Load the dataset from torchvision.datasets
- Use transforms or other PyTorch methods to convert the data to tensors, normalize, and flatten the data.
- Create a DataLoader for your dataset

* Step 2
- Visualize the dataset using the provided function and either:
- Your training data loader and inverting any normalization and flattening
- A second DataLoader without any normalization or flattening
- Explore the size and shape of the data to get a sense of what your inputs look like naturally and after   transformation. Provide a brief justification of any necessary preprocessing steps or why no preprocessing is needed.

* Step 3
- Using PyTorch, build a neural network to predict the class of each given input image
- Create an optimizer to update your network’s weights
- Use the training DataLoader to train your neural network

* Step 4
- Evaluate your neural network’s accuracy on the test set.
- Tune your model hyperparameters and network architecture to improve your test set accuracy, achieving at least 90% accuracy on the test set.

Step 5
- Use torch.save to save your trained model.

## License
[License](LICENSE.txt)
