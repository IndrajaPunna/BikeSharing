# BoomBikes Bike Sharing Service

> BoomBikes, a US bike-sharing provider hit by pandemic-related revenue challenges, is partnering with a consulting firm to model the demand for shared bikes post-lockdown. Their goal is to identify significant variables influencing demand, allowing strategic business adjustments to meet customer expectations and stand out in the market. Leveraging meteorological surveys and lifestyle data, they aim to create a predictive model that will guide the company in adapting its services to the evolving needs of customers, positioning BoomBikes for success in the post-pandemic economic landscape.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

- We are building the linear regression model from the dataset provided.
- The dataset we are using is bikesharing.csv file provided by the BoomBikes client.
- In this project we tried to figure out which features are most important and affect the demand for the Boombikes and what are the most important factors that drive the demand for bikes.

## Conclusions

- temp and atemp variables seem to have highest correlation with the target variable cnt by looking at the above pair-plot for numerical variables.
- Demand for the bikes seem to be very less during spring season and it seems to be on the higher side in fall season.
- The demand has risen considerably during 2019 compared to 2018.
- Demand seems to be high in September month and low in the month of January.
- There is not much of a difference in the demand during various days of a week. So, weekdays might not affect the demand. 
- The demand for bikes is very low during Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds days and high during Clear, Few clouds, partly cloudy, Partly cloudy days.
- cnt variable has high positive correlation with temp and atemp and negative correlation with windspeed.
- Distplot for residuals shows normal distribution with mean at 0.0, hence validating the assumption for linear regression
- The r2 scores of training and test data are very near. The percentage difference in r2 scores is less than 5%. Hence we consider this model is appropritae

## Technologies Used

- numpy - version 1.26.0
- pandas - version 2.1.1
- matplotlib - version 3.8.0
- seaborn - version 0.13.0
- scikitlearn - version 1.3.2
- statsmodel - version 0.14.1

## Acknowledgements

- This project was based on Linear Regression tutorial on Upgrad.

## Contact

Created by [@IndrajaPunna] - feel free to contact me!
