# Brent Oil Price Prediction

This project analyzes the impact of political and economic events on Brent oil prices using time series models, machine learning, and econometric analysis. The tech stack includes Python (ARIMA, LSTM, VAR), Flask, React, and data visualization tools like Recharts and D3.js.

## Project Structure


```
├── checkpoints
│   ├── arima_model.pkl
│   ├── garch_model.pkl
│   └── random_forest_model.pkl
├── notebooks
│   ├── 1.0-data-preprocessing.ipynb
│   ├── 2.0-data-exploration.ipynb
│   ├── 3.0-model-training.ipynb
│   ├── 4.0-model-evaluation.ipynb
│   └── README.md
├── scripts
│   ├── __init__.py
│   ├── explore_data.py
│   ├── preprocess_data.py
│   ├── train_models.py
│   └── README.md
├── src
│   ├── __init__.py
│   └── README.md
├── tests
│  └── __init__.py
├── README.md
└── requirements.txt
```


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Naod-Demissie/Brent-Oil-Price-Prediction.git
   cd Brent-Oil-Price-Prediction
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv/Scripts/activate`
   pip install -r requirements.txt
   ```
