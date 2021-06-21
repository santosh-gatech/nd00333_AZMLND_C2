# Machine Learning Operations

The goal of this project is to effectively configure a cloud-based machine learning production model, deploy it, and consume it using Azure ML Studio and SDK (pipelines).

The dataset is related to direct marketing campaigns of a banking institution. The task is to predict if the individual will subscribe to the bank service (bank term deposit). It's a classification task.

We first use Azure studio to create best model using Auto ML. After that, the best model is deployed. We then enable logging and application insights. Swagger documentation is also implemented. The deployed model endpoint is successfully tested.

The similar process is then followed using pipelines.

## Architectural Diagram

![plot](./starter_files/Architecture_Diagram.png)

## How to improve the project in future

I would like to try different deep learning architecures to see the difference in accuracy. Also, I would like to focus on the different data augmentation techniques to improve accuracy.      

## Key Steps

### Step 1 - Authentication (skipped)

### Step 2 - Automated ML Experiment

1) Registered Dataset (Bank-marketing)

![plot](./starter_files/Capture1_dataset.PNG)

2) AutoML Experiment successfuly completed 

![plot](./starter_files/Step_2_Capture_2_automl_completed.PNG)

3) Best performing model is Voting Ensemble 

![plot](./starter_files/Step_2_Capture_3_automl_best_model.PNG)

4) Details of the best model 

![plot](./starter_files/Step_2_Capture_4_automl_best_model_details.PNG)

### Step 3 - Best Model Deployed 

![plot](./starter_files/Step_3_Capture_1_deploy_automl.PNG)

### Step 4 - Enable logging and Application Insights

1) Enable Application Insights

![plot](./starter_files/Step_3_Capture_2_deploy_automl_app_insight.PNG)

2) Enable logging

![plot](./starter_files/Step_3_Capture_3_deploy_automl_logs.PNG)

### Step 5 - Swagger Documentation

It makes it easy to see the details of the endpoint.

1)

![plot](./starter_files/Step_5_Capture_1_swagger.PNG)

2) 

![plot](./starter_files/Step_5_Capture_2_swagger.PNG)

3)

![plot](./starter_files/Step_5_Capture_3_swagger.PNG)

4)

![plot](./starter_files/Step_5_Capture_4_swagger.PNG)

### Step 6 - Consume Model Endpoints 

Here we can observe the ouput

![plot](./starter_files/Step_6_Capture_1_endpoint.PNG)

### Step 7 - Create, Publish and Consume a Pipeline

1) Pipeline has been created

![plot](./starter_files/Step_7_Capture_2_pipeline_endpoint.PNG)

2) Pipeline Endpoint

![plot](./starter_files/Step_7_Capture_3_pipeline_endpoint_completed.PNG)

3) Bank marketing dataset with AutoML module

![plot](./starter_files/Step_7_Capture_4_sdk_automl_completed.PNG)

4) Published Pipeine overview showing a REST endpoint and status ACTIVE

![plot](./starter_files/Step_7_Capture_5_sdk_pipeline_endpoint_active.PNG)

5) RunDetails widget

![plot](./starter_files/Step_7_Capture_7_status.PNG)

6) ML Studio

![plot](./starter_files/Step_8_Capture_1.PNG)

## Screen Recording

Video url: https://youtu.be/SN8rV-0b8Xg

