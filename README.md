# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Background:
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

Business Goal:
I am required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

Dataset:
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusions

Ride count is 
	1) Heavily influenced by feeling temperature
	2) turning fortunes with more rides on new year
	3) negatively impacted considerably by humidity,windspeed
	4) Improved by Saturday and Clear weather

$ cnt = .23 + .23  \times\  yr + 0.05  \times  workingday + 0.5 \times atemp - 0.15 \times hum - 0.15 \times windspeed - 0.11 \times season_spring + 0.05 \times season_winter - 0.07 \times mnth_jul  + 0.06 \times mnth_sept + 0.06 \times weekday_sat + 0.0.06 \times waethersit_great - 0.19 \times weathersit_medium $

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
python==3.10.12
numpy==2.2.2
pandas==2.2.3
seaborn==0.13.2
re==2.2.1
platform==1.0.8
zipfile36==0.1.3
statsmodels==0.14.4
sklearn==1.6.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
This project was inspired by Upgrad and completed by Venkadesh Kannan Email: venkadesh@gmail.com- 

## Contact
Created by [@venkadesh-kannan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
