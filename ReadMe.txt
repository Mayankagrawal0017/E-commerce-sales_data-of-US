This is the analysis of sale data of  US E-commerce website to find the answers of key qustions 
which are common qustions ask by any E-commerce compony to imporve their sales.


# EDA Useing Pandas And Matplotlib
Data analysis of real world Sales_data using the Python Pandas and Matplotlib librarys.


## Content
This Repo has csv file "Sales" for analysis has  185950 rows and  6 columns and we also have 
a folder " Sales_Data " containing the the sales data for each month sepratly in 12 diffrent csv files.

List of columns:
1: Order ID  
2: Product	
3: Quantity Ordered	
4: Price Each	
5: Date	
6: Order Purchase Address


The other file "Analysis of sales_data"  is a notebook in Ipython formate  containing my code with all the key notes to 
help you understande my approche.

And last file "graphs" has all my answers in form of gaphical data.


# Tasks
"Merging the diffrent csv files to form sales csv" 
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

# Key Question which I answered with the analysis:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What product sold the most? Why do you think it sold the most?

To answer these questions i used diffrent methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs