# Final-Assignment-Project
This project is my final assignment for college graduation.

Initial prblem :
Environment issue regarding amount of trash volume in D.I Yogyakarta

Note :
This is time series problem so need to give more attention in data preprocessing

Purpose : 
Make a machine learning model using SVR algorithm
Calculate the prediction of trash volume for the next 6 months

Step :
1. Colecting the Data
   The data that used in this project is provided by Dinas Lingkungan Hidup dan Kehutanan Provinsi DIY
   /n The data is clean but need to transform into CSV
   /n The amount of data is pretty small, total 54 data only but still continue to proceed

2. Preprocessing the Data
   Transform the data into CSV files
   Do feature engineering, choosing the feature that will be used in this project (3 months prior to predict 1 month after)
   Data splitting, 80:20 ratio for training and testing
   Data standarization using standard scaler

3. Create the model
   Tune parameter using GridSearch
   Train the model using training set

5. Evaluating the model
   Do evaluation and testing using testing set
   calculate the performance using R square and MAPE
   choose the best performance

6. Do prediction
   using the last 3 months for predicting the next month
   repeat it until 6 times for 6 months
   
