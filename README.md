## PyBer_Analysis

Overview 

The objective of this analysis was to use Pandas create a dataframe that summarized ride share data and categorized findings by city type, which included Rural, Suburban and Urban.  In order to accurately obtain the total data needed, two data sets, city data and ride data were merged.  Once the data was merged we could find more information about the total number of rides given, drivers providing rides and how much the average fare was for each city type.
Using Pandas and Matplot lib libraries, the data was grouped by city type in order to find rides, drivers and the average fare per ride per city type. From there a new data frame was created with a pivot table in order to group the fares by week, using the resample function.  At that point a line chart could be used to plot the weekly fares by city type.

Results

It was clear that the Rural cities had a larger average fare per driver regardless that they had the least amount of fares, confirming that rural rides are generally longer in miles.  This can also be assumed since the rural average fare per ride is the highest of the three city types.  While the Urban city type had the largest number of total rides and smallest amount for average fare.  This could be since the urban areas are more compact, so the rides would travel a shorter distance, however they would occur at a higher rate. 

Summary

The analysis uotimately showed that fewer riders are occuring to the more rural city areas and this could be because of less job opportunities out side of the city.  However, since the rides are so long it could also mean that there are not enough people willing to pay out a higher fare due to the greater distances travelled.  One thing I would recommend would be to provide deals for longer distance travelers to encourage more rural rides.  A somewhat opposite angle could be taken on the urban and suburban city types as well.  Since the total rides are higher, there must be more of a demand there.  Inner city rides could charge a higher rate due to the constant turn over rate of rides.  With incentives for frequent riders to gain points or deals after a certain amount of rides have been accumulated.  
