# Boombikes Bike sharing system-Assignment
> Building a Multiple Linear Regression Model and find the variables significant in predicting the demand for shared bikes and how well those variables describe the bike demands.


## About The Project
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Technologies Used
-  pandas - 1.3.4
-  numpy - 1.20.3
-  seaborn - 0.11.2
-  matplotlib : 3.4.3
-  stasmodel- 0.12.2
-  sklearn- 0.24.2


## The company wants to know:

    * Which variables are significant in predicting the demand for shared bikes.
    * How well those variables describe the bike demands
    

## Steps followed during analysis
-  Step 1: Reading and Understanding the data
-  Step 2: Data visualization and outliers detection (if any)
-  Step 3: Data preparation
-  Step 4: Splitting the data into training and test sets
-  Step 5: Rescaling the variables
-  Step 6: Residual Analysis of the train data
-  Step 7: Making predictions using the test dataset with out model
-  Step 8: Model Evaluation and  Equation
-  Conclusion

Conclusions
- Temp is the most significant variable with the largest positive coefficient, with increase in temperature bike rentals increases.
- The count of bike sharing is increasing with year.
- Bike rentals is more for the winter season
- Bike rentals is more for the month of september
- The rentals reduce during bad weather i.e. weathersit_Light Snow & Rain
- The rentals reduce during high wind speed
- This indicates that the bike rentals is majorly affected by temperature,season and bad weather.

## Contact
Created by [@AjayDabral] - feel free to contact me!
