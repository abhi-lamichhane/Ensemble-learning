Project Name: Heart Failure Prediction
1. Introduction
Objective: Build and evaluate machine learning models to predict heart failure events from clinical data.

**Workflow: Data preprocessing, EDA, and model training.

2. Dataset Details
Source File: heart_failure_clinical_records.csv

**Key Features:

--age (years)

--anaemia (boolean)

--creatinine_phosphokinase (mcg/L)

--diabetes (boolean)

--ejection_fraction (%)

--high_blood_pressure (boolean)

--platelets (kiloplatelets/mL)

--serum_creatinine (mg/dL)

--serum_sodium (mEq/L)

--sex (binary, male/female)

--smoking (boolean)

--time (days)

---------Target Variable: death_event (boolean)

3. Methodology
Step 1: Data Preprocessing & EDA

- Load data into pandas DataFrame.

- Check for missing values.

- Visualize data distributions (histograms, bar plots).

Step 2: Model Training & Evaluation

-Models Tested:

   Gaussian Naive Bayes (GaussianNB)

   Support Vector Machine (SVM)

   XGBoost (XGBoost)

-Evaluation Metrics:

   classification_report

   confusion_matrix

   ROC curves

4. Technical Requirements
Required Libraries:

-numpy

-pandas

-matplotlib.pyplot

-sklearn (various modules)

-xgboost
