# mlflowbasicdemo


import dagshub
dagshub.init(repo_owner='raghav29061999', repo_name='mlflowbasicdemo', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)