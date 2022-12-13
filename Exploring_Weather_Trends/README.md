Summary:

This project analyzes and compares local (Philadelphia City) temperature data with global temperature trends. This project aims to visualize and describe the similarities and differences between global and local temperature trends.

Tools used:

1.SQL 

	writing the query to get the data from database and downloaded the same to .csv file. 
	To get the data I’ve written the following query: 

		SELECT * 
		FROM 
			global_data  
		SELECT 
			year, city, avg_temp 
		FROM 
			city_data 
		WHERE 
			city = ‘Philadelphia’


2.	I’ve used Excel and Python for Data Visualization

	(i) Using Excel:
 
	In new excel worksheet I imported the .csv files (global_data.csv & city_data.csv). Next, calculated the moving 	average for 20 rows using the formula 	“=AVERAGE(column1:column20).” Plotted the line chart with “Years” in X axis and 	“Temperature(°C)” on Y axis. 


	(ii) Using Python: 

	The global_data.csv file and the city_data.csv file were read in Python using "pandas as 	pd"; 

	“NumPy as np” library is used to calculate the moving average (calculated for 20 	years). Moving average was 	calculated using rolling mean function 	{df[‘column_name’].rolling(rolling_window).mean()} 
	(Reference taken from https://www.statology.org/rolling-mean-pandas/) 

	“Matplotlib as plt” library is used to visualize the data. 
	The line chart was plotted with “Years” in X axis and “Temperature(°C)” on Y axis using 	‘plt.legend()’ 	function.xlabel() and ylabel() functions to set a label for the x- and y-	axis. title() function 	to set a title for 	the plot. Labelling the chart as “Weather 	Trend.” 

 
Conclusion:

The observations about the similarities and differences between the world averages and your city’s averages, as well as overall trend are made.

 - Philadelphia city’s temperature has been higher than the global temperature over time. 
 - As the global temperature has been on rise over the years, the Philadelphia city’s                                   	temperatures has also been on rise. 
 - Both the global and local temperatures show an upward trend, i.e., the world is getting 	hotter
 - Overall Philadelphia city’s average temperatures show that Philadelphia is much hotter than global average temperatures 	and the difference is consistent. 

