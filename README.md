# Sales_analysis_python
Data analysis of sales of electronics products over a period of 12 months using Jupyter notebook.

In this Project I will use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I start by cleaning our data. Tasks during this section include:

~Droping NaN values from DataFrame
~Removing rows(duplicates) based on a condition
~Changing the type of columns (to_numeric, to_datetime, astype)
~Once I cleaned up our data a bit, I will move the data exploration section. In this section I will explore 5 high level business questions related to our data:

Q1.What was the best month for sales? How much was earned that month?

![image](https://user-images.githubusercontent.com/123319398/224082676-4e09fd6a-61c8-4049-8cec-f9f8b6431751.png)

Q2.What city sold the most product?

![image](https://user-images.githubusercontent.com/123319398/224082844-368c132a-88a7-4ff1-b598-8d256444ece7.png)


Q3.What time should we display advertisemens to maximize the likelihood of customer’s buying product?

![image](https://user-images.githubusercontent.com/123319398/224084628-56da6007-339f-4dea-bb03-3db40f70e582.png)


Q4.What products are most often sold together?

![image](https://user-images.githubusercontent.com/123319398/224085914-906abbac-06b1-42ad-a38c-2452b81e7ccb.png)


Q5.What product sold the most? Why do you think it sold the most?

![image](https://user-images.githubusercontent.com/123319398/224086060-b00ea162-8150-42b7-a6d1-126130f4673c.png)


To answer these questions I used different pandas & matplotlib methods. They include:

->Concatenating multiple csvs together to create a new DataFrame (pd.concat)
->Adding columns
->Parsing cells as strings to make new columns (.str)
->Using the .apply() method
->Using groupby to perform aggregate analysis
->Plotting bar charts and lines graphs to visualize our results
->Labeling our graphs
