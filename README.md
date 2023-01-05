#Linear-Regression-Bike-Sharing-Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information
- Problem:
		A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
		
		In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- Agenda :
		Which variables are significant in predicting the demand for shared bikes.
		How well those variables describe the bike demands	
	
- DataSet : 
		day.csv

- Steps Followed : 
		~ Reading and Understanding the Data
		~ Data Visualization
		~ Data Preparation
		~ Model Building
		~ Residual Analysis
		~ Making Predictions
		~ Model Evaluation

## Conclusions
	Fall season seems to have attracted more booking. And, in each season the booking count has increased from 2018 to 2019. 
	Most of the bookings has been done during the month of may, june, july, aug, sep and oct. Trend increased starting of the year till mid of the year and then it started decreasing as we approached the end of year. 
	Clear weather attracted more booking.
	Sun and Mon have comparatively less bookings.
	Booking is less on holidays.
	Booking seemed to be almost equal either on working day or non-working day. 
	2019 attracted more number of booking from the previous year, which shows good progress in terms of business.

## Technologies Used
Language : Python 

Libraries : 
      - pandas (To work with dataset)
      - numpy (Math library)
      - seaborn (Graph library that use matplot in background)
      - matplotlib.pyplot (to plot some parameters in seaborn)
      - warnings (to ignore warnings)
	  - sklearn.model_selection (to split the dataframe into Train and Test)
	  - sklearn.preprocessing (Using MinMaxScaler to Rescaling the features)
	  - sklearn.feature_selection (Importing RFE)
	  - sklearn.linear_model (Importing LinearRegression)
	  - statsmodels.stats.outliers_influence (Check for the VIF values of the feature variables)
	  - statsmodels.api (Building linear regression model)
	  - sklearn.metrics (R-squared score)

## Contact
Created by :
        Alok Narayan(https://github.com/aloknarayan23)
		            - feel free to contact me!