# Example MLflow project
```
export MLFLOW_TRACKING_URI="http://localhost:5000"
mlflow run --experiment-name="example" git@github.com:/tbenst/mlflow-example.git  -P alpha=0.5 -P l1_ratio=0.1
```
