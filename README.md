# CNR Wind Energy Production Forecasting Challenge

Welcome to the CNR Wind Energy Production Forecasting Challenge! This project marks my first foray into the fascinating world of data science and machine learning. It is about predicting wind energy production for CNR, a leading French producer of exclusive renewable energy sources including water, wind, and solar power. Additionally, CNR is responsible for managing the Rhône River for hydroelectric power generation, river navigation, and agricultural irrigation.

## Project Overview

CNR currently operates approximately 50 wind farms (WF) with a total installed capacity of over 600 megawatts (MW). Each day, CNR sells its wind energy production on the energy market for the following day. To ensure accurate energy sales and compliance with legal obligations toward the French Transmission System Operator (TSO) responsible for maintaining the electrical grid's stability, CNR must forecast how much energy their wind farms will produce the next day.

The primary goal of this challenge is to predict the energy production of six specific wind farms owned by CNR. Each wind farm's production will be predicted individually, using meteorological forecasts as input data. The forecasts will focus on energy production in advance, specifically providing hourly production forecasts from Day D+1 00:00 to Day D+2 00:00.

## Contents of This Repository

- `data/`: This directory contains the dataset provided for the challenge, including historical energy production and meteorological data for the six specified wind farms.

- `notebooks/`: This directory contains Jupyter notebooks with my analysis, data preprocessing, and machine learning model development.

- `src/`: This directory houses any source code or scripts that are essential for the project.

- `requirements.txt`: A list of Python dependencies and their versions for easy replication of the project environment.

## Data Sources

To make accurate predictions, we will be using historical data of wind farm energy production and meteorological information. The data was generously provided by CNR, and it forms the basis of our forecasting efforts.

Atys Panier