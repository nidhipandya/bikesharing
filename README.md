### NYC Bike Analysis

[Tableau Dashboard](https://public.tableau.com/app/profile/nidhi2196/viz/NYCBikeStory/Story1)

## Overview
There is already a successful model for bike sharing business in NYC, which is used for the study to start a bike sharing business in another city. We used citibank bike sharing data for August 2019 to prepare a business proposal for an investor to invest in Des Moines.

## Results
NYC_citibike_tripdata.csv data is used for the analysis

#### Customer Data study
![image1](https://github.com/nidhipandya/bikesharing/blob/main/img/image1.PNG)

As shown in the image above, we have the total number of customers. We got data for Gender breakdown and Usertype, long-term subscribers and short-term users.

#### Peak hours in August
![image2](https://github.com/nidhipandya/bikesharing/blob/main/img/image2.PNG)

The data above is for peak hours for bike trips during the month of August. This data will help us get a better idea of how many bikes we might need and which parts of the day we'll need the most bikes. If bike maintenance needs to be performed, it should be done when there is low usage. According to the graph above these maintenance times should be between 3a.m and 4 a.m and maintenance should be avoided between the hours of 4 p.m and 7 p.m which is the peak usage hours.

#### Checkout Times for Users (by Gender)
![image3](https://github.com/nidhipandya/bikesharing/blob/main/img/image3.PNG)

The graph above shows average checkout times by all gender catagories. When we look at the Gender graph, it looks to be that most of the usage is from male users. Using these two graphes, we can also conclude that males are more frequent users than Females.

#### Trip by Weekdays for Each hour
![image4](https://github.com/nidhipandya/bikesharing/blob/main/img/image4.PNG)

here we can see in detail about the trip duration for Each hour. By looking the graph the conclusion is the highest usage occurs during office rush hours in the morning and evening from Monday to Friday.  Most of the use is during the daytime hours.

#### Trip by Gender(Weekday/hr)
![image5](https://github.com/nidhipandya/bikesharing/blob/main/img/image5.PNG)
This is just split by gender from the previous graph. here finally we can conclude that male users are more frequent than Female users. Female users also show the same pattern using the bikes from Mon-Fri and weekends.

#### Trips by Gender by Weekday(UserType)
![image6](https://github.com/nidhipandya/bikesharing/blob/main/img/image6.PNG)

The graph above gives user data on weekdays and also shows the Gender breakdown and Usertype. By looking the graph we can see long term users, subscribers are more frequent than regular customers. From subscribers Male users are more frequent than Female users.

## Summary
After looking all the graphes, there are a few points we can conclude:

- Users are mostly Male users
- Most users are subscribers than customers
- Peak hours are 6am - 9am and 4pm-8pm on weekdays and 9am-6pm on weekends
- weekdays from 2am - 4am have the least amount of customers so this would be a good time for maintenance
- There are more users on weekdays than on weekends.
 
So we can say customers are mostly male and they use the bikes for commuting in NYC.

### Additional visualizations

- using this data we can also analyze in detail the Top start/stop locations in a Map graph
- We can also collect feedback from customers and use that data to get a more in depth analysis to help with deployment of bike sharing services for other locations and improve the investment being put into other cities.
