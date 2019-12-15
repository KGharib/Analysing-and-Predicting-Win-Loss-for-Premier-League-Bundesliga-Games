# project2_football_analysis

## Author: Khalid_Gharib

### Introduction
We will use SQL, OOP, API and NoSQL to analyse our data, perform EDA on our Data and then use an API key to request the Weather on games played in 2011. and then export the Data into a NoSQL
### Summary Methodology
i used SQL to import our data to jupyter and performed EDA on the data with a mixture of SQL and Pandas to extract the answer to the questions we were given. i then used matplotlib to plot our results.

i then requested the weather from DarkSky based on the dates of games played in the 2011 season using an API key. i exported the results into an csv file so i didnt have to keep making requests as we had a limited number of requests per day.

then i used MongoDB to export each questions dataset and also to export the plots.

### Summary Findings
we found the number of goals scored, the wins, draws and loses of each team in the 2011 season. we can see taht most of the teams were from Bundesliga.

we also saw in our dataset that when we used an API request to get the weather data many of them were Null values and there were very few rainy days where games were played and thus showing the percentage of wins in rainy days to total wins of each team would be a negligant % so i chose rather to show then number of wins/losses and total games played by each team in rain.

finally i used pymongo to export our data

### Conclusion
final notes on this would be that the dataset seemed very simple at first glance but when performing EDA i noticed the format was not very easy to perform EDA on, so we had to do a perform a mixture of SQL with Pandas to collect and extract the neccessary date.

also on top of that the limitation of 1000 request was something i had to keep into consideration since i wanted to get the weather on about 900 entries and so i would only have one chance, so when it worked i made sure to export it into a csv file so i can call upon it without worry.

the Dataset was interesting and i would like to redo this again and apply OOP more thoroughly and also attempt to answer more questions on the data set. 
