# <b><u> Project Title : Taxi trip time Prediction : Predicting total ride duration of taxi trips in New York City</u></b>

## 📋<b> Problem Description </b>

### Your task is to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📋<b> Data Description </b>

### The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set.

### <b>NYC Taxi Data.csv</b> - the training set (contains 1458644 trip records)


### Data fields
* #### id - a unique identifier for each trip
* #### vendor_id - a code indicating the provider associated with the trip record
* #### pickup_datetime - date and time when the meter was engaged
* #### dropoff_datetime - date and time when the meter was disengaged
* #### passenger_count - the number of passengers in the vehicle (driver entered value)
* #### pickup_longitude - the longitude where the meter was engaged
* #### pickup_latitude - the latitude where the meter was engaged
* #### dropoff_longitude - the longitude where the meter was disengaged
* #### dropoff_latitude - the latitude where the meter was disengaged
* #### store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
* #### trip_duration - duration of the trip in seconds

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# 📋 Summary
This project aims to predict New York city taxi trip times.

The dataset consists of 1458644 rows and 11 columns, containing features such as trip longitude and latitude values, day, month, year of the trip, etc.

The project is executed in 4 main steps:

* #### Data cleaning and feature engineering
* #### Exploratory data analysis
* #### Model building and evaluation
* #### Model tuning.

Features such as speed and distance are engineered, to create useful variables. Using latitude and longitude values the area of New York was focused on.

Exploratory data analysis (EDA) was performed, both univariate and bivariate analysis were done to gain better understanding about the data. Some understanding from the data was received such as, single passenger trips are the highest, March is the busiest month, Saturday is the busiest day, trips mostly range to 2000 seconds, highest average speed during the day is at 5 AM, etc.

Models experimented with:

* #### Decision Tree
* #### Random Forest
* #### Gradient Boost
* #### XGBoost

Random Forest perfomed best after hyperparameter tuning.

Root Mean Squared Error (RMSE) is chosen as the metric. The metric showed an RMSE of 221 seconds in predictions of trip time.

Improvement of 68% or reduction in deviation of time prediction by 8 minutes compared to the prediction deviations from the mean.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="credits"> :scroll: Credits</h2>

< Vidhuran Rajendran > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/vidhuran)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](github.com/Vidhuran-Rajendran)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@vidhuran_07)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

📚References
1.Haversine Distance - https://www.igismap.com/haversine-formula-calculate-geographic-distance-earth/
2.NYC boundaries - https://gist.github.com/jakebathman/719e8416191ba14bb6e700fc2d5fccc5
3.Random Forest Regressor - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
