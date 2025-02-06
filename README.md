# Predicting-Air-Quality-Index

Let us see how to predict the air quality index using Python. AQI is calculated based on chemical pollutant quantity. By using machine learning, we can predict the AQI.

AQI: The air quality index is an index for reporting air quality on a daily basis.  In other words, it is a measure of how air pollution affects one’s health within a short time period. The AQI is calculated based on the average concentration of a particular pollutant measured over a standard time interval. Generally, the time interval is 24 hours for most pollutants, and 8 hours for carbon monoxide and ozone.

Let’s find the AQI based on Chemical pollutants using Machine Learning Concept. 

Data Set Description:

It contains 7 attributes, of which 6 are chemical pollution quantities and one is Air Quality Index. AQI Value, CO AQI Value, Ozone AQI Value, NO2 AQI Value, PM2.5 AQI Value, lat,LNG are independent attributes. air_quality_index is a dependent attribute. Since air_quality_index is calculated based on the 7 attributes.

As the data is numeric and there are no missing values in the data, so no preprocessing is required. Our goal is to predict the AQI, so this task is either Classification or regression. So as our class label is continuous, regression technique is required.

Regression is supervised learning technique that fits the data in a given range. Example Regression techniques in Python:

Random Forest Regressor
Ada Boost Regressor
Bagging Regressor
Linear Regression etc.

After seeing the accuracy of our model, we can say that by given test data we got 9.9 and 46.5952 so the air is healthy.

Like my work, give me a star and fork this repository.

Thanks!
