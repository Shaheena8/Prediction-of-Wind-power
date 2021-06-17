# Prediction-of-Wind-power
Prediction of wind Power from windmills
 This submission consists of 3 files one is the prediction powers in train.csv, test.csv
 and source code in windTurbine_forecast-Submission1 ipython notebook. 

Step 1:
 Decide the targrt variable.
 Perform EDA on all the features with respect to target variable

Step 2: 
 Train and test data has similar density functions, hence outliers are not eliminated from the train dataset. 

Step 3:
 The catagorical data cloud_level and turbine staus are considered as catagorical data.
 The target is randomly distributed w.r.t these catagorical data.
 Hence we choose random forest or gradient boosting regression algorithms for these two algorithms 
 feature scaling is not necessary.

step 4: 
 Random forest and gradient booting algorithms are not influenced by the outliers hence final model is selected as one of these two.
 
step 5: 
  Among all regression models Gradient Boosting has higer effiency of 93.98 % hence this model is used to find the powers in test data set.
 
