# Predict-Credit-Consumption-of-Customer-For-Leading-Bank

Business Context:
Analytics driving every industry based on a variety of technology platforms which collect information
from various sources by analysing what customers certainly want. The Credit Card industry is also
data rich industry and data can be leveraged in infinite ways to understand customer behaviour.
The data from a credit card processor shows the consumer types and their business spending
behaviours. Therefore, companies can develop the marketing campaigns that directly address
consumers’ behaviour. In return, this helps to make better sales and the revenue undoubtedly grows
greater sales.
Understanding the consumption pattern for credit cards at an individual consumer level is important
for customer relationship management. This understanding allows banks to customize for
consumers and make strategic marketing plans. Thus it is imperative to study the relationship
between the characteristics of the consumers and their consumption patterns.
Business Objectives:
One of the leading banks provided below data
a. Customer Demographics
b. Customer Behavioural data (information on liabilities, assets and history of transactions with
the bank for each customer). Data has been provided for a particular set of customers' credit
card spend in the previous 3 months (April, May & June) and their expected average spend
in the coming 3 months (July, August & September)
c. Credit consumption

Data Dictionary
a. CustomerDemographics.csv
ID – Customer ID - Unique ID for every Customer
Account_type - Account Type (current or saving)
Gender- Gender of customer (M or F)
Age - Age of customer
Income – Income Levels (High/Medium/Low)
Emp_Tenure_Years – Experience – Employment Tenure of customer in Years
Tenure_with_Bank – Number of years with bank
Region_code Code assigned to region of residence (has order)
NetBanking_Flag – Whether customer is using net banking for the transactions
Avg_days_between_transaction – Average days between two transactions
b. CustomerBehaviorData.csv
ID – Customer ID - Unique ID for every Customer
CC_cons_apr - Credit card spend in April
DC_cons_apr - Debit card spend in April
CC_cons_may - Credit card spend in May
DC_cons_may - Debit card spend in May
CC_cons_jun - Credit card spend in June
DC_cons_jun - Debit card spend in June
CC_count_apr - Number of credit card transactions in April
CC_count_may - Number of credit card transactions in May
CC_count_jun - Number of credit card transactions in June
DC_count_apr - Number of debit card transactions in April
DC_count_may - Number of debit card transactions in May

DC_count_jun - Number of debit card transactions in June
Card_lim - Maximum Credit Card Limit allocated
Personal_loan_active - Active personal loan with other bank
Vehicle_loan_active - Active Vehicle loan with other bank
Personal_loan_closed - Closed personal loan in last 12 months
Vehicle_loan_closed - Closed vehicle loan in last 12 months
Investment_1 - DEMAT investment in june
Investment_2 - Fixed deposit investment in june
Investment_3 - Life Insurance investment in June
Investment_4 - General Insurance Investment in June
Debit_amount_apr - Total amount debited for April
Credit_amount_apr - Total amount credited for April
Debit_count_apr- Total number of times amount debited in april
Credit_count_apr - Total number of times amount credited in april
Max_credit_amount_apr - Maximum amount credited in April
Debit_amount_may - Total amount debited for May
Credit_amount_may - Total amount credited for May
Credit_count_may - Total number of times amount credited in May
Debit_count_may - Total number of times amount debited in May
Max_credit_amount_may - Maximum amount credited in May
Debit_amount_jun - Total amount debited for June
Credit_amount_jun - Total amount credited for June
Credit_count_jun - Total number of times amount credited in June
Debit_count_jun - Total number of times amount debited in June
Max_credit_amount_jun - Maximum amount credited in June
Loan_enq - Loan enquiry in last 3 months (Y or N)
Emi_active - Monthly EMI paid to other bank for active loans
c. CreditConsumptionData.csv
ID – Customer ID - Unique ID for every Customer
cc_cons (Target) - Average Credit Card Spend in next three months

Note: Some customers are having missing values for credit consumption. You need to build
the model using customer’s data where credit consumption is non- missing’s. You need to
predict the credit consumption for next three months for the customers having missing
values.


Model Evaluation Metric:
You should validate model using Root Mean Square Percentage Error (RMSPE) between the
predicted credit card consumption and Actual Credit Consumption.
Expected Outputs:
a. Detailed code with comments
b. Data Exploratory analysis
c. Model validation outputs
d. Model documentation with all the details
e. Predicted values for customers where target variable having missing values
