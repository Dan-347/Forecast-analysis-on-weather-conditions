# Predictive analysis of weather conditions in Biak Numfor

This project aims to analyze weather patterns and changes in Biak Numfor Regency during the period from January 2010 to August 2023, as well as to develop a prediction model based on historical data. The weather variables analyzed include:
- Minimum temperature
- Maximum temperature
- Average humidity
- Rainfall
- Maximum wind speed
- Wind direction at maximum speed

The analysis was conducted starting from data cleaning, trend and correlation analysis, to the development of a prediction model using Extreme Learning Machine (ELM). The model was not used to predict actual future data, but was tested using historical data to measure its performance.

## Background
The weather in Biak Numfor is known to be quite dynamic and often changes suddenly, which can affect various community activities such as flights, fishing activities, and daily planning. Although weather data is collected annually, this information is usually only used as a record without further analysis to identify patterns, trends, or relationships between variables. Therefore, more in-depth analysis and testing of prediction models are needed to determine whether historical data can help predict future weather conditions. This approach can be a first step toward a more accurate weather forecasting system that is useful for the local community.

## Objectives
This project aims to:
1. Analyzing weather patterns in Biak Numfor from 2010 to 2023.
2. Performing trend and correlation analyses to understand the relationships between weather variables.
3. Building a prediction model using the Extreme Learning Machine (ELM) method.
4. Testing the model's performance using historical data that the model has not seen before.
5. Evaluating the accuracy level using MAE, MAPE, MSE, RMSE, and coefficient of variation metrics.
6. Providing insight into the potential of this model for use in long-term weather prediction.

## Why This Analysis Matters
This analysis is important because it helps to understand how weather variables in Biak Numfor change over time and how consistently these patterns can be studied by predictive models. By evaluating model performance based on historical data, this study provides an overview of the potential and limitations of the forecasting methods used. These insights can be a first step in developing a more informative and useful weather prediction system for environmental monitoring and future activity planning needs.

## Analysis Steps
The analysis steps include:
1. **Data Collection** <br>
The first stage began with understanding the characteristics of Biak Numfor weather data for the period January 2010 – August 2023.
2. **Data Cleaning & Preprocessing** <br>
This stage ensures that the data is clean and ready for analysis and use as model input. The process involved selecting the variables to be used, removing missing values, converting date columns into datetime format, and removing outliers. The objective of this stage is to produce a consistent, accurate dataset that is suitable as input for statistical analysis and machine learning models.
3. **Exploratory Data Analysis (EDA)** <br>
This stage is used to understand patterns, trends, and relationships between variables through descriptive statistical analysis and visualization. The analysis conducted was to observe long-term patterns (increase, decrease, stable) for each weather variable and identify seasonal patterns such as high rainfall in certain months or temperature increases in certain periods.
4. **Modeling with Extreme Learning Machine (ELM)** <br>
During the modeling stage, the dataset is first divided into a training set and a testing set to ensure that the model can be trained on a portion of the data and evaluated using data it has never seen before. After the division is complete, the Extreme Learning Machine (ELM) model is trained to learn patterns and relationships between weather variables based on the data in the training set, so that the model can recognize the general structure needed to make predictions.
5. **Model Evaluation** <br>
After the model generates predictions, its performance is evaluated by comparing the predicted values with the actual values. The evaluation metrics used are MAE (Mean Absolute Error), MAPE (Mean Absolute Percentage Error), MSE (Mean Squared Error), RMSE (Root Mean Squared Error), and Coefficient of Variation. The interpretation is done to assess whether the model is sufficiently accurate and stable.

## Insights
Based on an analysis of weather trends in Biak Numfor from January 2010 to August 2023, the patterns of change in each variable show quite diverse dynamics. Minimum temperature, maximum temperature, and average temperature show relatively stable annual fluctuations, although there are indications of a gradual increase, especially in maximum temperature values. This condition illustrates the long-term warming trend commonly found in tropical coastal areas. Meanwhile, average humidity does not show a clear upward or downward trend, but rather fluctuates according to changing atmospheric conditions and seasons. Rainfall is the variable with the highest level of volatility, as seen from the significant difference between the maximum and annual average values, as well as the sharp ups and downs in certain periods. The duration of sunshine tends to be stable with small variations from year to year, while maximum wind speed shows a sharper pattern of change and often experiences extreme spikes. The direction of maximum wind speed varies widely, indicating the influence of sea-land winds and regional atmospheric dynamics. The correlation results show that the relationship between variables is weak, indicating that weather conditions in Biak Numfor are influenced by many independent factors.

The results of testing the Extreme Learning Machine (ELM) model show that the model is able to follow historical patterns well for variables such as temperature and humidity, which have smoother trends. However, its accuracy decreases for variables with extreme fluctuations, such as rainfall and wind direction, so this model is more suitable for use as a baseline rather than for long-term operational predictions. These findings reinforce the notion that weather modeling in coastal areas requires additional data and a more complex approach in order to capture atmospheric dynamics more accurately.

## Conclusion
Overall, the analysis results show that the temperature in Biak Numfor has a gradual upward trend, while humidity and sunlight are relatively stable. Variables such as rainfall and wind have much higher fluctuations, making them the most difficult components to predict. Testing of the ELM model shows good performance for variables with stable patterns such as temperature, but is less accurate for highly volatile variables. This indicates that ELM is suitable for use as a basic model, but more precise weather predictions require a more complex approach and additional supporting data.
