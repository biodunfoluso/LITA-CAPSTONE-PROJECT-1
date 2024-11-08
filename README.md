

## LITA CAPSTONE PROJECT 1

This is  where Lita Capstone data on sales performances for a retail store is analysed by analytical tools to make  findings. 

## PROJECT TITLE: 
SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE

## PROJECT OVERVIEW
'''
This project demonstrates how Ms.Excel,SQL,and power Bi tools can be combined to deliver a comprehensive, interactive analysis for business insights.

## AIM AND OBJECTIVES

 i. To analyse the sales performances 

 ii.To explore sales data to uncover the top selling products

 iii. To explore sales data to uncover the regional per monthly sales trends.

  iv. To produce an insight to the findings at the retail store base on the sales data, using Power Bi  as tool for final presentations.

## Data Sources
   Lita Capstone salesdata was used as the primary sources of data saved on Excel workbook.

  ## TOOLS USED

- Ms. Excel
- SQL
- Power Bi

## ACTIVITY CARRIED OUT

  - Downloading the sales data table on various tools used.

 - using pivot table for summarisation,and pivot chart for visualisation on Excel.
- Writing queries on SQL to provide result for the findings.
Data transformation,
- Data cleaning,viewing data status on column quality,column profile,column distribution. Column calculations and measure,and data visualisation on power Bi.

## SUMMARY FOR EACH TOOL USED

  From Ms. Excel analysis, the following pivot tables were prepared for the summary of the sales data.

- Total sales by product--- pivot table 2 

- Total sales by Month---   Pivot table 4
- Total sales by Region---Pivot table 6

- Average sales by product--- Pivot table 8

- Top selling product by sales--- Pivot table 16

- Top selling product by quantity---Pivot table 20 

- And their visualisation

 MySQL was used to justify the sales data questions and the following queries were executed to provide action output to the given findings.
See the files attached.![SQL PRODUCT BY TOTAL SALES](https://github.com/user-attachments/assets/0c0b8cfb-58a6-41b0-af14-02fd1558cc09)


## SUMMARY OF THE FINDINGS

Based on the analysed data, the following findings from the analysis are highlighted below;

- The salesdata table given contains 50,001rows with  the heading inclusive.

- Total sales column was calculated using                = PRODUCT(UNIT PRICE * QUANTITY)

- Total Revenue column was calculated by duplicating Total sales and renaming. Since Total Revenue = Quantity X price.

 - List of Tables connected to slicer for interactive activities are mentioned earlier.

- It is discovered that Total quantity was (345,000) in number.

- Sum of product number was calculated using new column and measure

- Shoes are the top selling product by total sales of (#3,087,500), next to shirt and hat.

While the Southern region has the highest sum of total sales(total revenue) and highest sum of quantity. Eastern region is the second with higher revenue which recorded the top selling product.

![PowerBi salesdata table andview](https://github.com/user-attachments/assets/5b32da81-d227-4ae2-b3f9-bd1d314742b9)
![Power Bi salesdata view](https://github.com/user-attachments/assets/5233a537-d513-48f7-bdb4-17a74a175c8f)
![Pivotchart for salesdata](https://github.com/user-attachments/assets/2c33e8ad-ec99-48b0-9a6d-bb81a2ba66b4)
![Pivot chart for saledata analysis](https://github.com/user-attachments/assets/d6abc725-ffcf-4851-a297-797aeebf87f6)
![Screenshot (46)](https://github.com/user-attachments/assets/f1eb3e67-6bf6-4704-a5ec-4df240f0b474)
![Pivot tables for salesdata](https://github.com/user-attachments/assets/4f55c4ed-13eb-4daf-a0e6-1ee7ffa29968)
![Salesdata table](https://github.com/user-attachments/assets/aac1699c-ca45-4c0b-b91e-d234bd7ac40f)

 

## Conclusion:

In line with the above findings, it can be deduced that the products were correctly distributed to the regions by well trained staff. The reason is that; no errors was recorded on the recording. No blank cells recorded and it seems monitoring of sales and inventory were made on regular bases.


 #  Lita Capstone project 2

 
### PROJECT TITLE:

# Customer Segmentation For a Subscription Service.

### Project Objectives

- To analyse customer data for a subscription services.

- To identify Segments on trends.

### Scope of study

1. To track the top selling subscription types

2. Understanding customer behavor.

3. To identify key trends in cancellations and renewals.

4. To interpret and present the analysison power Bi Dashboard.

### Tools used

Ms. Excel, and power Bi

### STEPS APPLIED

A. Using Ms Excel, to show the report of the following by creating pivot tables for summarisation with slicer in connection  for interraction. Additional column was created foŕ subscription Duration using 

=DATEDIF(Subscription Start,SubscriptionEnd, "d")

### LIST OF PIVOT TABLES

I. Pivot table 3--Subscription Count by Region

II. Pivot table 5--Showing report of the most popular Subscription tpes

III. Pivot table  7 --Count of Cancellation by Month.

IV. Pivot table 11 -- Revenue by  Subscription Type

V. Pivot table 13-- cancellation rate by Region.

VI. Pivot table 15-- customer name by subscription count.

B. Using Power Bi.

The customer data was loaded, transformed and cleaned. Prepared for Data visualisation connected with slicer.

See the screenshots below.
![POWERBicustomerdataview](https://github.com/user-attachments/assets/89f968f2-9431-442c-9565-9738c0069623)
![customerdatapivotchart](https://github.com/user-attachments/assets/092355f5-45e1-40d7-bae8-22bdc1c8ad66)
![Customerdata pivot chartview](https://github.com/user-attachments/assets/fb7ba550-e19a-4826-bc7b-22b10ca7c6ef)
![customerdatapivottables](https://github.com/user-attachments/assets/81c16f35-1cbd-45e5-ae8d-2fe2e820bb0c)
![customerdatatable](https://github.com/user-attachments/assets/69625ff2-9bfb-4d86-b47d-ca4a3509678a)

 

The above tasks help in the interpretation and presentations of the analysis.

### SUMMARY OF FINDINGS

The following findings are highlighted base on customer Segmentation for a subscription services analysis.

I. CustomerID count ,canceled count,on rows equal 75,000.

II. Sum of Revenue is 148,819,686 within January 2022  and August 2024.

III. Most popular Subscription type is Basic at the Eastern Regionwith count of 18,750.

IV. Subscription canceled is calculated on new column using conditional column = IF( Cancelled=True, "1", "0") which equals 33,750. While Subscription successful is 41, 250.

V. Average Subscription Duration equals 365days

VI. Monthly Subscription rate is 3,750. 

Based on these findings,it is discovered that the major subscription type demanded for, at the Eastern region shows that they prefered low cost of subscription types with no networking problem to canceled the subscriptions other region experienced on standard and premium.

I recommend the company to see to improving  their network on standard and premium  subscription types to increase their rate of income as revenue and profit making.
