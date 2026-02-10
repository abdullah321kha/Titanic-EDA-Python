# Titanic Survival Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an in depth Exploratory Data Analysis (EDA) on the Titanic dataset to identify key factors that influenced passenger survival.
The analysis focuses on data cleaning, visualization, statistical insights, and feature engineering to prepare the dataset for predictive modeling.



## 🎯 Objectives

Understand the structure and quality of the Titanic dataset

Handle missing values and clean the data

Explore survival patterns using visual and statistical analysis

Engineer meaningful features to enhance insights

Prepare a modeling ready dataset

## 🧰 Tools & Technologies

Programming Language: Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

## 📂 Dataset Information

Source: Seaborn built-in Titanic dataset

Records: 891 passengers

Features: Demographics, passenger class, fare, family relations, survival status


## 🔍 Key Steps Performed
### 1. Data Loading & Inspection

Loaded dataset using Seaborn

Inspected shape, data types, and missing values

### 2. Data Cleaning

Imputed missing values:

age → median

embarked → mode

Dropped deck due to excessive missing values

Converted categorical variables for better efficiency

### 3. Exploratory Data Analysis

Univariate Analysis: Survival distribution, age, passenger class

Bivariate Analysis: Survival vs gender, class, and age

Multivariate Analysis: Correlation heatmap

### 4. Feature Engineering

Created family_size feature from sibsp and parch

Analyzed survival trends based on family size


### 📊 Key Insights

Female passengers had significantly higher survival rates

First class passengers were more likely to survive

Younger passengers had better survival chances

Higher fare showed a positive correlation with survival

Passengers traveling with small families survived more than solo travelers


### 📈 Visualizations Included

Missing value heatmap

Survival count plots

Age distribution histogram

Gender and class-based survival plots

Correlation heatmap

Family size vs survival analysis


### ✅ Conclusion

This EDA revealed strong relationships between survival and factors such as gender, passenger class, age, fare, and family size.
The project provides a solid analytical foundation for building machine learning models to predict survival outcomes.


### 🚀 Future Work

Build predictive models (Logistic Regression, Random Forest)

Perform feature importance analysis

Hyperparameter tuning and model evaluation

Extend project into a full ML pipeline


#### 👤 Author

Abdullah Imran
Software Engineering Student | Data Science & AI Enthusiast