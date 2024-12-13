# Prediction-of-Product-Sales
Author: Huda J. AbuZayed
## Project Overview
This project is a sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.
Download the data using this link: [download the data] (https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view). (Note: [Original data source](https://www.analyticsvidhya.com/datahack/contest/practice-problem-big-mart-sales-iii/)).

 ### Data Dictionary 
![download (1)](https://github.com/user-attachments/assets/117ed04b-5018-484a-b008-2414c0d0b716)
### This project was built with these steps: 
- Load and Inspect Data
- Clean Data
- Exploratory Data Analysis
- Feature Inspection
- Preparing data for Machine Learning
- Preprocesing for Machine Learning
- Modeling for sales prediction project
- Evaluation
- Overall Recommendation



 #### Correlation Heatmap
 ![download (2)](https://github.com/user-attachments/assets/b513a960-f127-4a1b-8e2e-d05b02d5bd04)

 #### Exploratory Data Analysis
 ![download (4)](https://github.com/user-attachments/assets/e33dd1d5-276c-4274-b93a-8b5718df11ef)
![download (5)](https://github.com/user-attachments/assets/b07d0ed0-35a3-4bb7-bde8-944754ab9595)
![download (6)](https://github.com/user-attachments/assets/38cedad9-1543-45d0-bac4-4429a07ad029)



 #### Item_MRP and Item_Outlet_Sales
 ![download (3)](https://github.com/user-attachments/assets/7d47b62e-c66d-444a-88a9-8f55113833a4)

 ## Models:
- Linear Regression Model
- Random Forest Regressor Model
- Tuned Random Forest Regressor Model

  ## Which model do I recommend?
  After I evaluated the three models to predict the sales, I found that the Tuned Random Forest Regressor Model was the best modle with the following regression
  metrics:

  
  Regression Metrics: Training Data
------------------------------------------------------------
- MAE = 653.463
- MSE = 868,222.343
- RMSE = 931.784
- R^2 = 0.707

------------------------------------------------------------
Regression Metrics: Test Data
------------------------------------------------------------
- MAE = 734.382
- MSE = 1,118,329.337
- RMSE = 1,057.511
- R^2 = 0.595

If I choose this model to make a prediction of the sales, there will be an average error = 734.382$ which may be acceptable depending on the market and the product.


