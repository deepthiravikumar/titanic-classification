# Titanic Survival Prediction Web App

This code demonstrates the development of a web application that predicts whether a passenger aboard the Titanic survived or not. It uses machine learning, specifically a Random Forest Classifier, to make predictions based on passenger information.

## Introduction

Predicting passenger survival on the Titanic is a classic machine learning problem. The goal is to build a model that can predict whether a passenger survived (yes) or did not survive (no) based on various features such as passenger class, gender, age, number of siblings/spouses aboard, number of parents/children aboard, fare, cabin information, and the port of embarkation.

## Data Source

The Titanic dataset is used as the data source. It contains information about passengers on the Titanic, including whether they survived or not. The dataset is loaded and preprocessed to prepare it for machine learning.

## Data Preprocessing

- Label Encoding: Categorical variables like "Sex," "Cabin," and "Embarked" are encoded using Label Encoding to convert them into numerical form for machine learning.

- Handling Missing Values: Missing values in the "Age" column are imputed with the most frequent value.

- Feature Selection: The "PassengerId," "Name," and "Ticket" columns are dropped as they are not relevant for prediction.

- Data Split: The data is split into training and testing sets for model training and evaluation.

## Model Training

A Random Forest Classifier is used to build the predictive model. It is trained on the training data, and predictions are made on the testing data.

## Model Evaluation

The accuracy score and a classification report are used to evaluate the model's performance on the testing data. The classification report provides detailed metrics such as precision, recall, and F1-score for each class (survived and not survived).

## Web Application

The code uses Gradio to create a web interface for making predictions. Users can input passenger information such as class, gender, age, and more, and the model will predict whether the passenger survived or not.

## Usage

To run this code, ensure you have the required libraries installed, such as pandas, numpy, seaborn, scikit-learn, and Gradio. You can customize the code for your own dataset or problem by adjusting the features and model parameters as needed.

## Author

This code was written by deepthi_ravikumar.

For any questions or inquiries, please contact deepthisrikr01@gmail.com.
