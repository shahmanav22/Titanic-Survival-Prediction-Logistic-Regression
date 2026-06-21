# Titanic Survival Prediction using Logistic Regression

## Project Overview

This project implements a Machine Learning classification model to predict whether a passenger survived the Titanic disaster using the Titanic dataset. The project demonstrates the complete machine learning workflow, including data exploration, preprocessing, feature engineering, model training, and evaluation.

---

## Dataset

Dataset: Titanic Dataset by M Yasser H

https://www.kaggle.com/datasets/yasserh/titanic-dataset

The dataset contains passenger information such as age, gender, ticket class, fare, family members, embarkation port, and survival status.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration
- Loaded the dataset
- Examined data types and summary statistics
- Checked missing values
- Explored survival distribution
- Analyzed relationships between passenger attributes and survival

### 2. Data Preprocessing
- Filled missing values in Age using the mean
- Filled missing values in Embarked using the mode
- Dropped the Cabin column due to excessive missing values
- Removed unnecessary features (PassengerId, Name, Ticket)

### 3. Feature Engineering
- Encoded the Sex column into numerical values
- Applied One-Hot Encoding to the Embarked column

### 4. Model Building
- Split the dataset into training and testing sets
- Trained a Logistic Regression classifier
- Generated predictions on the test dataset

### 5. Model Evaluation
- Evaluated model performance using Accuracy Score

---

## Machine Learning Concepts Practiced

- Exploratory Data Analysis (EDA)
- Missing Value Treatment
- Feature Selection
- Feature Encoding
- Train-Test Split
- Binary Classification
- Logistic Regression
- Model Evaluation

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Preparing real-world datasets for machine learning
- Building an end-to-end binary classification pipeline
- Applying Logistic Regression using Scikit-learn
- Evaluating classification model performance

---

## Author

Manav Shah
