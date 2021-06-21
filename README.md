# Machine Learning Operations

The goal of this project is to effectively configure a cloud-based machine learning production model, deploy it, and consume it using Azure ML Studio and SDK (pipelines).

The dataset is related to direct marketing campaigns of a banking institution. The task is to predict if the individual will subscribe to the bank service (bank term deposit). It's a classification task.

We first use Azure studio to create best model using Auto ML. After that, the best model is deployed. We then enable logging and application insights. Swagger documentation is also implemented. The deployed model endpoint is successfully tested.

The similar process is then followed using pipelines.

## Architectural Diagram

![plot](./starter_files/Architecture_Diagram.png)

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



## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
