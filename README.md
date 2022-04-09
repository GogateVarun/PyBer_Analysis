## PyBer_Analysis

Overview 

The objective of this analysis was to use Pandas create a dataframe that summarized ride share data and categorized findings by city type.  In order to accurately obtain the total data needed, two data sets, city data and ride data were merged.  Once the data was merged we could find more information about the total number of rides given, drivers providing rides and how much the average fare was for each city type.
Using Pandas and Matplot lib libraries, the data was grouped by city type in order to find rides, drivers and the average fare per ride per city type. From there a new data frame was created with a pivot table in order to group the fares by week, using the resample function.  At that point a line chart could be used to plot the weekly fares by city type.

Results

It was clear that the Rural cities had a larger average fare per driver regardless that they had the least amount of fares, confirming that rural rides are generally longer in miles.  This can also be assumed since the rural average fare per ride is the highest of the three city types.  While the Urban city type had the largest number of total rides and smallest amount for average fare.  This could be since the urban areas are more compact, so the rides would travel a shorter distance, however they would occur at a higher rate. 
![image]

