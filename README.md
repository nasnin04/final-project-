Online News Popularity Prediction

Overview

In the digital age, online news articles compete for attention, but only a few achieve viral success. Understanding the factors influencing article popularity is crucial for publishers and content creators looking to maximize engagement. This project aims to develop a machine learning model that predicts the number of times an article will be shared based on its content attributes, social media engagement, and textual properties. By leveraging a dataset from the UCI Machine Learning Repository, we analyze key trends and patterns, train multiple regression models, and evaluate their performance to determine the best approach for predicting news popularity.

Dataset Description

The dataset used in this project is sourced from the UCI Machine Learning Repository and contains metadata related to online news articles. It includes:

Features: Various attributes such as word count, keyword presence, sentiment scores, and publication day.

Target Variable: shares (number of times an article is shared).

Challenges: The dataset contains a high number of features, potential skewness in the target variable, and the need for effective feature selection.


Methodology

To develop an accurate prediction model, the project follows these key steps:

1. Exploratory Data Analysis (EDA) – Understanding data distributions, correlations, and trends.


2. Data Preprocessing – Handling missing values, transforming skewed features, and scaling numerical attributes.


3. Feature Selection – Identifying the most significant variables that influence article popularity.


4. Model Training – Implementing and evaluating multiple regression models.


5. Hyperparameter Tuning – Optimizing the best-performing model for improved accuracy.



Model Selection

Five regression models were implemented and compared based on R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE):

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor


The best model was selected based on overall performance and predictive accuracy.

Results & Insights

Feature Importance: Certain features, such as keyword presence, sentiment polarity, and publication day, showed strong correlations with article popularity.

Model Performance: The Gradient Boosting Regressor and Random Forest Regressor performed best in terms of predictive accuracy.

Challenges: Skewness in the target variable impacted some models, and feature selection played a key role in improving predictions.


Conclusion

This project successfully developed a machine learning model to predict news article popularity based on multiple attributes. The findings highlight key factors that contribute to viral content and provide valuable insights for media professionals looking to optimize article engagement. Future improvements could include incorporating deep learning techniques and additional textual analysis for more precise predictions.


