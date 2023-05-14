# Gradient Decent Types in ANN

- This project provides an implementation of three different types of gradient descent algorithms for optimizing machine learning models: Stochastic Gradient Descent (SGD), Batch Gradient Descent (BGD), and Mini-batch Gradient Descent (MBGD).

## Gradient Descent Algorithms
Gradient descent is an optimization algorithm used to minimize the cost function of a machine learning model. The algorithm iteratively adjusts the model's parameters to reduce the error between the predicted output and the actual output. The following gradient descent algorithms are implemented in this project:

## Stochastic Gradient Descent (SGD): 
- This algorithm updates the model's parameters after each individual training example, making it computationally efficient but can result in noisy updates.


## Batch Gradient Descent (BGD): 
- This algorithm updates the model's parameters after each epoch by computing the average gradient of the cost function over the entire training set, making it more accurate but computationally expensive.


## Mini-batch Gradient Descent (MBGD): 
- This algorithm updates the model's parameters after a small batch of training examples, balancing the computational efficiency of SGD with the accuracy of BGD.


## Getting Started
To get started with the project, clone the repository and navigate to the project directory:

``
git clone https://github.com/VigneshwaranBS/Gradient-Decent-Types-in-ANN.git
``
## After cloning the repository, you can run the gradient descent algorithms using the following command:
``
python gradient_descent.py
``

- This will execute the script that loads a sample dataset, trains a linear regression model using each of the gradient descent algorithms, and outputs the results.

## Dependencies
The project has the following dependencies:

Python 3 
NumPy
You can install NumPy using pip:

``
pip install numpy
``

``
pip install pandas
``

## Contributing
- If you'd like to contribute to this project, please fork the repository and make your changes. Once you've made your changes, create a pull request and a project maintainer will review your changes.
