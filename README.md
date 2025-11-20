# House Price Prediction with Scikit Learn, Streamlit and Deployed with Flask

## Overview

This project predicts house prices using a machine learning model trained on a tabular dataset.
The interface is built with Streamlit, and predictions can also be served through a Flask API.
The model uses XGBRegressor along with preprocessing using Numpy, Pandas, and Scikit-Learn.


## House Price Prediction with Scikit Learn, Numpy, Pandas, Streamlit and Deployed with Flask 

The Model was trained with Tabular House Prices Dataset and with the `XGBRegressor` Architecture. The Model predicts the Price of a given House, also the U.I. to select the parameters of the House was built with Streamlit and the API with Flask. 

## Run it Locally

Test it Locally by running the `app.py` file, built with `Streamlit`, and the `api.py` file with `Flask`. Remember first to run the `api.py` file, copy the http url and saved in the API variable of the `app.py` file, and uncomment the code lines.

## App made with Streamlit
Once the API is running, launch the Streamlit interface:
```sh
streamlit run app.py
```

## Deployed with Flask to run locally
```sh
python api.py
```



## Resources
- House Price Dataset: https://www.kaggle.com/datasets/shibumohapatra/house-price
