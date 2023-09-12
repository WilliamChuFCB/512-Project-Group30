# 512-Project-Group30

You can access our final poster through this link:

https://drive.google.com/file/d/1Ml1MfTAIw7xN3TVXJ-WYjdseweOm55ZK/view?usp=drive_link

## Introduction

In such an era when the economic recession caused by the COVID-19 pandemic and the great turbulence of global geopolitics has dominated the world, more and more people are worried about their employment situations, hoping that their salaries can be raised to at least offset the pressure from the severe inflation recently. Also, new graduates panic about if they can be employed after graduation. In this case, it is practical to find out the factors that determine the salaries as well as the likelihood of being employed.

## Data Description

In this project, we used three different datasets sequentially from macro to micro. The first dataset “Per Capita Income by County (2021) vs. Education” contains the average personal income and education level of all the counties in the US. The second dataset originates from a US Census database, where each row is consist of different dimensions of information from a single person, such as education level, race and occupation. The target variable indicates whether a person’s income exceeds $50K. The third data is collected from an MBA program in India tracking the placement status as well as salaries of their new graduates. The dataset includes various background information of students such as their grades from secondary school to the MBA program, gender, major, and so on.

## Data science questions

- Are there differences in average income among states in the US?
- Is education level highly related to people’s income?
- What is the relationship between students’ academic performances and their employment status?
- What other factors affect people’s income？

## Methods

- Constructed a linear regression model with personal income per capita as the dependent variable
- Trained a classifier with different machine learning models, including Logistics Regression, XGBoost, SVM and Naive Bayes,  to predict the income category based on Census data
- Examined the feature importance when predicting the salary and likelihood of placement with Gini index and impurity
- Predicted the likelihood of being placed and salary with random forest classifier and random forest regressor
- Used Artificial Neural Networks (ANN) with the Multi-Layer Perceptron (MLP) Classifier method to classify salary categories

