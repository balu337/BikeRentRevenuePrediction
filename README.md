# Shared Bike Demand Prediction Project
Project involves building model to predict demand of shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
**Business Context** : A US bike-sharing provider BoomBikes wants to build a strategy to increase their revenue by predicting the demand for shared bikes. They had approached a consulting company to build a model to predict demand for shared bikes. BoomBikes team would also like to understand the factors impacting the demand of shared bikes.

**Problem Statement** : Build model to predict demand for shared bikes based on independent factors.

**Data** set is built based on various meteorological surveys and people's styles impacting daily bike demands across the American market. Data set includes Date,Year,Weekday,holiday, weather situation,temperature,humidity,wind speed, type of registered users and count( demand)

**Approach** 

- Step 1: Project Stetup & Data Import
- Step 2: Understanding and Visualizing data
- Step 3: Preparing Data for modelling
- Step 4: Build and Train the Model
- Step 5: Model Evaluation
- Step 6: Conclusion

## Conclusions

  - 3 significantly contributing factors are from ‘temperature’,’Weather situation-Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds’( negatively) and ‘Year’. 
  - Year and temperature are impacting positively. 
  - The Weather situation of Light (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds ) and wind speed are impacting negatively.

- Model to predict bike demand is represented as "Bike Demand(Y)  = 0.0875+ 0.2334*yr -0.0867*holiday + 0.5682 *temp -0.1455 * windspeed -0.2535 *light + 0.0812 *summer + 0.1261*winter + 0.0895 *Sep"
- Seasonal Factors : Fall has maximum demand and spring has lowest demand
- Other Observations
    - 2019 has more usage when compared to 2018
    - On clear days (Few clouds, Partly cloudy, Partly cloudy) usage is high
    - Its observed that on Non Holidays usage is higher than on holidays.




## Technologies Used
- Python - version 3.9.7
- pandas - version 1.3.4
- seaborn - version 0.11.2
- matplotlib  - version 3.4.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@balu337] - feel free to contact me!
