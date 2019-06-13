# Diabetes

## 1. Introduction

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

    i. Pregnancies: Number of times pregnant
    ii. Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
    iii. BloodPressure: Diastolic blood pressure (mm Hg)
    iv. SkinThickness: Triceps skin fold thickness (mm)
    v. Insulin: 2-Hour serum insulin (mu U/ml)
    vi. BMI: Body mass index (weight in kg/(height in m)^2)
    vii. DiabetesPedigreeFunction: Diabetes pedigree function
    viii. Age: Age (years)
    ix. Outcome: Class variable (0 or 1)


## 2. Description

Source: https://www.kaggle.com/uciml/pima-indians-diabetes-database/downloads/pima-indians-diabetes-database.zip/

Data: Download diabetes.zip from Kaggle.

   #### Problem statement :

    The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic        measurements included in the dataset. 

## 3. Real-world/Business objectives and constraints

    i. No low-latency requirement.    
    ii. Interpretability is important.    
    iii. Errors can be very costly.    
    iv. Probability of a data-point belonging to each class is needed.
    
## 4. Data Overview

   We have one data file: one conatins the information about the diabetes.

   #### Data file information:

        diabetes (Pregnancies,Glucose,BloodPressure,SkinThickness,Insulin,BMI,DiabetesPedigreeFunction,Age,Outcome)
  
 ## 5. Machine Learing Objectives and Constraints
  
   #### Objective:

        Predict the probability of each data-point belonging to two classes.

   #### Constraints:

        i. Interpretability
        ii. Class probabilities are needed.
        iii. Penalize the errors in class probabilites => Metric is Log-loss.
        iv. No Latency constraints.
        
   #### Train, CV and Test Datasets

     Split the dataset randomly into three parts train, cross validation and test with 64%,16%, 20% of data respectively




    
