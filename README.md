# Heart Disease Prediction

This project focuses on predicting heart disease using machine learning algorithms. The goal is to build a model that accurately classifies whether a patient is likely to have heart disease based on various medical attributes.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Requirements](#requirements)

## Project Overview
Heart disease remains one of the leading causes of death globally. Early detection is critical in preventing severe outcomes. This project leverages machine learning techniques to create a predictive model that helps in the early diagnosis of heart disease.

## Dataset
The dataset used in this project is the [Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) from the UCI Machine Learning Repository. The dataset includes features such as age, gender, chest pain type, resting blood pressure, cholesterol level, and more.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was conducted to understand the distribution and relationships between different features. The analysis included:
- Visualizing the distribution of each feature
- Investigating the relationships between features and the target variable (heart disease presence)
- Identifying and handling missing values and outliers

## Modeling
Several machine learning models were implemented and evaluated for their performance in predicting heart disease. These include:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)

## Evaluation
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The model performance was further improved through hyperparameter tuning and cross-validation.

## Conclusion
The Random Forest model achieved the highest accuracy in predicting heart disease. This model can be further improved with additional data and feature engineering.

## How to Run
To run this project locally:
1. Clone the repository.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter notebook `Heart_disease.ipynb` and run the cells sequentially.

## Requirements
- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
