# Bertelsmann/Arvato Project

## Table of Contents

1. Installation
2. How to run the notebook
3. Project Motivation
4. File Descriptions
5. Results
6. Licensing, Authors, and Acknowledgements

#### 1. Installation

In order to run the code you should count with the following libraries: 
numpy,pandas,matplotlib, seaborn, pickle, json, sklearn, imblearn, xgboost

#### 2. How to run the notebook

Open the "Arvato Project Workbook.ipynb" and go to cell>run all. Make sure the files "list_in_dict.pkl" and "dictionary_nulls.json" are in the same folder

#### 3. Project Motivation

The purpose of this project is to create a machine learning model to determine whether or not people in the general population of Germany are likely to be 
customers of a mail-order company. Demographic variables will be used for this analysis along with household, building, and neighborhood information. 
The ultimate goal is to improve the efficiency of the new customer acquisition process to make decisions based on data.

### 4. File Descriptions

By confidentiality agreement, the data cannot be openly shared. However, there are 4 inputs that were used for this project which are:

- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

### 5. Results

Two machine learning models were created: one for customer segmentation with the k-means algorithm and another for classification with the Gradient Boosting Classifier 
algorithm. The clustering model makes it possible to identify the segments of the general population of Germany that are most similar to current customers. 
The classification model makes it possible to establish whether or not the person is likely to be a client of the company.

### 6. Licensing, Authors, and Acknowledgements

I must give credit to Bertelsmann/Arvato for providing the data.
