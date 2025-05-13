# KPMG-Data-Analysis-using-Excel
Cleaned and standardized customer, transaction, and demographic data, ensuring consistency and accuracy for analysis. I conducted segmentation by wealth, gender, and industry, identifying key customer groups and behavioral trends. I analyzed sales trends, product performance, and customer purchase patterns, providing actionable insights into revenue drivers. Additionally, I estimated potential revenue and calculated customer lifetime value (CLV) to highlight high-value customer segments.
<br><br>
<b>TITLE:
<br>
KPMG Data Analysis using Excel</b>
[KPMG-dataset](https://docs.google.com/spreadsheets/d/1u7sGpjGXmPKOsg7FmyGHOGFPjK1esnuH/edit?usp=sharing&ouid=114143905310513993055&rtpof=true&sd=true)
<br>
<b>PROJECT OVERVIEW:</b>
<br>
This project aims to analyze customer demographics, transactions, and new customer data to provide insights into business
performance and customer behavior. The project consists of six tasks that involve data cleaning, data analysis, and visualization using
Excel.
<br><br>
<b>FINDINGS:</b><br><br>
<b>Task 1: Data Cleaning
<br>
Objective:</b> Prepare the datasets for analysis by cleaning and correcting any inconsistencies.
<br><br>
<b>1. Customer Address Data:<br>
   &nbsp;&nbsp;&nbsp;i.</b> Remove any duplicate records.<br>
   &nbsp;&nbsp;<b>ii.</b> Ensure all state names are correctly formatted.<br>
<b>2. Customer Demographic Data:<br>
   &nbsp;&nbsp;&nbsp;i.</b> Identify and correct any erroneous data entries (e.g., invalid characters in default).<br>
  &nbsp;&nbsp;<b>ii.</b> Standardize the format for missing data entries.<br>
 &nbsp;<b>iii.</b> Correct any anomalies in gender representation.<br>
<b>3. Transaction Data:<br>
   &nbsp;&nbsp;&nbsp;i.</b> Ensure that transaction_date is in a consistent date format.<br>
  &nbsp;&nbsp;<b>ii.</b> Remove any records with missing or incomplete information.<br>
<b>4. New Customer Data:<br>
   &nbsp;&nbsp;&nbsp;i.</b> Standardize address formatting.<br>
  &nbsp;&nbsp;<b>ii.</b> Ensure consistent gender representation.<br>
 &nbsp;<b>iii.</b> Correct any anomalies in job_title and job_industry_category.<br><br>

 <b>Task 2: Customer Segmentation<br>
Objective:</b> Segment customers based on demographic and transaction data to identify key customer groups.<br><br>
<b>1. Segmentation by Wealth Segment:<br>
&nbsp;&nbsp;&nbsp;i.</b> Show the number of customers in each wealth_segment.<br>
&nbsp;&nbsp;<b>ii.</b> Calculate the average tenure for each wealth_segment.<br>
<b>2. Segmentation by Gender:<br>
&nbsp;&nbsp;&nbsp;i.</b> Showing the number of customers by gender.<br>
&nbsp;&nbsp;<b>ii.</b> Calculate the average past_3_years_bike_related_purchases for each gender.<br>
<b>3. Segmentation by Job Industry:<br>
&nbsp;&nbsp;&nbsp;i.</b> Showing the number of customers in each job_industry_category.<br>
&nbsp;&nbsp;<b>ii.</b> Analyze the distribution of wealth_segment within each industry.<br><br>

<b>Task 3: Transaction Analysis<br>
Objective:</b> Analyze transaction data to identify trends and patterns.<br><br>
<b>1. Sales Trend Analysis:<br>
&nbsp;&nbsp;&nbsp;i.</b> Create a chart showing the total sales per month.<br>
&nbsp;&nbsp;<b>ii.</b> Identify any seasonal trends or significant spikes in sales.<br>
<b>2. Product Performance Analysis:<br>
&nbsp;&nbsp;&nbsp;i</b> Show the total sales for each brand.<br>
&nbsp;&nbsp;<b>ii.</b> Calculate the total sales and average list_price for each product_line.<br>
<b>3. Customer Purchase Behavior:<br>
&nbsp;&nbsp;&nbsp;i.</b> Identify the top 10 customers based on total transaction value.<br>
&nbsp;&nbsp;<b>ii.</b> Calculate the average number of purchases per customer.<br><br>

<b>Task 4: New Customer Insights<br>
Objective:</b> Analyze the new customer dataset to provide insights into potential new customer behavior and value.<br><br>
<b>1. New Customer Demographics:<br>
&nbsp;&nbsp;&nbsp;i.</b> Show the distribution of new customers by wealth_segment and job_industry_category.<br>
&nbsp;&nbsp;<b>ii.</b> Calculate the average past_3_years_bike_related_purchases for new customers.<br>
<b>2. New Customer Location Analysis:<br>
&nbsp;&nbsp;&nbsp;i.</b> Create a map or chart showing the distribution of new customers by state.<br>
&nbsp;&nbsp;<b>ii.</b> Analyze the correlation between property_valuation and customer wealth_segment.<br>
<b>3. Potential Revenue from New Customers:<br>
&nbsp;&nbsp;&nbsp;i.</b>Estimate potential revenue based on past_3_years_bike_related_purchases and value.<br><br>

<b>Task 5: Customer Lifetime Value (CLV) Analysis<br>
Objective:</b> Calculate and analyze the customer lifetime value to identify the most valuable customers.<br><br>
<b>1. CLV Calculation:<br>
&nbsp;&nbsp;&nbsp;i.</b> Use the formula<br>
&nbsp;&nbsp;<b>ii.</b> Calculate CLV for each customer using transaction data.<br>
<details>
<summary><strong>📦 <span style="color:blue; text-decoration:underline;">CLV Formula Breakdown</span></strong></summary>

<div style="border:1px solid #000; padding:16px; border-radius:6px; background-color:#f9f9f9;">

**Formula**  
`CLV = (Average Purchase Value × Purchase Frequency) × Customer Lifespan`

---

### **Average Purchase Value (APV):**

- This is the average amount of money a customer spends in a single purchase.  
- **Formula:** `APV = Total Revenue / Number of Purchases`
  - **Total Revenue** is the sum of all revenues generated from all purchases. You can get the total revenue from transactional data.
  - **Number of Purchases** is the total count of all transactions of that customer.

---

### **Purchase Frequency (PF):**

- This is the average number of times a customer makes a purchase in a given period.  
- **Formula:** `PF = Total Number of Transactions / Number of Unique Customers`

---

### **Customer Lifespan (CL):**

- This represents the average number of years a customer remains active.  
- In your dataset, this is represented by the `tenure` column in the Customer Demographic dataset.

</div>
</details>
<b>2. Segment CLV Analysis:<br>
&nbsp;&nbsp;&nbsp;i.</b> Show average CLV by wealth_segment.<br>
&nbsp;&nbsp;<b>ii.</b> Analyze the relationship between CLV and customer demographics (e.g., gender, job industry).<br><br>

<b>Task 6: Executive Summary and Recommendations<br>
Objective:</b> Summarize findings and provide actionable recommendations for business strategies.<br><br>
<b>1. Summary of Key Insights:<br>
&nbsp;&nbsp;&nbsp;i.</b> Highlight key findings from customer segmentation, transaction analysis, new customer insights, and CLV analysis.<br>
<b>2. Recommendations:<br>
&nbsp;&nbsp;&nbsp;i.</b> Provide recommendations for marketing strategies targeting high-value customer segments.<br>
&nbsp;&nbsp;<b>ii.</b> Suggest potential areas for business expansion based on new customer location analysis.<br>
&nbsp;<b>iii.</b> Recommend improvements in product offerings based on transaction analysis.<br>

