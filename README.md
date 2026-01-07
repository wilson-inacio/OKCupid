![OKCupid Banner](./OKCupid.jpg)
# OKCupid - Date a scientist!


# Overview
The aim of this project is to perform exploratory data analysis on a dataset containing user profiles from the OKCupid dating platform, followed by data cleaning, transformation, and machine learning modeling to make predictive inferences.


## Library Dependencies
`Python`: 3.11+ (Anaconda)<br>
`Pandas`: 2.3.3<br>
`Numpy`: 2.3.5<br>
`Matplotlib`: 3.10.7<br>
`SciKit-Learn`: 1.6.1


# Project Objectives
In this project I load, analise, clean and transform data from a dataset so it can be used with machine learning algorithms. With those algorithms we aim to make a few predictions that allow us to answer questions like:
* Which profile features are the most predictive of self-reported gender on OKCupid?
* Can lifestyle and demographic features predict whether a user owns pets?
* How accurately can a user's income be predicted based on demographic features?
* Which features consistently matter most across different prediction tasks and models?


# Dataset
The data used in this project was provided by [Codecademy](http://codecademy.com) and consists of one file named `profiles.csv` where each row corresponds to a user and each column is a response to one of the profile questions, and those can be either multiple choice or short answer.

## About the Dataset
The dataset is composed of 59,946 rows, where each row is a different user of the dating app, and 31 columns, which correspond to the responses the user inputs during profile creation.
The columns (also known as features) are:

|Feature|Description|
|---|---|
|age|The age of the user|
|body_type|Self-reported body type|
|diet|Type of diet that the user follows|
|drinks|Whether a user ingests alcoholic beverages|
|drugs|Whether a user uses recreational drugs|
|education|The user's education level|
|essay...|Series of open-ended short answers about users' likes and dislikes|
|height|User's self-reported height|
|income|User's income approximation|
|job|The user's occupation|
|last_online|Information about the last time the user was active on the app|
|location|The user's location|
|offspring|Whether the user has children|
|orientation|The user's sexual orientation|
|pets|Whether the user has pets|
|religion|The user's religious preference|
|sex|The user's self-reported gender|
|sign|User's zodiac sign|
|smokes|Whether a user smokes|
|speaks|List of languages the user speaks|
|status|The user's marital status|


# Index
1. Introduction
   - Main Questions
   - Data Sources
2. Scope
   - Project Goals
   - Data
   - Analysis
   - Evaluation
3. Exploratory Data Analysis
   - Importing Relevant Libraries
   - Loading the Data
   - Exploring the Data
4. Prediction Algorithms
   1. Which profile features are the most predictive of self-reported gender on OKCupid?
   2. Can lifestyle and demographic features predict whether a user owns pets?
   3. How accurately can a user's income be predicted based on demographic features?
   4. Which features consistently matter most across different prediction tasks and models?
5. Conclusion
   - Key Insights
   - Recommendations and Next Steps
  

# Conclusion
- Body type and occupation are consistently among the strongest predictors across tasks.
- Lifestyle features (diet, drinking, smoking) show moderate but stable predictive power.
- Linear models offer interpretability but limited performance on complex targets like income.

## ## Reproducibility Note
This project was developed in a Jupyter Notebook environment using Anaconda.  
Random seeds were fixed where applicable to ensure reproducibility.
