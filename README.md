# Mid-Course-Assessment---ML-Case-Study
Mid Course Assessment - ML Case Study(Credit Scoring (Banking &amp; Financial Services))


This project aims to develop a machine learning-based credit scoring system for a financial institution to classify customers into three credit risk categories: Good, Poor, or Standard. By leveraging historical financial behavior, loan history, and demographic data, the solution seeks to replace traditional, error-prone methods with a dynamic, interpretable model that improves risk assessment accuracy, reduces defaults, and enables personalized financial services.

Objective : 

* The main objective is to build a predictive model that can classify individuals into different credit score categories (e.g., Bad, Standard, Good) based on the available features. This can assist lenders in making informed decisions regarding credit approvals and risk management.

Data Description : 

* This dataset contains financial and credit-related information for customers, including details about their income, loans, credit behavior, and credit score classification. Below is a structured breakdown of the data:

* ID : Unique identifier for each entry.

* Customer_ID : Unique identifier for each customer.

* Month : The month when the data was recorded.

* Name : Customer's name.

* Age : Customer's age.

* SSN : Social Security Number of the customer.

* Occupation : Customer’s profession.

* Annual_Income : Total yearly income of the customer.  

* Monthly_Inhand_Salary : Net salary received per month after deductions.

* Num_Bank_Accounts : Total number of bank accounts held by the customer.

* Num_Credit_Card : Number of credit cards owned.

* Interest_Rate : Interest rate applied to loans or credits.

* Num_of_Loan : Number of loans taken by the customer.

* Type_of_Loan : Types of loans the customer has.

* Delay_from_due_date : Number of days a payment has been delayed beyond the due date.

* Num_of_Delayed_Payment : Total number of times the customer has delayed a payment.

* Changed_Credit_Limit : Any changes made to the customer's credit limit.

* Num_Credit_Inquiries : Number of times the customer’s credit history was checked.

* Credit_Mix : Composition of various types of credit accounts held by the customer.

* Outstanding_Debt : Total outstanding debt the customer owes.

* Credit_Utilization_Ratio : Ratio of utilized credit to the total available credit.

* Credit_History_Age : Length of the customer’s credit history.

* Payment_of_Min_Amount : Indicates if the customer has paid at least the minimum due amount.

* Total_EMI_per_month : Total Equated Monthly Installment (EMI) paid per month.

* Amount_invested_monthly : Monthly investment by the customer.

* Payment_Behaviour : Pattern of payments made by the customer.

* Monthly_Balance : Available balance in the customer’s account per month.

* Credit_Score (Target Variable) : The customer's credit score categorized as: (Good, Standard, Poor)


**Worked on a Credit Scoring Supervised Classification project to predict customer credit default risk. Cleaned the dataset by handling missing values and removing outliers. Performed EDA, feature selection, and handled class imbalance. Applied Label Encoding for categorical variables during preprocessing. Trained multiple models, including Logistic Regression, XGBoost, Random Forest, and Gradient Boosting. Random Forest achieved the best performance with an accuracy of 0.808. Evaluated models using precision, recall, F1-score, and confusion matrix. Performed hyperparameter tuning using GridSearchCV to optimize the Random Forest model. This project demonstrates the practical application of supervised learning in financial risk analysis.**
