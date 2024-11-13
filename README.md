[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/SjkiGG1E)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16343506&assignment_repo_type=AssignmentRepo)
# Homework 2: Neural Network in Numpy
  
This notebook features a basic Neural Network made only with Numpy, trained on the MNIST dataset. 
  
## Network Features
The network is implemented with the following architecture:  
  
Input Layer: 784 neurons (28x28 pixels)  
Hidden Layer 1: 256 neurons  
Hidden Layer 2: 128 neurons  
Hidden Layer 3: 64 neurons  
Output Layer: 10 neurons (0-9 digits)  
  
The activation functions for each layer are:  
  
Hidden Layer 1: ReLU  
Hidden Layer 2: SELU  
Hidden Layer 3: tanh  
Output Layer: Softmax  
  
The network is trained with the following hyperparameters:  
  
Learning Rate: 0.001  
Weight Initialization: Small Random Values  
Optimizer Algorithm: Adam  
Training: Mini-batch Gradient Descent (100)  
Loss function: Categorical Cross-entropy  
  
Results:  
The model achieved an accuracy of % on the test set.
