<img width="250" src="https://raw.githubusercontent.com/lukwies/mid-bootcamp-project/main/data/img/bikes.png">


# Bikesharing in Seoul (South Corea)


## Sources
 * Data: https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand
 * Image: https://global.chinadaily.com.cn/a/201801/25/WS5a69cab3a3106e7dcc136a6d.html


## Info
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort.
It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern.
The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.



## Buisness Questions
    * Which impact has the season (Spring, Summer, Autumn, Winter) on bike renting?
    * Which impact has the daytime on bike renting?
    * Which impact has the weather (temperature, rain, snow, ...) on bike renting?
    * Are there more bike rentals on holidays?

## Hypothesis
     1. The daily rental amount differs from 400 bikes/hour.
     2. We have a higher rental amount while holidays.
     3. The average rental amount is less if weather is cold (< 10°C)
     4. The average rental amount is higher at day (8°°-19°°) than at night.

## Prediction
    * Can we predict the amount of bikes rented for a given day?

