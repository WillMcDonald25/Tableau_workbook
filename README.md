# Tableau Challenge

Overview:

	In this project I attempt to use Tableau to visualize Citi Bike data. The data showcases popular Citi Bike stations throughout New York City based off the number of rides at each station. I acquired that data from the Citi Bike website, and chose three months from the year 2019, each month being its own separate CSV file. I used a Pandas notebook to congregate the three separate CSV files into one dataframe in order analyze all the data collectively. I then saved that one single dataframe as a single CSV file and loaded it into Tableau to begin analyzing and visualizing the data. 

Start Station Analysis Dashboard:

	Throughout all the Citi Bike stations in New York City, the one located at Grove Street seems to be the most popular by a longshot. Between October and December of 2019, over 10,000 rides started there from the dataset. This is much more than double than any other station in the dataset. Here you can also see the lowest ten performing start stations with the lowest being the station on Union Street. This dashboard also includes a map of all the different start stations in the city. The circles are all different colors so you can see which ones are different, and the size of the circle depends on how popular the station is (bigger the more total rides). This dashboard includes the ability to filter the data by month (either October, November, or December). It also includes the ability to select a single station at once. 

End Station Analysis Dashboard:

	This dashboard is the same thing as the start station dashboard except it includes all the data for the ending stations. The station at Grove Street continues to blow all the other stations out of the water with the greatest number of total rides. This dashboard shows the lowest end stations being a tie for last with only one ride ending at these specific stations. Like the first dashboard, you can filter out the month and the specific station if you’d like. 


Customer vs. Subscriber Analysis Dashboard:

The final dashboard details the distribution of the number of total rides between the paying subscribers of the Citi Bike service, and regular paying customers. Throughout the months October through December, the subscriber count is significantly higher than the customer count. You can see it is separated by color with subscriber count in orange, and customer count in blue. 
![image](https://github.com/WillMcDonald25/Tableau_workbook/assets/125604331/48db3c1c-4972-4463-8b2a-dbb0f589766a)
