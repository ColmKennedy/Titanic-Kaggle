# Titanic-Kaggle

This project is a work in progress. The goal of this project is to create a machine learning pipeline to predict an individual's survival after the sinking of the Titanic (https://en.wikipedia.org/wiki/Sinking_of_the_Titanic). These predictions will then be submited to the Titanic - Machine Learning from Disaster competion on Kaggle (https://www.kaggle.com/competitions/titanic).

Stages:
1. Exploratory Data Analysis
2. Preprocessing
3. Modeling
4. Validation/Testing
5. Feature Engineering
6. Prediction

Contents:
* eda.ipynb - Exploratory Data Analysis Notebook (EDA). Contains all EDA, will later be merged with scikit_workflow to create one project notebook. Currently in a drafting stage.
* preprocessing.ipynb - Using information from EDA, cleans data, feature engineering. This is a first draft of scikit_workflow.
* scikit_workflow.ipynb - Creates a baseline model with no feature engineering. This is a draft of changing my workflow to use pipelines in sklearn. This is meant to be a more streamlined, second iteration, of the notebook: preprocessing.ipynb. This will later be merged with eda.ipynb to create one whole analysis/prediction project.
