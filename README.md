# PyBer_Analysis 

## Purpose and Overview
Using our knowledge of Python and Pandas, we are tasked to create a summary DataFrame of the ride-sharing data by city type. This information will then be used to create a multi-line graph that shows the weekly fares by city type. The graph will be created using Matplotlib and Pandas. The analysis is split up into two sections. The first one, Deliverable 1, we created a ride-sharing summary DataFrame by city type. The second, Deliverable 2, a multiple-line chart of total fares for each city type. Finally, the results will be assessed. 

## Results
### Deliverable 1

The results of Deliverable 1, where we created a a ride-sharing summary DateFrame by city type can be seen the the Jupyter notebook, titled Pyber Challenge. First we imported provided data into a single , combined data set and a dataFrame was created. After that, a succession of steps were created including the total rides for each city type (Urban, Suburban, Rural), where Urban has the most amount of rides. The next step, we found the total drivers for each city type with Urban having 2405, Suburban 490, and Rural 78. We then found the total amount of fares with Urban again coming in at top with $39,854. The next interesting thing was finding the average fare per ride for each city type. The result was Rural at the most with $34 and Urban the least with $24. Finally we found the average fare per driver for each city type. The result was Rural at the highest with $55.48 and urban the lowest at $16.57 (Suburban was $39.50). After all the data was cleaned up, this information is found in the DataFrame called: pyper_summary_df

### Deliverable 2

The results of Deliverable 2 can be viewed in the challengeFig that is included in the file. We used the information we originally obtained from the merged csv file and created a new DataFrame. This time we used the function groupby and reset the index for displaying the time stamp. The time frame used for the graph was from January 2019 to the end of April 2019. We filtered the data even more and grouped the weeks together to get to total fares for that week for each city type. The graph was created using the object-oriented interface method. As seen in the graph, Urban fares results in the most money and rural fares the least. Suburban fare fell in the middle of the two other types.


## Summary
Both deliverables yielded interesting results. For deliverable one, where we made a summary table, we can see that there are a lot more rides, drivers, and total fares in the urban areas. But the amount per ride and average fare per driver were much higher in rural areas. The could attribute to destinations and pickups being further away. The first recommendation I would make is to collect the data on how long the average ride in time or miles, is per customer. Do longer rides always mean more money or more time spent on each customer? 

When we look at the information taken from the graph, we see the similar patterns for each city type. Meaning, during late February, we see a spike in fares. Is this from more drivers or more money spent. My second recommendations would to see a larger data set collected for the entire year and see if we see a trend toward the holiday season. 

The third recommendation I would make in reference to the data disparities, would be to charge less the longer the ride. This could increase the use of ride sharing more in the rural areas or at least more drivers available. 
