# PIMA_Diabetes_study

Before diving deep into the project, let's understand the problem statement and the data given to us.
Our Objective: build a model to accurately predict whether the patients in the dataset have diabetes or not.

# Dataset: Available in the project GitHub dir.

The dataset consists of several medical predictor variables and one target variable, Outcome.
Predictors:
     Pregnancies: Number of times pregnant
     Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
     blood pressure: Diastolic blood pressure (mm Hg)
     SkinThickness: Triceps skin fold thickness (mm)
     Insulin: 2-Hour serum insulin (mu U/ml)
     BMI: Body mass index (weight in kg/(height in m)^2)
     DiabetesPedigreeFunction: Diabetes pedigree function     Age: Age (years)
     Outcome: Class variable (0 or 1) 268 of 768 is 1, the others are 0

From the data description, we can point out some of the features and make certain assumptions:
The data set is not normalized, i.e., different features (variables) have other units of measurement. We will need to Standardize the dataset
Based on eight features/variables, we have to predict the "Outcome"(Target variable)
