## Kaggle-loan-lending-Club-ANN
This project focuses on predicting loan defaults using an Artificial Neural Network (ANN) built with Keras. The goal is to classify whether a borrower is likely to default based on historical lending data. The project includes data preprocessing, feature engineering, model training, and evaluation.
# Overview
Loan default prediction is critical for financial institutions to assess credit risk and manage lending policies effectively. This project leverages a Kaggle dataset and employs deep learning techniques to predict the likelihood of loan defaults based on borrower attributes and loan characteristics.
# Features
* Data Cleaning: Handles missing values and converts categorical data into numerical form.
* Feature Engineering: Encodes variables, normalizes data, and optimizes the input for ANN.
* Deep Learning Model:
  * Fully connected ANN with multiple layers.
  * ReLU activation in hidden layers.
  * Sigmoid activation in the output layer for binary classification.
* Evaluation Metrics:
  * Accuracy, Precision, Recall, F1-Score.
  * Confusion Matrix for detailed class-level analysis.
* Visualization: Includes learning curves and evaluation plots.
# Dataset
The dataset contains features like loan amount, term, interest rate, credit score, and payment history. These features are used to predict the likelihood of a loan default.
* Source: [Kaggle](https://www.kaggle.com/)
* DataSets: [lending_club_loan_two.csv](https://drive.google.com/file/d/1niYMelh1rfcm0HhdmR2hMtGkRYgk446r/view?usp=sharing)
# Results
* Training Accuracy: 93%
* Validation Accuracy: 90%
* Performance Metrics:
  * Precision: 93%
  * Recall: 89%
  * F1-Score: 89%
# Acknowledgments
Thanks to Kaggle for providing the dataset and to the open-source community for tools and resources.
