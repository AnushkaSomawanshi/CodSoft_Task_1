CODSOFT Internship Projects

This repository includes the work I completed as part of the CODSOFT Data Science Internship. During the internship, I worked on three machine learning projects that helped me build a deeper understanding of data analysis, model development, and practical applications of machine learning using Python.

Project Overview

1. Iris Flower Classification

In this task, I worked with the popular Iris dataset, which contains features like petal length, petal width, sepal length, and sepal width for three different species of Iris flowers.

What I did:
- Performed data cleaning and explored the dataset using visualizations like pairplots and boxplots to understand the relationships between features.
- Observed that petal length and petal width were the most distinguishing features between species.
- Applied classification algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), and Decision Tree.
- Compared model performances using accuracy scores and confusion matrices.

What I observed:
- KNN and Decision Tree models performed well with high accuracy.
- Setosa was easily separable, while Versicolor and Virginica had some overlap.
- Feature scaling significantly impacted KNN's performance.

This project helped me understand how basic machine learning models can be used to solve classification problems effectively.

2. Sales Prediction

This task involved predicting product sales using regression techniques. The dataset included features like advertising spend across different platforms (TV, Radio, and Newspaper) and corresponding sales figures.

What I did:
- Carried out exploratory data analysis and visualized the correlation between advertising spend and sales.
- Observed that TV and Radio spend had stronger positive correlation with sales than Newspaper spend.
- Implemented Linear Regression and Random Forest Regressor to predict future sales.
- Evaluated models using R-squared, MAE, and residual plots.

What I observed:
- Linear Regression gave a good baseline model, but Random Forest provided better accuracy and handled non-linearity more effectively.
- The model could be improved further by including more business-specific features like seasonality, discounts, or customer demographics.

This task gave me insights into how data-driven decisions can optimize marketing strategies and predict business performance.

3. Movie Rating Prediction

The goal of this project was to predict the rating of a movie based on available metadata such as genre, director, cast, and duration.

What I did:
- Cleaned and preprocessed the dataset, handled missing values, and encoded categorical variables like genre and director using label encoding and one-hot encoding.
- Explored how certain directors or genres were linked to higher average ratings.
- Built regression models including Linear Regression and Support Vector Regressor (SVR) to predict ratings.
- Evaluated the models using Mean Squared Error and R-squared metrics.

What I observed:
- Some categorical features (like popular directors or actor combinations) had a clear influence on ratings.
- Encoding technique and feature selection played a major role in model performance.
- SVR captured the trends better but required careful tuning.

This project taught me how to engineer features from categorical data and apply regression techniques to real-world prediction problems.

Tools and Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook / Google Colab

Repository Structure

CODSOFT/
│
├── Task 1 - Iris Flower Classification/
│   └── iris_classification.ipynb
│
├── Task 2 - Sales Prediction/
│   └── sales_prediction.ipynb
│
├── Task 3 - Movie Rating Prediction/
│   └── movie_rating_prediction.ipynb
│
└── README.md

Final Note

This internship gave me the opportunity to apply machine learning algorithms to real datasets and understand the end-to-end workflow, from data preprocessing to model evaluation. Each task helped me build confidence in working with Python and its data science libraries. I look forward to exploring more complex datasets and diving deeper into areas like feature engineering, hyperparameter tuning, and deep learning.
