 Cohort Analysis: Customer Retention, Segment by Quantity and Revenue
 
I. Introduction

1. About Cohort Analysis
What is cohort analysis?

Cohort analysis is an analytical technique that categorizes and divides data into groups (cohorts), with common characteristics prior to analysis. This technique helps us isolate, analyze, and detect patterns in the lifecycle of a user, to optimize customer retention, and to better understand user behavior in a particular cohort.

Businesses use cohort analysis to understand the trends and patterns of customers over time and to tailor product and service offers to the identified cohorts.

Three major types of Cohort

Time-based: groups customers based on the time they started using a company’s products or services.
Segment-based: groups customers by the type of product or level of service they signed up for.
Size-based: groups customers based on their size.
2. Business Questions
Using Python to create time-based cohorts analysis that allows stakeholders to assess and compare retention, order items quantity and order revenue from different cohorts of customer to optimize and tailor products and services offers to these specific cohorts.

3. About the Dataset
The dataset is from Kaggle (Link), consists of 36 columns and 286392 entries, records online sales data of different products, several merchandise and electronic in different states in USA from October 2020 to September 2021.

4. About this Project
This project focuses on performing time-bases Cohort Analysis: Customers will be divided into acquisition cohorts depending on the years that they become customers. Due to the wide spread of customer acquisition years (from 1978 to 2017), this project will create 5-year-bins and then assign each of customer’s transaction from October 2020 to September 2021 into these bins.

The goal of this project is to point out the significant trends and patterns in retention rate, order items quantity and revenue of different customer cohorts based on their acquirement time, then give recommendations to optimize sales and marketing strategies to improve overall performance.

The project will follow these steps:

Install the environment
Import and clean the dataset
Assign cohorts
Calculate retention rates
Segment data by Quantity and Revenue.


II. Data Visualization
1. Number of Customers per Cohort
<img width="1189" height="590" alt="cohort1" src="https://github.com/user-attachments/assets/dd866e37-0573-4c38-9e31-d802a1a5a344" />

2. Customer Retention and Retention Rate
   <img width="1095" height="790" alt="cohort3" src="https://github.com/user-attachments/assets/7dd7172a-c961-412f-a794-cbf15fb20cc8" />
<img width="1112" height="790" alt="cohort2" src="https://github.com/user-attachments/assets/94c86c06-4313-4f98-ba1b-f3d3766a228f" />
3. Cohorts by Quantity
<img width="1086" height="790" alt="cohort4" src="https://github.com/user-attachments/assets/57264b56-f6e4-465f-8153-742644bb1778" />
4. Cohorts by Revenue
<img width="1132" height="790" alt="cohort5" src="https://github.com/user-attachments/assets/541595a4-d806-4da7-9485-6cac56ab01fb" />

III. Insights

Number of Customers: Company has long lasting customers from 1978. The number of newly acquired customer has been increasing sustainably over the years.

Retention Rate: Though the number of customers in each cohort differs, it is notable that all cohorts roughly share the same trends and patterns in retention rates: highest peak of around 33% in Dec 2020 (holiday shopping season - Christmas and New Year) and second peak of approx. 22% in Apr 2021 (pre-summer holiday, warmer weather, sales events in April such as the annual Amazon Prime Day and the Memorial Day sales). Retention rates are lowest in Feb (after holiday season) and Aug-Oct (cooler weather in autumn, saving money for the winter holidays, fewer major sales events, etc.).

Average order items: Despite the fact that retention rate is highest on Dec 2020, this month also witnesses the lowest average items per order in all cohorts. Customers acquired from 1983-1988 ordered nearly 6 items in each order taken in Feb 2021. The average items per order seems higher in Mar and Jul for almost all cohorts.

Order Revenue: Orders placed by the 1988-1993 cohort have a relatively higher value than those placed by other cohorts. In Aug 2021, the order value for this cohort was an outstanding more than $1,000 per order. The oldest cohort, 1978-1983, also has a consistently high order value. In general, all cohorts have similar order value patterns over the months, with increases in Dec, Mar, and Apr, and decreases to the lowest levels in Jan and Feb.


IV. Recommendations

Newly acquired customers have been increasing steadily and have brought in a significant amount of orders and revenue. However, when converted to percentages, almost all cohorts, both old and new customers, have very similar trends and patterns in retention rate and revenue. In some cases, old customers even have higher average order values and sales amounts per order than new customers.

Apart from acquisition new customers, it's important to maintain and leverage the business relationship with old, long-lasting customers. This brings a lot of benefits: less marketing costs, better feedback, positive word-of-mouth marketing, sustainable revenue, less churn, etc.

It's necessary to investigate more about other factors such as Customer Acquisition Cost. Instead of spending expensive amount of money to acquire a new customer, it's worth to care old customer better: personalize customer experience, stay in touch, offer loyalty programs, offer incentives, etc.


