# Communities and Crime Regressor

## Description
This repository focuses on predicting the total number of violent crimes in communities using a fully connected neural network implemented with Keras. The objective is to develop a regression model that can accurately predict the crime rate based on various socio-economic factors.

The dataset used for this project is the Communities and Crime dataset, which contains socio-economic and crime-related information for various communities in the United States. By training a neural network on this dataset, we aim to capture the complex relationships between the features and the target variable (total number of violent crimes) and make accurate predictions.

## Dataset
The dataset used for this project is the Communities and Crime dataset from UCI. It contains a collection of features related to the socio-economic characteristics of communities, such as income levels, education, employment rates, and more. The target variable is the total number of violent crimes reported in each community.

The dataset is preprocessed and cleaned to handle missing values and ensure compatibility with the neural network model.

## Approach
The project involves the following steps:
1. Data preprocessing, including handling missing values, scaling features, and splitting the dataset into training and test sets.
2. Implementation of a fully connected neural network using Keras, a high-level deep learning library.
3. Model training and evaluation using the training set, followed by testing on the unseen test set.
4. Model performance validation using K-Folds cross-validation to assess the generalization ability of the model.

## Usage
1) Clone the repository to your local machine using the following command:
```
git clone https://github.com/kajolshah310/communities_and_crime_regressor.git
```
2) Open the communities_crimes_regressor.ipynb file in Jupyter Notebook or any other compatible IDE.

3) Install the required packages and dependencies mentioned in the notebook, if necessary.

4) Execute the code and follow along with the implementation of the crime regression model.

Feel free to modify the code, experiment with different neural network architectures or hyperparameters, or explore additional techniques to improve the accuracy of the crime rate predictions.

## References
1) Dataset:- http://archive.ics.uci.edu/ml/machine-learning-databases/communities/communities.data

## License
This repository is licensed under the MIT License. Feel free to use the code and the models for your own projects or research.
