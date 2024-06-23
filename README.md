Data Cleaning
In this section, we focus on refining our dataset through the following tasks:

Eliminating rows with missing values.
Removing rows based on specific conditions.
Converting column data types (using to_numeric, to_datetime, and astype).
Data Exploration
After tidying up our data, we delve into exploring key business questions, including:

Identifying the month with the highest sales and the corresponding revenue.
Determining which city had the highest product sales.
Finding the optimal time to display advertisements to increase the likelihood of customer purchases.
Discovering which products are frequently bought together.
Identifying the top-selling product and exploring the reasons behind its popularity.
Methods and Techniques
To answer these questions, we utilize various pandas and matplotlib techniques, such as:

Merging multiple CSV files into a single DataFrame using pd.concat.
Adding new columns to the DataFrame.
Parsing cell values as strings to create new columns using the .str accessor.
Applying functions to DataFrame columns with the .apply() method.
Performing aggregate analysis with the groupby method.
Visualizing our findings through bar charts and line graphs.
Adding appropriate labels to our graphs for better clarity.
