# PyBer_Analysis

Overview of the analysis:

We were tasked with creating a summary dataframe that will show the ride sharing data for Urban, Suburban, and Rural city types.
The end result of our analysis will be a multi-line graph that shows the weekly fares by each city type.

Using Pandas functions groupby, count, and sum, we were able to get the total number of drivers, rides, and fares aggregated by city type. This allowed us to then calculate the average fare per ride and driver. Using that information, we then created a new dataframe to reformat the columns in order to be able to piviot and resample the data, allowing us to create a multi-line graph. The graph shows the total fares, by week for each city type, between January and April of 2019.

#A review of the data shows the following:

- Rural cities had the lowest number of drivers, the lowest total fare amount, as well as the lowest averages for fare per ride and fare per driver.
- Suburban cities had roughly 5 times the number of rides as Rural areas, but only 2.5 times fewer rides than Urban. They fall roughly in the middle for number of drivers when compared to Rural and Urban.
- Unsurprisingly, most likely due to population density, Urban cities have the most rides, the most drivers, and the highest total fare.


- While Rural areas have the fewest drivers and have lower numbers of both rides and fares, their averages are the highest. This is most likely due to the distance traveled. Being able to pull mileage data as well would help prove or disprove this point.
- It's almost a given that Urban cities will have the most drivers, rides and fares. Because of this, they end up with the lowest average of fare per ride and fare per driver. This is most likely due to a high number of low mileage trips. Again, the addition of mileage data would help clarify this.

<img width="629" alt="PyBer RideShare Summary" src="https://github.com/ssheggrud/PyBer_Analysis/blob/fdd44b3790bb751e9d54b2fa7bbcde322ecacb55/analysis/pyber_summary.png">


# Total Fare by City Type chart between January & April of 2019

<img width="634" alt="Total Fare by City Type" src="https://github.com/ssheggrud/PyBer_Analysis/blob/fdd44b3790bb751e9d54b2fa7bbcde322ecacb55/analysis/Fig8.png">

Summary

After examining the data, we are able to tell what the average fare tends to be based on the originating city type. We have a solid overview of the variations that happen week by week, and could project what to expect in the upcoming months, barring unforseen circumstances like what was experienced during 2020. 


# Recommendations 

1. Consider a more indepth analysis involving the average mile per trip. This will help with decisions regarding discounts based off mileage.
2. For all areas, further analysis might be necessary to see how many passengers per ride there are, especially in Urban areas. Ridesharing could be part of the reason why theh average fare per driver is much lower in the Urban areas. 
3. Because there are significantly fewer drivers and passengers in Rural and Suburban areas, it could be useful to look at incentives to encourage people to use PyBer as opposed to their personal vehicles. A further analysis that compared the cost of driving a personal vehicle (gas, wear & tear, parking, time) to the savings of using PyBer for the daily commute could increase service in underserved areas.