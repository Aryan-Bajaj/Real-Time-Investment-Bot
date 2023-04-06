# Investment Game

Investment Game is a fun and interactive game that uses a Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) algorithm to predict the stock prices of different companies listed on the National Stock Exchange (NSE) and Bombay Stock Exchange (BSE) in India.

## Table of Contents
- [Built With](#built-with)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Game Stages](#game-stages)
- [Algorithm](#algorithm)
- [Data](#data)
- [Disclaimer](#disclaimer)
- [Feedback](#feedback)
- [Installation](#installation)
- [Contribution](#contribution)
- [Author](#author)
- [License](#license)

## Built With
This game is built using several libraries such as:

- [numpy](https://numpy.org/doc/): A library for numerical computing in Python.
- [pandas](https://pandas.pydata.org/docs/): A Python library used for data manipulation and analysis.
- [scikit-learn](https://scikit-learn.org/stable/): A machine learning library in Python used for classification, regression, clustering, and dimensionality reduction.
- [keras](https://keras.io/): A high-level neural networks API in Python.
- [tensorflow](https://www.tensorflow.org/): An open-source platform for machine learning.
- [matplotlib](https://matplotlib.org/): A data visualization library for creating static, animated, and interactive visualizations in Python.
- [seaborn](https://seaborn.pydata.org/): A Python library used for creating informative and attractive statistical graphics.
- [yfinance](https://pypi.org/project/yfinance/): A library for obtaining financial data from Yahoo Finance.
- datetime: A Python module for working with dates and times.
- warnings: A module for issuing warning messages to users.

## Prerequisites
Before you can play this game, you will need to have Python 3.x installed on your computer. You will also need to install the required dependencies.

## Getting Started
To get started with this game, you will need to download or clone this repository to your local machine. Once you have done that, navigate to the project directory and install the required dependencies. 

## Installation
To install the required dependencies, you can use pip by running the following command:

```
pip install numpy pandas scikit-learn keras tensorflow matplotlib seaborn yfinance
```

After installing the dependencies, you can run the game by executing the `investment_game.py` script from a Python IDE or terminal.

## Usage
To play the game, simply follow the on-screen instructions. The game is divided into five stages. In each stage, you will be given Rs. 1000 to invest in one of two companies from a specific sector. Your investment decision and the predicted stock prices of the chosen companies will then be processed using the RNN-LSTM algorithm to calculate your earnings.

After each investment decision, your earnings will be displayed, along with the predicted stock prices for the next day.

## Game Stages
1. Stage 1: Private Bank Sector - Axis Bank Limited and IndusInd Bank Limited
2. Stage 2: Technology Sector - Saksoft Ltd. and Wipro Limited
3. Stage 3: Pharmaceutical Sector - Dr. Reddy's Laboratories Ltd. and Divis Laboratories Ltd.
4. Stage 4: Automobile Sector - Eicher Motors Limited and Tata Motors Limited
5. Stage 5: Textile Sector - Dhunseri Investments Ltd. and Apollo Finvest (India) Limited

## Algorithm
This game uses a Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) algorithm to predict stock prices. The RNN-LSTM algorithm is a type of neural network that is well-suited for time series data such as stock prices because it can remember previous inputs and use them to make predictions.

In this game, the RNN-LSTM algorithm is trained on historical stock data to learn patterns and relationships between stock prices and other factors such as market trends and news events. The algorithm then uses this knowledge to make predictions about future stock prices.

## Data
This game uses real-time stock data extracted from the NSE/BSE website using the yfinance library. The data is processed and fed into the RNN-LSTM algorithm to make predictions about future stock prices.

## Disclaimer
At the end of the game, you will be asked to provide feedback and given a disclaimer that the game is based on real-time data extracted from the NSE/BSE website and that the predictions may not reflect actual market trends.

## Feedback
Your feedback is important to us! At the end of the game, you will be asked to provide feedback on your experience playing the game. Your feedback will be used to improve the game and make it more fun and engaging for future players.

## Contribution
If you would like to contribute to this project, please feel free to submit a pull request or open an issue.

## Author
**Aryan Bajaj**

## License
This project is licensed under the MIT license.
