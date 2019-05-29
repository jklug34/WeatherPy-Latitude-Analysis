# WeatherPy-Latitude-Analysis
Creation of an automated script that randomly selects 500+ cities around the world and pulls weather data from OpenWeatherMap API outputting scatter plot comparisons of different weather metrics


As a general trend the hottest temperatures occurred near the equator. Interestingly, the hottest temperatures grouped around latitudes (+20 degrees) slightly north of the equator.

![City_Lat_v_Max_Temp](https://user-images.githubusercontent.com/48166327/58584553-5ee7a000-820b-11e9-99ad-c2d044cc009d.png)

The highest humidity on average was at the equator. The scatter plot data showed a reduction in the variance of percent humidity centered at the equator.

![City_Lat_v_Humidity](https://user-images.githubusercontent.com/48166327/58584566-6313bd80-820b-11e9-8503-0873386c333b.png)

There was not a strong connection between city latitude and wind speed.

![City_Lat_v_Wind_Speed](https://user-images.githubusercontent.com/48166327/58584575-660eae00-820b-11e9-9ade-05483c743a2c.png)

There was no correlation between city latitude and the cloudiness of a city. Interestingly, the likelihood of an equatorial city cloudiness (%) near zero was very low.

![City_Lat_v_Cloudiness](https://user-images.githubusercontent.com/48166327/58584578-67d87180-820b-11e9-82ab-b618ec944e71.png)

In summary, these data suggest that on average the closer a city is to the equator the higher the temperature and more humid the city is likely to be. Additionally, there may be a weak association between low cloud cover and proximity to the equator.

