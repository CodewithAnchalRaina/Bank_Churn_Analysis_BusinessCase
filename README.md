**What is Customer churn ?**

Customer churn is the percentage of customers that stopped using your company's product or service during a certain time frame.

**Project Objective:**

The objective of this analysis is to discover various factors contributing to increased customer churn rate at the bank, and provide the business users with these insights which they can use to make informed decisions and strategize on how to improve customer retention and reduce churn rate.
 
The raw data was provided in the form of a CSV file with 10,000 rows of data. Data was sourced from a commercial bank who was looking to improve its customer churn rate.
 
**Data Contains:**

customer_id: This is the customers’ unique id which identifies them.
credit_score: this is the rating of the customer's credit Score.
country: This is the country the customer Come from.
gender: This is the sex of the customer, grouped into male and female.
age: This refers to the customer’s age.
tenure: The number of years of relationship this customer has maintained with the bank.
balance: The deductible balance on their bank account as at time this data was generated.
products_number: This shows the bank account type the customer has.
credit_card: This column shows if a customer has a credit card or not, represented as either 1 or 0 respectively.
active_member: These numerical values show whether an account is active or not, represented as either 1 or 0 respectively.
estimated_ salary: This is the average annual salary received into the account.
churn: This field shows if the customer is still with the bank or not, represented by either 0 or 1 respectively.

**Note:-The data provided by the business user is only that of salary-earning customers**

**1.Insights**

Those customer with credit card facility, the churn rate is highest amongst lowest credit score group of >400' 

Customer having age between 51-60 have very high Churn rate which is 56.2%

Surprisingly, the customers whose account balance are <=200k and in between 1k-10k are the most churned in terms of account balance.

Female Churn Rate is higher as compare to Male
Churn rate of country france and Germany have higher churn rate where Spain have lowest churn rate

**2. Recommendation**

The stakeholders could consider creating products that target seniors close to their early retirement age to avoid losing them.
An incentive program could be considered for customers who have maintained longer relationship with the bank.
In the same way, an exclusive package such as travel and vacation packages, subsidized investment portfolio, e.t.c., could be considered for the customers in the >200k account balance group, to reduce the rate at which they leave the bank.
The business needs to understand why there is 100% churn rate for Prod 2 customers with account balance of 1k-10k and how to get them back in business.
In Summary, age group of 51–60, people with low credit scores and those with high account balance (>200k) are most likely to churn. The bank should consider the recommendations above and other effective strategies that can address the findings, to better customer retention and reduce chrun rate.

**3. Conclusion**

In this Power BI analysis, I went through some major data analysis process to get the data from raw to cleaned and onto building the report, ensuring data quality across board. Most importantly, it provided valuable insights into some of the major factors that encourage customer churn at the bank.
With this report, the stakeholders can better manage the churn situation (specifically for salaried customers), by focusing on the key factors and evaluating the results of their changes periodically
