# Formula 1 Results Prediction Project

![formula-1-puts-pedal-metal-digital-acceleration](https://github.com/user-attachments/assets/52a186ca-fbc1-4d36-836b-1e433e4a2289)

##Predicting race winners using XGRADIENT Boost
###Background

I am a huge motorsports fan, whether Formula 1, or Indycar, or endurance racing. So as someone wanting to improve my data skills it seems natural I should try and combine this with one of my favirote hobbies. For this project I found a really extensible api that has a good mix of categorial and numerical data. We can query this api
The Model - XGradient Boost Reg:MSE

When first researching this I went through several models to determine what would be the best one to use in the given scenario. Since we have many parameters, from telemetry data on cars to historical driver data, I wanted a model that could handle mutliple data sets and still provide an accurate result. Something like binary classification or rank order modeling would not be well suited for this scenario. We have numeric data, sequential data, classification data etc. Since we want to show the predicted result as a real number we can use linear regression for this problem.

I also wanted to choose a model that would improve over each iteration and be able to handle missing values if needed. With those criteria in mind using XGBoost seemed to make the most sense in this scenario. Now lets see if we can use this model to predict the race winner for a given session using variuos data points gathered.

###Libraries and Resources Used
XGboost
Scikit-learn
OpenF1 API

This project is ongoing and more updates will be commited
