# Volatility LSTM Alerts

High-precision LSTM-based alert system for short-term market volatility forecasting.

### Key Results
- 67.8% binary precision for detecting ±2.5% moves over 2 days  
- 76.9% precision on directional rises  
- Backtested expected return: 1.21% per trade  

### Overview
Short-term directional prediction is difficult (<53% accuracy initially). This project reframes the task as detecting significant volatility events (±2.5% over 2 days) — a more actionable goal for risk management. An LSTM model with threshold optimization prioritizes high-confidence signals, delivering practical trading value.

### Tech Stack
- Python (TensorFlow/Keras, Pandas, NumPy, scikit-learn)  
- Time-series preprocessing & feature engineering  
- Threshold optimization & backtesting  

### Files
- dalas-project.ipynb → full analysis & training  
- report.pdf → complete report
