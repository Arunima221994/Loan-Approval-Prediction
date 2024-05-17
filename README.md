# Loan-Approval-Prediction
An end to end data analysis project on Retail industry data, doing EDA, Correlation analysis, prediction using Binary Classification. The following tasks have been performed:
# Steps:
	1.Gathering Data
	2.Exploratory Data Analysis
	3.Data Visualizations
	4.Machine Learning Model Decision.
	5.Traing the ML Model
	6.Predict Model
	7.Deploy Model

 The data was imported and read doing an initial feature analysis. The data was cleaned as required e.g. looking for null values, duplicate values, handling them, reduce redundancy in features etc. EDA was performed on the data with the help of visualisation. Correlation between the features was done and the important features on which the credit card loan approval status is highly corelated. Finally we chose the highly correlated feature values and trained and machine learning model to predict the upcoming sales of the store given all other features.

We used pandas,numpy, matplotlib, seaborn, scikit learn libraries and packages in our project.

# Understanding the problem statement : 
Dream Housing Finance company deals in all kinds of home loans. They have a presence across all urban, semi-urban and rural areas. The customer first applies for a home loan and after that, the company validates the customer eligibility for the loan.

The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling out online application forms. These details are Gender, Marital Status, Education, number of Dependents, Income, Loan Amount, Credit History, and others.

# EDA: Univariate Analysis

1. More Loans are approved Vs Rejected

2. Count of Male applicants is more than Female

3. Count of Married applicant is more than Non-married

4. Count of graduate is more than non-Graduate

5. Count of self-employed is less than that of Non-Self-employed

6. Maximum properties are located in Semiurban areas

7. Credit History is present for many applicants

8. The count of applicants with several dependents=0 is maximum.

# Bivariate Analysis: 
The mean value of Loan Amount applied by males (0) is slightly higher than Females(1).

If you are married then the loan amount requested is slightly higher than non-married.

Male have higher Co-applicant income than females in all three property areas.

# Multivariate Analysis: 
Correlation has been performed and as a result- there is a highly correlation with credit history on getting the loan appproval status

# Feature Analysis 
1. While doing the correlationI get to know which parameters are highly correlated with the "Loan status"

2. Loan sttaus is majorly correlated 65% with credit hostory

3. Here we took most of high and medium correlated features like, credit history, self employees, annual income, property area

# Binary Classification Model:

The goal of this section is to build a model that, given certain features====We have used multiple algorithms for training purposes like Decision Tree, Random Forest, Logistic Regression.

1. Select the features to be used in the model

2. Split between training and test sets

3. Scale numerical variables

4. Evaluate the model and claffify the problem


# Logistic regression performs best on the validation data with an accuracy score of 76%.




