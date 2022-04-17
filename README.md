# CryptoOfTheFuture

This project will implement a deep learning reinforcement algorithm — proximal policy optimization — to devise an automatically generating strategy for Ethereum transactions. Long short-term memory is used to make predictions for next day closing prices, which will in turn be used to construct the automatic policy. The completed stages of the project are as follows:

1. Extracted hourly Ethereum price data from Binance API beginning on August 21, 2017 through February 17, 2021
2. Preprocessed data using MinMaxScaler
3. Defined the LSTM model using TensorFlow. Generate train, validation, and test sets for the model.
4. Trained the model.
6. Visualized the actual and predicted prices in plt graph
7. Visualized the MSE loss of the training and testing sets in plt graph

## Dependencies

* **json + requests**: To fetch data from Binance API
* **sklearn**: For data preprocessing and train-test split
* **TensorFlow**: Machine Learning Library
* **Matplotlib**: For plotting loss and prediction graphs

## Getting Started:

### Requires Git, CUDA, Python 3.7–3.10, and pip >= 19.0

1. Clone this repo: `$ git clone https://github.com/arkokoley/CryptoOfTheFuture.git`
2. [Install Jupyter](https://jupyter.org/install)
3. Install Dependencies: `$ pip install -U matplotlib scikit-learn tensorflow`
4. Start the Project Jupyter notebook: `$ jupyter notebook CryptoOfTheFuture/Project.ipynb`

## Contibutors

Ariel Lee, Gaurav Koley, Rahul Razdan
