# Bikeshare Analysis

*Note: This repository was created to fulfill assignments (Module 14 Exercises and Challenge) for the UC Berkeley Data Analytics and Visualization Bootcamp. The analysis, content, and format of this report were based on the grading rubric.*


## Overview
This report presents an analysis of CitiBike rider data from New York City for August 2019 using Tableau Public. 

**Data Source:**
https://s3.amazonaws.com/tripdata/index.html

201908-citibike-tripdata.csv.zip


### Purpose
A fictional client wishes to establish a bike sharing business in Des Moine. To pitch the business to potential investors, she has asked us to analyze historic data from CitiBike, a bike share which has operated successfully in New York City for the past several years. Data from August 2019 was chosen as ridership is likely to be highest in summer and 2019 was the last pre-pandemic year and thus more representative of typical ridership patterns. 

---
## Results

### Visualizations:
**[Tableau - NYC August 2019 Citibike Analysis](https://public.tableau.com/app/profile/cindy.lai7570/viz/Module14ChallengeUCBDataBootcamp/NYCAugust2019CitibikeAnalysis?publish=yes)**

Our analysis and visualizations can be found in the above Tableau Public published story ("NYC August 2019 Citibike Analysis"). Key results and detailed below.



### Total Rides and Customers
The first page of the Tableau story displays simple aggregates of the total number of rides and breakdown of customers. 

**Figure 1: Aggregate CitiBike User Data**
![Fig1.png](/Images/Fig1.png)
Most Citibike users were subscribers paying $15 per month. With over 1.9 million subscribers, this would have generated a revenue of over $28 million that month for Citibike. Single time use customers booked 443,865 rides in the month of August. At a base rate of $3.50 per ride, this would have generated at least an additional $1.5 million. 


### Bike Checkout Patterns
Pages 2 and 3 of the Tableau story show different visualizations of bike checkout times and durations. 


**Figure 2: Bike Checkout Durations (first 3 hours)**
![Fig2.png](/Images/Fig2.png)

Most rides were under 30 minutes (Figure2 and story page 2, top left graph). 


**Figure 3: Bike Checkout Durations by Gender**
![Fig3.png](/Images/Fig3.png)

Gender did not appear to affect bike checkout durations (Figure 3 and story page 2, bottom left graph). 


**Figure 4: Bike Checkout Times**

![Fig4.png](/Images/Fig4.png)

The most popular checkout times were between 8 am and 8 pm, with heavier usage during morning and late afternoon rush hours (Figure 4 and story page 2, right graph). 


**Figure 5: Bike Checkout Times by Weekday**
![Fig5.png](/Images/Fig5.png)

Bike checkout patterns different on weekends versus weekdays (story page 3). The most popular times during weekends was between 11 am and 5 pm (Figure 5 and story page 3, left heatmap).


**Figure 6: Bike Checkout Times by Gender**

![Fig6.png](/Images/Fig6.png)

Again, there were no strong differences in checkout times between men and women (Figure 6 and story page 3, top right heatmap). 


**Figure 7: Bike Checkout by Gender and Weekday**

![Fig7.png](/Images/Fig7.png)

Those who listed "unknown" or did not provide an answer for their gender checked out bikes more on the weekends and tended to be single use customers. Most subsribers appeared to check out bikes on weekdays (Figure 7 and story page 3 lower right heatmap). 


### Popular Biking Locations
Pages 4 through 6 of the Tableau story display maps of bike usage (checkout and return locations) with bubbles and colors reprensented the number of bikes logged at each location. 


**Figure 8: Bike Checkout and Return Locations**
![Fig8.png](/Images/Fig8.png)
Citibike usage was greatest in Manhattan (Figure 8 and story page 4). 


**Figure 9: Bike Checkout and Return Locations for Subscribers**
![Fig9.png](/Images/Fig9.png)
Most subscribers rode bikes through Manhattan, especially south of Central Park (Figure 9 and story page 5). 


**Figure 10: Bike Checkout and Return Locations for Single Use Customers**
![Fig10.png](/Images/Fig10.png)
Single use customers however, checked out and returned bikes at certain locations in Manhattan more frequently (Figure 10 and story page 6). This may reflect rides to and from popular tourist destinations, recreational areas, or other points of interest.  


---

## Summary

This preliminary analysis of Citibike data from New York City shows various aspects of its successful operation there. Over the month of August in 2019, Citibike logged over 2.3 million rides and generated close to $30 million in revenue. Most revenue came from regular subscribers. Ridership patterns differed between subscribers and one time use customers, likely reflecting purpose of use and residential status. Non-subcribers may be more likely to be tourists, who might be visiting tourist attractions on the weekends, while subscribers may be using Citibike for regular work and errands. 

An additional analysis that could be preformed with this dataset include a breakdown of trip durations by subscribers versus one time customers. The current visualizations for ridership during weekdays can be improved by also including a breakdown of subscribers versus non-subscribers (story page 3, left heatmap). For target advertising, analysis of ridership patterns by age can be performed (number of rides versus age, calculated by birth year). This analysis can be further sub-divided by subscriber status and filtered by trip length for more insights. Finally, other factors which could impact a bike share business should be compared and contrasted between New York and Des Moine. Such factors could include population, tourism numbers, traffic patterns, city drivability, weather, and other location or city dependent traits.




