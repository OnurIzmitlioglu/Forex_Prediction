# Performance Comparison of ANN(Artificial Neural Network) and SVM(Support Vector Machine) on Forex Prediction

This project is mainly built on to compare the two well-known Machine Learning algorithms which are ANN and SVM on predicting the future foreign exchange ranges. This project is written in Python language and Jupyter Notebook environment.

## Installation

To be able to run the .ipynb files, first download the Jupyter Notebook from Anaconda or the 
```pip``` command. [Link for the website](https://jupyter.org/install)

After successfully installing Jupyter notebook, the third party library [Alpha Vantage API](https://www.alphavantage.co) is used to obtain the real-time data for the foreign exchange rates. To be able to add the library to the notebook environment, use:

```bash
pip install alpha_vantage
```

See the Alpha Vantage website for more details.

You are all ready to go.

## Usage

There are some parameters in the MLPRegressor and svm libraries effecting the cross validation errors being calculated in the testing phase, the parameters which are being used are:

#### MLPRegressor
```Hidden Layer Size: Determines the size of the hidden layer, note that the number of hidden layers is set to 1 by default.```

```Alpha Value: Used to evaluate the bias-variance tradeoff as a regularization term.```

#### svm
```Epsilon Value```

```Cost Value```

## Contributing
Pull requests are always welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
