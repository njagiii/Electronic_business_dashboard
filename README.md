# Electronic_business_dashboard

The duplicates have been highlighted in red colour.
The data has been formatted to the correct data types i.e orderdate and requireddate to dates, numbers to numbers, unit cost to currency, SKU to text, quantity to number etc..
Blanks have been replaced with: unknown city, unknown salesperson and unknown channel for the respective columns.
Negative unit values were identified and converted to positive values.
Identified the discount percentage >30 and replaced them with null and then calculated the mean and replaced the nulls mean 
Used IF to swap required dates that were earlier than order date. Then generated the lead time (required date-ordered date)
Utilised Quartile function and divided unit prices based on 25th, 50th and 75th quantiles to develop price bands.
A pivot table to show the first month a specific country appeared on the orders and the gross revenue for that month.
ABC analysis was done and colours were assigned to different classes i.e A - Blue, B - Green and C - Orange
Asales productivity pivot table has been created to show salespersons with the highest orders overall.
A revenue share pivot table has been created and a pie chart was used to visualize sales per region using different channels in Africa and Asia, the retail channel dominated while in America and Europe the online channel dominated
A scenario panel has been created on the dashboard with its own KPIs.

The highest revenue collected per month in Africa occurred in the Sixth month
In America, online channel dominated all other channels
In Asia, the retail channel dominated all other channels
In Europe, United Kingdom had the highest gross revenue
In Europe, the retail channel made losses

