# Onion Price Prediction and Forecasting

![Onion Price Prediction]((https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.hindustantimes.com%2Findia-news%2Fat-70-kg-onion-prices-rage-in-delhi-ncr-upsurge-likely-till-december-101698468288532.html&psig=AOvVaw2bApbuoXBgV0i56mphpTPd&ust=1733106365321000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMC4jMrChYoDFQAAAAAdAAAAABAE)

## Problem Statement
The volatility in onion prices poses a significant challenge to market stability and economic planning in India. Factors such as unpredictable weather, supply-demand imbalance, and limited storage facilities contribute to sudden price fluctuations, impacting both farmers and consumers.

## Objective
This project aims to predict and forecast onion prices using a hybrid approach that combines:
- **Traditional Machine Learning Models** for classification into price categories: Low, Mid, High.
- **Deep Learning (LSTM)** for time-series forecasting to capture temporal patterns and long-term trends.

## Methodology
1. **Data Collection**: Web-scraped daily onion price data from 2012 to 2024 using Agmarknet.
2. **Data Analysis**: Pre-processed the dataset by handling missing values, categorizing prices, and identifying seasonal trends.
3. **Algorithm Implementation**:
   - Machine Learning Models: KNN, Naïve Bayes, Decision Tree, SVM, Neural Network.
   - Deep Learning Model: LSTM for sequential forecasting.
4. **Evaluation**: Models evaluated on metrics like accuracy, precision, recall, and MSE.

## Key Features
- Categorizes onion prices into three ranges: Low, Mid, and High.
- Implements LSTM to effectively capture long-term dependencies in price trends.
- Utilizes both classification and forecasting techniques to provide actionable insights.

## Results
- **Traditional Models**: KNN (60.96%), Decision Tree (86.35%), SVM (84.32%), Neural Network (80.27%).
- **LSTM Model**: Outperformed traditional methods with 88.20% accuracy.

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/onion-price-forecasting.git
   ```
