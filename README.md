# Sales_analysis1

We used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.
<br>
We start by cleaning our data. Following steps we performed:
<br>
Drop NaN values from DataFrame.
<br>
Removing rows based on a condition.
<br>
Change the type of columns (to_numeric, to_datetime, astype).
<br>
Once we have cleaned up our data a bit, we move the data exploration section. 
<br>


What was the best month for sales? How much was earned that month?
<br>
What city sold the most product?
<br>
What time should we display advertisemens to maximize the likelihood of customer’s buying product?
<br>
What products are most often sold together?
<br>
What product sold the most? Why do you think it sold the most?
<br>
To answer these questions we walk through many different pandas & matplotlib methods. They include:

Concatenating multiple csvs together to create a new DataFrame (pd.concat)
<br>
Adding columns
<br>
Parsing cells as strings to make new columns (.str)
<br>
Using the .apply() method
<br>
Using groupby to perform aggregate analysis
<br>
Plotting bar charts and lines graphs to visualize our results
<br>
Labeling our graphs
