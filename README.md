# Artificial-Intelligence-Project
### Authors: Aadi Gopi, Janine Yanes, Jason Cai

### Project Overview
This repository contains the final project for the Intro to AI course. We implemented and compared three models - Perceptron, Neural Network, and PyTorch Neural Network - on two datasets: Faces and Digits. The goal was to analyze how training size impacts accuracy, error, standard deviation, and training time.
_________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
### Models Implemented
#### 1. Perceptron
&emsp; Multi-class perceptron with separate weight vectors per class.
 
&emsp; Updates weights based on prediction correctness.
 
&emsp; Trained iteratively using gradient descent-like updates.

#### 2. Neural Network 
&emsp; Architecture: 2 hidden layers, 100 neurons each.

&emsp; Activation: ReLU for hidden layers, softmax for output.

&emsp; Weight initialization: He initialization.

&emsp; Training: Mini-batch gradient descent with L2 regularization.

#### 3. PyTorch Neural Network
&emsp; Same architecture as above, implemented using PyTorch.

&emsp; Automatic differentiation and streamlined training loop.

_________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
### Datasets
&emsp; Faces Dataset: 451 training size.

&emsp; Digits Dataset: 5000 training size.

_________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
### Key Observations
#### Perceptron:
&emsp; Training time increased with more data.

&emsp; Highest mean accuracy was reached at ~50% of training data for Faces.

&emsp; Convergence observed for Faces (As more training data was used, std of accuracy became 0%).

&emsp; Less accurate than neural networks.

#### Neural Network:
&emsp; Better accuracy than Perceptron, especially on Digits.

&emsp; Required more data for Faces to reach similar accuracy as Digits.

&emsp; Training time was significantly lower than Perceptron for larger datasets.

#### PyTorch Neural Network:
&emsp; Highest overall accuracy and lowest error.

&emsp; Fastest training time due to optimized PyTorch backend.

&emsp; More stable results with generally lower standard deviation.

