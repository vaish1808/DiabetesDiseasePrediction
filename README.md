# Diabetes Disease Prediction
## Introduction
Diasense is a website that not only predicts risk associated with the diabetes but also offers vital information on diabetes such as its
types, symptoms, causes, recommended exercises, and dietary advice thus serving as an informative and diagnostic
platform. Dataset was used to train ML model (i.e Logistic Regression) to predict the result based on various deciding factors. The predicted result is 80% accurate.

## Dataset
I gathered the dataset from Kaggle, link for the same is https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

## Required Libraries
The libraries required for this project are:<br>
• Numpy (to perform logical/mathematical operations on arrays/matrices)<br>
• Pandas (data analysis & manipulation)<br>
• sklearn (Machine learning library).

## Preprocessing the dataset
• Check for missing data : As sometimes if values are missing it might create error while training model. <br>
• Co-relation matrix : used to find co-relation b/w various columns. <br>
• Heat map : Since results of co-relation are not that clear so to visualise it in better manner we plot heat map....darker the color, least is the co-relation, outcome least dependent on bp & most on glucose. <br>
• Training &amp; testing model : Created 2 variables X (independent columns) &amp; Y(Dependent column). 80% data training &amp; 20% data
testing. <br>
• To increase accuracy : use different train to test ratio, normalize data
&amp; change classifier.

## Logistic Regression
It is a type of statistical analysis used to model and
analyze relationships between a dependent variable and one or more
independent variables. It is commonly used in machine learning and data
science for binary classification tasks, where the goal is to predict a
binary outcome (e.g., true/false, yes/no, 1/0)

## Tech Stack
HTML, CSS, Javascript, Python, Django, Machine Learning


https://github.com/vaish1808/DiabetesDiseasePrediction/assets/140848722/59c10cc1-d4b5-4867-8148-0e7c301647e9

https://github.com/vaish1808/DiabetesDiseasePrediction/assets/140848722/204952e7-a8b7-4b85-afbd-1ada13c6ad6a


https://github.com/vaish1808/DiabetesDiseasePrediction/assets/140848722/c83bb326-5d0c-4a59-9416-8123fd9828ea




