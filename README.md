# Pyber_Analysis

## Overview of the analysis:

Working as a data anaylyst for Pyber, a Python based ride-sharing app company. My assignment was to perform an exploratory analysis on data in some very large csv files. To aid this process, I created several types of visualizations that told a compelling story about the data. I wrote Python scripts using Pandas libraries, Jupyter Notebook, andMatplotlib to create a variety of charts that showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders and drivers by type of city. The analysis and visualizations I produced will help Pyber improve access to ride-sharing services and determine affordibility to underserved neighborhoods.

## Results: 

For results we will be taking a look at the differences in ride-sharing data among the different city types. Those different city types are; urban, suburban and rural.

### Total Rides

Total rides for Pyber’s three different city types varied greatly. Urban rides, where we would expect the most usage, had 1,625 rides.  Rural city type, which had the leat amount of rides had only 125. In image 2 (pie chart) below, shows total rides by city type as viewed by percentages. Those 1,625 urban rides made up nearly 70% of Pyber's total ride count.

<img width="600" alt="total_rides" src="https://user-images.githubusercontent.com/102890151/167330602-c515fcbd-dc76-454e-99a5-c539b38d7f73.png">

image 2

<img width="270" alt="total_rides_city_type" src="https://user-images.githubusercontent.com/102890151/167328346-f81cb82c-775e-4713-a52a-a5d4b223f4b6.png">


### Total Drivers

Urban city type had the most rides and the most drivers at 2,405 (seen in table below). Urban city type actually had more drivers than total rides (1,625 rides vs 2, 405 drivers). This was the only city type to have more drivers than riders.

<img width="600" alt="total_drivers" src="https://user-images.githubusercontent.com/102890151/167330795-9c5cefa5-4e33-4d45-b390-fa540c98ebda.png">

<img width="300" alt="total_drivers_city_type" src="https://user-images.githubusercontent.com/102890151/167328313-a02d4870-96b5-41c9-8a6b-2333ea9977e7.png">

Total drivers as viewed by percentage (above)


### Total Fares

Urban city type made just under $40,000 dollars or roughly 62% of total fares. Recall the Urban city type had roughly 68% of total rides. Rural city type made up 6.8% of total fares and had 5.3 % of the total rides. see images below

<img width="600" alt="total_fares" src="https://user-images.githubusercontent.com/102890151/167330963-8115b18a-d016-456a-bf33-c9e5f0b742a5.png">


   <img width="270" alt="total_fares_city_type" src="https://user-images.githubusercontent.com/102890151/167328228-40ed960c-c53b-432d-9b2d-e351ef575dc9.png">



### Average Fare per Ride and Driver


Shown below are the average fare by ride and by driver. Fares in urban city type were the smallest amounts, as reflecting shorter trips, as one would expect.  The difference wasn’t that significant, however, if we look at average fare per driver, the difference is dramatic. Rural drivers average fair was $55.49 vs an urban drivers average fare at just $16.57


<img width="550" alt="av_fare" src="https://user-images.githubusercontent.com/102890151/167331548-4487a391-8bc3-49c0-aedf-ae689e4ee111.png">

<img width="550" alt="av_fare_city_type" src="https://user-images.githubusercontent.com/102890151/167331638-e509a194-04a7-46ad-abba-31a595c8e403.png">


Bubble chart below showing the average fare by city type. As the data reflects we can see in the bubble chart that there are far less drivers (size of bubble) and the average fare in rurla areas is higher than it's counterpart city types.

<img width="740" alt="download" src="https://user-images.githubusercontent.com/102890151/167328061-bf528b4f-bdd8-4aa7-b6ac-6bb026638045.png">


### Total Fare by City Type

Lastly, looking at total fares by city type we can see that urban city type had the consistently the highest fare total. Rural city type had the steadiest total fare with urban being next.  Both suburban and urban city types had higher total fares in April, than January when data was collected. Noted was a spike for all 3 city types the 3rd week of Feb.


<img width="648" alt="Pyber_fare_summary (1)" src="https://user-images.githubusercontent.com/102890151/167328132-9dc34c11-8e03-40d9-9525-610ee09c1280.png">


## Summary: Three business recommendations to the CEO for addressing any disparities among the city types

The following recommendations might be considered to address any disparities among the city types. 

Urban city types was the only city type to post more drivers than rides. This might indicate an excess of drivers. Is this just one city with an excess of drivers, several urban cities or is this company wide for urban cities. Further analysis should be done. 

Suburban cities make up 17% of Pyber's drivers in suburban areas, but they currently make up 30% of total fares. While the number of drivers in the urban areas is nearly 5 times greater the total number of suburban drivers, the total revenue from the urban cities is only twice of that of suburban city types. As mentioned above, with the excess in urban drivers the possibly of reallocating some urban drivers to suburban areas might be benificial and possibly with that re assignment might be able to bring some of that profiability with them to the suburban areas.

As noted in above in graph, "Total fares by City Type" there was a noted increase in activity in late February. Does this increase happen yearly, or was this just a one time occurance? If the spike is a yearly occurrence, this demand could be anticipated and taken advantage of by fielding a larger number of drivers in each market for greater profitability.
