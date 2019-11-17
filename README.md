# python-api-challenge

## Analysis Results

![alt text](https://github.com/remclellan/python-api-challenge/blob/master/WeatherPy/output_data/City%20Latitude%20vs.%20Max%20Temperature.png)     ![alt text](https://github.com/remclellan/python-api-challenge/blob/master/WeatherPy/output_data/City%20Latitude%20vs.%20Humidity%20Plot.png)

![alt text](https://github.com/remclellan/python-api-challenge/blob/master/WeatherPy/output_data/City%20Latitude%20vs.%20Cloudiness.png)     ![alt text](https://github.com/remclellan/python-api-challenge/blob/master/WeatherPy/output_data/City%20Latitude%20vs.%20Wind%20Speed.png)

Click the link below to access data file of random city and weather data collected from OpenWeatherMap:
https://github.com/remclellan/python-api-challenge/blob/master/WeatherPy/output_data/Cities.csv


## Observations

While the ask was to prove if the weather gets hotter as one approaches the equator which the data set shows, especially in the first chart above, there are other observable items both in the data acquisition and analysis of note.  Here are my observations from this assignment:

* While the data collected was random, there were instances of cities in the original latitude/longitude sets that were not able to be located using the API pull from OpenWeatherMap.  Of those that were found, it was notable that more were located North than South of the equator.  This skewing of the data set itself may not give as complete a picture in the comparison of warmer temperatures overall as it may also be that those locations South could have been warmer than the Northern locations observed, which can be seen albeit slightly in the Max Temperature chart in the immediate Southern portion from the equator (-20).  Additionally, the drop off as the locations shifted further North in temperature was significant though not unexpected given the the current winter season due to time of year.
* Wind speed was in general lower though there were outliers more to the North (40 - 60), which could be attributable to items such as storm activity in that area though it was hard to correlate specifically as the cloudiness level showed it was not impacted necessarily by the location to the equator while the humidity chart did show a higher level in the same area.
* Overall Humidity was higher throughout immediate area around the equator as expected with a tropical region though it was not necessarily the most humid region during the time of the analysis.