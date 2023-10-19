# SUPER-STORE-SALES-ANALYSIS
## Introduction
Superstore is a retail sales store that deals in diverse array of products ranging from furniture, office supplies, and technologic equipment which have been further grouped into corporate, home office and consumer segments. 
It is exclusively an online store, with a number of outlets within the US states and shipping services available across all the United State. 
## Objective
This report examines the superstore sales records across 4 years within the different states and regions of the US by providing solutions to the following business questions
## Analysis Tool & Data Source
This data set was provided by Chinonso my data analysis tutor as part of our data training exercise whike **Excel** was the tool used to find solutions to the problem
## Analysis Process
1.	Case study:
The dataset consists of 9,800 rows and 18 columns which therein are embedded with information concerning customers names, customer ID, ship date, segment, country, category and region are a few important pieces of information about the dataset.
2.	Data cleaning and transformation:
Some data cleaning and transformation was done to be able to solve the business questions and provide KPIs that was required as shown below.
## Business Questions and Solution
Provided below are the questions and answers to the business’s problem:
1.	Total Revenue Generated: 
Excel Formula Syntax =SUM (W2: W9801)  
Returned value = $2,261,536.783
2.	Highest Revenue Generated: 
Excel Formula Syntax =MAX (W2:W9801)  
Returned value = $22,638.480
3.	Lowest Revenue Generated:  Excel Formula Syntax =MIN (W2:W9801)                                                                                                                Returned value = $0.444
4.	Total Numbers of Sales Made:  
Excel Formula Syntax =COUNTA (W2:W9801)

5.	
Returned value = 9800
6.	Number of Cities where the Business Was Located:
Excel formula Syntax =SUMPRODUCT (1/COUNTIF(N2:N9801,N2:N9801)returned value
Returned value = 529 cities
7.	Determine the customers responsible for the highest and lowest sales generated by the company. 
•	The highest customer with sales
Excel formula used is VLOOKUP (lookup_value, table_array, col_index_num, [range_ lookup])  
VLOOKUP (22638.48, H2:L9801, 4, FALSE)
Returned value = SEAN MILLER
•	The lowest customer with sales
Excel formula used is VLOOKUP (lookup_value, table_array, col_index_num, [range_ lookup]) 
VLOOKUP(0.44,H2:L9801,4,FALSE)
Returned value = ZUSCHUSS CARROLL
8.	What is the total revenue generated in “Kentucky”
Excel Formular SUMIF(range, criteria, [sum_range])
= SUMIF(O2:O9801,"Kentucky",V2:V9801)
Returned value = $36,458.39.

## PIVOT TABLES
Pivot tables are one of Excel’s features. It is an interactive way to quickly summarize large amount of data. This is especially useful for querying large data hence making it very valuable for data analysis. In this analysis, the pivot table has been used to uncover patterns, trends, and insights within the data. Below we will be showing our values with pivot tables:

## CONCLUSION
In the US superstore dataset, we have examined and analyzed multiple user cases. By visualizing the data, we gained valuable insights into the variation of ship modes and categories among customers, which can be utilized for future improvements. Additionally, we identified the customers who generated the highest and lowest sales and the number of cities where the business is located.

## RECOMMENDATIONS
1. It is important to ensure that popular items such as phones, chairs, storage, tables, and binder sets are always available and not out of stock.
2. It is advisable to have technology and furniture products readily accessible for customers.
3. In order to stimulate increased purchases, it would be beneficial to offer a discount that is accessible during the holiday season.
4. The advertisements and campaigns should be targeted to prioritize those residing in the top 10 most performing cities.
5. Additionally, discounts should be offered for the least performing products to entice customers to order them.





