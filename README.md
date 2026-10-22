
# Ford Car Price Prediction

## Project Overview

This project focuses on predicting the prices of used Ford cars using machine learning. I explored the dataset, performed data preprocessing, and built two Linear Regression models to understand how different categorical encoding techniques affect prediction performance.

The project helped me gain practical experience with data analysis, feature encoding, feature scaling, model training, and evaluation.

## Dataset

The dataset contains used Ford car listings with features such as:

- Model
- Year
- Transmission
- Mileage
- Fuel Type
- Tax
- Miles Per Gallon (MPG)
- Engine Size

The target variable is the car price.

## Models and Approaches

### 1. Linear Regression with One-Hot Encoding

In the first approach, I used One-Hot Encoding to transform categorical features such as model, transmission, and fuel type into numerical columns. I also applied StandardScaler to the numerical features before training the Linear Regression model.

**R² Score: 0.8397**

**Adjusted R² Score: 0.8387**

### 2. Linear Regression with Label Encoding

In the second approach, I used Label Encoding to convert categorical features into numerical values. I then applied feature scaling and trained another Linear Regression model.

**R² Score: 0.7310**

## Model Comparison

The first model, which uses One-Hot Encoding, achieved a higher R² score than the second model using Label Encoding.

This comparison helped me understand how categorical feature representation can influence the performance of a machine learning model.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Kaggle

## Project Workflow

1. Loaded and explored the dataset.
2. Performed exploratory data analysis (EDA).
3. Examined relationships between vehicle features and prices.
4. Encoded categorical variables using two different approaches.
5. Applied feature scaling.
6. Split the dataset into training and testing sets.
7. Trained two Linear Regression models.
8. Evaluated and compared model performance using R² and Adjusted R².

## Key Learnings

- Data cleaning and exploratory data analysis.
- One-Hot Encoding and Label Encoding.
- Feature scaling using StandardScaler.
- Training regression models with Scikit-learn.
- Evaluating and comparing machine learning model performance.

## Purpose

This project was developed as a hands-on machine learning practice project to strengthen my understanding of regression, preprocessing techniques, and model evaluation.
