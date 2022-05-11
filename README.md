![ffd700](https://user-images.githubusercontent.com/15967377/167264671-29ccef9c-4055-4c43-a859-94b468ccd0ec.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![87ceeb](https://user-images.githubusercontent.com/15967377/167264698-7d98a2e9-5144-4c59-90aa-12c46743045c.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![ff7f50](https://user-images.githubusercontent.com/15967377/167264692-42e9e685-aa13-4c4b-a1e6-0db215d34b00.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
***
# Overview

Our task was to identify differences in the total weekly fares for each of the three city types.
We were excited to have the opportunity to work for V. Isualize and hope you will be pleased with our presentation as Omar and I worked dilligently to bring this to you today. While we could have used the MATLAB approach for everything we needed, we chose to showcase our abilites by at times using the Object-Oriented approach as an homage to the time V. Isualize spent as a programmer at MathWorks.  


# Results

The 'ride_id' is a unique identifier for each ride which allows us to easily get an overview of data such as the total number of rides for each city 'type' by grouping each city 'type' and counting the 'ride_id'.  

        total_rides = pyber_data_df.groupby('type')['ride_id'].count()

| ![Summary Table](analysis/summary_table.png) |
|:--:|
| **Pyber Summary DataFrame** |

Based on the information we compiled, we were able to determine that while the Urban city type had more than 80% of the total drivers, it had less than 70% of the total rides. 

As one might expect, the Urban city type had about 50% more total fares than the Suburban city type, however, the average fare per driver for the Suburban city type was over 138% more than the average fare per driver for the Urban city type.

| ![Weekly Summary Table](analysis/weekly_summary.PNG) |
|:--:|
| **Pyber Weekly Summary by City Type Table** |

![PyBer Line Chart](analysis/Pyber_fare_summary.png)

# Summary
***

1. Based on the ratio of total Urban drivers compared to the total Urban rides, it is likely there is more competition within the Urban city type. Offering an incentive for Urban drivers to expand their range to cover the Suburban and Rural areas could decrease the amount of competition as well as increase the per driver average fare. 
2. With an increase in fares for only the Suburban city type at the end of April, it may be beneficial next year to have Rural and Urban drivers available to handle that increase.
3. Decreasing the average fare in the Rural city type may increase volume and likely do so with little effect to the average fare per driver.

***
![ffd700](https://user-images.githubusercontent.com/15967377/167264671-29ccef9c-4055-4c43-a859-94b468ccd0ec.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![87ceeb](https://user-images.githubusercontent.com/15967377/167264698-7d98a2e9-5144-4c59-90aa-12c46743045c.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![ff7f50](https://user-images.githubusercontent.com/15967377/167264692-42e9e685-aa13-4c4b-a1e6-0db215d34b00.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
