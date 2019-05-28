# WeatherPy-Latitude-Analysis
Creation of an automated script that randomly selects 500+ cities around the world and pulls weather data from OpenWeatherMap API outputting scatter plot comparisons of different weather metrics.

As a general trend the hottest temperatures occurred near the equator. Interestingly, the hottest temperatures grouped around latitudes (+20 degrees) slightly north of the equator.    

![City_Lat_v_Max_Temp](https://user-images.githubusercontent.com/48166327/58502982-8ae82000-813c-11e9-81e8-1837a92f1175.png)

The highest humidity on average was at the equator. The scatter plot data showed a reduction in the variance of percent humidity  centered at the equator within a range of +20 and -20 degrees latitude. 

![City_Lat_v_Humidity](https://user-images.githubusercontent.com/48166327/58503005-93d8f180-813c-11e9-969b-bd48fe26d825.png)

There was not a strong connection between city latitude and wind speed. The scatter plot data showed a modest reduction in the variance of wind speed centered at the equator. Some of the windiest cities occurred in latitudes farthest from the equator.  

![City_Lat_v_Wind_Speed](https://user-images.githubusercontent.com/48166327/58503016-976c7880-813c-11e9-83cd-f15fa02fb7bf.png)

There was no correlation between city latitude and the cloudiness of a city. Interestingly, the likelihood of an equatorial city cloudiness (%) near zero was very low.  

![City_Lat_v_Cloudiness](https://user-images.githubusercontent.com/48166327/58503023-9a676900-813c-11e9-91d8-2e13c2683b68.png)

In summary, these data suggest that on average the closer a city is to the equator the higher the temperature and more humid the city is likely to be. Additionally, there might be a weak association between low wind speeds or low cloud cover on average in equatorial cities.


