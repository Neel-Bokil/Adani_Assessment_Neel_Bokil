# Electricity Consumption Prediction

This project predicts hourly electricity consumption using time-based features extracted from start and end timestamps.

## Approach
- Converted timestamps to datetime format
- Engineered time-based features (hour, day, weekday, month, weekend)
- Used a time-aware train-test split to avoid data leakage
- Trained a Gradient Boosting Regressor for prediction
- Evaluated performance using MAE, RMSE, and R² score

## Results
- MAE: ~535 MWh  
- RMSE: ~750 MWh  
- R²: ~0.77  

## How to Run
```bash
pip install -r requirements.txt
python src/train.py
