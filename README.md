# Predictions of Solar Energy Production Using the LSTM Model with an Attention Mechanism

This repository contains the code and data for predicting solar energy production using a Long Short-Term Memory (LSTM) model enhanced with an attention mechanism. The goal of this project is to accurately forecast energy production for the upcoming week based on historical data.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Solar energy production is highly dependent on various factors such as weather conditions, time of the year, and geographical location. Accurate prediction of solar energy production can help in optimizing the use of renewable energy sources and in better planning of energy distribution.

This project employs a Long Short-Term Memory (LSTM) network with an attention mechanism to improve the accuracy of predictions. The attention mechanism helps the model to focus on relevant parts of the input sequence, which is crucial for time series forecasting.

## Dataset

The dataset used in this project consists of 10 years of solar energy production data. The columns in the dataset are:
- `date`: The date of the recorded data
- `from`: The starting time of the energy production record
- `to`: The ending time of the energy production record
- `MW`: The amount of energy produced in megawatts

## Model Architecture

The model is built using an LSTM network with an attention mechanism. The architecture can be summarized as follows:
- LSTM layers to capture temporal dependencies
- Attention mechanism to focus on relevant parts of the input sequence
- Dense layers to produce the final output

## Installation

To run this project, you need to have Python and the following libraries installed:

- numpy
- pandas
- matplotlib
- tensorflow
- keras

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib tensorflow keras
```

## Usage

 1 - Clone the repository:

```bash
git clone https://github.com/MohamedAitHassoun/Predictions-of-solar-energy-production-using-the-LSTM-model-with-an-attention-mechanism.git
```

 2 - Navigate to the project directory:

```bash
cd Predictions_of_solar_energy_production_using_the_LSTM_model_with_an_attention_mechanism
```

 3 - Open the Jupyter Notebook:

```bash
jupyter notebook Predictions_of_solar_energy_production_using_the_LSTM_model_with_an_attention_mechanism.ipynb
```
 4 - Follow the instructions in the notebook to preprocess the data, train the model, and make predictions.

## Results

The model's performance is evaluated based on various metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The results show that the LSTM model with an attention mechanism provides more accurate predictions compared to a standard LSTM model.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

