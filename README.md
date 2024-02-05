# DeepaSijoyKochery_Lab5_Python-for-DS
Machine Learning Model with flask to predict selling price of car
Objective:
1.To Build a Machine Learning Model to predict the price of used cars based on different input factors like fuel_type,kms_driven,type_of_transmission
2.Deploy the machine learning model with help of flask framework.

Dataset info:-### Dataset Information:
#### Dataset Source: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=CAR+DETAILS+FROM+CAR+DEKHO.csv
This dataset contains information about used cars listed on www.cardekho.com
- Car_Name: Name of the car
- Year: Year of Purchase
- Selling Price (target): Selling price of the car in lakhs
- Present Price: Present price of the car in lakhs
- Kms_Driven: kilometers driven
- Fuel_Type: Petrol/diesel/CNG
- Seller_Type: Dealer or Indiviual
- Transmission: Manual or Automatic
- Owner: first, second or third owner


  Steps in EDA and Feature Engineering:-
  1)Loaded data set,checked basic info of the data set
  2) Checked for duplicate records and redundant column for analysis dropped (Car_Name)
  3)Extracted Age of car from year column and dropped year.
  4)Encoded the categorical variable of which Fuel_type,Seller_Type and Transmission manually encoded
  
  Training and Model Evaluation
  1)Separated the dependent feature Selling_Price from the rest of data set
  2)Split data into Train and test
  3)Built a Random Forest Regressor Model and checked R2 score-The goal is to predict a continuos numeric output.Each tree in the forest will predict an output and average will be taken
  4)Model built and pickled

  Using Pycharm to create a basic app to predict the sellipng price.

  

