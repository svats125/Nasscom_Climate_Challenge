# f25cdd11-ee25-46fb-91db-aba028d3e2e9
https://sonarcloud.io/summary/overall?id=examly-test_f25cdd11-ee25-46fb-91db-aba028d3e2e9
# HEATWAVE & AQI PREDICTION
Foreacsting the heatwave and AQI occurences for 5 districts of Telangana - Adilabad, Karimnagar, Khammam, Nizamabad & Warangal for the year 2023

## How to run 
* Download the entire repo as a zip file
* Run the 'Heatwave-Final.ipynb' file with other 10 dataset files in the same folder as the notebook file

## Dataset 
There are a total of 10 .csv files in dataset. Two for each district- one containing data from 2018-2022 and the other containing data  projected for the year 2023 for certain features

Features used :
* Maximum & Minimum Temperature
* Rainfall
* Maximum & Minimum Humidity
* Maximum & Minimum Wind speed
* SO2, NH3, NOx, PM2.5, PM10
* Vehicle Sales

Granularity - Daily , Mandal-wise

## Model
1. Exponential Smoothing - For forecasting input features for the year 2023
2. Random Forest Regression - For predicting heatwave occurence
3. Support Vector Regression - For predicting AQI values 

