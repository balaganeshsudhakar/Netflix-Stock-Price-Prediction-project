Netflix Stock Price Prediction
Project on Netflix Stock Price Prediction Using SVR,GBR,LR Method Prediction
Description
In the New & Old era stock market plays a important vital roles in economy of the country, Thus stock market price trend prediction is always a hot topic for researchers from both financial and technical domains. In this research, our objective is to build a state-of-art prediction model for price prediction using python as major role , support vector Regression(SVR),Linear Regression(LR) & Gradient Boosting Regression(GBR) methods the prediction is done

Approach

Here in my project Netflix Stock Price Prediction i have used following steps

Importing the required Libraries such as
Pandas
Numpy
Matplotlib
sciket learn for
splitting data
importing support vector Regressor
importing Gradient Boosting Regressor
Importing Linear Regressor
Minmax scaler.

Reading required Data - I have taken Netflix stock data

collecting Data information

Dropping the Adjecent closing values

forcasting

Droping the pridiction which has Nan values

slicing the array tp exclude the last forecast_out rows for x values

splitting the Data for training & testing

scaling using minmax scaler

using the SVR (support vector Regression) finding the svr confidence value

using the LR (linear Regression) finding the lr confidence value

using the GBR(gradient boosting Regression). finding the GBR confidence value

find the x forecast

predicting with svr,gbr,lr

using minmax scaler finding the x test 1

using kneighborsRegression fing the root mean square error(rmsr) value

plotting Rmse vs k value graph we get a elbow curve

predicting

Cross validation

splitting train and test

fitting the training and testing and validations

finding the train and test indexs

predicting the scores & percentage

Scaled Cross-validated scores (in percentage): [ 86.3482035 44.8661837 100. 55.29330478 62.78674938
91.23357129 72.42554908 28.59619398 80.97659899 0. ]
The end
