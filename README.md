# PyBer_Analysis
## Purpose:
The purpose of this challenge is to help PyBer a Python based ride sharing app to analyze a large set of data. The analysis we produce will help the CEO making decisions on improving access to ride sharing services and determine affordability for underserved neighborhoods. 

To aim ourselves on this analysis, we will write python script using pandas library, Jupyter notebook, and matplotlib to create charts that showcase the relationship between the type of city and the numbers of drivers and riders by type of cities as well as the percentage of total fares, riders and drivers by type of cities. 

# Results:
### The urban cities have:
* 2.7X more rides than the suburban cities and 13X more rides than the rural cities

* 5X more drivers than the suburban cities and 30X more drivers than the rural cities

* 2X more fares than the suburban cities and 9X more fares than the rural cities

While urban cities have the highest number of total rides, drivers, and fares, when it comes to average fare per ride and average fare per driver it has the lowest. This makes sense since urban cities are more populated than rural and suburban, and more people use ride sharing services than in the rural and suburban cities. There are more drivers in the suburban cities making it more competitive and more favorable for lower prices. Where the demand of drivers is low like rural cities the fare per ride will increase and this is exactly what we see in the DataFrame below. 

![PyBer_summary_df.png](https://github.com/LucyPill/PyBer_Analysis/blob/main/Images/PyBer_summary_df.png)


We went further in our analysis and took a look at the fares among the cities per week between Jan 2019 and April 2019. We created a line chart that showcase the weekly total fares for each city type. The fares for each city during this perios of time seen to stay at a  constant range. For example, the urban cities fares between Jan-April was between $$1,600-$2,500, the surbuban cities range is $750-$1,500, and the rural cities range is $100-$500. As we can see here, these results are the same as the results in the table above. The rural cities has the lowest revenue when compared to urban and rurals. There is a peak that coincides on all three lines but it seems not to be significant perhaps that could be a weekend where an event or a holiday is taking place and people are out and about that weekend.

![PyBer_fare_summary.png](https://github.com/LucyPill/PyBer_Analysis/blob/main/Images/PyBer_fare_summary.png)

# Summary:
From this analysis we can conclude that rural cities are the most impacted when it comes to ride sharing services. Rural cities do not have as many drivers as urban and suburban cities have. This cause an increase in the fare per ride and creates less revenue for company and drivers in general.
There are a few ideas that PyBer could implement so it helps rural cities to make ride sharng more accessible to these communities.
1. PyBer should work on providing accesibility of ride sharing in rural areas.
2. PyBer should come up with a plan to make ride sharing more affordable in rural areas. As of now, rural areas are the most expensive per ride. If the fares/ride are more affordable is more likely for people to consider using the service.
3.  Incentivate drivers to drive in rural cities by offering them a better share of the fare/ride. This can motivates drivers to be more willing to work in rural areas making the it more affordable, and more accessible to the public in this areas.
