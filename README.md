# Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This repository contains the Linear Regression model for the Bike sharing service provider named BoomBikes.
- <b>Background</b>: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
    
    A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

    In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


- <b>Business Problem</b>: Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
    
- Dataset Provided: The dataset provided for this problem contains 730 records and 29 columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### R-squared is 83.5% on train set and 80.3% on test set
### Adjusted R-squared is 83.2% on train set and 79.1% on test set

### The good predictors for the target variable were these 12 predictor variables:

- temp: tells about the temperature of the day
- workingday: tells if the day was a working day or not
- windspeed: tells about speed of the wind of the day
- season_spring: represents the spring season
- year
- weekday_Saturday: represents saturday
- month_July: represents July month
- weathersit_Mist + Cloudy: represents the weather situation
- month_September : represents the September month
- season_winter: represents the winter season
- season_summer: represents the October month
- weathersit_Light Snow: represents the snow


#### the equation of the regression line:
##### let Xi denote the variables with i is the variable number in the above list of predictors, so the equation will be:
$ Count = 0.162 + 0.235 \times year + 0.055 \times workingday + 0.478 \times temp -0.153 \times windspeed -0.075 \times season_spring + 0.041 \times season_summer + 0.078 \times season_winter -0.036 \times month_July + 0.062 \times month_September + 0.068 \times weekday_Saturday -0.275 \times weathersit_Light Snow  -0.082 \times weathersit_Mist + Cloudy $

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- IDE - Anaconda Jupyter Notebook and VS Code
- language - python v3.9
- library - pandas v1.4.4
- library - numpy v1.21.5
- library - matplotlib v3.5.2
- library - seaborn v0.11.2
- library - sklearn
- library - statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was a business problem provided by Upgrad
- References taken for this case study are:
    1. https://stackoverflow.com/
    2. https://www.kaggle.com/
    3. https://www.google.com/
    4. https://towardsdatascience.com/
    5. https://medium.com/


## Contact
Created by [https://github.com/kuldeeplodha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->