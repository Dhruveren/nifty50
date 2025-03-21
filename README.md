# NIFTY 50 Stock Market Prediction Model

## Overview

This project uses historical data from the NIFTY 50 index (`^NSEI`) to predict whether the index will rise or fall on the next trading day. It employs a Random Forest Classifier from `scikit-learn` with basic and derived features, such as rolling averages and trends. The code is written in Python within a Jupyter Notebook environment and includes data fetching, preprocessing, model training, backtesting, and evaluation.

The current date in the dataset extends to **March 21, 2025**, and the model is saved for potential reuse.

---

## Prerequisites

To run this project, ensure you have the following installed:
- **Python 3.13** (or compatible version)
- **Jupyter Notebook** or **JupyterLab**
- Required Python libraries (installed via `pip`):
  - `yfinance` (for fetching stock data)
  - `pandas` (for data manipulation)
  
---

## Setup

1. **Clone or Download the Project**
   - Download the Jupyter Notebook file (e.g., `nifty50_prediction.ipynb`) and associated files (if any).

2. **Install Dependencies**
   - Open a terminal and run:
     ```bash
     pip install yfinance pandas numpy scikit-learn joblib
