# Time Series Forecasting for Energy Consumption


## 0. Introduction: 

### Time Series Analysis 
Time series refers to an arrangement and presentation of statistical data in chronological order. The statistical data is collected over a period of time. According to Spiegel, “A time series is a set of observations taken at specified times, usually at equal intervals.” There exist various forces that affect the values of the phenomenon in a time series. These are also the components of the time series analysis

1. Secular Trend or Simple trend or Long term movement: Secular trend refers to the general tendency of data to increase or decrease or stagnate over a long period of time. Time series relating to Economic, Business, and Commerce may show an upward or increasing tendency. Whereas, the time series relating to death rates, birth rates, share prices, etc. may show a downward or decreasing tendency.
2. Seasonal variations: Seasonal variations refer to the changes that take place due to the rhythmic forces which operate in a regular and periodic manner. These forces usually have the same or most similar pattern year after year. When we record data weekly, monthly or quarterly, we can see and calculate seasonal variations. Thus, when a time series consists of data only based on annual figures, there will be seen no seasonal variations. These variations may be due to seasons, weather conditions, habits, customs or traditions. For example, in summers the sale of ice-cream increases and at the time of Diwali the sale of diyas, crackers, etc. go up.
3. Cyclical variations: Cyclical variations are due to the ups and downs recurring after a period from time to time. These are due to the business cycle and every organization has to phase all the four phases of a business cycle some time or the other. Prosperity or boom, recession, depression, and recovery are the four phases of a business cycle.
4. Random or irregular variations: Random variations are fluctuations which are a result of unforeseen and unpredictable forces. These forces operate in an absolutely random or erratic manner and do not have any definite pattern. Thus, these variations may be due to floods, famines, earthquakes, strikes, etc.

### XGBOOST
 * XGBoost is a machine learning algorithm that falls under the broader category of gradient boosting, which is a type of ensemble learning.
 * Speed - parallelization, cache optimization, out of memory computation
 * Performance - regularization, auto proning, missing values treatment
 * language support, integrable, portable

## 1. Time Series Forecasting for Energy Consumption:
* Dataset Exploration: Initial analysis and visualization of the PJME hourly dataset, showcasing energy consumption trends.
* Train-Test Split: Division of the dataset into training and test sets, with the split occurring at the start of 2015.

## 2. XGBoost Model Training and Evaluation:
* Feature Engineering: Creation of time-related features to enhance model understanding.
* Model Selection: Adoption of the XGBoost algorithm for time series forecasting.
* Forecasting and Evaluation: Training the model on the training set, forecasting on the test set, and assessing performance using Root Mean Squared Error (RMSE).
* Error Analysis: Identification of best and worst prediction days, providing insights into model strengths and weaknesses.
  
## 3. Results:

![01  PJME energy used in MW](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/cb4caeaa-4fa9-407b-8aa2-2791c0fc7959)

![02  data train   test split](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/e468b603-d950-4a21-897c-5660dd20ffaa)

![03  week of data](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/ce7ebb00-70ad-4249-bc0f-0dd27dedcca2)

![04  MW by Hours](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/8cdaeedd-57b3-40a3-a289-d87e8133fa41)

![05  MW by Months](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/7ef363d5-4c79-470a-a847-52ef6a2783dd)

![06  Feature importance](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/c06c2561-d4a3-4dbb-93ab-61d22cb90a82)

![07  Raw data and Prediction](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/2145567d-5e8c-4743-aefe-2f8b1421ba6a)

![08  week of data (Truth data + prediction)](https://github.com/ArpitaSatsangi/Time-Series-Forecasting/assets/107709451/5a5ba5bb-ccfd-4663-99fd-cd632e87a947)
