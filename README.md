# Loan Eligibility Prediction
A machine learning project to predict loan eligibility of a person based on their income and other factors. The model uses the Support Vector Machine (SVM) algorithm to classify whether a person is eligible for a loan or not. The model has been trained and tested on a loan dataset which consists of 614 rows and 13 columns.

## Prerequisites
Before running the code, make sure you have the following libraries installed:

Numpy

Pandas

Seaborn

Scikit-learn

### You can install these libraries using the following pip command:
![image](https://user-images.githubusercontent.com/102272183/218292532-47882113-7d8f-4e7c-acd5-91c1f7260918.png)

## Project Flow
The code follows the following steps to classify the loan eligibility of the applicants:

1.Load the dataset into a Pandas DataFrame.

2.Handle missing values by dropping the rows with missing values.

3.Label encoding the target variable (Loan_Status).

4.Plotting the data to understand the relationship between different features and target variable.

5.Replace categorical data with numerical values to make it suitable for training the model.

6.Split the data into training and testing datasets.

7.Train the Support Vector Machine (SVM) model.

8.Evaluate the model on the training and testing data to check the accuracy.

9.Load the test data and repeat the steps from 3 to 8 to classify the loan eligibility of test data.

## Data Preparation
The data used in this project is loan-train.csv and loan-test.csv which are loaded into pandas DataFrames. The data contains missing values which are dropped from the dataset. The categorical columns are label-encoded and numerical values are used to train the model.

## Model Training
The data and labels are separated, and the model is trained on 90% of the data. The accuracy of the model on the training data is 79.86%. The accuracy of the model on the test data is 83.33%.

## Real Test Data
The real test data is loaded into a pandas DataFrame and the same pre-processing steps are applied to it. The model is used to predict the loan eligibility of the test data.

## Conclusion
The accuracy of the model is 83.33% on the test data, which means it can correctly classify the loan eligibility of 83.33% of the applicants. However, further tuning and improvement can be made to increase the accuracy of the model.
