# Bike Sharing in our City

In this analysis, I explore the usage patterns of a bike sharing service in New York City in order to predict usage in the metropolitan area of Des Moines, Iowa. By revealing patterns in usertypes, usage times, and peak locations, we can implement a plan for our own bike sharing company and share the potential as we seek investors. You can find the dashboard of this analysis [HERE](https://public.tableau.com/views/Challenge1_16793296422620/BikeSharinginOurCity?:language=en-US&:display_count=n&:origin=viz_share_link).


## Results

The daily usage of New York City's bike sharing service provides valuable insights into predicting how we can make a service in Des Moines successful. With bike stations spread throughout the urban center of NYC and into outlying neighborhoods, we can plot usage across the region.

![locations](https://github.com/ChallahBack83/bikesharing/blob/main/images/locations.png)

When we focus in on the busiest locations, what we see is a heavy focus in the main city center.

![Story_1](https://github.com/ChallahBack83/bikesharing/blob/main/images/Story_1.png)

Downtown Manhattan is an area of business and tourism, therefore it sees the most foot traffic. With congested roads and crowded streets, bikes are a convenient, fast, and affordable mode of transportation. In Des Moines, bicycle stations should be concentrated around similar business and tourist districts to promote usage.

This hypothesis is further supported by looking at usage of these bicycles by hour.  Look at the peak hours for usage in August.

![August_peak](https://github.com/ChallahBack83/bikesharing/blob/main/images/Aug_Peak.png)

In August, there were 224,566 bike rentals between 5 & 6 pm, the highest hour for usage and the most common time for commuters.  The hours of 6 pm and 8 am, also commuting hours, are not much further behind. But how does this breakdown by weekday?

![Weekday_hour](https://github.com/ChallahBack83/bikesharing/blob/main/images/Weekday_Hour.png)

This heatmap highlights the day and time with the highest ride usage. The darker cells are times with the highest concentration of rides. Here we once again see the busiest times are at 5 pm, 6 pm, and 8 am.  However, these times are specific to the weekdays with Thursday at 6 pm at the top with 44,905 rides. Looking at the heatmap, we can also see a more even spread of usage throughout the days on Saturday, Sunday, and even Friday. Once again, this supports the theory of tourist or recreational use during these time frames. We can further understand this by breaking down the usertype.

![Weekday_Gender](https://github.com/ChallahBack83/bikesharing/blob/main/images/Weekday_Gender.png)  

![Week_Hr_Gender](https://github.com/ChallahBack83/bikesharing/blob/main/images/Week_Hr_gender.png)

These two heatmaps visualize weekday usage by both gender and usertype.  Here we can see that male subscribers dominate the usage of the bike sharing service, especially on Monday through Friday. We can once again theorize that these are our primary commuters utilizing the bikes on a regular basis.  When we focus in on the Customer usertype, meaning they do not use these bikes regularly, we also see the concentration of weekend usage.

![customer_weekday](https://github.com/ChallahBack83/bikesharing/blob/main/images/customer_weekday.png)

When not in use by primary customers, the commuters, we can suppose through this heatmap that the bikes are still used recreationally for transportation to social activities such as dinner or theater, especially in a city with such an active night life like New York City. To support these users in Des Moines, bicycles will need to be adequately stocked for Friday through Sunday in these night life or entertainment areas.

Lastly, we need to also understand the wear and tear on these bikes by how long they are used and how often. This will help us stock an adequate amount of bikes to allow for checkout times and plan for how often we may need to do repairs.

![Story_4](https://github.com/ChallahBack83/bikesharing/blob/main/images/Story_4.png)

The above graphs from our dashboard show that the duration of trips by users are mostly less than an hour long. In fact, our peak trip duration is only 5 minutes long with a count of 146,752 rides. Users are primarly interested in going from point A to point B and not casually using the bike throughout the day. With the bike sharing service, they have the option to checkout a new ride when they need it again. Shorter trips means quicker turn around for available bikes, but as we can see from the focused graph, we still need to plan for some longer rentals.


## Summary & Suggestions

In summary, a bike sharing service in Des Moines has a good chance of being successful.  Based on our analysis, we can expect consistency of commuters as the primary users with tourists or visitors supplementing regular usage on weekends.  To make our business a success, we should be certain to select convenient locations for commuters as well as the entertainment districts. We can plan on most maintenance being done overnight or on Sundays.

For further analysis, I suggest comparing gender and commuter demographics for Des Moines to those of New York City. We may have more suburban commuters than they do, and since we know most bike rides are 5 minutes in length, this will help us accurately account for the number of bikes and locations.  Gender in Des Moines is nearly evenly split (females at 50.1% of the population in 2022 census).  How is this percentage in comparison to New York, where we know the  majority of users were men.

To better understand usage by usertype, I would like to do a visualization on users versus location.  This will help plan accurately for varying locations and how well they should be stocked. I also suggest looking at age versus usage by day of the week and time and comparing to age demographics in and around Des Moines.

