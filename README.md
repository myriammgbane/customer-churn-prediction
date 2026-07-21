# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn is a key challenge for businesses, as losing customers can negatively impact revenue and long-term customer relationships. This project applies machine learning techniques to predict customer churn using the Acme Telephonica dataset.

The aim of this project was to develop classification models that could identify patterns associated with customer churn and evaluate how predictive analytics can support targeted customer retention strategies.

## Objectives

The objectives of this project were to:

- Explore customer data to identify factors associated with churn.
- Clean and preprocess data for machine learning analysis.
- Develop and compare multiple classification models.
- Evaluate model performance and consider the business implications of predictive insights.

## Dataset

The project used the Acme Telephonica customer dataset, containing customer information and attributes related to service usage and account behaviour.

The dataset was analysed to understand patterns between customer characteristics and churn outcomes.

## Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Data Preparation

The dataset was prepared for machine learning by:

- Cleaning and preprocessing customer data.
- Preparing features and target variables.
- Splitting data into training and testing datasets.
- Transforming data into a suitable format for classification models.

## Exploratory Data Analysis

Exploratory data analysis was conducted to investigate customer characteristics and identify patterns related to churn.

Visualisations were used to understand relationships within the dataset and support interpretation of model results.

## Machine Learning Models

Three classification models were developed and compared:

### Logistic Regression

A statistical classification approach used to predict the likelihood of customer churn based on customer features.

### Decision Tree

A tree-based classification model used to identify decision patterns within customer data.

### K-Nearest Neighbours (KNN)

A distance-based classification algorithm used to classify customers based on similarities within the dataset.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These evaluation methods were used to assess both overall model performance and how effectively each model identified customers at risk of churn.

## Results & Findings

The models achieved similar levels of predictive performance, with K-Nearest Neighbours achieving the highest overall accuracy.

| Model | Accuracy |
| --- | --- |
| Logistic Regression | 54.55% |
| Decision Tree | 52.35% |
| K-Nearest Neighbours (KNN) | 56.11% |

Although KNN achieved the highest accuracy, further evaluation showed that performance varied across different classification metrics. This highlights the importance of considering measures beyond accuracy when applying machine learning to customer churn problems.

The results demonstrated that customer churn prediction is a challenging task, and model effectiveness depends heavily on the quality and relevance of available customer data.

## Business Insights

The project highlights how machine learning can support customer retention strategies by identifying customers who may be at risk of leaving.

Potential business applications include:

- Developing targeted retention campaigns.
- Improving customer engagement strategies.
- Supporting data-driven decision-making.

## Conclusion

This project demonstrated how machine learning can be applied to a real-world business problem through predictive analytics.

The findings highlight the importance of selecting appropriate evaluation methods and understanding the limitations of predictive models. While machine learning can provide valuable insights into customer behaviour, improving prediction performance may require additional customer information, feature engineering, or more advanced modelling techniques.
