# Heart Disease Prediction using Logistic Regression

This project aims to predict the likelihood of heart disease in individuals based on various health parameters using logistic regression.

## Dataset

The dataset used in this project is given in the files it can be downloaded. The features include:

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol in mg/dl (chol)
- Fasting blood sugar > 120 mg/dl (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- ST depression induced by exercise relative to rest (oldpeak)
- Slope of the peak exercise ST segment (slope)
- Number of major vessels (0-3) colored by flourosopy (ca)
- Thalassemia (thal)

The target variable (label) is the presence of heart disease (target), where 1 indicates the presence and 0 indicates the absence of heart disease.

## Libraries Used

- NumPy
- Pandas
- scikit-learn

## Installation

1. Clone the repository
2. Navigate to the project directory
3. Run the Python script

## Model Evaluation

- The model achieved an accuracy of 0.8512396694214877 on the training data.
- The model achieved an accuracy of 0.819672131147541 on the test data.

## Prediction Example

For example, let's consider an input data point:

- Age: 62
- Sex: 0 (Female)
- cp: 0
- trestbps: 140
- chol: 268
- fbs: 0
- restecg: 0
- thalach: 160
- exang: 0
- oldpeak: 3.6
- slope: 0
- ca: 2
- thal: 2

The model predicts that the person does not have a heart disease.
