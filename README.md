CODSOFT Internship Projects

This repository includes the work I completed as part of the CODSOFT Data Science Internship. During the internship, I worked on three machine learning projects that helped me build a deeper understanding of data analysis, model development, and practical applications of machine learning using Python.
Titanic Survival Prediction
Internship: CodSoft Data Science Internship
Task 1: Titanic Survival Prediction
Objective
The objective of this project is to predict whether a passenger on the Titanic survived or not, using machine learning techniques. This task involves cleaning and analyzing real-world data, selecting meaningful features, training classification models, and evaluating their performance. This is a classic beginner-friendly problem that builds a strong foundation in supervised learning.

Dataset Description
The dataset used in this task contains data of passengers aboard the RMS Titanic. Each row represents one person, and columns contain information such as:

PassengerId: Unique identifier for each passenger

Pclass: Ticket class (1 = Upper, 2 = Middle, 3 = Lower)

Name: Full name

Sex: Gender

Age: Age in years

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Amount paid for the ticket

Cabin: Cabin number

Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Target variable (0 = Did not survive, 1 = Survived)

Steps Performed
1. Data Preprocessing
Handled missing values in columns like Age, Cabin, and Embarked.

Converted categorical variables into numeric using encoding techniques.

Removed unnecessary features such as Name, Ticket, and Cabin for model simplicity.

2. Exploratory Data Analysis (EDA)
Analyzed survival distribution based on gender, class, age, etc.

Used visualizations like bar plots, histograms, and correlation heatmaps.

3. Feature Engineering
Selected relevant features based on domain knowledge and correlation.

Transformed and scaled data where needed.

4. Model Building
Applied supervised learning algorithms such as:

Logistic Regression

Random Forest Classifier

Split data into training and test sets using train_test_split.

5. Model Evaluation
Evaluated models using metrics like:

Accuracy

Confusion Matrix

Precision, Recall, and F1-Score

(Optional) ROC Curve and AUC score

Results
The Random Forest Classifier gave the best accuracy among the models.

Gender, passenger class, and fare were among the top predictors of survival.

Female passengers and those in higher classes had higher survival probabilities.

Future Scope
Use advanced models like XGBoost or ensemble techniques for improved accuracy.

Deploy the model using Streamlit to create a web-based Titanic survival predictor.

Tune hyperparameters using GridSearchCV.

Apply cross-validation to reduce variance in model performance.
