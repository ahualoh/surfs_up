# surfs_up "Waves and Ice Cream" 
 Module 9: Advanced Data Storage and Retrieval (using SQLAlchemy, SQLite, and Flask)
 
## Overview of the analysis: Explain the purpose of this analysis.
We are interested in opening up an ice cream shop on the Hawaiian Island of Oahu... This analsysi specifically addresses the "investor", W. Avy's, request to compare the temperatures of June and December to get a general idea for weather patterns throughout the year. 


## Results: 
See <image1> and <image2> respectively for the summary statistics from both months. Of note, for June and December respectively...
 
- Avereage Temperatures: 74 degrees | 71 degrees
- Standard Deviation: 3.26 | 3.75
- Min & Max: 64 & 85 degrees | 56 & 83 degrees

## Summary: 
 
The results above show that on average, the temperatures stay fairly consistent throughout the year... that is, assuming that December is indeed the coldest month. (June also does not necessarily mean the hottest month either - it seems we are assuming June is a benchmark of adequate ice-cream-eating-temperature). With the standard deviations being so similar also implies that the fluctuations in temperature are also not wildly different in each month. 

While we can see that the minimum temperature in December can be almost 10 degrees colder than June's lowest temperature, if we glance at Decembers 25% percentile, it can be assumed that December's lowest temperature is actually rare anyways. 
 
Aside from just temperature, we may need to consider other weather factors that may influence customer's availability for going out for ice cream... such as the days of rain/cloudiness (and how much rain and clouds there are on those days) and wind speed (as this can affect the type of outdoor activities... are people surfing? Swimming? Just lounging on the beach?). 
 
Temperature alone will not be enough to determine viability of an ice cream shop, but this is a start. We will need to consider competition - especially how many are there within a certain distance. Is there already enough supply for demand? Is there an optimal area of the island to set up a shop? Many more questions should be considered before moving forward!
