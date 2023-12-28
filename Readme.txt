# Natrual Gas Demand Forecasting with Causality Analysis

This repository hosts the Python code and datasets created for my Master's thesis, dedicated to exploring non-linear causality within German natural gas demand and other influencing factors, employing LSTM, GRU, and other neural network methodologies. The approach encompasses a spectrum from machine learning techniques to statistical testing.

The foundational functions employed in this analysis were sourced from the Nonlincausality repository at https://github.com/mrosol/Nonlincausality, which have been adapted and applied to examine natural gas demand data.

## Repository Structure

- `Causality test.ipynb`: Notebook detailing the granger causality test and self-coded non-linear granger causality test using Prophet, LSTM. It also scatter plots of the data to visualise the relationship between the dependent variable and predictors. 
- `Done_ngd_fc_LSTM.ipynb`: Notebook with implementation of the LSTM model for forecasting natural gas demand with multiple explanatory variables.
- `Done_ngd_fc_Prophet.ipynb`: Notebook with the application of Facebook's Prophet model for time-series forecasting natural gas demand with multiple explanatory variables.
- `Done_ngd_fc_svm.ipynb`: Support Vector Machine model applied to forecasting natural gas demand with multiple explanatory variables.
- `down_load_hdd.ipynb`: Script for downloading and processing the latest heating degree day data from the DWD FTP server. 
- `mutualinformation.ipynb`: Calculation and analysis of mutual information and correlations in the dataset.
- `Stationary_test.ipynb`: Implementation of statistical tests to check the stationarity of the time-series data and transfer the data using first difference, logarithm and seasonal decomposition.
- `average_hdd_data.csv`: Dataset containing average HDD data.
- `daily_NGD.csv`: Historical daily NGD (German Natural Gas Demands) and explanatory variables dataset.
- `seasonal_decom_stationary_daily_NGD.csv`: Dataset with seasonal decomposition and stationarity applied to daily NGD data.
- `stationary_daily_NGD.csv`: Processed dataset with stationarity enforced on daily NGD data.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages: pandas, numpy, matplotlib, scikit-learn, statsmodels, seaborn, tensorflow, prophet
