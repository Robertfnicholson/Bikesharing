# NYC CitiBike Challenge – 
## Overview of Project
I used Tableau, a data analysis and visualization tool, to create powerful analytical dashboards that are visually appealing and easy for 
non-technical audience to understand. I prepared visualizations on NYC’s Citi Bike, a bike sharing service, for potential investors for a 
similar service in another city.   My Python code can be found in NYC_CitiBike_Challenge.ipynb. </p>

</p>

## Results
Using data from Citi Bike’s website, I downloaded the August 2019 trip dataset. This was to view the peak riding month for the bike sharing service. I used 
Python and Pandas to change the “tripduration” column from an integer to a datetime datatype. This allowed me to create a series of visualizations using this 
data. Visualizations created were the following:
*	Checkout Times for Users: this is a graph of the length of time that bikes are checked out for all riders. The graph indicates that most of the trips are 
under 20  minutes and a mode of 5-minute trip duration with 146,752 trips or 6% of the total 2,344,224 trips in the month of August 2019.
![Checkout_times_for_users.png](https://github.com/Robertfnicholson/Bikesharing/blob/462ac8f68989aa0c32f5186663ac3a3d5878f094/Checkout_times_for_users.png)
*	Checkout Times by Gender: this is a graph of the length of time that bikes are checked out by gender. Although males had more trips, the genders have similar 
trip duration with a mode of 6 minutes for males with 108,087 trips or 7% of the total 1,530,272 trips and a mode of 5 minutes for females with 34,151 or 6% 
of the total 588,431 trips.
![Checkout_times_by_gender.png](https://github.com/Robertfnicholson/Bikesharing/blob/462ac8f68989aa0c32f5186663ac3a3d5878f094/Checkout_times_by_gender.png)
*	Trips by Weekday for Each Hour: this is a heatmap showing the number of bike trips by weekday for each hour of the day. The rush hour times of 7AM-9PM 
and 5PM-7PM show the expected highest number of trips during these periods during the week but not on the weekend. The lowest level of trips is consistently 
the early morning hours of 12AM – 5AM. 
![Trips_by_weekday_for_each_hour.png](https://github.com/Robertfnicholson/Bikesharing/blob/462ac8f68989aa0c32f5186663ac3a3d5878f094/Trips_by_weekday_for_each_hour.png)
*	Trips by Gender – Weekday Per Hour: this is a heatmap showing the number of bike trips by weekday for each hour of the day by gender. The males have similar 
results as the overall pattern with highest number of trips during rush hour, likely for commuting to work. Females show more dispersion of trips across the day 
and over the weekend.
![Trips_by_gender_weekday_per_hour.png](https://github.com/Robertfnicholson/Bikesharing/blob/462ac8f68989aa0c32f5186663ac3a3d5878f094/Trips_by_gender_weekday_per_hour.png)
*	User Trips by Gender by Weekday: this is a heatmap showing the number of bike trips broken down by gender for each day of the week by each Usertype. The 
heatmap shows that the Subscriber type, those riders with a longer-term subscription to the service, tend to use the service more during the week than the 
weekends. The customer type, those riders with a on-demand access, use the service more evenly throughout the week. This rider type is likely more tourist oriented. 
![User_trips_by_gender_by_weekday.png](https://github.com/Robertfnicholson/Bikesharing/blob/462ac8f68989aa0c32f5186663ac3a3d5878f094/User_trips_by_gender_by_weekday.png)
The next four graphs are contained in the Trip Detail Dashboard shown below.
*	Average Trip Duration: this graph displays the average trip duration by the rider’s birth year. This shows that younger riders tend to have longer average 
trip duration.
![Trip_detail_dashboard.png](https://github.com/Robertfnicholson/Bikesharing/blob/5e34dc533dde64f0eeee6ab04cd22114f814fbc2/Trip_detail_dashboard.png)
*	Bike Utilization: this is a heatmap providing the number of trips by Bikeid. This will assist in identifying the bikes with the highest utilization rates, 
those in dark color, for a preventative maintenance program. 
*	Top Starting Locations: this is a heat map of the top trip starting positions. This can assist in relocating bicycles, if necessary, to maximize utilization 
rates.
*	Top Ending Locations: this is a heat map of the top trip ending positions. This can assist in relocating bicycles, if necessary, to maximize utilization rates.



The visualizations can be found at [link to dashboard](https://public.tableau.com/app/profile/robert.nicholson8820/viz/NYC_Citibike_Challenge_16465803716180/NYCCitibikeStory?publish=yes).</p>

## Summary
The analysis revealed the following:
*	In Aug 2019 riders took 2,344,224 trips on the bike sharing service.
*	Most of the bike trips were under 20 minutes with a mode of 5-minute trip duration with 146,752 trips or 6%.
*	Trip durations were similar between males and females with a mode of 5 minutes for males and 6 minutes for females.
*	The bike service has the highest usage during weekday rush hour times of 7AM-9PM and 5PM-7PM but not on the weekend. The lowest level of trips is 
	consistently the early morning hours of 12AM – 5AM. 
*	The Subscriber type tend to use the service more during the week than the weekends. The customer type tend to use the service more evenly throughout 
the week. This rider type is likely more tourist oriented. 
*	I suggest getting data and creating visualizations on the rates charged to customers, particularly those for the customer type on a weekday and hourly 
basis per weekday. This can assist in maximizing utilization rates and profitability.
