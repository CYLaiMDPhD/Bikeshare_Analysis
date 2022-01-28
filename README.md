# Bikesharing

*Note: This repository was generated to fulfill assignments (Module 14 Exercises and Challenge) for the UC Berkeley Data Analytics and Visualization Bootcamp. Submitted on 1-28-22 for grading.*


## Overview
This report presents an analysis of CitiBike rider data from New York City for August 2019 using Tableau Public. 

### Purpose
To aid our client in her pitch to investors about starting a Bike share business in Des Moines, we've analyzed historic data from CitiBike, which has operated successfully in New York City for the past several years. Data from August 2019 was chosen as ridership is likely to be highst in summer and 2019 was the last pre-pandemic year and thus more representative of typical ridership patterns. 

---
## Results

**Data Source**



**Link to Tableau Story**
[Link](https://public.tableau.com/app/profile/cindy.lai7570/viz/Module14ChallengeUCBDataBootcamp/NYCAugust2019CitibikeAnalysis?publish=yes)

Our analysis and visualizations can be found in the above Tableau Public published story ("NYC August 2019 Citibike Analysis").



### Total Rides and Customers
The first page of the Tableau story displays simple aggregates of the total number of rides and breakdown of customers. Most Citibike users were subscribers paying $15 per month. With over 1.9 million subscribers, this would have generated a revenue of over $28 million that month for Citibike. Single time use customers booked 443,865 rides in the month of August. At a base rate of $3.50 per ride, this would have generated at least an additional $1.5 million. 


### Bike Checkout Patterns
Pages 2 and 3 of the Tableau story show different visualizations of bike checkout times and durations. Most rides were under 30 minutes (page 2, top left graph). Gender did not appear to affect bike checkout durations (page 2, bottom left graph). The most popular checkout times were between 8 am and 8 pm, with heavier usage during morning and late afternoon rush hours (page 2, right graph). Bike checkout patterns different on weekends versus weekdays (page 3). The most popular times during weekends was between 11 am and 5 pm (page 3, left heatmap). Again, there were no strong differences in checkout times between men and women (page 3, top right heatmap). Those who listed "unknown" or did not provide an answer for their gender checked out bikes more on the weekends and tended to be single use customers. Most subsribers appeared to check out bikes on weekdays (page 3 lower right heatmap). 


### Popular Biking Locations
Pages 4 through 6 of the Tableau story display maps of bike usage (checkout and return locations) with bubbles and colors reprensented the number of bikes logged at each location. Citibike usage was greatest in Manhattan (page 4). Most subscribers rode bikes through Manhattan, especially south of Central Park (page 5). Single use customers however, checked out and returned bikes at certain locations in Manhattan more frequently (page 6). This may reflect rides to and from popular tourist destinations, recreational areas, or other points of interest.  


---

## Summary

This preliminary analysis of Citibike data from New York City shows various aspects of its successful operation there. Over the month of August in 2019, Citibike logged over 2.3 million rides and generated close to $30 million in revenue. Most revenue came from regular subscribers. Ridership patterns differed between subscribers and one time use customers, likely reflecting purpose of use and residential status. Non-subcribers may be more likely to be tourists, who might be visiting tourist attractions on the weekends, while subscribers may be using Citibike for regular work and errands. 

Additional analysis that could be preformed with this dataset include a breakdown of trip durations by subscribers versus one time customers. The current vizualizations for ridership during weekdays can be improved by also including a breakdown of subscribers versus non-subscribers (story page 3, left heatmap). For target advertising, analysis of ridership patterns by age can be performed (number of rides versus age, calculated by birthyear). This analysis can be further sub-divided by subscriber status and filtered by trip length for more insights. Finally, correlations and analysis should also be made to compare an contrast Des Moines and New York in terms of population, tourism, traffic patterns, city drivability, weather, and other factors which will influence a bike share business.




