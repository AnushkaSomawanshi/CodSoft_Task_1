# CODSOFT Internship Projects

This repository includes the work I completed as part of the CODSOFT Data Science Internship.  
During the internship, I worked on three machine learning projects that helped me build a deeper understanding of data analysis, model development, and the practical applications of machine learning using Python.

This README file describes Task 1: Titanic Survival Prediction, the first project in the internship.

---

# Titanic Survival Prediction

## Project Overview

This project aims to predict the survival of passengers aboard the Titanic using supervised machine learning algorithms.  
The dataset contains passenger details such as age, gender, class, fare, and embarkation point.  
The objective is to build a model that accurately classifies whether a given passenger survived or not.

---

## What I Did

- Loaded and explored the Titanic dataset  
- Cleaned the data by handling missing values in key columns like Age, Embarked, and Cabin  
- Performed exploratory data analysis (EDA) to identify important patterns and survival trends  
- Converted categorical features to numerical using encoding techniques  
- Selected the most relevant features for model training  
- Trained and tested classification models:
  - Logistic Regression  
  - Random Forest Classifier  
- Evaluated model performance using accuracy, confusion matrix, and classification report  
- Interpreted feature importance to understand which variables influenced survival the most  

---

## What I Observed

- Gender was a major factor: female passengers had significantly higher survival rates  
- Passenger class also played a strong role — first-class passengers had better survival outcomes  
- Fare and embarkation point had a moderate influence on survival  
- The Random Forest Classifier outperformed Logistic Regression in terms of accuracy and generalization  
- Data visualizations made patterns more obvious and helped guide feature selection  

---

## Dataset Description

The Titanic dataset includes the following features:

- PassengerId: Unique identifier for each passenger  
- Pclass: Ticket class (1 = Upper, 2 = Middle, 3 = Lower)  
- Name, Sex, Age  
- SibSp, Parch: Number of relatives aboard  
- Ticket, Fare, Cabin  
- Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  
- Survived: Target variable (0 = Did not survive, 1 = Survived)  

---

## Key Steps in the Project

### 1. Data Cleaning

- Handled missing values using imputation or dropping as appropriate  
- Removed less useful columns like Name, Ticket, and Cabin  

### 2. Exploratory Data Analysis (EDA)

- Analyzed survival rates by gender, class, age groups, and more  
- Visualized data using seaborn and matplotlib libraries  

### 3. Feature Engineering

- Encoded categorical variables such as Sex and Embarked  
- Selected features like Pclass, Sex, Age, Fare, SibSp, and Parch  

### 4. Model Training and Evaluation

- Split data into training and testing sets using train_test_split  
- Trained Logistic Regression and Random Forest models  
- Evaluated results using:
  - Accuracy Score  
  - Confusion Matrix  
  - Classification Report  

---

## Future Enhancements

- Improve performance using advanced models like XGBoost or Support Vector Machines  
- Create a simple web interface using Streamlit for live predictions  
- Perform hyperparameter tuning with GridSearchCV  
- Use cross-validation for more robust model evaluation  


