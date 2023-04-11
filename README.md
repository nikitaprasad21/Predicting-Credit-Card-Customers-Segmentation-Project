# Predicting-Credit-Card-Customers-Segmentation-Project

## Introduction

#### The credit score of a person determines the creditworthiness of the person. It helps financial companies determine repayment of the loan or credit customers are applying for. In this project I have done analysis using SQL, developed Dashboard using Tableau and created classification model using Python to identify and predict hidden patterns and trends from records.

##### Below are all the features in the dataset:

###### Customer_ID: Unique ID of the customer
###### Age: The age of the person
###### Gender: Customers Gender
###### Geography: Geographical Location
###### Occupation: The occupation of the person
###### Annual_Income: The Annual Income of the person
###### Monthly_Inhand_Salary: Monthly in-hand salary of the person
###### Num_Bank_Accounts: The number of bank accounts of the person
###### Num_Credit_Card: Number of credit cards the person is having
###### Interest_Rate: The interest rate on the credit card of the person
###### Num_of_Loan: The number of loans taken by the person from the bank
###### Type_of_Loan: The types of loans taken by the person from the bank
###### Delay_from_due_date: The average number of days delayed by the person from the date of payment
###### Num_of_Delayed_Payment: Number of payments delayed by the person
###### Credit_Mix: Classification of Credit Mix of the customer
###### Outstanding_Debt: The outstanding balance of the person
###### Credit_Utilization_Ratio: The credit utilization ratio of the credit card of the customer
###### Credit_History_Age: The age of the credit history of the person
###### Payment_of_Min_Amount: Yes if the person paid the minimum amount to be paid only, otherwise no.
###### Payment_Behaviour: The payment behaviour of the person
###### Monthly_Balance: The monthly balance left in the account of the person
###### Credit_Score: The credit score of the person
###### Status : Existing and Attrited Customers

##### The Credit Score is the target variable in this problem. Based on this criteria banks classify credit scores and train a model to classify the credit score of a person.

## Analytics

#### Below is the dashboard I created to better understand dataset.

![Screenshot 2023-04-11 170828](https://user-images.githubusercontent.com/84131752/231197672-95e68421-88a9-4257-845b-1b876c9fccb6.png)

#### The 3 important conclusions made from the above dashboard are mentioned as follows:
* More tahn 50% of the Customer has done the repayment of the Minimum Credit Amount.
* Credit Score of people with age range between 20-50 has a good Credit Score. 
* Credit Score of Media Manager lies in Good Category whereas for Entrepreneur lies in Poor Category.

## Credit Score Classification Model 

#### I have deployed Supervised Machine Learning Models to improve retention rate with accuracy of 75.28% on test data for Random Forest Classifier (RFC).
