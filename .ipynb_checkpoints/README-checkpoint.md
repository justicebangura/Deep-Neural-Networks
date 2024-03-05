# Venture Funding with Deep Learning

![Neural Network](https://cdn-images-1.medium.com/max/2000/1*ILJI87KKC7Y3y5ExxbGA8A.png)

In this project, I developed a deep learning model to predict the success of funding applicants for Alphabet Soup.

## Steps:

The steps for this challenge are broken down into the following sections:

1. Data Preparation: Preparing the data for use in a neural network model.
2. Model Compilation and Evaluation: Compiling and evaluating a binary classification model using a neural network.
3. Model Optimization: Optimizing the neural network model to improve accuracy.

## Process

I utilized Pandas for data preprocessing, scikit-learn’s StandardScaler() for feature scaling, and TensorFlow along with Keras for building and training the neural network model. The dataset was compiled and evaluated, and the neural network model was optimized to enhance its predictive performance.

## Report

### Original Model:
- Defined the number of input features and created two hidden layers with ReLU activation for the hidden layers and Sigmoid for the output layer.
- Fitted the model using 50 epochs and the training data.

Evaluation:
- Loss: 0.5589
- Accuracy: 0.7262

### Alternative Model:
- Defined the number of input features and created one hidden layer with ReLU activation for the hidden layer and Sigmoid for the output layer.
- Fitted the model using 50 epochs and the training data.

Evaluation:
- Loss: 0.5630
- Accuracy: 0.7301

### Alternative Model 2:
- Defined the number of input features and created one hidden layer with more neurons.
- Used ReLU activation for the hidden layer and Sigmoid for the output layer.
- Fitted the model using 100 epochs and the training data.

Evaluation:
- Loss: 0.5686
- Accuracy: 0.7308

## Summary

The original model achieved a moderate level of accuracy, which was improved slightly in the alternative models by adjusting the architecture and training duration. Saving the models as HDF5 files ensures their accessibility for future use.
