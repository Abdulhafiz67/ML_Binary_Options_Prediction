# Predicting Binary Options Time Series Outcome with Machine Learning.
This project is my first step to creating a trading robot that uses a Gradient boosting classifier to not only make predictions about a trade but to also execute the trade on live data. 
This model is tested against past data with the currency pair being USD/CAD. The symbols can be easily changed for generalization.

## About the data
   - The csv files were extracted from Dukascopy.
   - The forex that we try to predict here is USD/CAD.
   - All datetime indexes are in GMT.
   
## Installation
To run this project, you'll need the following enviroments and libraries:

   - Python 3.X
   - Jupyter Notebook
   - Numpy
   - Pandas
   - Scipy
   - Sklearn
   - Matplotlib

## Backtest example for USD/CAD 
This example uses sample data from December 2021. 95% of the data is used for training and the remaining 5% for testing. 
Green and red vertical lines represent winning trade and losing trade respectively.
![image](https://user-images.githubusercontent.com/43554997/117063697-6a3e8280-ace2-11eb-8793-c2951a22d187.png)
