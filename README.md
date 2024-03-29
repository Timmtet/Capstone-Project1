# Capstone-Project1

Table of Content

1. Project Overview

2. Data Files

3. Technical Overview

4. Requirements

5. Results


1. Project Overview

In this project, we were provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

This project was divided into three steps, namely:

a. Customer Segmentation using unsupervised learning: In this part a thorough data analysis and feature engineering steps were performed to prepare the data for further steps. A Principal Component Analysis (PCA) was also performed for dimensionality reduction. Then K-Means Clustering was performed on the PCA components to cluster the general population and the customer population into different segments. These clusters were studied to determine what features make a customer with the help of cluster weights and component weights.

b. Customer Acquisition using supervised learning: Here, the previous analysis  was used to build a machine learning model that predicts whether or not each individual will respond to the campaign.

c. Kaggle Competition - This used the chosen model to make predictions on the campaign data as part of a Kaggle Competition to see how it measures up to the other peoples's work.


2. Data Files

There were four data files provided by Arvato for this project. The last file was created by the user. As part of the terms and conditions of Arvato, the files cannot be shared in this repository. However, they can be described below.

azdias.csv - Demographics data for the general population of Germany - 891,211 persons (rows) x 366 features (columns)

customers.csv - Demographics data for customers of a mail-order company - 191,652 persons (rows) x 369 features (columns)

mailout_train.csv - Demographics data for individuals who were targets of a marketing campaign (train) - 42,982 persons (rows) x 367 (columns)

mailout_test.csv - Demographics data for individuals who were targets of a marketing campaign (test) - 42,833 persons (rows) x 366 (columns)

feat_info.csv - Contains a summary of properties for each demographics data column created by the user - 366 features (rows) x 4 (columns) 


3. Technical Overview

The analysis was divided into various steps which include:

Data Exploration 

Data Wrangling

Feature Engineering

Dimensionality Reduction

Clustering

Supervised Learning

Model Evaluation

Predictions on Test data

Kaggle Submission

4. Requirements

All of the requirements are given in requirements.txt. To install Run: pip install -r requirements.txt

5. Results

The results have been clearly documented in the Jupyter Notebook. Please refer Arvato Project Workbook.ipynb.

The blog post for this project can be found in the link below:
https://medium.com/@akintilotimileyin/capstone-project-customer-segmentation-5f2844515909
