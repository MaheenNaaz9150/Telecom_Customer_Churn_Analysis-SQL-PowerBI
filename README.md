# Telecom_Customer_Churn_Analysis ( SQL + PowerBI )

# Overview

This project focuses on analyzing customer churn in a telecom company, aiming to find the main reasons for customer loss. Using SQL for data analysis and Power BI for visualizations, it provides insights into customer behavior, helping to develop effective retention strategies.

# Objective

1. Uncover underlying patterns that contribute to customer churn within the telecom sector.
2. Explore the relationship between diverse customer attributes and their likelihood of leaving.
3. Generate strategic recommendations aimed at enhancing customer retention and loyalty.

# Dataset
The analysis is based on a comprehensive dataset ( telecom_customer_churn.csv) collected from kaggle of telecom customers, including demographics, service usage patterns, billing information, and churn status.

 **Tools
. SQL Scripts** : Contains all SQL queries used for data analysis.
**. Power BI Dashboard:** An interactive dashboard providing insights into customer churn.

**Insights**

1. The database contains 7,043 customers.
2. Among all customers in the database, 26.54% belong to the “Churned” category, totaling 1,869 lost customers.
3. Older customers (average age of 50 years) are more likely to leave the company, while newer customers are younger (average age of 43 years).
4. There is no correlation between the customer’s gender and the “Churned” status, as half of the customers in this category are female (49.76%) and half are male 
   (50.24%).
5. Among the customers classified as “Churned”, 64.21% are not married, while the remaining 35.79% are married.
6. Of the customers classified as “Churned”, 95% do not have children, while 5% do. This ratio is not observed in the same way in other categories, where 30% of 
   “Stayed” users have children, and 17.62% of newly “Joined” users have children. There is a significant difference for users who leave the company and have children.
7. Users who leave the company have an average referral score of 0.52, while users who stay with the company have an average of 2.61, and new users have an average of 
   0.95.
8. Offer E is provided to new users and has the highest “Churned” rate, while for customers who stay with the company, the most popular offer is Offer B.
9. The average time for customers to leave the company is approximately 18 months.
10. Both customer statuses have the same average monthly long-distance charge.
11. Both customer statuses are balanced in terms of having more than one line or not.
12. The internet service is subscribed to by 94% of customers classified as “Churned”, 75% of “Stayed” users have internet service, and 60% of newly “Joined” users 
    subscribe to the internet service upon joining the company.
13. The primary method of using the internet service is via fiber optic.
14. Customers who leave the company have the lowest average monthly download (GB).
15. Of the customers who leave (“Churned”) and join (“Joined”) the company, 83% do not have online insurance service, while 48% of users who stay with the company 
    have the online security service.
16. Of the customers who leave the company (“Churned”), 70% do not have an online backup service. Of the newly joined customers (“Joined”), 80% do not have an online 
    backup service. And of the customers who stay with the company (“Stayed”), only about 47% do not have this type of service.
17. Of the customers who leave the company (“Churned”), 69% do not have a device protection plan. Of the newly joined customers (“Joined”), 88% do not have a device 
    protection plan. And of the customers who stay with the company (“Stayed”), only about 47% do not have this type of service.
18. Of the customers who leave the company (“Churned”), 82% do not have premium technical support. Of the newly joined customers (“Joined”), 82% do not have premium 
    technical support. And of the customers who stay with the company (“Stayed”), only about 48% do not have this type of service.
19. All streaming services have the same adoption rate (about 50%) for the “Churned” and “Stayed” customer categories, suggesting there is no correlation between 
    subscribing to streaming services and the decision to leave or stay with the company.
20. Unlimited data plans are adopted at the same rate by both customer classes, suggesting there is no correlation with customer churn.
21. The most common type of contract for new customers and those who leave the company is monthly, while about 67% of customers who stay with the company have a 
    contract of at least one year.
22. Customers who leave the company (“Churned”) are the ones who spend the most on average per month.


