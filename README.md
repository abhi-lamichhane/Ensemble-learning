**Heart Failure Prediction Model
This project aims to build and evaluate machine learning models to predict the likelihood of heart failure events based on a patient's clinical records.

**Problem Statement
The goal is to use a dataset of clinical records to create and test machine learning models for classifying heart failure risk. The project involves data preprocessing, exploratory data analysis (EDA), and model training using several algorithms.

**Dataset
The model is trained on the heart_failure_clinical_records.csv dataset, which contains clinical parameters for patients.

**Columns
The dataset includes the following features:

age: Age of the patient (years)

anaemia: Decrease of red blood cells or hemoglobin (boolean)

creatinine_phosphokinase: Level of the CPK enzyme in the blood (mcg/L)

diabetes: If the patient has diabetes (boolean)

ejection_fraction: Percentage of blood leaving the heart at each contraction (percentage)

high_blood_pressure: If the patient has hypertension (boolean)

platelets: Platelets in the blood (kiloplatelets/mL)

serum_creatinine: Level of serum creatinine in the blood (mg/dL)

serum_sodium: Level of serum sodium in the blood (mEq/L)

sex: Sex of the patient (binary, 1 for male, 0 for female)

smoking: If the patient smokes or not (boolean)

time: Follow-up period (days)

death_event: The target variable, indicating if the patient died during the follow-up period (boolean)

**Methodology
The project follows a standard machine learning workflow, including the following steps:

1. Data Preprocessing and EDA

   
Importing the data from heart_failure_clinical_records.csv into a pandas DataFrame.

Displaying the dimensions (rows and columns) of the dataset.

Checking for and handling any missing values.

Performing statistical analysis and visualization, such as histograms for continuous features and bar plots for binary features, to understand data distribution.


2. Model Training and Evaluation

   
The notebook trains and evaluates the following machine learning models:

Gaussian Naive Bayes (GaussianNB)

Support Vector Machine (SVM)

XGBoost (XGBoost)

Model performance is analyzed using metrics like classification_report, confusion_matrix, and ROC curves to inform cost-benefit decisions.

Required Libraries
This project requires the following Python libraries:

numpy

pandas

matplotlib.pyplot

sklearn.model_selection

sklearn.preprocessing

sklearn.naive_bayes

sklearn.svm

sklearn.tree

xgboost

sklearn.metrics
