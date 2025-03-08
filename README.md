# Customer-Retention-Analysis
![image](https://github.com/user-attachments/assets/90b2c52b-6d0e-473a-83c8-0a34e2bb17ae)
## Phone-Now-PWC--Power-BI 
## Report link:
https://app.powerbi.com/view?r=eyJrIjoiZDdjYTcxYjUtOTc2NS00ZmQ4LTgwZmMtNGJhZjRhN2ZlMGUwIiwidCI6IjU1YmQ5ZTdkLTdkMWEtNGZlNy1hNmZmLTJhOWY0YzdkZjAxYSJ9
## Project Overview:
To analyze customer churn within Phone Now ( PWC project), identify key factors influencing customer retention, and provide actionable recommendations to mitigate churn and improve customer satisfaction.
## Data Structure:
![image](https://github.com/user-attachments/assets/6eb62b65-f046-420f-8604-1098f688c542)

The provided image showcases a Power BI data model with two primary tables:

### Churn:
Contains detailed customer information, including demographics, service usage, payment methods, and churn status.
Key columns: CustomerID, Churn, Contract, InternetService, MonthlyCharges, TotalCharges, etc.

### Churn - Unpivot Groups:
A normalized version of the Churn table, where categorical attributes (like InternetService, PaymentMethod) are unpivoted into rows.
Key columns: CustomerID, Attribute, Value
Relationship between Tables:

One-to-Many Relationship:
The Churn table is the parent table.
The Churn - Unpivot Groups table is the child table.
The relationship is established based on the CustomerID column.

### Data Model Diagram:
In essence, the data model is designed to facilitate analysis and visualization of customer churn patterns across various dimensions, such as:

Demographic Factors: Age, gender, senior citizen status, etc.
Service Usage: Internet service type, phone service, multiple lines, etc.
Payment Methods: Electronic check, mailed check, bank transfer, credit card.
Contract Type: Month-to-month, one-year, two-year.
Support Tickets: Number of technical and administrative tickets.

![image](https://github.com/user-attachments/assets/0afa65ae-d5a6-49c8-945f-6b12b36a8d39)

## Executive Summary:
This analysis reveals a significant churn rate of 26.54% within PhoneNow. Key factors driving churn include:

Fiber Optic and Month-to-Month Contracts: Customers with these attributes exhibit higher churn rates.
Support Ticket Volume: High numbers of technical support tickets correlate with increased churn.
Payment Method: Electronic checks are associated with higher churn.
To mitigate churn, we recommend:

Targeted Retention: Implement personalized retention strategies for high-risk segments.
Enhanced Support: Optimize technical support for faster resolution times.
Payment Method Optimization: Explore alternatives to electronic checks.
Loyalty Programs: Introduce loyalty programs to encourage long-term contracts.
Data-Driven Decision Making: Continuously monitor key metrics and leverage data insights.
By addressing these areas, PhoneNow can significantly reduce churn and improve customer satisfaction.


## Insights Deep Dive:
![image](https://github.com/user-attachments/assets/c91e87ea-0f20-49e3-ac4b-d1bd946f6b9b)

### Customer Demographics and Behavior:

Senior Citizen Impact: 25% of customers are senior citizens, suggesting a need for tailored services and support.

Payment Method Preferences: Electronic checks are the most common payment method, followed by mailed checks and bank transfers.

Service Usage: Phone service is the most widely adopted service, followed by streaming TV and movies.

Contract Duration: A significant portion of customers (53%) are on month-to-month contracts, which can lead to higher churn rates.

### Churn Risk Factors:
Fiber Optic Customers: Customers with fiber optic internet service have a higher churn rate (41.89%).

Month-to-Month Contracts: Customers on month-to-month contracts are more likely to churn (40%).

High Support Ticket Volume: Customers with a high number of technical support tickets are at higher risk of churn.

### Financial Implications:
Yearly Charges: The total yearly charges amount to $2.86 million.

Monthly Charges: The average monthly charge is $139.13.

Revenue by Service: Fiber optic services contribute the most to monthly revenue ($283K).


### Additional Insights:
Paperless Billing: A lower percentage of customers use paperless billing, which might indicate opportunities for improvement in billing processes.

Device Protection and Online Security: A significant number of customers have opted for these services, suggesting their importance in customer retention.

![image](https://github.com/user-attachments/assets/2a10cf8a-dcc3-4b49-a279-420df1c1a101)


### Churn Risk:

Overall Churn Rate: 26.54% of customers are at risk of churning, indicating a significant concern.

Internet Service Impact: Customers with Fiber Optic internet are at the highest risk of churning (41.89%).

Contract Type: Month-to-month contracts have the highest churn rate (40%), highlighting the need for longer-term contracts.

### Customer Behavior and Demographics:

Senior Citizen Segment: 25% of customers are senior citizens, suggesting a need for tailored services and support.

Payment Method Preferences: Electronic checks are the most common payment method.

Service Usage: Phone service is the most widely adopted service, followed by streaming TV and movies.

Support Ticket Volume: The majority of support tickets are administrative, indicating a potential need for process improvements.

### Financial Implications:

Total Yearly Charges: The total yearly revenue is $16.06 million.
Monthly Revenue: The average monthly revenue per customer is $139.13.

Fiber Optic Revenue: Fiber optic services contribute the most to monthly revenue ($283K).

## Recommendations:
### Targeted Retention Strategies:
 Implement personalized retention programs for high-risk customer segments, such as fiber optic customers and month-to-month contract holders.

### Enhanced Customer Support: 
Optimize technical support efficiency and explore additional support channels to reduce ticket volumes and improve customer satisfaction.

### Payment Method Optimization:
 Analyze the reasons for higher churn among customers using electronic checks and consider alternative payment options.

### Loyalty Programs: 
Introduce loyalty programs or incentives to encourage longer-term contracts and reduce churn.

### Data-Driven Decision Making: 
Continuously monitor key metrics and leverage data insights to make informed business decisions.
