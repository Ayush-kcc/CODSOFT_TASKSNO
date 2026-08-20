# 🎬 IMDb Movie Rating Prediction

## 📌 Project Overview

This project is part of my **CODSOFT Data Science Internship – Task 2**.

The objective of this project is to build a Machine Learning model that predicts the rating of a movie based on available movie-related features such as **genre, director, and actors**.

The project uses the **IMDb Movies India** dataset and applies data preprocessing, exploratory data analysis, feature engineering, regression models, and model evaluation.

---

## 🎯 Objective

The main objectives of this project are:

- Analyze historical movie data.
- Clean and preprocess the dataset.
- Handle missing and inconsistent values.
- Perform exploratory data analysis.
- Prepare features for Machine Learning.
- Train regression models to predict movie ratings.
- Evaluate model performance using appropriate metrics.
- Perform hyperparameter tuning.
- Save the trained Machine Learning model.
- Use the trained model to make predictions.

---

## 📊 Dataset

The dataset used in this project is:

**IMDb Movies India Dataset**

Dataset source:

https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies

The dataset contains information about Indian movies, including details such as:

- Movie name
- Genre
- Director
- Actors
- Duration
- Votes
- Rating
- Year

The **Rating** column is used as the target variable for prediction.

---

## 🛠️ Technologies and Libraries Used

- **Python** – Programming language
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine Learning
- **Joblib** – Model saving and loading
- **Jupyter Notebook** – Development environment

---

## 🔄 Project Workflow

The project follows these main steps:

### 1. Data Loading

The IMDb Movies India dataset is loaded into a Pandas DataFrame.

### 2. Data Exploration

The dataset is examined to understand:

- Number of rows and columns
- Column names
- Data types
- Missing values
- Duplicate records
- Statistical information

### 3. Data Cleaning

The data is cleaned by:

- Handling missing values
- Removing unnecessary spaces
- Converting appropriate columns into numerical formats
- Handling inconsistent data
- Removing duplicate records where required

### 4. Exploratory Data Analysis

Different visualizations are used to understand the dataset and identify patterns between movie features and ratings.

### 5. Feature Engineering

Relevant movie features are selected and prepared for Machine Learning.

Categorical features such as genre, director, and actors are transformed into numerical representations using preprocessing techniques.

### 6. Model Building

Regression-based Machine Learning models are trained to predict movie ratings.

### 7. Model Evaluation

The model is evaluated using metrics such as:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### 8. Hyperparameter Tuning

Hyperparameter tuning is performed to find better model parameters and improve the model's performance.

### 9. Feature Importance

Feature importance is analyzed to understand which features have a greater influence on movie rating predictions.

### 10. Model Saving

The final trained model is saved using `joblib` so that it can be reused for future predictions.

---

## 🤖 Machine Learning

This project uses **regression techniques** because the target variable, movie rating, is a numerical value.

A **Random Forest Regressor** is used as one of the main Machine Learning models.

The model learns relationships between movie features and historical ratings and uses those relationships to estimate ratings for new movies.

---

## 📈 Model Performance

The final model achieved an **R² score of approximately 0.3584** on the evaluation data.

This means the model is able to explain a portion of the variation in movie ratings based on the available features.

The performance can potentially be improved with:

- More informative features
- Better feature engineering
- Additional data
- Improved preprocessing
- Further hyperparameter optimization

---

## 💾 Saved Model

The trained model is saved as:

```text
imdb_movie_rating_model.pkl
