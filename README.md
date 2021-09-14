# Pyber Analysis

## Overview of Analysis
The purpose of this analysis was to look into the relationship between total weekly fares and city type.  The visualizations created will help to make more informed assessments on scalability based on city type, and will help to make data driven decisions on the future business strategy of Pyber.

## Results

<img src="/Users/robertyokabaskas/Desktop/Coursework/Pyber_Analysis/Resources/pyber_dataframe.png" alt="pyber_dataframe" style="zoom:150%;" />

###### Figure 1: Dataframe of Key Pyber Metrics based on City Type

In the DataFrame above, the data shows a clear relationship between population density and total rides.  The total rides of a city skyrocket the more urbanized that city is.  The urban environment allows Pyber to be a more efficient marketplace by grouping rides together, as well as just having increased driver supply and consumer demand.  The Suburban city environment shows some promise with total fares close to $20,000.  However, the Suburban and Rural city environments have much higher fares than Urban environments do.  This could be because the average length of ride is longer, or because the marketplace in these environments is less efficient most likely due to a driver supply bottleneck.  No clear conclusion can be made in regards to this as the data for total rides requested is not available.

<img src="/Users/robertyokabaskas/Desktop/Coursework/Pyber_Analysis/Resources/Pyber_fare_summary.png" alt="pyber_dataframe" style="zoom:100%;" />

###### Figure 2: Total Fare by City Type (Weekly)

The graph above shows growth in terms of total fares being fairly flat from January to the end of April.  By city type, Urban cities bring in the most revenue, followed distantly by Suburban cities, and with Rural cities bringing in very little revenue overall.


## Summary
The following bullet points represent three possible business strategies for increasing growth and removing disparities between ridership based on city type.

* Since it is not really possible to increase the fare price for rural and suburban environments without crushing ridership, a possible strategy could be slightly raising fare prices in urban cities where ridership is already strong.  This additional revenue could be used to subsidize fares in suburban and rural cities which would make the pricepoint more attractive to potential customers.

* In Figure 2, the graph shows minimal growth between January to the end of April.  This is not a time of the year that is synonymous with social events and comingling, especially in nonurban cities.  This is a riskier strategy but a major marketing push could be made in May or June at trying to increase ridership in suburban and rural cities.  This marketing strategy could involve partnering with concerts and different seasonal events to maximize exposure.  This is a riskier strategy because there is no data present on whether or not ridership spikes in the summer months, but since growth has been flat over the winter it would be likely there would be a major uptick in user growth.  The only serious downside to this strategy is there could be a massive global pandemic!

* The last possible strategy is to create an adjusted pricing model based on the per capita population density of each city type.  Since suburban and rural cities are naturally less dense, it is unfare to see the total fares by city type as a pricing discrepancy when suburban and rural fares are compared to urban fares.  The urban marketplace is just so much more robust and profitable.  This pricing strategy would mainly target urban and suburban cities as the primary revenue generating city types.  Less emphasis on the rural market would better focus resources towards the suburban and urban environments which are the key growth areas for Pyber.  People in rural environments are much more likely to own a car, and be daily drivers themselves.  Just from a qualitative standpoint, product adoption of Pyber in rural city environments will be slow regardless of strategy.
