# Bike-Sharing-Demand-Prediction:
## **Problem Description**
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

![image](https://user-images.githubusercontent.com/100409195/173507855-261c814b-bded-4bde-a7ba-c5b945893607.png)

# **Data Description:**
 The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

### <b>Attribute Information: </b>

* ### Date : year-month-day
* ### Rented Bike count - Count of bikes rented at each hour
* ### Hour - Hour of he day
* ### Temperature-Temperature in Celsius
* ### Humidity - %
* ### Windspeed - m/s
* ### Visibility - 10m
* ### Dew point temperature - Celsius
* ### Solar radiation - MJ/m2
* ### Rainfall - mm
* ### Snowfall - cm
* ### Seasons - Winter, Spring, Summer, Autumn
* ### Holiday - Holiday/No holiday
* ### Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


# **Data Pipeline:**

*  **Data Understanding:** Understanding the data set available, getting to know about the dependent variable and independent variables, their data type, have an overview    of the statistics of the numerical features in our dataset.
* **Data Processing:** Making the data fit for future analysis is the main objective of this step. During this stage, gone through each input variable and studied the      type of features make them suitable for the analysis and tried to further break down the features into segments to make our dataset more informative like we did        to date column. Also, looked forward to the outliers, null values to keep our data free from any anomaly. Checking for the duplicate values as it can mar the          accuracy of our dataset. 

* **EDA**: EDA or Exploratory Data Analysis to observe  certain trends and dependencies and also drawn certain conclusions from the dataset that will be useful for        further processing

* **Model Building:** During this step we have fit our data to different models and tried to fit our data to different models and predicted the output and then            calculated the metrics to check which ever model fits the best for further predictions.

# **Observations:**
* From the model evaluation table Linear regression ,Ridge Regression,Lasso Regression is not giving great results.

* Random Forest tuning with Randomized Search CV and  Gradient Boosting Regressor with GridSearchCV is giving comparably good results R2 score is 89% and 91% repectively.


# **Summary:**
* Starting with loading the data and having an understanding of the data next step is processing the data set by looking and treating the outliers, duplicates, missing values ,encoding of categorical columns, transforming the data,checking, transforming the data according to the assumption  was a challenging task and at last building the model. Testing the models on the test data the R2 score ranged from 54.5% to 91.5% and hypertunned  Gradient Boosting Regressor giving the best results.







