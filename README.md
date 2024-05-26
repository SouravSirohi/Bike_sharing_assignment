# Project Name
> Bike Sharing Assignment.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

-Which variables are significant in predicting the demand for shared bikes.
-How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Business Goal

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
1. Following variables are significant in predicting the demand for shared bike:
    - Temperature of the day
    - Number of years the company is in business
    - Season i.e. Spring, Summer, Fall, Winter
    - Working day or Holiday
    - Weather situation i.e. Clear sky, Cloudy or Rainy
    - Windspeed
2. Temperature of the day:
    - Temprature shows positive correlation with respect to bike usage
    - On a warmer day people are more likely to use the bike in comparision to a colder day
3. Year:
    - 2019 shows much higher demand than 2018
    - This helps us infer that company may have executed certain steps in 2019 that leads to higher demand
4. Windspeed:
    - On a windy day people are less likely to use the bike service
5. Weather Situation:
    - On a rainy day or cloudy day people are less likely to use the bike service
6. Working day:
    - Working days shows higher usage than during weekends or holidays
    - Which suggests that more people are using the bike service to commute to work than for leisure activity
7. Season:
    - During Spring the usage is likely to drop
8. Top 4 predictors are:
    1. Temperature
    2. Weather situation specially if it is raining
    3. Windspeed
    4. Number of years in business i.e. popularity or how many people knows about it


## Technologies Used
- library - pandas
- library - numpy
- library - sklearn
- library - statsmodels
- library - seaborn
- library - matplotlib.pyplol


## Contact
Created by [@githubusername] - feel free to contact me!
