# Agriculture Price Prediction (Python + ML)

Forecast crop prices using historical data and machine learning, enabling smarter decisions for farmers and market players.

<p align="center">
  <img src="images/price_plot.png" alt="Predicted vs Actual Prices" width="60%" />
</p>

---

##  Project Overview
This project uses historical agricultural data (e.g., prices, weather patterns, supply indicators) to predict future commodity prices. Built in **2023** by **Gunapu Bhargava**, it showcases practical application of time-series forecasting with machine learning.

---

##  Key Highlights
- **Data-driven forecasting** using regression and ensemble models
- **Accurate results** — (e.g., MSE, RMSE, MAE metrics)
- **Visual reports** — interactive plots showing trend predictions
- **Clear structure** — modular code for data loading, feature engineering, model training, and evaluation
- **Easy to extend** — integrate additional datasets or improve model architecture

---

##  Methodology

1. **Data Collection & Preprocessing**  
   - Load price and auxiliary data (like weather, yield)
   - Handle missing values, outlier detection, normalization

2. **Feature Engineering**  
   - Time-based features (lag, rolling averages)
   - Macro / seasonal indicators

3. **Model Training**  
   - Try regression models: *Linear Regression*, *Random Forest*, *XGBoost*
   - Use cross-validation to evaluate performance

4. **Evaluation & Visualization**  
   - Compute MAE, RMSE, MAPE  
   - Visualize predictions vs. actuals

5. **Prediction Interface**  
   - Simple script (`predict.py`) to forecast future prices using saved model

---

##  Usage Instructions

```bash
# Clone the repo
git clone https://github.com/Bhargav1026/Agriculture-Price-Prediction.git
cd Agriculture-Price-Prediction

# Install dependencies
pip install -r requirements.txt
Run the pipeline:

bash
Copy code
python train_model.py      # Generate and evaluate model
python predict.py          # Make forecasts with saved model
Preview of Results
Metric	Value
MAE	4.23
RMSE	5.67
MAPE	8.5%

(Edit these with your actual numbers.)

Visualization below illustrates how well the model tracks actual price movements:


Future Enhancements
Try LSTM or ARIMA for advanced time series modeling

Add external features like rainfall, yield, market demand

Deploy as a web app with interactive charts (e.g., using Dash or Streamlit)

Build an automated model retraining pipeline with new data

Why This Project Stands Out
Real-world applicability in agriculture economics

Solid combination of ML modeling and visualization

Excellent for portfolios targeting data science, forecasting, or agriculture tech roles

License & Author
MIT License © 2023 Gunapu Bhargava
