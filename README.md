# Machine Learning Engineer Nanodegree
### Predicting Boston Housing Prices
by Robert Latimer
April 14, 2017

### Description

The goal of this project is to apply basic machine learning concepts on Boston house pricing data to predict the selling price of a new home. We begin by exploring the data to obtain important features and descriptive statistics. Then, we split the data into training and testing sets and determine a suitable performance metric. We then analyze performance graphs for a learning algorithm with various parameters and training set sizes and choose a model that best generalizes for unseen data. Lastly, we test the optimal model on a new sample to see how accurately it can predict a selling price.

You can view the full detail of the project [here](boston_housing_predictions/boston_housing_rlatimer.ipynb).

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [iPython Notebook](http://ipython.org/notebook.html)

### Code

All orignal coding was completed in the `boston_housing_rlatimer.ipynb` iPython Notebook file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing_predictions/` (that contains this README) and run one of the following commands:

```ipython notebook boston_housing_rlatimer.ipynb```
```jupyter notebook boston_housing_rlatimer.ipynb```

This will open the iPython Notebook software and project file in your browser.

## Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php).

**Features**

1. `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town
**Target Variable** 4. `MEDV`: median value of owner-occupied homes
