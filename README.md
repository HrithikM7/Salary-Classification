# Salary-Classification

## Quick Intro
Enclosed is a Jupyter Notebook which uses various Machine Learning Models to predict whether a person makes over $50K a year.

## Problem Statement
The extraction of data has been done Barry Becker from the 1994 Census database.
Based on the various columns available (i.e Age, Education, Race, Hours worked per week, etc...), our task is classify an employee into 2 categories: 
* &gt;=50K 
* <50K 

## Approach
I used several features (College GPA, SAT Scores, etc...) to predict our target variable (student success) and split the data into tresting and training groups. I then created a naive baseline to which I would compare my machine earning models against. I implemented several machine learning algorithms such as Random Forest, Logistic Regression, Support Vector Machine and Neural Networks to model and fit our data. To quantify our models I used the metrics of model accuracy, model classification report (F1 Score, Precision, Accuracy Between Classes, Recall), model confusion matrix, model ROC Curve and AUC score.

## Result
In this notebook I implemented Logistic Regression, Random Forest, Support Vector Machine and Neural Network models for a machine learning supervised classification task. The best result using only institutional variables : Random Forest w/ AUC Score: 0.7669, Model Accuracy Score : 83.46%, F1 Score : 0.79

## Importance
The use of machine learning and data mining techniques has exploded in recent years with the field of educational data mining making significant growth in the past two decades. No work has been done at this institution, a primarily undergraduate institution with a variety of ethnic backgrounds. This work will serve as the baseline for all future Machine Learning work at this institution. Predicting student success has many use cases and will ultimately benefit both the students and professors in creating instructional techniques/habits that will gear students towards better/more efficient course performance.

