# Ford GoBike System Data Exploration
## by Emmanuel Boluwaji Adeyeye


## Dataset

The explored dataset originally contained information about 183,412 rides made in
February 2022 in a bike-sharing system covering the greater San Francisco Bay area. 
The attributes include the start and end times of the rides, the year of birth of 
the user, and the user type. The start and end times variables were converted into 
DateTime datatypes, and the ride duration which was in seconds was converted to minutes. 
New variables were also extracted: the hour and the day of the week from 
the start and end times variables and Member age from the year of the birth variable 
before being cut into bins. 8780 data points were removed from the analysis due to 
inconsistencies or missing information. Irrelevant variables were dropped too.


## Summary of Findings

In the exploration, I found out that there is a strong relationship between the user 
type and the average ride duration, with modifying effects from the start hour and the 
day of the week the ride was made. Though there are more subscribers than customers, 
the latter spend more time per ride. The number of rides made on weekends (Saturday 
and Sunday) by subscribers is significantly lower than that of weekdays whereas customers 
make almost the same number of rides on weekends as weekdays. However, the average ride 
duration made on weekends is significantly higher for both user types, with customers 
having a higher ratio of the average ride duration on a weekend day to that of a weekday.


## Key Insights for Presentation

For the presentation, I focus on the effect of user type, start hour, 
and day of the week on the average ride duration. I start by introducing the
ride duration variable.

Afterward, I introduce user type using a pie chart to show the proportion of the values. 
It is followed by the average ride duration for each user type, and over time (start hour 
and day of the week). The distribution of user type over time is taken next.
Finally, I show the average ride duration for each user type over time using 
point plots. I used different color palettes for each user type variable to show the 
difference between plots.