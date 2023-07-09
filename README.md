# source_assignment_manola
data science assignment by Iris Manola for Source.ag

The code is run in python 3.7 in Jupyter Notebook.
The two required .csv files are included in the folder. You only have to change the path in the cell 5 and 6
(df_outd = pd.read_csv("/Users/irismanola/Documents/ML/Source_Assignment/Weather.csv")
and
df_ind = pd.read_csv("/Users/irismanola/Documents/ML/Source_Assignment/GreenhouseClimate.csv")).

If new data should be imported this path needs to be changed.

The steps followed in the assignement are the following:
1. Introduction
2. Exploration of Indoors temperature dataset
3. Stationarity Tests
4. Univariate Temperature forecasting using smoothing
5. Univariate Temperature forecasting using SARIMA Model
6. Multivariate Temperature forecasting using SARIMAX Model
7. Final Comparison of Models Using MSE

The accuracy of the smoothing models is evaluated with the MSE metric.
The accuracy of the SARIMA and SARIMAX models is evaluates with the MSE, RMSE, MAE and MAPE.
The accuracy of the 4 models is compared using the MSE metric.


Filenames:
The Source_Assignment_Manola.ipynb is the Jupyter Notebook python script.
The Source_Assignment_Manola.pdf is a copy of the notebook in a .pdf format.
