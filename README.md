# PREDICTION OF FUEL CONSUMPTIONS


A machine learning model is proposed for estimating fuel consumption for a vehicle, based on existing data on its MPG(Miles Per Gallon), cylinders, displacement horsepower, weight, acceleration, model year and origin attributes.


Exploratory data analysis was done first because if the model is fed with data which does not have any problem such as missing values, more consistent and realistic results will be obtained. Then, outliers from our dataset to get accurate predictions were excluded. After clearing data and analyzing them, features that were expected to be useful in explaining the target variable were determined. This step is called feature extraction. Regularization methods such as Lasso, Ridge, Elastic Net and XGB method are used to find the smallest Mean-Square Error. Then averages of two regularization methods which have minimum Mean-Square Error value were taken. 

Finally, an optimization exercise (Predicting the MPG) was carried out to minimize fuel consumption via modification of controllable vehicle characteristics such as acceleration.

In this project you can see the exploratory data analysis and difference machine learning models that predict fuel consumption.

**You can find the detailed code and project report above!**

