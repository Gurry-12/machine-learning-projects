# House_price_pridection
This repository houses a machine learning model designed to predict house prices based on various features. The model utilizes a dataset containing historical house prices and associated attributes. It serves as a temporary project for learning and experimentation purposes, and it is not intended for production deployment.

# House Price Prediction Model


## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Dataset](#dataset)


## Overview

This repository contains a machine learning model for predicting house prices based on various features. The model has been trained on a dataset comprising historical house prices and their associated attributes. This project serves as a temporary learning and experimentation exercise and is not intended for production deployment.

## Installation

To use the house price prediction model, you'll need Python and several libraries installed. Follow these steps to set up your environment:
        
        import pandas as pd
        import matplotlib.pyplot as plt
        import numpy as np
        from sklearn.model_selection import train_test_split 
        from sklearn.model_selection import StratifiedShuffleSplit
        from pandas.plotting import scatter_matrix
        from sklearn.pipeline import Pipeline
        from sklearn.preprocessing import StandardScaler
        from sklearn.impute import SimpleImputer as Imputer
        from sklearn.linear_model import LinearRegression
        from sklearn.metrics import mean_squared_error
        from sklearn.model_selection import cross_val_score
        from joblib import  dump 
        
## Usage

To run the house price prediction model on your own data, follow these steps:

    Prepare your input data in CSV format, with each row representing a house and its features.
    Use the following code snippet to load the model and make predictions:
    
view this file - [usage.py](usage.py)


## Model Details

The house price prediction model is built using linear regression. It leverages scikit-learn's pipeline functionality to handle missing values with a median imputer and standard scale the features. The model is trained on the stratified train set and evaluated using cross-validation to ensure robust performance.

## Dataset

The dataset used to train and evaluate the model can be found in the file  - [Housing1.csv](Housing1.csv) . It contains historical house prices and various attributes. Note that this dataset is not included in the repository due to its size.

## Contributing

Contributions are welcome! Since this is a temporary project for learning purposes, feel free to experiment and explore different techniques. You can create branches or make changes as needed without worrying about production deployment or strict coding conventions.

For any questions or inquiries about the project, you can contact me at singhsarpreet234@gmail.com.
