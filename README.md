# Bitcoin Price Prediction

## Overview

This project implements a machine learning model to predict Bitcoin prices using historical data. The model leverages advanced techniques to analyze and forecast future price trends, providing valuable insights for traders and analysts.

## Features

- **Data Collection** -> utilizes historical Bitcoin price data for training the model
- **Modeling Techniques** -> implements machine learning algorithms to predict future prices
- **Visualization** -> provides graphical representations of predicted vs actual prices
- **User Interface** -> includes an interactive interface for users to input parameters and view predictions.

## Project Structure

- `binance_data.csv`: Dataset containing historical Bitcoin price data from Binance.
- `bitcoin_fin.csv`: Additional financial data related to Bitcoin.
- `index.html`: Frontend interface for user interaction.
- `README.md`: Documentation for the project.

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `keras`
- `tensorflow`

You can install the necessary dependencies using pip:

```bash
pip install -r requirements.txt

Setup and Usage

    Clone the Repository:
git clone https://github.com/FabioNotaro2001/BitcoinPricePrediction.git
cd BitcoinPricePrediction
Prepare the Data:

Ensure that the binance_data.csv and bitcoin_fin.csv files are placed in the project directory.

Train the Model:

Run the training script to build and train the model:
python train_model.py

Run the Application:

Launch the application to start making predictions:
python app.py

    Access the Interface:

    Open your web browser and navigate to http://localhost:5000 to interact with the application.

License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    The project utilizes data from Binance and other financial sources.

    Machine learning models are built using Keras and TensorFlow frameworks.

    Special thanks to the open-source community for their invaluable contributions.
