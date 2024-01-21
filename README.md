# Time Series Analysis Project

## Project Overview

This project involves conducting a time series analysis of crude oil price changes over a given period and making predictions about the future based on historical data. The analysis utilizes Long Short-Term Memory (LSTM) models for deep learning on extended historical data.

## Table of Contents

- [Project Overview](#project-overview)
- [Approach](#approach)
- [Project Workflow](#project-workflow)
  1. [Data Acquisition](#1-data-acquisition)
  2. [Data Processing](#2-data-processing)
  3. [Prediction](#3-prediction)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Approach

The project is structured into three main sections:

1. **Data Acquisition:** Gathering the necessary data from the source.
2. **Data Processing:** Filtering and preparing the data for analysis.
3. **Prediction:** Utilizing LSTM models to make future predictions based on the analyzed historical data.

## Project Workflow

### 1. Data Acquisition

I gather data from the website 'https://www.eia.gov/' by utilizing an API key. The data is obtained from the 'Petroleum > Prices > Spot Prices' section.

### 2. Data Processing

The data is filtered and columns are renamed for better clarity. Standard scaling is applied to normalize the data. The time window is set, and training/testing data is separated.

### 3. Prediction

A LSTM model is created and trained using the prepared data. The model is used for predicting future values, and the results are visualized.

## Getting Started

To get started with this project, follow the steps below.

### Dependencies

- Pandas
- NumPy
- Matplotlib
- TensorFlow (for LSTM models)
- Scikit-Learn (for data scaling)
