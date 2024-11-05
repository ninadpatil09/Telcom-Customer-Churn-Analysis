# Telcom Customer Churn Analysis 

## Project Overview

### Objective: 
This project aims to analyze customer behavior and identify factors contributing to churn, helping the company design focused retention strategies to retain customers and increase customer loyalty.

### Requirement: 
The goal is to predict churn and provide insights that can lead to effective customer retention programs. By examining various customer demographics, account details, and service preferences, we can pinpoint key drivers of churn and propose actionable strategies to reduce it.

### Data Used

The dataset includes:

- Customer Churn Data: Indicates whether a customer left in the last month.
- Service Data: Details on services each customer subscribed to, such as phone, multiple lines, internet (DSL/Fiber), online security, online backup, device protection, tech support, streaming services, etc.
- Account Information: Length of tenure, contract type, payment method, monthly charges, and total charges.
- Demographic Information: Gender, age range, partner status, and dependent information.

![CustomerDemographics](https://github.com/user-attachments/assets/2a669d4b-9a6d-4d1a-9c49-f581b94cca3d)

![CustomerServicesDashboard](https://github.com/user-attachments/assets/7881625e-d928-4c39-94cb-c94d939d3c4f)


## Key Insights

### Churn Metrics:

- Total Customers: 7,032

- Churned Customers: 1,869

- Churn Rate: 26.58%

- Average Monthly Charges: $64.80

- Average Customer Tenure: 32 months

### Churn by Service Usage:

- Customers with 2-5 services show the highest churn rates, peaking at 44.9% for those with three services.

- Single-service customers (Phone Service only) have a low churn rate at 7.4%.

- Churn is notably high among Fiber Optic users, suggesting possible dissatisfaction with service quality or cost.

### Churn by Customer Demographics:

- Contract Type: Monthly contract customers have a significantly higher churn rate (23.54%) compared to those on annual or biennial contracts.

- Senior Citizens: Senior customers show a high churn rate of 70%, indicating potential service or support issues for this demographic.

- Dependents and Partner Status: Customers with dependents and/or partners show lower churn rates, suggesting family-oriented packages may be effective for retention.

### Churn by Account Details:

- Payment Method: Electronic Check users have the highest churn rate at 80%, potentially due to payment process dissatisfaction.

- Paperless Billing: Customers using paperless billing show moderate churn, possibly due to lower engagement or billing concerns.

## Retention Strategies

Based on these insights, here are some targeted retention strategies:

### Enhance Onboarding for New Customers

Focus on customers with tenure <12 months, who show the highest churn risk.

Implement a structured onboarding process with check-ins, educational resources, and introductory offers to increase engagement early on.

### Encourage Long-Term Contracts
Monthly contract users churn more often. Provide incentives like discounts or added features for customers who switch to annual or biennial contracts.

### Focus on Fiber Optic Customer Satisfaction
Fiber Optic users experience higher churn than DSL users. Conduct satisfaction surveys to identify pain points and consider offering promotions or adjustments to improve service value perception.

### Age-Specific Engagement for Senior Citizens
Senior citizens show higher churn rates. Create support programs that cater to older customers, such as simplified billing, priority customer service, and senior-friendly communication options.

### Promote Reliable Payment Methods
Customers paying via Electronic Check have a high churn rate. Offer discounts or incentives for switching to credit cards or bank transfers, which might provide a smoother experience.
