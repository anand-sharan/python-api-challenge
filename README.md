# Python API Homework - What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

## Charts
## Scatter plots
1. City Latitude vs. Max Temperature:

![Weather](/Images/ScatterCityLatitudeMaxTemperature.png)

2. City Latitude vs. Humidity:

![Weather](/Images/ScatterCityLatitudeHumidity.png)

3. City Latitude vs. Cloudiness:

![Weather](/Images/ScatterCityLatitudeCloudiness.png)

4. City Latitude vs. Wind Speed:

![Weather](/Images/ScatterCityLatitudeWindSpeed.png)

## Scatter plots with regression

5. Northern Hemisphere - Temperature (F) vs. Latitude

![Weather](/Images/ScatterNHLatitudeMaxTempRegression.png)

6. Southern Hemisphere - Temperature (F) vs. Latitude

![Weather](/Images/ScatterSHLatitudeMaxTempRegression.png)

7. Northern Hemisphere - Humidity (%) vs. Latitude

![Weather](/Images/ScatternHLatitudeHumidityRegression.png)

8. Southern Hemisphere - Humidity (%) vs. Latitude

![Weather](/Images/ScatterSHLatitudeHumidityRegression.png)

9. Northern Hemisphere - Cloudiness (%) vs. Latitude

![Weather](/Images/ScatterNHLatitudeCloudinessRegression.png)

10. Southern Hemisphere - Cloudiness (%) vs. Latitude

![Weather](/Images/ScatterSHLatitudeCloudinessRegression.png)

11. Northern Hemisphere - Wind Speed (mph) vs. Latitude

![Weather](/Images/ScatterNHLatitudeWindSpeedRegression.png)

12. Southern Hemisphere - Wind Speed (mph) vs. Latitude

![Weather](/Images/ScatterSHLatitudeWindSpeedRegression.png)

## Analysis and Conclusion
1. When we move from north pole or equator and south pole to equator we see that the temparature are more near the equator.
2. From the plot Northern Hemisphere - Temperature (F) vs. Latitude, the r-value is: -0.85, which more than -0.5 and this show they are negatively correlated.
3. From the plot Southern Hemisphere - Temperature (F) vs. Latitude, the r-value is: 0.66 is more than 0.5 show that they are positively correlated.
4. There is not much relationship between latitude and wind speed.
5. There is not much relationship between latitude and cloudiness.