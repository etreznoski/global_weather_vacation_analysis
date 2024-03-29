# global_weather_vacation_analysis
Using the Open Weather API the following project analyzed weather measurements from 571 randomly generated
cities accross the globe. Maximum temperature, humidity, cloudiness and wind speed measurements were used.

The data showed that cities closer to the equator have a higher maximum temperature.
The further from the equater a city is then the lower maximum temperature that city is likely to have. 
The scatter plot depicting city latitude and maximum temperature shows that cities from -40 latitude to about 15 latitude have higher maximum temperature than cities further away.

![lat_temp](https://user-images.githubusercontent.com/73403293/125845161-85708348-2abe-4fd8-8631-342caf3e5909.png)

When cities were divided into southern and northern hemisperes for linear regression, the northern hemisphere showed a clear correlation between proximity to the equator and maximum temperature. The southern hemisphere data also showed that cities closer the the equator tend to have higher maximum temperatures but the trend was much less defined.

![north_temp](https://user-images.githubusercontent.com/73403293/125845065-9bd78f7f-b6b0-4231-88bf-b4a9029a29a3.png)
![south_temp](https://user-images.githubusercontent.com/73403293/125845102-c047902d-16ed-4f92-9182-2e4a27a6c9d4.png)


The other measurement taken (wind speed, humidity, and cloudiness) showed only weak correlations if any.

It should be noted that this data is froma sample of only 571 cities worldwide. For more accurate trends,
many random samples should be generated and tested.

Based on the weather data collected I selected 8 cities with maximum temperatures between 80-90F and
cloudiness between 15-25. I then used the Google Places API to find hotels in those cities and plotted them on a humidity heat map.
