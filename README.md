# mental_health_predictor
# 🧠 Student Mental Health Prediction

## Overview

This project develops a machine learning model to predict students' **Mental Health Score** using demographic, academic, lifestyle, and social media usage data. The project follows a complete end-to-end machine learning workflow, including data exploration, preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, and model serialization.

---

## Dataset

The dataset contains information related to students' mental health and daily habits.

**Features include:**

* Age
* Gender
* Country
* Academic Level
* Study Hours
* Social Media Usage
* Daily Unlocks
* Most Used Platform
* Sleep Hours
* Physical Activity
* Stress Level
* Relationship Status

**Target Variable**

* Mental_Health_Score

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration

* Loaded and explored the dataset
* Performed Exploratory Data Analysis (EDA)
* Identified missing values, duplicates, and feature distributions
* Visualized relationships using histograms, box plots, scatter plots, and correlation heatmaps

### 2. Data Preprocessing

* Removed duplicate records
* Corrected inconsistent values
* Applied log transformation to skewed features
* Grouped high-cardinality categories
* Encoded categorical variables using **OrdinalEncoder** and **OneHotEncoder**
* Scaled numerical features using **StandardScaler**

### 3. Feature Engineering & Pipeline

* Split the data into training and testing sets before preprocessing to prevent data leakage
* Built a preprocessing workflow using **ColumnTransformer**
* Combined preprocessing and model training into a single **Scikit-learn Pipeline** for reproducible and deployment-ready predictions

### 4. Model Development

Implemented and compared:

* Linear Regression
* Random Forest Regressor

Optimized the Random Forest model using **RandomizedSearchCV**.

### 5. Model Evaluation

Models were evaluated using:

* R² Score
* MAE
* MSE
* RMSE

The best-performing model and its complete preprocessing pipeline were saved using **Joblib** for future inference.

---

## Results

This project demonstrates an end-to-end machine learning workflow while following industry best practices such as:

* Comprehensive Exploratory Data Analysis
* Robust Data Preprocessing
* Feature Engineering
* Scikit-learn Pipeline Architecture
* Hyperparameter Tuning
* Model Performance Comparison
* Deployment-ready Model Serialization

---

## Project Structure

```text
├── data/
│   └── Student_Social_Media_Mental_Health.csv
│
├── notebooks/
│   └── Student_Mental_Health_Prediction.ipynb
│
├── models/
│   └── mental_health_pipeline.pkl
│
├── images/
│   └── visualizations/
│
├── requirements.txt
└── README.md
```
## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Feature Engineering
* Machine Learning
* Scikit-learn Pipeline
* ColumnTransformer
* Hyperparameter Tuning
* Model Evaluation
* Model Serialization
* Predictive Analytics

---

## Author

**Anshu Kumar**
