# Comparative-Analysis-of-KNN-and-Naive-Bayes-Algorithms-for-Student-Performance-Prediction
# Loan Prediction System

This project implements a Loan Prediction System using machine learning algorithms in Python. It aims to predict the status of a loan application based on various features.

## Dataset

The dataset used for this project consists of two files: `loan_train.csv` and `loan_test.csv`. The training dataset (`loan_train.csv`) is used to train the models, while the testing dataset (`loan_test.csv`) is used to make predictions.

## Setup

To run the project, follow these steps:

1. Install the required libraries by running `pip install -r requirements.txt`.
2. Place the dataset files (`loan_train.csv` and `loan_test.csv`) in the same directory as the code files.
3. Run the `loan_prediction.py` script to train the models, make predictions, and evaluate their performance.

## Usage

The `loan_prediction.py` script performs the following steps:

1. Data Cleaning: Missing values in categorical features are filled with the mode, and missing values in numerical features are filled with the median.
2. Data Preprocessing: Categorical variables are converted to numerical using Label Encoding.
3. Model Training: The dataset is split into training and validation sets. Two models, K-Nearest Neighbors (KNN) and Naive Bayes, are trained on the training set.
4. Model Evaluation: The accuracy and confusion matrix are computed for both models on the validation set.
5. Model Testing: Predictions are made for the test dataset using both models, and their accuracy and confusion matrix are calculated.

## Results

The results of the model predictions and evaluation are printed to the console. The accuracy and confusion matrices for both models on the validation and test datasets are displayed.
