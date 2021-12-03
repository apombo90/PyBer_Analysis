# PyBer_Analysis
## Project Overview
Analysis done for a ride-sharing app (Pyber) to analyze all the rideshare data from January to early May of 2019 and create compelling visualizations that will help improve access to ride-sharing services and determine affordability for underserved neighborhoods. The analysis was done by completing the following tasks:

  1.  Create a summary DataFrame of the ride-sharing data by city type.
  2.  Create a multiple-line graph that shows the total weekly fares for each city type.

## Resources
- Data source: ride_data.csv, city_data.csv
- Software: Python 3.7.10, Jupyter Notebook
## Results

![image](https://user-images.githubusercontent.com/91766276/144371489-92616fa1-2081-4ded-9eb6-6caaeba8a027.png)

- Rural cities have the smaller number of rides with only the 5.3% of the total rides, followed by Suburban cities that had the 26.3% of the total number of rides and leaving Urban cities with the highest volume of rides, 68.4% of the total.
- The difference among types of cities is bigger in terms of number of drivers. Urban cities have the 80.9%, Suburban has the 16.5% and Rural 2.6% of the total drivers.
- Urban cities are generating the most revenue with 62.7% of the total fares, followed by Suburban cities with 30.5% and Rural cities with 6.8% of the total fares.
- Passengers are paying more per ride in Rural areas with an average of $34.62 per ride. This is almost $4 dollars more than the average fare in Suburban cities which is $30.97 and $10 higher than the average fare paid per raid in Urban cities ($24.53).
- The average fare per driver also has a considerable difference among the different city types. The average fare per driver in Rural cities is 334.8% higher than in Urban cities, $55.49 and $16.57 respectively. Suburban cities on the other hand, have an average fare per driver of $39.50.

![image](https://user-images.githubusercontent.com/91766276/144371631-93ea96d6-25bc-43c4-a858-d0a615a0b1e5.png)

- Weekly total fares have significant peaks among each city type. Rural cities had their lowest total weekly fare on the second week in January making only $67.65, whereas their highest peak was on the first week of April making $501.24. Suburban cities had their lowest total fare on the first week of January having only $721.60 in that week, but they had a high peak in the last week of February making $1,412.74. Finally, Urban cities also had their lowest total fare on the first week of January making $1,661.68 and they also have their highest peak in the last week of February reaching $2,466.29 total fares that week.

## Summary
- Urban cities have too many drivers, in fact they have more drivers than rides and the company could have more drivers in the Rural or Suburban areas where the demand is higher than the number of drivers. This will allow the company to reduce the number of drivers that are not producing any income in the Urban areas and at the same time it will meet the demand in the Rural and Suburban Areas.
- On average, Rural cities are paying the highest *fare per ride* and this underserved region could represent a higher profit for the company. This is worth considering to determine affordability for underserved neighborhoods specially when on average riders are paying $10 more per ride compared to Urban cities.
- Finally, it is possible to identify that there is a seasonal pattern specially in Urban cities where their total fare per week varies in a considerable amount every week. It would be important to find a relation like *weather conditions* to have a better understanding of what is causing more people to use PyBer in some weeks than others.
