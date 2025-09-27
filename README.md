# House Price Prediction 🏡

This project predicts house prices using the **Kaggle House Prices Dataset**.

## Project Structure
house-price-prediction/
├── data/ # contains the training data CSV
├── notebooks/ # Jupyter notebook
├── requirements.txt # Python libraries needed
└── README.md # project overview

## Models Used
- Linear Regression
- Random Forest
- XGBoost

## Results
| Model              | RMSE       |
|--------------------|-----------|
| Linear Regression  | 677,542   |
| Random Forest      | 29,794    |
| XGBoost            | 26,741    |

XGBoost performed the best with the lowest RMSE.

## How to Run
1. Clone this repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3.Open the notebook:
jupyter notebook notebooks/house_price_prediction.ipynb
