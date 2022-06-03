# Sparkify-project
### Building Customer Churn Predictive Model Using SPARK

 This repository contains the results of the Data Science Nanodegree Sparkify Capstone Project. Its main porpouse is to analyze raw data provided by a music app called Sparkify and predict if the users will churn or not based on their behaviour. For that, using the Pyspark environment, we cleaned the data, perfomed EDA, extracted features and trained Machine Learning Models.  More information can be found on a [Medium Blog Post](http).


## Table of Contents
  - Installation
  - Project Motivation
  - Files Description
  - Result
  - Licensing, Authors, and Acknowledgements
  
  
## Installation
  
    This project uses the following software and Python libraries:

    Python
    Spark
    Pyspark
    pandas
    Matplotlib
    Seaborn

You will also need to have software installed like Anaconda to run and execute a Jupyter Notebook.

## Project Motivation

#### developing Skills of:

- Loading large datasets into Spark and manipulating them using Spark SQL and Spark Dataframes
- Using the machine learning APIs within Spark ML to build and tune models
- Integrating the skills I've learned in the Spark course and the Data Scientist Nanodegree program

## Files Description

- Sparkify.ipynb Notebook is the main file of the project.
- It demonstrates the process of using pyspark to explore the data and build the model.

## Result
We Split the data into train and test sets , built a transformation pipeline and trained four Machine Learning models(Logistic Regression, Random Forest, Decision Trees and Gradient-Boosted Trees).
Since the churned users are a fairly small subset, we used F1 score as the metric to optimize and found that GBTClassifier was the best one to predict if a user will churn. 


## Licensing, Authors, Acknowledgements

Must give credit to Udacity for the project. And instructions in the notebook are also well prepared by Udacity team.
