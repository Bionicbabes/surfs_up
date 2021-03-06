# **Surfs Up**

----------------------------------

# **Overview of the analysis**

----------------------------------

* W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

----------------------------------

# **Results**

----------------------------------

# **Deliverable 1: Determine the Summary Statistics for June**

* Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

![deliverable_1.PNG](https://github.com/Bionicbabes/surfs_up/blob/main/Resources/deliverable_1.PNG)

# **Deliverable 2: Determine the Summary Statistics for December**

* Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

![deliverable_2.PNG](https://github.com/Bionicbabes/surfs_up/blob/main/Resources/deliverable_2.PNG)

----------------------------------

# **Summary**

----------------------------------

* Looking at the Temperature data we can see that the from June to December the mean temperature only decreasing by four degreee ( 75 F to 71 F).  With the plans of opening up a surf shop this make for an ideal situation.  We analyize the data even further to see that in both months that standard deviation is between 3.2 to 3.7, meaning that the fluctuation in temperature remains fairly stable.  Investigating a bit further we can look at the max temp and the min temp in June min/max is 64/85, and in December min/max is 56/83.  Given the stablity I would definitely move forward with the surf shop based on temperature analysis. 

* We were also given the percipitation data, and i think that this would be more telling of whether we would be able to keep consistent cash flow from people renting surf boards.  If it is raining out it is highly unlikey to rent board and keep the shop open.  We have made a query to look at the 8/23/2016 to 8/23/2017 which is a 1 year snap shot of the most recent data.  


![percip.PNG](https://github.com/Bionicbabes/surfs_up/blob/main/Resources/percip.PNG)

* To open this surf shop i think there is a lot more analysis that will need to happen to ensure a successfull business.  I would want to look into tourism data and compare that to weather data to make sure that during peak times it is not raining. 













