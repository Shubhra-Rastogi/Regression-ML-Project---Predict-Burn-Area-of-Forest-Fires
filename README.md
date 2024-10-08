# Regression/ML Project - Predict Burn Area of Forest Fires

🌟 IBM Data Science Professional Certificate Project 1 : UCI Forest Fires 🌟
---

This is a difficult regression task, where the aim is to predict the burned area of forest fires, in the northeast region of Portugal, by using meteorological and other data. This data set is sourced from the UCI Machine Learning Repository.

Understanding the causes and timings of forest fires is crucial, given their potential threat to human lives. The dataset utilized in this project is linked to a scientific study focused on predicting forest fire occurrences in Portugal through modeling techniques. However, the project's scope extends beyond modeling to include data visualization. An exploratory analysis of the data will also be conducted to gain a deeper understanding and identify any possible insights within the dataset.
##
Project Tasks:

- Data Exploration: missing values, duplicated values
- Data Analysis: outlier detection, response insights, initial visualization to understand the data
- Data Pre-Processing: cleaning and sorting data
- Machine learning model: Test/Train split, sklearn vector
- Parameter Tuning 
## 
Attribute information:

- X - x-axis spatial coordinate within the Montesinho park map: 1 to 9
- Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9
- month - month of the year: "jan" to "dec"
- day - day of the week: "mon" to "sun"
- FFMC - FFMC index from the FWI system: 18.7 to 96.20
- DMC - DMC index from the FWI system: 1.1 to 291.3
- DC - DC index from the FWI system: 7.9 to 860.6
- ISI - ISI index from the FWI system: 0.0 to 56.10
- temp - temperature in Celsius degrees: 2.2 to 33.30
- RH - relative humidity in %: 15.0 to 100
- wind - wind speed in km/h: 0.40 to 9.40
- rain - outside rain in mm/m2 : 0.0 to 6.4
- area - the burned area of the forest (in ha): 0.00 to 1090.84 (this output variable is very skewed towards 0.0, thus it may make sense to model with the logarithm transform).
