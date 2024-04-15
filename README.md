# dl-chest-cancer-classification

### Dagshub

Bash:
```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/NutBodyslam053/dl-chest-cancer-classification.mlflow
export MLFLOW_TRACKING_USERNAME=NutBodyslam053
export MLFLOW_TRACKING_PASSWORD=b85bafd69d98861fee89f5bf70dc5f62cf41c2e5
```

Windows:
```bash
set MLFLOW_TRACKING_URI=https://dagshub.com/NutBodyslam053/dl-chest-cancer-classification.mlflow
set MLFLOW_TRACKING_USERNAME=NutBodyslam053
set MLFLOW_TRACKING_PASSWORD=b85bafd69d98861fee89f5bf70dc5f62cf41c2e5
```

### DVC

```bash
dvc init
dvc repro
dvc dag
```

### Github Secret

```bash
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION = demo>> us-east-1
AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com
ECR_REPOSITORY_NAME = 
```