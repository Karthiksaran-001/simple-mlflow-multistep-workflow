# simple-mlflow-multistep-workflow

### create and  activate environment 
```
sh init_pro.sh
```

### export environment file
```
conda env export > conda.yml
```
### simple workflow execution without new conda env
```
mlflow run . --no-conda
```
### simple workflow execution without new conda env with parameters
```
mlflow run . -P param=value --no-conda
```
## want to run prediction pipeline 
```
mlflow run . -P training=0 --no-conda
```