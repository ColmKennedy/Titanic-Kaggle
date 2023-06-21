# Titanic-Kaggle

## Introduction

This project is a work in progress. The goal of this project is to create a machine learning pipeline to predict an individual's survival after the sinking of the Titanic (https://en.wikipedia.org/wiki/Sinking_of_the_Titanic). These predictions will then be submited to the Titanic - Machine Learning from Disaster competion on Kaggle (https://www.kaggle.com/competitions/titanic). 

## Mission Statement

My focus in this project is to establish my own workflow and machine learning pipeline, in order to participate in more advanced Kaggle competitions. I chose this competition, specifically, because it is a common beginner competition, with plenty of documentation and references online. 

## Stages:

1. Exploratory Data Analysis
2. Preprocessing
3. Modeling
4. Validation/Testing
5. Feature Engineering
6. Prediction

## Contents:

* eda.ipynb - Exploratory Data Analysis Notebook (EDA). Contains all EDA, will later be merged with scikit_workflow to create one project notebook. Currently in a drafting stage.
* preprocessing.ipynb - Using information from EDA, cleans data, feature engineering. This is a first draft of scikit_workflow.
* scikit_workflow.ipynb - Creates a baseline model with no feature engineering. This is a draft of changing my workflow to use pipelines in sklearn. This is meant to be a more streamlined, second iteration, of the notebook: preprocessing.ipynb. This will later be merged with eda.ipynb to create one whole analysis/prediction project.


## Predictions

Currently, I have made four submissions to this competition. All of these models are based on Random Forest Classifiers. The most recent, submission_4.csv, achieved a public score of 0.76076. This represents predictions of survival with about 76% success. There is still much room for improvement. The next steps will focus on feature engineering, then attempting different types of modeling.
