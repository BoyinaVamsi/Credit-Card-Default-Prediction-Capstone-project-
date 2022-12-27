# Credit-Card-Default-Prediction-Capstone-project-
# Introduction
Credit risk plays a major role in the banking industry business. Banks main sources for income are granting loans through various schemes, credit card, investment, mortgage, and others. Credit card has been one of the most booming financial services by banks over the past years. However, with the growing number of credit card users, banks have been facing an escalating credit card default rate.With a large number of banks selling credit cards, the phenomenon of credit card default emerges one after another. It is very important for banks to effectively identify high-risk credit card default users.

# Problem Statement
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

# Attributes Information
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

ID: Customer ID

LIMIT_BAL: Amount of the given credit: it includes both the individual consumer credit and his/her family (supplementary) credit.

Gender: Type of gender Male/Female/Others. (1 = male; 2 = female).

Education: Education level (1 = graduate school; 2 = university; 3 = high school; 4 = others).

Marriage: Married/Un-married (1 = married; 2 = single; 3 = others).

Age: Age of the card holder in years.

PAY_0 to PAY_6: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: Pay_0 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;Pay_6 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

BILL_AMT1-BILL_AMT6: Amount of bill statement (NT dollar). BILL_AMT1 = amount of bill statement in September, 2005; BILL_AMT2 = amount of bill statement in August, 2005; . . .; BILL_AMT6 = amount of bill statement in April, 2005.

PAY_AMT1-PAY_AMT6: Amount of previous payment (NT dollar). PAY_AMT1 = amount paid in September, 2005; PAY_AMT2 = amount paid in August, 2005; . . .;PAY_AMT6 = amount paid in April, 2005.

Default: describes the customers who may default.

