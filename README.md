# <p align = 'center'> Predicting and Analysing Customer's Payment Behaviour </p>

## PROBLEM DEFINATION

In this project we have used various machine learning methodologies to predict the borrower's default status using borrower's information and payment behaviors. Used Clustering analysis to segment the portfolio and check if model prediction accuracy improves or not.

The goal of this project is to:

1. Check credit card holder's behaviors, trends and factors to identify default risks.
2. Predicting if borrower is going to default in next month or not given all the borrower and payment information.
3. Using cluster analysis to segment the portfolio so that we can improve the model prediction accuracy for each segment.
4. Checking techniques to make a prediction.
5. Assessing if clustering helps us to improve the model performance or not.


## DATA DESCRIPTION

This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

The dataset was collected from kaggle - <a href = "https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset">Default of Credit Card Clients Dataset</a>

There are 25 variables:

1. ID: ID of each client
2. LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
3. SEX: Gender (1=male, 2=female)
4. EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=unknown, 6=unknown)
5. MARRIAGE: Marital status (1=married, 2=single, 3=others)
6. AGE: Age in years
7. PAY_0: Repayment status in September, 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay 8. for two months, … 8=payment delay for eight months, 9=payment delay for nine months and above)
9. PAY_2: Repayment status in August, 2005 (scale same as above)
10. PAY_3: Repayment status in July, 2005 (scale same as above)
11. PAY_4: Repayment status in June, 2005 (scale same as above)
12. PAY_5: Repayment status in May, 2005 (scale same as above)
13. PAY_6: Repayment status in April, 2005 (scale same as above)
14. BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
15. BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
16. BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
17. BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
18. BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
19. BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
20. PAY_AMT1: Amount of previous payment in September, 2005 (NT dollar)
21. PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
22. PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
23. PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
24. PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
25. PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
26. default.payment.next.month: Default payment (1=yes, 0=no)


## QUESTIONS TO PERFORM DATA EXPLORATION:

1. How does the probability of default payment vary by categories of different demographic variables?
2. Which variables are the strongest predictors of default payment?