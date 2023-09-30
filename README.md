# Credit Card Fraud Detection

This project is an implementation of a credit card fraud detection system using machine learning. The goal of this project is to build a model that can identify fraudulent credit card transactions from a dataset.

## Overview

- The project is implemented in a Jupyter Notebook (`Credit Card Fraud Detection.ipynb`).
- The dataset used for this project is named `creditcard.csv`, and it is available [here](https://colab.research.google.com/drive/1kyPYayGWgQIcGYfgelu2m6WOdGQ23GM4).
- It uses Python and popular libraries like Pandas, Matplotlib, Seaborn, and Scikit-Learn for data analysis, data preprocessing, and machine learning.

## Data Exploration

- The notebook starts with loading the dataset and performing initial data exploration.
- It checks for missing values and examines the unique values in each column.
- It also handles the 'Time' column, which contains a mix of timestamps in seconds and 'HH:MM:SS' format, by converting it to a consistent format.

## Data Analysis

- The project includes an analysis of the class distribution to understand the proportion of fraudulent and non-fraudulent transactions in the dataset.

## Model Training

- The notebook splits the dataset into training and testing sets.
- It trains a logistic regression classifier on the training data to build a fraud detection model.
- The model's performance is evaluated using ROC-AUC score and the ROC curve.

## How to Use

1. Clone the repository to your local machine:

   ```shell
   https://github.com/SurajSanap/Credit-Card-Fraud-Detection.git
