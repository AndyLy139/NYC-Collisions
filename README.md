![alt text](https://cdn.dribbble.com/users/1144020/screenshots/2775331/dude_s-car-accident.gif)
---
# NYC Traffic Collisions Analyst
---
# Problem Statement

My goal is to delve into the extensive dataset of NYC traffic collisions and extract valuable insights. By analyzing factors such as borough, crash time, vehicle type and contributing factors. Through this analysis, I hope to provide meaningful recommendations to enhance traffic safety measures, imporove transportation infrastructure and improve overall road safety.
---
## Data Dictionary
---
| Column                        | Type    |
|:------------------------------|:--------|
| CRASH DATE                    | object  |
| CRASH TIME                    | object  |
| BOROUGH                       | object  |
| ZIP CODE                      | object  |
| LATITUDE                      | float64 |
| LONGITUDE                     | float64 |
| LOCATION                      | object  |
| ON STREET NAME                | object  |
| CROSS STREET NAME             | object  |
| OFF STREET NAME               | object  |
| NUMBER OF PERSONS INJURED     | float64 |
| NUMBER OF PERSONS KILLED      | float64 |
| NUMBER OF PEDESTRIANS INJURED | int64   |
| NUMBER OF PEDESTRIANS KILLED  | int64   |
| NUMBER OF CYCLIST INJURED     | int64   |
| NUMBER OF CYCLIST KILLED      | int64   |
| NUMBER OF MOTORIST INJURED    | int64   |
| NUMBER OF MOTORIST KILLED     | int64   |
| CONTRIBUTING FACTOR VEHICLE 1 | object  |
| CONTRIBUTING FACTOR VEHICLE 2 | object  |
| CONTRIBUTING FACTOR VEHICLE 3 | object  |
| CONTRIBUTING FACTOR VEHICLE 4 | object  |
| CONTRIBUTING FACTOR VEHICLE 5 | object  |
| COLLISION_ID                  | int64   |
| VEHICLE TYPE CODE 1           | object  |
| VEHICLE TYPE CODE 2           | object  |
| VEHICLE TYPE CODE 3           | object  |
| VEHICLE TYPE CODE 4           | object  |
| VEHICLE TYPE CODE 5           | object  |

# Analysis
| BOROUGH       |   PEDESTRIAN_AFFECTED |   CYCLIST_AFFECTED |   MOTORIST_AFFECTED |
|:--------------|----------------------:|-------------------:|--------------------:|
| BROOKLYN      |                 23347 |              12767 |               77505 |
| QUEENS        |                 16422 |               6457 |               67167 |
| MANHATTAN     |                 16283 |               9115 |               24107 |
| BRONX         |                 10676 |               3340 |               35784 |
| STATEN ISLAND |                  1870 |                382 |               11548 |
---
Top 5 hours with the most collisions in New York City
|   Hour |   Total Collisions |
|-------:|-------------------:|
|     16 |             144106 |
|     17 |             140850 |
|     14 |             133442 |
|     15 |             124731 |
|     18 |             123845 |
---
Top 5 vehicles with the most collisions in New York City
| Vehicle Type                        |   Total Collisions |
|:------------------------------------|-------------------:|
| PASSENGER VEHICLE                   |             306097 |
| Sedan                               |             213490 |
| Station Wagon/Sport Utility Vehicle |             159679 |
| SPORT UTILITY / STATION WAGON       |             132435 |
| TAXI                                |              28044 |
---
Top 5 Contributing Factor
| Factor                         |   Total Collisions |
|:-------------------------------|-------------------:|
| Unspecified                    |             423164 |
| Driver Inattention/Distraction |             184686 |
| Failure to Yield Right-of-Way  |              73377 |
| Other Vehicular                |              33987 |
| Backing Unsafely               |              32668 |
