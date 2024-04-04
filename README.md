# Telecom-Customer-Churn-Analysis
In the Second task of the Virtual Internship experience with PwC, I was asked to create a dashboard indicating insightful KPIs about customer retention in PhoneNow. 
Refer to PwC Switzerland Power BI Virtual Case Experience Task [here](https://www.theforage.com/virtual-experience/a87GpgE6tiku7q3gu/pw-c-switzerland/power-bi-cqxg/diversity-inclusion)

## PROBLEM STATEMENT
The Retention department in the telecom company, PhoneNow, is concerned about losing its customers and also wants to identify the customers at risk. Hence the engagement partner, requested for the following tasks:

1. Define proper KPIs
2. Create a dashboard for the retention manager reflecting the KPIs
3. Write a short email to him (the engagement partner) explaining my findings, and include suggestions as to what needs to be changed.

## Overview
This project provides a comprehensive analysis of customer churn for PhoneNow, a telecom company. Utilizing a dataset provided by PwC, the analysis focuses on identifying key factors that contribute to customer retention and churn. The dashboard developed as part of this project aids in visualizing important KPIs and understanding customer behaviours and preferences, thereby enabling PhoneNow to make data-driven decisions to improve customer satisfaction and reduce churn rates.

## Skills
1. DAX (Data Analysis Expression) Concept for Calculated Measures.
2. Power Query Editor for data cleaning (Conditional Columns and Added Columns)
3. Understanding the data and identifying impactful KPI's

## Dataset
The dataset includes various customer attributes such as service subscription details, account information, demographic data, and support ticket histories, offering a rich foundation for in-depth analysis.

## Insights

1. **Customer Base and Retention**: With a total customer count of 7,043 and a churn rate of 26% indicative of a higher retention rate of 74% which generally suggests customer satisfaction and effective retention strategies.

2. **Service Adoption**: Phone services have the highest adoption rate at 90.32%, suggesting that it's the core service customers are interested in. Internet services also have a high adoption rate of 78.33%. On the other hand, services like Online Security, Tech Support, and Device Protection have lower adoption rates, which may highlight opportunities for marketing these services more effectively.

3. **Financial Insight**: The "Top 10 Customers by Revenue" section highlights that the highest-paying customers contribute a substantial sum to the total revenue (over $85k). Ensuring the satisfaction and retention of these top customers could be key to maintaining a healthy revenue stream.

4. **Billing and Payments**: About 30% of customers prefer electronic checks over other payment methods with credit card payments being the second most popular. This preference for electronic checks might influence how to handle payment processing and what options to prioritize.

5. **Churn and Customer Tenure**: The average customer tenure is 17.98 months. The churned customers have a lower tenure on average, this could indicate that customers are leaving before reaching a certain loyalty threshold. Strategies could be implemented to boost engagement and value offered within the first year and a half to reduce churn.

6. **High Churn Among Month-to-Month Contracts**: A significant portion of the contracts are month-to-month (23.5%). The most churned customers are from this group, it could suggest that customers on month-to-month contracts might require more incentives to convert to longer-term commitments to reduce churn.

7. **Customer Support Effectiveness**: A higher average of tech support tickets may suggest that churned customers encounter more issues requiring support, which could be a sign of dissatisfaction with the product or service. If these issues are not resolved satisfactorily, it could lead to frustration and eventually churn.
   
8. **Monthly charges effect**: Average customers are charged around $64 every month. But the highest Churn rate is among those that are charged above $70 monthly making it easy to retain customers that were charged below $60 monthly.

9. **Significant Revenue Contribution by Senior Citizens**: Senior citizens represent a critical 16.21% segment of the customer base yet contribute a disproportionate $3.21 million to revenue, indicating higher service utilization and potential for targeted growth strategies. With an average monthly charge of $79.82, this demographic demonstrates both a strong engagement with the company's offerings and a possible preference for premium services. Leveraging their lower tech support interactions and notable adoption of paperless billing, the company could significantly enhance service offerings and digital engagement to further increase the high-value senior segment's satisfaction and revenue contribution.

10.**Churn by Service Type** - Increase tech support capacity for Fiber Optic customers and lower tech tickets per customer to 0.5

## Project Structure

1. dataset: 01_churn_dataset
2. PowerBI_Dashboard: Customer_churn_dashboard
3. analysis
4. README.md 

## Dashboard

Preview and [link](https://app.powerbi.com/view?r=eyJrIjoiNDhhMTIyZTQtYzI3NS00YmQ0LWI4YTQtZDE3MTk1Mzk1M2JjIiwidCI6Ijk2NDY0YThhLWY4ZWQtNDBiMS05OWUyLTVmNmI1MGEyMDI1MCIsImMiOjN9) of the PowerBI dashboard:

![image](https://github.com/soniaditi098/Telecom-Customer-Churn-Analysis/assets/41970334/27a56a01-e140-4a2f-b41f-d08a2497543b)


## Recommendations

Based on the insights from the dashboard, recommendations include:

- Enhancing support for Fiber Optic service users to reduce churn.
- Introducing incentives for month-to-month contract holders to adopt longer-term contracts.
- Tailoring services and communications to better engage senior citizens, leveraging their value to the company.
- Reducing tech tickets could lead to customer satisfaction and retention.

## Usage

To use this dashboard:

1. Clone this repository.
2. Open the dashboard with PowerBI.
3. Explore the visualized data to uncover actionable insights.




