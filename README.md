# Predictive-Analytics-Diabetes
A Predictive ML project to analyze and predict the likelihood of diabetes from other parameters such as Age, Smoking History, BMI, HbA1c Level, Blood Glucose Level, etc.

## 1. Project description
### Context and goals
Likelihood of having diabetes could depend on various aspects like medical history and demographic information. This dataset can be used to build machine learning models to predict diabetes in patients based on their medical history and demographic information. This can be useful for healthcare professionals in identifying patients who may be at risk of developing diabetes and in developing personalized treatment plans. 

### Dataset information
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
<br> The Diabetes prediction dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). The data includes features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level. 

## 2. Summary of project stages
### Stage 1: Data cleaning and preparation
- Data overview
- Data cleaning
- Dealing with imbalanced data by doing oversampling
- Label encoding to deal with categorical columns

### Stage 2: Predictive analysis with the Random Forest machine learning algorithm
-  Selection of dependent and independent variables
- Dataset splitting into training and test subsets
- Feature engineering with correlation matrix
- Feature selection with recursive feature elimination and cross-validation
- Hyperparameter tuning of a random forest model with cross-validation
- Training and evaluation of the model with the best hyperparameters on the training data with cross-validation
- Validation of the model on the test subset
- Conclusions

