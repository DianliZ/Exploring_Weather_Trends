# Exploring_Weather_Trends

## Outline:
### 1.	Write SQL query to extract data from the temperatures database:
1)	Select * From city_list—to extract a list of cities and countries and download it to find the nearest city;
2)	Select * From city_data—to extract the average temperatures for each city by year (ºC);
3)	Select * From global_data—to extract the average temperatures for each city by year (ºC);
4)	Download the results to a CSV.
### 2.	Calculate the moving average:
1)	Copy data for Seattle from coty_data list, and paste data to global_data list. Save to Excel Worksheet;
2)	Delete gap data and use data from the year 1847 through 2013; 
3)	Since there are average temperatures for 158 years, use AVERAGE() function to calculate the 10-year moving average temperatures for both Seattle and global to smooth out data to make it easier to observe long-term trends and not get lost in yearly fluctuations. 
### 3.	Draw line chart to compare 10-year moving average temperatures of  Seattle with the  global one:
1)	Use data of Global 10 yr MA and Seattle 10 yr MA to create line chart;
2)	Edit Axis and Titles.
Line chart:
 
 
## Observations:
1.	Average temperatures for both Global and Seattle are increasing from 1847 through 2013;
2.	Global temperatures are increasing smoother than Seattle temperatures;
3.	From 1945 to 1956, temperature drop in Seattle is more significant than globally;
4.	Overall, global temperature increased from 8.059 ºC to 9.556 ºC, and Seattle temperature increased from 7.355  ºC to 8.336 ºC.
