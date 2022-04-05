**Problem Statement:**
The company to find sales insights accurately and quickly without checking the bulk of excel sheets.
Before getting started on the project, project planning is vital. It can give us a clear idea to plan and achieve the target effectively and quickly.
I have chosen the project management tool named ‘AIMS GRID’. It helps us to define our project scope based upon the below 4 criteria.
1.	Purpose
2.	Stakeholders
3.	End Result
4.	Success Criteria

**Purpose:**
Business people to find the hidden insights from the reports and take effective decisions.
To reduce the manual time which is being spent by them on analyzing the business of the company.

**Stakeholders:**
Sales Team
Marketing Team
Finance team
Customer service team
Data analysis Team
IT team

**End Result:**
An automated dashboard provides quick and instant sales visions in order to support data-driven decision-making.

**Success Criteria:**
The sales team can make better decisions, this leads to better cost savings from the total spend
It saves the time of the sales analysts for manually analyzing and gathering up the data trend. So that they can reinvest their time in other value-added activities.

The entire data analysis project will follow the below phases.
Data Discovery 
Data Cleaning 
Data Transformation Building Reports & Dashboards (1st version) 
Get feedback from stakeholders 
Build version based on user’s feedback 
Publish and share
Data-driven insights & Business decisions


Connected the MySQL database with Power BI and loaded the tables – Customers, Markets, Products, Transactions, Date.

**Data cleaning/Data cleaning/Data Wrangling steps done:**

1.	Unselected the rows with values Newyork and Paris from the market table as companies only doing business in India.
2.	Removed Sales amount<= 0 from the transaction table
3.	Created a custom column named Normalised_currency by converting the currency from USD to INR in the Transaction table
4.	Removed duplicate transactions from the sales transaction table

Applied the **STAR schema** in data modeling where the fact table (sales transactions) sits at the center and small dimensional tables are branched off to form the points of the star.

**Insights Driven**

To increase sales growth, the sales director needs to give more importance to the below metrics.
1.	Top 5 customers by Revenue
2.	Top 5 products by Revenue (Increase the manufacturing of those products)
3.	Markets by revenue
4.	Less revenue yielding customers (get the feedback from the customers, given offers and discounts)
5.	Less revenue yielding products (stop selling those products or identify the reason why sales are declining and work on that)
6.	Sales by Zone (Identity the zones having very low sales and stop selling the products in that zone to avoid transportation charges)
7.	Revenue trend over the years and months
8.	Sales by customer type (Concentrate more on the customers who are doing more business)
