#  Forecasting the M5 dataset using machine learning

An end-to-end tutorial on using a global forecasting model (i.e., LightGBM) on a retail sales dataset (the M5 competition) using multi-step recursive forecasting. 

This tutorial emulates a batch forecasting workflow, breaking the process into multiple steps:

0. Obtain the raw data.
1. Create the base dataset containing sales, price, promos etc. by product id
 and date.
2. Create a feature engineering pipeline, create the training data, and store
the pipeline and training data.
3. Train the model and store it.
4. Create a forecast using recursive forecasting.
5. Plot the forecast, feature importance, and other model diagnostics.

For more on feature engineering for time series forecasting check out this [course](https://www.courses.trainindata.com/p/feature-engineering-for-forecasting). 

# Installation

This tutorial requires:
- numpy
- pandas
- scikit-learn
- joblib
- matplotlib
- sktime
- jupyter
- pyarrow 
- lightgbm

These can be installed by from the `requirements.txt`. 

```Python
pip install -r requirements.txt
```

The notebooks were run on Python 3.10.2. 
