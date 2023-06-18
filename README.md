# Multivariate Time Series Analysis for Commodity Futures Prices
This repository contains an LSTM module meant to forecast crude oil futures prices using 5 features:
1) Open
2) Close
3) Low
4) High
5) Volume

Modern tools like GPT-3.5, GitHub Copilot, and BlackBox AI were employed in building the model, albeit cautiously.

The results are summarized in the code(notebook) file `model.ipynb` in the form of accuracy metrics and graphs. Feel free to have a look. I tried to comment the code as much as I can. See if you can write these comments and get the same GitHub Copilot output.

The data for the crude oil prices was obtained from [Investing.com](https://www.investing.com/commodities/crude-oil-historical-data) and is contained in `data/oil_data_uncleaned.csv`.
The original data was cleaned and augmented by the model to produce relevant features, contained in `new_train.csv` and `new_test.csv`, also in the `data` folder.

## References
- https://www.investing.com/commodities/crude-oil
- https://www.kaggle.com/code/ryanholbrook/time-series-as-features
- https://medium.com/@vinayarun/from-scratch-an-lstm-model-to-predict-commodity-prices-179e12445c5a
- https://github.com/OrestisMk/OrestisMk-Multivariate-forecast-with-VAR-SVR-RNN-LSTM/blob/main/RNN-LSTM(2%20models).ipynb
- Vancsura L, Tatay T, Bareith T. Evaluating the Effectiveness of Modern Forecasting Models in Predicting Commodity Futures Prices in Volatile Economic Times. Risks. 2023; 11(2):27. https://doi.org/10.3390/risks11020027
