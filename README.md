## ML FLow experiements

import dagshub
dagshub.init(repo_owner='pisethchum616', repo_name='mlflowexperiments', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)