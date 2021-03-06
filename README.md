# Forecast of bitcoin using Python's scikit-learn
With the recent bitcoin craze, I thought it would be fun to try and create a machine learning algorithm to forecast bitcoin. I used two datasets in csv format, which can be found [here](https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory/data). The two datasets contain over a thousand daily entries pertaining to various information about bitcoin. Utilizing different inputs, scikit-learn's MinMaxScaler and MPLRegressor, a forecast of bitcoin was created. Further analysis was done using scikit-learn's mean_squared_error to sum the squared errors between the expected output and my predicted output. From there, I changed the inputs to minimize the mean squared error and optimize the forecast's accuracy. 

## Machine Learning Flow Diagram
![alt-text](Diagram.png)
