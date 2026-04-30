# CA 24: Theory Assignment 1

## Student Details
- **Name:** Waqar Ahmed  
- **Roll No:** 25MCA053  
- **Assignment Topic:** Multi-Output Time-series Forecasting Using LSTM

---
## Project Description

This project implements a **time series forecasting model using Long Short-Term Memory (LSTM)** networks to predict all features of the data based on historical data.
The model takes a sequence of past features values as input and predicts future values, enabling trend analysis and forecasting.

---

## Features

- Time series forecasting using LSTM
- Data preprocessing and normalization
- Sliding window sequence generation
- Training and testing split
- Visualization of predicted vs actual features values

---

## Tech Stack

- Python
- Pytorch
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## Dataset

- Historical stock price data (CSV format)
- Typical features used:
  - Prev Close
  - Open
  - High
  - Low
  - Last
  - Close
  - VWAP
  - Volume
  - Turnover
  - Trades
  - Deliverable Volume/percent Deliverble
---

## Model Architecture

The model follows a sequential deep learning architecture:

- Input Layer (time step sequences)
- LSTM Layer(s) for capturing temporal dependencies
- Dense Layer for output prediction
