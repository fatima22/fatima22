

## Data 
- Hourly data were collected from LFE (http://www.forstliche-umweltkontrolle-bb.de/r3_meteo.php) and DWD (https://www.dwd.de/EN/climate_environment/cdc/cdc_node.html)
   
- Preproessed data are saved in’lfe_UTC.db’.
- Each lfestation is sarownded by two or more than two dwd stations. Check the metadata or read the paper, which dwd stations delong to which LFE station. 


## Models
- Install SHAP (https://github.com/slundberg/shap/blob/master/notebooks/overviews/An%20introduction%20to%20explainable%20AI%20with%20Shapley%20values.ipynb)

- Each script (RF_regression.py’, ‘Mlregression.py’, ‘XGB_regression.py’ ‘SVM_regression.py’) analyses performance of one model with tunning the hyperparameters.
- in ‘XGB_regression .py’, the XGBoost model run and SHAP and resambling method were applied.
