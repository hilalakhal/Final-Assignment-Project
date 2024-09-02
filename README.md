# Final-Assignment-Project
This project is my final assignment for college graduation.

*Initial problem :*
Environment issue regarding amount of trash volume in D.I Yogyakarta

*Note :*
This is time series problem so need to give more attention in data preprocessing

**Purpose :** 
Make a machine learning model using SVR algorithm
Calculate the prediction of trash volume for the next 6 months

Step :
**1. Colecting the Data** <br />
   The data that used in this project is provided by Dinas Lingkungan Hidup dan Kehutanan Provinsi DIY <br />
   The data is clean but need to transform into CSV <br />
   The amount of data is pretty small, total 54 data only but still continue to proceed <br />

**2. Preprocessing the Data** <br />
   Transform the data into CSV files <br />
   Do feature engineering, choosing the feature that will be used in this project (3 months prior to predict 1 month after) <br />
   Data splitting, 80:20 ratio for training and testing <br />
   Data standarization using standard scaler <br />

**3. Create the model** <br />
   Tune parameter using GridSearch <br />
   Train the model using training set <br />

**4. Evaluating the model** <br />
   Do evaluation and testing using testing set <br />
   calculate the performance using R square and MAPE <br />
   choose the best performance <br />

**5. Do prediction** <br />
   using the last 3 months for predicting the next month <br />
   repeat it until 6 times for 6 months <br />
   
