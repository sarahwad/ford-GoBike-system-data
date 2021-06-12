# Ford GoBike System Data Exploration
## by Sarah Alwadaah


## Dataset

The dataset for Ford GoBike system that includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area and can be found in [Ford GoBike System Data](https://www.fordgobike.com/system-data). The data I chose covers entries from June 28th 2017 to December 31st 2019 has 4890404 rides and 15 features, after the cleaning process it became 12 features. 


## Summary of Findings

In the exploration, I looked at user types where subscibers make up the vast majority
with a pie chart to show the difference. I looked at the average duration which was 
10 mins and distance that was 1-1.5 km using histogram to plot continues numerical 
variables. I also looked at the top ten start stations with a bar chart describing 
categorical data. Then I plotted the distribution of rides by month by subplotting 
each year that told me winter has the least number of rides.

Using regression linear function and another scatter plot with transparancy for 
handling overplotting, I found that the relationship between duration of rides and 
distance is very weak unlike my initial assumption with r = 0.039, which disregarded 
many plotting ideas I had in mind. I explored duration and distance further more by 
introducing user type as a second variable in a boxplot which told me that customers 
take the longest rides in both duration and distance.

Lastly, I explored my two main variable of interests distance and duration with month
of each year and user type. The first multivariate plot using pointplot for duration 
with year_month and user type showed very interesting decrease in duration for 
customers over the years and a stable almost consistant duration for suscribers.


## Key Insights for Presentation


For the presentation, I focus on duration and distance mostly and their relationship 
with user type and month of the year. At first I showed my variable of interest in 
univariate plots to introduce them for later plots. I showed user type pie chart 
with percentages to tell that subscibers make up the majority. Then the histograms 
for duration and distance side by side to show their distribution over the number of 
rides. Then I displayed the 3 bar chart indicating the number of rides by month for 
each year.

Afterwards, I showed a two bivariate plots side by side of duration and distance of 
rides dy user types that showed customers use the bike-sharing system for longer rides 
compared to subscriber.

Finally, I introduced the month of the year to my previous bivariate duration plot to 
make a multivariate plot of duration of rides by months for each user type. This gave 
interesting result of declining ride duration made by customers throughout the years 
while it remained the same for subscribers, it also showed that month of the year had 
little to no affect on customers using bike-sharing system unlike subscribers.
