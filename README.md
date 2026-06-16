# Ad Sale Prediction Using Machine Learning

## Project Overview

This project predicts whether a customer will purchase a product after viewing an advertisement based on their demographic information such as Age and Estimated Salary.

The model is trained using machine learning classification algorithms and allows users to enter customer details and receive a prediction indicating whether the customer is likely to purchase the product.

---

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature scaling using StandardScaler
* Multiple machine learning model training
* Model evaluation and comparison
* Hyperparameter tuning
* User input prediction system
* Purchase probability estimation
* Easy-to-use prediction interface

---

## Dataset Information

The dataset contains customer information and purchase behavior.

### Input Features

| Feature         | Description              |
| --------------- | ------------------------ |
| Age             | Customer's age           |
| EstimatedSalary | Customer's annual salary |

### Target Variable

| Variable  | Description                      |
| --------- | -------------------------------- |
| Purchased | 1 = Purchased, 0 = Not Purchased |

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
---

## Machine Learning Workflow

### 1. Data Collection

Load the advertisement dataset.

### 2. Data Preprocessing

* Handle missing values
* Select input and output features
* Split dataset into training and testing sets

### 3. Feature Scaling

StandardScaler is used to normalize Age and Salary values.

### 4. Model Training

The following algorithms can be evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

### 5. Model Evaluation

Performance is measured using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation

### 6. Prediction

The trained model predicts whether a customer will purchase a product.

---

## User Input Prediction

The application accepts:

* Customer Age
* Customer Salary

Example:

Enter Customer Age: 35

Enter Customer Salary: 60000

Output:

Purchase Probability: 82.45%

Prediction: Customer WILL Purchase the Product
