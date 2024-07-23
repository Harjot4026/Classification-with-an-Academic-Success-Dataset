# Classification-with-an-Academic-Success-Dataset
Kaggle Competition

 

# Classification of Academic Success

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
  

## Introduction
 The goal of this competition is to predict academic risk of students in higher education.

## Dataset
The dataset used for this project contains information about students' academic records and personal characteristics. The key columns in the dataset are:

- `id`: Unique identifier for each student
- `Marital status`: Marital status of the student
- `Application mode`: Mode of application
- `Application order`: Order of application
- `Course`: Course enrolled by the student
- `Daytime/evening attendance`: Whether the student attends during the day or evening
- `Previous qualification`: Previous qualification of the student
- `Previous qualification (grade)`: Grade in the previous qualification
- `Nacionality`: Nationality of the student
- `Mother's qualification`: Qualification of the student's mother
- `Father's qualification`: Qualification of the student's father
- `Mother's occupation`: Occupation of the student's mother
- `Father's occupation`: Occupation of the student's father
- `Admission grade`: Admission grade of the student
- `Displaced`: Whether the student is displaced
- `Educational special needs`: Whether the student has special educational needs
- `Debtor`: Whether the student is a debtor
- `Tuition fees up to date`: Whether the student's tuition fees are up to date
- `Gender`: Gender of the student
- `Scholarship holder`: Whether the student is a scholarship holder
- `Age at enrollment`: Age of the student at enrollment
- `International`: Whether the student is international
- `Curricular units 1st sem (credited)`: Number of credited curricular units in the 1st semester
- `Curricular units 1st sem (enrolled)`: Number of enrolled curricular units in the 1st semester
- `Curricular units 1st sem (evaluations)`: Number of evaluations in the 1st semester
- `Curricular units 1st sem (approved)`: Number of approved curricular units in the 1st semester
- `Curricular units 1st sem (grade)`: Grade in the 1st semester
- `Curricular units 1st sem (without evaluations)`: Number of curricular units without evaluations in the 1st semester
- `Curricular units 2nd sem (credited)`: Number of credited curricular units in the 2nd semester
- `Curricular units 2nd sem (enrolled)`: Number of enrolled curricular units in the 2nd semester
- `Curricular units 2nd sem (evaluations)`: Number of evaluations in the 2nd semester
- `Curricular units 2nd sem (approved)`: Number of approved curricular units in the 2nd semester
- `Curricular units 2nd sem (grade)`: Grade in the 2nd semester
- `Curricular units 2nd sem (without evaluations)`: Number of curricular units without evaluations in the 2nd semester
- `Unemployment rate`: Unemployment rate during the period of study
- `Inflation rate`: Inflation rate during the period of study
- `GDP`: Gross Domestic Product during the period of study
- `Target`: Academic success (0: Fail, 1: Pass)
 

## Feature Engineering
Feature engineering techniques applied in this project include:

- Handling missing values
- Encoding categorical variables
- Creating new features based on domain knowledge
- Scaling numerical features

## Modeling
Various classification models have been experimented with, including:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier
- LightGBM Classifier
- CatBoost Classifier
- Neural Networks

  
Hyperparameter tuning has been performed using techniques such as Grid Search and Random Search to optimize model performance.

## Evaluation
The models are evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results
Getting rank at 241 out of 2642 on the test set.

 
