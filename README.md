# Heart Disease Prediction

This project involves building a machine learning model to predict the likelihood of heart disease in patients. The project leverages various data preprocessing techniques and employs a Logistic Regression model to make predictions. The model's performance is evaluated using accuracy metrics.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Modeling](#modeling)
- [Results](#results)
- [How to Use](#how-to-use)

## Project Overview
The primary goal of this project is to develop a predictive model that can accurately classify whether a patient is likely to have heart disease based on specific health indicators. This model is particularly useful for early detection and preventive care in the healthcare industry.

## Dataset
The dataset used in this project contains features such as age, cholesterol levels, and blood pressure, among others. It is split into training and testing sets to evaluate the performance of the model.

## Project Structure
The notebook follows this structure:
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling features.
2. **Model Training**: Training a Logistic Regression model on the training data.
3. **Model Validation**: Evaluating the model's accuracy using the test data.
4. **Model Saving**: The trained model is saved as `saved_model.sav` for future use.

## Modeling
- **Algorithm Used**: Logistic Regression
- **Training Process**: The model was trained on the preprocessed dataset using a Logistic Regression classifier.
- **Evaluation**: The accuracy of the model was calculated using the `accuracy_score` metric from `sklearn`.

## Results
The model achieved an accuracy of **91.44%** on the test data, indicating a strong ability to predict heart disease cases.

## How to Use
1. Run the Jupyter notebook `Heart_disease.ipynb` to preprocess the data, train the model, and make predictions.
2. The trained model is saved in the file `saved_model.sav`. You can load this model and use it for prediction tasks on new data.
