# Test command

```
cd <PROJECT_DIR>
export MLFLOW_TRACKING_URI=databricks
mlflow run . -b databricks --backend-config cluster-spec.json --experiment-id <experiment-id> -P script_name=train.py -P model_name=model123
```
