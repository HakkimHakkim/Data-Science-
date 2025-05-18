📈 Stock Price Prediction using LSTM with Multi-Feature Time Series Data
This project demonstrates how to use LSTM (Long Short-Term Memory) neural networks to predict stock closing prices using historical market data and technical/economic indicators.

📁 Dataset
The dataset (stock_data.csv) includes:

Historical market data: Open, High, Low, Close, Volume

Technical indicators: RSI, MACD, Bollinger Upper, Bollinger Lower

Economic indicators: GDP Growth, Inflation Rate

Sentiment analysis score: Sentiment_Score

🚀 Project Features
🧹 Data Cleaning

🔢 Feature Scaling with MinMaxScaler (or StandardScaler)

🔗 Time Series Sequence Generation

🧠 LSTM Neural Network Model using TensorFlow/Keras

📊 Performance Visualization (Predicted vs Real Prices)

📦 Exportable predictions via CSV

📌 Project Structure
bash
Copy
Edit
📁 stock-price-prediction-lstm/
│
├── stock_data.csv                  # Dataset file
├── stock_price_prediction_lstm_full_features.ipynb  # Main Colab notebook
├── README.md                       # Project documentation
└── requirements.txt                # Required packages
🛠️ How to Run (in Google Colab)
Open the notebook in Google Colab

Upload stock_data.csv when prompted

Run all cells to:

Preprocess the data

Train the model

Visualize predictions

Export results

🧪 Requirements
Install using:

bash
Copy
Edit
pip install pandas numpy matplotlib scikit-learn tensorflow
📤 Export Predictions
The notebook includes code to:

Save predicted vs real prices to predicted_stock_prices.csv

Download file directly within Colab

📷 Sample Output

📚 Model Architecture
LSTM (64 units, return sequences)

LSTM (32 units)

Dense (1 output)

💡 Notes
Sequence length is configurable (default = 60)

You can switch to StandardScaler if your model/data benefits from standardization

📜 License
This project is open-source under the MIT License.

Ownership:
HAKKIM NAJIR











