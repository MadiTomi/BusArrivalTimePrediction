# 🚍 Bus Arrival Time Prediction with Machine Learning

## 📌 Project Overview
This project aims to predict bus arrival times using various machine learning models, including Random Forest, XGBoost, and LSTM. The goal is to minimize prediction errors and improve the accuracy of estimated arrival times, contributing to a more efficient public transportation system.

## 📊 Dataset
- The dataset contains historical bus arrival times, congestion levels, and timestamps.
- Data was preprocessed to handle missing values and extract meaningful time-based features.

## ⚙️ Models Implemented
1. **Random Forest** - A tree-based ensemble learning method.
2. **XGBoost** - A gradient boosting algorithm optimized for speed and performance.
3. **LSTM (Long Short-Term Memory)** - A deep learning model specialized in time-series forecasting.

## 📈 Visualizations
### 1️⃣ Histogram of Bus Arrival Times
- **Description:** Displays the distribution of bus arrivals at different hours of the day.
- **Insights:** Peak arrival times are observed around 14:00, with lower frequencies during early morning and late-night hours.

### 2️⃣ Pairplot of Arrival Hour vs. Congestion Level
- **Description:** Shows relationships between arrival hour and congestion levels.
- **Insights:** Peak congestion corresponds to rush hours, affecting bus arrival times.

### 3️⃣ RMSE Comparison Heatmap
- **Description:** Compares the Root Mean Squared Error (RMSE) of different models.
- **Insights:** LSTM achieves the lowest RMSE (13.00), outperforming Random Forest (58.59) and XGBoost (59.58).

## Results
- **Best Model:** LSTM achieved the best performance with the lowest RMSE.
- **Key Findings:** Deep learning models significantly improve prediction accuracy for time-series data.

## 🛠 Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, TensorFlow/Keras (for LSTM)

## Future Improvements
- Collect more real-time data to enhance model generalization.
- Implement transformer-based models for improved accuracy.
- Deploy as an API for real-time predictions.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

