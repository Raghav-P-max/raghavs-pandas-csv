## IMPORTING LIBRARIES
First, pandas is imported using 'import pandas', designed for data manipulation and storage
Then , matplotlib.pyplot is imported, a library used to create data visualizations and manipulations.

## LOADING FILES
Next, the contents of csv file are loaded as:
                     Bike   Price  Number_sold
0  Royal Enfield Himalayan  300000           70
1    Royal Enfield Classic  180000          100
2               TVS Apache   95000          100
3           Hero Splendour   85000          150
4              Bajaj Pulsar  80000          180

## PLOTTING TABLES AND GRAPHS
Then, the function 'df.head()' loads only the first 5 rows of the table,, which already consists of only 5 rows.
Then, we create a new column called - "Total_revenue" by multiplying the contents of the columns:"Price" and "Number_sold"
Then, all the contents of the column : "Total_revenue" are added using sum() function.

To create a bar chart of total revenue, 'bike model' is plotted against x axis and 'revenue' is plotted against y-axis.

Next, to calculate total number of bikes sold, all the contents of the column: "Number_sold" are added using sum() function.
Similarly, the bar graph is plotted by plotting 'bike model' along x axis, and 'number of bikes sold' along y axis.
