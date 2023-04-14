# Credit Card Fraud Detection using PyCaret
This repository contains a Jupyter Notebook where we will perform Credit Card Fraud Detection using PyCaret, a Python library for machine learning.

## Context
The dataset contains transactions made by credit cards in September 2013 by European cardholders.

## Overview
Credit card fraud is a common problem that affects many people worldwide. Detecting fraudulent transactions in a timely manner is essential to prevent monetary losses. In this project, we will use machine learning algorithms to classify credit card transactions as either fraudulent or genuine.

We will perform the following tasks:

1.Data Analysis: We will analyze the credit card transactions dataset to understand the distribution of fraudulent and genuine transactions.

2.Feature Engineering: We will create new features from the existing ones to improve the performance of the machine learning models.

3.Model Building and Prediction using ML Techniques: We will build several machine learning models using various algorithms and evaluate their performance.

4.Model Building and Prediction using PyCaret(Auto ML): We will use PyCaret, an automated machine learning library, to build and evaluate machine learning models.

## Dependencies
To run this notebook, you will need the following dependencies:

- PyCaret (version 2.3.1 or  higher)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
## Installation
To import the required dependencies, you can use pip, the Python package manager. Run the following command:

```bash
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import sklearn
import scipy
from sklearn.metrics import classification_report,accuracy_score 
```
## Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. It contains credit card transactions made by European cardholders. The dataset is highly unbalanced, with a very low percentage of fraudulent transactions (0.172%).

## Usage
To run the notebook, simply open it using Jupyter Notebook or Jupyter Lab and run the cells in order. Make sure to have all the dependencies installed.

## Results
Our analysis shows that PyCaret can be a powerful tool for Credit Card Fraud Detection. The AutoML feature allows us to quickly and efficiently build and evaluate several machine learning models, selecting the best performing one for the task.
![Logo](https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg)



