# Predicting-the-AQI-of-Indian-Cities-Using-Machine-Learning : H2O.ai Hackathon

# Introduction

Air Quality Index (AQI) is a crucial indicator of the air quality in a given area, providing valuable insights into the potential health risks associated with air pollution. With the rise of urbanization and industrialization, many cities in India face significant air quality challenges. Accurate prediction of AQI can aid in proactive planning and policy-making to mitigate the adverse effects of air pollution on public health and the environment.

This project aims to develop a machine learning model that predicts the AQI of Indian cities based on various environmental and meteorological factors. By harnessing historical air quality and relevant feature data, we intend to create a predictive model that can assist local authorities and residents in understanding and preparing for potential changes in air quality. 


# Objectives

The primary objectives of this project are as follows:

# Data Collection: 
 Gather historical AQI data from various cities across India, along with relevant environmental and meteorological features such as particulate matter levels (PM2.5, PM10,O3,CO,SO2),StateCode,AQI Values.

# Data Preprocessing: 
Clean, preprocess, and transform the collected data into a suitable format for training machine learning models.
Handle missing values, outliers, and ensure data consistency.

# Feature Selection/Engineering: 
Identify the most influential features impacting AQI and perform feature engineering if necessary. 
This step aims to enhance the model's predictive power by focusing on key variables.

# Model Selection:
Explore and evaluate different machine learning algorithms such as  i choosen  ARIMA,SARIMAX,FB PROPHET. Choose the most appropriate model based on performance metrics.

# Model Training:
Train the selected machine learning model using historical data. 
Implement techniques like cross-validation to prevent overfitting and ensure generalization.

# Model Training: 
Train the selected machine learning model using historical data. Implement techniques like cross-validation to prevent overfitting and ensure generalization.

# Model Evaluation: 

Assess the model's performance using relevant evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE). 

 > I got MAE for FB PROPHET MODEL IS  : 528.99

 > I got MAE FOR  SARIMAX MODEL IS : 36.89
>  I MAE for ARIMA + BoxCox transformation : 32

 > Which ever has less MAE VALUE perfoms well 

 > So I have choosen ARIMA + BoxCox Transformation MODEL to train future data values 


# Conclusion
This project aims to contribute to the understanding and prediction of air quality in Indian cities using machine learning techniques.
By developing an accurate AQI prediction model, we aspire to empower local governments, policymakers, and residents with valuable information to make informed decisions and take proactive steps toward improving air quality and public health.





