# Salary-Classification

## Quick Intro
Enclosed is a Jupyter Notebook which uses various Machine Learning Models to predict whether a person makes over $50K a year.

## Dataset
* Download the dataset for custom training.
* https://archive.ics.uci.edu/ml/datasets/Census+Income 

## Problem Statement
The extraction of data has been done Barry Becker from the 1994 Census database.
Based on the various columns available (i.e Age, Education, Race, Hours worked per week, etc...), our task is classify an employee into 2 categories: 
                                                                                                                                                    * &gt;=50K 
                                                                                                                                                    * <50K 

## Approach
I used several features (i.e Age, Education, Maritial Status, etc...) to predict our target variable (i.e Salary) and split the data into training and testing datasets.
I tried to cover every step of the machine learning pipeline while making this project. I started out by performing basic EDA to get more insight about the data at hand. Following which, Feature encoding, Feature selection, and Feature scaling were performed before training the model. I implemented several machine learning algorithms such as Decision Tree, Random Forest, Logistic Regression, KNN, and Gradient Boosting to model and fit the data. GridSearchCV was used to perform hyperparameter tuning to get the best parameters for each algorithm used. To quantify the models, I used the metrics of accuracy_score and model confusion matrix. 

## Result
In this notebook I implemented Decision Tree, Random Forest, Logistic Regression, KNN and Gradient Boosting for a machine learning supervised classification task. The best result that was obtained was : Decision Tree w/ Model Accuracy Score : 84.869%

## Importance
The field of machine learning has seen a tremendous growth over the past few years, and is only going to grow further in the future. 
Predicting the salary of an employee has many use cases and will ultimately benefit both the employees as well as the recruiters who are responsible for hiring new candidates to a company. This model can be used to even check whether a particular employee is being over-paid or under-paid.

## Authors

Hrithik Maddirala  
[@hrithik_m245](https://www.linkedin.com/in/hrithik-maddirala/)


<img src="DSC_0037-01-01.jpeg" width="100">
