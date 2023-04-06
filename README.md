# Bank Loan Prediction

#INTRODUCTION

A loan default occurs when a person(known as a borrower) takes money from a bank and he/she is not able to repay the loan. People often fail to repay(default) loans due to some personal or various reason after the loan has been acqured.people who are not able to repay their loans does not only damage their risk of being
sued in court but somethings also put their families in debt or on edges of losing a valueable family properties like houses,lands,cars etc. Banks or financial institutions somethings loses huge sums of their financial assets after their borrowers are not able to fulfill their end of the bagain.
Although it is quite profitable and beneficial for both the lenders and the borrowers. However, it carries a great risk, which in the domain of loan lending is referred to as Loan risk. Industry experts and researchers around the world assign individuals with numerical scores known as credit scores to measure the risk and their
creditworthiness.

let take a closer look at types of loan.
A Secured Loan: with this kind of loan the individual uses his/her own asset as collateral, the lender can take the asset if the person does not repay the loan.

An Unsecured Loan: this type does not requires any collateral, they usually have high interest rates compared to secured loans because they are very risky to the lender.

An Installment Loan: this kind is repaid with fixed amount in a particular set period

Types of loans by purpose
1. Personal Loan
2. Auto Loan 
3. Student Loan
4. Mortgage Loan 5.Home Equity Loans
5. Credit-Builder Loans etc


# Methodology
The dataset is made up of simulated from Kaggle with loan acquired from a financial institution, with both the borrower paying at the end of the stated period and not paying at the end of the stated period. The total number of loan is 850, with 265 borrowers not paying at the end of the stated period and 585 customers paying on time. The dataset contain 6 columns ('age', 'ed', 'employ', 'address', 'income','status') of which addresses are irrelevant in fitting the model.

age= age of the borrower ed=education level of the borrower employ= number of employment of the borrower 

income=income level of the borrower in thousands

status= status of either settled on time or not 

0= settled loan on time

1=did not settle loan on time

Binary Logistc Regression model was used for making the prediction

# Confusion Matrix
Confusion matrix is used to evaluate classification models.Classification models categorize the outcome into two or more categories in our case whether the customer will pay the loan amount on time or not

![1_umiim1SOOriOGA2izJJn1A](https://user-images.githubusercontent.com/59277986/228695552-25389030-cdba-4bb1-b33d-8b88b284f34b.png)
![download](https://user-images.githubusercontent.com/59277986/228700203-9b392eec-ce8c-4bca-a678-605b6817fb98.png)


Explanation:

True Positive: actual category and predicted category are both positive. Number of times the model correctly classified an status as default.

True Negative: actual category and predicted category are both negative. Number of times the model correctly classified an status as no-default.

False Positive: actual category is negative and predicted category is positive. Number of times the model classified an status as default, when it is actually not-default.

False Negative: actual category is positive and predicted category is negative. Number of times the model classified an status as not-default, when it is actually default.

# 1.1e+02=110

There are several statistical measures we can derive:

# 1.Overall accuracy: TP + TN / Total No. of Records

110 + 0 / (54+0+3+110) = 65.868%

This is a general measure of the model performance.

# 2. Sensitivity or Recall: TP / (TP + FN)

110 / (110 + 3) = 97.3451%

This measures the proportion of actual positives that the model correctly classifies.

# 3. Specificity: TN / (FP + TN)

0/ (54 + 0) = 0%

This measures the performance of the model in predicting negative outcome.

# 4. Precision: TP / (TP + FP)

110 / (110 + 54) = 67.07 %

This measures the accuracy of predicted positive outcome
