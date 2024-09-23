1. Project Title :
Customer Churn Analysis

2. Introduction :
This project aims to analyze customer churn data to identify patterns and insights that could help reduce churn and optimize business strategies. By analyzing customer tenure, payment 
methods, and service usage, the model provides actionable insights to improve customer retention and minimize revenue loss.

3. Problem Statement :
 Implement a strategy for tracking customer journey, identifying patterns related to churn, predicting who is likely to churn, take pre-emptive actions to prevent future churns.

4. Dataset :
i used dataset from kaggle : https://www.kaggle.com/blastchar/telco-customer-churn
it's include : Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents.

5. Methodology :
- Data Exploration:
Analyzed customer churn data, which includes features like tenure, payment methods, types of services, and monthly charges.
Identified significant patterns and correlations between churn behavior and key variables such as contract type, internet service, and the number of services subscribed.
- Data Preprocessing:
Handled missing data, performed data normalization, and encoded categorical variables.
Grouped customers by services and payment methods to better understand the factors contributing to churn.
- Visualization:
Created visualizations to examine the relationships between churn status and various features such as monthly charges, payment methods, contract type, and tenure.
Bar charts, heatmaps, and boxplots were used to show churn tendencies.
- Churn Analysis:
Applied segmentation analysis to pinpoint customer groups more prone to churn (e.g., customers with month-to-month contracts or those using electronic checks).
Investigated how service type (e.g., fiber optic internet) affects churn rates.
- Predictive Modeling :
Implemented Logistic Regression model to predict customer churn with accuracy 80%.

6. Results :
- 26% of customers churn, which results in a 31% monthly revenue loss for the company.
- 53% of customers with month-to-month contracts and using electronic check payment methods are more likely to churn.
- 41% of churned customers use fiber optic internet services.
- Churn customers with multiple services tend to pay higher monthly charges compared to non-churn customers with multiple services.
- Targeting the 53% of customers who use month-to-month contracts and electronic checks for retention efforts could significantly reduce revenue loss up to 16%.
  
7. Conclusion : 
This analysis of customer churn provides valuable insights that can help the business reduce revenue loss. By identifying specific customer segments at high risk of churn, such as those with month-to-month contracts and electronic check payments, the business can implement targeted retention strategies. Furthermore, addressing the needs of high-paying customers with multiple services could help improve customer satisfaction and reduce churn rates. With these insights, the company can take proactive measures to reduce churn, increase customer loyalty, and protect revenue.






