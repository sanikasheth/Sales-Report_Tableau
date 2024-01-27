# Sales-Report_Tableau
Creating a dashboard using Tableau to visualize the sales report

#Datasets:
Sample Superstore

#Business Scenario:

A manager has to submit a monthly sales report to her director. She needs to show the monthly trend in sales across various products, distinct orders placed by the customers and the performance of those customers, With the help of this analysis, the manager and her director want to reform their sales strategy and take substantial measures for upcoming orders and for the next year.



#Steps to perform:
1.	Create a custom date on Order Date at Month/Year level 
2.	Create a Highlight table with Order Date (Month/Year), Category, and Sales 
3.	Add Profit Ratio to the tooltip
4.	Sort months by profit ratio in descending order
5.	Create a parameter to dynamically change Dimensions in a view 
6.	Create a parameter to dynamically change Measures in a view
7.	Create the calculated fields using these parameters 
8.	Create a view using these calculated fields
9.	Create a calculated field to show distinct orders placed by the customer using an LOD calculation
10.	Create a calculated field to generate the rank of customers using the index function
11.	Create a view using these calculated fields
12.	Break the view by placing the customer name in detail
13.	Color the view with profit
14.	Set the scope of table calculation applied to rank as customer name
15.	Sort the calculations in ascending order based on profit
16.	Change the default color of marks using the color property
17.	Combine the Orders, Returns, and People tables
18.	Use inner join to combine Orders and People tables
19.	Use the left join between Orders and Returns table
20.	Create the required view
21.	Enable mark labels


#Answers
Based on the view, these are the answers to the questions in the problem statement:

1.	In August 2022, which category recorded the highest sales?=>Furniture
2.	Which month in 2022 has the highest accumulated profit ratio across all product categories?=>December
3.	Which customer has generated the highest sales?=>Tamara Chand
4.	Which Sub-Category has the lowest profit?=>Tables
5.	Which customer is generating the highest profit, and what is the value and number of orders placed by that customer?=> Tamara Chand,orders placed 5,Profit-8981
6.	Which region has the highest number of products returned by customers? =?central
7.	Which is the least profitable state?=>Texas

#Dashboard:

![image](https://github.com/sanikasheth/Sales-Report_Tableau/assets/78950430/3ce3c4c2-2e98-4cb2-8969-65be97752f45)

#Link to Live dashboard on Tableau:
https://public.tableau.com/views/Customdataex/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link



