#  Predicting Whether The Customer Will Subscribe To Term Deposit or NOT .

## Introduction

The purpose of the banking system is to provide an easy way for people to pay for goods and services, save their money, and transfer money between accounts. Banking systems provide credit opportunities, facilitate fund flow into the economy, ensure financial generation for public development and growth, and provide payment options.



## Problem Statement

A banking institution wants to develop a model that predicts whether a customer will subscribe to a term deposit or not based on their banking behaviour. They have collected a dataset of past customers with information about their demographics, account details, and whether they subscribed to a term deposit or not. The bank wants to build a model using Logistic Regression to predict whether a new customer will subscribe to a term deposit or not based on their banking behaviour.
The dataset used for this problem statement is the "Bank Marketing Data Set" which contains information on customers of a bank. The dataset includes 17 attributes such as customer demographics, account details, and whether the customer subscribed to a term deposit or not. Each customer is classified as either yes or no based on whether they subscribed to a term deposit or not.



#### What is a Term Deposit?
A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. Term deposits can be invested into a bank, building society or credit union.

When the money is deposited, the customer understands that the money is there for the pre-determined period which usually ranges from 1 month to 5 years and the interest rate is guaranteed not to change for that nominated period of time. Typically, the money can only be withdrawn at the end of the period – or earlier with a penalty attached.

Term deposits are popular with investors who prefer capital security and a set return as opposed to the fluctuations of, say, the share market. Many investors also use term deposits as a part of their investment mix.For more information with regards to Term Deposits please click on this link from Investopedia: https://www.investopedia.com/terms/t/termdeposit.asp


here some  files:

1. train.csv : Use this dataset to train the model. This file contains all the client and call details as well 
as the target variable “subscribed”. You have to train your model using this file.

2. test.csv : Use the trained model to predict whether a new set of clients
will subscribe the term deposit.

### Dataset Attributes

Here is the description of all the variables :

- Variable: Definition
- ID: Unique client ID
- age: Age of the client
- job: Type of job
- marital: Marital status of the client
- education: Education level
- default: Credit in default.
- housing: Housing loan
- loan: Personal loan
- contact: Type of communication
- month: Contact month
- day_of_week: Day of week of contact
- duration: Contact duration
- campaign: number of contacts performed during this campaign to the client
- pdays: number of days that passed by after the client was last contacted
- previous: number of contacts performed before this campaign
- poutcome: outcome of the previous marketing campaign

##### Output variable (desired target):
- Subscribed (target): has the client subscribed a term deposit?

## Tools and Algorithms Used for Analysis

- Python
- Numpy
- Pandas
- Seaborn
- Logistic Regression


## References


