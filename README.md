# 🔮 Time Series Forecasting with State Space Model and LSTM

## 📌 Objective
Implement and compare two neural models for time series forecasting:
- A custom **State Space Model (SSM)** using matrix operations
- A standard **LSTM** model using PyTorch

## 📈 Dataset
- **Daily Minimum Temperatures in Melbourne (1981–1990)**
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Daily+Minimum+Temperatures+in+Melbourne)

## 🛠️ Tools & Libraries
- Python, PyTorch, NumPy, Pandas
- Matplotlib for visualization

## 🧠 Model Architectures
### 🔹 State Space Model
- Learnable parameters: A, B, C, D matrices
- Simulates a simplified dynamic system

### 🔹 LSTM
- Single-layer LSTM with a Linear decoder
- Suitable for sequential temporal patterns

## 🔍 Evaluation Metrics
- RMSE (Root Mean Square Error)
- MAE (Mean Absolute Error)

## 📊 Results

| Model | RMSE | MAE |
|-------|------|-----|
| LSTM  | 2.18 | 1.72 |
| SSM   | 2.25 | 1.76 |

