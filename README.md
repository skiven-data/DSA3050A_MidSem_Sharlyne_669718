# DSA3050A_MidSem_Sharlyne_669718
**Student Name:** Sharlyne Kiven
**Student ID:** 669718

## Dataset
- Name: Bank Marketing Dataset
- Source: https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
- Rows: 11,162
- Columns: 17

## Business Problem
ABC Bank wants to identify which customer characteristics 
influence subscription to term deposits so that future 
marketing campaigns can be more effective and targeted.

## Power Query Transformations Performed
- Renamed pdays to Days Since Previous Contact
- Renamed poutcome to Previous Campaign Outcome
- Renamed deposit to Subscription Status
- Changed data types for age, balance, duration, campaign, previous
- Removed duplicate records
- Removed blank rows
- Trimmed and cleaned text columns: job, marital, education, contact
- Replaced unknown with Unknown and admin. with Administrative
- Removed the day column
- Duplicated contact column into Contact Type and Contact Device
- Replaced values in Contact Device: cellular to Mobile, telephone to Landline
- Merged job and marital into Customer Profile
- Created custom column: Balance Per Campaign
- Created conditional column: Balance Category
- Created Campaign Date column and extracted Year, Month, Quarter, Day
- Filtered rows by balance greater than 1000 and Subscription Status = yes
- Sorted data by balance descending
- Added index column from 1
- Created Date Table using blank query
- Used Group By on job with Customer Count, Average Balance, Maximum Balance
- Replaced errors in balance column with 0
- Created Customer Tier column using nested conditional logic
- Created Reference Query showing Job and Average Balance
- Enabled Column Quality, Distribution, and Profile

## Visuals Created
- KPI Card: Total Customers
- KPI Card: Total Subscribers
- KPI Card: Subscription Rate
- Bar Chart: Subscribers by Occupation
- Column Chart: Subscribers by Customer Tier
- Line Chart: Campaign Trend
- Donut Chart: Contact Method Used
- Table: Customer Details
- Matrix: Average Balance by Occupation and Customer Tier
- Treemap: Balance Distribution
- Scatter Chart: Age vs Balance

## Map Visual Note
The Bank Marketing dataset does not contain geographic data 
such as country, city, or coordinates. A Scatter Chart was 
used as a substitute visual.

## Business Insights
1. Customers in the Premium balance category have the highest 
subscription rate, indicating they should be prioritized in 
future campaigns.

2. The contact method influences campaign success, suggesting 
the bank should focus on the communication channel with the 
highest conversion rate.

3. Campaign performance varies over time and certain months 
show higher subscription rates. Scheduling campaigns during 
peak periods may improve overall effectiveness.
