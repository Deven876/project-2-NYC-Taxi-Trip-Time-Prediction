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

 ### :floppy_disk: Project Files Description</h2>

This Project includes 2 executable files, 1  python file and 1 directory as follows:</p>
 #### Executable Files:

  <li><b>project_2_Taxi_Trip_Time_Prediction_.ipynb</b> - Includes all functions required for classification operations.</li>
  
 #### Source Directories:</h4>

  <li><b>Train and test directory</b> - Includes all training and testing data </li>

  
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)  

<h2>:book: Random Forest </h2>
  
  Random Forest is a popular machine learning algorithm that belongs to the supervised learning technique. It can be used for both Classification and Regression problems in ML. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.

As the name suggests, "Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset." Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.

The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png) 

# 📋 Execution Instruction
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

* #### PCA
* #### Linear Regression
* #### Decision Tree
* #### Random Forest

Random Forest perfomed best with PCA performed data

Root Mean Squared Error (RMSE) is chosen as the metric. The metric showed an RMSE of 221 seconds in predictions of trip time.

Achieved R2 score of 91% which menas 91 % correctly trip duration can be explained using data.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="credits"> :scroll: Credits</h2>

< Devendra Bhangale > | Problem Solver | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devendra-bhangale-b326a1169/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Deven876)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@devabhangale)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

📚References
1.Haversine Distance - https://www.igismap.com/haversine-formula-calculate-geographic-distance-earth/
2.NYC boundaries - https://gist.github.com/jakebathman/719e8416191ba14bb6e700fc2d5fccc5
3.Random Forest Regressor - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
