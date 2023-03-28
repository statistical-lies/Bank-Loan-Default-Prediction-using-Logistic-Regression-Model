# DATA-SCIENCE-AND-MACHINE-LEARNING
Bank Loan Prediction

# INTRODUCTION

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
