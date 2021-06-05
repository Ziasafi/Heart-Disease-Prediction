# Heart Disease Prediction System Using Machine Learning


The objective of this project is to predict heart disease using machine learning algorithms. The project involved 2 classification models using scikit-learn: Logistic Regression, and  Support Vector Classifier Model to investigate their performance on heart disease datasets obtained from the UCI data repository. 
I've used above mentioned Machine Learning algorithms, implemented in Python, to predict the presence of heart disease in a patient. This is a classification problem, with input features as a variety of parameters, and the target variable as a binary variable, predicting whether heart disease is present or not.


# Dataset Introduction


In this project, A model for classification of given dataset (heart.csv) has been proposed. This dataset
has 14 attributes (age, sex, cp trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal,
target) and 1025 obersvations. The ‘target’ field refers where the patient has heart disease or not.
This is a binary classification problem as our target has two integer values 0(has no heart disease)
and 1(has heart disease). In our dataset we have Discrete, Nominal, Ordinal, and continuous
attributes.Following document outlines walkthrough of process that was followed for the
completion, discusses model trials, comparison of their performance and the reasoning of final
model selection


# Pre-Analysis
1. Target variable had class labels instead of continuous data hence we decided to treat this as
a classification
2. None of the observation had any missing value, so data imputation was not implemented
3. Class distribution was in original data was fairly balanced. There seems to be no considerable
over-representation or underrepresentation of any class


Dataset used: https://www.kaggle.com/ronitf/heart-disease-uci


The choice of model was logistic regression with accuracy of 86.34% and the accuracy of Support vector machine
was 83.9%. Logistic regression performed well on heart disease dataset.


How to run the Jupyter notebook?

**How to set it up?**

pip install -r requirements.txt

**How to run the code?**

Run Jupyter notebook



