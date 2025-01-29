# ICU-Moratality-Predictions--Machine-Learning

## Predicting Patient Survival with Machine Learning

#### Team Members:
Brinda Asuri, Pranav Garg, Soham Bidyadhar, Grayson Merritt, Tom Starkie

### Project Overview
Accurate mortality predictions are essential for timely medical interventions and optimal resource allocation in ICUs. Traditional severity scoring systems, like APACHE, struggle with generalization across diverse healthcare settings.
This project leverages machine learning (ML) techniques to develop a robust hospital mortality prediction model using a globally diverse dataset.

### Objectives
- Develop an ML model to accurately predict ICU patient survival.
- Create a universal severity scoring system applicable across different hospitals and countries.
- Compare the ML model's performance against APACHE scores.

### Data Collection
Dataset:
- Source: GOSSIS Consortium (Argentina, Australia, New Zealand, Bangladesh, India, Nepal, Sri Lanka, Brazil, USA)
- Size: 380,280 patients from 385 hospitals (91,713 rows subset available on Kaggle)
  
Collected Features:
- Vital Signs: Blood pressure, heart rate, oxygen saturation, etc.
- Lab Results: Blood tests, metabolic panels, etc.
- Admission Diagnoses & Demographics
- Glasgow Coma Scale (GCS), Chronic Conditions
- Collected within the first 24 hours of ICU admission

### Exploratory Data Analysis (EDA)
Feature Engineering:
- Dropped IDs, missing values, and unimportant categories.
- Compressed Comorbidities & Glasgow Coma Scale (GCS) into total score variables.
- Principal Component Analysis (PCA) for dimensionality reduction.
- Standardized numerical features using StandardScaler.
- Label encoding categorical variables.

### Model Development
Trained ML Models
- Logistic Regression (with class weighting)
- Decision Tree Classifier
- Random Forest
- XGBoost
- CatBoost
- Support Vector Machines (SVM)
- Naïve Bayes
- Multi-Layer Perceptron (MLP) Neural Network
- Stacking Classifier (Ensemble)





