# Sales_DataAnalysis_PowerBI

 ## Description

 Data Analysis on a companies total sales of its various branches using Power BI.

 ## Data Modeling

 Star Schema model.
 ![Data Modeling](ScreenShots/DataModeling.png)

 ## Data Cleaning

 1. Sales Market Table:
   - Removed the entries which did not have any region as they were the transactions outside India and we are only focusing on the transactions in India as they are currently operating only in India.
   - Before
   ![Data Cleaning Sales Market Before](ScreenShots/sales_markets_before.png)
   - After
   ![Data Cleaning Sales Market After](ScreenShots/sales_markets_after.png)
 2. Sales Transactions Table:
   - Removed the entries which had sales amount as 0 or in negative and added a new column norm_curr in which I converted all the USD sales amounts to INR to keep it consistent throughout for data analysis (1USD = 84INR).
   - Before 
    ![Data Cleaning Sales Transactions Before](ScreenShots/sales_transactions_before.png)
   - After
    ![Data Cleaning Sales Transactions After](ScreenShots/sales_transactions_after.png)

 ## Things I learned

 - Data Modelling
 - PowerBI
 - Data transformation and cleaning
 - Exploratory Data Analysis

## Acknowledgement

Coding Challenge from a youtube channel codebasics Sales Insights Power BI project.
[codebasics](https://www.youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9)

