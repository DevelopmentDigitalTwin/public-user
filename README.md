# Visual Machine Learning Modeling Project (MVP)

This project solves your ML model building problems efficiently!

## Getting Started
1. type url:

   http://74.248.112.32:9165/   

2. Register:

   ![Register Page](/images/register.gif "user register")

3. Login

    ![Login Page](/images/login.gif "user login")

## Upload Training Data
##### MVP Limitation:
         - just could use CSV files as datasource
4. Upload training  CSV files:
##### MVP Limitation:
         - just could upload atmost 10MB CSV files

   ![Upload File Page](/images/train-file-slim.gif "upload train csv file")

6. Make training datasets:

    ![Dataset Page](/images/train-dataset.gif "create train dataset")

## Build and run ML Models:

6. Make modeling pipeline:
##### MVP Limitation:
      - all input and output columns must be numerical
      - one transformer and one model must be added to pipeline
      - just could use imputation (dropna) as transformer
      - just could use linear regression (xgboost) as model
      - other modeling settins such as column types, scaling methods, evaluation metrics and tuning parameters are set by defaut values
        
   ![Model Pipeline Page](/images/model-build-slim.gif "train linear regression model")

8. upload prediction csv file:
##### MVP Limitation:
         - just could upload atmost 10MB CSV files
   
   ![Upload File Page](/images/predict-file-slim.gif "upload prediction csv file")

10. create prediction dataset

     ![Dataset Page](/images/predict-dataset.gif "create prediction dataset")

11. wait for training model be completed

     ![Model Pipeline Status](/images/model-status.gif "model training status on server")

12. map training model with prediction dataset        

    ![Model Schedule Page](/images/model-scheduling-slim.gif "schedule prediction")

 
## Visualize predicted data 

11. download predicted values
##### MVP Limitation:
         - just could add (download) predicted values as CSV file to datasources
    
   ![Add New File](/images/predicted-download.gif "download predicted values as e new data source")

13. Make new dataset from prediction and predicted files:

     ![Dataset Page](/images/predicted-dataset.gif "create dataset of prediction and predicted values")

15. Make dashboard from prediction and predicted dataset:

    ![Dashboard Page](/images/login.gif "create dashboard of predicted values")
    

   


























