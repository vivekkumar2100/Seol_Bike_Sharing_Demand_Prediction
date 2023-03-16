# Seol_Bike_Sharing_Demand_Prediction
LINEAR REGRESSION SUPERVISED MACHINE LEARNING

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. Data Description The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

# Variable

Date : year-month-day
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity- %
Windspeed - m/s
Visibility - 10m
Dew point temperature** - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn

# Steps

1-PROBLEM STATEMNET-The main objective is to build a predictive model, which could help to train a model 
                    to predict the number of bike rentals of the year given the weather conditions.
2-Importing the data
3-Data Processing (Treatment of null values and outliers
4-Exploratory Data Analysis
5-Feature Selection
6-Splitting the Data into train and test data
7-Fitting the different model like (Linear Regression,Lasso,Ridge,Elastic,Random Forest Regression,Cross Validated Random ForesT,Polynomial Regression
8-Evaluation of different model on different metrics like Mean Absolute Error,Mean Squared Error,Root Mean Squarede Error,R2_Score
9-Comparison of different model
10-Conclusion

# Conclusion

During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Rented Bike Count' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented 6 machine learning algorithms Linear Regression,lasso,ridge,elasticnet,Random Forest. We did hyperparameter tuning to improve our model performance. The results of our evaluation are:

No overfitting is seen.

Random forest Regressor and Gradient Boosting gridsearchcv gives the highest R2 score of 99% and 94% recpectively for Train Set and 92% for Test set.

Feature Importance value for Random Forest and Gradient Boost are different.

We can deploy this model.

However, this is not the ultimate end. As this data is time dependent, the values for variables like temperature, windspeed, solar radiation etc., will not always be consistent. Therefore, there will be scenarios where the model might not perform well. As Machine learning is an exponentially evolving field, we will have to be prepared for all contingencies and also keep checking our model from time to time. Therefore, having a quality knowledge and keeping pace with the ever evolving ML field would surely help one to stay a step ahead in future.
