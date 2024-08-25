# Project Name
> This project involves developing a multi-linear regression model to predict the demand for bike-sharing services based on various factors such as weather conditions, seasonal data, and temporal variables.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project aims to understand and predict the factors influencing the demand for bike-sharing services in the American market.
- **Background:** BoomBikes, a US-based bike-sharing provider, has experienced a significant dip in revenue due to the ongoing pandemic. The - company seeks to anticipate the demand for shared bikes once the situation improves.
- **Business Problem:** The key problem is to forecast the demand for bike rentals, which will help BoomBikes optimize their operations and - resource allocation.
- **Dataset:** The dataset includes daily records of bike rentals, categorized by factors such as weather conditions 
  (e.g., temperature,humidity, wind speed), seasonal data (e.g., spring, summer), and temporal factors (e.g., year, month, day of the week). 
- The target variable is the total number of bike rentals (`cnt`).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Seasonal Influence:** Summer and Fall seasons significantly increase bike-sharing demand compared to Spring and Winter.
- **Weather Impact:** Favorable weather conditions, particularly higher temperatures, lead to increased bike rentals, 
  while adverse conditions like light snow/rain reduce demand.
- **Temporal Trends:** Bike-sharing demand increased from 2018 to 2019, reflecting the growing popularity of the service.
- **Feature Selection:** The final model effectively reduced multicollinearity by selecting key features with low VIF 
- and significant p-values, leading to more reliable predictions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- **Python 3.8**
- **pandas 1.3.3**
- **scikit-learn 0.24.2**
- **statsmodels 0.12.2**
- **matplotlib 3.4.3**
- **seaborn 0.11.2**

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on (https://learn.upgrad.com/).


## Contact
Created by [@amitpataskar] - feel free to contact me!
