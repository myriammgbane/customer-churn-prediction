# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer retention is a key challenge for businesses, as losing customers can directly impact revenue and long-term growth. This project applies machine learning techniques to predict customer churn and identify customers who may be at risk of leaving.

Using the Acme Telephonica customer dataset, this project explores how predictive modelling can support data-driven decision-making and help organisations develop targeted customer retention strategies.

## Objectives

The main objectives of this project were to:

- Analyse customer data to identify patterns associated with churn.
- Clean and prepare data for machine learning modelling.
- Develop classification models to predict customer churn.
- Compare model performance and evaluate their suitability from a business perspective.

## Tools & Technologies

- **Programming Language:** Python
- **Environment:** Google Colab
- **Data Analysis:** Pandas, NumPy
- **Data Visualisation:** Matplotlib
- **Machine Learning:** Scikit-learn

## Data Preparation

The dataset was prepared for machine learning through:

- Data cleaning and preprocessing.
- Preparing features and target variables.
- Splitting the dataset into training and testing sets.
- Transforming data into a format suitable for classification models.

## Exploratory Data Analysis

Exploratory analysis was conducted to understand customer characteristics and identify patterns linked to churn.

Analysis included:

- Examining customer attributes and their relationship with churn.
- Visualising trends within the dataset.
- Identifying potential factors influencing customer retention.

## Machine Learning Models

Three classification models were developed and compared:

### Logistic Regression
A statistical classification model used as a baseline approach for predicting customer churn.

### Decision Tree
A tree-based model used to identify patterns and decision rules within customer data.

### K-Nearest Neighbours (KNN)
A distance-based classification algorithm used to compare customer similarities and predict churn outcomes.

## Model Evaluation

The models were evaluated using multiple classification metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics were used to assess overall model performance while considering the importance of correctly identifying customers who were likely to churn. F1-score was particularly useful as it balances precision and recall, providing a more reliable measure for an imbalanced classification problem.

## Results & Findings

The three models achieved moderate predictive performance, with differences across evaluation metrics.

While KNN achieved strong overall accuracy, Logistic Regression provided a more balanced performance across precision, recall and F1-score, making it more suitable for identifying customers at risk of churn.

The results demonstrate that the best-performing model should not be selected based on accuracy alone. For customer churn prediction, correctly identifying potential churners is a key business objective, making recall and F1-score important considerations.

## Business Insights

The project highlights how machine learning can support customer retention strategies by identifying customers who may be at risk of leaving.

Potential business applications include:

- Targeting customers with personalised retention offers.
- Improving customer engagement strategies.
- Using predictive insights to support proactive decision-making.

## Conclusion

This project demonstrates how machine learning can be applied to solve a real-world business problem through predictive analytics.

The findings highlight the importance of selecting appropriate evaluation methods, as accuracy alone may not always reflect the usefulness of a model in a business context. Identifying customers likely to churn requires models that balance overall performance with the ability to detect churn cases effectively.

Future improvements could include incorporating additional customer data, applying feature engineering techniques, and testing more advanced machine learning approaches to improve predictive performance.
