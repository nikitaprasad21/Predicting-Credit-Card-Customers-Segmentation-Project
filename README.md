# Predicting-Credit-Card-Customers-Segmentation-Project

### Introduction

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

### Work Process

• Performed Attrition Analysis for 25K Credit Card Users using SQL to identify factors contributing to churn rate across different countries.
• Developed Customer Churning Analysis Visualizations, identified critical patterns ofroot causes behind attrition using Tableau.
• Deployed Supervised ML Models to improve retention rate achieving accuracy of 75.28% on test data for Random Forest Classifier(RFC).


### Tools Used

* Excel for Data Cleaning
* Tableau for creating dashboard
* SQL for analysis
* Python for Model Building 


### Analytics

#### Below is the dashboard I created to better understand dataset.

![Screenshot 2023-04-11 170828](https://user-images.githubusercontent.com/84131752/231197672-95e68421-88a9-4257-845b-1b876c9fccb6.png)

Based on the analysis of the dashboard, the following key conclusions can be drawn:

1. **Repayment Behavior:** The data reveals that over 50% of the customers have successfully repaid the minimum credit amount, indicating a positive repayment behavior. This highlights the creditworthiness and reliability of a significant portion of the customer base.
2. **Age and Credit Score:** There is a notable correlation between age and credit score. Customers within the age range of 20-50 exhibit good credit scores, suggesting a positive credit history and responsible financial behavior within this demographic segment.
3. **Credit Score by Occupation:** The analysis indicates variations in credit scores based on occupation. Media Managers tend to have good credit scores, reflecting their financial stability and responsible credit management. On the other hand, Entrepreneurs exhibit lower credit scores, possibly due to the higher financial risks associated with entrepreneurship.

Based on the conclusions drawn from the analysis, the following recommendations can be made:

1. **Encourage Timely Repayments:** Since more than 50% of customers have successfully repaid the minimum credit amount, it is important to promote and incentivize timely repayments. Implement strategies such as offering rewards, discounts, or credit score-based benefits to encourage customers to maintain positive repayment behavior.
2. **Target Age-Specific Credit Products:** Recognizing the correlation between age and credit score, consider developing tailored credit products that cater to the specific needs and preferences of customers within the 20-50 age range. Offer competitive interest rates, flexible repayment options, and customized benefits to attract and retain customers in this demographic.
3. **Provide Financial Education for Entrepreneurs:** Given that entrepreneurs exhibit lower credit scores, it is essential to provide financial education and support to this customer segment. Offer resources, workshops, or personalized guidance to help entrepreneurs manage their finances effectively, improve their credit scores, and mitigate financial risks associated with their ventures.
4. **Develop Occupation-Specific Credit Solutions:** Capitalize on the insight that media managers tend to have good credit scores by designing occupation-specific credit solutions tailored to their needs. This may include specialized credit programs, exclusive benefits, or targeted marketing campaigns to attract media managers as valued customers.

### Credit Score Classification Model 

#### I have deployed Supervised Machine Learning Models to improve retention rate with accuracy of 85.19% on test data for Bagging Classifier.

### Conclusion

By implementing these recommendations, the business can enhance customer repayment behavior, cater to specific age-related credit needs, provide valuable financial education, and develop occupation-specific credit solutions. These initiatives will contribute to improved credit scores, customer satisfaction, and long-term financial stability for both customers and the business.
