# Tracking Temperatures
Time series analysis to model and predict temperature across five cities in the United States.

## I. Data Overview:
The data is obtained from [Berkley Earth](http://berkeleyearth.org/data/) and contains the average monthly temperature for various cities around the world.

All Temperature values are in Celsius.

## II. Analysis Overview:
The analysis is being performed for 5 cities across different regions of the United States namely:

1. Chicago
2. New York
3. Minneapolis
4. Houston
5. Los Angeles

These cities are chosen because they represent different climates, geography in the same country.

The data is split by time - the training data ranges from January 1800 to December 2011 while the test set contains temperature values as of and after January 2012.

## III Conclusion:
The analysis performed looks at identifying trends in the temperature data across the years and making predictions for temperature for 5 different cities in the United States. Through the analysis, it can be concluded that:

![climatep]/(climate_predictions.png)
- No discernable trend was observed in the temperature values for each of the cities during the exploratory phase.
- ARIMA model used for prediction of the temperature values, makes the best predictions for Los Angeles and Houston.

It is to be noted that weather prediction depends highly on local climate and is subject to frequent change depending on the local conditions. Thus, the root mean squared error values achieved by us represent good estimation of the temperature which when combined with certain other weather parameters can yield even better results but is beyond the scope of our current analysis.
