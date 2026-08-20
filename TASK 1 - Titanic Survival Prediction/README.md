# Titanic Survival Prediction

## Project Overview

This project focuses on predicting whether a passenger survived the Titanic disaster using Machine Learning techniques.

The model analyzes passenger information such as age, gender, passenger class, fare, and other available features to predict the survival outcome.

## Objective

The main objective of this project is to:

- Analyze the Titanic passenger dataset.
- Clean and preprocess the data.
- Explore important patterns and relationships.
- Perform feature engineering.
- Train a Machine Learning classification model.
- Evaluate the model's performance.
- Predict whether a passenger survived or not.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning

This is a **classification problem** because the target variable represents two possible outcomes:

- `0` → Did not survive
- `1` → Survived

The project uses Machine Learning classification techniques to learn patterns from historical passenger data and make predictions.

## Dataset

The dataset contains information about passengers who were aboard the Titanic.

Some important features include:

- Passenger Class
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare
- Port of Embarkation

The target variable is:

**Survived**

## Project Workflow

The project follows these major steps:

1. Import required libraries
2. Load the dataset
3. Understand the dataset
4. Perform Exploratory Data Analysis (EDA)
5. Check missing values
6. Clean and preprocess the data
7. Perform feature engineering
8. Split data into training and testing sets
9. Train the Machine Learning model
10. Evaluate model performance
11. Make predictions
12. Save the trained model

## Data Preprocessing

The dataset is processed before training the model.

The preprocessing includes:

- Handling missing values
- Removing unnecessary columns
- Encoding categorical variables
- Converting data into suitable numerical form
- Preparing features and target variables

## Model Evaluation

The trained model is evaluated using appropriate classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help determine how well the model predicts passenger survival.

## Project Files

```text
Titanic-Survival-Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── Titanic-Dataset.csv
├── requirements.txt
└── README.md
