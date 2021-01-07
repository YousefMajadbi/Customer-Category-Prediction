# Customer-Category-Prediction

## Introduction
**Customer Segmentation** is the process of partitioning a customer base into groups of individuals that have similar characteristics ("Clustering them").

A Telecommunication provider has segmented its customer base by service usage patterns, categorizing the customers into four groups:
<ol>
  <li>Basic Service.</li>
  <li>E-Service.</li>
  <li>Plus Service.</li>
  <li>Total Service.</li>
</ol>

## Problem Description
If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers. It is a classification problem. That is, given the dataset, with predefined labels, we need to build a model to be used to predict class of a new or unknown case.

## Objective
Our objective is to build a classifier, to predict the class of unknown cases.
So, we need to determine which classification algorithm would be the best suited to create our model.

## Data
We are going to use a dataset pulled out from the telecommunication company database, and we ensured that it does not contains any PII. Here is the file [teleCust1000t.csv](https://github.com/YousefMajadbi/Customer-Category-Prediction/blob/main/teleCust1000t.csv)

The example focuses on using demographic data, such as region, age, and marital, to predict usage patterns.

The target field, called **custcat**.

## Methodology
- Exploratory Data Analysis.
- Data Visualization.
- Data Wrangling.
- Supervised Machine Learning.
- Classification.
- Model Evaluation.

## Technologies
- Python.
- Jupyter.
- Pandas.
- Numpy.
- Seaborn.
- Matplotlib.
- scikit-learn.

## Results
Considering the following **Evaluation Metrics** we can rely on **Logistic Regression Algorithm** as the most appropriate classifier to build our model.
#### Evaluation Metrics: 
- Accuracy Score.
- Jaccard Score.
- F1 Score.
- Log Loss. 
