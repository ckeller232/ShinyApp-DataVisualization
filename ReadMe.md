# Shiny App created in R to visualize sales of Superstore data over roughly a 4 year time frame

### On the top of the main page, the user will see the total number of orders and total sales (in dollars) for the selected criteria (it is interactive).
### App allows the user to look at a Geo_plot, hover over each state, and visualize the total sales and state name.
### App also shows a time series plot, that allows the user to interactively change the trends (days, weekly, monthly, quarterly or annually)
### There is a second page in the app that has tables.  The main table summarises Sales, Profits and Number of Orders grouped by State and the Category of the sale.
### The bottom two tables show the same summaries, but are grouped by State and Subcategory (left table) and by State only (right lower table).
### The third page of the app includes additional visualizations such as Time Series plot by Sales Category, a Sales vs Profits dot plot (also by Category) and a total sales analysis by Region.
### All visualizations on the third page of the app are also interactive where the user can use the filter on the main summary panel to filter what they want to see.


### The app inludes reactive buttons that allows the user to look at both the visualizations and the tables by selecting certain date ranges, categories, sub-categories or specific states as filters.
### To reset the app to its default state, simply hit the 'Reset' button in the app.



# Note: dataset is an open source dataset downloaded from Kaggle. Dataset has 9994 rows and 21 column variables. R and R-Studio version 4.2.1 or newer should be used.  Once the file is knitted and run, open in a Web Browser for best performance and to utilize the scroll bars on the tables.  Link is found below:
###  https://www.kaggle.com/datasets/vivek468/superstore-dataset-final