# kaggle-housePrice
predicting price of houses from features using lenear regression


num of features = 80


for train:

  {labeling data except NaN
  
  replacing mean of columns inplace of NaNs
  
  scaling using standard scaler}
  
for test:

  {labeling data except NaN
  
  replacing mean of columns inplace of NaNs
  
  scaling using standard scaler}
  
testing different ways of considering features(heatmap for most important features / only number-type data / all) -> "all" gave the best result

split train data to test and train(65 to 35 was best)

fitting on train data

predicting on train data to find R^2, MAE, MSE, RMSE for both train and test of train data

predicting prices of test data from features
