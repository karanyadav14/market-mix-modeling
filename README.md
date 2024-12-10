# market-mix-modeling


### Setup Environment
1. Create python virtual environment and create jupyter kernel 
```
ENV_NAME=myenv && python3 -m venv $ENV_NAME && source $ENV_NAME/bin/activate && pip install ipykernel && python -m ipykernel install --user --name=$ENV_NAME
```
1. Install requried python libraries
```
pip install -r requirements.txt
```


### Get data
1. Download data from [here](!https://docs.google.com/spreadsheets/d/1WVHqUKVesxWKX8o1Yhr1oRQnxmZbIdSO10QHb65YXQI/edit?gid=1297295324#gid=1297295324).


### Tools used
- pymc_marketing
- statsmodels
- pandas
- numpy
- matplotlib
- seaborn