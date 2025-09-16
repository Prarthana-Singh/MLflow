# MLflow



# For Dagshub

import dagshub
dagshub.init(repo_owner='ps3493049', repo_name='MLflow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


$env:MLFLOW_TRACKING_URI = "https://dagshub.com/ps3493049/MLflow.mlflow"
$env:MLFLOW_TRACKING_USERNAME = "ps3493049"
$env:MLFLOW_TRACKING_PASSWORD = "91d3ccb73742c58a9cba320dad3f1f8cb8c63fc9"
