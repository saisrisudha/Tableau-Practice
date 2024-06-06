# Tableau-Practice

Charts & Quick Table Calculations

1
---

Create a table with columns such as category, sub-category in rows and region in columns with total sales and total profit shown for each region along with grand total and percent of pane total sorted by sum of sales in descending manner as shown in below image.
 



Data Combining Techniques & Filtering

2
---
From the Netflix Titles dataset, merge tables using Inner Joins and identify the actor/actress with the highest number of appearances in Sports Movies. Provide the name of the actor/actress and the corresponding movie titles they've starred in.




LODs & Histogram
3
---
Create a Tableau histogram displaying the count of customers based on their order frequency, with the number of orders on the x-axis and the corresponding customer count on the y-axis
 

Sets
 4
---
Create a pie chart showing Top 50 customers Vs Other customers with respect to sum of sales shown in below image.

 
Custom Visual: KPI Card & Table Calculations

 5
---
Create a Tableau KPI card showcasing 
•	total profit for the current year (last year of the dataset)
•	percentage growth from the previous year, indicated by a green upward arrow with a "+" sign for positive growth and a red downward arrow with a "-ve" sign for negative growth.
•	Incorporate a line chart depicting monthly profit trends for the current year. 

Note: 
Copy and paste the signs from below:
“▼"  , "▲" 
 

Parameters & Groups

 6
---
1) Create the parameter with name as View by. Use three values in parameter i.e., Region, Category and Sub-category. If the user selects any value, then show the sum of sales with respect to the value chosen in the parameter as a bar chart. E.g., If the user selects a category, then show category wise sales. Make sure to edit the worksheet title w.r.t. View by value.

2) Make groups for Acco, 3M, Samsung, Apple, Xerox products. (For remaining products included in others folder). Display each group as an average discount percentage.

Dashboard

7
---
Develop a Tableau dashboard utilizing the Sample Superstore dataset, as shown in below figures. The formatting / labelling / spacing / alignment should be the same as used in the charts. The Dashboard should have the following features:

Features:

a)	Divide the dashboard into two planes. The left plane will feature the company logo, interaction controls, and filters for year and region. The right plane will contain 6 dynamic visualizations and 3 Key Performance Indicator (KPI) cards based on selected metrics.
o	Profit Margin = total profit/ total sales
o	Return Rate = quantity returned/ quantity ordered

b)	Create a parameter “Metric” that will allow users to select a metric for analysis from options including sales, profit, and no. of orders (# Orders). Visualizations will dynamically adjust based on the selected metric, with titles and tooltips changing accordingly. For instance, if "sales" is chosen, the visualization will display "Sales by Category."
  


c)	Implement filtering options for year and region, allowing users to further refine their analysis. Include a button to hide/display both filters for improved viewing experience.
  

d)	Ensure that the dashboard consistently displays the top 5 products based on the selected metric, regardless of any filter actions or dropdown selections made by the user.

e)	Implement a filter action on the category chart to dynamically filter data in the other five charts and KPI cards upon interaction. 

f)	Clicking on the logo should redirect users to the dashboard published on Tableau Public.

g)	Display Average and Trend Lines where required.

h)	Find the dashboard logo and filters logo attached below.




















