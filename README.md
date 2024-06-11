# Forecasting Stock Market Prices

It is a **Time Series** dataset.A time series is simply a series of data points ordered in time.In a time series, time is often the independent variable and the goal is usually to make a forecast for the future. 

## PROBLEM STATEMENT: 

Our Aim  is to create a model that can forecast the future stock price based on the model training and provided dataset.

### Data
We will be using a [Huge stock market dataset](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs) from the Kaggle platform which has a very good collection of datasets.The file we will be using is present in following directory in the dataset zip file input\Data\Stocks\gs.us.txt
  
The data is presented in CSV format as follows : Date, Open, High, Low, Close, Volume, OpenInt.

Features:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume
  - OpenInt
  
Note that prices have been adjusted for dividends and splits.

### LICENSE OF DATASET : [LICENSE](https://creativecommons.org/publicdomain/zero/1.0/)

### Requirements

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, or [Google colab](https://colab.google/) which already has the above packages and more included. 

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [statsmodels](https://www.statsmodels.org/stable/)

### Run

In a terminal or command window, navigate to the top-level project directory `STOCK MARKET FORECASTING/` (that contains this README) and run one of the following commands:


ipython notebook Forecasting_Stock_Market_Prices_task.ipynb

or

jupyter notebook Forecasting_Stock_Market_Prices_task.ipynb


This will open the Jupyter Notebook software and project file in your browser.

### Steps :
1. Importing Libraries
2. Exploring the Dataset
3. Exploratory Data Analysis
> * Univariate Analysis
4. Data Preprocessing
5. Model Building
> * AUTOREGRESSIVE MODEL
> * MOVING AVERAGE MODEL
6. Evaluation
> * MEAN SQUARE ERROR
> * MEAN ABSOLUTE ERROR
> * ROOT MEAN SQUARE ERROR
7. Conclusion



### See Analysis image 
Exploratory Data Analysis (EDA):
![ex](https://github.com/Azad2181/Stock-forecasting-project/assets/121395998/b7442441-2ed5-46fa-932e-a9c6e194425d)

### Moving Average Model:
![mam1](https://github.com/Azad2181/Stock-forecasting-project/assets/121395998/5e849c2c-5d82-462c-bd8e-3fb4c4482cde)
![mam2](https://github.com/Azad2181/Stock-forecasting-project/assets/121395998/8b269f8b-e956-4802-8303-c8f196d9d8a5)
