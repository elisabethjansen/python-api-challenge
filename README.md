# python-api-challenge

# Weather API

## Task
For this analysis a list of cities was generated randomly by coordinates from the citypy library. With the collected cities, the following variables were gathered through API calls: 

Latitude, Longitude, Max Temperature, Humidity, Cloudiness, Wind Speed, Country, and Date. 

Scatter plots were generated for the relationships of: Latitude vs max temp, latitude vs humidity, latitude vs cloudiness, and latitude vs wind speed. 

Linear regressions were computed for each of the above relationships in both the northern and southern hemisphere. 

## Analysis
The only sigificant finding was the strong negative and postive correlation in the northern and southern hemispheres, respectively, bewteen temperature and latitude. 

In the northern hemisphere this indicates that as a city moves further away from the equator (latitude increasing), the max temperature decreases. In the southern hemisphere, as latitude increases (getting closer to the equator) the max temperature also increases. 

All other analyses can insignificant findings. 

# Vacation API

## Task 
For this analysis, the city data generated and exported in the previous analysis was used to map out all cities and further narrow down the list by ideal conditions. Given the ideal conditions list, the closest hotel within a 10000m radius was collected and mapped. 



## References
This assignment was completed individually and guided by class materials, examples, and the Xpert learning assistant, to correct for syntax and debugging. Class materials also served as a guide for correctly calling and using the Weather API and the geoapify interfaces. 