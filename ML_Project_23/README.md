# **Smart Grid Energy Forecasting using Neural Architecture Search (NAS)**

## **Overview**

This project applies Optuna-based Neural Architecture Search (NAS) to optimize deep learning models — LSTM, CNN, and Transformer for smart grid energy forecasting.
The goal is to accurately predict household electricity consumption and solar PV generation, enabling better demand–supply management in smart grids.

## **Team**

Developed by: Diya D Bhat, Dhanya Prabhu

## **Project Description**

This work explores the use of automated hyperparameter optimization to improve time series forecasting models for energy data.
Using Optuna’s multi-objective search and pareto frontal analysis, the system identifies efficient neural architectures balancing model accuracy and training efficiency. An ensemble approach is implemented to combine the best-performing LSTM, CNN, and Transformer models for robust prediction.

Additionally, a Hyperband optimization approach is implemented for comparative analysis of tuning efficiency and model performance.

## **Dataset**

The dataset used in this project is “Household Load and Solar Generation” from Kaggle.
It contains minute-level measurements of grid import/export and PV generation from residential smart meters.
Due to its large size, the dataset is not hosted directly in this repository. We used household_data_15min_raw.csv as our dataset in this project.
Access it here:
https://www.kaggle.com/datasets/mexwell/household-load-and-solar-generation

## **Running the Project**

**Step 1:** Clone the repository and install dependencies

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt

**Step 2:** Prepare the dataset

If you have clean data (e.g., household_data_15min_clean.csv), place it in the project folder.
If using raw data, run the preprocessing cells in the notebook to clean and format it.

**Step 3:** Run the notebooks

Open Optuna NAS.ipynb to train and evaluate models (LSTM, CNN, Transformer) using Optuna.
Run Hyperband approach.ipynb for comparison of optimization methods.

**Step 4:** View Results

Trained models and scalers are saved in /models/.
Evaluation metrics, Pareto front plots, and ensemble results will be displayed automatically.
