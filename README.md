## Project Information:

In this project, I used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months' worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

I started by cleaning the data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Changing the type of columns (to_numeric, to_datetime, astype)

After cleaning up the data a bit, I moved to the data exploration section. In this section, I explored 5 high-level business questions related to the data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisements to maximize the likelihood of customers buying products?
- What product sold the most? Why do you think it sold the most?

To answer these questions I followed different pandas & matplotlib methods, which include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and line graphs to visualize our results
- Labeling our graphs
