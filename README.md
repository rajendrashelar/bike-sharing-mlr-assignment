# Bike Sharing Demand Model using multiple linear regression

> This model is developed to analyse the demand for shared bikes with the available datasets. This will be used by the management to understand the demands vs features. Management will adjust business strategy to meet customer's expectations and demands. In addition, this model will guide management on the developing new strategy to meet new demand in this domain. 


## Table of Contents
* [Background](#background)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

### Background
- Bike usage is generally effective for short distance travel where carrying own bike is not feasible hence bike-sharing business is good idea to serve such commuters. To manage sharing of the company bike, there is need of the system which provides ease in renting the bike for short term where they don’t need to worry about maintenance of the bike.  This project will help companies who are running such business to enhance their system to serve better to their customers
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
### Problem Statement
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
### Dataset
- Large dataset on daily bike demands across the American market gathered using various meteorological surveys and people's styles which has usage pattern based on Season, Weather, Duration, Period etc. 

## Conclusions
- Data interpretation, data visualisation, data pre-processing was done to design the model for feature selection, residual analysis
- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library
- Categorical Variables	Analysis
  - season	
    - Bike demand likely to be higher in summer and fall season. 
    - Marketing campaigns can be planned around this period
  - yr
    - Bookings increased in Year 2019 compared to previous year
  - mnth
    - Booking is higher between June to October months.
  - holiday
    - Ad-hoc (casual ) customers prefers biking during holiday whereas registered users less biking during holiday
  - weekday
    - bike usage is higher on working days by registered users whereas Ad-hoc (casual) users book bike less on weekday
  - workingday
    - There is no much difference in the booking over weekend or weekdays. Bike rental is high during weekday by registered users
    - There are bookings on working days by registered users and ad-hoc booking over weekend hence this information does not give much to identify potential customers*. 

  - weathersit
    - Usage of the biked by Registered users is higher irrespective to weather condition.

#### Usage can be generalised as commuting to the workplace / school etc 
#### Typically, common weather if high usages is clean/few clouds days


## Technologies Used
- python and excel was used to perform the analysis 
- following libraries in the python used 
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy


## Acknowledgements
- This project was developed as part of assignment 

## Contact
Created by [rajendrashelar] - feel free to contact me!
 
