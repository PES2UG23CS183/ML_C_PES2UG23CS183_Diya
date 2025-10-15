Smart Grid Energy Forecasting using Neural Architecture Search (NAS)

Overview

This project applies Optuna-based Neural Architecture Search (NAS) to optimize deep learning models — LSTM, CNN, and Transformer — for smart grid energy forecasting.
The goal is to accurately predict household electricity consumption and solar PV generation, enabling better demand–supply management in smart grids.

Team

Developed by: Diya D Bhat, Dhanya Prabhu

Project Description

This work explores the use of automated hyperparameter optimization to improve time series forecasting models for energy data.
Using Optuna’s multi-objective search and pareto frontal analysis, the system identifies efficient neural architectures balancing model accuracy and training efficiency. An ensemble approach is implemented to combine the best-performing LSTM, CNN, and Transformer models for robust prediction.

Dataset

The dataset used in this project is “Household Load and Solar Generation” from Kaggle.
It contains minute-level measurements of grid import/export and PV generation from residential smart meters.
Due to its large size, the dataset is not hosted directly in this repository.
Access it here:
https://www.kaggle.com/datasets/mexwell/household-load-and-solar-generation
