# End-to-End-Chest-Cancer-Classification-using-MLflow-DVC
Deep Learning project
Workflows
Update config.yaml
Update secrets.yaml [Optional]
Update params.yaml
Update the entity
Update the configuration manager in src config
Update the components
Update the pipeline
Update the main.py
Update the dvc.yaml


import dagshub
dagshub.init(repo_owner='ravivarmanr26', repo_name='End-to-End-Chest-Cancer-Classification-using-MLflow-DVC', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)