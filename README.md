# Telco-Churn-analysis
![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSdF2Cx3s03z6zgLHICWGdpEmZdTbxhneRgwg&usqp=CAU)

Customer churn is the loss of customers,also called customer attrition. In this project, I analyse the data and examine any patterns that may arise while deriving actionable insights on the churn rate.

## Introduction
Customer churn  is the number of paying customers who fail to become repeat customers. churn is a quantifiable rate of change that occurs over a specified amount of time. It is also called customer attrition.A high churn means that a higher number of customers no longer want to purchase goods and services from the business.
Churn rate is calculated by dividing the number of customers you lost during that time period by the number of customers you had at the beginning of that time period. It is natural to lose customers. However, it is important to keep the churn rate low as it costs more to acquire new customers than it does to retain existing customers. 

## The Dataset

I downloaded the data from Kaggle https://www.kaggle.com/datasets/blastchar/telco-customer-churn . The raw data contains 7043 rows (customers) and 21 columns (features). Each row represents a customer, each column contains customer’s attributes described on the column Metadata.The dataset has information on:
1. Customer ID which is the unique identifier.
2. Demographic information - This has the customer's gender,whether they have a partner, dependents or is a senior citizen.
3. Customer information - This has details on the tenure,whethet they have phone service, multiple lines, tech support, internet service, Online security, online back up, device protection, streaming TV and  streaming movies.
4. Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges.
5. Churn - Customers who left within the last month.

## Summary of the analysis

I downloaded the data to a google worksheet and used power querry to clean and transform the data. I replaced the 'No' on the churn column with Active and 'Yes' with Inactive to make it easily understandable. The Telco had a total of 7043 customers with 5174 being active while 1869 were inactive. This gave a churn rate of 27%.

### Customers with a longer contract remained active  for long while those with a month-month contract had the highest churn rate.
![image](https://user-images.githubusercontent.com/118395584/233087094-0a371e68-b2f6-45d0-9809-b71909632dfa.png)

### Customers with phone service remained active  for long.
![image](https://user-images.githubusercontent.com/118395584/233087454-443da4fe-8d8d-4682-a959-e99036273c4c.png)

### Customers with multiple lines remained active for long and there was little variance between males and females
![image](https://user-images.githubusercontent.com/118395584/233087638-e6261912-1dc9-49d0-abbf-0324309522ca.png)

### Electronic check users had the highest churn rate while Credit card users had the lowest
![image](https://user-images.githubusercontent.com/118395584/233087848-b71750cf-c9c8-4237-a3a2-547b7404d100.png)

### Customers with no partner and dependents had a higher churn rate
![image](https://user-images.githubusercontent.com/118395584/233088055-0084cace-50e6-423c-bcd9-a2e9811d3848.png)

## Reccomendations

1. Analyze churn as it occurs. This will enable the Telco to identify and resolve issues as they arise and effectively reduce the 27% churn rate.
2. Ask your customers the right question. This is by taking customer feedback surveys that will help make informed decision and timely changes.
3. Offer more to your loyal customers. This can be through long term discounts that are beneficial to both the customer and the company.
