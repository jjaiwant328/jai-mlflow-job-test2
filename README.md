# Test command

```
cd <PROJECT_DIR>
export MLFLOW_TRACKING_URI=databricks
mlflow run . -b databricks --backend-config cluster-spec.json\
 -P script_name=train.py -P model_name=model123\
 --experiment-id <experiment-id>
```
